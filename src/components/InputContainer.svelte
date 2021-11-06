<script>
    import Button from "./Button.svelte";
</script>


<div class="button-col-1">
    <Button action={"Fly"} />
</div>
<div class="button-col-2">
    <Button action={"Walk"} />
</div>
<div class="button-col-3">
    <Button action={"Swim"} />
</div>

<style>
    .button-col-1 {
        grid-column-start: 2;
        justify-self: center;
    }
    
    .button-col-2 {
        grid-column-start: 3;
        justify-self: center;
    }
    
    .button-col-3 {
        grid-column-start: 4;
        justify-self: center;
    }
</style>