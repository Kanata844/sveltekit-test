<script lang="ts">
    import RedButton from "$lib/RedButton.svelte";

    let n = $state(0)
</script>

<h1>これはさらに別のページです</h1>
<p><a href="/">元のページに戻る</a></p>
<button onclick={()=>{n++}}>{n}</button>
<RedButton/>

<style>
    button {background-color: blue;}
</style>