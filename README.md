<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hasil Pencarian Personel</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      background: linear-gradient(to bottom right, #e9eff5, #ffffff);
      color: #333;
    }
    .header-bar {
      background-color: #0a1c4e;
      color: white;
      padding: 15px 20px;
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-between;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }
    .header-bar img {
      height: 50px;
    }
    .nav-menu {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      margin-top: 10px;
    }
    .nav-menu a {
      color: white;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s;
    }
    .nav-menu a:hover {
      color: #ffd700;
    }
    .main-container {
      width: 95%;
      max-width: 1200px;
      background: white;
      margin: 40px auto;
      box-shadow: 0 6px 20px rgba(0,0,0,0.1);
      border-radius: 12px;
      padding: 30px;
    }
    .main-container h2 {
      text-align: center;
      font-size: 26px;
      margin-bottom: 25px;
      color: #0a1c4e;
    }
    .table-responsive {
      overflow-x: auto;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      min-width: 800px;
      font-size: 14px;
      border-radius: 8px;
      overflow: hidden;
    }
    th, td {
      padding: 12px 10px;
      text-align: center;
      border: 1px solid #ddd;
    }
    th {
      background-color: #f4f6fa;
      font-weight: 600;
      color: #0a1c4e;
    }
    tr:nth-child(even) {
      background-color: #f9f9f9;
    }
    .btn-kembali {
      display: inline-block;
      margin: 30px auto 0;
      background: #0a1c4e;
      color: white;
      padding: 12px 30px;
      border-radius: 6px;
      font-weight: 600;
      font-size: 15px;
      border: none;
      cursor: pointer;
      transition: background 0.3s;
    }
    .btn-kembali:hover {
      background: #09203f;
    }
    .footer {
      background-color: #0a1c4e;
      color: white;
      text-align: center;
      padding: 25px;
      font-size: 13px;
      margin-top: 60px;
      border-top: 5px solid #ffd700;
    }
    .footer img {
      height: 40px;
      margin: 10px;
      vertical-align: middle;
    }
    @media (max-width: 768px) {
      .header-bar {
        flex-direction: column;
        align-items: flex-start;
      }
      .nav-menu {
        flex-direction: column;
        width: 100%;
        margin-top: 10px;
      }
      table {
        font-size: 12px;
      }
    }
  </style>
</head>
<body>

  <div class="header-bar">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/Logo_Kementerian_Ketenagakerjaan_Republik_Indonesia_%282020%29.svg/512px-Logo_Kementerian_Ketenagakerjaan_Republik_Indonesia_%282020%29.svg.png" alt="Logo Kemnaker">
    <div class="nav-menu">
      <a href="#">BERANDA</a>
      <a href="https://temank3.kemnaker.go.id/page/flowchart" target="_blank">FLOW CHART</a>
      <a href="#">LAYANAN</a>
      <a href="#">INFO & ARTIKEL</a>
      <a href="#">DOKUMEN K3</a>
      <a href="https://temank3.kemnaker.go.id/page/kontak" target="_blank">HUBUNGI KAMI</a>
    </div>
  </div>

  <div class="main-container">
    <h2>Hasil Pencarian Personel</h2>
    <div class="table-responsive">
      <table>
        <thead>
          <tr>
            <th>No</th>
            <th>Nama</th>
            <th>Tempat & Tanggal Lahir</th>
            <th>Nama Instansi</th>
            <th>Jenis Personil</th>
            <th>Jenis Alat</th>
            <th>Klasifikasi</th>
            <th>Kelas</th>
            <th>No. Registrasi</th>
            <th>Masa Berlaku</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>1</td>
            <td>JOKO HENDRA SAPUTRA</td>
            <td>Jakarta, 3 Desember 1994</td>
            <td>PT. MUTIARA MUTU SERTIFIKASI</td>
            <td>Trainer</td>
            <td>-</td>
            <td>TRAINER BIDANG PENANGGULANGAN KEBAKARAN (AL(PK3))</td>
            <td>Non Kelas</td>
            <td>0992071122</td>
            <td>7 November 2025</td>
          </tr>
          <tr>
            <td>3</td>
            <td>Joko Hendra Saputra</td>
            <td>Jakarta, 3 Desember 1994</td>
            <td>PT Mutiara Mutu Sertifikasi</td>
            <td>Ahli K3</td>
            <td>-</td>
            <td>Ahli K3 Umum</td>
            <td>-</td>
            <td>50721</td>
            <td>-</td>
          </tr>
          <tr>
            <td>5</td>
            <td>JOKO HENDRA SAPUTRA</td>
            <td>Jakarta, 3 Desember 1994</td>
            <td>PT Mutiara Mutu Sertifikasi</td>
            <td>Ahli K3</td>
            <td>-</td>
            <td>Ahli K3 Spesialis Penanggulangan Kebakaran (Kelas A)</td>
            <td>Non Kelas</td>
            <td>579</td>
            <td>-</td>
          </tr>
          <tr>
            <td>7</td>
            <td>JOKO HENDRA SAPUTRA</td>
            <td>Jakarta, 3 Desember 1994</td>
            <td>PT. MUTIARA MUTU SERTIFIKASI</td>
            <td>Ahli K3</td>
            <td>-</td>
            <td>Ahli K3 bidang Konstruksi dan Bangunan</td>
            <td>Muda</td>
            <td>17/098/AMK3/III/2021-PD</td>
            <td>-</td>
          </tr>
        </tbody>
      </table>
    </div>
    <button class="btn-kembali">Kembali</button>
  </div>

  <div class="footer">
    <p>Jl. Jenderal Gatot Subroto Kav. 51, Daerah Khusus Ibukota Jakarta 12750, Indonesia.</p>
    <div>
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/Logo_Kementerian_Ketenagakerjaan_Republik_Indonesia_%282020%29.svg/512px-Logo_Kementerian_Ketenagakerjaan_Republik_Indonesia_%282020%29.svg.png" alt="K3">
      <img src="https://upload.wikimedia.org/wikipedia/commons/4/43/G20_Indonesia_2022_logo.svg" alt="G20">
    </div>
    <p>Copyright © 2020-2025 Ditjen Binwasnaker & K3, Kemnaker RI.</p>
  </div>

</body>
</html>

