
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>JobSeekr - Temukan Karier Impianmu</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<style>
  body { 
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      text-align: center;
      padding: 50px;
  }
  .icon-box {
      border: 1px solid #6c757d;
      display: inline-block;
      padding: 12px;
      margin: 30px;
      border-radius: 10px;
  }
  .icon-box {
      color:  #0046be;
      margin-bottom: 10px;
      font-size: 50px;
  }
  .icon-box:hover {
      border: 1px solid #2d2d2d;
      animation: bounce 2s infinite;
  }

  @keyframes bounce {
      0%, 20%, 50%, 80%, 100% {
          transform: translateY(0);
      }
      40% {
          transform: translateY(-30px);
      }
      60% {
          transform: translateY(-10px);
      }
  }

  .icon-box i.rotate {
      animation: rotate 2s linear infinite;
  }
  @keyframes rotate {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
  }
  .icon-box:hover i {
      color: #00a6ff;
  }
</style>
<body>
  <p style="background-color: #f6f8fb></p>
  <header>
    <img src="logo.png">
    <h1>Temukan Karier Impianmu</h1>
    <p>Buat resume profesional, cari pekerjaan, dan kelola aplikasi Anda – semuanya dalam satu platform.</p>
    <button class="btn-primary">Mulai Sekarang</button>
  </header>

  <section class="steps">
    <div class="step">
      <i class="fas fa-file-alt"></i>
      <h3>Buat Resume</h3>
      <p>Gunakan pembuat resume kami yang modern untuk membuat dokumen profesional dalam hitungan menit.</p>
    </div>
    <div class="step">
      <i class="fas fa-search"></i>
      <h3>Cari Pekerjaan</h3>
      <p>Telusuri ribuan lowongan kerja yang relevan dengan keahlian dan lokasi Anda.</p>
    </div>
    <div class="step">
      <i class="fas fa-briefcase"></i>
      <h3>Lamar dan Kelola</h3>
      <p>Lacak lamaran Anda dan simpan pekerjaan favorit dengan mudah dalam dashboard pribadi Anda.</p>
    </div>
  </section>

  <section class="reviews">
    <h2>Testimoni Pengguna</h2>
    <div class="review-list">
      <div class="review">
        <p>"JobSeekr membantu saya membuat resume yang profesional dan mudah diterima oleh perusahaan!"</p>
        <h4>— Rina, Fresh Graduate</h4>
      </div>
      <div class="review">
        <p>"Saya suka fitur pelacakan lamaran. Semua lowongan yang saya lamar bisa saya pantau dengan mudah."</p>
        <h4>— Andre, Digital Marketer</h4>
      </div>
      <div class="review">
        <p>"Prosesnya cepat dan antarmukanya mudah digunakan. Sangat cocok untuk profesional yang sibuk."</p>
        <h4>— Sari, HR Specialist</h4>
      </div>
    </div>
  </section>

  <section class="cta">
    <h2>Wujudkan Masa Depan Profesional Anda</h2>
    <p>Bergabunglah dengan komunitas global pencari kerja dan buka peluang karier yang lebih luas hari ini.</p>
    <button class="btn-primary">Gabung Gratis</button>
  </section>

  <footer>
    <p>&copy; 2025 JobSeekr</p>
  </footer>
</body>
</html>

