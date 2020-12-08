<template>
  <div class="container-fluid text-center distance bg_gray">
    <div>
      <h3>在线订单</h3>
      <p class="font18">- 婚纱摄影解决方案 -</p>
      <!-- 表单部分 -->
      <div class="bg_blue">
        <form class="d-flex justify-content-around">
          <input type="text" placeholder="姓名" name="uname">
          <input type="text" placeholder="电话" name="uphone">
          <input type="text" placeholder="微信" name="wechat">
          <input type="text" placeholder="预期价格" name="price">
          <input type="text" placeholder="预约时间" name="time">
        </form>
        <button>提交</button>
      </div>
      <!-- 底部样片 -->
      <div>
        <h3 class="mt-5">样片推荐</h3>
        <div class="d-flex justify-content-around">
         <div>
           <div class="img_scale">
             <img src="../assets/img_online/couple_2.jpg">
             <p class="img_bottom">VIEW DETAIL</p>
           </div>
           <div class="d-flex justify-content-between">
              <span>photo name</span>
              <span>date</span>
           </div>
           <p class="text-left">游艇会</p>
         </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
.bg_blue{
  margin: 0 auto;
  width: 1127px;  height: 265px;
  background: url('../assets/img_online/bg_blue.png') no-repeat center center;
}
input{
  width: 194px;
  /* background: none; */
  margin-top: 110px;
  background: none;
  border: 0;
  outline: none;
  border-bottom: 2px solid #fff;
  box-shadow: none;
}
input::placeholder{
  color: #fff;
  font-size: 12px;
  text-indent: 4px;
}
button{
  width: 172px;
  border:3px solid #fff;
  border-radius: 5px;
  background: none;
  font-size:16px;
  margin-top: 50px;
  color:#fff;
  cursor: pointer;
  box-shadow: none;
  outline: none;
}
.img_scale{
  overflow: hidden;
}
.img_scale>img:hover{
  z-index: 1;
  transform: scale(1.2);
}

.img_bottom:hover{
  display: block;
  z-index: 111;
  width: 280px;
  height: 72px;
  bottom: -72px;
  background: rgba(0,0,0,0.8);
  line-height: 72px;
  text-align: center;
  text-transform: uppercase;
  font-size: 17px;
  color: #fff;
  transition: all .3s ease-out;
}
.img_bottom{
  display: none;
  
}

</style>
