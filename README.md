<!DOCTYPE html>
<html lang="el">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ΕΛ.ΑΣ | Ελληνική Αστυνομία</title>

<style>
:root{
--primary:#003b7a;
--secondary:#0057b8;
--dark:#08111f;
--light:#f5f7fa;
}

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Segoe UI',sans-serif;
scroll-behavior:smooth;
}

body{
background:#0a1424;
color:white;
line-height:1.6;
}

nav{
position:fixed;
top:0;
width:100%;
background:rgba(0,0,0,.85);
backdrop-filter:blur(10px);
z-index:1000;
}

.nav-container{
max-width:1200px;
margin:auto;
display:flex;
justify-content:space-between;
align-items:center;
padding:15px 20px;
}

.logo{
font-size:1.5rem;
font-weight:bold;
color:#fff;
}

.nav-links a{
color:white;
text-decoration:none;
margin-left:20px;
transition:.3s;
}

.nav-links a:hover{
color:#4da6ff;
}

.hero{
height:100vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
background:
linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)),
url('https://images.unsplash.com/photo-1517841905240-472988babdf9?auto=format&fit=crop&w=1600&q=80');
background-size:cover;
background-position:center;
}

.hero-content h1{
font-size:4rem;
margin-bottom:15px;
}

.hero-content p{
font-size:1.3rem;
margin-bottom:25px;
}

.btn{
display:inline-block;
padding:14px 30px;
background:var(--secondary);
color:white;
text-decoration:none;
border-radius:8px;
font-weight:bold;
transition:.3s;
}

.btn:hover{
background:#0077ff;
transform:translateY(-2px);
}

section{
padding:90px 20px;
}

.container{
max-width:1200px;
margin:auto;
}

.section-title{
text-align:center;
font-size:2.3rem;
margin-bottom:50px;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:#121f33;
padding:30px;
border-radius:12px;
border:1px solid #1f3352;
transition:.3s;
}

.card:hover{
transform:translateY(-5px);
}

.card h3{
margin-bottom:15px;
color:#66b3ff;
}

.staff-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:25px;
}

.staff{
background:#121f33;
padding:25px;
border-radius:12px;
text-align:center;
}

.staff h3{
color:#66b3ff;
margin-bottom:10px;
}

.contact{
text-align:center;
}

footer{
background:#050b15;
padding:30px;
text-align:center;
border-top:1px solid #1d2f4a;
}

@media(max-width:768px){

.hero-content h1{
font-size:2.5rem;
}

.nav-links{
display:none;
}

}
</style>
</head>
<body>

<nav>
<div class="nav-container">
<div class="logo">🚔 ΕΛ.ΑΣ</div>

<div class="nav-links">
<a href="#about">Αρχική</a>
<a href="#services">Υπηρεσίες</a>
<a href="#staff">Διοίκηση</a>
<a href="#contact">Επικοινωνία</a>
</div>
</div>
</nav>

<section class="hero">

<div class="hero-content">

<h1>ΕΛ.ΑΣ</h1>

<p>Ελληνική Αστυνομία - FiveM Roleplay Community</p>

<a href="https://discord.gg/ΒΑΛΕ-ΤΟ-LINK-ΣΟΥ" class="btn">
Σύνδεση στο Discord
</a>

</div>

</section>

<section id="about">

<div class="container">

<h2 class="section-title">Σχετικά με την Υπηρεσία</h2>

<div class="cards">

<div class="card">
<h3>🚓 Περιπολίες</h3>
<p>24ωρη αστυνόμευση και άμεση ανταπόκριση σε περιστατικά.</p>
</div>

<div class="card">
<h3>⚖️ Τήρηση Νόμου</h3>
<p>Εφαρμογή της νομοθεσίας και προστασία των πολιτών.</p>
</div>

<div class="card">
<h3>📞 Άμεση Επέμβαση</h3>
<p>Γρήγορη κινητοποίηση σε συμβάντα υψηλής προτεραιότητας.</p>
</div>

</div>

</div>

</section>

<section id="services">

<div class="container">

<h2 class="section-title">Τμήματα</h2>

<div class="cards">

<div class="card">
<h3>👮 Ασφάλεια</h3>
<p>Έρευνες και καταπολέμηση εγκληματικότητας.</p>
</div>

<div class="card">
<h3>🚔 Τροχαία</h3>
<p>Έλεγχος κυκλοφορίας και οδική ασφάλεια.</p>
</div>

<div class="card">
<h3>🛡️ ΕΚΑΜ</h3>
<p>Ειδικές επιχειρήσεις υψηλού κινδύνου.</p>
</div>

</div>

</div>

</section>

<section id="staff">

<div class="container">

<h2 class="section-title">Διοίκηση</h2>

<div class="staff-grid">

<div class="staff">
<h3>Αρχηγός ΕΛ.ΑΣ</h3>
<p>Το Όνομά Σου</p>
</div>

<div class="staff">
<h3>Υπαρχηγός</h3>
<p>Όνομα Υπαρχηγού</p>
</div>

<div class="staff">
<h3>Διοικητής</h3>
<p>Όνομα Διοικητή</p>
</div>

</div>

</div>

</section>

<section id="contact">

<div class="container contact">

<h2 class="section-title">Επικοινωνία</h2>

<p>Discord: ΒΑΛΕ ΤΟ DISCORD ΣΟΥ</p>

<br>

<a href="https://discord.gg/ΒΑΛΕ-ΤΟ-LINK-ΣΟΥ" class="btn">
Join Discord
</a>

</div>

</section>

<footer>

<p>© 2026 ΕΛ.ΑΣ - FiveM Roleplay Server</p>

</footer>

</body>
</html>
