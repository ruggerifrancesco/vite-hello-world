<script>
    export default {
      data() {
        return {
            appTitle: 'La mia prima app con Vite!',
        }
      },
    }
</script>

<template>
    <h1 class="app-title">
        {{ appTitle }}
    </h1>
</template>

<style scoped>
    @import url('https://fonts.googleapis.com/css2?family=Tilt+Prism&display=swap');
    .app-title {
        font-family: 'Tilt Prism', cursive;
        font-size: 5rem;
        text-align: center;
        text-decoration: underline;
    }
</style>