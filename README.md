<!DOCTYPE html>
<html lang="so">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Somali News Magazine</title>
<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#f4f4f4;
}
header{
    background:#0d47a1;
    color:white;
    padding:20px;
    text-align:center;
}
nav{
    background:#1565c0;
    padding:10px;
    text-align:center;
}
nav a{
    color:white;
    text-decoration:none;
    margin:0 15px;
}
.hero{
    background:white;
    margin:20px;
    padding:20px;
    border-radius:10px;
}
.news-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
    margin:20px;
}
.card{
    background:white;
    padding:15px;
    border-radius:10px;
    box-shadow:0 2px 5px rgba(0,0,0,0.1);
}
footer{
    background:#0d47a1;
    color:white;
    text-align:center;
    padding:15px;
    margin-top:20px;
}
</style>
</head>
<body>

<header>
<h1>Somali News Magazine</h1>
<p>Wararka Soomaaliya iyo Caalamka</p>
</header>

<nav>
<a href="#">Home</a>
<a href="#">Politics</a>
<a href="#">Business</a>
<a href="#">Sports</a>
<a href="#">Technology</a>
<a href="#">Contact</a>
</nav>

<div class="hero">
<h2>War Deg Deg Ah</h2>
<p>Ku soo dhawoow Somali News Magazine. Halkan waxaad ka heli doontaa wararkii ugu dambeeyey.</p>
</div>

<div class="news-grid">
<div class="card">
<h3>Siyaasadda</h3>
<p>Wararkii ugu dambeeyey ee siyaasadda Soomaaliya.</p>
</div>

<div class="card">
<h3>Ciyaaraha</h3>
<p>Natiijooyinka iyo wararka kubadda cagta.</p>
</div>

<div class="card">
<h3>Ganacsiga</h3>
<p>Falanqayn iyo warar dhaqaale.</p>
</div>

<div class="card">
<h3>Teknoolojiyadda</h3>
<p>Wararka AI, internet-ka iyo tiknoolajiyada cusub.</p>
</div>
</div>

<footer>
© 2026 Somali News Magazine
</footer>

</body>
</html>
