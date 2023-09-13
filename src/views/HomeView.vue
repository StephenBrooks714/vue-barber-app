<template>
  <header class="home-intro">
    <div class="container">
      <div class="row justify-content-center align-items-center">
        <div class="col-md-10">
          <img src="/img/mainLogo.png" class="img-fluid" alt="img" />
          <h2 class="text-yellow fw-bold">
            Get An Appointment With A View Barber
          </h2>
          <a href="#" class="btn btn-outline-white me-2 rounded-pill">
            Get Started
          </a>
          <a href="#" class="btn btn-gold me-2 rounded-pill">About Us</a>
        </div>
      </div>
    </div>
  </header>
  <div class="home">
    <HelloWorld />
  </div>
</template>
<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>
