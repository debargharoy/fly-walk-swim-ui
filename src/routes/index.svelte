<script>
    import DisplayContainer from "../components/DisplayContainer.svelte";
    import InputContainer from "../components/InputContainer.svelte";
</script>

<div class="container">
    <div class="item data-container">
        <DisplayContainer />
    </div>
    <div class="item input-container">
        <InputContainer />
    </div>
</div>

<style>
    .container {
        display: grid;
        grid-template-rows: 1fr 1fr;
        row-gap: 2em;
    }

    .input-container {
        display: grid;
        grid-template-columns: repeat(5, 1fr);
        column-gap: 1em;
    }

    
    .data-container { 
        display: grid;
        grid-template-columns: repeat(3, 1fr)
    }
</style>