<html>
<head>
  <title>Interaktif ANDA KAMU</title>
  <style>
    body {
      background-image: url('Franco.jpg');
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
    }
    .tidak {
      cursor: not-allowed;
      color: red;
      font-weight: bold;

    #kamuContent {
      text-align: center;
    }
  </style>
</head>
<body>
  <p onclick="toggleAnda()" style="text-align: center;">Hati-Hati ada kembarannya Hendry</p>
  <div id="andaContent" class="hidden">
    <p onclick="toggleKamu()" style="text-align: center;">Jangan di buka nanti nyesal</p>
    <div id="kamuContent" class="hidden">
      <a href="https://www.pinterest.com/pin/167829523609590445/" target="_blank" class="ya">Klik Gambar</a>
      <br>
      <a href="https://www.pinterest.com/pin/71072500370112573/" target="_blank" class="tidak">Jangan di Klik</a>
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
      alert("❌ MEMANG MIRIP SEKALI SAMA HENDRY!");
    }
  </script>
</body>
</html>
