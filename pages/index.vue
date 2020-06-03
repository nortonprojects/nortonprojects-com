<template>
  <div class="grid grid-cols-1 grid-flow-row lg:grid-cols-3 gap-2 lg:gap-8 p-2 lg:px-8 lg:py-8 flex-grow lg:h-64">
    <div class="col-span-1 lg:col-span-3">
      <h1 class="text-gray-800 font-bold font-mono text-6xl">Norton Projects</h1>
      <p class="ml-12 font-mono text-gray-700 font-bold italic tracking-tight text-xl">What I'm up to&#8230;</p>
    </div>
    <Panel>
      <nuxt-link to="/software/" class="w-full h-full flex flex-col">
        <h2 class="text-left ml-6 text-gray-700 text-3xl font-bold font-mono">Software</h2>
        <div class="mt-8 flex-grow rounded bg-cover" style="background-image: url('/software.jpg')"></div>
      </nuxt-link>
    </Panel>
    <Panel>
      <nuxt-link to="/woodwork/" class="w-full h-full flex flex-col">
        <h2 class="text-left ml-6 text-gray-700 text-3xl font-bold font-serif">Woodwork</h2>
        <div class="mt-8 flex-grow rounded bg-cover" style="background-image: url('/woodwork.jpg')"></div>
      </nuxt-link>
    </Panel>
    <Panel>
      <nuxt-link to="/podcast/" class="w-full h-full flex flex-col">
        <h2 class="text-left ml-6 text-gray-700 text-3xl font-bold font-sans">Podcast</h2>
        <div class="mt-8 flex-grow rounded bg-cover" style="background-image: url('/podcast.jpg')"></div>
      </nuxt-link>
    </Panel>
  </div>
</template>

<script>
import Panel from '@/components/FullPanel.vue';

export default {
  layout: 'home',
  components: {
    Panel
  }
}
</script>

<style scoped>
.grid {
  grid-template-rows: 1fr 9fr;
  grid-auto-rows: 9fr;
}
</style>