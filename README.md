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
