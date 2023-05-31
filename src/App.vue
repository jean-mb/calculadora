<template>
  <CalculdadoraComponent msg="Calculadora"/>
</template>

<script>
import CalculdadoraComponent from './components/CalculdadoraComponent.vue';

export default {
  name: 'App',
  components: {
    CalculdadoraComponent
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
