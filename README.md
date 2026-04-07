# mj-auto-service
<!DOCTYPE html>
<html lang="ms">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MJ Auto Service</title>

<style>
body {
    margin: 0;
    font-family: Arial;
    background: #0d0d0d;
    color: white;
}

/* Header */
header {
    background: black;
    text-align: center;
    padding: 20px;
    border-bottom: 2px solid red;
}

/* Nav */
nav {
    background: #111;
    text-align: center;
    padding: 10px;
}

nav a {
    color: white;
    margin: 10px;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    color: red;
}

/* Hero */
.hero {
    padding: 80px 20px;
    background: linear-gradient(to right, black, #1a1a1a);
    text-align: center;
}

.hero h2 {
    font-size: 30px;
}

.btn {
    display: inline-block;
    margin-top: 20px;
    padding: 12px 25px;
    background: red;
    color: white;
    text-decoration: none;
    border-radius: 30px;
}

/* Section */
section {
    padding: 50px 20px;
    text-align: center;
}

h2 {
    color: red;
}

/* Cards */
.card-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

.card {
    background: #111;
    margin: 10px;
    padding: 20px;
    border-radius: 15px;
    border: 1px solid red;
    width: 200px;
}

/* Social */
.social a {
    display: inline-block;
    margin: 10px;
    padding: 12px 25px;
    border-radius: 30px;
    background: #111;
    border: 1px solid red;
    color: white;
    text-decoration: none;
}

.social a:hover {
    background: red;
    color: black;
}

/* Footer */
footer {
    background: black;
    padding: 10px;
    text-align: center;
}

/* WhatsApp Floating */
.wa {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: green;
    color: white;
    padding: 15px;
    border-radius: 50%;
    text-decoration: none;
    font-size: 20px;
}
</style>

</head>

<body>

<header>
    <h1>MJ AUTO SERVICE</h1>
    <p>Professional Automotive Repair & Service</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
</nav>

<section id="home" class="hero">
    <h2>Servis Kereta Profesional</h2>
    <p>Pakar Enjin • Aircond • Wiring • Diagnose ECU</p>
    <a href="https://wa.me/601116121092" class="btn">WhatsApp Sekarang</a>
</section>

<section id="about">
    <h2>Tentang Kami</h2>
    <p>MJ Auto Service menyediakan servis automotif berkualiti tinggi dengan pengalaman dalam pembaikan enjin, aircond dan wiring. Kepuasan pelanggan adalah keutamaan kami.</p>
</section>

<section id="services">
    <h2>Servis Kami</h2>
    <div class="card-container">
        <div class="card">🔧 Servis Enjin</div>
        <div class="card">❄️ Baiki Aircond</div>
        <div class="card">⚡ Wiring & Elektrikal</div>
        <div class="card">🚗 Tune Up</div>
        <div class="card">💻 Diagnose ECU</div>
    </div>
</section>

<section id="contact">
    <h2>Hubungi Kami</h2>
    <p>📍 Sarawak</p>
    <p>📞 WhatsApp: +6011-1612 1092</p>

    <div class="social">
        <a href="https://tiktok.com/@mjautoservice15" target="_blank">🚗 TikTok</a>
        <a href="https://www.facebook.com/share/1DWe9G4a9A/" target="_blank">🔵 Facebook</a>
        <a href="https://www.instagram.com/mjautoservice.15?igsh=MTR2bTc3aXF4b2trMw==" target="_blank">📸 Instagram</a>
    </div>
</section>

<footer>
    <p>© 2026 MJ Auto Service</p>
</footer>

<!-- WhatsApp Floating -->
<a href="https://wa.me/601116121092" class="wa">💬</a>

</body>
</html>
