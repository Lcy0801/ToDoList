<template>
  <div id="app">
    <AddTD></AddTD>
  </div>
</template>

<script>
import  AddTD  from "./components/AddTD.vue"
import  ListTD  from "./components/ListTD.vue"
import  StatesTD from "./components/StatesTD.vue"

export default {
  name: 'App',
  components: {
    AddTD,
    ListTD,
    StatesTD,
    AddTD
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
