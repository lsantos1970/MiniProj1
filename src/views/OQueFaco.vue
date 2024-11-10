<template>
  <h1>O Que Faço</h1>
  <p>
    Sou especialista de sistemas e tecnologias de informação <br />
    num organismo público. <br />
  </p>
  <div class="oquefaco">
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
