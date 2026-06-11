<!DOCTYPE html>

<html lang="el">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ΕΛ.ΑΣ | Ελληνική Αστυνομία FiveM</title>

<style>
:root{
--blue:#004a99;
--blue2:#0066cc;
--dark:#08101d;
--card:#101b2d;
--white:#ffffff;
}

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Segoe UI',sans-serif;
scroll-behavior:smooth;
}

body{
background:var(--dark);
color:white;
}

nav{
position:fixed;
top:0;
width:100%;
background:rgba(0,0,0,.85);
backdrop-filter:blur(10px);
z-index:1000;
}

.navbar{
max-width:1300px;
margin:auto;
display:flex;
justify-content:space-between;
align-items:center;
padding:15px 25px;
}

.logo{
font-size:28px;
font-weight:bold;
}

.menu a{
color:white;
text-decoration:none;
margin-left:20px;
font-weight:600;
}

.menu a:hover{
color:#4da6ff;
}

.hero{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
background:
linear-gradient(rgba(0,0,0,.65),rgba(0,0,0,.65)),
url("https://images.unsplash.com/photo-1517841905240-472988babdf9?auto=format&fit=crop&w=1600&q=80");
background-size:cover;
background-position:center;
}

.hero h1{
font-size:70px;
margin-bottom:15px;
}

.hero p{
font-size:22px;
margin-bottom:25px;
}

.btn{
display:inline-block;
padding:14px 28px;
margin:10px;
border-radius:10px;
text-decoration:none;
font-weight:bold;
color:white;
background:var(--blue2);
transition:.3s;
}

.btn:hover{
transform:translateY(-3px);
}

section{
padding:100px 20px;
}

.container{
max-width:1300px;
margin:auto;
}

.title{
text-align:center;
font-size:40px;
margin-bottom:50px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.card{
background:var(--card);
padding:25px;
border-radius:15px;
border:1px solid rgba(255,255,255,.1);
}

.card h3{
margin-bottom:10px;
color:#6fb6ff;
}

.staff{
text-align:center;
}

.staff img{
width:100px;
height:100px;
border-radius:50%;
margin-bottom:15px;
}

.rules li{
margin-bottom:10px;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:15px;
}

.gallery img{
width:100%;
border-radius:12px;
}

footer{
background:#050a12;
padding:30px;
text-align:center;
}

@media(max-width:768px){

.hero h1{
font-size:45px;
}

.menu{
display:none;
}

}
</style>

</head>

<body>

<nav>
<div class="navbar">
<div class="logo">🚔 ΕΛ.ΑΣ</div>

<div class="menu">
<a href="#home">Αρχική</a>
<a href="#departments">Τμήματα</a>
<a href="#ranks">Βαθμοί</a>
<a href="#staff">Προσωπικό</a>
<a href="#rules">Κανόνες</a>
<a href="#gallery">Gallery</a>
<a href="#contact">Επικοινωνία</a>
</div>
</div>
</nav>

<section class="hero" id="home">

<div>

<h1>ΕΛ.ΑΣ</h1>

<p>Ελληνική Αστυνομία FiveM Roleplay</p>

<a href="YOUR_DISCORD_LINK" class="btn">
Discord
</a>

<a href="YOUR_FIVEM_LINK" class="btn">
Σύνδεση στον Server
</a>

</div>

</section>

<section id="departments">

<div class="container">

<h2 class="title">Τμήματα</h2>

<div class="grid">

<div class="card">
<h3>🚓 Τροχαία</h3>
<p>Έλεγχος κυκλοφορίας και παραβάσεων.</p>
</div>

<div class="card">
<h3>👮 Ασφάλεια</h3>
<p>Έρευνες και καταπολέμηση εγκληματικότητας.</p>
</div>

<div class="card">
<h3>🛡️ ΕΚΑΜ</h3>
<p>Ειδικές επιχειρήσεις υψηλού κινδύνου.</p>
</div>

<div class="card">
<h3>⚡ ΔΙ.ΑΣ</h3>
<p>Άμεση ανταπόκριση σε συμβάντα.</p>
</div>

</div>

</div>

</section>

<section id="ranks">

<div class="container">

<h2 class="title">Βαθμοί</h2>

<div class="grid">

<div class="card">Αρχηγός ΕΛ.ΑΣ</div>
<div class="card">Υπαρχηγός</div>
<div class="card">Ταξίαρχος</div>
<div class="card">Αστυνομικός Διευθυντής</div>
<div class="card">Αστυνόμος Α'</div>
<div class="card">Αστυνόμος Β'</div>
<div class="card">Υπαστυνόμος</div>
<div class="card">Αρχιφύλακας</div>
<div class="card">Αστυφύλακας</div>

</div>

</div>

</section>

<section id="staff">

<div class="container">

<h2 class="title">Διοίκηση</h2>

<div class="grid">

<div class="card staff">
<h3>Αρχηγός</h3>
<p>Το Όνομά Σου</p>
</div>

<div class="card staff">
<h3>Υπαρχηγός</h3>
<p>Όνομα</p>
</div>

<div class="card staff">
<h3>Διοικητής</h3>
<p>Όνομα</p>
</div>

</div>

</div>

</section>

<section id="rules">

<div class="container">

<h2 class="title">Κανόνες</h2>

<div class="card">

<ul class="rules">
<li>Σεβασμός προς όλους τους παίκτες.</li>
<li>Απαγορεύεται η κατάχρηση εξουσίας.</li>
<li>Υποχρεωτικό σοβαρό Roleplay.</li>
<li>Χρήση ασυρμάτου κατά την υπηρεσία.</li>
<li>Τήρηση SOP της υπηρεσίας.</li>
</ul>

</div>

</div>

</section>

<section id="gallery">

<div class="container">

<h2 class="title">Gallery</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1494905998402-395d579af36f">
<img src="https://images.unsplash.com/photo-1502877338535-766e1452684a">
<img src="https://images.unsplash.com/photo-1503376780353-7e6692767b70">

</div>

</div>

</section>

<section id="contact">

<div class="container">

<h2 class="title">Επικοινωνία</h2>

<div class="card">

<p>Discord Server: YOUR_DISCORD_LINK</p>
<br>
<p>Υποστήριξη μέσω Discord Tickets.</p>

</div>

</div>

</section>

<footer>
© 2026 ΕΛ.ΑΣ FiveM Roleplay Community
</footer>

</body>
</html>


</footer>

</body>
</html>
