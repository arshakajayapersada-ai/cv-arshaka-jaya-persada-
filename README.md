# cv-arshaka-jaya-persada-
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>CV ARSHAKA JAYA PERSADA | Konsultan Perizinan & Sertifikasi</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<style>

:root{
    --navy:#0b1f3a;
    --gold:#d4af37;
    --light:#f5f7fa;
    --dark:#222;
}

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    color:var(--dark);
    background:#fff;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
}

header{
    position:fixed;
    width:100%;
    top:0;
    z-index:999;
    background:rgba(11,31,58,.95);
    backdrop-filter:blur(10px);
}

.navbar{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:18px 0;
}

.logo{
    color:#fff;
    font-size:24px;
    font-weight:800;
}

.logo span{
    color:var(--gold);
}

nav ul{
    display:flex;
    list-style:none;
    gap:30px;
}

nav a{
    text-decoration:none;
    color:#fff;
    font-weight:500;
}

.btn{
    background:var(--gold);
    color:#000;
    padding:12px 24px;
    border-radius:30px;
    text-decoration:none;
    font-weight:600;
    transition:.3s;
}

.btn:hover{
    transform:translateY(-3px);
}

.hero{
    min-height:100vh;
    background:
    linear-gradient(rgba(11,31,58,.8),rgba(11,31,58,.8)),
    url('https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?auto=format&fit=crop&w=1600&q=80');
    background-size:cover;
    background-position:center;
    display:flex;
    align-items:center;
    color:#fff;
}

.hero-content{
    max-width:700px;
}

.hero h1{
    font-size:60px;
    line-height:1.1;
    margin-bottom:20px;
}

.hero h1 span{
    color:var(--gold);
}

.hero p{
    font-size:20px;
    margin-bottom:30px;
}

.hero-buttons{
    display:flex;
    gap:15px;
    flex-wrap:wrap;
}

.btn-outline{
    border:2px solid #fff;
    color:#fff;
    padding:12px 24px;
    border-radius:30px;
    text-decoration:none;
}

.stats{
    margin-top:50px;
    display:flex;
    gap:50px;
    flex-wrap:wrap;
}

.stat h3{
    color:var(--gold);
    font-size:32px;
}

section{
    padding:100px 0;
}

.section-title{
    text-align:center;
    margin-bottom:50px;
}

.section-title h2{
    font-size:40px;
    color:var(--navy);
}

.features{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.feature{
    background:#fff;
    padding:30px;
    border-radius:15px;
    box-shadow:0 10px 25px rgba(0,0,0,.08);
    text-align:center;
}

.services{
    background:var(--light);
}

.service-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:25px;
}

.service-card{
    background:#fff;
    padding:30px;
    border-radius:15px;
    box-shadow:0 10px 25px rgba(0,0,0,.08);
}

.service-card h3{
    color:var(--navy);
    margin-bottom:10px;
}

.process{
    background:var(--navy);
    color:#fff;
}

.process-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
    gap:20px;
    text-align:center;
}

.step{
    padding:20px;
}

.number{
    width:60px;
    height:60px;
    background:var(--gold);
    border-radius:50%;
    display:flex;
    justify-content:center;
    align-items:center;
    margin:auto;
    color:#000;
    font-weight:bold;
    margin-bottom:15px;
}

.portfolio-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.portfolio-item{
    background:#fff;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 10px 20px rgba(0,0,0,.08);
}

.portfolio-item img{
    width:100%;
    height:220px;
    object-fit:cover;
}

.portfolio-item h4{
    padding:15px;
}

.testimonials{
    background:var(--light);
}

.testimonial-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:20px;
}

.testimonial{
    background:#fff;
    padding:30px;
    border-radius:15px;
}

.faq-item{
    margin-bottom:15px;
}

.faq-question{
    background:var(--navy);
    color:#fff;
    padding:15px;
    cursor:pointer;
}

.faq-answer{
    display:none;
    padding:15px;
    border:1px solid #ddd;
}

