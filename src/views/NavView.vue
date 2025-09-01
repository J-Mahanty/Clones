<script setup lang="ts">
import { RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav class="navbar">
        <div class="logo">
          <h1>DarkSide</h1>
        </div>
        <div class="links">
          <p @click="$router.push('home')">Home</p>
          <p @click="$router.push('about')">About</p>
          <p @click="$router.push('portfolio')">Portfolio</p>
          <p @click="$router.push('support')">Support</p>
          <p @click="$router.push('contact')">Contact</p>
        </div>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style lang="scss" scoped>
.wrapper {
  max-width: 100%;
  width: 2000px;
  position: fixed;
  background-color: rgba(250, 250, 250, 0.1);

  .navbar {
    max-width: 100%;
    padding: 28px;
    display: flex;
    position: relative;
    flex-direction: row;
    justify-content: space-between;
    color: white;

    .logo {
      position: absolute;
      left: 10;
      display: flex;

      h1 {
        font-size: 20px;
        line-height: 2px;
      }
    }

    .links {
      position: absolute;
      right: 0;
      display: flex;
      flex-direction: row;
      justify-content: space-between;

      p {
        font-size: 20px;
        line-height: 2px;
        margin: 0 10px;
        cursor: pointer;

        &:hover {
          color: #c5bdbd;
        }
      }
    }
  }
}
</style>
