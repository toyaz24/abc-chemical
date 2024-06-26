<template>
      <div id="carouselExampl"  style="background-color: #eeeced;" class="carousel slide pt-4" data-bs-ride="carousel" data-bs-wrap="false">
  <ol class="carousel-indicators">
    <li data-bs-target="#carousel-footer" data-bs-slide-to="0" class="active"><span class="visually-hidden">Slide 1</span></li>
    <li data-bs-target="#carousel-footer" data-bs-slide-to="1"><span class="visually-hidden">Slide 2</span></li>
    <li data-bs-target="#carousel-footer" data-bs-slide-to="2"><span class="visually-hidden">Slide 3</span></li>
  </ol>
  <div class="carousel-inner container" style="padding: 50px; border-top: 1px solid #E2E2E2;">
    <div class="carousel-item active">
      <div class="d-flex">
        <img class="carousel-img" :src="require('@/assets/companyFourLogo.png')" alt="First slide">
        <img class="carousel-img" :src="require('@/assets/companySixLogo.png')" alt="Second slide">
        <img class="carousel-img" :src="require('@/assets/bannerOne.jpg')" alt="Third slide">
        <img class="carousel-img" :src="require('@/assets/companyFourLogo.png')" alt="Fourth slide">
        <img class="carousel-img" :src="require('@/assets/companySixLogo.png')" alt="Fifth slide">
        <img class="carousel-img" :src="require('@/assets/bannerOne.jpg')" alt="Sixth slide">
        <img class="carousel-img" :src="require('@/assets/companyFourLogo.png')" alt="Seventh slide">
      </div>
    </div>
    <div class="carousel-item">
      <div class="d-flex">
        <img class="carousel-img" :src="require('@/assets/companyFourLogo.png')" alt="Eighth slide">
        <img class="carousel-img" :src="require('@/assets/companySixLogo.png')" alt="Ninth slide">
        <img class="carousel-img" :src="require('@/assets/bannerOne.jpg')" alt="Tenth slide">
        <img class="carousel-img" :src="require('@/assets/companyFourLogo.png')" alt="Eleventh slide">
        <img class="carousel-img" :src="require('@/assets/companySixLogo.png')" alt="Twelfth slide">
        <img class="carousel-img" :src="require('@/assets/bannerOne.jpg')" alt="Thirteenth slide">
        <img class="carousel-img" :src="require('@/assets/companySixLogo.png')" alt="Fourteenth slide">
      </div>
    </div>
  </div>
  <a class="carousel-control-prev" href="#carousel-footer" role="button" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
  </a>
  <a class="carousel-control-next" href="#carousel-footer" role="button" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
  </a>
</div>
</template>
<script>
    export default{
        name:"carouselFooterComponent"
    }

</script>
<style>
    .carousel-item {
  display: flex;
  justify-content: center;
  align-items: center;
}

.carousel-img {
  width: 129px;
  height: 70px;
  object-fit: cover;
  margin-right: 40px;
}

.carousel-control-prev,
.carousel-control-next {
  width: 5%;
}

.carousel-indicators {
  position: absolute;
  bottom: -30px;
}

.carousel-indicators li {
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background-color: #000;
}

.carousel-indicators .active {
  background-color: #fff;
}

</style>
