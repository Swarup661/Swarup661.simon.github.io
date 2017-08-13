# Swarup661.simon.github.io
<!DOCTYPE html>
<html>
<head>
<style>
html, body {
	background-image: url("retina_wood.png");
	text-align: centre;
}
.out-circle{
	width: 500 ;
	height: 500 ;
	background-color: #343438;
	position:relative;
	border-radius: 290 ;
	padding: 40 ;
	border: 1  solid #444;
	margin: 5% auto;
}
.out-circle .green{
	position: relative;
	top: 0;
	left: 0;
	background-color: #00ff00;
	width: 240 ;
	height: 240 ;
	border-radius: 100% 0 0 0;
	display: inline-block;
	margin-right: 8 ;
	margin-bottom: 8 ;
}
.out-circle .red{
	position: relative;
	top: 0;
	right: 0;
	background-color: #ff0000;
	width: 240 ;
	height: 240 ;
	border-radius: 0 100% 0 0;
	display: inline-block;
	margin-left: 8 ;
	margin-bottom: 8 ;
}
.out-circle .yellow{
	position: relative;
	bottom: 0;
	left: 0;
	background-color: #ffff00;
	width: 240 ;
	height: 240 ;
	border-radius: 0 0 0 100%;
	display: inline-block;
	margin-right: 8 ;
	margin-top: 8 ;
}
.out-circle .blue{
	position: relative;
	bottom: 0;
	right: 0;
	background-color: #0000ff;
	width: 240 ;
	height: 240 ;
	border-radius: 0 0 100% 0;
	display: inline-block;
	margin-left: 8 ;
	margin-top: 8 ;
}
.out-circle .game-out-circle{
	height: 200 ;
	width: 200 ;
	border: 40  solid #343438;
	border-radius: 160 ;
	position: absolute;
	left: 150 ;
	top: 150 ;
	background-color: white;
}
.out-circle .game-in-circle{
	height: 148 ;
	width: 148 ;
	border-radius: 74 ;
	position: relative;
	left: 16 ;
	top: 16 ;
	background-color: white;
}
.out-circle .game-in-circle .game-name{
	color: #343438;
	font-family: Alfa Slab One;
	font-size: 50;
	font-weight: bold;
	position: relative;
	top: 5 ;
	left: 15 ;
}
.out-circle .game-in-circle .count{
	width: 50 ;
	height: 30 ;
	padding: 10 ;
	text-align: center;
	border: 1  solid #343438;
	border-radius: 7 ;
	font-size: small;
	color: maroon;
	top: 70 ;
	left: 1 ;
	position: absolute;
	background-color: #370410;
	font-family: VT323;
}
input:hover, input:focus{
	outline: none;
	box-shadow: none;
}
.out-circle .game-in-circle .start{
	position: absolute;
	width: 30 ;
	height: 30 ;
	border: 4  solid #343438;
	border-radius: 17 ; 
	top: 70 ;
	left: 77 ;
	background-color: #CB151F;
}
inout:hover, input:focus{
	outline: none;
	box-shadow: none;
}
.out-circle .game-in-circle .strict{
	position: absolute;
	width: 30 ;
	height: 30 ;
	border: 4  solid #343438;
	border-radius: 17 ;
	top: 70 ;
	left: 130 ;
	background-color: #F9FF02;
}
.out-circle .game-in-circle .strict-indicator{
	position: absolute;
	width: 10 ;
	height: 10 ;
	border: none;
	border-radius: 5 ;
	top: 55 ;
	left: 140 ;
	background-color: black;
}
.out-circle .game-in-circle .toogle-button{
	position: absolute;	
	width: 50 ;
	height: 20 ;
	padding: none;
	border: none;
	border-radius: 15% 15% 15% 15%;
	top: 140 ;
	left: 60 ;
	background: black;
}
.out-circle .game-in-circle .text-name .text-count{
	position: absolute;
	top: 105 ;
	left: 5 ;
	font-family: oswald;
	font-size: 12;
}
.out-circle .game-in-circle .text-name .text-start{
	position: absolute;
	top: 105 ;
	left: 75 ;
	font-family: oswald;
	font-size:12;
}
.out-circle .game-in-circle .text-name .text-strict{
	position: absolute;
	top: 105 ;
	left: 125 ;
	font-family: oswald;
	font-size:12;
}
.out-circle .game-in-circle .text-name .toogle-button-off{
	position: absolute;
	top: 145 ;
	left: 35 ;
	font-family: oswald;
	font-size: 10;
}
.out-circle .game-in-circle .text-name .toogle-button-on{
	position: absolute;
	top: 145 ;
	left: 115 ;
	font-family: oswald;
	font-size: 10;
}
</style>
</head>
<body>
<div class="out-circle">
<div id="green" class="green"></div>
<div id="red" class="red"></div>
<div id="yellow" class="yellow"></div>
<div id="blue" class="blue"></div>
<div class="game-out-circle">
<div class="game-in-circle">
<span class="game-name">Simon</span>
<input class="count" id="count" name="count" type="text" value="-   -" />
<button class="start" id="start" name="start" type="button"></button>
<button class="strict" id="strict" name="strict" type="button"></button>
<input class="strict-indicator" id="strict-indicator" name="strict-indicator" type="text"/>
<button class="toogle-button" id="toogole-button" name="toogle-button" type="button"></button>
<div class="text-name"> 
<span class="text-count">COUNT</span>
<span class="text-start">  START</span>
<span class="text-strict">STRICT</span>
<span class="toogle-button-off">OFF</span>
<span class="toogle-button-on">ON</span>
</div>
</div>
</div>
</div>
<body>
</html>