.cta{
    background:linear-gradient(135deg,var(--navy),#143b6d);
    color:#fff;
    text-align:center;
}

footer{
    background:#081526;
    color:#fff;
    padding:50px 0;
}

.footer-grid{
    display:grid;
    grid-template-columns:2fr 1fr;
    gap:30px;
}

@media(max-width:768px){

.hero h1{
    font-size:40px;
}

nav{
    display:none;
}

}

</style>
</head>
<body>

<header>
<div class="container navbar">

<div class="logo">
AJP <span>GROUP</span>
</div>

<nav>
<ul>
<li><a href="#beranda">Beranda</a></li>
<li><a href="#layanan">Layanan</a></li>
<li><a href="#tentang">Tentang</a></li>
<li><a href="#portofolio">Portofolio</a></li>
<li><a href="#faq">FAQ</a></li>
<li><a href="#kontak">Kontak</a></li>
</ul>
</nav>

<a href="https://wa.me/62818877568" class="btn">
Konsultasi Gratis
</a>

</div>
</header>

<section class="hero" id="beranda">
<div class="container hero-content">

<h1>
URUS IZIN USAHA &
<span>SERTIFIKASI TANPA RIBET</span>
</h1>

<p>
Solusi Profesional Pengurusan SLF, PBG, SBUJK, ISO, AMDAL, SIPA Air Tanah, dan Sumur Bor di Seluruh Indonesia.
</p>

<div class="hero-buttons">
<a href="https://wa.me/62818877568" class="btn">
Konsultasi Sekarang
</a>

<a href="#layanan" class="btn-outline">
Lihat Layanan
</a>
</div>

<div class="stats">
<div class="stat">
<h3>500+</h3>
<p>Proyek Selesai</p>
</div>

<div class="stat">
<h3>100+</h3>
<p>Klien Perusahaan</p>
</div>

<div class="stat">
<h3>Indonesia</h3>
<p>Jangkauan Nasional</p>
</div>
</div>

</div>
</section>

<section id="tentang">
<div class="container">

<div class="section-title">
<h2>Mengapa Memilih Kami?</h2>
</div>

<div class="features">

<div class="feature">
<h3>Tim Profesional</h3>
<p>Berpengalaman dalam perizinan dan sertifikasi.</p>
</div>

<div class="feature">
<h3>Proses Cepat</h3>
<p>Pendampingan hingga izin terbit.</p>
</div>

<div class="feature">
<h3>Harga Kompetitif</h3>
<p>Transparan dan sesuai kebutuhan.</p>
</div>

<div class="feature">
<h3>Legal & Terpercaya</h3>
<p>Mengikuti regulasi pemerintah terbaru.</p>
</div>

</div>

</div>
</section>

<section class="services" id="layanan">

<div class="container">

<div class="section-title">
<h2>Layanan Kami</h2>
</div>

<div class="service-grid">

<div class="service-card">
<h3>SLF</h3>
<p>Sertifikat Laik Fungsi bangunan.</p>
</div>

<div class="service-card">
<h3>PBG</h3>
<p>Persetujuan Bangunan Gedung.</p>
</div>

<div class="service-card">
<h3>ISO</h3>
<p>ISO 9001, 14001, 45001, 37001.</p>
</div>

<div class="service-card">
<h3>AMDAL & UKL-UPL</h3>
<p>Penyusunan dokumen lingkungan.</p>
</div>

<div class="service-card">
<h3>SIPA Air Tanah</h3>
<p>Perizinan pengambilan air bawah tanah.</p>
</div>

<div class="service-card">
<h3>SBUJK</h3>
<p>Sertifikat Badan Usaha Jasa Konstruksi.</p>
</div>

</div>

</div>

</section>

<section class="process">

<div class="container">

<div class="section-title">
<h2 style="color:white">Alur Kerja</h2>
</div>

<div class="process-grid">

<div class="step"><div class="number">01</div>Konsultasi</div>
<div class="step"><div class="number">02</div>Survey</div>
<div class="step"><div class="number">03</div>Dokumen</div>
<div class="step"><div class="number">04</div>Pengajuan</div>
<div class="step"><div class="number">05</div>Penerbitan</div>

</div>

</div>

</section>

<section id="portofolio">

<div class="container">

<div class="section-title">
<h2>Portofolio</h2>
</div>

<div class="portfolio-grid">

<div class="portfolio-item">
<img src="https://images.unsplash.com/photo-1565008447742-97f6f38c985c" alt="">
<h4>SLF Gudang Industri</h4>
</div>

<div class="portfolio-item">
<img src="https://images.unsplash.com/photo-1517048676732-d65bc937f952" alt="">
<h4>Sertifikasi ISO</h4>
</div>

<div class="portfolio-item">
<img src="https://images.unsplash.com/photo-1509395176047-4a66953fd231" alt="">
<h4>AMDAL Kawasan Industri</h4>
</div>

</div>

</div>

</section>

<section class="testimonials">

<div class="container">

<div class="section-title">
<h2>Testimoni Klien</h2>
</div>

<div class="testimonial-grid">

<div class="testimonial">
★★★★★
<p>Pelayanan cepat dan profesional.</p>
</div>

<div class="testimonial">
★★★★★
<p>Pendampingan sangat membantu.</p>
</div>

<div class="testimonial">
★★★★★
<p>Dokumen terbit sesuai target.</p>
</div>

</div>

</div>

</section>

<section id="faq">

<div class="container">

<div class="section-title">
<h2>FAQ</h2>
</div>

<div class="faq-item">
<div class="faq-question">Berapa lama proses SLF?</div>
<div class="faq-answer">Tergantung jenis bangunan dan dokumen.</div>
</div>

<div class="faq-item">
<div class="faq-question">Apakah melayani seluruh Indonesia?</div>
<div class="faq-answer">Ya, seluruh wilayah Indonesia.</div>
</div>

</div>

</section>

<section class="cta">

<div class="container">

<h2>Siap Mengurus Perizinan Anda?</h2>

<br>

<a href="https://wa.me/62818877568" class="btn">
Hubungi Kami Sekarang
</a>

</div>

</section>

<footer id="kontak">

<div class="container footer-grid">

<div>
<h3>CV ARSHAKA JAYA PERSADA</h3>
<br>
<p>
Regus, Scientia Business Park Tower 2 Lt.2<br>
Jl. Boulevard Gading Serpong Blok O/2<br>
Tangerang - Banten 15810
</p>
</div>

<div>
<h3>Kontak</h3>
<br>
<p>WhatsApp: 0818-8775-68</p>
<p>Email: arshakajayapersda@gmail.com</p>
</div>

</div>

</footer>

<script>

document.querySelectorAll('.faq-question').forEach(item=>{
item.addEventListener('click',()=>{
const answer=item.nextElementSibling;

answer.style.display=
answer.style.display==='block'
?'none'
:'block';
});
});

</script>

</body>
</html>
