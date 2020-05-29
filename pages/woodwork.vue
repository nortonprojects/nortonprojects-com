<template>
  <div class="grid grid-cols-1 md:grid-cols-3 gap-2 md:gap-8 p-2 md:px-8 md:py-16 h-full">
    <Panel>
      <nuxt-link to="/" class="w-full h-full flex flex-col">
        <h1 class="text-center text-gray-700 text-3xl font-bold font-sans">Woodwork</h1>
        <div class="mt-8 flex-grow rounded" style="background-image: url('/woodwork.jpg')"></div>
      </nuxt-link>
    </Panel>
  </div>
</template>

<script>
import Panel from '@/components/FullPanel.vue';

export default {
  components: {
    Panel
  }
}
</script>
