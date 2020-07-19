<!-- TEMPLATE -->
<template>
  <div>
    <h2>Hello World</h2>
    <h3>{{ texto }}</h3>
    <h3>{{ pingüino }}</h3>
    <MiComponente />
  </div>
</template>

<!-- SCRIPT -->
<script>
import MiComponente from "./MiComponente.vue";
export default {
  name: "HelloWorld",
  components: {
    MiComponente
  },
  props: {
    msg: String
  },
  data() {
    return {
      texto: "Hola Mundo desde componente",
      pingüino: "Soy un pingüino"
    };
  }
};
</script>

<!-- STYLE -->
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
