<template>
	<header class="header">
		<div class="container">
			<div class="row row-head">
				<nav id="nav" class="nav navigation-enter">
					<ul class="menu">
						<li class="menu__item"><a class="menu-link" href="/">Главная</a></li>
						<li class="menu__item"><a class="menu-link" href="/route">Маршрут</a></li>
						<li class="menu__item"><a class="menu-link" href="/price">Тарифы</a></li>
						<li class="menu__item"><a class="menu-link" href="/contacts">Контакты</a></li>  
					</ul>
				</nav>
			</div>
		</div>
		<div class="menu__background__mobile menu-active">
			<div class="burger">
				<button id="burger__btn"><span></span></button>
			</div>
		</div>
    </header>
</template>

<script>
export default {

  name: 'Header',

  data(){
	  
  },

  methods:{
	  openMobileMenu(){
		  this
	  }
  }



}
</script>

<style scopped>
	.menu-link.active{
		color: #f39c12
	}
	button#burger__btn {
		background-color: inherit;
		width: 40px;
		height: 40px;
	}
</style>

<style scoped>
	header{
		position: relative;
		top: 0;
		left: 0;
		right: 0;
		height: 60px;
		background-color: #34495e;
	}
</style>