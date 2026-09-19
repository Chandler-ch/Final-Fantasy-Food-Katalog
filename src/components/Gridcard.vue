<script setup lang="ts">
interface Props {
  index: Number
  title: string
}

const props = defineProps<Props>()
</script>
<template>
  <div class="container">
    <img src="/meals/Flame_Roasted_Toast.webp" />
    <span class="subtitle">{{ index }}</span>
    <h2 class="title">{{ title }}</h2>
  </div>
</template>
<style scoped>
.container {
  border: 1px solid lightblue;
  display: flex;
  flex-direction: column;
}
</style>
