<script>
	import { tick } from "svelte";


	export let foo;

	console.log({ foo });

	export const thisIs = 'readonly';

	export function greet(name) {
		alert(`hello ${name}`);
	}

    export let format = n => n.toFixed(2)
</script>

<style>
	/* style goes here */
</style>
