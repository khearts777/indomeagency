<!DOCTYPE html>
<html>
<head>

<title>Indome Agency 🌴</title>

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>

@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Poppins&display=swap');

*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
}

body{
background:#faf5ed;
color:#3d3428;
font-family:Poppins,sans-serif;
}

h1,h2{
font-family:"Playfair Display",serif;
}


/* HEADER */

header{
background:#fffaf2;
padding:20px 8%;
display:flex;
justify-content:space-between;
align-items:center;
position:sticky;
top:0;
box-shadow:0 5px 20px #0002;
}

.logo h2{
color:#b08d57;
}

.logo p{
font-size:13px;
}


nav a{
text-decoration:none;
color:#5c4930;
margin:15px;
}


/* HERO */

.hero{
height:90vh;
background:
linear-gradient(#0006,#0006),
url("https://images.unsplash.com/photo-1507525428034-b723cf961d3e");

background-size:cover;
background-position:center;

display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;

color:white;
padding:20px;
}

.hero h1{
font-size:70px;
}

.hero p{
font-size:22px;
margin:25px;
}


.button{

background:#b08d57;
color:white;
padding:15px 35px;
border-radius:40px;
text-decoration:none;

}



/* PACKAGES */

.packages{
padding:70px 10%;
}


.title{
text-align:center;
font-size:45px;
color:#b08d57;
margin-bottom:40px;
}


.banner{

height:250px;

border-radius:25px;

display:flex;
justify-content:center;
align-items:center;

color:white;

font-size:40px;

font-family:"Playfair Display",serif;

cursor:pointer;

background-size:cover;
background-position:center;

margin-top:40px;

text-shadow:0 3px 10px black;

}



.city{

background-image:
linear-gradient(#0005,#0005),
url("https://images.unsplash.com/photo-1523731407965-2430cd12f5e4");

}


.adventure{

background-image:
linear-gradient(#0005,#0005),
url("https://images.unsplash.com/photo-1464822759023-fed622ff2c3b");

}


.outlander{

background-image:
linear-gradient(#0005,#0005),
url("https://images.unsplash.com/photo-1537996194471-e657df975ab4");

}



.details{

display:none;

background:white;

padding:35px;

border-radius:25px;

margin-top:15px;

box-shadow:0 10px 25px #0002;

}


.details h2{
color:#b08d57;
}


.details h3{
color:#8c6b3f;
margin-top:20px;
}


.details li{
margin:8px;
}





/* OFFER */

.offer{

margin:50px 10%;
padding:50px;

background:#b08d57;

color:white;

border-radius:30px;

text-align:center;

}



/* CONTACT */

.contact{

padding:60px;

text-align:center;

}


.box{

background:white;

padding:30px;

border-radius:20px;

box-shadow:0 10px 20px #0002;

}




footer{

background:#333;

color:white;

padding:25px;

text-align:center;

}


</style>

</head>



<body>


<header>

<div class="logo">
<h2>🌴 Indome Agency</h2>
<p>Nothing Beats An Indome Holiday.If you sign up for an indome holiday right now, you can save up to 50 dollar per person! Thats 200 dollars for a family of 4!</p>
</div>


<nav>

<a href="#packages">Packages</a>
<a href="#contact">Contact</a>

</nav>


</header>




<section class="hero">

<h1>Luxury Indonesia Escapes</h1>

<p>
Experience beautiful destinations,
premium stays and unforgettable memories.
</p>

<a class="button" href="#packages">
Explore Packages
</a>

</section>






<section class="packages" id="packages">


<h2 class="title">
Our Luxury Packages
</h2>



<div class="banner city" onclick="show('cityInfo')">
🏙️ City-Girl Holiday
</div>


<div class="details" id="cityInfo">

<h2>🏙️ City-Girl Holiday</h2>

<h3>5 Days 4 Nights</h3>

<p>
Perfect for shopping lovers, foodies and luxury travellers.
</p>

<h3>Highlights</h3>

<ul>
<li>Jakarta luxury hotel</li>
<li>Grand Indonesia Mall</li>
<li>Plaza Indonesia shopping</li>
<li>Kota Tua Old Town</li>
<li>Bandung spa experience</li>
<li>Floating Market Lembang</li>
</ul>

<h3>Includes</h3>

<ul>
<li>⭐ 5-star hotel</li>
<li>🚐 Airport transfers</li>
<li>🍽️ Breakfast</li>
<li>🛍️ Shopping guide</li>
</ul>

<a class="button">Book Now</a>

</div>





<div class="banner adventure" onclick="show('adventureInfo')">
🎈 Urban Adventure
</div>


<div class="details" id="adventureInfo">

<h2>🎈 Urban Adventure</h2>

<h3>5 Days 4 Nights</h3>

<p>
Perfect for nature lovers and thrill seekers.
</p>

<ul>
<li>Yogyakarta food adventure</li>
<li>Borobudur sunrise tour</li>
<li>Hot-air balloon experience</li>
<li>Mount Merapi jeep adventure</li>
<li>Waterfall trekking</li>
<li>Cave tubing</li>
</ul>

<h3>Includes</h3>

<ul>
<li>🚙 Jeep tour</li>
<li>🎈 Balloon experience</li>
<li>🥾 Guided hikes</li>
<li>🏨 Hotel stay</li>
</ul>

<a class="button">Book Now</a>

</div>





<div class="banner outlander" onclick="show('outlanderInfo')">
🌴 Outlander Package
</div>


<div class="details" id="outlanderInfo">

<h2>🌴 Outlander Package (Chic Nomad)</h2>

<h3>5 Days 4 Nights</h3>

<p>
Perfect for relaxation and beautiful scenery.
</p>

<ul>
<li>Bali beach resort</li>
<li>Tanah Lot Temple</li>
<li>Nusa Penida island tour</li>
<li>Snorkelling at Crystal Bay</li>
<li>Luxury glamping</li>
<li>Stargazing and BBQ dinner</li>
</ul>


<h3>Includes</h3>

<ul>
<li>🏖️ Beach resort</li>
<li>⛺ Luxury glamping</li>
<li>🚤 Island tour</li>
<li>🤿 Snorkelling</li>
</ul>


<a class="button">Book Now</a>

</div>


</section>





<section class="offer">

<h2>✨ Exclusive Indome Offer</h2>

<p>
Sign up today for your dream Indonesian holiday.
</p>

<br>

<a class="button">
Reserve Now
</a>

</section>





<section class="contact" id="contact">

<h2 class="title">
Contact Us
</h2>


<div class="box">

<p>📧 indomeagency@gmail.com</p>

<p>📱 +65 11111111</p>

</div>

</section>





<footer>

© 2026 Indome Agency 🌴

</footer>





<script>

function show(id){

let box=document.getElementById(id);

if(box.style.display=="block"){

box.style.display="none";

}

else{

box.style.display="block";

}

}

</script>


</body>

</html>
