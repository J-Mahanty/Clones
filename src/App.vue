<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import NavView from './views/NavView.vue'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <NavView />
      </nav>
    </div>
  </header>
</template>

<style lang="scss" scoped></style>
