<template>
	<header class="header">
		<div class="container">
			<div class="row row-head">
				<nav id="nav" :class="['nav', isMobileMenuOpen ? 'navigation-enter-active' : 'navigation-enter' ]">
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
				<button id="burger__btn" :class="{'burger--open' : isMobileMenuOpen}" @click="toggleMobileMenu"><span></span></button>
			</div>
		</div>
    </header>
</template>

<script>
export default {

  name: 'Header',

  data(){
	  return {
		  isMobileMenuOpen: false
	  }
  },

  methods:{
	  toggleMobileMenu(){
		  this.isMobileMenuOpen=!this.isMobileMenuOpen
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
	.nav {
		transition: all .4s cubic-bezier(0.075, 0.82, 0.165, 1);
	}
</style>