---
title: People
layout: page
---
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
    * {
  box-sizing: border-box;
}

h1 {text-align: center;}

img {
    border-radius: 50%;
    width: 150px;
    height: 150px;
}

.column {
  float: left;
  width: 45%;
}

.row {
    display: flex;
    justify-content: space-around; /* Align columns horizontally with space between */
}

.container.column.is-centered {
    display: flex;
    flex-direction: column;
    justify-content: center; /* Center content vertically */
    align-items: center; /* Center content horizontally */
}

.container.is-centered {
    display: flex;
    justify-content: center;
    align-items: center;
}

.container.is-centered a {
    margin: 0 10px; /* Optional: Add some horizontal space between the images */
}

.center {
    max-width: 100%; /* Ensure images don't exceed container width */
    height: auto; /* Maintain aspect ratio */
    display: block; /* Remove any default inline spacing */
}

</style>
</head>
<body>
<div class="row">
    <div class="container column is-centered"> 
        <h1>Current supervisors</h1>
        <div class="container is-centered">
            <a href="https://scholar.google.com/citations?user=vsskO0AAAAAJ&hl=fr">
                <img src="assets/images/people/brovelli.jpg" title="Andrea Brovelli" class="center">
            </a>
            <a href="https://matthieugilson.eu/">
                <img src="assets/images/people/gilson.jpg" title="Matthieu Gilson"  class="center">
            </a>
        </div>
    </div>
    <div class="container column is-centered">
        <h1>Past supervisors</h1>
        <div class="container is-centered">
            <a href="https://matematicalm.campusnet.unito.it/do/docenti.pl/Alias?federica.galluzzi#tab-profilo">
                <img src="assets/images/people/galluzzi.jpg" title="Federica Galluzzi" class="center">
            </a>
            <a href="https://lordgrilo.github.io/">
                <img src="assets/images/people/petri.jpg" title="Giovanni Petri" class="center">
            </a>
        </div>
    </div>
</div>

<div class="container is-centered">
    <h1>Co-authors</h1>
</div>
<div class="container is-centered">
        <a href="https://scholar.google.it/citations?user=mozT7wUAAAAJ&hl=en">
            <img src="assets/images/people/gili.jpg" title="Tommaso Gili" class="center">
        </a>
        <a href="https://scholar.google.com/citations?user=4XfzoZQAAAAJ&hl=en">
            <img src="assets/images/people/vaccarino.png" title="Francesco Vaccarino" class="center">
        </a>
        <a href="https://maximelucas.github.io/">
            <img src="assets/images/people/lucas.jpg" title="Maxime Lucas" class="center">
        </a>
        <a href="https://scholar.google.com/citations?user=vAaWpu8AAAAJ&hl=it">
            <img src="assets/images/people/nurisso.jpg" title="Marco Nurisso" class="center">
        </a>
</div>
