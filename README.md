<!DOCTYPE html>
<html>
<head>

<!-- Font Awesome Icon Library -->
<link rel="stylesheet"
href="https://cdnjs.cloudflare.com/ajax/libs/font-
awesome/4.7.0/css/font-awesome.min.css">

<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

<style>

.checked {
  color: orange;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}

.navbar {
  overflow: hidden;
  background-color: blue; 
}

.navbar a {
  float: left;
  font-size: 16px;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

.subnav {
  float: left;
  overflow: hidden;
}

.subnav .subnavbtn {
  font-size: 16px;  
  border: none;
  outline: none;
  color: white;
  padding: 14px 16px;
  background-color: inherit;
  font-family: inherit;
  margin: 0;
}

.navbar a:hover, .subnav:hover .subnavbtn {
  background-color: red;
}

.subnav-content {
  display: none;
  position: absolute;
  left: 0;
  background-color: red;
  width: 100%;
  z-index: 1;
}

.subnav-content a {
  float: left;
  color: white;
  text-decoration: none;
}

.subnav-content a:hover {
  background-color: #eee;
  color: black;
}

.subnav:hover .subnav-content {
  display: block;
}
</style>
</head>
<body>


<div class="navbar">
  <a><img src="logo-6.png" height="49" width="70"></a>
  <a href="Tapaswi.html">Home</a>
  <div class="subnav">
<td><input type="text" placeholder="serch for products,brands and more" style="width:300px;height:35px;"></td>
<input type="button" value="search" style="width:120px;height:35px;">

    <button class="subnavbtn">About <i class="fa fa-caret-down"></i></button>
    <div class="subnav-content">
      <a href="About.html">know about us</a>
    </div>
  </div> 
  <div class="subnav">
    <button class="subnavbtn">categerios <i class="fa fa-caret-down"></i></button>
    <div class="subnav-content">
      <a href="earring.html">earring</a>
      <a href="necklace.html">necklace</a>
      <a href="#bangles">bangles</a>
      <a href="#leg chain">anklet</a>
     </div>
  </div> 
  <div class="subnav">
    <a href="Regester form.html">login in</a>
    <div>
    </div>
  </div>
  <a href="contact.html">Contact</a>
</div>

<div style="padding:0 16px">
  <h3>tapaswi jewellers</h3>
  <p> "about", "services" or "partners" this jewellery you can buy in tapaswi jewellery</p>
</div>

<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
</style>
</head>
<body>

<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 3</div>
  <img src="IMG_20210526_124910ima.jpeg" style="width:100%" height="500">
  <div class="text">RING</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="IMG_20210526_123306.jpeg" style="width:100%" height="500">
  <div class="text">necklace </div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 4</div>
  <img src="IMG_20210526_123630.jpeg" style="width:100%" height="500">
  <div class="text">temple jewellery Three</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">4 / 4</div>
  <img src="IMG_20210526_131134.jpeg" style="width:100%" height="500">
  <div class="text">temple jewellery Three</div>
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
</div>

<br>
<table border="0" width="100%" bgcolor="white">
<tr>
<td colspan="5"><h2>DEAL OF THE DAY</h2><hr></td>
<tr>
<th><img src="IMG_20210526_123306.jpeg" width="100%" height="21%"></th>
<th><img src="IMG_20210526_123630.jpeg" width="100%"></th>
<th><img src="IMG_20210526_123630.jpeg" width="100%"></th>
<th><img src="IMG_20210526_123630.jpeg" width="100%"></th>
</tr>

<a herf="details.html">

<tr>

<th>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star"></span>
</th>

<th>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star"></span>
</th>

<th>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star"></span>
</th>

<th>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star"></span>
</th>





<tr>
<th>20 grams</th>
<th>20 grams</th>
<th>20 grams</th>
<th>20 grams</th>

<tr>
<th><a href="details2.html"><input type="button" value="show details" style="width:120px; height:25px;"></th>

<th><input type="button" value="show details" style="width:120px; height:25px;"></th>

<th><input type="button" value="show details" style="width:120px; height:25px;"></th>

<th><input type="button" value="show details" style="width:120px; height:25px;"></th>

</tr>




</table>

<tr>
<td></td>

<br>
<table border="0" width="100%" bgcolor="white">
<tr>
<td colspan="5"><h2>RECOMMENDED JEWELLRY</h2><hr></td>
<tr>
<th><img src="IMG_20210526_124910ima.jpeg" width="100%" height="21%"></th>
<th><img src="IMG_20210526_123630.jpeg" width="100%"></th>
<th><img src="IMG_20210526_123630.jpeg" width="100%"></th>
<th><img src="IMG_20210526_123630.jpeg" width="100%"></th>
</tr>

<a href="details.html">

<th>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star"></span>
</th>


<th>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star"></span>
</th>


<th>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star"></span>
</th>



<th>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star"></span>
</th>


<tr>
<th>20 grams</th>
<th>20 grams</th>
<th>20 grams</th>
<th>20 grams</th>

<tr>
<th><a href="details.html"><input type="button" value="show details" style="width:120px; height:25px;"></th></a>

<th> <a href=""><input type="button" value="show details" style="width:120px; height:25px;"></th>

<th><input type="button" value="show details" style="width:120px; height:25px;"></th>

<th><input type="button" value="show details" style="width:120px; height:25px;"></th>

<br>
<table border="0" width="100%" bgcolor="white">
<tr>
<td colspan="5"><h2>5 STAR RATED</h2><hr></td>
<tr>
<th><img src="IMG_20210526_124910ima.jpeg" width="100%" height="21%"></th>
<th><img src="IMG_20210526_123630.jpeg" width="100%"></th>
<th><img src="IMG_20210526_123630.jpeg" width="100%"></th>
<th><img src="IMG_20210526_123630.jpeg" width="100%"></th>
</tr>

<a herf="details.html">

<th>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
</th>


<th>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
</th>


<th>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
</th>



<th>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
<span class="fa fa-star checked" style="color:orange;"></span>
</th>


<tr>
<th>20 grams</th>
<th>20 grams</th>
<th>20 grams</th>
<th>20 grams</th>

<tr>
<th><a href="details.html"><input type="button" value="show details" style="width:120px; height:25px;"></th></a>

<th> <a href=""><input type="button" value="show details" style="width:120px; height:25px;"></th>

<th><input type="button" value="show details" style="width:120px; height:25px;"></th>

<th><input type="button" value="show details" style="width:120px; height:25px;"></th>

</table>

<table border="3" width="100%" bgcolor="blue">
<tr>
<td bgcolor="black" width="25%"><font color="white"><b>QUICK LINK</b></td>
<td bgcolor="black" width="25%"><font color="white"><b>FOLLOW US</b></td>
<td bgcolor="black" width="25%"><font color="white"><b>CONTACT</b></td>
<td bgcolor="black" width="25%"><font color="white"><b>SEARCH</b></td>
</tr>

<tr>
<td>
<ul>
<li><font color="white">earring</font></li>
<li><font color="white">necklace</font></li>
<li><font color="white">anklet</font></li>
<li><font color="white">bangles</font></li>
</ul>


<td>
<ul>
<li><font color="white">facebook</font></li>
<li><font color="white">twitter</font></li>
<li><font color="white">instagram</font></li>
<li><font color="white">youtube</font></li>
</ul>

<td>
<ul>
<li><font color="white">Tapaswi jewellers</font></li>
<li><font color="white">+91 9876543210</font></li>
<li><font color="white">india</font></li>
<li><font color="white">505325</font></li>
</ul>

<td><input type="text" placeholder="search">
<input type="button" value="search">
</td>
<tr>



</table>


<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}   





</script>

</body>
</html> 
