<template>
  <div class="home">
    <HelloLuis msg="Benvindo à minha página pessoal" />
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
