<script lang="ts">
    import Display from "./display/display.svelte";
    import Keyboard from "./keyboard/keyboard.svelte";    
</script>

<div class="columns">
    <div class="column is-half" style="min-height : 60vh;"><Display/></div>
    <div class="column" style="max-height : 100vh;"><Keyboard/></div>
</div>

<style>
    .columns {
        height: 100vh;
      }
</style>