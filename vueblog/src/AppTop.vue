<template>
		<div class='app_top'>
          <ul class='top_ul'>
            <!-- <li class='li_img'><img src="./assets/logo.png"></li> -->
            <li>Home</li>
            <li>IOS</li>
            <li>Android</li>
            <li>Html</li>
            <li>Java</li>
          </ul>
          <Input class='top_search' v-model="value" placeholder="请搜索..." style="width: 200px;" ></Input>
      </div>
</template>


<script type="text/javascript">
	export default({
		data: {

		},
		methods: {

		}
	});
</script>

<style type="text/css">
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
  margin: 0 1.2%;
  height: 70px;
  line-height: 70px;
  padding: 3px 3px;
  background-color: red;
}
.li_img {
   padding-left: 10%;
}
.top_search {
 
}
.top_ul li:hover{
  color: red;
}

</style>