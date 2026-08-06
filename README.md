<All travel plans are not exact!>
<html lang="en">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Indome Agency | Luxury Indonesia Holidays</title>

<style>

@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Poppins:wght@300;400;600&display=swap');


*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}


body{
    background:#faf7f0;
    color:#3a2f25;
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

    box-shadow:0 5px 20px rgba(0,0,0,.12);

}


.logo h2{

    color:#c9a45c;
    font-size:35px;

}


.logo p{

    font-size:13px;
    letter-spacing:1px;

}



nav a{

    text-decoration:none;
    color:#3a2f25;

    margin-left:25px;

    font-weight:600;

}


nav a:hover{

    color:#c9a45c;

}




/* HERO */


.hero{

    height:95vh;

    background:

    linear-gradient(
    rgba(0,0,0,.35),
    rgba(0,0,0,.35)
    ),

    url("https://images.unsplash.com/photo-1537996194471-e657df975ab4");


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

    font-size:85px;

    letter-spacing:3px;

}



.hero p{

    font-size:22px;

    max-width:700px;

    margin:25px;

}




.button{

    background:#c9a45c;

    color:white;

    padding:16px 40px;

    border-radius:50px;

    text-decoration:none;

    font-weight:bold;

    transition:.3s;

}



.button:hover{

    background:#a88648;

    transform:translateY(-5px);

}





/* SECTION TITLE */


.section-title{

    text-align:center;

    color:#c9a45c;

    font-size:55px;

    margin-bottom:40px;

}




/* WHY CHOOSE US */


.why{

    padding:90px 10%;

}



.why-cards{

    display:grid;

    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));

    gap:30px;

}



.why-card{

    background:white;

    padding:35px;

    border-radius:25px;

    text-align:center;

    box-shadow:0 10px 25px rgba(0,0,0,.1);

}



.why-card h3{

    color:#c9a45c;

    font-size:30px;

    margin-bottom:15px;

}


</style>

</head>


<body>


<header>


<div class="logo">

<h2>🌴 Indome Agency</h2>

<p>Nothing Beats An Indome Holiday</p>

</div>



<nav>

<a href="#packages">Packages</a>

<a href="#booking">Booking</a>

<a href="#contact">Contact</a>

</nav>



</header>





<section class="hero">


<h1>
Luxury Indonesia Escapes
</h1>


<p>
Experience unforgettable journeys,
beautiful destinations and premium stays.
</p>


<a href="#packages" class="button">
Explore Packages
</a>



</section>






<section class="why">


<h2 class="section-title">
Why Choose Indome?
</h2>


<div class="why-cards">


<div class="why-card">

<h3>🏨 Luxury Stays</h3>

<p>
Carefully selected hotels and resorts for your comfort.
</p>

</div>



<div class="why-card">

<h3>✈️ Easy Travel</h3>

<p>
Airport transfers and travel planning handled for you.
</p>

</div>




<div class="why-card">

<h3>✨ Unique Experiences</h3>

<p>
Create memories with exclusive Indonesian adventures.
</p>

</div>



</div>


</section><!-- PACKAGES SECTION -->

<section id="packages" class="packages">


<h2 class="section-title">
Our Signature Packages
</h2>



<style>


.packages{

    padding:90px 10%;

}



.package-card{

    margin-bottom:50px;

}



.package-banner{

    height:280px;

    border-radius:30px;

    display:flex;

    justify-content:center;

    align-items:center;

    color:white;

    font-size:45px;

    font-family:'Playfair Display',serif;

    cursor:pointer;

    background-size:cover;

    background-position:center;

    text-shadow:0 3px 15px black;

    transition:.4s;

}



.package-banner:hover{

    transform:scale(1.03);

}




.city{

background:

linear-gradient(rgba(0,0,0,.35),rgba(0,0,0,.35)),

url("https://images.unsplash.com/photo-1555899434-94d1368aa7af");

}



.adventure{

background:

linear-gradient(rgba(0,0,0,.35),rgba(0,0,0,.35)),

url("https://images.unsplash.com/photo-1464822759023-fed622ff2c3b");

}




