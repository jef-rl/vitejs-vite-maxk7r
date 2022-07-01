<svelte:options tag="my-element" />

<script lang="ts">
	export let name = 'world';
</script>

<h1>Hello {name}!</h1>
<slot></slot>