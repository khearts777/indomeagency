<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Indome Agency | Luxury Indonesia Holidays</title>


<style>

@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Poppins:wght@300;400;600&display=swap');


*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}


body{

    background:#faf5ed;
    color:#3d3428;
    font-family:'Poppins',sans-serif;

}



h1,h2,h3{

    font-family:'Playfair Display',serif;

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

    z-index:1000;

    box-shadow:0 5px 20px rgba(0,0,0,.1);

}



.logo h2{

    color:#b08d57;

    font-size:32px;

}



.logo p{

    color:#7d6848;

}





nav a{

    text-decoration:none;

    color:#5c4930;

    margin-left:25px;

    font-weight:600;

}



nav a:hover{

    color:#b08d57;

}







/* HERO */


.hero{


height:90vh;


background:


linear-gradient(
rgba(0,0,0,.35),
rgba(0,0,0,.35)
),


url("https://images.unsplash.com/photo-1507525428034-b723cf961d3e");



background-size:cover;

background-position:center;


display:flex;

flex-direction:column;

justify-content:center;

align-items:center;


text-align:center;

color:white;


}



.hero h1{

    font-size:75px;

}



.hero p{

    font-size:22px;

    max-width:750px;

    margin:25px;

}






.button{


display:inline-block;

background:#b08d57;

color:white;

padding:15px 40px;

border-radius:50px;

text-decoration:none;

font-weight:bold;

transition:.3s;

}



.button:hover{

    background:#8c6b3f;

    transform:scale(1.05);

}







/* PACKAGE AREA */


.packages{

    padding:80px 10%;

}



.title{

    text-align:center;

    font-size:45px;

    color:#b08d57;

    margin-bottom:50px;

}




.package-card{


margin-bottom:40px;


}





/* CLICKABLE BANNER */


.package-title{


height:250px;


border-radius:25px;


display:flex;


justify-content:center;


align-items:center;


font-size:40px;


color:white;


font-family:'Playfair Display',serif;


background-size:cover;


background-position:center;


cursor:pointer;


box-shadow:0 15px 30px rgba(0,0,0,.2);


transition:.4s;


}



.package-title:hover{

    transform:scale(1.02);

}





.city{

background:

linear-gradient(
rgba(0,0,0,.35),
rgba(0,0,0,.35)
),

url("https://images.unsplash.com/photo-1555899434-94d1368aa7af");

}




.adventure{


background:

linear-gradient(
rgba(0,0,0,.35),
rgba(0,0,0,.35)
),

url("https://images.unsplash.com/photo-1464822759023-fed622ff2c3b");

}




.outlander{


background:

linear-gradient(
rgba(0,0,0,.35),
rgba(0,0,0,.35)
),

url("https://images.unsplash.com/photo-1537996194471-e657df975ab4");

}






/* HIDDEN DETAILS */


.details{


display:none;


background:white;


margin-top:20px;


padding:40px;


border-radius:25px;


box-shadow:0 10px 25px rgba(0,0,0,.12);


}



.details h2{

color:#b08d57;

}



.details h3{

color:#8c6b3f;

margin-top:20px;

}



.details li{

margin:10px 0;

}



.show{

display:block;

}

</style>

</head>


<body>


<header>

<div class="logo">

<h2>Indome Agency</h2>

<p>Nothing Beats An Indome Holiday</p>

</div>


<nav>

<a href="#packages">Packages</a>

<a href="#contact">Contact</a>

</nav>

</header>






<section class="hero">

<h1>
Luxury Indonesia Escapes
</h1>


<p>
Discover breathtaking destinations,
exclusive stays and unforgettable experiences.
</p>


<a href="#packages" class="button">
Explore Packages
</a>


</section>







<section class="packages" id="packages">


<h2 class="title">
Our Luxury Holiday Packages
</h2>





<!-- CITY GIRL -->


<div class="package-card">


<div class="package-title city" onclick="openPackage('cityDetails')">

🏙️ City-Girl Holiday

</div>



<div class="details" id="cityDetails">


<h2>
🏙️ City-Girl Holiday
</h2>


<h3>
5 Days 4 Nights
</h3>


<p>
Perfect for: Shopping lovers, foodies,
and people who enjoy luxury.
</p>



<h3>
Day 1 – Jakarta
</h3>

<ul>

<li>✈️ Airport pickup</li>

<li>🏨 Check into a 5-star hotel</li>

<li>🍽️ Welcome dinner</li>

<li>🛍️ Visit Grand Indonesia Mall</li>

</ul>




<h3>
Day 2 – Jakarta
</h3>

<ul>

<li>Shopping at Plaza Indonesia</li>

<li>Café hopping</li>

<li>Kota Tua (Old Town)</li>

<li>Sunset rooftop dinner</li>

</ul>





<h3>
Day 3 – Bandung
</h3>

<ul>

<li>Travel to Bandung</li>

<li>The Great Asia Africa</li>

<li>Factory outlet shopping</li>

