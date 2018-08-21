<!DOCTYPE html>
<html>
<head>
	<title>HOME</title>
	<style type="text/css">
		html,body,h1,h2,h3,h4,h5,h6,p,ul,li,ol,pre,blockquote{
			margin: 0px;
			padding: 0px;
		}	
		.header ul li{
			float: left;	
			display:inline-block;
			padding: 15px;
			margin: auto;
			position: relative;	
			font-size: 20px;
			font-family: sans-serif;
		}
		.header ul{
			background-color: black;
		}
		.header ul li a{
			text-decoration: none;
		}
		.header ul li:nth-child(6){
			float: right;
		}
		.header ul li:hover {
			background-color: gray
		}
		.header ul li:nth-child(5) div {
			display: block;

		}
	
		.banner div h3{
			position:absolute;
			bottom: 50px;
			left: 45%;
		}
		.banner div p{
			position: absolute;
			bottom: 20px;
			left:38%;
		}
		.banner {
			background-image:url('images/banner.jpg');
			height:600px;
			color:white;
			font-family: sans-serif;
			position: relative;
		}
		br{
			clear:both;
		}
	</style>
</head>


<body>
	<div class="header">
		<ul>
			<li><a href="#">Home</a></li>
			<li><a href="#">Band</a></li>
			<li><a href="#">Tour</a></li>
			<li><a href="#">Contact</a></li>
			<li>
				<a href="#">More</a>
				<div>
					<a href="#">Marchandise</a>
					<a href="#">Extras</a>
					<a href="#">Media</a>
				</div>
			</li>
			<li><a href="#">Search</a></li>
		</ul>
	</div>
	<br>
	<div class="banner">
		<div>
			<h3>Chicago</h3>
			<p>Thank you, Chicago - A night we won't forget.</p>
		</div>	
	<div>
	</div>
</body>
</html>
