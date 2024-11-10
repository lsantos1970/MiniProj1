<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
  <div class="texto">
    <h1>{{ corpo }}</h1>
  </div>

  <footer>
    <h3>Redes Sociais</h3>
    <ul>
      <li>
        <a
          href="https://www.facebook.com/luiscardososantos?locale=pt_PT"
          target="_blank"
          rel="noopener"
          >Facebook</a
        >
      </li>
      <li>
        <a
          href="https://www.linkedin.com/in/lu%C3%ADs-santos-607962269/"
          target="_blank"
          rel="noopener"
          >Linkedin</a
        >
      </li>
      <li>
        <a href="https://github.com" target="_blank" rel="noopener">Github</a>
      </li>
    </ul>
    <p>&copy; 2024 Luís Santos. Todos os direitos reservados.</p>
  </footer>
</template>

<script>
export default {
  name: "HelloLuis",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
