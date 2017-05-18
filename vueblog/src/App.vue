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
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  font-size: 18px;
  color: #3f3f3f;
}
.app_top {
  height: 70px;
  line-height: 70px;
}
.top_ul {
  text-align: center;
}
.top_ul li{
  list-style: none;
  float: left;
  margin: 0 20px;
  height: 70px;
  line-height: 70px;
}
.li_img {
   padding-left: 10%;
}
.top_search {
 
}
.top_ul li:hover{
  color: red;
}
.app_center {
  background-color: #f5f5f5;
  height: 700px;
}
</style>





