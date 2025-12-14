<script lang="ts">
    let n = $state(0);
</script>

<button onclick={()=>{n++}}>{n}</button>

<style>
    button {background-color: red;}
</style>