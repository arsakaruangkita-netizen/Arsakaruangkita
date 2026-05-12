# Arsakaruangkita
buatkan seperti ini https://bit.ly/Arsakaruangkita
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Konsultasi - Arsaka Ruang Kita</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #2563eb; /* Biru Profesional */
            --bg: #f8fafc;
            --text: #1e293b;
            --white: #ffffff;
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg);
            color: var(--text);
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            width: 100%;
            padding: 20px 0;
            text-align: center;
            background: var(--white);
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
        }

        .container {
            max-width: 600px;
            width: 90%;
            margin: 40px 0;
            background: var(--white);
            padding: 30px;
            border-radius: 16px;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
        }

        h1 {
            font-size: 1.8rem;
            margin-bottom: 10px;
            text-align: center;
        }

        p.subtitle {
            text-align: center;
            color: #64748b;
            margin-bottom: 30px;
        }

        .form-group {
            margin-bottom: 20px;
        }

        label {
            display: block;
            font-weight: 500;
            margin-bottom: 8px;
            font-size: 0.95rem;
        }

        input, select, textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #e2e8f0;
            border-radius: 8px;
            font-family: inherit;
            box-sizing: border-box; /* Sangat penting agar rapi */
            font-size: 1rem;
        }

        input:focus, textarea:focus {
            outline: none;
            border-color: var(--primary);
            box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.1);
        }

        button {
            width: 100%;
            padding: 14px;
            background-color: var(--primary);
            color: white;
            border: none;
            border-radius: 8px;
            font-weight: 600;
            font-size: 1rem;
            cursor: pointer;
            transition: background 0.3s ease;
        }

        button:hover {
            background-color: #1d4ed8;
        }

        .footer {
            margin-top: 20px;
            font-size: 0.85rem;
            color: #94a3b8;
            text-align: center;
        }
    </style>
</head>
<body>

<header>
    <strong>Arsaka Ruang Kita</strong>
</header>

<div class="container">
    <h1>Layanan Konsultasi</h1>
    <p class="subtitle">Ceritakan kendala Anda, kami siap membantu mencari solusi terbaik.</p>

    <form action="https://formspree.io/f/YOUR_ID" method="POST"> <!-- Ganti YOUR_ID nanti -->
        <div class="form-group">
            <label for="nama">Nama Lengkap</label>
            <input type="text" id="nama" name="nama" placeholder="Masukkan nama Anda" required>
        </div>

        <div class="form-group">
            <label for="whatsapp">Nomor WhatsApp</label>
            <input type="tel" id="whatsapp" name="whatsapp" placeholder="Contoh: 08123456xxx" required>
        </div>

        <div class="form-group">
            <label for="layanan">Jenis Konsultasi</label>
            <select id="layanan" name="layanan">
                <option value="umum">Konsultasi Umum</option>
                <option value="akademik">Konsultasi Akademik</option>
                <option value="psikologi">Bimbingan & Konseling</option>
                <option value="organisasi">Manajemen Organisasi</option>
            </select>
        </div>

        <div class="form-group">
            <label for="pesan">Pesan atau Keluhan</label>
            <textarea id="pesan" name="pesan" rows="5" placeholder="Tuliskan apa yang ingin Anda diskusikan..." required></textarea>
        </div>

        <button type="submit">Kirim Jadwal Konsultasi</button>
    </form>
</div>

<div class="footer">
    &copy; 2026 Arsaka Ruang Kita. Terhubung untuk Maju.
</div>

</body>
</html>
