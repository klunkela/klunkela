<script setup>
import Hello from "@/components/Hello.vue";
</script>

<template>
  <div>
    <Hello :text="'через один год - 01.06.2025 - я буду успешным человеком'"/>
  </div>
</template>

<style scoped lang="scss">
div {
  max-width: 1280px;
  min-height: 100vh;
  margin: auto;
  padding: 24px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
</style>
