<template>
  <div class="">
  <HeaderComponent />
  <NavbarComponent/>
  <CarouselComponent :header=true></CarouselComponent>
  <PromotionalText/>
  <CarouselFooterComponent></CarouselFooterComponent>
  <productsComponent></productsComponent>

  
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue';
import NavbarComponent from './components/NavbarComponent.vue';
import  CarouselComponent from './components/CarouselComponent.vue';
import PromotionalText from "./components/promotionalText.vue"
import CarouselFooterComponent from "./components/carouselFooterComponent.vue";
import productsComponent from "./components/productsComponent.vue"


export default {
  name: 'App',
  components: {
    HeaderComponent,
    NavbarComponent,
    CarouselComponent,
    PromotionalText,
    CarouselFooterComponent,
    productsComponent
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
