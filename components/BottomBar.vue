<template>
  <div class="flex-grow-0 justify-center order-last flex font-mono">
    <ul>
      <li><nuxt-link to="/tech-stack/">Tech Stack</nuxt-link></li>
    </ul>
    <ul class="ml-4 list-disc list-inside">
      <li><nuxt-link to="/resume/">Résumé</nuxt-link></li>
    </ul>
    <ul class="ml-4 list-disc list-inside">
      <li><nuxt-link to="/about/">About</nuxt-link></li>
    </ul>
    <ul class="ml-4 list-disc list-inside">
      <li><nuxt-link to="/now/">Now</nuxt-link></li>
    </ul>
    <ul class="ml-4 list-disc list-inside">
      <li><nuxt-link to="/repos/">Repos</nuxt-link></li>
    </ul>
  </div>
</template>

<script>

export default {
  components: {
  }
}
</script>