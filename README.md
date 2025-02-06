<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laporan Praktikum - Pengkabelan / Cabling</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #333;
        }
        img {
            width: 200px;
            display: block;
            margin: 10px 0;
        }
        .step {
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Laporan Praktikum: Pengkabelan / Cabling</h1>
        <h2>Nama: Andhika Fajjriansyah</h2>
        <h2>NIM: 09030282327025</h2>
        <h2>Program Studi: Teknik Komputer</h2>
        
        <h2>Langkah-langkah Crimping Kabel UTP</h2>
        <h3>Persiapan Bahan</h3>
        <ul>
            <li>Kabel UTP Cat5e atau Cat6 <br><img src="https://github.com/user-attachments/assets/c143de95-4713-4a48-aaac-3fba3f7c84b7" alt="Kabel UTP"></li>
            <li>Konektor RJ-45 <br><img src="https://github.com/user-attachments/assets/65242523-00f6-48d9-a1a7-a12526dbb48d" alt="Konektor RJ-45"></li>
            <li>Crimping tool <br><img src="https://github.com/user-attachments/assets/d2cb538c-92d5-4730-bbd7-08c005591c58" alt="Crimping Tool"></li>
            <li>LAN Tester <br><img src="https://github.com/user-attachments/assets/19a3eca1-68a2-4cb0-bb8f-2b8434a29b9a" alt="LAN Tester"></li>
        </ul>
        
        <h3>Langkah-langkah</h3>
        <div class="step">
            <h4>1. Potong Kabel UTP</h4>
            <p>Gunakan alat pemotong untuk memotong ujung kabel UTP agar rata.</p>
        </div>
        <div class="step">
            <h4>2. Kupas Lapisan Luar Kabel</h4>
            <p>Gunakan crimping tool untuk mengupas sekitar 2-3 cm lapisan luar kabel UTP.</p>
            <img src="https://github.com/user-attachments/assets/6f412d99-094f-43c2-a5ad-c482207790b3" alt="Kupas Kabel">
        </div>
        <div class="step">
            <h4>3. Pisahkan Pasangan Kabel</h4>
            <p>Pisahkan keempat pasang kabel dan luruskan.</p>
            <img src="https://github.com/user-attachments/assets/9c872a16-d498-4aa8-a19d-9a74a348f1b2" alt="Pisahkan Kabel">
        </div>
        <div class="step">
            <h4>4. Susun Kabel Sesuai Urutan Standar</h4>
            <p>T568A: Hijau-putih, hijau, oranye-putih, biru, biru-putih, oranye, cokelat-putih, cokelat.</p>
            <p>T568B: Oranye-putih, oranye, hijau-putih, biru, biru-putih, hijau, cokelat-putih, cokelat.</p>
            <img src="https://github.com/user-attachments/assets/059e64d4-cf05-4d8f-a19c-2bbe3d19687e" alt="Standar Kabel">
        </div>
        <div class="step">
            <h4>5. Masukkan Kabel ke Konektor RJ-45</h4>
            <p>Pastikan setiap kabel masuk ke jalurnya.</p>
            <img src="https://github.com/user-attachments/assets/460b30a9-bc64-4ea7-a86d-f052cc0b6a77" alt="Masukkan Kabel">
        </div>
        <div class="step">
            <h4>6. Uji Koneksi dengan Cable Tester</h4>
            <p>Gunakan LAN tester untuk memastikan koneksi stabil.</p>
            <img src="https://github.com/user-attachments/assets/2f31fcad-3527-4cbc-b11f-addb21750c85" alt="Uji Kabel">
        </div>
        
        <h3>Analisis</h3>
        <p>Crimping kabel UTP adalah proses menyambungkan kabel ke konektor RJ-45 menggunakan crimping tool. Tahapannya meliputi pemotongan, penyusunan standar warna, dan penjepitan agar koneksi kuat serta stabil. Proses ini penting untuk memastikan transfer data optimal dalam jaringan komputer.</p>
        
        <h3>Kesimpulan Percobaan</h3>
        <p>Kabel LAN memiliki dua jenis konfigurasi utama: straight dan cross.</p>
        <ul>
            <li><b>Kabel straight</b>: Menghubungkan perangkat berbeda (PC ke switch, router ke PC).</li>
            <li><b>Kabel cross</b>: Menghubungkan perangkat yang sama (PC ke PC, switch ke switch).</li>
        </ul>
        <p>Penggunaan crimping tool yang tepat sangat penting untuk memastikan koneksi kabel tidak longgar dan dapat berfungsi dengan baik. LAN tester digunakan untuk mengecek apakah kabel telah terpasang dengan benar.</p>
    </div>
</body>
</html>
