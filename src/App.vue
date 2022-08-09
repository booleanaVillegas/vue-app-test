<script>
import DisplayConcept from './components/DisplayConcept.vue'

export default {
  components: {
    DisplayConcept
  }
}
</script>

<template>
  <header><h1>Vue Conceptos Basicos</h1></header>

  <main>
    <DisplayConcept /> 
  </main>

  <footer>Clase de programación web avanzada</footer>
</template>

<style scoped>
header {
  background-color: cadetblue;
  color: white;
  width: 100%;
}

h1 {
  margin: 0 auto;
  text-align: center;
}

main {
  display: flex;
  flex-direction: column;
  justify-items: center;
}
</style>
