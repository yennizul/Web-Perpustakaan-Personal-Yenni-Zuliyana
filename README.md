# Web-Perpustakaan-Personal-Yenni-Zuliyana
web
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>internalcss</title>
</head>
<body>

<style type="text/css">

body {
    background-color: red;
}
.fContainer {
    display: flex;
    justify-content:center;
    width: 100%;
    height: 25vh;
    background-color:pink;
}

.wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 20px;
    padding: 15px;
    width: 800px;
    height: 80px;
    background-color:blueviolet;
}

.brand {
    display: flex;
    flex-direction: row;
    font-size: 20px;
    text-transform: capitalize;
}

.firstname {
    color:black;
    font-size: 30px;
    font-weight: 700;
}

.navigation {
    display: flex;
    justify-content: center;
    align-items: center;
}

.navigation>li {
    list-style-type: none;
    padding: 15px;
}

.navigation>li>a {
    color: black;
    text-decoration: none;
    text-transform: capitalize;
    font-size: 20px;
}


.nomor1 {
    color:black;
    font-size: 20px;
    font-variant: small-caps;
}

.nomor2 {
    text-transform: capitalize;
}

</style>


  <div class="fContainer">
  <nav class="wrapper">
    <div class="brand">
      <div class="firstname">Perpustakaan</div>
    </div>
    <ul class="navigation">
      <li><a href="/">Profil</a></li>
      <li><a href="/">Pendaftaran</a></li>
      <li><a href="/">Sirkulasi</a></li>
      <li><a href="Modul 3 nomor 2.html">Pengenalan HTML dan CSS </a></li>
      <li><a href="Modul 4 Table and Bodered.html">Table dan Bodered </a></li>
    </ul>
  </nav>
  </div>

  <div class="nomor1"> <ul><li>Perpustakaan Nasional Republik Indonesia (Perpusnas) </li></ul>
  </div>

  <div>
    <a href="https://www.perpusnas.go.id/">
      <img src="Poto Perpustakaan Nasional.jpg" alt="">
    </a>
    
</div>
<div class="nomor2">Perpustakaan Nasional Republik Indonesia adalah lembaga yang mengumpulkan, melestarikan, dan menyediakan akses kepada berbagai bahan pustaka yang mencerminkan kekayaan intelektual dan budaya Indonesia.
</div>


<div class="nomor1"> <ul><li>Perpustakaan Universitas Sumatera Utara</li></ul>
</div>

<div>
  <a href="https://library.usu.ac.id/">
    <img src="Poto Perpustakaan Universitas Sumatera Utara.jpg" alt="">
  </a>
  
</div>
<div class="nomor2">Perpustakaan Universitas Sumatera Utara adalah fasilitas yang menyediakan akses kepada berbagai bahan pustaka untuk mendukung kegiatan akademik, penelitian, dan pengembangan ilmu di lingkungan universitas tersebut.
</div>

<div class="nomor1"> <ul><li>Perpustakaan Bung Hatta</li></ul>
</div>

<div>
  <a href="https://upt-perpusbunghatta.perpusnas.go.id">
    <img src="Poto Perpustakaan Bung Hatta.jpg" alt="">
  </a>
  
</div>
<div class="nomor2">Perpustakaan Bung Hatta menyimpan koleksi bahan pustaka yang berkaitan dengan pemikiran dan karya ekonomi serta politik Bung Hatta, salah satu founding father Indonesia.
</div>
  
</body>
</html>
