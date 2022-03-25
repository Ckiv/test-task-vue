<template>
  <header class="header">
    <div class="container">
      <div class="header-inner">
        <img src="../../public/icons/logo.svg" alt="logo" class="logo">
        <ul class="header-inner-menu-list">
          <li class="header-inner-menu-list__item"><img src="../../public/icons/person.svg" alt="person" class="person"></li>
          <li class="header-inner-menu-list__item"><img src="../../public/icons/favorite.svg" alt="favorite" class="favorite"></li>
          <li class="header-inner-menu-list__item"><img src="../../public/icons/buy.svg" alt="buy" class="buy"></li>
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderSite"
}
</script>

<style scoped>
.header {
  width: 100%;
  height: 40px;
  margin-bottom: 24px;
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.1);
}
.header-inner {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
  height: 40px;
}
.header-inner-menu-list {
  display: flex;
  width: 168px;
  height: 24px;
  justify-content: space-between;
  list-style-type: none;
}
.logo {
  width: 67px;
  height: 16px;
}
</style>