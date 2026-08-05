<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Indome Agency | Luxury Indonesia Holidays</title>


<style>

@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500;700&family=Poppins:wght@300;400;600&display=swap');


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

    font-family:'Cormorant Garamond',serif;

}




/* NAVBAR */


header{

    background:#fffaf2;

    padding:20px 8%;

    display:flex;

    justify-content:space-between;

    align-items:center;

    position:sticky;

    top:0;

    z-index:999;

    box-shadow:0 5px 20px rgba(0,0,0,.1);

}



.logo h2{

    color:#c9a45c;

    font-size:36px;

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

    letter-spacing:2px;

}



.hero p{

    font-size:22px;

    max-width:750px;

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

display:inline-block;


}



.button:hover{

    background:#a88648;

    transform:translateY(-5px);

}







/* TITLES */


.section-title{

text-align:center;

font-size:55px;

color:#c9a45c;

margin-bottom:50px;

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

border-top:5px solid #c9a45c;

transition:.3s;


}




.why-card:hover{

transform:translateY(-10px);

}



.why-card h3{

font-size:30px;

color:#c9a45c;

margin-bottom:15px;

}



.why-card p{

line-height:1.7;

}</style>

</head>


<body>



<header>

<div class="logo">

<h2>🌴 Indome Agency</h2>

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
Curated journeys, premium stays and unforgettable experiences across Indonesia.
</p>


<a class="button" href="#packages">
Explore Packages
</a>


</section>








<section class="why">


<h2 class="section-title">
Why Choose Indome?
</h2>


<div class="why-cards">


<div class="why-card">

<h3>
🏨 Luxury Stays
</h3>

<p>
Hand-picked hotels, resorts and unique accommodations for a comfortable journey.
</p>

</div>



<div class="why-card">

<h3>
🌏 Unique Experiences
</h3>

<p>
From temples and islands to city adventures, discover Indonesia in style.
</p>

</div>




<div class="why-card">

<h3>
🧳 Stress-Free Travel
</h3>

<p>
We arrange transport, activities and unforgettable moments for you.
</p>

</div>


</div>


</section>










<section id="packages" class="packages">


<h2 class="section-title">
Our Signature Packages
</h2>








<!-- PACKAGE 1 -->


<div class="package-card">


<div class="banner city" onclick="openPackage('city')">

<h2>
🏙️ City-Girl Holiday
</h2>

</div>



<div class="details" id="city">


<h2>
🏙️ City-Girl Holiday
</h2>


<h3>
5 Days 4 Nights
</h3>


<p>
Perfect for shopping lovers, foodies and luxury travellers.
</p>




<h3>
Day 1 – Jakarta
</h3>

<ul>

<li>✈️ Airport pickup</li>

<li>🏨 5-star hotel check-in</li>

<li>🍽️ Welcome dinner</li>

<li>🛍️ Grand Indonesia Mall</li>

</ul>





<h3>
Day 2 – Jakarta
</h3>

<ul>

<li>Plaza Indonesia shopping</li>

<li>Café hopping</li>

<li>Kota Tua Old Town</li>

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

<li>Floating Market Lembang</li>

<li>Souvenir shopping</li>

</ul>





<h3>
Includes
</h3>

<ul>

<li>⭐ 5-star hotel</li>

<li>🚐 Airport transfers</li>

<li>🍽️ Breakfast daily</li>

<li>🛍️ Shopping guide</li>

<li>📸 Photo stops</li>

</ul>



<a class="button">
Book Now
</a>


</div>


</div>










<!-- PACKAGE 2 -->


<div class="package-card">


<div class="banner adventure" onclick="openPackage('adventure')">


<h2>
🎈 Urban Adventure
</h2>


</div>





<div class="details" id="adventure">


<h2>
🎈 Urban Adventure
</h2>


<h3>
5 Days 4 Nights
</h3>


<p>
Perfect for nature lovers and thrill seekers.
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

<li>🚙 Mount Merapi Jeep Adventure</li>

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



<a class="button">
Book Now
</a>



</div>


</div><!-- PACKAGE 3 -->


<div class="package-card">


<div class="banner outlander" onclick="openPackage('outlander')">


<h2>
🌴 Outlander Package
</h2>


</div>




<div class="details" id="outlander">


<h2>
🌴 Outlander Package (Chic Nomad)
</h2>


<h3>
5 Days 4 Nights
</h3>


<p>
Perfect for relaxation and beautiful scenery.
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



<a class="button">
Book Now
</a>


</div>


</div>


</section>









<!-- COMPARISON -->


<section class="comparison">


<h2 class="section-title">
Find Your Perfect Escape
</h2>


<table>


<tr>

<th>Package</th>

<th>Best For</th>

<th>Style</th>

</tr>


<tr>

<td>🏙️ City-Girl Holiday</td>

<td>Shopping & Food</td>

<td>Luxury City</td>

</tr>


<tr>

<td>🎈 Urban Adventure</td>

<td>Nature Lovers</td>

<td>Adventure</td>

</tr>


<tr>

<td>🌴 Outlander</td>

<td>Relaxation</td>

<td>Beach Escape</td>

</tr>


</table>


</section>








<!-- REVIEWS -->


<section class="reviews">


<h2 class="section-title">
Guest Experiences
</h2>



<div class="review-box">


<p>
⭐⭐⭐⭐⭐
</p>


<p>
"The Bali glamping experience was magical.
Everything was planned perfectly!"
</p>


<h3>
— Amelia, Singapore
</h3>


</div>





<div class="review-box">


<p>
⭐⭐⭐⭐⭐
</p>


<p>
"Indome Agency made our Indonesia trip
smooth, luxurious and unforgettable."
</p>


<h3>
— Ethan, Malaysia
</h3>


</div>


</section>








<!-- OFFER -->


<section class="offer">


<h2>
✨ Limited Luxury Offer
</h2>


<p>
Book your Indome Holiday today and receive exclusive travel benefits.
</p>


<br>


<a class="button">
Reserve Your Trip
</a>


</section>








<!-- BOOKING FORM -->


<section id="contact" class="contact">


<h2 class="section-title">
Start Your Journey
</h2>




<form>


<input type="text" placeholder="Your Name">


<input type="email" placeholder="Email Address">


<select>

<option>
Choose Package
</option>

<option>
🏙️ City-Girl Holiday
</option>

<option>
🎈 Urban Adventure
</option>

<option>
🌴 Outlander Package
</option>

</select>



<textarea placeholder="Special Requests"></textarea>



<button>
Submit Booking
</button>



</form>



</section>







<footer>


<h2>
🌴 Indome Agency
</h2>


<p>
Nothing Beats An Indome Holiday
</p>


<p>
© 2026 Indome Agency
</p>


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
