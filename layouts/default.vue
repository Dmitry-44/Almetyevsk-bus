<template>
	<div>
		<Header />
		<main>
			<div class="container-app">
				<Nuxt />
			</div>
		</main>
		<footer>
			<span>&copy; {{ new Date().getFullYear() }}</span>
		</footer>
	</div>
</template>

<script>

	export default {
		name: "Default layout",
	}
</script>

<style scoped>
	.container-app{
		margin-top: 60px
	}
</style>