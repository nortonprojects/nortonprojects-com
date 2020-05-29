<template>
  <div class="main-bg lg:h-screen lg:max-h-screen max-w-screen  max-h-full">
    <div class="container mx-auto h-full flex flex-col">
      <nuxt />
      <BottomBar/>
    </div>
  </div>
</template>


<script>
import BottomBar from '@/components/BottomBar.vue';

export default {
  layout: 'home',
  components: {
    BottomBar
  }
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
.main-bg {
  background-color: #38b2ac;
  background-image: url("~assets/topography.svg");
}
</style>
