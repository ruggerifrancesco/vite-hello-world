<script>
import AppTitle from './AppTitle.vue';

    export default {
      components: {
        AppTitle
      },
      data() {
        return {
            imgHeader: {
              imgSrc: "https://tophinhanhdep.com/wp-content/uploads/2021/10/Neon-City-Wallpapers.jpg",
              imgAlt: "scenery",
            },
        }
      },
    }
</script>

<template>
    <header class="jumbotron">
        <img :src="imgHeader.imgSrc" :alt="imgHeader.imgAlt">
        <AppTitle />
    </header>
</template>

<style scoped>
  .jumbotron {
    width: 1200px;
    height: 550px;
    border-radius: 1rem;
    overflow: hidden;
    position: relative;
  }
  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: top;
  }
</style>