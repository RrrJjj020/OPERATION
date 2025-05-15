<html>
<head>
  <title>Contoh Klik Sederhana</title>
  <style>
    #pesan {
      display: none;
      margin-top: 10px;
      color: blue;
    }
  </style>
</head>
<body>
  <h1 onclick="togglePesan()">kamu siapa?</h1>
  <p id="pesan">Ini aku yg sangat sangat suka jalan jalan</p>
  <h2 onclick="togglePesan()">Klik tulisan ini!</h2>
  <p id="pesan">Ini adalah pesan yang muncul saat diklik.</p>
  <script>
    function togglePesan() {
      var pesan = document.getElementById("pesan");
      if (pesan.style.display === "none") {
        pesan.style.display = "block";
      } else {
        pesan.style.display = "none";
      }
    }
  </script>
</body>
</html>
