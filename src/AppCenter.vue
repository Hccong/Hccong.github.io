<template>
		<div class='app_center'>
        <div class='center_banner'>
            <img src="https://ss0.bdstatic.com/94oJfD_bAAcT8t7mm9GUKT-xh_/timg?image&quality=100&size=b4000_4000&sec=1495103770&di=2080756a519276466fde89c1bc70cedc&src=http://img.zcool.cn/community/0155fd580d9db9a84a0e282b276e3c.jpg@900w_1l_2o_100sh.jpg"> 
        </div>
        <div class='center_ad'>
             <div>
                 <transition enter-active-class="zoomInLeft" leave-active-class="zoomOutRight">
                    <p v-show="shows" class="animated rubberBand 1s infinite" >2017年新的起点,技术研究院正式开通啦~</p>
                 </transition>
             </div>
        </div>
        <div class='center_table'>
     <!--      <Row type="flex" justify="space-around" class="code-row-bg" v-for='(index, value) in arr'>
            <Col span="1" offset="0"><div>{{value}}</div></Col>
            <div class='clear'></div>
          </Row> -->

            <div class="row table_row" v-for='(index, value) in arr'>
              <div class="col-md-<span style="color: #fff;
                <div>
                    <div>
                      Harry{{value}}
                    </div>
                    <div class='cell_imgdiv'>
                      <img src="http://thumb102.hellorf.com/preview/115044886.jpg" class='cell_img'>
                    </div>

                </div>
              </div>
            </div>
        </div>
    </div>
</template>


<script>
	export default({
		data() {
        return{
          shows: true,
          arr: ['1', '2', '3', '4', '5','11', '22', '33', '44', '55', '66']
        }
		},
    mounted: function () {
       
    },
		methods: {
     
		},
    transitions: {
      bounce: {
        enterClass: 'bounceInLeft',
        leaveClass: 'bounceOutRight'
      }
    },
    watch: {
      
    }
});
</script>

<style type="text/css">
.app_center {
  background-color: #f5f5f5;
}
.center_banner img {
  padding: 0;
  margin: 0;
  margin: 0 10%;
  width: 80%;
  display: block;
}
.center_ad {
  margin: 0 10%;
  background-color: #e8e8e8;
  height: 40px;
  text-align: left;
}
.center_ad p {
  line-height: 40px;
  text-align: center;
  font-size: 15px;
}
.center_table {
  margin-top: 30px;
}
.code-row-bg {
  background-color: red;
}
.center_table .table_row {
  display: inline-block;
  background-color: #fff;
  height: 320px;
  width: 290px;
  margin-top: 30px;
  margin-right: 30px;
  border: 0.1px solid #000;
  border-radius: 5px;
}
.cell_imgdiv {
  font-size: 0;
}
.cell_img {
  width: 100%;
  height: 230px;
  overflow: hidden;
  margin: 0;
  padding: 0;
}
.clear {
  clear: both;
}

</style>


