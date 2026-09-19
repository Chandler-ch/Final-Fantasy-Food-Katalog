<script setup lang="ts">
interface Props {
  index: Number
  title: string
}

const props = defineProps<Props>()
</script>
<template>
  <div class="container">
    <img />
    <span class="subtitle">{{ index }}</span>
    <h2 class="title">{{ title }}</h2>
  </div>
</template>
<style scoped></style>
