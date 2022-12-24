<template>
  <div id="app">
    <h1>Calculadora</h1>
    <CalculatorMain />
  </div>
</template>

<script>
import CalculatorMain from './main/CalculatorMain.vue'
export default {
  components: { CalculatorMain },
}
</script>

<style>
* {
  font-family: 'Roboto Mono', monospace;
  font-weight: 100;
  margin: 0;
  padding: 0;
  color: #ffffff;
}

html {
  font-size: 62.5%;
}

body {
  background: linear-gradient(to right, rgb(83, 105, 118), rgb(41, 46, 73));
}

#app {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  height: 100vh;
}
</style>
