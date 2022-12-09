<script lang="ts">
	import * as Icon from './index';

	type T = keyof typeof Icon;

	export let size: string | number | undefined = '24';
	export let strokeWidth: string | number | undefined = '32';
	export let color: string | undefined = 'currentColor';
	export let name: T = 'Accessibility';
</script>

<svelte:component this={Icon[name]} {size} {strokeWidth} {color} class={$$props.class} />