.outlander{

background:

linear-gradient(rgba(0,0,0,.35),rgba(0,0,0,.35)),

url("https://images.unsplash.com/photo-1537996194471-e657df975ab4");

}



.itinerary{

display:none;

background:white;

padding:40px;

border-radius:25px;

margin-top:20px;

box-shadow:0 10px 25px rgba(0,0,0,.12);

}



.itinerary h2{

color:#c9a45c;

}



.itinerary h3{

color:#a88648;

margin-top:20px;

}



.itinerary li{

margin:10px 0;

}



</style>







<!-- CITY GIRL -->


<div class="package-card">


<div class="package-banner city"
onclick="openTrip('cityTrip')">


🏙️ City-Girl Holiday


</div>




<div class="itinerary" id="cityTrip">


<h2>
🏙️ City-Girl Holiday
</h2>


<h3>
5 Days 4 Nights
</h3>


<p>
Perfect for: Shopping lovers, foodies and luxury travellers.
</p>



<h3>
Day 1 – Jakarta
</h3>

<ul>

<li>✈️ Airport pickup</li>

<li>🏨 Check into a 5-star hotel</li>

<li>🍽️ Welcome dinner</li>

<li>🛍️ Indonesia Mall</li>

</ul>




<h3>
Day 2 – Jakarta
</h3>

<ul>

<li>Plaza Indonesia shopping</li>

<li>Café hopping</li>

<li>Visit an old town</li>

<li>Sunset rooftop dinner</li>

</ul>




<h3>
Day 3 – Bandung
</h3>

<ul>

<li>Travel to Bandung</li>

<li>The Great Asia Africa</li>

<li>Factory outlets</li>

<li>Luxury spa</li>

</ul>




<h3>
Day 4 – Bandung
</h3>

<ul>

<li>Scenic café brunch</li>

<li>Floating Market </li>

<li>Souvenir shopping</li>

</ul>




<h3>
Includes</h3>

<ul>

<li>⭐ 5-star hotel</li>

<li>🚐 Airport transfers</li>

<li>🍽️ Breakfast daily</li>

<li>🛍️ Shopping guide</li>

</ul>


<br>

<a href="#booking" class="button">
Reserve This Holiday
</a>


</div>


</div>









<!-- URBAN ADVENTURE -->


<div class="package-card">


<div class="package-banner adventure"
onclick="openTrip('adventureTrip')">


🎈 Urban Adventure


</div>





<div class="itinerary" id="adventureTrip">


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

<li>Famous Street</li>

<li>Local food tasting</li>

</ul>




<h3>
Day 2
</h3>

<ul>

<li>🌄 Sunrise Tour</li>

<li>🎈 Hot-air balloon experience</li>

<li>Village cycling</li>

</ul>




<h3>
Day 3
</h3>

<ul>

<li>🚙 Jeep Adventure</li>

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
Includes
</h3>

<ul>

<li>🚙 Jeep tour</li>

<li>🎈 Hot-air balloon</li>

<li>🥾 Guided hikes</li>

<li>🏨 Hotel stay</li>

</ul>


<br>


<a href="#booking" class="button">
Reserve This Holiday
</a>



</div>


</div><!-- OUTLANDER PACKAGE -->


<div class="package-card">


<div class="package-banner outlander"
onclick="openTrip('outlanderTrip')">


🌴 Outlander Package


</div>




<div class="itinerary" id="outlanderTrip">


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

<li>✈️ Airport pickup</li>

<li>🏖️ Beach resort check-in</li>

<li>🌅 Sunset dinner</li>

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

<li>🚤 Nusa Penida island tour</li>

<li>🤿 Snorkelling</li>

<li>Crystal Bay</li>

</ul>




<h3>
Day 4
</h3>

<ul>

<li>⛺ Luxury glamping</li>

<li>🔥 Campfire</li>

<li>✨ Stargazing</li>

<li>🍖 BBQ dinner</li>

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
Includes
</h3>

<ul>

<li>🏖️ Beach resort</li>

<li>⛺ Luxury glamping</li>

<li>🚤 Island tour</li>

<li>🤿 Snorkelling</li>

<li>🚐 Airport transfers</li>

</ul>



<br>


<a href="#booking" class="button">
Reserve This Holiday
</a>



</div>


</div>



