<script>
	export let size = '24';
	export let color = 'currentColor';
</script>

<svg
	xmlns="http://www.w3.org/2000/svg"
	viewBox="0 0 512 512"
	{...$$restProps}
	width={size}
	height={size}
	fill={color}
	class={$$props.class}
	><rect x="128" y="64" width="256" height="32" /><rect
		x="96"
		y="112"
		width="320"
		height="32"
	/><path d="M464,448H48V160H464Z" /></svg
>
