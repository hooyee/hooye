# hooye
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>学习布局</title>
		<style type="text/css">
			#header{background:darkcyan;width: 100%;height: 250px;}
			.area1{width: 960px;height: 150px;text-align: center;margin: auto;}
			h2{float: left;}
			h4{text-decoration: underline;float: right;}
			#banner{width: 100%;height:100px;position: right left;}
			.page1,.page2,.page3{float:right;text-align: center;width: 100px;padding:7px 5px;line-height: 50px;}
			.page1{background: lavender;width: 20px;height: 50px;border: 1px solid;margin:20px 2px;}
			.page2{background: khaki;width: 20px;height: 60px;border: 1px solid;margin:10px 2px;}
			.page3{background: lavender;width: 20px;height: 50px;border: 1px solid;margin:20px 2px;}
			#main{width: 960px;margin: auto;}
			#nav{display: inline-block;width: 100%;height: 42px;border-bottom: 1px solid #CCC;margin: 0 auto;text-align: center;}
			.home,.profile,.about{border:1px solid #CCC;border-top-left-radius:100px;border-top-right-radius: 100px;width: 60px;padding: 10px;float: left;}
			#div1{display:flex;}
			.c{border: 1px solid #CCC;box-sizing: border-box;padding: 10px;flex: 1 1 auto;margin: 5px;min-width: 200px;height: 160px;line-height: 160px;text-align: center;box-shadow: 0 0 5px #DDD;}
			#bottom{background: grey;width: 100%;height: auto;text-align: center;margin:0 auto;}
		</style>
	</head>
	<body>
		<div id="div0">
			<div id="header">
				<div class="area1">
					<h2>logo</h2>
					<h4>Github&nbsp;&nbsp;Login</h4>
			    </div>
				<div id="banner">
					<div class="page1">3</div>
					<div class="page2">2</div>
					<div class="page3">1</div>
				</div>
			</div>
			<div id="main">
				<div id="nav">
					<div class="home">HOME</div>
					<div class="profile">PROFILE</div>
					<div class="about">ABOUT</div>
				</div>
				<div id="content">
					<div id="div1">
						<div class="c">content 1</div>
						<div class="c">content 2</div>
						<div class="c">content 1</div>
					</div>
					<div id="div1">
						<div class="c">content 4</div>
						<div class="c">content 5</div>
						<div class="c">content 6</div>
						<div class="c">content 7</div>
					</div>
					<div id="div1">
						<div class="c">content 8</div>
						<div class="c">content 9</div>
						<div class="c">content 10</div>
					</div>
				</div>
			</div>
			<div id="bottom">&copy;2018&nbsp;ife.baidu.com</div>
		</div>
	</body>
</html>

