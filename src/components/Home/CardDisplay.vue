<script setup lang="ts">
import Card from './Card.vue'
</script>

<template>
  <div class="wrapper">
    <h2>Languages Used</h2>
    <Card />
  </div>
</template>

<style lang="scss" scoped>
.wrapper {
  max-width: 100%;
  background-color: rgba(0, 0, 0, 0.85);
  height: 800px;

  h2 {
    color: white;
    padding: 60px 140px 30px;
    margin: 0 20px;
    font-size: 28px;
  }
}
</style>
