<script>
	import Secondary from "./secondary.svelte";
	let count = 10;

	let box = {
		x: 5,
		y: 10
	};
	
</script>


<button on:click={() => count++}>+</button>
<Secondary {count} {...box} />
