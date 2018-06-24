<template>
  <div id="app">
    <nav id="menu" class="navbar navbar-default navbar-fixed-top">
	<div class="container">
		
		<div class="navbar-header">
		  <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
			<span class="sr-only">Toggle navigation</span>
			<span class="icon-bar"></span>
			<span class="icon-bar"></span>
			<span class="icon-bar"></span>
		  </button>
		  <a class="navbar-brand" href="#"><img src="src/img/logo.png" alt="..."></a>
		</div>

		<div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
		  <ul class="nav navbar-nav navbar-right">
			<li><a href="#home" class="scroll">首页</a></li>
			<li><a href="#whatIdo" class="scroll">我的工作</a></li>
			<li><a href="#about" class="scroll">关于我</a></li>
			<li><a href="#works" class="scroll">作品</a></li>
			<li><a href="#experience" class="scroll">经验</a></li> 
			<li><a href="#contact" class="scroll">练习</a></li>
		  </ul>
		</div>
	</div>
</nav>

<section id="home">
	<div class="overlay"> 
		<div class="container"> 
			<div class="content-heading text-center"> 
				<h1>嗨，我是一名前端工程师</h1>
				<p class="lead">我喜欢敲打健壮的代码.</p>
				<a href="#works" class="scroll goto-btn">查看</a> 
			</div>
		</div> 
	</div>
</section>
<section id="intro">
	<div class="container"> 
		<div class="row">

			<div class="col-md-8 col-md-offset-2"> 
				 <h1>嗨，我是一名前端工程师</h1>
				<p class="lead">我喜欢敲打健壮的代码</p>
			</div>
			
		</div>
	</div>
</section>

<section id="whatIdo">
	<div class="container"> 

		<div class="section-header">
			<h2>我的 <span class="highlight"><strong>工作</strong></span></h2>
			<div class="fancy"><span></span></div>
		</div>

		<div class="row">
			
			<div class="col-md-6 text-right">  
				<img src="src/img/design.jpg" class="intro-logo img-responsive" alt="free-template">
			</div>

			<div class="col-md-6"> 
			  
				<div class="media service"> 
					<div class="media-left media-middle">
						<img src="src/img/1.png" class="imgPng" alt="">
					</div>
					<div class="media-body">
						<h4 style="height: 100%;line-height: 80px" class="media-heading">前端页面开发</h4>
					</div>
				</div>

				<div class="media service">
					<div class="media-left media-middle">
						<img src="src/img/2.png" class="imgPng" alt="">
					</div>
					<div class="media-body">
						<h4 style="height: 100%;line-height: 80px" class="media-heading">实现页面交互</h4>
					</div>
				</div>

				<div class="media service">
					<div class="media-left media-middle">
						<img src="src/img/3.png" class="imgPng" alt="">
					</div>
					<div class="media-body">
						<h4 style="height: 100%;line-height: 80px" class="media-heading">切图</h4>
					</div>
				</div>
			</div>
			
		</div>

	</div>
</section>


<section id="about">
<div class="container">
		<div class="section-header">
			<h2>关于我 <span class="highlight"><strong></strong></span></h2>
			<h5><em>我是一个阳光明媚的男孩！</em></h5>
			<div class="fancy"><span></span></div>
		</div>
	</div>
<div class="container">

	<div class="row">
		<div class="col-sm-4 col-sm-offset-1 scrollimation fade-right in">
			<img class="img-responsive img-circle img-center" src="src/img/about.jpg" alt="">
		</div>
		<div class="col-sm-6 col-sm-offset-1 scrollimation fade-left in">
			<h1>你好，我叫梁亚鹏</h1>
			<p style="text-indent: 2em;">屏幕前的朋友们，你们好，自我介绍一下，我叫梁亚鹏，家乡河北邯郸。是河南科技大学本科。从事咱们前端行业已经三年出头了。爱好程序设计，喜欢开发自已的小型产品，追求技术上的满足感;稳固的架构，健壮的代码，团结的合作，是我的不懈追求。
有良好的编程习惯，以及程序错误控制和解决能力，我爱程序员这个岗位，当每天敲着代码，听着音乐，是很快乐的
用心工作，用心生活!我可能不是最好的，最合适的，我觉得我是最有潜力的!</p>
			
		</div>
	</div>
	
