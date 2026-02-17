<!DOCTYPE html>
<html>
<head>
  <title>Paskal Shopping & Reservasi</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      margin: 0;
    }

    header {
      background: #222;
      color: white;
      padding: 20px;
      text-align: center;
    }

    section {
      padding: 30px;
    }

    .card {
      background: white;
      width: 450px;
      margin: auto;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.15);
    }

    h2 {
      text-align: center;
    }

    label {
      font-weight: bold;
    }

    input, select {
      width: 100%;
      padding: 8px;
      margin: 5px 0 15px;
      border-radius: 6px;
      border: 1px solid #ccc;
    }

    button {
      width: 100%;
      padding: 10px;
      background: #222;
      color: white;
      border: none;
      border-radius: 8px;
    }
  </style>
</head>
<body>

<header>
  <h1>paskal shopping center</h1>
  <p>website informasi & reservasi pengunjung</p>
</header>

<section>
  <h2>tentang paskal</h2>
  <p>
    paskal shopping center adalah salah satu pusat perbelanjaan modern
    yang terletak di kota bandung dengan berbagai tenant kuliner,
    fashion, dan hiburan keluarga.
  </p>
</section>

<section>
  <div class="card">
    <h2>form reservasi pengunjung</h2>

    <form>
      <input type="hidden" value="PASKAL01">

      <label>nama</label>
      <input type="text">

      <label>email</label>
      <input type="email">

      <label>pin 6 digit</label>
      <input type="password" minlength="6" maxlength="6">

      <label>provinsi</label>
      <select>
        <option>jawa barat</option>
        <option>dki jakarta</option>
      </select>

      <label>kota</label>
      <select>
        <option>bandung</option>
        <option>jakarta</option>
      </select>

      <label>meeting point</label>
      <select>
        <option>lobby utama</option>
        <option>parkiran basement</option>
      </select>

      <label>tujuan kunjungan</label>
      <input type="search">

      <label>tanggal</label>
      <input type="date">

      <label>jam</label>
      <input type="time">

      <label>jumlah orang</label>
      <input type="number" min="1" max="20">

      <label>link medsos</label>
      <input type="url">

      <label>warna seragam</label>
      <input type="color">

      <label>pembayaran</label><br>
      <input type="radio" name="bayar"> full  
      <input type="radio" name="bayar"> dp 50%
      <br><br>

      <label>fasilitas</label><br>
      <input type="checkbox"> parkir vip  
      <input type="checkbox"> guide mall  
      <input type="checkbox"> voucher makan
      <br><br>

      <label>upload ktp</label>
      <input type="file">

      <button type="submit">kirim reservasi</button>
    </form>
  </div>
</section>

</body>
</html># reservasi-paskal
