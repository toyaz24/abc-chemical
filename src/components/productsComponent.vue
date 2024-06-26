<template>
    <div class="pt-4 product-section ">
       
    <div class="d-flex container pt-4" style="flex-direction: column;">
        <div class="section-title"><h1 class="d-flex justify-content-start " style="color: white;">Products</h1></div>
      <div class="row">
        <div class="col-md-3 col-6 pb-4 pb-md-0">
          <div style="cursor: pointer;">
            <img class="w-100" :src="require('@/assets/pigment.jpg')" />
          </div>
        </div>
        <div class="col-md-3 col-6 pb-4 pb-md-0">
          <div style="cursor: pointer;">
            <img class="w-100" :src="require('@/assets/RESINS.jpg')" />
          </div>
        </div>
        <div class="col-md-3 col-6 pb-4 pb-md-0">
          <div style="cursor: pointer;">
            <img class="w-100" :src="require('@/assets/pigment.jpg')" />
          </div>
        </div>
        <div class="col-md-3 col-6  pb-4 pb-md-0">
          <div style="cursor: pointer;">
            <img class="w-100" :src="require('@/assets/RESINS.jpg')" />
          </div>
        </div>
      </div>
      <div class="row pt-5">
        <div class="col-md-6 col-12 pb-4 pb-md-0">
          <div>
            <img class="w-100" style="cursor: pointer;" :src="require('@/assets/Additive.jpg')" />
          </div>
        </div>
        <div class="col-md-6 col-12 pb-4 pb-md-0">
          <div>
            <img class="w-100" style="cursor: pointer;" :src="require('@/assets/resignraw.jpg')" />
          </div>
        </div>
      </div>
    </div>
</div>
  </template>
  
  <script>
  export default {
    name: "productsComponent"
  }
  </script>
  
  <style scoped>
  .product-section {
    background: url('../assets/productbg.jpg') 0 0 no-repeat;
    background-size: cover;
    padding: 80px 0;
  }
  
  .section-title h1 {

    font-size: 24px;
    line-height: 16px;
    color: #000000;
    font-weight: bold;
    text-transform: uppercase;
    margin: 0;
    margin-bottom: 50px;
    border-bottom: 1px solid #E2E2E2;
    padding-bottom: 20px;
    position: relative;
  }
  </style>
  
  