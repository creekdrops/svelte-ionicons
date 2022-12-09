<script lang="ts">
	export let size: string | number = "24";
	export let strokeWidth: string | number = "36"
	export let color: string = "currentColor";
</script>

<svg
	id="icons"
	xmlns="http://www.w3.org/2000/svg"
	viewBox="0 0 512 512"
	{...$$restProps}
	width={size}
	height={size}
	fill={color}
	class={$$props.class}
	><path
		d="M208,352H144a96,96,0,0,1,0-192h64"
		fill="none"
		stroke={color}
		stroke-linecap="round"
		stroke-linejoin="round"
		stroke-width={strokeWidth}
	/><path
		d="M304,160h64a96,96,0,0,1,0,192H304"
		fill="none"
		stroke={color}
		stroke-linecap="round"
		stroke-linejoin="round"
		stroke-width={strokeWidth}
	/></svg
>
