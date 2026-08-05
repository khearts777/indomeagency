<!DOCTYPE html>
<html lang="en">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Indome Agency</title>

<style>

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');


*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
    scroll-behavior:smooth;
}


body{
    background:#fff7ed;
    color:#333;
}



/* HEADER */

header{
    background:linear-gradient(90deg,#ff9966,#ffcc70);
    padding:20px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:sticky;
    top:0;
    z-index:100;
}


.logo h2{
    color:white;
    font-size:30px;
}


.logo p{
    color:white;
}



nav a{
    color:white;
    text-decoration:none;
    margin-left:25px;
    font-weight:600;
}



nav a:hover{
    color:#8b4513;
}




/* HERO */


.hero{

    height:90vh;

    background:
    linear-gradient(rgba(0,0,0,.35),rgba(0,0,0,.35)),
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
    font-size:60px;
}


.hero p{
    font-size:20px;
    max-width:700px;
    margin:25px;
}



/* BUTTON */


.button{

    background:linear-gradient(45deg,#ff7b54,#ffb26b);

    color:white;

    text-decoration:none;

    padding:15px 35px;

    border-radius:50px;

    font-weight:bold;

    display:inline-block;

    transition:.3s;

}


.button:hover{

    transform:scale(1.08);

}





/* SECTIONS */


section{

    padding:70px 10%;

}


h2{

    text-align:center;

    font-size:40px;

    margin-bottom:20px;

}





/* CARDS */


.cards{

    display:grid;

    grid-template-columns:repeat(auto-fit,minmax(320px,1fr));

    gap:35px;

    margin-top:40px;

}



.card{

    background:white;

    padding:30px;

    border-radius:20px;

    box-shadow:0 10px 25px rgba(0,0,0,.15);

    border-top:10px solid #ff9966;

    transition:.3s;

}


.card:hover{

    transform:translateY(-10px);

}



.card h3{

    color:#ff7b54;

    font-size:28px;

}



.card h4{

    margin-top:20px;

    color:#e67e22;

}



.card li{

    margin:8px;

}





/* OFFER */


#offer{

    background:linear-gradient(90deg,#ff9966,#ffcc70);

    color:white;

    border-radius:30px;

}


.offer-box{

    background:white;

    color:#333;

    padding:40px;

    border-radius:20px;

    text-align:center;

}


.offer-box h3{

    color:#ff7b54;

    font-size:30px;

}





/* CONTACT */


.contact-box{

    background:white;

    padding:35px;

    border-radius:20px;

    text-align:center;

    box-shadow:0 10px 20px rgba(0,0,0,.1);

}




/* FOOTER */


footer{

    background:#333;

    color:white;

    text-align:center;

    padding:25px;

}





@media(max-width:800px){

header{

    flex-direction:column;

}


nav{

    margin-top:15px;

}


.hero h1{

    font-size:40px;

}

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

<a href="#home">Home</a>

<a href="#packages">Packages</a>

<a href="#offer">Offers</a>

<a href="#contact">Contact</a>

</nav>


</header>





<section class="hero" id="home">


<h1>
Nothing Beats An Indome Agency
</h1>


<p>
Explore Indonesia with luxury stays,
amazing food, adventure and unforgettable memories.
</p>


<a class="button" href="#packages">
Explore Packages
</a>


</section>






<section id="packages">


<h2>🌏 Our Holiday Packages</h2>


<div class="cards">





<div class="card">


<h3>🏙️ City-Girl Holiday</h3>

<h4>5 Days 4 Nights</h4>


<p>
Perfect for shopping lovers, foodies,
and luxury travellers.
</p>


<h4>Day 1 – Jakarta</h4>

<ul>
<li>✈️ Airport pickup</li>
<li>5-star hotel check-in</li>
<li>Welcome dinner</li>
<li>Grand Indonesia Mall</li>
</ul>


<h4>Day 2 – Jakarta</h4>

<ul>
<li>Plaza Indonesia shopping</li>
<li>Café hopping</li>
<li>Kota Tua Old Town</li>
<li>Sunset rooftop dinner</li>
</ul>


<h4>Day 3 – Bandung</h4>

<ul>
<li>The Great Asia Africa</li>
<li>Factory outlets</li>
<li>Luxury spa</li>
</ul>


<h4>Day 4 – Bandung</h4>

<ul>
<li>Scenic café brunch</li>
<li>Floating Market Lembang</li>
<li>Souvenir shopping</li>
</ul>


<h4>Includes</h4>

<ul>
<li>⭐ 5-star hotel</li>
<li>🚐 Transfers</li>
<li>🍽️ Breakfast</li>
<li>🛍️ Shopping guide</li>
</ul>


<a class="button" href="#contact">
Book Now
</a>


</div>








<div class="card">


<h3>🎈 Urban Adventure</h3>


<h4>5 Days 4 Nights</h4>


<p>
Perfect for nature lovers
and thrill seekers.
</p>



<h4>Day 1 – Yogyakarta</h4>

<ul>
<li>Malioboro Street</li>
<li>Local food tasting</li>
</ul>



<h4>Day 2</h4>

<ul>
<li>🌄 Borobudur Sunrise Tour</li>
<li>🎈 Hot-air balloon</li>
<li>Village cycling</li>
</ul>



<h4>Day 3</h4>

<ul>
<li>🚙 Mount Merapi Jeep Tour</li>
<li>Lava Museum</li>
<li>Campfire dinner</li>
</ul>



<h4>Day 4</h4>

<ul>
<li>Waterfall trekking</li>
<li>Cave tubing</li>
<li>Cultural performance</li>
</ul>



<h4>Includes</h4>

<ul>
<li>🚙 Jeep tour</li>
<li>🎈 Balloon experience</li>
<li>🥾 Guided hikes</li>
<li>🏨 Hotel stay</li>
</ul>



<a class="button" href="#contact">
Book Now
</a>



</div>



</div>


</section>







<section id="offer">


<h2>🎉 Special Offer</h2>


<div class="offer-box">


<h3>
Sign Up For An Indome Holiday Today!
</h3>


<p>
Get exclusive deals, travel planning,
and unforgettable Indonesian experiences.
</p>


<br>


<a class="button" href="#contact">
Claim Offer
</a>


</div>


</section>







<section id="contact">


<h2>📩 Contact Us</h2>


<div class="contact-box">

<p>Email: indomeagency@gmail.com</p>

<p>Phone: +65 8888 8888</p>

<p>Start your dream holiday with Indome Agency!</p>


</div>


</section>





<footer>

© 2026 Indome Agency 🌴
<br>
Nothing Beats An Indome Holiday

</footer>



</body>

</html>
