<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Hafizh Ayyasy Pratama - Profile</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .animated-name {
            display: flex;
            justify-content: center;
            font-size: 2.5em;
            color: #333;
            overflow: hidden;
        }
        .animated-name span {
            display: inline-block;
            opacity: 0;
            animation: slideIn 0.5s forwards;
        }
        @keyframes slideIn {
            from { 
                transform: translateY(50px);
                opacity: 0;
            }
            to { 
                transform: translateY(0);
                opacity: 1;
            }
        }
        .animated-name span:nth-child(1) { animation-delay: 0.1s; }
        .animated-name span:nth-child(2) { animation-delay: 0.2s; }
        .animated-name span:nth-child(3) { animation-delay: 0.3s; }
        .section {
            background-color: white;
            border-radius: 10px;
            padding: 20px;
            margin: 20px 0;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
        }
        .skill-badge {
            background-color: #4CAF50;
            color: white;
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 0.8em;
            animation: popIn 0.5s ease-in-out;
        }
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        .social-icon {
            transition: transform 0.3s ease;
        }
        .social-icon:hover {
            transform: scale(1.2);
        }
        .tools {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
        }
        .tool-badge {
            display: flex;
            align-items: center;
            background-color: #f0f0f0;
            border-radius: 20px;
            padding: 8px 15px;
            transition: transform 0.3s ease;
        }
        .tool-badge:hover {
            transform: scale(1.05);
        }
        .tool-badge img {
            margin-right: 10px;
            width: 24px;
            height: 24px;
        }
        .view-counter {
            text-align: center;
            margin-top: 20px;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        @keyframes popIn {
            from { transform: scale(0.5); opacity: 0; }
            to { transform: scale(1); opacity: 1; }
        }
    </style>
</head>
<body>
    <div class="animated-name">
        <span>H</span>
        <span>a</span>
        <span>fizh</span>
    </div>
    <h1 align="center">Ayyasy Pratama 👋</h1>
    
    <div class="section">
        <p align="center">Selamat datang di Github Profile Saya, Saya adalah seorang mahasiswa yang saat ini menempuh studi di Politeknik STMI Jakarta dengan fokus pada Sistem Informasi Otomotif Industri 🎓. Saya tertarik dalam pengembangan pemrograman web 🌐 serta pengolahan data dan jaringan komputer 📊💻.</p>
    </div>

    <div class="section">
        <h2>🎯 Current Focus</h2>
        <div class="skills">
            <span class="skill-badge">Networking</span>
            <span class="skill-badge">Data Mining</span>
            <span class="skill-badge">Web Programming</span>
            <span class="skill-badge">Microsoft Office</span>
        </div>
    </div>

    <div class="section">
        <h2>💼 Tools & Technologies</h2>
        <div class="tools">
            <div class="tool-badge">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/html5.svg" alt="HTML5">
                <span>HTML5</span>
            </div>
            <div class="tool-badge">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/css3.svg" alt="CSS3">
                <span>CSS3</span>
            </div>
            <div class="tool-badge">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/bootstrap.svg" alt="Bootstrap">
                <span>Bootstrap 5</span>
            </div>
            <div class="tool-badge">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/php.svg" alt="PHP">
                <span>PHP</span>
            </div>
            <div class="tool-badge">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/mysql.svg" alt="MySQL">
                <span>MySQL</span>
            </div>
            <div class="tool-badge">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/java.svg" alt="Java">
                <span>Java</span>
            </div>
            <div class="tool-badge">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/python.svg" alt="Python">
                <span>Python</span>
            </div>
            <div class="tool-badge">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/xampp.svg" alt="XAMPP">
                <span>XAMPP</span>
            </div>
            <div class="tool-badge">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/git.svg" alt="Git">
                <span>Git</span>
            </div>
            <div class="tool-badge">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/cisco.svg" alt="Cisco Packet Tracer">
                <span>Cisco Packet Tracer</span>
            </div>
            <div class="tool-badge">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v5/icons/jupyter.svg" alt="Jupyter">
                <span>Jupyter Notebook</span>
            </div>
        </div>
    </div>

    <div class="section">
        <h2>🚀 Featured Projects</h2>
        <ul>
            <li>
                <strong>Sistem Penerimaan Beasiswa</strong>
                <p>Sebuah sistem manajemen beasiswa berbasis web dengan fitur:
                    - 🔒 Sistem autentikasi berbasis peran (Admin & Pengguna)
                    - 📄 Manajemen pendaftaran yang fleksibel
                    - 📈 Fitur analisis pada tampilan dasboard
                    - 🗄️ Integrasi dengan database MySQL
                    - 📱 Tampilan yang responsif
                </p>
            </li>
            <li>
                <strong>Sistem Pencarian Bengkel Terdekat</strong>
                <p>Solusi pencarian bengkel terdekat yang efisien, dengan:
                    - 📍 Lokasi bengkel berdasarkan jarak terdekat
                    - 🗺️ Antarmuka pengguna sederhana dan mudah digunakan
                    - 💻 Dikembangkan menggunakan Bahasa C
                </p>
            </li>
        </ul>
    </div>

    <div class="section">
        <h2>🌐 Terhubung dengan Saya</h2>
        <div class="social-links">
            <a href="https://www.linkedin.com/in/hafizh-ayyasy-pratama" class="social-icon">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="LinkedIn" height="30" width="30" />
            </a>
            <a href="https://www.instagram.com/hafizhpratam_/" class="social-icon">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/instagram.svg" alt="Instagram" height="30" width="30" />
            </a>
            <a href="https://www.youtube.com/@hafizhayyasypratama8530" class="social-icon">
                <img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/youtube.svg" alt="YouTube" height="30" width="30" />
            </a>
        </div>
    </div>

    <div class="section">
        <h2>📈 Statistik GitHub</h2>
        <div style="display: flex; justify-content: center; flex-wrap: wrap;">
            <img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=Hafizhayyasypratama04&show_icons=true&locale=id&layout=compact" alt="hafizhayyasy" />
            <img align="left" src="https://github-readme-stats.vercel.app/api?username=Hafizhayyasypratama04&show_icons=true&locale=id" alt="hafizhayyasy" />
        </div>
    </div>

    <div class="view-counter">
        <img src="https://profile-counter.glitch.me/Hafizhayyasypratama04/count.svg" alt="Visitor Count">
    </div>
</body>
</html>
