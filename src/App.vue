<template>
  <div id="app">
    <plateform class="center"></plateform>
  </div>
</template>

<script>
import plateform from '@/views/plateform.vue'
export default {
  name: 'App',
  components: {
	plateform
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
}
html,
body {
  width: 100%;
  height: 100vh;
  padding: 0;
  margin: 0;
  /* overflow-y: scroll; */
  /* overflow-x: hidden; */
}
.center {
  width: 1440px;
  margin: auto;
}
</style>
