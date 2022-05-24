<template>
  <div>
    <img src="https://i.artfile.ru/1920x1200_1411196_[www.ArtFile.ru].jpg" class="img-fluid" alt="Responsive image">
  </div>
  <div class="position-absolute top-50 start-50 translate-middle" style="font-size: 60px; color: white">
    <h1>Добро пожаловать</h1>
  </div>
</template>

<script>
export default {
  name: "MyHome"
}
</script>
<style>
img {
  position: absolute;
  filter: brightness(50%);
}
</style>