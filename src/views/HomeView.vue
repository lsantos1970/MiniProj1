<template>
  <h1>Benvindo à minha página pessoal</h1>
  <img alt="Vue logo" src="../assets/Homepicture.jpg" />
  <div class="home">
    <HelloLuis msg="" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloLuis from "@/components/MiniProject1.vue";

export default {
  name: "HomeView",
  components: {
    HelloLuis,
  },
};
</script>
