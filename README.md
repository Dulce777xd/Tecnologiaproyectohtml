<!DOCTYPE html>
<html>
<head>
<title>Mi primer página</title>
<title>Bootstrap 5 Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>





</head>
<body>


<div class="container-fluid p-5 bg-primary text-white text-center">
  <h1>Tecnología de la Información</h1>
  <h2>Curso 4º 2da turno mañana</h2> 
</div>
  <p>Estamos prácticando páginas web.</p>
<div class="container mt-5">
  <div class="row">
    <div class="col-sm-4">
      <h3>El Cóndor</h3>
<p>El cóndor andino, también conocido como cóndor de los Andes o simplemente cóndor, es una especie emblematica de sudamerica y es considerada patrimonio natural y cultural del continente.</p>
<br>
<img src="condor.png" alt="Condor"width="300" height="300">
      <p>..</p>
      
        </div>

    <div class="col-sm-4">
      <h3>El Hornero</h3>
      <p>El hornero, es un ave emblematica de america del sur. Es el ave nacional de Argentina y simboliza la identidad cultural del pais. Es conocido por su habilidad para construir nidos de barro, lo que refleja el ingenio y la tenacidad del pueblo argentino.</p>
      <img src="hornero.png" alt="hornero"width="300" height="300">
      <p>..</p>

    </div>
    <div class="col-sm-4">
      <h3>El Yaguarete</h3>        
      <p>El yaguarete, es una de las diez especies de felinos silvestres que habitan en Argentina, es el felino mas grande de latinoamerica y el tercero a nivel mundial y es una especie en extincion por deforestacion, caza y atropellamiento. </p>
      <img src="yaguarete.png" alt="yaguarete"width="300" height="300">
      <p>..</p>
    </div>
  </div>
</div>

<div style="text-align:center">
  <button onclick="playPause()">Play/Pause</button>
  <button onclick="makeBig()">Big</button>
  <button onclick="makeSmall()">Small</button>
  <button onclick="makeNormal()">Normal</button>
  <br><br>
  <video id="video" width="420">
    <source src="PROYECTO.mp4" type="video/mp4">
    <source src="video.ogg" type="video/ogg">
    Your browser does not support HTML video.
  </video>
</div>

<script>
var myVideo = document.getElementById("video");

function playPause() {
  if (myVideo.paused)
    myVideo.play();
  else
    myVideo.pause();
}

function makeBig() {
    myVideo.width = 560;
}

function makeSmall() {
    myVideo.width = 320;
}

function makeNormal() {
    myVideo.width = 420;
}
</script>









</body>
</html>
