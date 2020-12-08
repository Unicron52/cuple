<template>
  <div class="container-fluid bg_gray">
    <!-- 关于我们 -->
      <div class="font14">
        <a class="text-muted" href="#">首页</a>
			  <span class="ml-4 mr-4">/</span>
			  <a class="text-muted" href="#">关于我们</a>
      </div>
		<!-- 联系我们 -->
			<div class="text-center mt-5 mb-4">
        <h3>联系我们</h3>
			  <h5 class="font18">- CONTACT US -</h5>
      </div>
    <!-- smallmap -->
			<div class="comap">
				<img class="w-100" src="../assets/img_contact/smallmap.jpg">
			</div>
		<!-- 介绍 -->
			<div class="intr font12">
				<p>厦门市思明区薇薇新娘婚纱影楼</p>
				<p>在2005年就引导旅游婚纱摄影新概念W.P.T（Wedding photo in travelling），</p>
				<p>推出旅行婚照拍摄服务项目，</p>
				<p>接待了数万对来自上海、北京、武汉、南京、香港、深圳、广州等客人，</p>
				<p>省内漳州、泉州、三明、福州、南平等客人来厦旅行拍婚照</p>
			</div>
			<div>
				<ul class="unstyled d-flex justify-content-around conect ">
					<li>
						<img src="../assets/img_contact/c2.png">
						<p class="font_weight">TEL</p>
						<p class="font12">官方微博</p>
					</li>
					<li>
						<img src="../assets/img_contact/c3.png">
						<p class="font_weight">微博</p>
						<p class="font12">4000-334420</p>
					</li>
					<li>
						<img src="../assets/img_contact/c4.png">
						<p class="font_weight">WEIXIN</p>
						<p class="font12">xmvivi520</p>
					</li>
				</ul>
			</div>
			<div class=" text-center mt-5">
				<p class="mb-1 font18">ADRESS</p>
				<p class="mb-3">厦门市思明区厦禾路986-988号银河大厦18楼18C</p>
				<div><img src="../assets/img_contact/wxx.jpg"></div>
				<p class="mt-2 font-weight-light">关注微信，扫一扫</p>
			</div>
  </div>
</template>
<style>
.font14{
  border-bottom: 1px solid #98a0be;
  height: 49px;
  line-height: 49px;
  text-align: center;
  font-size: 14px;
  color: #adadad;   
}
a:hover{
  text-decoration: none;
}
.comap{
  margin: 0 auto;
  width: 1178px;
  border: 1px solid #7488b7;
  padding: 10px;
}
.intr{
  margin-top: 60px;
}
.font12{
  text-align: center;
  color: #a9a9a9;
  font-size: 12px;
  line-height: 1;
}
.conect{
  display: block;
  overflow: hidden;
  width: 840px;
  padding: 40px 0;
  border-bottom: 1px solid #999ca3;
  border-top: 1px solid #999ca3;
  margin: 0 auto;
  text-align: center;
  margin-top: 40px;
}
.font_weight{
  font-size: 14px;
  font-weight: bold;
  margin-top: 5px;
}

</style>