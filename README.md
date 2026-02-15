<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Raka Laundry</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:#F5FAFF;
    color:#0B2545;
}

/* NAVBAR */
header{
    background:#0B2545;
    padding:20px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

header h1{
    color:white;
    font-weight:700;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:25px;
    font-weight:500;
}

/* HERO */
.hero{
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:80px 8%;
    flex-wrap:wrap;
    background:linear-gradient(135deg,#0B2545,#2E8BC0);
    color:white;
}

.hero-text{
    max-width:500px;
}

.hero h2{
    font-size:44px;
    margin-bottom:20px;
}

.hero p{
    margin-bottom:25px;
    line-height:1.6;
}

.hero img{
    width:500px;
    border-radius:20px;
    box-shadow:0 20px 40px rgba(0,0,0,0.3);
}

/* BUTTON */
.btn{
    padding:14px 30px;
    background:white;
    color:#0B2545;
    border-radius:30px;
    text-decoration:none;
    font-weight:600;
    transition:0.3s;
}

.btn:hover{
    background:#BFD7ED;
}

/* SECTION */
.section{
    padding:80px 8%;
    text-align:center;
}

.section h3{
    font-size:32px;
    margin-bottom:20px;
}

/* PRICE */
.price-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    padding:25px;
    border-radius:20px;
    box-shadow:0 10px 25px rgba(0,0,0,0.08);
    transition:0.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card h4{
    color:#2E8BC0;
    margin-bottom:8px;
}

/* CONTACT */
.contact{
    background:#0B2545;
    color:white;
    padding:70px 8%;
    text-align:center;
}

.contact a{
    display:inline-block;
    margin-top:20px;
    padding:14px 30px;
    background:#2E8BC0;
    color:white;
    border-radius:30px;
    text-decoration:none;
    font-weight:600;
}

/* FLOAT WA */
.wa-float{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:white;
    padding:15px 18px;
    border-radius:50%;
    font-size:22px;
    text-decoration:none;
    box-shadow:0 8px 20px rgba(0,0,0,0.2);
}

footer{
    background:#061726;
    color:white;
    text-align:center;
    padding:20px;
}

/* RESPONSIVE */
@media(max-width:768px){
    .hero{
        text-align:center;
    }
    .hero img{
        margin-top:40px;
        width:100%;
    }
}
</style>
</head>

<body>

<header>
    <h1>Raka Laundry</h1>
    <nav>
        <a href="#tentang">Tentang</a>
        <a href="#harga">Harga</a>
        <a href="#kontak">Kontak</a>
    </nav>
</header>

<section class="hero">
    <div class="hero-text">
        <h2>Laundry Cepat & Bersih ✨</h2>
        <p>Raka Laundry melayani cuci, setrika, hingga item khusus dengan hasil bersih, wangi, dan rapi. Gratis antar jemput area Pare & sekitarnya.</p>
        <a href="https://wa.me/6282331066999" class="btn">Chat WhatsApp</a>
    </div>

    <!-- GANTI NAMA FILE SESUAI FILE GAMBAR LO -->
    <img src="laundry-hero.jpg" alt="Raka Laundry">
</section>

<section class="section" id="tentang">
    <h3>Tentang Kami</h3>
    <p>
        Raka Laundry berlokasi di Jl. Soekarno Hatta No.108, Ngeblek, Pelem, 
        Kec. Pare, Kabupaten Kediri, Jawa Timur 64213. 
        Kami menyediakan layanan laundry profesional dengan harga terjangkau dan pelayanan ramah.
    </p>
</section>

<section class="section" id="harga">
    <h3>Price List</h3>
    <div class="price-grid">
        <div class="card"><h4>Cuci + Setrika</h4><p>Rp 6.000 / kg</p></div>
        <div class="card"><h4>Cuci Kering</h4><p>Rp 5.000 / kg</p></div>
        <div class="card"><h4>Setrika</h4><p>Rp 5.000 / kg</p></div>
        <div class="card"><h4>Karpet</h4><p>Mulai Rp 7.500 / meter</p></div>
        <div class="card"><h4>Sofa/Kursi</h4><p>Mulai Rp 60.000</p></div>
        <div class="card"><h4>Sepatu</h4><p>Mulai Rp 20.000</p></div>
        <div class="card"><h4>Tas</h4><p>Mulai Rp 10.000</p></div>
        <div class="card"><h4>Bedcover</h4><p>Mulai Rp 15.000</p></div>
        <div class="card"><h4>Jas Lengkap</h4><p>Mulai Rp 30.000</p></div>
        <div class="card"><h4>Springbed</h4><p>Mulai Rp 170.000</p></div>
        <div class="card"><h4>Gorden</h4><p>Rp 20.000 / kg</p></div>
        <div class="card"><h4>Bantal/Guling</h4><p>Mulai Rp 25.000</p></div>
        <div class="card"><h4>Helm</h4><p>Rp 25.000</p></div>
        <div class="card"><h4>Trolley</h4><p>Mulai Rp 60.000</p></div>
    </div>
</section>

<section class="contact" id="kontak">
    <h3>Hubungi Kami</h3>
    <p>Gratis Antar Jemput 🚚</p>
    <p>Jl. Soekarno Hatta No.108, Pare, Kediri</p>
    <a href="https://wa.me/6282331066999">Klik Chat WhatsApp</a>
</section>

<a href="https://wa.me/6282331066999" class="wa-float">💬</a>

<footer>
    © 2026 Raka Laundry
</footer>

</body>
</html>
