
<script lang="ts">
    let count = 0;
</script>

<h1>Counter : {count}</h1>
<button on:click={()=> count++}>+</button>
<button on:click={()=> count--}>-</button>
<button on:click={()=> count--}>Multiply</button>