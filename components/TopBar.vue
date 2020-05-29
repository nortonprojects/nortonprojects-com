<template>
  <div class="flex-grow-0 flex justify-start font-mono my-2 mx-4">
    <ul>
      <li class="text-xl font-semibold"><nuxt-link to="/">Norton Projects</nuxt-link></li>
    </ul>
    <ul class="ml-4 list-disc list-inside">
      <li><nuxt-link to="/software">Software</nuxt-link></li>
    </ul>
    <ul class="ml-4 list-disc list-inside">
      <li><nuxt-link to="/woodwork">Woodwork</nuxt-link></li>
    </ul>
    <ul class="ml-4 list-disc list-inside">
      <li><nuxt-link to="/podcast">Podcast</nuxt-link></li>
    </ul>
  </div>
</template>

<script>

export default {
  components: {
  }
}
</script>
