<template>
  <div class="hobbies">
    <h1>TRIATLO</h1>
    <img alt="Vue logo" src="../assets/triatlo.png" />
    <p>
      Desde 2008 que entrei no mundo do Triatlo<br />
      começando pelas distâncias menores, mas neste<br />
      momento apenas faço as provas de longa distância,<br />
      conhecidas por IRONMAN.
    </p>
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
