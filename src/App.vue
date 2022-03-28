<template>
  <div id="app">
    <IndexHeader />
    <IndexMain />
  </div>
</template>

<script>
import IndexHeader from './components/IndexHeader.vue'
import IndexMain from './components/IndexMain.vue'

export default {
  name: 'App',
  components: {
    IndexHeader,
    IndexMain,
  }
}
</script>

<style lang="scss">
@import "./assets/scss/style.css";
@import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@400;700&display=swap');
#app {
  font-family: 'Roboto Mono', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
*{
  box-sizing: border-box;
  margin:0;
  padding:0;
}
</style>
