<template>
  <div id="app">
    <EmployeesList />
  </div>
</template>

<script>
import EmployeesList from './components/Employee.vue'

export default {
  name: 'App',
  components: {
    EmployeesList
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