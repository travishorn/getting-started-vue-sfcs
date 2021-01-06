<template>
  <div id="app">
    <h1>My Vue App</h1>
    <PersonGreeter personName="Travis" />
  </div>
</template>

<script>
import PersonGreeter from './components/PersonGreeter.vue'

export default {
  name: 'App',
  components: {
    PersonGreeter
  }
}
</script>

<style>
#app {
  font-family: Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