<li>Luxury spa</li>

</ul>





<h3>
Day 4 – Bandung
</h3>

<ul>

<li>Scenic café brunch</li>

<li>Floating Market Lembang</li>

<li>Souvenir shopping</li>

<li>Free evening</li>

</ul>





<h3>
Day 5
</h3>

<ul>

<li>Hotel breakfast</li>

<li>Airport transfer</li>

</ul>





<h3>
Package Includes
</h3>


<ul>

<li>⭐ 5-star hotel</li>

<li>🚐 Airport transfers</li>

<li>🍽️ Breakfast daily</li>

<li>🛍️ Shopping guide</li>

<li>📸 Photo stops</li>

</ul>


<br>


<a href="#contact" class="button">
Book Now
</a>


</div>

</div>










<!-- URBAN ADVENTURE -->


<div class="package-card">


<div class="package-title adventure" onclick="openPackage('adventureDetails')">


🎈 Urban Adventure


</div>



<div class="details" id="adventureDetails">


<h2>
🎈 Urban Adventure
</h2>


<h3>
5 Days 4 Nights
</h3>



<p>
Perfect for: Nature lovers and thrill seekers.
</p>




<h3>
Day 1 – Yogyakarta
</h3>


<ul>

<li>Airport pickup</li>

<li>Malioboro Street</li>

<li>Local food tasting</li>

</ul>




<h3>
Day 2
</h3>


<ul>

<li>🌄 Borobudur Sunrise Tour</li>

<li>🎈 Hot-air balloon experience</li>

<li>Village cycling</li>

</ul>





<h3>
Day 3
</h3>


<ul>

<li>🚙 Jeep adventure on Mount Merapi</li>

<li>Lava Museum</li>

<li>Campfire dinner</li>

</ul>





<h3>
Day 4
</h3>


<ul>

<li>Waterfall trekking</li>

<li>Cave tubing</li>

<li>Cultural performance</li>

</ul>





<h3>
Day 5
</h3>


<ul>

<li>Souvenir shopping</li>

<li>Airport transfer</li>

</ul>





<h3>
Package Includes
</h3>


<ul>

<li>🚙 Jeep tour</li>

<li>🎈 Hot-air balloon</li>

<li>🥾 Guided hikes</li>

<li>🍽️ Meals</li>

<li>🏨 Hotel stay</li>

</ul>



<br>


<a href="#contact" class="button">
Book Now
</a>


</div>


</div>









<!-- OUTLANDER -->


<div class="package-card">


<div class="package-title outlander" onclick="openPackage('outlanderDetails')">


🌴 Outlander Package (Chic Nomad)


</div>




<div class="details" id="outlanderDetails">


<h2>
🌴 Outlander Package (Chic Nomad)
</h2>



<h3>
5 Days 4 Nights
</h3>



<p>
Perfect for: Relaxation and beautiful scenery.
</p>





<h3>
Day 1 – Bali
</h3>


<ul>

<li>Airport pickup</li>

<li>Beach resort check-in</li>

<li>Sunset dinner</li>

</ul>





<h3>
Day 2
</h3>


<ul>

<li>Tanah Lot Temple</li>

<li>Beach picnic</li>

<li>Spa session</li>

</ul>





<h3>
Day 3
</h3>


<ul>

<li>Nusa Penida island tour</li>

<li>Snorkelling</li>

<li>Crystal Bay</li>

</ul>





<h3>
Day 4
</h3>


<ul>

<li>Luxury glamping</li>

<li>Campfire</li>

<li>Stargazing</li>

<li>BBQ dinner</li>

</ul>





<h3>
Day 5
</h3>


<ul>

<li>Morning beach walk</li>

<li>Souvenir shopping</li>

<li>Airport transfer</li>

</ul>





<h3>
Package Includes
</h3>


<ul>

<li>🏖️ Beach resort</li>

<li>⛺ Luxury glamping</li>

<li>🚤 Island tour</li>

<li>🤿 Snorkelling</li>

<li>🚐 Airport transfers</li>

</ul>




<br>


<a href="#contact" class="button">
Book Now
</a>


</div>


</div>



</section>









<section class="offer">


<h2>
✨ Exclusive Indome Offer
</h2>


<p>
Book your luxury Indonesian holiday today
and receive special travel benefits.
</p>


<br>


<a href="#contact" class="button">
Reserve Your Trip
</a>


</section>








<section id="contact" class="contact">


<h2 class="title">
Contact Us
</h2>


<div class="contact-box">


<p>📧 indomeagency@gmail.com</p>

<p>📱 +65 8888 8888</p>

<p>🤍 Your dream luxury holiday awaits.</p>


</div>


</section>








<footer>


© 2026 Indome Agency
<br>
Nothing Beats An Indome Holiday


</footer>







<script>


function openPackage(id){


let box=document.getElementById(id);


if(box.style.display==="block"){

box.style.display="none";

}

else{

box.style.display="block";

}


}


</script>



</body>

</html>
