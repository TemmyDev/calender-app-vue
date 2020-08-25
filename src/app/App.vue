<template>
  <div id="app">
    <CalenderWeek />
    <CalenderEntry />
  </div>
</template>

<script>
import CalenderWeek from './components/CalenderWeek.vue';
import CalenderEntry from './components/CalenderEntry.vue';
export default {
  name: 'App',
  components: {
    CalenderWeek,
    CalenderEntry
  }
}
</script>

<style lang="scss">
html, body {
  height: 100%;
}
</style>

<style lang="scss" scoped>
   #app {
  height: inherit;
  background: #6e6e6e;
  display: flex;
  flex-direction: column;
  align-items: center;
  -webkit-align-items: center;
  justify-content: center;
  -webkit-justify-content: center;
}
</style>
