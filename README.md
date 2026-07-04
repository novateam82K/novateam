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

/* BUTTONS */
.btn{
display:inline-block;
margin:10px;
padding:12px 20px;
color:white;
text-decoration:none;
font-weight:bold;
border-radius:12px;
box-shadow:0 0 15px rgba(255,255,255,0.2);
transition:0.3s;
}

/* DISCORD */
.discord-btn{
background:#5865F2;
}
.discord-btn:hover{
transform:scale(1.1);
box-shadow:0 0 25px #5865F2;
}

/* TIKTOK */
.tiktok-btn{
background:#000;
border:2px solid #ff2d55;
}
.tiktok-btn:hover{
transform:scale(1.1);
box-shadow:0 0 25px #ff2d55;
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

<!-- BOUTONS -->
<a href="https://discord.gg/REVmqPTNx" target="_blank" class="btn discord-btn">
  NOVATEAM ➜ Discord
</a>

<a href="https://www.tiktok.com/@la.nova.team/video/7658716192722439457?is_from_webapp=1&sender_device=pc" target="_blank" class="btn tiktok-btn">
  NOVATEAM ➜ TikTok
</a>

</header>

<div class="container">

<!-- VIDEO 1 -->
<div class="video">
<iframe 
src="https://www.youtube.com/embed/5LEm5RSSpfU"
allowfullscreen>
</iframe>
<p>Vidéo Fortnite 1</p>
</div>

<!-- VIDEO 2 -->
<div class="video">
<iframe 
src="https://www.youtube.com/embed/SBDcIFwWiHY"
allowfullscreen>
</iframe>
<p>Vidéo Fortnite 2</p>
</div>

</div>

<footer>
© 2026 NOVATEAM - Fortnite Highlights
</footer>

</body>
</html>
