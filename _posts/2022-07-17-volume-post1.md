---
title: Exoplanets
tags: [astronomy, volume]
style: border                               #border, fill, 
color: danger                           #primary, secondary, success, danger, warning, info, light, dark
description: ASTROINFO [Post-1]
external_url:  
comments: false
---

<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.mySlides {display:none;}
button{
  font-size: 40px;
  margin: 10px;
}
#container2{
  text-align: center;
}
.slider-button{
  border: none;
  outline: none;
  z-index: 2;
  top: 50%;
}
</style>
<body>

<div class="container1">
  <img class="mySlides" src="../assets/img-volume/post-1/EXOPLANETS-1.png" width="300">
  <img class="mySlides" src="../assets/img-volume/post-1/EXOPLANETS-2.png" width="300">
  <img class="mySlides" src="../assets/img-volume/post-1/EXOPLANETS-3.png" width="300">
  <img class="mySlides" src="../assets/img-volume/post-1/EXOPLANETS-4.png" width="300">
  <img class="mySlides" src="../assets/img-volume/post-1/EXOPLANETS-5.png" width="300">
  <img class="mySlides" src="../assets/img-volume/post-1/EXOPLANETS-6.png" width="300">
  <img class="mySlides" src="../assets/img-volume/post-1/EXOPLANETS-7.png" width="300">
  <img class="mySlides" src="../assets/img-volume/post-1/EXOPLANETS-8.png" width="300">
  <div id="container2">
    <button type="button" class="slider-button" onclick="plusDivs(-1)">&#10094;</button>
    <button type="button" class="slider-button" onclick="plusDivs(1)">&#10095;</button>
  </div>
</div>

<script>
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  if (n > x.length) {slideIndex = 1}
  if (n < 1) {slideIndex = x.length}
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  x[slideIndex-1].style.display = "block";  
}
</script>

</body>
