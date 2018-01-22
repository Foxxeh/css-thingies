@keyframes bgmove {
	from {background-position:top left;}
	to {background-position:bottom right;}
}
/* Background */
body {
	background-image:url("http://cdn.mysitemyway.com/etc-mysitemyway/webtreats/assets/posts/857/full/tileable-classic-nebula-space-patterns-8.jpg");
	animation-name:bgmove;
	animation-duration:60s;
	animation-iteration-count:infinite;
	animation-direction:alternate;
}
/* Welcome Message */
#test {
	padding-top:20%;
	padding-bottom:15%;
	text-align:center;
	color:#ddd;
	font-size:100pt;
	font-weight:800;
	font-family:helvetica;
	letter-spacing:200%;
	text-shadow:5px 5px 0px #bbb;
}
/* Copyright */
#credit {
	overflow:hidden;
	white-space: nowrap;
	margin-left:64%;
	margin-top:64px;
	text-align:left;
	color:#ddd;
	font-family:consolas;
	font-size:8pt;
	transition-duration:2s;
}
#credit:hover {
	margin-left:0%;
}
/* Header Bars */
.header {
	padding:10px;
	color:#ddd;
	font-size:30pt;
	font-family:helvetica;
	text-align:center;
	background:rgba(100,100,100,0.4);
	border-style:outset;
	border-color:#fff;
	transition-duration:2s;
}
.header:hover {
	border-color:#ccc;
	background:rgba(150,150,150,0.5);
}
/* Body Paragraphs */
.par {
	color:#ccc;
	margin-top:30px;
	margin-left:20%;
	margin-right:20%;
	padding:20px;
	font-family:helvetica;
	font-size:20pt;
	background:rgba(100,100,100,0.4);
	border-style:outset;
	transition-duration:2s;
}
.par:hover {
	border-color:#ccc;
	background:rgba(150,150,150,0.5);
}
/* Fake Button */
#pseudobutton {
	text-align:center;
	margin-top:10%;
	margin-left:30%;
	margin-right:30%;
	margin-bottom:10%;
	padding:20px;
	background:rgba(230,50,50,0.7);
	font-family:helvetica;
	font-size:20pt;
	color:rgba(190,10,10,1);
	border-width:5px;
	border-style:outset;
	transition-duration:5s;
}
#pseudobutton:hover {
	background:rgba(230,230,50,1);
	color:rgba(190,190,10,1);
	border-width:10px;
	font-size:40pt;
}
/* Links */
a:link {
	color:inherit;
	text-decoration:none;
}
a:visited {
	color:inherit;
	text-decoration:none;
}
a:hover {
	color:inherit;
	text-decoration:none;
}
a:active {
	color:inherit;
	text-decoration:none;
}
