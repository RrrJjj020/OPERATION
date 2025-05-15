<html>
<head>
  <title>Contoh Klik Sederhana</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
    }

    button {
      font-size: 18px;
      padding: 10px 20px;
      margin: 10px 0;
      cursor: pointer;
    }

    .pesan {
      display: none;
      margin: 10px 0;
      padding: 10px;
      border-left: 4px solid #007BFF;
      background-color: #f0f8ff;
      cursor: pointer;
      animation: fadeIn 0.5s ease-in-out;
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }
  </style>
</head>
<body>
  <h1 onclick="toggle('pesan1')">kamu siapa?</h1>
  <p id="pesan1" class="pesan" onclick="window.open('', '_blank')">
    Ini aku yg sangat sangat suka jalan jalan
  </p>
  <h2 onclick="toggle(pesan2)">Klik tulisan ini!</h2>
  <p id="pesan2" class="pesan" onclick="window.open('', '_blank')">
    Ini adalah pesan yang muncul saat diklik.
  </p>
  <script>
    function toggle(id) {
      const el = document.getElementById(id);
      el.style.display = (el.style.display === "none") ? "block" : "none";
    }
  </script>
</body>
</html>
