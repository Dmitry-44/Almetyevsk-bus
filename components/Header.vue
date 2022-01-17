<template>
	<header class="header">
		<div class="container">
			<div class="row row-head">
				<nav id="nav" class="nav navigation-enter">
					<ul class="menu">
						<li class="menu__item"><NuxtLink class="menu-link"  to="/">Главная</NuxtLink></li>
						<li class="menu__item"><NuxtLink class="menu-link" activeClass="active" to="/route">Маршрут</NuxtLink></li>
						<li class="menu__item"><NuxtLink class="menu-link" activeClass="active" to="/price">Тарифы</NuxtLink></li>
						<li class="menu__item"><NuxtLink class="menu-link" activeClass="active" to="/contacts">Контакты</NuxtLink></li>  
					</ul>
				</nav>
			</div>
		</div>
		<div class="menu__background__mobile menu-active">
			<div class="burger">
				<a id="burger__btn" href="#"><span></span></a> 
			</div>
		</div>
		<nav id="mobile_nav" class="nav navigation-enter" v-if="mobileMenuIsOpen">
			<ul class="menu">
				<li class="menu__item"><NuxtLink class="menu-link"  to="/">Главная</NuxtLink></li>
				<li class="menu__item"><NuxtLink class="menu-link" activeClass="active" to="/route">Маршрут</NuxtLink></li>
				<li class="menu__item"><NuxtLink class="menu-link" activeClass="active" to="/price">Тарифы</NuxtLink></li>
				<li class="menu__item"><NuxtLink class="menu-link" activeClass="active" to="/contacts">Контакты</NuxtLink></li>  
			</ul>
		</nav>
    </header>
</template>

<script>
export default {

  name: 'Header',

  data(){ 
	  return {
		  mobileMenuIsOpen: false
	  }
  },

  methods:{
	  openMobileMenu(){
		  this.mobileMenuIsOpen = !this.mobileMenuIsOpen;
	  }
  }



}
</script>

<style scopped>
	.menu-link.active{
		color: #f39c12
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