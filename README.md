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
text-shadow:0 0 10px #d600ff,0 0 30px #9d00ff;
}

h2{
margin-top:10px;
color:#ddd;
}

/* DISCORD BUTTON */
.discord-btn{
display:inline-block;
margin-top:20px;
padding:12px 20px;
background:#5865F2;
color:white;
text-decoration:none;
font-weight:bold;
border-radius:12px;
box-shadow:0 0 15px #5865F2aa;
transition:0.3s;
}

.discord-btn:hover{
transform:scale(1.1);
box-shadow:0 0 25px #5865F2;
}

/* VIDEOS */
.container{
width:90%;
margin:auto;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:25px;
padding:40px;
}

.video{
background:rgba(255,255,255,0.08);
border:2px solid #a000ff;
border-radius:20px;
padding:15px;
transition:0.3s;
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

video{
width:100%;
height:220px;
border-radius:15px;
background:black;
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

<!-- DISCORD BUTTON -->
<a href="https://discord.gg/REVmqPTNx" target="_blank" class="discord-btn">
  NOVATEAM ➜ Discord
</a>

</header>

<div class="container">

<!-- VIDEO 1 YOUTUBE -->
<div class="video">
<iframe src="https://www.youtube.com/embed/hAj4zeE5csA" allowfullscreen></iframe>
<p>Vidéo Fortnite 1</p>
</div>

<!-- VIDEO 2 DISCORD -->
<div class="video">
<video controls>
<source src="https://cdn.discordapp.com/attachments/1522993788262547648/1523016416016728215/8bb640d40214ada19dd1b097667d3821.mp4" type="video/mp4">
</video>
<p>Vidéo Fortnite 2</p>
</div>

</div>

<footer>
© 2026 NOVATEAM - Fortnite Highlights
</footer>

</body>
</html>
