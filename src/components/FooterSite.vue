<template>
<footer class="footer">
  <ul class="footer-menu text text-black text-normal" >
    <li class="footer-menu__item text-uppercase-normal">покупателям</li>
    <li class="footer-menu__item"><a href="#" class="footer-menu__item-link">Каталог</a></li>
    <li class="footer-menu__item"><a href="#" class="footer-menu__item-link">Акции</a></li>
    <li class="footer-menu__item"><a href="#" class="footer-menu__item-link">Бренды</a></li>
  </ul>
  <ul class="footer-menu text text-black text-normal">
    <li class="footer-menu__item text-uppercase-normal">о нас</li>
    <li class="footer-menu__item"><a href="#" class="footer-menu__item-link">О компании</a></li>
    <li class="footer-menu__item"><a href="#" class="footer-menu__item-link">Новости</a></li>
    <li class="footer-menu__item"><a href="#" class="footer-menu__item-link">Команда</a></li>
  </ul>
  <div class="follow-block">
    <p class="follow-block-text text text-black text-uppercase-normal">Узнайте первыми о новинках и акциях</p>
    <form class="follow-block-form" action="#" method="post">
      <input type="email" class="follow-block-form__email-input text text-black text-normal">
      <botton class="follow-block-form__btn text text-black text-normal" type="submit">Подписаться</botton>
    </form>
  </div>
</footer>
</template>

<script>
export default {
  name: "FooterSite"
}
</script>

<style scoped>
.footer {
  display: flex;
  justify-content: space-around;
  margin-bottom: 70px;
}
.footer-menu {
  list-style-type: none;
  padding: 0;
}
.footer-menu li:first-child {
  font-weight: 400;
  font-size: 16px;
  line-height: 24px;
  letter-spacing: 0.04em;
  text-transform: uppercase;
  margin-bottom: 16px;
}
.footer-menu li {
  margin-bottom: 8px;
}
.footer-menu__item-link {
  text-decoration: none;
  color: #333333;
}
.follow-block {
  width: 452px;
}
.follow-block-form {
  display: flex;
  flex-direction: column;
  align-items: end;
}
.follow-block-form__email-input {
  width: 100%;
  height: 32px;
  border: transparent;
  border-bottom: 1px solid #C4C4C4;
  margin-bottom: 35px;
}
.follow-block-text {
  margin-bottom: 45px;
}
.follow-block-form__btn {
  width: 150px;
  height: 36px;
  background: #FFFFFF;
  border: 1px solid #333333;
  box-sizing: border-box;
  text-align: center;
  line-height: 30px;
}
</style>