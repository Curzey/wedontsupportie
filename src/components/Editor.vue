<template>
	<article id="editor">
		<header class="section-header">
			<h5>Editor</h5>
		</header>
		
		<article class="editor__intro">
			<p>Welcome to <span class="wedontsupportie">wedontsupportie.</span> This is where you'll find snippets for all the great things you can do without IE11 in your life!</p>
		</article>

	</article>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

	#editor {
		grid-area: editor;
		background: var(--background-darker);
		padding: var(--box-padding);
		color: var(--primary-color);
		align-self: stretch;
	}

</style>
