<template>
  <div id="app">
      <Top></Top>
      <AppCenter></AppCenter>
      
  </div>
</template>

<script>
import Top from './AppTop.vue';
import AppCenter from './AppCenter';

export default {
  name: 'app',
  data: {

  },
  methods: {

  },
  components: {
    Top,
    AppCenter
  }
}
</script>

<style>
* {
  padding: 0;
  margin: 0;
  user-select: none;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  font-size: 18px;
  color: #3f3f3f;
}

</style>





