<template>
<h1>Signupform</h1>
<Mysignup/>
</template>

<script>

import Mysignup from './components/Mysignup.vue'


export default {
  name: 'App',
  components: {Mysignup
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
body{
  margin:0
}
</style>
