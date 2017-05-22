<template>
		<div class='app_top'>
          <img class='logo_img' src="./assets/logo.png">
          <ul class='top_ul'>
            <li><a href="javascript:void(0);">HOME</a></li>
            <li><a href="javascript:void(0);">IOS</a></li>
            <li><a href="javascript:void(0);">Android</a></li>
            <li><a href="javascript:void(0);">HTML</a></li>
            <li><a href="javascript:void(0);">JAVA</a></li>
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
.logo_img {
  float: left;
  margin-top: 10px;
  margin-left: 5%;
  margin-right: 10%;
}
.top_ul {
  list-style:none; 
}

.top_ul li {
  float: left;
}

.top_ul li a {
    color: rgb(51, 51, 51); 
    line-height: 30px; 
    padding: 4px 20px;
    text-decoration: none;
    white-space: nowrap;
    margin-top: 15px;
}
.top_ul li a:hover {
    background-color: #555; 
    border: 0.1px #555 solid; 
    border-radius: 3px;
    color: #fff;
}
.li_img {
   padding-left: 10%;
}
.top_search {
 float: right;
 right: 5%;
}
.top_ul li:hover{
  color: red;
}

</style>