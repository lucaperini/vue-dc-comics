<template>
  <div id="app">
    <IndexHeader />
    <IndexMain />
    <IndexServices />
    <IndexFooter />
    <IndexFooterSocial />
  </div>
</template>

<script>
import IndexHeader from './components/IndexHeader.vue'
import IndexMain from './components/IndexMain.vue'
import IndexServices from './components/IndexServices.vue'
import IndexFooter from './components/IndexFooter.vue'
import IndexFooterSocial from './components/IndexFooterSocial.vue'


export default {
  name: 'App',
  components: {
    IndexHeader,
    IndexMain,
    IndexServices,
    IndexFooter,
    IndexFooterSocial,
  }
}
</script>

<style lang="scss">
@import "./assets/scss/style.css";
@import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@400;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap');

#app {
  font-family: 'Montserrat', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
