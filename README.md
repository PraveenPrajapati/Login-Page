# Login-Page
HTML and CSS Login Page 
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  
	<link rel="stylesheet" type="text/css" href="FrontLoginCss.css">
	<title>Login House Potter</title>
</head>
<body>
	
	<div class="signin">
		<form>
			<h2 style="color: white">Log In </h2>
			<input type="text" name="UserName" placeholder="UserName">
			<input type="Password" name="Password" placeholder="Password">
			<br><br>
			<a href="Congrates.html"> <input type="button" value="Log In"></a><br><br>
			<div id="container">
				<a href="#" style="margin-right: 0px; font-size: 13px; font-family: Tahoma,Geneva,sans-serif;">Reset Password</a>
				<a href="#" style="margin-right: 0px; font-size: 13px; font-family: Tahoma,Geneva,sans-serif;">Forget Password</a>
			</div>
			<br><br><br><br><br><br>
			Don't have account ? <a href="SignUp.html"> &nbsp; Sign Up</a>	
		</form>
	</div>
	</div>
<script type="text/javascript" src="bootstrap.min.js"></script>
<script type="text/javascript" src="bootstrap.js" ></script>
</body>
</html>

-----------------------------------------------------------------------------------------------------------------------

body
{
	font-family: Tahoma, Geneva,sans-serif;
	color: #fff;
	background: url(unnamed.jpg);
	background-size: cover;	
}
.signin
{
	background: rgba(44,62,80,0.7);
	padding: 80px;
	width: 250px;
	margin: auto;
	margin-top: 50px;
	height: 400px;
	margin-left: 480px;
}
form
{
	width: 240px;
	text-align: center;;
}
input/*[type=text]*/
{
	width: 240px;
	text-align: center;
	background: transparent;
	border:none;
	border-bottom: 1px solid #fff;
	font-family: 'play' sans-serif;
	font-size: 16px;
	font-weight: 200px;
	padding: 10px 0;
	transition: border 0.5s;
	outline: none;
	color: #fff;
}

input[type=button]
{
	border: none;
	width: 190px;
	background: white;
	color: #000;
	padding: 10px 0;
	font-size: 16px;
	line-height: 25px;
	border-radius: 15px;
	cursor: pointer;
}
input[type=button]:hover
{
	color: #fff;
	background-color: black;
}
h2
{
	color: white;
}
a
{
	color: yellow;
	text-decoration:blink;
}
a:hover
{
	color: skyblue;
}
.container
{
	display: flex;
	flex-direction: row;
	width: 100px;
}


::placeholder
{
	color:aliceblue;
	opacity: 0.8;
}
