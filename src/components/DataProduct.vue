<template>
  <div class="data-product">
    <div class="data-product-description">
      <p class="data-product-description__name text text-title text-black">Пижама для девочек</p>
      <p class="data-product-description__number text text-transparent text-gray">Арт. 02765/46</p>
      <p class="data-product-description__feedback text text-normal text-black">Отзывы ***** 14 отзывов ></p>
    </div>
    <div class="data-product-price">
      <p class="data-product-price__current text text-uppercase text-black">
        800 ₽ <span class="data-product-price__full text-normal text-gray">1 500 ₽</span> >
      </p>
      <div class="data-product-price-discount">
        <p class="data-product-price-discount__first text text-transparent text-black discount-box">скидка -36%</p>
        <p class="data-product-price-discount__second text text-transparent text-black discount-box">скидка -20%</p>
      </div>
    </div>
    <div class="data-product-size">
      <select class="data-product-size-choice text text-normal text-black">
        <option selected value="size-choice ">Выбрать размер</option>
        <option value="L">L</option>
        <option value="XL">XL</option>
        <option value="XXL">XXL</option>
      </select>
      <a href="#" class="data-product-size-choice__link text text-normal text-black">Определить размер</a>
    </div>
    <div class="data-product-count">
      <div class="data-product-count-inner">
        <input type="number" class="data-product-count-product">
        <button class="data-product-count__btn-add text text-normal text-white">Добавить в корзину</button>
        <button class="data-product-count__count-favorite"><img src="../../public/icons/favorite-white.svg" alt="favorite" class="favorite"></button>
      </div>
      <a href="#" class="data-product-count__link text text-normal text-black">Купить в 1 клик</a>
    </div>
    <div class="data-product-menu">
      <ul class="data-product-menu-list">
        <li class="data-product-menu-list__item text text-normal text-black"><img src="../../public/icons/closes.svg" alt="closes" class="closes"> Описание товара</li>
        <li class="data-product-menu-list__item text text-normal text-black"><img src="../../public/icons/clock.svg" alt="clock" class="clock"> Доставка и возврат</li>
        <li class="data-product-menu-list__item text text-normal text-black"><img src="../../public/icons/pay.svg" alt="pay" class="pay"> Способы оплаты</li>
      </ul>
    </div>
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
.data-product-description {
  margin-bottom: 46px;
  padding-left: 20px;
}
.data-product-price {
  margin-bottom: 35px;
  padding-left: 20px;
}
.data-product-size {
  display: flex;
  flex-direction: column;
  width: 315px;
  margin-bottom: 40px;
  padding-left: 20px;
}
.data-product-count {
  border-bottom: 0.5px solid #C4C4C4;
  margin-bottom: 24px;
  height: 105px;
  padding-left: 20px;
}
.data-product-description__name {
  margin-bottom: 8px;
}
.data-product-description__number {
  margin-bottom: 18px;
}
.data-product-price__current {
  margin-bottom: 12px;
}
.data-product-price-discount {
  display: flex;
  width: 198px;
  height: 32px;
  justify-content: space-between;
}
.discount-box {
  width: 91px;
  height: 24px;
  text-align: center;
  border: 1px solid #333333;
  box-sizing: border-box;
}
.data-product-size-choice {
  height: 44px;
  margin-bottom: 12px;
}
.data-product-count-product {
  width: 145px;
  height: 44px;
  margin-right: 12px;
  border: 1px solid #C4C4C4;
  box-sizing: border-box;
  background: #F2F2F2;
  padding: 0;
}
.data-product-count__btn-add {
  width: 203px;
  height: 44px;
  margin-right: 4px;
  background: #333333;
  border: 1px solid #333333;
  box-sizing: border-box;

  padding: 0;
}
.data-product-count__count-favorite {
  width: 44px;
  height: 44px;
  background: #333333;
  border: 1px solid #333333;
  box-sizing: border-box;
}
.data-product-count-inner {
  display: flex;
  align-items: center;
  margin-bottom: 12px;
}
.favorite {
  margin: 0 auto;
}
.data-product-menu {
  padding-left: 20px;
}
.data-product-menu-list {
  padding: 0;
  list-style-type: none;
}
.data-product-menu-list__item {
  display: flex;
  margin-right: 6px;
  margin-bottom: 12px;
}
</style>