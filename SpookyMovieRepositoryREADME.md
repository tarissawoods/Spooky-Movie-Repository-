# Spooky-Movie-Repository-
Halloween themed movie recommendation webpage built with HTML and CSS.
Features:
-Interactive movie posters
-Trailer links
-Custom styling and design


<!DOCTYPE html>
<html>
<head>
  <title>Spooky Movie Repository</title>
  <style>
    /*kind of like methods for how you want it to look*/
    .container {
      display: flex;               /* puts images in a row */
      justify-content: center;     /* centers them horizontally */
      gap: 20px;                   /* space between items */
      margin-top: 20px;       
    }

    .item {
      text-align: center;          /* centers the title above each image */
    }

    .item img {
      width: 180px;
      height: 300px;
      border-radius: 5px;
    }
  </style>
</head>

<body style="background-color:#9f040b; color:black;">

  <h1 align="center">Spooky Movie Repository 🎃</h1>
  <h3 align="center">Ta'Rissa Woods</h3>
  <h4 align="center">
    Welcome to the Spooky Movie Repository! Nothing like a few scares to set the spooky mood. 
    Click on the movies to watch the trailers and consider watching this Halloween. Happy Frights!
  </h4>
  <h4 align="center">*NOT MY VIDEOS, ALL CREDIT TO THE CREATORS*</h4>

  <div class="container"> 
    <div class="item">
      <h3>Beetlejuice (1988)</h3>
      <a href="https://www.youtube.com/watch?v=GuyNP-XyFHs" target="_blank">
        <img src="https://m.media-amazon.com/images/M/MV5BYjkwNzVlNDEtMTJlNy00OTdlLTljYWItM2RkZmZkYzY3YjM2XkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg" alt="Beetlejuice Movie Poster">
      </a>
    </div>
    <div class="item">
      <h3>Corpse Bride</h3>
      <a href="https://www.youtube.com/watch?v=EcrreL7Z98M" target="_blank">
        <img src="https://m.media-amazon.com/images/M/MV5BMTk1MTY1NjU4MF5BMl5BanBnXkFtZTcwNjIzMTEzMw@@._V1_FMjpg_UX1000_.jpg" alt="Corpse Bride Movie Poster">
      </a>
    </div>
    <div class="item">
      <h3>The Black Phone (2021)</h3>
      <a href="https://www.youtube.com/watch?v=3eGP6im8AZA" target="_blank">
        <img src="https://m.media-amazon.com/images/I/71xrBCbYJCL.jpg" alt="The Black Phone Movie Poster">
      </a>
    </div>
  </div>
  
  <div class="container"> 
    <div class="item">
      <h3>Barbarian</h3>
      <a href="https://www.youtube.com/watch?v=Dr89pmKrqkI" target="_blank">
        <img src="https://m.media-amazon.com/images/I/61Qc7JBCqwL.jpg" alt="Barbarian Movie Poster">
      </a>
    </div>
    <div class="item">
      <h3>Crimson Peak</h3>
      <a href="https://www.youtube.com/watch?v=oquZifON8Eg" target="_blank">
        <img src="https://m.media-amazon.com/images/I/719OQAc1MVL._AC_UF894,1000_QL80_.jpg" alt="Crimson Peak Movie Poster">
      </a>
    </div>
    <div class="item">
      <h3>Ghostbusters (1984)</h3>
      <a href="https://www.youtube.com/watch?v=wQAljlSmjC8" target="_blank">
        <img src="https://m.media-amazon.com/images/I/51Hdl8C50+L._AC_UF894,1000_QL80_.jpg" alt="Ghostbusters Movie Poster">
      </a>
    </div>
  </div>
  
  <div class="container"> 
    <div class="item">
      <h3>Hocus Pocus (1993)</h3>
      <a href="https://www.youtube.com/watch?v=F4e6YQFrt1s" target="_blank">
        <img src="https://m.media-amazon.com/images/I/51ns0Y-G14L._AC_UF894,1000_QL80_.jpg" alt="Hocus Pocus Movie Poster">
      </a>
    </div>
    <div class="item">
      <h3>Coraline</h3>
      <a href="https://www.youtube.com/watch?v=m9bOpeuvNwY" target="_blank">
        <img src="https://m.media-amazon.com/images/M/MV5BMzQxNjM5NzkxNV5BMl5BanBnXkFtZTcwMzg5NDMwMg@@._V1_.jpg" alt="Coraline Movie Poster">
      </a>
    </div>
    <div class="item">
      <h3>It (2017)</h3>
      <a href="https://www.youtube.com/watch?v=FnCdOQsX5kc" target="_blank">
        <img src="https://m.media-amazon.com/images/I/61L9icyqjqL.jpg" alt="It Movie Poster">
      </a>
    </div>
  </div>

  <h4><br><br>If you would like for me to add more movies to the repository, send me an email down below!</h4>
  <a href="mailto:tarissawoods@gmail.com">Send an email!</a>

</body>
</html>
