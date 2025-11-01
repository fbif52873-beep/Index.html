<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SMP Muhammadiyah 37 Parung</title>
    <style>
        /* --- Global Setup & Dark Mode --- */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
                         Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            /* Latar belakang dark mode */
            background-color: #121212;
            /* Efek background gradien gelap agar lebih dinamis */
            background-image: radial-gradient(circle at 10% 20%, rgba(0, 80, 30, 0.3), transparent 50%),
                              radial-gradient(circle at 80% 90%, rgba(0, 100, 50, 0.2), transparent 60%);
            color: #e0e0e0;
            min-height: 100vh;
            padding: 20px;
        }
        /* --- Efek Glassmorphism (Kaca) --- */
        .glass-card {
            /* 1. Latar belakang semi-transparan */
            background: rgba(0, 255, 100, 0.05); /* Sedikit warna hijau transparan */            
            /* 2. Efek blur (inti dari glassmorphism) */
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px); /* Dukungan untuk Safari */            
            /* 3. Garis batas (border) tipis */
            border: 1px solid rgba(0, 255, 100, 0.2);            
            /* 4. Efek bayangan (shadow) untuk "bersinar" */
            box-shadow: 0 0 25px rgba(0, 255, 100, 0.15), /* Cahaya hijau lembut */
                        0 4px 30px rgba(0, 0, 0, 0.2);  /* Shadow standar */          
            border-radius: 16px;
            padding: 25px;
            margin-bottom: 20px;
        }
        /* --- Header & Navigasi --- */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap; /* Agar responsif di HP */
        }
        header h1 {
            font-size: 1.8rem;
            /* Efek "Hijau Bersinar" untuk Teks */
            color: #39ff14; /* Warna hijau neon */
            text-shadow: 0 0 5px #39ff14,
                         0 0 10px #39ff14,
                         0 0 15px #39ff14;
            margin-bottom: 10px; /* Jarak jika di HP */
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }
        nav a {
            text-decoration: none;
            color: #39ff14;
            font-weight: bold;
            padding: 5px 10px;
            border-radius: 5px;
            transition: all 0.3s ease;
        }
        nav a:hover {
            background-color: #39ff14;
            color: #121212;
            text-shadow: none;
            box-shadow: 0 0 15px #39ff14;
        }
        /* --- Konten Utama --- */
        main {
            margin-top: 20px;
        }
        .hero h2 {
            color: #fff;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 1.1rem;
            line-height: 1.6;
        }
        /* Tombol Aksi */
        .cta-button {
            display: inline-block;
            margin-top: 15px;
            padding: 12px 25px;
            background-color: #39ff14;
            color: #121212;
            text-decoration: none;
            font-weight: bold;
            border-radius: 8px;
            border: none;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 0 10px #39ff14;
        }
        .cta-button:hover {
            transform: scale(1.05);
            box-shadow: 0 0 20px #39ff14;
        }
        /* Layout Grid untuk Info */
        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .info-grid h3 {
            color: #39ff14;
            margin-bottom: 10px;
            text-shadow: 0 0 5px rgba(57, 255, 20, 0.5);
        }
        /* --- Footer --- */
        footer {
            text-align: center;
            margin-top: 30px;
            padding: 20px;
            background: rgba(0, 0, 0, 0.2); /* Footer lebih simpel */
            border-radius: 10px;
            font-size: 0.9rem;
            color: #aaa;
        }
    </style>
</head>
<body>
    <header class="glass-card">
        <h1>SMK Muhammadiyah 37 Parung</h1>
        <nav>
            <ul>
                <li><a href="#">Beranda</a></li>
                <li><a href="#">Profil</a></li>
                <li><a href="#">Pendaftaran</a></li>
                <li><a href="#">Kontak</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="hero glass-card">
            <h2>Selamat Datang di Website Resmi Kami</h2>
            <p>Mencetak generasi Islami, unggul dalam prestasi, dan siap menghadapi tantangan global.</p>
            <a href="#" class="cta-button">Daftar Sekarang</a>
        </section>
        <section class="info-grid">
            <div class="glass-card">
                <h3>Visi</h3>
                <p>Menjadi sekolah kejuruan yang Islami, modern, dan berdaya saing tinggi di tingkat nasional maupun internasional.</p>
            </div>    
            <div class="glass-card">
                <h3>Misi</h3>
                <ul>
                    <li>Menyelenggarakan pendidikan berkualitas.</li>
                    <li>Mengembangkan potensi peserta didik.</li>
                    <li>Membina akhlakul karimah.</li>
                </ul>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 SMK Muhammadiyah 37 Parung. All Rights Reserved.</p>
    </footer>

</body>
</html>
