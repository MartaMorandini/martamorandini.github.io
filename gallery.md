---
title: Gallery
layout: page
---

<html>
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial;
}

.header {
  text-align: center;
  padding: 32px;
}

.row {
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
  padding: 0 4px;
}

/* Create four equal columns that sits next to each other */
.column {
  -ms-flex: 32%; /* IE10 */
  flex: 32%;
  max-width: 32%;
  padding: 0 2px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
  width: 100%;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 800px) {
  .column {
    -ms-flex: 50%;
    flex: 50%;
    max-width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    -ms-flex: 100%;
    flex: 100%;
    max-width: 100%;
  }
}

.container {
  position: relative;
  /* width: 50%;
  max-width: 300px;
}

/* The overlay effect - lays on top of the container and over the image */
.overlay {
  position: absolute;
  bottom: 0;
  background: rgb(0, 0, 0);
  background: rgba(0, 0, 0, 0.5); /* Black see-through */
  color: #f1f1f1;
  width: 100%;
  transition: .5s ease;
  opacity:0;
  color: white;
  font-size: 20px;
  padding: 20px;
  text-align: center;
}

/* When you mouse over the container, fade in the overlay title */
.container:hover .overlay {
  opacity: 1;
}

</style>
<body>

<!-- Photo Grid -->
<div class="row"> 
  <div class="column">
      <div class="container">
        <img src="/assets/images/gallery/catania_2020.jpg" style="width:100%">
        <div class="overlay">Catania, 2020</div>
      </div>
      <div class="container">
        <img src="/assets/images/gallery/cavaglià_2021.jpg" style="width:100%">
        <div class="overlay">Cavaglià, 2021</div>
      </div>
       <div class="container">
        <img src="/assets/images/gallery/orangerie_2023.png" style="width:100%">
        <div class="overlay">Paris, 2023</div>
      </div>
       <div class="container">
        <img src="/assets/images/gallery/alba_2020.JPG" style="width:100%">
        <div class="overlay">Alba, 2020</div>
      </div>
  </div>
  <div class="column">
     <div class="container">
        <img src="/assets/images/gallery/orsay_2023.JPG" style="width:100%">
        <div class="overlay">Paris, 2023</div>
      </div>
      <div class="container">
        <img src="/assets/images/gallery/longchamp_2024.jpeg" style="width:100%">
        <div class="overlay">Marseille, 2024</div>
      </div>
      <div class="container">
        <img src="/assets/images/gallery/musaba_2019.jpg" style="width:100%">
        <div class="overlay">Parco Museo MUSABA, 2019</div>
      </div>
      <div class="container">
        <img src="/assets/images/gallery/venezia_2023.JPG" style="width:100%">
        <div class="overlay">Venezia, 2023</div>
      </div>
      <div class="container">
        <img src="/assets/images/gallery/pisa_2022.jpeg" style="width:100%">
        <div class="overlay">Pisa, 2022</div>
      </div>
  </div>  
  <div class="column">
    <div class="container">
        <img src="/assets/images/gallery/viverone_2022.jpeg" style="width:100%">
        <div class="overlay">Viverone, 2022</div>
    </div>
     <div class="container">
        <img src="/assets/images/gallery/jago_2023.jpeg" style="width:100%">
        <div class="overlay">Napoli, 2023</div>
      </div>
       <div class="container">
        <img src="/assets/images/gallery/cavaglià_2022.jpeg" style="width:100%">
        <div class="overlay">Cavaglià, 2022</div>
    </div>
      <div class="container">
        <img src="/assets/images/gallery/matera_2020.JPG" style="width:100%">
        <div class="overlay">Matera, 2020</div>
      </div>
  </div>
</div>

</body>
</html>