<!DOCTYPE html>
<html lang="en">

<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Indome Agency 🌴</title>


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
    background:#fff8ef;
    color:#333;
}




/* HEADER */

header{

    background:linear-gradient(90deg,#ff9966,#ffc371);

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

    font-weight:bold;

}





/* HERO BANNER */


.hero{


height:100vh;


background:

linear-gradient(
rgba(0,0,0,.35),
rgba(0,0,0,.35)
),

url("https://images.unsplash.com/photo-1537996194471-e657df975ab4");


background-size:cover;

background-position:center;


display:flex;

justify-content:center;

align-items:center;

flex-direction:column;


text-align:center;

color:white;


}



.hero h1{

font-size:65px;

}



.hero p{

font-size:22px;

max-width:700px;

margin:25px;

}





.button{


background:#ff7b54;

color:white;

padding:15px 35px;

border-radius:50px;

text-decoration:none;

font-weight:bold;

transition:.3s;


}



.button:hover{

background:#e85d3f;

transform:scale(1.1);

}





/* SECTION */


section{

padding:90px 10%;

}



.title{

text-align:center;

font-size:42px;

margin-bottom:30px;

}





/* PACKAGE SECTIONS */


.package{


min-height:100vh;

display:flex;

align-items:center;

gap:50px;


}



.package:nth-child(even){

background:#fff0df;

}





.package img{


width:45%;

height:400px;

object-fit:cover;

border-radius:30px;


}



.package-info{


background:white;

padding:40px;

border-radius:30px;

box-shadow:0 10px 30px rgba(0,0,0,.15);


}



.package-info h2{

color:#ff7b54;

font-size:35px;

}



.package-info h3{

margin-top:20px;

color:#e67e22;

}



.package-info li{

margin:10px;

}






/* OFFER */


.offer{


background:linear-gradient(90deg,#ff9966,#ffc371);

color:white;

text-align:center;

border-radius:30px;


}



.offer h2{

font-size:40px;

}



.offer .button{

background:white;

color:#ff7b54;

}





/* CONTACT */


.contact{

text-align:center;

}



.contact-box{


background:white;

padding:40px;

border-radius:25px;

box-shadow:0 10px 25px rgba(0,0,0,.1);


}





footer{


background:#333;

color:white;

text-align:center;

padding:25px;


}





@media(max-width:900px){


.package{

flex-direction:column;

}


.package img{

width:100%;

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

<a href="#city">City</a>

<a href="#adventure">Adventure</a>

<a href="#contact">Contact</a>


</nav>


</header>







<section class="hero" id="home">


<h1>
Nothing Beats An Indome Agency
</h1>


<p>
Discover Indonesia through luxury,
culture, food and adventure.
</p>


<a class="button" href="#city">
Explore Holidays
</a>


</section>









<section class="package" id="city">


<img src="https://images.unsplash.com/photo-1555899434-94d1368aa7af">


<div class="package-info">


<h2>🏙️ City-Girl Holiday</h2>


<h3>5 Days 4 Nights</h3>


<p>
Perfect for shopping lovers,
foodies and luxury travellers.
</p>


<h3>Itinerary</h3>


<ul>

<li>Day 1: Jakarta airport pickup, 5-star hotel, welcome dinner, Grand Indonesia Mall</li>

<li>Day 2: Plaza Indonesia shopping, café hopping, Kota Tua, rooftop dinner</li>

<li>Day 3: Bandung trip, The Great Asia Africa, factory outlets, luxury spa</li>

<li>Day 4: Scenic café brunch, Floating Market Lembang, souvenirs</li>

<li>Day 5: Breakfast and airport transfer</li>


</ul>



<h3>Includes</h3>


<ul>

<li>⭐ 5-star hotel</li>

<li>🚐 Airport transfers</li>

<li>🍽️ Breakfast daily</li>

<li>🛍️ Shopping guide</li>

<li>📸 Photo stops</li>

</ul>



<a href="#contact" class="button">
Book City-Girl Holiday
</a>


</div>


</section>










<section class="package" id="adventure">


<img src="https://images.unsplash.com/photo-1516690561799-46d8f74f9abf">



<div class="package-info">


<h2>🎈 Urban Adventure</h2>


<h3>5 Days 4 Nights</h3>


<p>
Perfect for nature lovers
and thrill seekers.
</p>



<h3>Itinerary</h3>


<ul>


<li>Day 1: Yogyakarta, Malioboro Street, local food tasting</li>


<li>Day 2: Borobudur sunrise tour, hot-air balloon, village cycling</li>


<li>Day 3: Mount Merapi jeep adventure, Lava Museum, campfire dinner</li>


<li>Day 4: Waterfall trekking, cave tubing, cultural performance</li>


<li>Day 5: Souvenir shopping and airport transfer</li>


</ul>



<h3>Includes</h3>


<ul>

<li>🚙 Jeep tour</li>

<li>🎈 Hot-air balloon</li>

<li>🥾 Guided hikes</li>

<li>🍽️ Meals</li>

<li>🏨 Hotel stay</li>


</ul>



<a href="#contact" class="button">
Book Urban Adventure
</a>


</div>


</section>









<section class="offer">


<h2>🎉 Special Indome Offer</h2>


<p>
Sign up today and enjoy exclusive holiday benefits!
</p>


<br>


<a href="#contact" class="button">
Claim Offer
</a>


</section>







<section class="contact" id="contact">


<h2 class="title">
📞 Contact Us
</h2>



<div class="contact-box">


<p>
📧 indomeagency@gmail.com
</p>


<p>
📱 +65 8888 8888
</p>


<p>
🌏 Your dream Indonesia holiday starts here!
</p>


</div>


</section>








<footer>


© 2026 Indome Agency 🌴
<br>
Nothing Beats An Indome Holiday


</footer>




</body>

</html>
