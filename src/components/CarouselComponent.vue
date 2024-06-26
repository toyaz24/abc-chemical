<template>
  <div id="carouselExampleIndicators" class="carousel slide pt-4" data-bs-ride="carousel" v-if="header">
    <ol class="carousel-indicators">
      <li data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active"><span class="visually-hidden">Slide 1</span></li>
      <li data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"><span class="visually-hidden">Slide 2</span></li>
      <li data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"><span class="visually-hidden">Slide 3</span></li>
    </ol>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img class="d-block"
         :class="header ? 'd-block w-100' : 'd-block w-25'" 
          :src="header ? require('@/assets/bannerOne.jpg') : require('@/assets/companySixLogo.png')" 
          
         alt="First slide">
      </div>
      <div class="carousel-item">
        <img 
        :class="header ? 'd-block w-100' : 'd-block w-25'" 
          :src="header ? require('@/assets/banner.jpg') : require('@/assets/companyFourLogo.png')" 
        alt="Second slide">
      </div>
      <div class="carousel-item">
        <img 
        :class="header ? 'd-block w-100' : 'd-block w-25'" 
          :src="header ? require('@/assets/bannerOne.jpg') : require('@/assets/companySixLogo.png')"  
        alt="Third slide">
      </div>
    </div>
    <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
    </a>
  </div>


</template>

<script>
export default {
  props:['header'],
  name: 'CarouselComponent',
};
</script>

<style scoped>
.carousel-inner img {
  width: 100%;
  height: auto;
}

.carousel-indicators li {
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background-color: rgba(0, 0, 0, 0.5);
}

.carousel-indicators .active {
  background-color: white;
}

.carousel-control-prev-icon,
.carousel-control-next-icon {
  background-color: rgba(0, 0, 0, 0.5);
  padding: 10px;
  border-radius: 50%;
}
</style>
