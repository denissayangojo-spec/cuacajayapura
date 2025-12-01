<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Halaman Web Pantauan Suhu Harian</title>
  <style>
    /* --- GLOBAL STYLE --- */
    body {
        font-family: Arial, Helvetica, sans-serif;
        margin: 0;
        padding: 20px;
        background:#FFFFFF #1A80E5;
        color: #333;
    }

    /* --- TITLE --- */
    h2 {
        text-align: center;
        color: #2c3e50;
        margin-bottom: 10px;
    }

    /* --- HORIZONTAL LINE --- */
    hr {
        border: none;
        height: 3px;
        background: #3498db;
        width: 100px;
        margin: 10px auto 20px auto;
    }

    /* --- MAP --- */
    iframe {
        border-radius: 10px;
        margin-bottom: 20px;
    }

    /* --- TABLE STYLE --- */
    table {
        width: 100%;
        border-collapse: collapse;
        background: #BADDEA;
        border-radius: 10px;
        overflow: hidden;
    }

    table th, table td {
        padding: 12px;
        text-align: center;
        border: 1px solid #FFEFEF;
    }

    /* --- FOOTER --- */
    p {
        text-align: center;
        margin-top: 20px;
        color: #555;
    }
  </style>
</head>
<body>
  <h2>Kondisi Cuaca Daerah Jayapura</h2>
  <hr>
  <p style="text-align:center;">Lokasi</p>
  <iframe 
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d127399.7833455976!2d140.6151148!3d-2.5916025!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x686c580de57e80e9%3A0x3039d80b220d6e0!2sJayapura%2C%20Kota%20Jayapura%2C%20Papua!5e0!3m2!1sid!2sid!4v1701420000000" 
    width="100%" 
    height="400" 
    style="border:0;" 
    allowfullscreen="" 
    loading="lazy" 
    referrerpolicy="no-referrer-when-downgrade">
  </iframe>

  <table>
    <tr>
      <th>No.</th>
      <th>Hari</th>
      <th>Tanggal</th>
      <th>Suhu (°C)</th>
      <th>Kelembapan (%)</th>
    </tr>
    <tr>
      <td>1</td>
      <td>Senin</td>
      <td>1/12/25</td>
      <td>31°C</td>
      <td>62%</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Selasa</td>
      <td>2/12/25</td>
      <td>24°C</td>
      <td>98%</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Rabu</td>
      <td>3/12/25</td>
      <td>23°C</td>
      <td>99%</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Kamis</td>
      <td>4/12/25</td>
      <td>23°C</td>
      <td>99%</td>
    </tr>
    <tr>
      <td>5</td>
      <td>Jumat</td>
      <td>5/12/25</td>
      <td>22°C</td>
      <td>99%</td>
    </tr>
    <tr>
      <td>6</td>
      <td>Sabtu</td>
      <td>6/12/25</td>
      <td>30°C</td>
      <td>68%</td>
    </tr>
    <tr>
      <td>7</td>
      <td>Minggu</td>
      <td>7/12/25</td>
      <td>23°C</td>
      <td>99%</td>
    </tr>
  </table>

  <p>dibuat &copy; oleh Maurinda Denis Arista</p>
</body>
</html>
