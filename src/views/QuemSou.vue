<template>
  <h1>Quem Sou</h1>
  <p>
    Sou um profissional apaixonado por tecnologia, especializado em <br />
    desenvolvimento web e engenharia de software. Tenho experiência em <br />
    diversos projetos que abrangem tecnologias modernas e frameworks,<br />
    procuro sempre a melhor solução para cada desafio.
  </p>

  <div class="quemsou">
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
