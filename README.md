
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NextGen Gaming</title>
<style>
*{margin:0;padding:0;box-sizing:border-box}
body{
font-family:Arial,sans-serif;
background:#080b16;
color:white;
}
header{
padding:22px;
display:flex;
justify-content:space-between;
align-items:center;
background:#11172a;
}
.logo{color:#00eaff;font-size:25px;font-weight:bold}
nav a{
color:white;text-decoration:none;
margin-left:15px;font-size:14px;
}
.hero{
min-height:420px;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
padding:25px;
background:linear-gradient(135deg,#101c44,#261044);
}
.hero h1{font-size:42px;margin-bottom:15px}
.hero h1 span{color:#00eaff}
.hero p{color:#c6c9d8;line-height:1.7}
.btn{
display:inline-block;
margin-top:25px;
padding:14px 28px;
background:#00d9ff;
color:#07101b;
text-decoration:none;
font-weight:bold;
border-radius:8px;
}
section{padding:45px 20px}
h2{text-align:center;margin-bottom:25px}
.games{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
max-width:1000px;
margin:auto;
}
.card{
background:#151c30;
padding:25px;
border-radius:14px;
text-align:center;
border:1px solid #26314d;
transition:.3s;
}
.card:hover{transform:translateY(-7px);border-color:#00eaff}
.card .emoji{font-size:48px}
.card h3{margin:15px}
.card p{color:#b5bdd0}
.card button{
margin-top:15px;
padding:10px 20px;
border:0;border-radius:6px;
background:#00d9ff;font-weight:bold;
}
footer{
text-align:center;
padding:25px;
background:#11172a;
color:#aab3ca;
}
@media(max-width:600px){
header{flex-direction:column;gap:15px}
.hero h1{font-size:32px}
nav a{margin:0 6px}
}
</style>
</head>
<body>

<header>
<div class="logo">NEXTGEN</div>
<nav>
<a href="#home">Home</a>
<a href="#games">Games</a>
<a href="#about">About</a>
</nav>
</header>

<div class="hero" id="home">
<h1>WELCOME TO <span>NEXTGEN</span></h1>
<p>Discover amazing games and explore a new world of gaming.</p>
<a href="#games" class="btn">EXPLORE GAMES</a>
</div>

<section id="games">
<h2>🔥 POPULAR GAMES</h2>
<div class="games">
<div class="card">
<div class="emoji">🎮</div>
<h3>Adventure World</h3>
<p>Explore a mysterious gaming world.</p>
<button onclick="play('Adventure World')">Play Now</button>
</div>
<div class="card">
<div class="emoji">🏎️</div>
<h3>Speed Racing</h3>
<p>Experience exciting racing action.</p>
<button onclick="play('Speed Racing')">Play Now</button>
</div>
<div class="card">
<div class="emoji">⚔️</div>
<h3>Battle Arena</h3>
<p>Enter the ultimate battle challenge.</p>
<button onclick="play('Battle Arena')">Play Now</button>
</div>
</div>
</section>

<section id="about">
<h2>ABOUT NEXTGEN</h2>
<p style="text-align:center;color:#b5bdd0">
Welcome to NextGen Gaming. Your destination for fun and adventure.
</p>
</section>

<footer>
© 2026 NextGen Gaming. All Rights Reserved.
</footer>

<script>
function play(game){
alert("Welcome to "+game+"! Game coming soon.");
}
</script>

</body>
</html>
