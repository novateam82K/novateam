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
transition:0.3s;
}

.discord{background:#5865F2;}
.tiktok{background:#000;border:2px solid #ff2d55;}

.btn:hover{
transform:scale(1.1);
}

/* SECTIONS */
.section{
width:90%;
margin:auto;
padding:30px;
}

.card{
background:rgba(255,255,255,0.08);
border:2px solid #a000ff;
border-radius:20px;
padding:20px;
margin-top:20px;
box-shadow:0 0 20px rgba(160,0,255,0.3);
}

/* VIDEOS */
.container{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:25px;
padding:20px;
}

iframe{
width:100%;
height:220px;
border:none;
border-radius:15px;
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
<h2>🔥 Fortnite Highlights + Tournois 🔥</h2>

<a href="https://discord.gg/REVmqPTNx" target="_blank" class="btn discord">
NOVATEAM ➜ Discord
</a>

<a href="https://www.tiktok.com/@la.nova.team/video/7658716192722439457?is_from_webapp=1&sender_device=pc" target="_blank" class="btn tiktok">
NOVATEAM ➜ TikTok
</a>

</header>

<!-- VIDEOS -->
<div class="section">
<h2>🎥 Vidéos Fortnite</h2>

<div class="container">

<div class="card">
<iframe src="https://www.youtube.com/embed/5LEm5RSSpfU" allowfullscreen></iframe>
<p>Vidéo Fortnite 1</p>
</div>

<div class="card">
<iframe src="https://www.youtube.com/embed/SBDcIFwWiHY" allowfullscreen></iframe>
<p>Vidéo Fortnite 2</p>
</div>

</div>
</div>

<!-- TOURNOIS -->
<div class="section">
<h2>🏆 Tournois Fortnite Duos</h2>

<div class="card">
<p>🔥 Début : 18h00</p>
<p>🎮 Mode : Duos</p>
<p>💰 Récompense : À définir</p>
<p>📍 Serveur : Europe</p>
</div>

<div class="card">
<p>🔥 Début : 20h30</p>
<p>🎮 Mode : Duos Arena</p>
<p>💰 Récompense : Cash / Gift</p>
<p>📍 Serveur : Europe</p>
</div>

</div>

<!-- DEMAIN -->
<div class="section">
<h2>📅 Section du lendemain</h2>

<div class="card">
<p>🕒 Programme à venir :</p>
<p>🎥 Nouvelle vidéo Fortnite</p>
<p>🏆 Nouveau tournoi Duos</p>
<p>🔥 Event spécial NovaTeam</p>
</div>

</div>

<footer>
© 2026 NOVATEAM - Fortnite Highlights
</footer>

</body>
</html>
