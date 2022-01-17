<template>
	<div>
		<Header />
		<main>
			<div class="container-app">
				<Nuxt />
			</div>
		</main>
		<footer class="footer">
			<div class="footerLeft"><p>Альметьевск</p><span>&copy; {{ new Date().getFullYear() }}</span></div>
			<div class="footerRight">
				<div class="footerRight__number"><p><a href="tel:+ 79179029715">+7 917 902 97 15</a></p>
				</div>
				<div class="footerRight__icon"><span class="fa fa-whatsapp" aria-hidden="true"></span></div>
				<div class="footerRight__icon"><span class="fa fa-telegram" aria-hidden="true"></span></div>
				<div class="footerRight__icon"><span class="fa fa-phone" aria-hidden="true"></span></div>
			</div>
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
		margin-top: 60px;
		margin-bottom: 60px
	}

	.footer{
		position: fixed;
		bottom: 0;
		width: 100%;
		height: 60px;
		background-color: #fcfcfc;
		padding: 0px 30px;
		font-weight: 600;
		font-size: 12px;
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
		-webkit-box-pack: justify;
		-ms-flex-pack: justify;
		justify-content: space-between;
		-webkit-box-align: center;
		-ms-flex-align: center;
		align-items: center;
	}
</style>