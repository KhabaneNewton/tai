<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KMI Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            text-align: center;
        }
        header {
            background-color: #4CAF50;
            padding: 20px;
            color: white;
        }
        header h1 {
            margin: 0;
        }
        .content {
            padding: 20px;
        }
        .content h2 {
            color: #4CAF50;
        }
        .buttons a {
            display: inline-block;
            margin: 10px;
            padding: 10px 20px;
            background-color: #3b473c;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .buttons a:hover {
            background-color: #45a049;
        }
        footer {
            padding: 10px;
            background-color: #333;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tentang Khabane Newton</h1>
    </header>
    <div class="content">
        <h2>Halo, Saya KhabaneNewton!</h2>
        <p>Saya suka membuat konten dan berbagi pengalaman dengan teman-teman di internet. Jangan lupa cek halaman dibawah ini!</p>
        <div class="buttons">
            <a href="https://saweria.co/KhabaneNewton12" target="_blank">Saweria</a>
            <a href="https://www.youtube.com/@KhabaneNewtonOfficial" target="_blank">YouTube</a>
            <a href="https://open.spotify.com/show/2IKRIegPwocjPGrYBrBsWb?si=9da62e4fe4114486" targer="blank">KMI FM</a>
            <a href="https://open.spotify.com/artist/4qp1Jh35kGq4pzj0bFZAN4?si=0cd33983f86d402d" targer="blank">Khabane Newton Artist</a>
            <a href="https://khabanenewton.blogspot.com/" target="blank">Website Blog saya</a>
            <a href="https://discord.gg/UtKdcnf2rZ" target="_blank">discord server</a>
            <a href="https://sociabuzz.com/khabane_newton/tribe" target="_blank">Sociabuzz</a>
            <a href="https://forms.gle/4eLQJZ6MjQw28vvd9" target="_blank">Kritik Dan Saran</a>
         </div>
    <div class="content">
        <h2>Sejarah terbentuknya nama KhabaneNewton</h2>
        <p> di suatu hari, pada hari Senin-Minggu pada saat saya lagi boker tiba-tiba kepikiran nama samaran baru dan hatiku berkata "mau pake nama samaran apa ya?? ohh ya Khabane Newton", Khabane Newton itu Adalah potongan sebuah nama dari Khabane Lame dan Issac Newton dan terbentuklah nama Khabane Newton, dan besoknya saya membuat hampir semua nama akun saya Khabane Newton dan nama asli saya adalah "A" cari sendiri ya, dan ya nama Khabane Newton telah Terkenal  sekian blog pertama saya, sekian terimakasih
            DONASI WOI BIAR OWNERNYA BAHAGIA YGY </p>
<html lang="id">
    <!DOCTYPE html>
    <html lang="id">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Toggle Tema Gelap</title>
    <style>
    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    transition: background-color 0.3s, color 0.3s;
    }
    
    body.dark-mode {
    background-color: #121212;
    color: #e0e0e0;
    }
    
    #toggle-theme-btn {
    position: fixed;
    bottom: 80px; /* Geser lebih tinggi dari footer */
    right: 20px; /* Geser lebih jauh dari tepi */
    background-color: #333;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
    }
    
    #toggle-theme-btn:hover {
    background-color: #444;
    }
    
    footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
    z-index: 1;
    }
    </style>
    </head>
    <body>
    
    <button id="toggle-theme-btn">Tema Gelap</button>
    
    <footer>
    <p>&copy; 2024 KhabaneNewton Hak Cipta Di Lindungi.</p>
    </footer>
    
    <script>
    function applyTheme(themeName) {
    document.body.className = themeName;
    localStorage.setItem('theme', themeName);
    }
    
    document.getElementById('toggle-theme-btn').addEventListener('click', function(e) {
    e.preventDefault();
    let currentTheme = localStorage.getItem('theme');
    if (currentTheme === 'dark-mode') {
    applyTheme('');
    this.textContent = 'Tema Gelap';
    } else {
    applyTheme('dark-mode');
    this.textContent = 'Tema Terang';
    }
    });
    
    // Pas halaman di-load, cek setting tema di local storage
    document.addEventListener('DOMContentLoaded', function() {
    let currentTheme = localStorage.getItem('theme');
    if (currentTheme === 'dark-mode') {
    applyTheme('dark-mode');
    document.getElementById('toggle-theme-btn').textContent = 'Tema Terang';
    } else {
    document.getElementById('toggle-theme-btn').textContent = 'Tema Gelap';
    }
    });
    </script>
    
    </body>
    </html>
