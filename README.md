<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Berita Terbaru</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 10px;
        }
        .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .grid-item {
            background: #f4f4f4;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .grid-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
        }
        .grid-item a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
            display: block;
            margin-top: 10px;
        }
        .grid-item a:hover {
            color: #4CAF50;
        }
    </style>
</head>
<body>
    <header>
        <h1>Berita Terbaru</h1>
    </header>
    <div class="grid-container">
        <div class="grid-item">
            <h3>Berita PKN Terbaru Hari Ini - Bobo.ID</h3>
            <p>Berita seputar PPKn untuk anak SD, membahas topik-topik menarik dan relevan.</p>
            <a href="https://bobo.grid.id/read/083129793/kumpulan-soal-ppkn-kelas-5-sd-dan-kunci-jawaban" target="_blank">Baca Selengkapnya</a>
        </div>
        <div class="grid-item">
            <h3>Berita PKN Kelas 6 SD - Kompas.com</h3>
            <p>Informasi terbaru mengenai materi dan pembelajaran PPKn untuk kelas 6 SD.</p>
            <a href="https://www.kompas.com/edu/read/2021/06/02/163000671/materi-pelajaran-ppkn-kelas-6-sd-tentang-persatuan-dan-kesatuan" target="_blank">Baca Selengkapnya</a>
        </div>
        <div class="grid-item">
            <h3>Berita PPKn Kelas 5 SD - Republika.co.id</h3>
            <p>Materi menarik dan interaktif untuk mendukung pembelajaran PPKn anak SD.</p>
            <a href="https://www.republika.co.id/berita/qmvn06368/soal-dan-jawaban-ppkn-kelas-5-sd-tentang-demokrasi" target="_blank">Baca Selengkapnya</a>
            
        </div>
    </div>
    <div class="back-button">
        <a href="index.html">
     Kembali
        </a>
    </div>
</body>
</html>
