<template>
  <div id="app">
    <HeaderSite />
    <div class="container">
      <div class="description-product">
        <PhotoProduct />
        <DataProduct />
      </div>
      <p class="link-all-style text text-black text-normal"><a>Посмотреть все стили</a></p>
      <GalleryPhoto />
      <FooterSite />
    </div>
  </div>
</template>

<script>

import HeaderSite from "@/components/HeaderSite";
import DataProduct from "@/components/DataProduct";
import PhotoProduct from "@/components/PhotoProduct";
import GalleryPhoto from "@/components/GalleryPhoto";
import FooterSite from "@/components/FooterSite";
export default {
  name: 'App',
  components: {
    HeaderSite,
    DataProduct,
    PhotoProduct,
    GalleryPhoto,
    FooterSite
  }
}
</script>

<style>
.container {
  width: 1390px;
  margin: 0 auto;
}
h1 {
  font-family: 'Open Sans', sans-serif;
}
.description-product {
  display: flex;
  justify-content: space-between;
  margin-bottom: 32px;
}
.text {
  font-family: 'Open Sans';
  font-style: normal;
}
.text-black {
  color: #333333;
}
.text-gray {
  color: #828282;
}
.text-white {
  color: #FFFFFF;
}
.text-title {
  font-weight: 600;
  font-size: 18px;
  line-height: 24px;
}
.text-transparent {
  font-weight: 400;
  font-size: 12px;
  line-height: 16px;
  letter-spacing: 0.04em;
}
.text-normal {
  font-weight: 400;
  font-size: 14px;
  line-height: 20px;
  letter-spacing: 0.04em;
}
.text-uppercase-bold {
  font-weight: 700;
  font-size: 24px;
  line-height: 24px;
  letter-spacing: 0.04em;
  text-transform: uppercase;
}
.text-uppercase-normal {
  font-weight: 400;
  font-size: 16px;
  line-height: 24px;
  letter-spacing: 0.04em;
  text-transform: uppercase;
}
.link-all-style {
  text-align: center;
  margin-bottom: 23px;
}
</style>
