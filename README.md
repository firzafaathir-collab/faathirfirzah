<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodata Diri - Faathir</title>

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #5a0f1c, #800020, #3b000f);
            background-size: 300% 300%;
            animation: gradientMove 8s ease infinite;
        }

        @keyframes gradientMove {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .card {
            background: rgba(255, 255, 255, 0.08);
            backdrop-filter: blur(15px);
            padding: 40px;
            width: 380px;
            border-radius: 20px;
            text-align: center;
            color: white;
            box-shadow: 0 15px 35px rgba(0,0,0,0.4);
            animation: fadeIn 1.5s ease;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .foto img {
            width: 130px;
            height: 130px;
            object-fit: cover;
            border-radius: 50%;
            border: 4px solid #ffccd5;
            margin-bottom: 20px;
            transition: 0.4s;
        }

        .foto img:hover {
            transform: scale(1.1);
            box-shadow: 0 0 20px #ffccd5;
        }

        h1 {
            font-size: 22px;
            font-weight: 700;
            margin-bottom: 10px;
            letter-spacing: 1px;
            color: #ffd6db;
        }

        .nama {
            font-size: 18px;
            font-weight: 600;
            margin-bottom: 15px;
            color: #ffffff;
        }

        .deskripsi {
            font-size: 14px;
            line-height: 1.6;
            margin-bottom: 20px;
            color: #f8d7da;
        }

        footer {
            font-size: 13px;
            color: #ffd6db;
        }

        hr {
            border: 0;
            height: 1px;
            background: #ffd6db;
            margin: 15px 0;
            opacity: 0.5;
        }

        footer strong {
            color: #ffffff;
        }

        /* Responsive */
        @media (max-width: 450px) {
            .card {
                width: 90%;
                padding: 25px;
            }
        }

    </style>
</head>
<body>

    <div class="card">
        <div class="foto">
            <img src="latar biru.jpeg" alt="Foto Profil">
        </div>

        <h1>BIODATA DIRI</h1>

        <p class="nama">Muhammad Faathir Firzah</p>

        <p class="deskripsi">
            Nama saya Muhammad Faathir Firzah, sering dipanggil Fathir.
            Saya berasal dari Kabupaten Tolitoli, Sulawesi Tengah.
            Saya berusia 19 tahun dan saat ini berkuliah di Universitas Hasanuddin
            jurusan Terapi Gigi dan Mulut angkatan 2024.
        </p>

        <footer>
            <hr>
            <p><strong>Alamat:</strong> Jl. Perjuangan, Tamalanrea, Kota Makassar, Sulawesi Selatan</p>
        </footer>
    </div>

</body>
</html>
