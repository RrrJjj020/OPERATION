<html>
<head>
  <title>Interaktif ANDA KAMU</title>
  <style>
    body {
      background-image: url('Wanted.jpg');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      margin: 0;
      height: 100vh;
      padding: 0;
      color: white;
      font-family: sans-serif;
    }
    .content {
      padding-top: 20%;
      text-align: center;
    }
    body {
      font-family: Arial, sans-serif;
    }
    p, a {
      cursor: pointer;
      margin: 5px 0;
      font-size: 35px;
      text-decoration: none;
    }
    .hidden {
      display: none;
    }
    .ya {
      cursor: pointer;
      color: green;
      font-weight: bold;
      text-align: center;
    }
    .tidak {
      cursor: not-allowed;
      color: red;
      font-weight: bold;
      text-align: center;

    #kamuContent {
      text-align: center;
    }
  </style>
</head>
<body>
  <h1 style="text-align: center;">Selamat Datang Di Website Ini</h1>
  <p onclick="toggleAnda()" style="text-align: center;">Ini Adalah Website Khusus Untuk Orang Tercinta</p>
  <div id="andaContent" class="hidden">
    <p onclick="toggleKamu()" style="text-align: center;">Klik ini Untuk Mengetahuinya</p>
    <div id="kamuContent" class="hidden">
      <a href="Nah.jpg" target="_blank" class="ya" style="display: block; text-align: center;">Klik Gambar</a>
      <br>
      <a href="keren.jpg" target="_blank" class="tidak" style="display: block; text-align: center;">Jangan di Klik</a>
    </div>
    
    <p onclick="errorSaya()" style="text-align: center;">jangan di buka</p>
  </div>
  <div style="width: 50%; margin: auto; text-align: center;">
    <p>&copy;2025 Bertemu Kembaran</p>
  </div>
  <script>
    function toggleAnda() {
      document.getElementById("andaContent").classList.toggle("hidden");
    }
    function toggleKamu() {
      document.getElementById("kamuContent").classList.toggle("hidden");
    }
    function errorSaya() {
      alert("❌ INI ORANG KEREN CUY!!! JANGAN MEMBANTAH!!!");
    }
  </script>
</body>
</html>
