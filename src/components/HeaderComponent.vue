<template>
  <header>
    <div class="hero">
      <div class="overlay"></div>
      <div class="hero-text">
        <h1>Get the fastest and safest flight with us.</h1>
        <v-btn x-large flat elevation="0" color="#00A2CC" style="color: white"
          >Start Booking</v-btn
        >
      </div>
    </div>
  </header>
</template>

<script>
export default {
  components: {},
};
</script>

<style scoped>
.hero {
  background-image: url("@/assets/hero-plane-2.jpg");
  background-size: cover;
  background-position: top;
  height: 100vh;
  position: relative;
}

.hero .hero-text {
  text-align: center;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}

.hero .hero-text h1 {
  width: 709px;
  font-weight: 700;
  font-size: 64px;
  line-height: 78px;
  color: #ffffff;
  margin-bottom: 40px;
}
</style>
