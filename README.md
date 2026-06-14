<!DOCTYPE html>
<html lang="so">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Somali Magazine</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f4f4f4;
}

header {
    background: linear-gradient(90deg, #0f172a, #1e3a8a);
    color: white;
    padding: 20px;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 30px;
}

nav {
    background: #111827;
    padding: 10px;
    text-align: center;
}

nav a {
    color: white;
    margin: 10px;
    text-decoration: none;
    font-weight: bold;
}

.container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 15px;
    padding: 20px;
}

.card {
    background: white;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 2px 8px rgba(0,0,0,0.2);
    transition: 0.3s;
}

.card:hover {
    transform: scale(1.03);
}

.card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
}

.card h3 {
    padding: 10px;
    margin: 0;
}

.card p {
    padding: 0 10px 10px 10px;
    font-size: 14px;
    color: #555;
}

footer {
    background: #111827;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}
</style>

</head>

<body>

<header>
    <h1>Somali Magazine 🌍</h1>
    <p>Warar • Qurux • Dhaqan • Sawiro</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">News</a>
    <a href="#">Culture</a>
    <a href="#">Gallery</a>
</nav>

<div class="container">

    <div class="card">
        <img src="https://source.unsplash.com/400x300/?somalia" alt="">
        <h3>Somalia Quruxdeeda</h3>
        <p>Dhulka Soomaaliya iyo muuqaal qurux badan.</p>
    </div>

    <div class="card">
        <img src="https://source.unsplash.com/400x300/?mogadishu" alt="">
        <h3>Mogadishu City</h3>
        <p>Caasimadda Soomaaliya ee Muqdisho.</p>
    </div>

    <div class="card">
        <img src="https://source.unsplash.com/400x300/?africa,people" alt="">
        <h3>Dhaqanka Afrika</h3>
        <p>Dad iyo dhaqan Afrika ah oo hodan ah.</p>
    </div>

    <div class="card">
        <img src="https://source.unsplash.com/400x300/?ocean,boat" alt="">
        <h3>Badda Soomaaliya</h3>
        <p>Badda dheer ee Soomaaliya iyo kalluumaysi.</p>
    </div>

</div>

<footer>
    © 2026 Somali Magazine | Designed by You
</footer>

</body>
</html>
