<template>
  <div class="home">
    <h1>Welcome to Ghala's Hotel</h1>
    <h3>Yesterdays Expertise is Todays Properties</h3>
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

<style>
.home {
  background-color: blue;
  height: 85vh;
  background-image: url(https://raw.githubusercontent.com/ismaeeladams/Property-List/main/beach2.jpg);
  /* background-repeat: no-repeat; */
  background-size: cover;
}
</style>
