<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodata & Portofolio - Florida Roulina Manihuruk</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f7f6;
            color: #333;
            line-height: 1.6;
            padding: 20px;
        }

        .container {
            max-width: 850px;
            margin: 20px auto;
            background: #fff;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.08);
        }

        /* Header / Profile Section */
        .header {
            display: flex;
            align-items: center;
            gap: 30px;
            border-bottom: 2px solid #eaeaea;
            padding-bottom: 30px;
            margin-bottom: 30px;
        }

        .profile-img {
            width: 150px;
            height: 190px;
            object-fit: cover;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.15);
        }

        .header-text h1 {
            font-size: 28px;
            color: #1a2a3a;
            margin-bottom: 10px;
        }

        .contact-info p {
            font-size: 14px;
            color: #555;
            margin-bottom: 4px;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        /* Section Styling */
        .section {
            margin-bottom: 30px;
        }

        .section-title {
            font-size: 20px;
            color: #1a2a3a;
            border-left: 4px solid #0066cc;
            padding-left: 10px;
            margin-bottom: 15px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .section p {
            color: #444;
            text-align: justify;
        }

        /* List Styling */
        ul {
            list-style-type: none;
            padding-left: 0;
        }

        ul li {
            position: relative;
            padding-left: 20px;
            margin-bottom: 10px;
            color: #444;
        }

        ul li::before {
            content: "•";
            color: #0066cc;
            font-weight: bold;
            font-size: 18px;
            position: absolute;
            left: 0;
            top: -2px;
        }

        /* Timeline / Experience Items */
        .item {
            margin-bottom: 20px;
        }

        .item-title {
            font-weight: bold;
            font-size: 16px;
            color: #222;
        }

        .item-sub {
            font-size: 14px;
            color: #666;
            margin-bottom: 6px;
            font-style: italic;
        }

        /* Skills Tag Styling */
        .skills-container {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .skill-tag {
            background-color: #eef5ff;
            color: #0066cc;
            padding: 8px 14px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: 500;
            border: 1px solid #cce0ff;
        }

        /* Responsive Design */
        @media (max-width: 600px) {
            .header {
                flex-direction: column;
                text-align: center;
            }

            .contact-info p {
                justify-content: center;
            }

            .container {
                padding: 20px;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Header / Profil Utama -->
        <header class="header">
            <!-- Foto dihubungkan langsung sesuai nama file gambar Anda -->
            <img src="WhatsApp Image 2026-10-04 at 20.09.54.jpeg" alt="Foto Florida Roulina Manihuruk" class="profile-img">
            <div class="header-text">
                <h1>Florida Roulina Manihuruk</h1>
                <div class="contact-info">
                    <p>📞 +62 823-3930-8788</p>
                    <p>✉️ florida.124230050@student.itera.ac.id</p>
                    <p>📍 Way Huwi, Lampung Selatan</p>
                </div>
            </div>
        </header>

        <!-- Profil Singkat -->
        <section class="section">
            <h2 class="section-title">Profil Singkat</h2>
            <p>
                Mahasiswi Teknik Geomatika yang memiliki ketertarikan pada teknologi, pemetaan digital, dan analisis data[cite: 1]. Saya adalah pembelajar yang cepat, teliti, dan suka mengeksplorasi hal baru, terutama yang berkaitan dengan logika dan teknologi[cite: 1]. Saya berkomitmen mengembangkan kemampuan yang mendukung dunia teknologi dan geospasial modern[cite: 1].
            </p>
        </section>

        <!-- Pendidikan -->
        <section class="section">
            <h2 class="section-title">Pendidikan</h2>
            <ul>
                <li><strong>SMAN 1 Pangururan</strong> (2021 - 2024) — Matematika dan Ilmu Pengetahuan Alam[cite: 1]</li>
                <li><strong>Institut Teknologi Sumatera</strong> (2024 - Sekarang) — Teknik Geomatika[cite: 1]</li>
            </ul>
        </section>

        <!-- Pengalaman Kerja & Organisasi -->
        <section class="section">
            <h2 class="section-title">Pengalaman Kerja & Organisasi</h2>
            
            <div class="item">
                <div class="item-title">OSIS Divisi Ilmu Pengetahuan dan Teknologi</div>
                <div class="item-sub">2022 - 2023</div>
                <p>Saya membantu dalam penyusunan lomba-lomba berkaitan dengan akademik untuk kegiatan OSIS dan membantu dalam pengembangan web sekolah[cite: 1]. Selain itu saya juga mengambil bagian dalam mendokumentasikan serta mempublikasikan kegiatan-kegiatan yang telah dilakukan[cite: 1].</p>
            </div>

            <div class="item">
                <div class="item-title">Finalis OSN Informatika Tingkat Provinsi</div>
                <div class="item-sub">2023</div>
                <p>Saya belajar banyak tentang <em>problem solving</em> dengan logika dan matematis serta mengimplementasikannya menggunakan bahasa C++[cite: 1].</p>
            </div>

            <div class="item">
                <div class="item-title">Panitia Sponsorship GEOSAINS</div>
                <div class="item-sub">2025</div>
                <p>Menyusun proposal dan mengelola komunikasi dengan calon sponsor, melakukan negosiasi, serta memastikan terjalinnya kerja sama untuk mendukung kebutuhan acara[cite: 1].</p>
            </div>
        </section>

        <!-- Kemampuan -->
        <section class="section">
            <h2 class="section-title">Kemampuan</h2>
            <div class="skills-container">
                <span class="skill-tag">Competitive Programming</span>
                <span class="skill-tag">Pemrograman (C++, PostgreSQL)</span>
                <span class="skill-tag">Problem Solving Algoritmik</span>
                <span class="skill-tag">Koordinasi Lintas Divisi</span>
                <span class="skill-tag">Analisis Data</span>
            </div>
        </section>
    </div>

</body>
</html>
