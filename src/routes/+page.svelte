<script>
	let innerHTML = 'Hello World';
	export let test = false;
</script>

<h1 bind:innerHTML={innerHTML} contenteditable="true" class:test={test} />
<h1 innerHTML={innerHTML} class:test={test}/>

<style>
	.test{
		display: none;
	}
</style>