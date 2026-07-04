<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NovaTeam</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,Helvetica,sans-serif;
}

body{
background:linear-gradient(135deg,#050505,#150022,#2d0057,#090909);
background-size:400% 400%;
animation:bg 12s ease infinite;
color:white;
}

@keyframes bg{
0%{background-position:0% 50%;}
50%{background-position:100% 50%;}
100%{background-position:0% 50%;}
}

header{
padding:40px;
text-align:center;
}

.logo{
font-size:70px;
font-weight:bold;
color:#d600ff;
text-shadow:
0 0 5px #d600ff,
0 0 10px #d600ff,
0 0 20px #d600ff,
0 0 40px #9d00ff,
0 0 80px #9d00ff;
animation:neon 2s infinite alternate;
}

@keyframes neon{
from{
text-shadow:
0 0 5px #d600ff,
0 0 10px #d600ff,
0 0 20px #d600ff;
}
to{
text-shadow:
0 0 10px #d600ff,
0 0 25px #d600ff,
0 0 50px #d600ff,
0 0 90px #9d00ff;
}
}

h2{
margin-top:10px;
color:#ddd;
}

.container{
width:90%;
margin:auto;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(350px,1fr));
gap:30px;
padding:40px;
}

.video{
width:100%;
height:220px;
border-radius:15px;
background:black;
}

.video:hover{
transform:scale(1.05);
box-shadow:0 0 35px #c000ff;
}

iframe{
width:100%;
height:220px;
border:none;
border-radius:15px;
}

p{
margin-top:10px;
text-align:center;
font-size:18px;
}

footer{
padding:30px;
text-align:center;
color:#aaa;
}
</style>

</head>

<body>

<header>

<div class="logo">NOVATEAM</div>

<h2>🔥 Les meilleures vidéos Fortnite 🔥</h2>

</header>

<div class="container">

<div class="video">
<iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ"></iframe>
<p>Vidéo Fortnite 1</p>
</div>

<div class="video">
<iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ"></iframe>
<p>Vidéo Fortnite 2</p>
</div>

<div class="video">
<iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ"></iframe>
<p>Vidéo Fortnite 3</p>
</div>

</div>

<footer>
© 2026 NOVATEAM - Fortnite Highlights
</footer>

</body>
</html>
