<script lang="ts">
	let testcounter = $state(0);
	function greet() {
		testcounter++;
		console.log("hi chrissa");
	}
</script>

<h1>Welcome to SvelteKit</h1>
<p>
	Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read
	the documentation
</p>
<button onclick={greet}>testing {testcounter} - count</button>

<style>
	button {
		background: green;
		color: white;
	}
</style>
