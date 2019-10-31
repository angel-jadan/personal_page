<template>
  <div id="app">
    <div>
      <li>INICIO</li>
      <li>ACERCA DE</li>
      <li>PORTAFOLIO</li>
      <li>SERVICIOS</li>
      <li>CONTACTO</li>
    </div>
    <img src="https://angel-jadan.github.io/personal_page/dist/logo.png">
    <h3></h3>
    <h2></h2>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'W E L C O M E'
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
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
