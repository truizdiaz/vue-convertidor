<template>
  <div class="fondo">
    <Navbar />
    <Convertidor />
  </div>
</template>

<script>
import Convertidor from "./components/Convertidor";
import Navbar from "./components/Navbar";

export default {
  name: "App",
  components: {
    Convertidor,
    Navbar,
  },
};
</script>

<style>
.fondo {
  background-image: url("./assets/fondo.jpg");
  height: 100vh;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
</style>
