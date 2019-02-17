
<!DOCTYPE html>
<html>

<body style="background-color: #B3DCBB ; ">

<head>
<link rel="stylesheet" href="styleethical.css">
<h1><font size="80">Conscious Consumer</font></h1>
</head>

<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
    @import url('https://fonts.googleapis.com/css?family=Playfair+Display+SC');
body { font-family: 'Playfair Display SC', serif; }

.sidenav { height: 100%; width: 0; position: fixed; z-index: 1; top: 0; left: 0; background-color: #D6DCF1; overflow-x: hidden; transition: 0.5s; padding-top: 60px; text-align:center; }
.sidenav a { padding: 8px 8px 8px 32px; text-decoration: none; font-size: 25px; color: #818181; display: block; transition: 0.3s; }
.sidenav .closebtn { position: absolute; top: 0; right: 25px; font-size: 36px; margin-left: 50px; }

@media screen and (max-height: 450px) {
.sidenav {padding-top: 15px;}
.sidenav a {font-size: 18px;}
}
</style>

<div id="mySidenav" class="sidenav">
<a href="javascript:void(0)" class="closebtn" onclick="closeNav()">&times;</a>
<a text><b>What do we define as sustainable?</a></b>
<a text>We define sustainable as products/businesses that are organic, fair-trade, or locally sourced
    within the Southeast U.S.
</a>
<br>
<br>
<br>
<a href="https://www.usda.gov/topics/organic" target="_blank">  <font size="4">Click to learn more about organic</a></font>
<a href="https://www.fairtradecertified.org/" target="_blank"><font size="4">Click to learn more about fair trade</a></font>
</div>

<h2> <span style="font-size:20px;cursor:pointer" onclick="openNav()">&#9776; Why sustainable?</span> </h2>

<script>
function openNav() {
document.getElementById("mySidenav").style.width = "100%";
}

function closeNav() {
document.getElementById("mySidenav").style.width = "0";
}
</script>

<div id="wrapper">
 <div class="column"><div id="food"> 
   <div class="flip-card">
     <div class="flip-card-inner">
       <div class="flip-card-front">
         <img src="foodlogo.jpg.png" alt="Avatar" style="width:200px;height:200px;">
       </div>
       <div class="flip-card-back">
         <h3>Food</h3>
         <p><a href=#breakfast>Breakfast</a></p>
         <p><a href=#linner>Lunch/Dinner</a></p>
         <p><a href=#dessert>Coffee/Dessert</a></p>
       </div>
     </div>
     </div>
   </div>
 </div>
<div class="column"><div id="clothes"> 
 <div class="flip-card">
   <div class="flip-card-inner">
     <div class="flip-card-front">
       <img src="clotheslogo.png" alt="Avatar" style="width:200px;height:200px;">
     </div>
     <div class="flip-card-back">
       <h3>Clothes</h3>
       <p><a href=#used>Used</a></p>
     </div>
     </div>
   </div>
 </div>
</div>

<br>
<div class="section"><a name="breakfast"><font size="5">Breakfast</a></font>
<br>
<!-- THIS IS THE FIRST ONE -->
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
 #overlay9 {
 position: fixed;
 display: none;
 width: 100%;
 height: 100%;
 top: 0;
 left: 0;
 right: 0;
 bottom: 0;
 background-color: rgba(0,0,0,0.5);
 z-index: 2;
 cursor: pointer;
 }
 #text{
 position: absolute;
 top: 50%;
 left: 50%;
 font-size: 20px;
 color: white;
 transform: translate(-50%,-50%);
 -ms-transform: translate(-50%,-50%);
 }
</style>
  <script>
   function on9() {
       document.getElementById("overlay9").style.display = "block";
   }
   function off9() {
       document.getElementById("overlay9").style.display = "none";
   }
 </script>
  <div id="overlay9" onclick="off9()">
 <div id="text">
     <h2>Ye Olde Waffle Shoppe</h2>
     <p>http://www.yeoldewaffleshoppe.com/</p>
     <p> 173 E Franklin Street Chapel Hill, NC 27514</p>
     <p>Why it's sustainable: Ye Olde Waffle House is a restaurant that uses locally-sourced, organic ingredients. </p>
 </div>
 </div>
  <div class="column">
 <div id="b1">
 <div style="padding:20px">
 <h4>Ye Olde Waffle Shoppe</h4>
 <img src=https://static1.squarespace.com/static/50454623e4b0b97fe5aa64c5/51d32d56e4b0b8187479b629/51d32e60e4b0b8d0c5d93c2e/1372794474879/DSC_0324.jpg alt="b1" style="width:200px;height:200px;" onclick="on9()">
 </div> </div>
 </div>

