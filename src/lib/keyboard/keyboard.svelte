<script lang="ts">
    import AritmeticOperations from "./aritmetic_operations.svelte";
    import Keypad from "./keypad.svelte";
</script>

<div class="columns is-mobile is-vcentered">
    <div class="column is-four-fifths"><Keypad/></div>
    <div class="column"><AritmeticOperations/></div>
</div>
<style>
    .columns {
        overflow: auto;
    }
</style>