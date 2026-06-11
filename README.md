<!DOCTYPE html>
<html lang="el">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ΕΛ.ΑΣ | Greek RP Police Portal</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Segoe UI,sans-serif;
scroll-behavior:smooth;
}

body{
background:#000;
color:white;
}

/* BACKGROUND */
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
}

.overlay{
position:absolute;
top:0;
left:0;
width:100%;
height:100%;
background:rgba(0,0,0,.65);
}

/* NAV */
nav{
position:fixed;
top:0;
width:100%;
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 40px;
z-index:10;
background:rgba(0,0,0,.3);
backdrop-filter:blur(10px);
}

.logo{
font-size:20px;
font-weight:bold;
}

.menu{
display:flex;
gap:20px;
}

.menu a{
color:white;
text-decoration:none;
font-weight:500;
transition:.3s;
}

.menu a:hover{
color:#4da6ff;
}

/* CENTER */
.center{
position:relative;
z-index:2;
color:white;
}

.center h1{
font-size:60px;
letter-spacing:3px;
}

.center p{
font-size:18px;
opacity:.8;
margin-top:10px;
}

.btns{
margin-top:25px;
}

.btn{
display:inline-block;
padding:12px 25px;
margin:10px;
background:#0066cc;
color:white;
text-decoration:none;
border-radius:8px;
transition:.3s;
}

.btn:hover{
transform:scale(1.05);
background:#0080ff;
}

/* SECTIONS */
section{
padding:100px 20px;
background:#0b111a;
}

.container{
max-width:1100px;
margin:auto;
}

h2{
text-align:center;
margin-bottom:40px;
color:#4da6ff;
}

.card{
background:#121c2a;
padding:25px;
border-radius:12px;
margin-bottom:20px;
border:1px solid #1f2d40;
}

/* GRID */
.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

</style>
</head>

<body>

<!-- NAV -->
<nav>
<div class="logo">🚔 ΕΛ.ΑΣ PORTAL</div>

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
<div class="hero" id="home">
<div class="overlay"></div>

<div class="center">
<h1>ΕΛΛΗΝΙΚΗ ΑΣΤΥΝΟΜΙΑ</h1>
<p>FiveM Roleplay Official Police Portal</p>

<div class="btns">
<a class="btn" href="YOUR_FIVEM_LINK">Σύνδεση Server</a>
<a class="btn" href="YOUR_DISCORD_LINK">Discord</a>
</div>
</div>
</div>

<!-- CODE -->
<section id="code">
<div class="container">
<h2>Κώδικας Δεοντολογίας</h2>

<div class="card">
<p>1. Ο κάθε αστυνομικός υπακούει τους νόμους.</p>
<p>2. Διατηρεί ψυχραιμία σε κάθε κατάσταση.</p>
<p>3. Σέβεται τους πολίτες και λειτουργεί επαγγελματικά.</p>
<p>4. Τηρεί την ιεραρχία χωρίς αντίρρηση.</p>
<p>5. Χρήση εξοπλισμού μόνο εν ώρα υπηρεσίας.</p>
</div>

</div>
</section>

<!-- RIGHTS -->
<section id="rights">
<div class="container">
<h2>Δικαιώματα Πολίτη</h2>

<div class="card">
<p>• Δικαίωμα σιωπής</p>
<p>• Δικαίωμα δικηγόρου</p>
<p>• Δικαίωμα τηλεφωνήματος</p>
<p>• Ό,τι πείτε μπορεί να χρησιμοποιηθεί στο δικαστήριο</p>
<p>• Τα δικαιώματα διαβάζονται πάντα πριν τη διαδικασία</p>
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
<p>Άμεση Δράση – πρώτη ανταπόκριση σε συμβάντα.</p>
</div>

<div class="card">
<h3>🏍️ ΔΙ.ΑΣ</h3>
<p>Ταχεία επέμβαση και καταδιώξεις.</p>
</div>

<div class="card">
<h3>🛡️ Ο.Π.Κ.Ε</h3>
<p>Ειδικές επιχειρήσεις υψηλού κινδύνου.</p>
</div>

<div class="card">
<h3>⚔️ Ε.Κ.Α.Μ</h3>
<p>Αντιτρομοκρατικές και κρίσιμες αποστολές.</p>
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
<p>Εκπαίδευση νέων αστυνομικών με θεωρία και πρακτική.</p>
</div>

<div class="card">
<h3>Σχολή Αξιωματικών</h3>
<p>Ανώτερη εκπαίδευση στελεχών και ηγεσίας.</p>
</div>

</div>
</section>

<!-- STAFF -->
<section id="staff">
<div class="container">
<h2>Προσωπικό</h2>

<div class="card">
<h3>Διοικητής ΕΛ.ΑΣ</h3>
<p>Andreas Tarantino</p>
</div>

</div>
</section>

</body>
</html>
