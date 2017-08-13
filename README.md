# Swarup661.simon.github.io
<head>
<style>
html, body {
	background-image: url("retina_wood.png");
	text-align: centre;
}
.out-circle{
	width: 500px;
	height: 500px;
	background-color: #343438;
	position:relative;
	border-radius: 290px;
	padding: 40px;
	border: 1px solid #444;
	margin: 5% auto;
}
.out-circle .green{
	position: relative;
	top: 0;
	left: 0;
	background-color: #00ff00;
	width: 240px;
	height: 240px;
	border-radius: 100% 0 0 0;
	display: inline-block;
	margin-right: 8px;
	margin-bottom: 8px;
}
.out-circle .red{
	position: relative;
	top: 0;
	right: 0;
	background-color: #ff0000;
	width: 240px;
	height: 240px;
	border-radius: 0 100% 0 0;
	display: inline-block;
	margin-left: 8px;
	margin-bottom: 8px;
}
.out-circle .yellow{
	position: relative;
	bottom: 0;
	left: 0;
	background-color: #ffff00;
	width: 240px;
	height: 240px;
	border-radius: 0 0 0 100%;
	display: inline-block;
	margin-right: 8px;
	margin-top: 8px;
}
.out-circle .blue{
	position: relative;
	bottom: 0;
	right: 0;
	background-color: #0000ff;
	width: 240px;
	height: 240px;
	border-radius: 0 0 100% 0;
	display: inline-block;
	margin-left: 8px;
	margin-top: 8px;
}
.out-circle .game-out-circle{
	height: 200px;
	width: 200px;
	border: 40px solid #343438;
	border-radius: 160px;
	position: absolute;
	left: 150px;
	top: 150px;
	background-color: white;
}
.out-circle .game-in-circle{
	height: 148px;
	width: 148px;
	border-radius: 74px;
	position: relative;
	left: 16px;
	top: 16px;
	background-color: white;
}
.out-circle .game-in-circle .game-name{
	color: #343438;
	font-family: Alfa Slab One;
	font-size: 50;
	font-weight: bold;
	position: relative;
	top: 5px;
	left: 15px;
}
.out-circle .game-in-circle .count{
	width: 50px;
	height: 30px;
	padding: 10px;
	text-align: center;
	border: 1px solid #343438;
	border-radius: 7px;
	font-size: small;
	color: maroon;
	top: 70px;
	left: 1px;
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
	width: 30px;
	height: 30px;
	border: 4px solid #343438;
	border-radius: 17px; 
	top: 70px;
	left: 77px;
	background-color: #CB151F;
}
inout:hover, input:focus{
	outline: none;
	box-shadow: none;
}
.out-circle .game-in-circle .strict{
	position: absolute;
	width: 30px;
	height: 30px;
	border: 4px solid #343438;
	border-radius: 17px;
	top: 70px;
	left: 130px;
	background-color: #F9FF02;
}
.out-circle .game-in-circle .strict-indicator{
	position: absolute;
	width: 10px;
	height: 10px;
	border: none;
	border-radius: 5px;
	top: 55px;
	left: 140px;
	background-color: black;
}
.out-circle .game-in-circle .toogle-button{
	position: absolute;	
	width: 50px;
	height: 20px;
	padding: none;
	border: none;
	border-radius: 15% 15% 15% 15%;
	top: 140px;
	left: 60px;
	background: black;
}
.out-circle .game-in-circle .text-name .text-count{
	position: absolute;
	top: 105px;
	left: 5px;
	font-family: oswald;
	font-size: 12;
}
.out-circle .game-in-circle .text-name .text-start{
	position: absolute;
	top: 105px;
	left: 75px;
	font-family: oswald;
	font-size:12;
}
.out-circle .game-in-circle .text-name .text-strict{
	position: absolute;
	top: 105px;
	left: 125px;
	font-family: oswald;
	font-size:12;
}
.out-circle .game-in-circle .text-name .toogle-button-off{
	position: absolute;
	top: 145px;
	left: 35px;
	font-family: oswald;
	font-size: 10;
}
.out-circle .game-in-circle .text-name .toogle-button-on{
	position: absolute;
	top: 145px;
	left: 115px;
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
