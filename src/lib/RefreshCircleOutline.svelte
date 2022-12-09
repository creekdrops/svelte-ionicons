<script lang="ts">
	export let size: string | number = "24";
	export let strokeWidth: string | number = "28"
	export let color: string = "currentColor";
</script>

<svg
	xmlns="http://www.w3.org/2000/svg"
	viewBox="0 0 512 512"
	{...$$restProps}
	width={size}
	height={size}
	fill={color}
	class={$$props.class}
	><title>ionicons-v5-b</title><path
		d="M288,193s12.18-6-32-6a80,80,0,1,0,80,80"
		style="fill:none;stroke:{color};stroke-linecap:round;stroke-miterlimit:10;stroke-width:{strokeWidth}px"
	/><polyline
		points="256 149 296 189 256 229"
		style="fill:none;stroke:{color};stroke-linecap:round;stroke-linejoin:round;stroke-width:{strokeWidth}px"
	/><path
		d="M256,64C150,64,64,150,64,256s86,192,192,192,192-86,192-192S362,64,256,64Z"
		style="fill:none;stroke:{color};stroke-miterlimit:10;stroke-width:{strokeWidth}px"
	/></svg
>
