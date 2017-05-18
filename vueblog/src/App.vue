<template>
  <div id="app">
      <div class='app_top'>
          <ul class='top_ul'>
            <li class='li_img'><img src="./assets/logo.png"></li>
            <li>Home</li>
            <li>IOS</li>
            <li>Android</li>
            <li>Html</li>
            <li>Java</li>
          </ul>
      </div>

    
      <div class='app_center'>
          <div class="input-group col-md-3">  

            <Input v-model="value" placeholder="请输入..." style="width: 300px"></Input>
            <Button type="info">信息按钮</Button>
          </div>  
      </div>
  </div>
</template>

<script>
export default {
  name: 'app'
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
   padding-left: 20%;
}
.top_ul li:hover{
  color: red;
}
.app_center {
  background-color: #f5f5f5;
  height: 700px;
}
</style>