</div>

		<div id="counter" class="text-center">
			<div class="container">
				<div class="row">
				  <div class="col-md-6">
					 <div class="row">
						  <div class="counter"> 

					  <div class="col-xs-6 facts">
						<div class="count-box"> 
							<h4 class="count">420</h4>
							<p class="small">移动应用</p>
						</div> 
					  </div>

					  <div class="col-xs-6 facts">
						<div class="count-box">
						  <h4 class="count">625</h4>
						  <p class="small">web应用程序</p>
						</div>
					  </div>
					  </div>
					  </div>
					  <div class="row">	
						<div class="counter"> 						  
					  <div class="col-xs-6 facts"> 
						<div class="count-box">
						  <h4 class="count">10</h4>
						  <p class="small">UI设计</p>
						</div>
					  </div>

					  <div class="col-xs-6 facts"> 
						<div class="count-box">
						  <h4 class="count">152</h4>
						  <p class="small">项目</p>
						</div>
					  </div>

					  </div>

					</div>

					 </div> 
					<div class="col-md-6">
					<div>

						
						<div class="skills"> 
							<div class="skillset"> 
								<p>HTML5，CSS3，JS</p>
								<div class="progress">
									<div class="progress-bar" role="progressbar" aria-valuenow="90" aria-valuemin="0" aria-valuemax="100" style="width: 90%;">
										<span class="sr-only">99% Complete</span>
									</div>
								</div>
							</div>

							<div class="skillset"> 
								<p>node.js</p>
								<div class="progress">
									<div class="progress-bar" role="progressbar" aria-valuenow="85" aria-valuemin="0" aria-valuemax="100" style="width: 75%;">
										<span class="sr-only">93% Complete</span>
									</div>
								</div>
							</div>

							<div class="skillset"> 
								<p>MySql</p>
								<div class="progress">
									<div class="progress-bar" role="progressbar" aria-valuenow="99" aria-valuemin="0" aria-valuemax="100" style="width: 89%;">
										<span class="sr-only">70% Complete</span>
									</div>
								</div>
							</div>

							<div class="skillset">
								<p>Vue，React</p>
								<div class="progress">
									<div class="progress-bar" role="progressbar" aria-valuenow="70" aria-valuemin="0" aria-valuemax="100" style="width: 80%;">
										<span class="sr-only">90% Complete</span>
									</div>
								</div>
							</div>

							<div class="skillset">
								<p>git</p>
								<div class="progress">
									<div class="progress-bar" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width: 70%;">
										<span class="sr-only">50% Complete</span>
									</div>
								</div>
							</div>
						</div>

					</div>
				</div>
				   
				  </div>
			</div>
		</div>

</section>
<section id="works">
	<div class="container">
		<div class="section-header">
			<h2>我的作品</h2>
			<div class="fancy"><span></span></div>
		</div>
	</div>

	<div class="container-fluid"> 
		 <div id="itemsWork" class="row text-center"> 

			<div class="col-xs-12 col-sm-6 col-md-3 col-lg-3 nopadding brand others">
				<div class="box"> 
					<div class="hover-bg">
						<img src="src/img/1.jpg" class="img-responsive" alt="Image"> 
					</div>
				</div>
			</div>

			<div class="col-xs-12 col-sm-6 col-md-3 col-lg-3 nopadding apps">
				<div class="box">
					<div class="hover-bg">
						<img src="src/img/2.jpg" class="img-responsive" alt="Image"> 
					</div>
				</div>
			</div>

			<div class="col-xs-12 col-sm-6 col-md-3 col-lg-3 nopadding others brand">
				<div class="box">
					<div class="hover-bg">
						<img src="src/img/3.jpg" class="img-responsive" alt="Image"> 
					</div>
				</div>
			</div>

			<div class="col-xs-12 col-sm-6 col-md-3 col-lg-3 nopadding others web"> 
				<div class="box">
					<div class="hover-bg">
						<img src="src/img/04.png" class="img-responsive" alt="Image">
					</div>
				</div>
			</div>
		</div> 
	</div> 
</section>

