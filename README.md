
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FiberPro - Jasa Fiber Optik</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background: #0b1120;
      color: white;
      line-height: 1.6;
    }

    header {
      padding: 20px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: #111827;
    }

    .logo {
      color: #38bdf8;
      font-size: 23px;
      font-weight: bold;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 15px;
    }

    .hero {
      padding: 80px 8%;
      text-align: center;
      background: linear-gradient(135deg, #0f172a, #075985);
    }

    .hero h1 {
      font-size: 36px;
      margin-bottom: 15px;
    }

    .hero p {
      color: #dbeafe;
      margin-bottom: 25px;
    }

    .btn {
      display: inline-block;
      background: #22c55e;
      color: white;
      padding: 12px 24px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 50px 8%;
      text-align: center;
    }

    h2 {
      margin-bottom: 25px;
      color: #38bdf8;
    }

    .layanan {
      display: grid;
      grid-template-columns: repeat(
        auto-fit, minmax(220px, 1fr)
      );
      gap: 20px;
    }

    .card {
      background: #1e293b;
      padding: 25px;
      border-radius: 12px;
      border: 1px solid #334155;
    }

    .card h3 {
      margin-bottom: 12px;
      color: #7dd3fc;
    }

    .harga {
      font-size: 22px;
      font-weight: bold;
      color: #4ade80;
      margin: 15px 0;
    }

    .kontak {
      background: #111827;
    }

    footer {
      padding: 20px;
      text-align: center;
      color: #94a3b8;
    }

    @media (max-width: 600px) {
      .hero h1 {
        font-size: 28px;
      }

      nav a {
        margin-left: 8px;
        font-size: 13px;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">FiberPro</div>
    <nav>
      <a href="#layanan">Layanan</a>
      <a href="#harga">Harga</a>
      <a href="#penutup">penutup</a>
      <a href="#kontak">Kontak</a>
    </nav>
  </header>

  <div class="hero">
    <h1>Jasa Pemasangan Fiber Optik</h1>
    <p>
      Solusi instalasi jaringan fiber optik
      untuk rumah, kantor, dan usaha.
    </p>
    <a class="btn"
       href="https://wa.me/6282161153043">
      Pesan Sekarang
    </a>
  </div>

  <section id="layanan">
    <h2>Layanan Kami</h2>

    <div class="layanan">
      <div class="card">
        <h3>Instalasi Fiber Optik</h3>
        <p>Pemasangan kabel fiber optik untuk jaringan internet.</p>
      </div>

      <div class="card">
        <h3>Splicing Fiber Optik</h3>
        <p>Penyambungan kabel fiber optik menggunakan alat khusus.</p>
      </div>

      <div class="card">
        <h3>Perbaikan Jaringan</h3>
        <p>Pemeriksaan dan perbaikan gangguan jaringan fiber optik.</p>
      </div>
    </div>
  </section>

  <style>
  .daftar-harga {
    max-width: 1000px;
    margin: 40px auto;
    padding: 20px;
    box-sizing: border-box;
    color: white;
    font-family: Arial, sans-serif;
  }

  .daftar-harga h2 {
    text-align: center;
    color: #60c5f5;
    border-bottom: 1px solid #64748b;
    padding-bottom: 12px;
    margin-bottom: 20px;
  }

  .paket-wifi {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 15px;
  }

  .paket {
    background: #1e293b;
    padding: 25px 15px;
    border-radius: 10px;
    text-align: center;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
    border: 1px solid #29364a;
  }

  .paket h3 {
    color: #7dd3fc;
    font-size: 17px;
  }

  .paket p {
    font-size: 14px;
    color: #d1d5db;
  }

  .paket .harga {
    color: #4ade80;
    font-size: 17px;
    font-weight: bold;
  }

  .info-wifi {
    margin-top: 25px;
    padding: 20px;
    background: #1e293b;
    border-radius: 10px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
  }

  @media (max-width: 600px) {
    .paket-wifi {
      grid-template-columns: repeat(2, 1fr);
    }
  }
</style>

<section class="daftar-harga">

  <h2>DAFTAR HARGA WIFI</h2>

  <div class="paket-wifi">

    <div class="paket">
      <h3>20 Mbps</h3>
      <p>Internet fiber optik unlimited</p>
      <p class="harga">Rp150.000/bulan</p>
    </div>

    <div class="paket">
      <h3>30 Mbps</h3>
      <p>Internet fiber optik unlimited</p>
      <p class="harga">Rp200.000/bulan</p>
    </div>

    <div class="paket">
      <h3>50 Mbps</h3>
      <p>Internet fiber optik unlimited</p>
      <p class="harga">Rp250.000/bulan</p>
    </div>

    <div class="paket">
      <h3>100 Mbps</h3>
      <p>Internet fiber optik unlimited</p>
      <p class="harga">Rp350.000/bulan</p>
    </div>

    <div class="paket">
      <h3>200 Mbps</h3>
      <p>Internet fiber optik unlimited</p>
      <p class="harga">Rp500.000/bulan</p>
    </div>

  </div>

  <div class="info-wifi">
    <p><strong>Layanan:</strong> Internet fiber optik unlimited.</p>
    <p><strong>Instalasi baru:</strong> Rp250.000.</p>
  </div>

</section>

  <section id="kontak" class="kontak">
    <h2>Hubungi Kami</h2>
    <p>Butuh pemasangan fiber optik? Konsultasikan kebutuhan Anda.</p>
    <br>

    <a class="btn"
       href="https://wa.me/6282161153043?text=Halo%2C%20saya%20ingin%20memesan%20jasa%20fiber%20optik">
      Chat WhatsApp
    </a>
  </section>

  <footer>
    <p>© 2026 FiberPro | Jasa Fiber Optik</p>
  </footer>

<style>
  /* Bagian penutup sejajar dengan daftar harga */
  #penutup {
    width: 100%;
    margin: 40px 0 0;
    padding: 0;
    box-sizing: border-box;
  }

  #penutup .container {
    width: 100%;
    max-width: 1000px;
    margin: 0 auto;
    padding: 0 20px;
    box-sizing: border-box;
  }

  #penutup h2 {
    width: 100%;
    margin: 0 0 15px;
    padding-bottom: 10px;
    color: #60c5f5;
    text-align: center;
    font-size: 20px;
    line-height: 1.5;
    border-bottom: 1px solid #64748b;
    box-sizing: border-box;
  }

  #penutup .penutup {
    width: 100%;
    margin: 0;
    padding: 25px 20px;
    background: #1e293b;
    border-radius: 10px;
    color: #fff;
    text-align: center;
    box-sizing: border-box;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
  }

  #penutup p {
    line-height: 1.6;
    overflow-wrap: anywhere;
  }

  #penutup a {
    color: #60c5f5;
    font-weight: bold;
    text-decoration: none;
  }

  @media (max-width: 600px) {
    #penutup .container {
      padding: 0 15px;
    }

    #penutup h2 {
      font-size: 17px;
    }

    #penutup .penutup {
      padding: 20px 15px;
    }
  }
</style>

<section id="penutup">
  <div class="container">

    <h2>
      Siap Memasang & Memperbaiki Jaringan Fiber Optik Anda
    </h2>

    <div class="penutup">
      <h4>Penutup</h4>

      <p>
        Kami menyediakan jasa pemasangan, penyambungan,
        perbaikan serta pengecekan jaringan fiber optik
        untuk rumah, kantor, sekolah dan perkantoran.
        Tim kami berpengalaman menangani penyambungan
        kabel fiber optik, pemasangan terminal ODB
        hingga pengecekan kerusakan kabel menggunakan alat OTDR.
      </p>

      <p>
        Jika Anda membutuhkan jasa pemasangan atau
        perbaikan jaringan fiber optik yang cepat,
        rapi dan terpercaya, silakan hubungi kami
        untuk konsultasi dan penawaran harga terbaik.
      </p>

      <a href="https://wa.me/6283140517726">
        💬 Chat WhatsApp Kami
      </a>
    </div>

  </div>
</section>

</body>
</html>