</section>








<!-- BOOKING -->


<section id="booking" class="booking">


<h2 class="section-title">
Book Your Indome Holiday
</h2>



<form>


<input type="text" placeholder="Full Name">


<input type="email" placeholder="Email Address">


<input type="tel" placeholder="Phone Number">


<select>

<option>Select Package</option>

<option>🏙️ City-Girl Holiday</option>

<option>🎈 Urban Adventure</option>

<option>🌴 Outlander Package</option>


</select>



<input type="number" placeholder="Number of Travellers">


<input type="date">


<textarea placeholder="Special Requests"></textarea>



<button>
Submit Booking
</button>



</form>


</section>








<!-- REVIEWS -->


<section class="reviews">


<h2 class="section-title">
Guest Reviews
</h2>



<div class="review">

⭐⭐⭐⭐⭐

<p>
"Indome planned our Bali holiday perfectly. 
Every moment was unforgettable!"
</p>

<h3>
— Sarah, Singapore
</h3>

</div>



<div class="review">

⭐⭐⭐⭐⭐

<p>
"The luxury hotel and experiences were amazing!"
</p>

<h3>
— Daniel, Malaysia
</h3>

</div>



</section>








<!-- CONTACT -->


<section id="contact" class="contact">


<h2 class="section-title">
Contact Us
</h2>


<p>
📞 +65 8888 8888
</p>


<p>
📧 indomeagency@gmail.com
</p>


<p>
📍 Singapore
</p>


<p>
🕘 Monday - Friday | 9AM - 6PM
</p>



</section>







<!-- OFFER -->


<section class="offer">


<h2>
✨ Exclusive Indome Offer
</h2>


<p>
Book your dream Indonesia escape today and enjoy premium travel benefits.
</p>


<br>


<a href="#booking" class="button">
Start Booking
</a>


</section><style>


/* BOOKING */

.booking{

padding:90px 10%;

text-align:center;

}



form{

max-width:650px;

margin:auto;

background:white;

padding:40px;

border-radius:30px;

box-shadow:0 10px 25px rgba(0,0,0,.12);

}



form input,
form select,
form textarea{


width:100%;

padding:15px;

margin:12px 0;

border-radius:15px;

border:1px solid #ddd;

font-family:'Poppins',sans-serif;


}



form textarea{

height:120px;

resize:none;

}



form button{

background:#c9a45c;

color:white;

border:none;

padding:15px 40px;

border-radius:50px;

font-weight:bold;

cursor:pointer;

font-size:16px;

}



form button:hover{

background:#a88648;

}






/* REVIEWS */


.reviews{

padding:80px 10%;

display:grid;

grid-template-columns:repeat(auto-fit,minmax(250px,1fr));

gap:30px;

}



.review{


background:white;

padding:35px;

border-radius:25px;

box-shadow:0 10px 20px rgba(0,0,0,.1);

text-align:center;

}



.review:first-letter{

color:#c9a45c;

}



.review h3{

color:#c9a45c;

margin-top:15px;

}






/* CONTACT */


.contact{

padding:80px 10%;

text-align:center;

background:#fffaf2;

}



.contact p{

font-size:18px;

margin:15px;

}







/* OFFER */


.offer{

margin:60px 10%;

padding:60px;

background:#c9a45c;

color:white;

border-radius:35px;

text-align:center;

}



.offer h2{

font-size:45px;

}








/* FOOTER */


footer{

background:#3a2f25;

color:white;

padding:35px;

text-align:center;

}



footer h2{

color:#c9a45c;

}




/* MOBILE */


@media(max-width:800px){


header{

flex-direction:column;

}


nav{

margin-top:15px;

}



.hero h1{

font-size:50px;

}



.package-banner{

font-size:32px;

}


}



</style>






<footer>


<h2>
🌴 Indome Agency
</h2>


<p>
Nothing Beats An Indome Holiday
</p>


<p>
© 2026 Indome Agency | Luxury Indonesia Escapes
</p>


</footer>






<script>


function openTrip(id){


let trip=document.getElementById(id);



if(trip.style.display==="block"){


trip.style.display="none";


}

else{


trip.style.display="block";


}


}



</script>





</body>

</html>
