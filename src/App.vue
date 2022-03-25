<template>
  <div id="app">
    <HeaderSite />
    <div class="container">
      <div class="description-product">
        <PhotoProduct />
        <DataProduct />
      </div>
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
}
</style>
