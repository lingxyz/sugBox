<template>
	<div>
		<p class="card">
			{{text}}
		</p>
	</div>
</template>

<script>
export default {
	props: ['text']
}
</script>

<style lang="stylus" scoped>
.card
	padding: 10px
</style>
