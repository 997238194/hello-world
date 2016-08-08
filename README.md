# hello-world<<!DOCTYPE html>
<html>
<head>
	<title>
		zjj
	</title>
	<style>
      #div{
      	width:10px;
      	height: 10px;
      	background: red;
      }
     #ul1 li:nth-child(even) {
     	background: #fff;
     	border: 10px solid #000;
     }  
     #div1:target{
     	background: red;
     }
   	</style>
</head>
<body>
	<div id="div">
		
	</div>
	<ul id="ul1">
		<li>aaa</li>
		<li>aaa</li>
		<li>aaa</li>
	</ul>
	<a href="#div1">click</a>
	<div id="div1">aaaa</div>
</body>
</html>
