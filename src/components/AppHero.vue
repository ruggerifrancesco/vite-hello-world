<script>
    export default {
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
    outline: 1px solid red;
  }
  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
</style>