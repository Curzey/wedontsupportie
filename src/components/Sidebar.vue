<template>
	<article id="sidebar">
		<header class="section-header">
			<h5>Wedontsupportie</h5>	
		</header>
		
	</article>
</template>

<script>
export default {
	/*data() {
		categories: {
			"Javascript",
			"CSS"
		}
	}*/
}
</script>

<style lang="scss" scoped>

	#sidebar {
		padding: var(--box-padding);
		grid-area: sidebar;
		min-width: 25rem;
		background: var(--background);
		color: var(--primary-text);
		border-right: 2px solid var(--background-lighter);
	}

</style>
