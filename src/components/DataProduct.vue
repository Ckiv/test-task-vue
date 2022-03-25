<template>
  <div class="data-product">
    <div class="data-product-description">
      <p class="data-product-description__name">Пижама для девочек</p>
      <p class="data-product-description__number">Арт. 02765/46</p>
      <p class="data-product-description__feedback">Отзывы ***** 14 отзывов ></p>
    </div>
    <div class="data-product-price">
      <p class="data-product-price__discount">
        800 ₽ <span class="data-product-price__full">1 500 ₽</span> >
      </p>
    </div>
    <div class="data-product-size"></div>
    <div class="data-product-count"></div>
    <div class="data-product-menu"></div>
  </div>
</template>

<script>
export default {
  name: "DataProduct"
}
</script>

<style scoped>
.data-product {
  width: 686px;
  height: 880px;
}
</style>