<template>
  <div class="photo-product">
    <div class="photo-product-slide">
      <img src="../../public/picture/pajamas-1.jpg" alt="pajamas" class="photo-product-slide__items">
      <img src="../../public/picture/pajamas-2.jpg" alt="pajamas" class="photo-product-slide__items">
      <img src="../../public/picture/pajamas-3.jpg" alt="pajamas" class="photo-product-slide__items">
      <img src="../../public/picture/pajamas-4.jpg" alt="pajamas" class="photo-product-slide__items">
      <img src="../../public/picture/pajamas-5.jpg" alt="pajamas" class="photo-product-slide__items">
    </div>
  </div>
</template>

<script>
export default {
  name: "PhotoProduct"
}

</script>

<style scoped>
.photo-product {
  width: 686px;
  height: 880px;
  background-image: url("../../public/picture/pajamas-1.jpg");
  background-repeat: no-repeat;
  background-size: 100%;
}
.photo-product-slide {
  margin: 24px 0 0 26px;
}
.photo-product-slide__items {
  width: 70px;
  height: 91px;
  margin-bottom: 7px;
}
</style>