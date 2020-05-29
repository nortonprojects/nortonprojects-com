<template>
  <div class="lg:h-screen max-w-screen  max-h-screen">
    <div class="main-bg absolute top-0 left-0 h-screen w-screen"></div>
    <div class="container max-h-screen mx-auto h-full flex flex-col pt-8 justify-between">
      <TopBar class="fixed top-0 left-0"/>
      <nuxt />
      <BottomBar class="container"/>
    </div>
  </div>
</template>

<script>
import BottomBar from '@/components/BottomBar.vue';
import TopBar from '@/components/TopBar.vue';

export default {
  layout: 'home',
  components: {
    BottomBar,
    TopBar,
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
  z-index: -1;
}
</style>
