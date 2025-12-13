<script lang="ts">
    let n = $state(0)
</script>

<h1>これはさらに別のページです</h1>
<p><a href="/">元のページに戻る</a></p>
<button onclick={()=>{n++}}>{n}</button>