<section id="experience">
	<div class="container"> 
		<div class="section-header">
			<h2>我的经验</h2>
			<div class="fancy"><span></span></div>
		</div>
	</div>

	<div class="gray-bg"> 
		<div class="container">
			<div id="experience" class="row">
				<div class="col-md-10 col-md-offset-1">

					<div class="media experience">
						<div class="media-right media-middle">
							<i class="fa fa-facebook"></i>
						</div>
						<div class="media-body">
							<h4 class="media-heading">北京商云科技发展有限公司</h4>
							<h5>2018</h5>
							<p>负责官网页面制作。PSD切图后构建页面框架。负责网站商城的全部模块开发与后台动态交互数据。利用JS、CSS3前端功能，让页面更充实丰富，给用户更好浏览网站体验。并将代码上传到代码托管平台上。</p>
						</div>
					</div>

					<div class="media experience"> 
						<div class="media-right media-middle">
							<i class="fa fa-google-plus"></i>
						</div>
						<div class="media-body">
							<h4 class="media-heading">北京企云互联科技有限公司</h4>
							<h5>2016</h5>
							<p>负责前端页面开发，根据需求实现页面动画效果。利用jquery、CSS3技术完善前端功能，让页面更充实丰富。配合后端完成页面动态交互效果。</p>
						</div>
					</div>

					<div class="media experience">
						<div class="media-right media-middle">
							<i class="fa fa-yahoo"></i>
						</div>
						<div class="media-body">
							<h4 class="media-heading">北京瀚博视美文化传播有限公司</h4>
							<h5>2015</h5>
							<p>根据ui设计图进行切图，通过html，div+css对页面进行布局完成前端页面开发。优化调整页面加载性能，尽量减少页面加载时间。维护已完成的项目代码，测试网站各个功能。</p>
						</div>
					</div>					
				</div>

			</div> 
		</div>
	</div> 
</section>


<section id="contact">

	<div class="container"> 
		<div class="section-header">
			<h2>联系我</h2>
			<div class="fancy"><span></span></div>
		</div>
	</div>

	<div class="container">
		<div class="row">
			<div class="col-md-10 col-md-offset-1"> 
				<div class="row"> 

					<div class="col-md-4">  
						<div class="contact-detail">
							<img src="src/img/13.png" alt="">
							<h4>北京大兴</h4>
						</div>
					</div>
					<div class="col-md-4">
						<div class="contact-detail">
							<img src="src/img/15.png" alt="">
							<h4>2475496837@qq.com</h4>、
						</div>
					</div>

					<div class="col-md-4">
						<div class="contact-detail">
							<img src="src/img/16.png" alt="">
							<h4>17600211541</h4>、
						</div>
					</div>

				</div> 
			</div> 
		</div>

		<div class="row text-center"> 
			<div class="col-md-10 col-md-offset-1"> 
				<form id="contact-form" class="form" name="sentMessage" novalidate>

					<div class="row"> 

						<div class="col-md-4">
							<div class="form-group"> 
								<input type="text" autocomplete="off" class="form-control" placeholder="Your Name *" id="name" required data-validation-required-message="Please enter your name.">
								<p class="help-block text-danger"></p>
							</div>
						</div>

						<div class="col-md-4">
							<div class="form-group">
								<input type="email" autocomplete="off" class="form-control" placeholder="Your Email *" id="email" required data-validation-required-message="Please enter your email address.">
								<p class="help-block text-danger"></p>
							</div>
						</div>

						<div class="col-md-4">
							<div class="form-group">
								<input type="text" autocomplete="off" class="form-control" placeholder="Your Phone No. *" id="phone" required data-validation-required-message="Please enter your phone no.">
								<p class="help-block text-danger"></p>
							</div>
						</div>

					</div>
					<div class="form-group"> 
						<textarea class="form-control" rows="7" placeholder="Tell Us Something..." id="message" required data-validation-required-message="Please enter a message."></textarea>
						<p class="help-block text-danger"></p>
						<div id="success"></div>
					</div>
					<button type="submit" class="btn btn-primary btn color">Send Message</button> 
				</form>
			</div>
		</div>
	</div>
</section>
<section id="footer">
	<div class="container">
	 <ul class="list-inline social pull-left">
			<li><a href="#"><img class="imgs" src="src/img/17.png" alt=""></i></a></li>
			<li><a href="#"><img class="imgs" src="src/img/18.png" alt=""></a></li> 
			<li><a href="#"><img class="imgs" src="src/img/19.png" alt=""></a></li>
			<li><a href="#"><img class="imgs" src="src/img/20.png" alt=""></a></li>
			<li><a href="#"><img class="imgs" src="src/img/21.png" alt=""></a></li> 
		</ul>
		<p class="pull-right">版权所有©2016.个人网站</p> 
	</div>
</section>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
    }
  }
}
</script>

<style scoped>
  .imgs{
	  float: left;
	  margin-right:15px;
  }
  .imgPng{
	  margin-left:1.25em;
  }
</style>
