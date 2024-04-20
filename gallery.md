---
title: Gallery
layout: page
---
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box;}

.image {
  display: block;
  width: 30%;
  height: auto;
}

.overlay {
  position: absolute; 
  bottom: 0; 
  background: rgb(0, 0, 0);
  background: rgba(0, 0, 0, 0.5); /* Black see-through */
  color: #f1f1f1; 
  width: 30%;
  transition: .5s ease;
  opacity:0;
  color: white;
  font-size: 20px;
  padding: 20px;
  text-align: center;
}

.container:hover .overlay {
  opacity: 1;
}
</style>
</head>
<body>

<div class="container has-centered-text">
  <img src="assets/images/gallery/monet.JPG" alt="Avatar" class="image">
  <div class="overlay">My Name is John</div>
</div>

</body>
</html>