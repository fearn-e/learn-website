<script>
	export let id = '';
	export let caption = '';
</script>

<div class="container">
	<iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay" title={caption} src={id} />

	<div class="caption">
		<p>{caption}</p>
	</div>
</div>

<style >
	.container {
		padding-top: 1em;
		padding-bottom: 1em;
	}

	.caption :global(p) {
		font-style: italic;
		text-align: center;
		width: 80%;
		margin: 0 auto;
		font-size: 0.8rem;
	}
</style>
