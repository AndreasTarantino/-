<!DOCTYPE html>
<html lang="el">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GreekLife EL.AS | Ultra Police Portal</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Segoe UI,sans-serif;
scroll-behavior:smooth;
}

body{
background:#050b14;
color:white;
}

/* TOP NAV */
nav{
position:fixed;
top:0;
width:100%;
display:flex;
justify-content:space-between;
align-items:center;
padding:16px 40px;
z-index:1000;
background:rgba(0,0,0,.35);
backdrop-filter:blur(14px);
border-bottom:1px solid rgba(255,255,255,.08);
}

.logo{
font-size:20px;
font-weight:bold;
letter-spacing:1px;
}

.menu{
display:flex;
gap:16px;
flex-wrap:wrap;
}

.menu a{
color:white;
text-decoration:none;
font-size:13px;
transition:.3s;
opacity:.85;
}

.menu a:hover{
color:#4da6ff;
opacity:1;
}

/* HERO */
.hero{
height:100vh;
background:url("https://images.unsplash.com/photo-1526778548025-fa2f459cd5c1?auto=format&fit=crop&w=1600&q=80");
background-size:cover;
background-position:center;
position:relative;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
overflow:hidden;
}

/* animated overlay */
.hero::before{
content:"";
position:absolute;
width:200%;
height:200%;
background:radial-gradient(circle,rgba(0,102,204,.25),transparent 60%);
animation:move 8s infinite linear;
}

@keyframes move{
0%{transform:translate(-20%,-20%);}
50%{transform:translate(20%,20%);}
100%{transform:translate(-20%,-20%);}
}

.overlay{
position:absolute;
top:0;
left:0;
width:100%;
height:100%;
background:rgba(0,0,0,.7);
}

.hero-content{
position:relative;
z-index:2;
animation:fadeIn 1.2s ease;
}

@keyframes fadeIn{
from{opacity:0; transform:translateY(20px);}
to{opacity:1; transform:translateY(0);}
}

.hero h1{
font-size:60px;
letter-spacing:3px;
}

.hero p{
margin-top:10px;
opacity:.8;
font-size:18px;
}

.btn{
display:inline-block;
margin-top:20px;
padding:12px 26px;
background:#0066cc;
color:white;
text-decoration:none;
border-radius:10px;
transition:.3s;
}

.btn:hover{
transform:scale(1.05);
background:#0080ff;
}

/* SECTIONS */
section{
padding:110px 20px;
background:#07101d;
}

.container{
max-width:1100px;
margin:auto;
}

h2{
text-align:center;
margin-bottom:35px;
color:#4da6ff;
font-size:28px;
}

/* CARDS */
.card{
background:rgba(15,27,45,.85);
backdrop-filter:blur(10px);
padding:25px;
border-radius:14px;
margin-bottom:20px;
border:1px solid rgba(255,255,255,.08);
transition:.3s;
}

.card:hover{
transform:translateY(-5px);
border-color:#4da6ff;
}

/* GRID */
.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(230px,1fr));
gap:15px;
}

/* SMALL TAG */
.tag{
display:inline-block;
padding:3px 10px;
font-size:12px;
background:#0b3b66;
border-radius:20px;
margin-bottom:10px;
}

</style>
</head>

<body>

<!-- NAV -->
<nav>
<div class="logo">🚔 GreekLife EL.AS</div>

<div class="menu">
<a href="#home">Αρχική</a>
<a href="#code">Κώδικας</a>
<a href="#rights">Δικαιώματα</a>
<a href="#units">Κλιμάκια</a>
<a href="#schools">Σχολές</a>
<a href="#staff">Προσωπικό</a>
<a href="YOUR_DISCORD_LINK">Discord</a>
</div>
</nav>

<!-- HERO -->
<section class="hero" id="home">
<div class="overlay"></div>

<div class="hero-content">
<h1>ΚΑΛΩΣΟΡΙΣΕΣ</h1>
<p>στην ιστοσελίδα του GreekLife EL.AS</p>

<a class="btn" href="YOUR_FIVEM_LINK">Σύνδεση Server</a>
<a class="btn" href="YOUR_DISCORD_LINK">Discord</a>
</div>
</section>

<!-- CODE -->
<section id="code">
<div class="container">
<h2>Κώδικας Δεοντολογίας</h2>

<div class="card">
<span class="tag">ΕΛ.ΑΣ SOP</span>
<p>• Υπακοή στην ιεραρχία και στους νόμους</p>
<p>• Ψυχραιμία σε όλα τα περιστατικά</p>
<p>• Σεβασμός προς πολίτες</p>
<p>• Χρήση εξοπλισμού μόνο εν υπηρεσία</p>
<p>• Επαγγελματική συμπεριφορά πάντα</p>
</div>

</div>
</section>

<!-- RIGHTS -->
<section id="rights">
<div class="container">
<h2>Δικαιώματα Πολίτη</h2>

<div class="card">
<span class="tag">Legal Protocol</span>
<p>• Δικαίωμα σιωπής</p>
<p>• Δικαίωμα δικηγόρου</p>
<p>• Δικαίωμα τηλεφωνήματος</p>
<p>• Ό,τι πείτε χρησιμοποιείται στο δικαστήριο</p>
<p>• Διαβάζονται πάντα πριν τη σύλληψη</p>
</div>

</div>
</section>

<!-- UNITS -->
<section id="units">
<div class="container">
<h2>Κλιμάκια ΕΛ.ΑΣ</h2>

<div class="grid">

<div class="card">
<h3>🚓 Α.Δ</h3>
<p>Πρώτη ανταπόκριση σε όλα τα συμβάντα.</p>
</div>

<div class="card">
<h3>🏍️ ΔΙ.ΑΣ</h3>
<p>Ταχεία επέμβαση και καταδιώξεις.</p>
</div>

<div class="card">
<h3>🛡️ Ο.Π.Κ.Ε</h3>
<p>Υψηλού κινδύνου επιχειρήσεις.</p>
</div>

<div class="card">
<h3>⚔️ Ε.Κ.Α.Μ</h3>
<p>Αντιτρομοκρατικές αποστολές.</p>
</div>

</div>

</div>
</section>

<!-- SCHOOLS -->
<section id="schools">
<div class="container">
<h2>Σχολές ΕΛ.ΑΣ</h2>

<div class="card">
<h3>Σχολή Δοκίμων Αστυφυλάκων</h3>
<p>Βασική εκπαίδευση νέων αστυνομικών.</p>
</div>

<div class="card">
<h3>Σχολή Αξιωματικών</h3>
<p>Ανώτερη εκπαίδευση και ηγεσία.</p>
</div>

</div>
</section>

<!-- STAFF -->
<section id="staff">
<div class="container">
<h2>Διοίκηση</h2>

<div class="card">
<h3>👮 Διοικητής ΕΛ.ΑΣ</h3>
<p>Andreas Tarantino</p>
</div>

</div>
</section>

</body>
</html>
