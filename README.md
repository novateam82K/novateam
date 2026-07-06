
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>knos</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,Helvetica,sans-serif;
}

body{
background:#000;
color:#fff;
}

/* HEADER */
header{
padding:40px;
text-align:center;
border-bottom:1px solid #333;
}

.logo{
font-size:70px;
font-weight:bold;
color:#fff;
letter-spacing:4px;
text-shadow:0 0 10px #fff;
}

h2{
margin-top:10px;
color:#bbb;
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
border:1px solid #fff;
}

.btn:hover{
transform:scale(1.08);
box-shadow:0 0 15px #fff;
}

/* DISCORD */
.discord-btn{
background:#111;
}

/* TIKTOK */
.tiktok-btn{
background:#000;
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
background:#0a0a0a;
border:1px solid #444;
border-radius:20px;
padding:15px;
transition:0.3s;
}

.video:hover{
transform:scale(1.03);
border-color:#fff;
}

iframe{
width:100%;
height:220px;
border:none;
border-radius:15px;
filter:grayscale(100%);
}

p{
margin-top:10px;
text-align:center;
font-size:18px;
color:#ccc;
}

footer{
padding:30px;
text-align:center;
color:#666;
border-top:1px solid #333;
}
</style>

</head>

<body>

<header>

<div class="logo">KNOS</div>
<h2>🔥 Best Fortnite Highlights 🔥</h2>

<a href="https://discord.gg/REVmqPTNx" target="_blank" class="btn discord-btn">
  KNOS ➜ Discord
</a>

<a href="https://www.tiktok.com/@la.nova.team/video/7658716192722439457?is_from_webapp=1&sender_device=pc" target="_blank" class="btn tiktok-btn">
  KNOS ➜ TikTok
</a>

</header>

<div class="container">

<div class="video">
<iframe src="https://www.youtube.com/embed/5LEm5RSSpfU" allowfullscreen></iframe>
<p>Fortnite Video 1</p>
</div>

<div class="video">
<iframe src="https://www.youtube.com/embed/SBDcIFwWiHY" allowfullscreen></iframe>
<p>Fortnite Video 2</p>
</div>

</div>

<footer>
© 2026 KNOS - Fortnite Highlights
</footer>

</body>
</html>
