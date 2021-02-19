<template>
  <div id="app">
    <Menu />
    <Home />
    <Sobre />
    <Galeria />
    <Depoimentos />
    <Button />
    <Contato />
  </div>
</template>

<script>
import Menu from './components/Menu.vue'
import Home from './components/Home.vue'
import Sobre from './components/Sobre.vue'
import Galeria from './components/Galeria.vue'
import Depoimentos from './components/Depoimentos.vue'
import Button from './components/Button.vue'
import Contato from './components/Contato.vue'


export default {
  name: 'App',
  components: {
    Menu,
    Home,
    Sobre,
    Galeria,
    Depoimentos,
    Button,
    Contato
  }
}
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  width: 100%;
}
body {
  overflow-x: hidden;
  background-color: #0b0c0c;
}

* {
  margin: 0;
  padding: 0;
}

.container {
  max-width: 960px;
  margin: 0 auto;
}
</style>
