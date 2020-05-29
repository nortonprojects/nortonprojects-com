<template>
    <div class="panel">
        <slot></slot>
    </div>
</template>

<script>

export default {
  components: {
  }
}
</script>

<style scoped>
.panel {
  @apply px-6 py-8 shadow-lg border border-gray-400 rounded bg-gray-200 max-h-full transform transition duration-700 ease-in-out;
  &:hover{
    @apply border-blue-900 scale-105 opacity-75;
  }
}
</style>