<script setup>

defineProps({
  text: String,
})
</script>

<template>
  <h3>{{ text }}</h3>
</template>

<style scoped lang="scss">
h3 {
  letter-spacing: 2px;
  text-align: center;
}
</style>
