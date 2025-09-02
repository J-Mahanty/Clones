<script setup lang="ts"></script>

<template>
  <div class="wrapper">
    <div class="image-wrapper">
      <img src="../../assets/HomeImages/sample.jpeg" alt="Programming" />
      <h4>Sub-details</h4>
      <h3>Details</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse tempor eros vitae
        hendrerit ultrices. Aliquam diam felis, faucibus non libero quis, commodo sagittis libero.
      </p>
    </div>

    <!-- <div class="image-wrapper">
      <img src="../../assets/HomeImages/sample.jpeg" alt="Programming" />
      <h4>Sub-details</h4>
      <h3>Details</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse tempor eros vitae
        hendrerit ultrices. Aliquam diam felis, faucibus non libero quis, commodo sagittis libero.
      </p>
    </div>

    <div class="image-wrapper">
      <img src="../../assets/HomeImages/sample.jpeg" alt="Programming" />
      <h4>Sub-details</h4>
      <h3>Details</h3>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse tempor eros vitae
        hendrerit ultrices. Aliquam diam felis, faucibus non libero quis, commodo sagittis libero.
      </p>
    </div> -->
  </div>
</template>

<style lang="scss" scoped>
.wrapper {
  max-width: 80%;
  width: 80%;
  height: 600px !important;
  justify-self: center;
  background-color: transparent !important;
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;

  .image-wrapper {
    margin: 20px 30px 0;
    height: 450px;
    width: 350px;

    img {
      height: 250px;
      width: 350px;
    }

    h4 {
      font-size: 16px;
      margin: 8px 4px;
      color: #8f8a8a;
    }

    h3 {
      font-size: 20px;
      margin: 4px 4px 8px;
      color: #ffffff;
    }

    p {
      margin: 16px 4px;
      font-size: 16px;
      font-weight: 400;
      color: white;
    }
  }
}
</style>
