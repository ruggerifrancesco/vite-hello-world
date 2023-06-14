<script>
import AppTitle from './AppTitle';

    export default {
      components: {
        AppTitle
      },
      data() {
        return {
            imgHeader: {
              imgSrc: "https://img.freepik.com/premium-photo/painting-mountain-landscape-with-river-foreground-mountain-background_864560-11.jpg",
              imgAlt: "scenery",
            },
        }
      },
    }
</script>

<template>
    <header class="jumbotron">
        <img :src="imgHeader.imgSrc" :alt="imgHeader.imgAlt">
    </header>
</template>

<style scoped>
  .jumbotron {
    width: 1200px;
    height: 550px;
    border-radius: 1rem;
    overflow: hidden;
  }
  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: top;
  }
</style>