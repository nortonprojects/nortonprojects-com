<template>
  <div class="grid grid-cols-1 md:grid-cols-3 grid-rows-2 gap-2 md:gap-8 p-2 md:px-8 md:py-16 h-full">
    <Panel v-for="post in posts" :key="post.url">
      <nuxt-link :to="post.url" class="w-full h-full flex flex-col">
        <h1 class="text-center text-gray-700 text-3xl font-bold font-sans">{{post.title}}</h1>
        <div class="mt-4 flex-grow rounded" :style="`background-image: url('${post.image}')`"></div>
      </nuxt-link>
    </Panel>
  </div>
</template>

<script>
import Panel from '@/components/FullPanel.vue';

export default {
  components: {
    Panel
  },
  data: () => ({
    posts: [
      {
        url: 'starting-from-scratch',
        title: 'Starting From Scratch',
        image: '/software.jpg',
      },
      {
        url: 'starting-from-scratch',
        title: 'Starting From Scratch',
        image: '/software.jpg',
      },
      {
        url: 'starting-from-scratch',
        title: 'Starting From Scratch',
        image: '/software.jpg',
      },
      {
        url: 'starting-from-scratch',
        title: 'Starting From Scratch',
        image: '/software.jpg',
      },
      {
        url: 'starting-from-scratch',
        title: 'Starting From Scratch',
        image: '/software.jpg',
      },
      {
        url: 'starting-from-scratch',
        title: 'Starting From Scratch',
        image: '/software.jpg',
      },
      {
        url: 'starting-from-scratch',
        title: 'Starting From Scratch',
        image: '/software.jpg',
      },
      {
        url: 'starting-from-scratch',
        title: 'Starting From Scratch',
        image: '/software.jpg',
      },
      {
        url: 'starting-from-scratch',
        title: 'Starting From Scratch',
        image: '/software.jpg',
      },
      {
        url: 'starting-from-scratch',
        title: 'Starting From Scratch',
        image: '/software.jpg',
      },
      {
        url: 'starting-from-scratch',
        title: 'Starting From Scratch',
        image: '/software.jpg',
      },
    ],
  }),
}
</script>
