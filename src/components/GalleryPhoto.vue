<template>
<div class="gallery">
  <img src="../../public/picture/gallery-1.jpg" alt="gallery image" class="gallery__img-1">
  <img src="../../public/picture/gallery-2.jpg" alt="gallery image" class="gallery__img-2">
  <img src="../../public/picture/gallery-3.jpg" alt="gallery image" class="gallery__img-3">
  <img src="../../public/picture/gallery-4.jpg" alt="gallery image" class="gallery__img-4">
  <img src="../../public/picture/gallery-5.jpg" alt="gallery image" class="gallery__img-5">
</div>
</template>

<script>
export default {
  name: "GalleryPhoto"
}
</script>

<style scoped>
.gallery {
  display: grid;
  grid-template-areas:
        "gallery__img-1 gallery__img-2 gallery__img-3"
        "gallery__img-1 gallery__img-4 gallery__img-5";
  grid-gap: 16px;
  margin-bottom: 142px;
}
.gallery__img-1 {
  grid-area: gallery__img-1;
}
.gallery__img-2 {
  grid-area: gallery__img-2;
}
.gallery__img-3 {
  grid-area: gallery__img-3;
}
.gallery__img-4 {
  grid-area: gallery__img-4;
}
.gallery__img-5 {
  grid-area: gallery__img-5;
}
</style>