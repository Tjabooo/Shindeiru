Source Code / index.html
------------------------
<!DOCTYPE html>
<html>
<head>
	<title>Min Info</title>
	<link rel="stylesheet" type="text/css" href="style/style.css">
</head>
<body>
	  <ul>
		<li><a href="index.html" id="Hem">Hem</a></li>	
		<li><a id="SocialaMedier">Sociala Medier</a>
			<ul>
				<li><a href="https://www.instagram.com/__tjabo__/" id="Instagram">Instagram</a></li>
				<li><a href="https://www.snapchat.com/add/kajstheman" id="Snapchat">Snapchat</a></li>
				<li><a href="https://twitter.com/Little_Tjabo" id="Twitter">Twitter</a></li>
			</ul>
		</li>
		<li><a id="Steam">Steam</a>
					<ul>
						<li><a href="https://steamcommunity.com/id/willevacbanandyouknow" id="Profil">Steam Profil</a></li>
						<li><a href="https://steamcommunity.com/tradeoffer/new/?partner=842131423&token=jbCWI8ya" id="BytesURL">Bytes-URL</a></li>
						<li><a href="https://steamcommunity.com/id/willevacbanandyouknow/inventory/" id="Förråd">Förråd</a></li>
					</ul>
		</li>
			<ul>
				<li><a href="https://twitch.tv/tjabo001" id="Twitch">Twitch</a></li>
			</ul>
			<ul>
				<li><a href="https://www.youtube.com/channel/UCPoczjC-UaDAGfxFSgOtTyg?view_as=subscriber" id="YouTube">YouTube</a></li>

			</ul>
			<ul>
</body>
</html>
---------------------------------------------------------------------------------------------------------------------------------------
style.css
------------
body {
	background-image: url(http://i64.tinypic.com/2jeej9s.jpg);
	font-family: Arial;
	color: white;
}
ul {
	margin: 0px;
	padding: 0px ;
	list-style: none;
}
ul li {
	float: left;
	width: 250px;
	height: 40px;
	background-color: black;
	opacity: 1;
	line-height: 40px;
	text-align: center;
	margin-right: 30px;
}
ul li a {
	text-decoration: none;
	color: white;
	display: block;
}
ul li a:hover {
	background-color: green;
}
ul li ul li {
	display: none;
}
ul li:hover ul li {
	display: block;
}
li:hover {
	background-color: green;
}
#Snapchat:hover {
	background-color: yellow;
	color: black;
}
#Twitter:hover {
	background-color: aqua;
	color: black;
}
#Instagram:hover {
	background-color: pink;
	color: black;
}
#Twitch:hover {
	background-color: purple;
	color: black;
}
#SocialaMedier {
	color: green;
}
#Steam:hover {
	color: black;
	background-color: blue;
}
#Steam {
	color: blue;
}
#Twitch {
	color: purple;
}
#Instagram {
	color: pink;
}
#SocialaMedier:hover {
	color: black;
}
#Snapchat {
	color: yellow;
}
#Twitter {
	color: aqua;
}
#Profil {
	color: blue;
}
#Hem {
	color: green;
}
#BytesURL {
	color: blue;
}
#Förråd {
	color: blue;
}
#Profil:hover {
	background-color: blue;
	color: black;
}
#BytesURL:hover {
	background-color: blue;
	color: black;
}
#Förråd:hover {
	background-color: blue;
	color: black;
}
#Hem:hover {
	color: black;
}
#YouTube {
	color: red;
}
#YouTube:hover {
	background-color: red;
	color: black;
}
