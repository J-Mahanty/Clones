<script setup lang="ts"></script>

<template>
  <div class="wrapper">
    <div class="image-wrapper">
      <img src="../../assets/HomeImages/sample.jpeg" alt="Programming" />
    </div>
    <div class="image-wrapper">
      <img src="../../assets/HomeImages/sample.jpeg" alt="Programming" />
    </div>
    <div class="image-wrapper">
      <img src="../../assets/HomeImages/sample.jpeg" alt="Programming" />
    </div>
  </div>
</template>

<style lang="scss" scoped>
.wrapper {
  border: 1px solid pink;
  max-width: 80%;
  width: 80%;
  height: 600px;
  justify-self: center;
  background-color: transparent;
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;

  .image-wrapper {
    margin: 20px 30px 0;
    height: 250px;
    width: 350px;

    img {
      height: 250px;
      width: 350px;
    }
  }
}
</style>