<!-- THIS IS THE SECOND ONE -->
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
#overlay10 {
position: fixed;
display: none;
width: 100%;
height: 100%;
top: 0;
left: 0;
right: 0;
bottom: 0;
background-color: rgba(0,0,0,0.5);
z-index: 2;
cursor: pointer;
}
#text{
position: absolute;
top: 50%;
left: 50%;
font-size: 20px;
color: white;
transform: translate(-50%,-50%);
-ms-transform: translate(-50%,-50%);
}
</style>

<script>
 function on10() {
     document.getElementById("overlay10").style.display = "block";
 }
 function off10() {
     document.getElementById("overlay10").style.display = "none";
 }
</script>

<div id="overlay10" onclick="off10()">
<div id="text">
   <h2>Perennial</h2>
   <p>https://www.perennial.cafe/</p>
   <p> 403 W Franklin St, Chapel Hill, NC 27516 </p>
   <p>Why it's sustainable: Perennial is a restaurant that uses locally-sourced, organic ingredients. </p>
</div>
</div>

<div class="column">
<div id="b2">
<div style="padding:20px">
<h4>Perennial</h4>
<img src=https://assets.simpleviewinc.com/simpleview/image/upload/crm/chapelhill/Perennial-Coffee-Pastries-1-3--385197385056b3a_385198f5-5056-b3a8-49b6140e5396c28d.jpg alt="b2" style="width:200px;height:200px;" onclick="on10()">
</div> </div>
</div>
</div>

<div class="section"> <a name="linner"><font size="5">Lunch/Dinner</a></font>
<br>
<!-- THIS IS THE THIRD ONE -->
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
#overlay12 {
position: fixed;
display: none;
width: 100%;
height: 100%;
top: 0;
left: 0;
right: 0;
bottom: 0;
background-color: rgba(0,0,0,0.5);
z-index: 2;
cursor: pointer;
}
#text{
position: absolute;
top: 50%;
left: 50%;
font-size: 20px;
color: white;
transform: translate(-50%,-50%);
-ms-transform: translate(-50%,-50%);
}
</style>

<script>
 function on12() {
     document.getElementById("overlay12").style.display = "block";
 }
 function off12() {
     document.getElementById("overlay12").style.display = "none";
 }
</script>

<div id="overlay12" onclick="off12()">
<div id="text">
   <h2>CholaNad Restaurant and Bar</h2>
   <p>http://cholanad.com/ </p>
   <p> 308 W Franklin St Chapel Hill, NC 27516 </p>
   <p>Why it's sustainable: CholaNad is a restaurant that uses locally-sourced, organic ingredients. </p>
</div>
</div>

<div class="column">
<div id="b3">
<div style="padding:20px">
<h4>CholaNad Restaurant and Bar</h4>
<img src=http://navigatingfoodatunc.web.unc.edu/files/2017/11/IMG_0338-e1510082464386-480x420.jpg alt="b3" style="width:200px;height:200px;" onclick="on12()">
</div> </div>
</div>

<!-- THIS IS THE FOURTH ONE -->
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
#overlay13 {
position: fixed;
display: none;
width: 100%;
height: 100%;
top: 0;
left: 0;
right: 0;
bottom: 0;
background-color: rgba(0,0,0,0.5);
z-index: 2;
cursor: pointer;
}
#text{
position: absolute;
top: 50%;
left: 50%;
font-size: 20px;
color: white;
transform: translate(-50%,-50%);
-ms-transform: translate(-50%,-50%);
}
</style>

<script>
 function on13() {
     document.getElementById("overlay13").style.display = "block";
 }
 function off13() {
     document.getElementById("overlay13").style.display = "none";
 }
</script>

<div id="overlay13" onclick="off13()">
<div id="text">
   <h2>Top of the Hill Restaurant and Brewery</h2>
   <p>https://www.thetopofthehill.com/ </p>
   <p> 100 East Franklin Street Chapel Hill, NC 27514 </p>
   <p>Why it's sustainable: Top of the Hill is a restaurant that uses locally-sourced, organic ingredients. </p>
</div>
</div>

<div class="column">
<div id="b4">
<div style="padding:20px">
<h4>Top of the Hill Restaurant and Brewery</h4>
<img src=https://upload.wikimedia.org/wikipedia/commons/thumb/5/52/Franklin_Street_Chapel_Hill_NC.jpg/1200px-Franklin_Street_Chapel_Hill_NC.jpg alt="b4" style="width:200px;height:200px;" onclick="on13()">
</div> </div>
</div>
</div>

