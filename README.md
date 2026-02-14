[index.html](https://github.com/user-attachments/files/25309647/index.html)
<!DOCTYPE html>
<html>
<head>
  <title>Website Lukman</title>
  <style>
    body {
      text-align: center;
      font-family: Arial, sans-serif;
      margin-top: 50px;
    }

    button {
      padding: 12px 25px;
      font-size: 18px;
      cursor: pointer;
      border: none;
      background-color: #28a745;
      color: white;
      border-radius: 8px;
    }

    img {
      margin-top: 20px;
      max-width: 300px;
      display: none;
      border-radius: 10px;
    }
  </style>
</head>
<body>

  <button onclick="tampilkanGambar()">Klik Disini</button>

  <br>
  <img id="gambarSaya" src="IMG_2866.PNG" alt="Gambar Lukman">

  <script>
    function tampilkanGambar() {
      document.getElementById("gambarSaya").style.display = "block";
    }
  </script>

</body>
</html>
