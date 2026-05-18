# suresh-website
My first premium website by Suresh
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Suresh Premium Website</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:sans-serif;
}

body{
background:#000;
color:white;
text-align:center;
overflow-x:hidden;
}

header{
padding:80px 20px;
background:linear-gradient(45deg,#ff0000,#000);
}

h1{
font-size:45px;
margin-bottom:20px;
}

p{
font-size:20px;
margin-bottom:30px;
}

button{
padding:15px 40px;
font-size:20px;
border:none;
border-radius:12px;
background:red;
color:white;
cursor:pointer;
transition:0.3s;
}

button:hover{
background:white;
color:black;
transform:scale(1.1);
}

section{
padding:60px 20px;
}

.card{
background:#111;
padding:30px;
margin:20px auto;
max-width:400px;
border-radius:20px;
box-shadow:0 0 20px red;
}

footer{
padding:20px;
background:#111;
margin-top:50px;
}

</style>
</head>

<body>

<header>

<h1>Welcome To Suresh Website</h1>

<p>Premium Website By Suresh Bishnoi</p>

<button onclick="showMessage()">
Click Here
</button>

</header>

<section>

<div class="card">
<h2>Gaming Website</h2>
<p>Play games and enjoy premium experience.</p>
</div>

<div class="card">
<h2>3D Design</h2>
<p>Modern animation and mobile responsive design.</p>
</div>

<div class="card">
<h2>Install App</h2>
<p>You can install this website like an app.</p>
</div>

</section>

<footer>

<p>© 2026 Suresh Website</p>

</footer>

<script>

function showMessage(){
alert("Welcome Suresh Bishnoi");
}

</script>

</body>
</html>