<div class="section"><a name="dessert"><font size="5">Coffee/Dessert</a></font>
<br>

<!-- THIS IS THE FIFTH ONE -->
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
#overlay14 {
position: fixed;
display: none;
width: 100%;
height: 100%;
top: 0;
left: 0;
right: 0;
bottom: 0;
background-color: rgba(0,0,0,0.5);
z-index: 2;
cursor: pointer;
}
#text{
position: absolute;
top: 50%;
left: 50%;
font-size: 20px;
color: white;
transform: translate(-50%,-50%);
-ms-transform: translate(-50%,-50%);
}
</style>

<script>
 function on14() {
     document.getElementById("overlay14").style.display = "block";
 }
 function off14() {
     document.getElementById("overlay14").style.display = "none";
 }
</script>

<div id="overlay14" onclick="off14()">
<div id="text">
   <h2>Market Street Coffee & Ice Cream</h2>
   <p>http://marketstcoffee.com/#contact /</p>
   <p> Address: 227 S Elliott Road, Chapel Hill, NC 27514 </p>
   <p>Why it's sustainable: Market Street Coffee and Ice Cream is a restaurant that uses locally-sourced, organic ingredients. </p>
</div>
</div>

<div class="column">
<div id="b5">
<div style="padding:20px">
<h4>Market Street Coffee & Ice Cream</h4>
<img src=https://s3-media4.fl.yelpcdn.com/bphoto/dPsDQ7iOhtmbuMjmUAljLQ/ls.jpg alt="b5" style="width:200px;height:200px;" onclick="on14()">
</div> </div>
</div>

<!-- SIXTH ONE, LAST ONE -->
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
#overlay15 {
position: fixed;
display: none;
width: 100%;
height: 100%;
top: 0;
left: 0;
right: 0;
bottom: 0;
background-color: rgba(0,0,0,0.5);
z-index: 2;
cursor: pointer;
}
#text{
position: absolute;
top: 50%;
left: 50%;
font-size: 20px;
color: white;
transform: translate(-50%,-50%);
-ms-transform: translate(-50%,-50%);
}
</style>

<script>
 function on15() {
     document.getElementById("overlay15").style.display = "block";
 }
 function off15() {
     document.getElementById("overlay15").style.display = "none";
 }
</script>

<div id="overlay15" onclick="off15()">
<div id="text">
   <h2>Open Eye Cafe</h2>
   <p>https://openeyecafe.com/</p>
   <p> Address: 101 S GREENSBORO ST, CARRBORO, NC 27510 </p>
   <p>Why it's sustainable: Open Eye Cafe is a restaurant that uses locally-sourced, organic ingredients. </p>
</div>
</div>

<div class="column">
<div id="b6">
<div style="padding:20px">
<h4>Open Eye Cafe</h4>
<img src=https://openeyecafe.com/wp-content/uploads/2017/02/oe-hp-slider-1.jpg alt="b6" style="width:200px;height:200px;" onclick="on15()">
</div> </div>
</div>
</div>

<div class="section"><a name="used"><font size="5">Used Clothes</a></font>
<br>
<!-- LOL CLOTHES 1 -->
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
#overlay0 {
position: fixed;
display: none;
width: 100%;
height: 100%;
top: 0;
left: 0;
right: 0;
bottom: 0;
background-color: rgba(0,0,0,0.5);
z-index: 2;
cursor: pointer;
}
#text{
position: absolute;
top: 50%;
left: 50%;
font-size: 20px;
color: white;
transform: translate(-50%,-50%);
-ms-transform: translate(-50%,-50%);
}
</style>

<script>
 function on0() {
     document.getElementById("overlay0").style.display = "block";
 }
 function off0() {
     document.getElementById("overlay0").style.display = "none";
 }
</script>

<div id="overlay0" onclick="off0()">
<div id="text">
   <h2>Rumors</h2>
   <p>Website: facebook.com/rumorschapelhill</p>
   <p> Address: 106 North Graham Street Suite C Chapel Hill, North Carolina </p>
   <p>Why it's sustainable: Rumors sells gently-used clothing; making it an environmentally sustainable option for jazzing up your wardrobe.</p>
</div>
</div>

<div class="column">
<div id="c1">
<div style="padding:20px">
<h4>Rumors</h4>
<img src=https://s3-media1.fl.yelpcdn.com/bphoto/3bYFEtyGxyhCI3wYqGOwIA/ls.jpg alt="c1" style="width:200px;height:200px;" onclick="on0()">
</div>
</div>



</body>
</html>
