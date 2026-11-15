<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Indome Agency | Discover Indonesia</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@400;500;600;700&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    font-family: 'DM Sans', sans-serif;
    background: #faf8f3;
    color: #39352e;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 22px 7%;
    background: white;
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: 0 2px 15px #00000008;
}

.logo {
    font-family: 'Playfair Display', serif;
    font-size: 25px;
    color: #a88749;
    letter-spacing: 2px;
    font-weight: bold;
}

nav ul {
    display: flex;
    list-style: none;
    gap: 22px;
}

nav a {
    text-decoration: none;
    color: #514b40;
    font-size: 13px;
}

nav a:hover {
    color: #b49355;
}

.hero {
    min-height: 650px;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 60px 20px;
    background: linear-gradient(#0006,#0007),
    url('https://images.unsplash.com/photo-1537996194471-e657df975ab4?w=1800') center/cover;
    color: white;
}

.hero small {
    letter-spacing: 5px;
    color: #e8d4a8;
}

.hero h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(45px, 7vw, 75px);
    margin: 25px 0;
}

.hero p {
    line-height: 1.9;
    font-size: 16px;
    margin-bottom: 30px;
}

.btn {
    display: inline-block;
    padding: 15px 30px;
    background: #b49355;
    color: white;
    border: none;
    text-decoration: none;
    cursor: pointer;
    transition: .3s;
    font-family: inherit;
}

.btn:hover {
    background: #8e703d;
}

section {
    padding: 85px 8%;
}

.heading {
    text-align: center;
    margin-bottom: 45px;
}

.heading small {
    color: #b49355;
    letter-spacing: 4px;
}

.heading h2 {
    font-family: 'Playfair Display', serif;
    font-size: 40px;
    color: #98783e;
    margin: 15px 0;
}

.heading p {
    color: #81796d;
    line-height: 1.8;
}

.about {
    background: white;
    text-align: center;
}

.about-content {
    max-width: 800px;
    margin: auto;
    line-height: 2;
    color: #70685e;
}

.features {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
}

.feature {
    background: white;
    padding: 35px 20px;
    text-align: center;
    border: 1px solid #eadfc9;
    transition: .3s;
}

.feature:hover {
    transform: translateY(-6px);
}

.feature .icon {
    font-size: 35px;
    margin-bottom: 15px;
}

.feature h3 {
    font-family: 'Playfair Display', serif;
    color: #a88749;
    margin-bottom: 12px;
}

.feature p {
    font-size: 13px;
    color: #777;
    line-height: 1.8;
}

.packages {
    background: white;
}

.package-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
    align-items: start;
}

.package-card {
    background: #faf8f3;
    border: 1px solid #eadfc9;
    overflow: hidden;
}

.package-card img {
    width: 100%;
    height: 220px;
    object-fit: cover;
    display: block;
}

.package-info {
    padding: 25px;
}

.package-info h3 {
    font-family: 'Playfair Display', serif;
    color: #98783e;
    font-size: 24px;
    margin-bottom: 12px;
}

.package-info p {
    color: #777;
    font-size: 13px;
    line-height: 1.8;
}

.price {
    font-size: 27px;
    color: #b49355;
    font-weight: bold;
    margin: 20px 0;
}

.price span {
    font-size: 12px;
    color: #888;
    font-weight: normal;
}

.toggle {
    width: 100%;
    padding: 14px;
    background: white;
    color: #98783e;
    border: 1px solid #b49355;
    cursor: pointer;
    font-family: inherit;
    transition: .3s;
}

.toggle:hover,
.toggle.active {
    background: #b49355;
    color: white;
}

.itinerary {
    display: none;
    background: white;
    padding: 22px;
    font-size: 13px;
    line-height: 1.9;
}

.itinerary.show {
    display: block;
    animation: fade .3s ease;
}

@keyframes fade {
    from {opacity: 0; transform: translateY(-8px);}
    to {opacity: 1; transform: translateY(0);}
}

.itinerary h4 {
    color: #98783e;
    font-family: 'Playfair Display', serif;
    font-size: 17px;
    margin: 16px 0 5px;
}

.includes {
    border-top: 1px solid #eadfc9;
    margin-top: 15px;
    padding-top: 10px;
}

.reviews {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 22px;
}

.review {
    background: white;
    padding: 30px;
    border: 1px solid #eadfc9;
}

.stars {
    color: #b49355;
    letter-spacing: 3px;
    margin-bottom: 15px;
}

.review p {
    color: #777;
    font-size: 14px;
    line-height: 1.9;
    margin-bottom: 20px;
}

.review h3 {
    color: #98783e;
    font-family: 'Playfair Display', serif;
}

.review small {
    color: #999;
}

.booking {
    background: white;
}

.booking-form {
    max-width: 750px;
    margin: auto;
    padding: 40px;
    background: #faf8f3;
    border: 1px solid #eadfc9;
}

.form-group {
    margin-bottom: 20px;
}

.form-group label {
    display: block;
    margin-bottom: 9px;
    font-size: 13px;
    font-weight: bold;
}

.form-group input,
.form-group select,
.form-group textarea {
    width: 100%;
    padding: 14px;
    border: 1px solid #dfd4c1;
    background: white;
    font-family: inherit;
    font-size: 14px;
}

.form-group textarea {
    min-height: 110px;
    resize: vertical;
}

.booking-form button {
    width: 100%;
}

.contact {
    background: #302c24;
    color: white;
    text-align: center;
}

.contact h2 {
    font-family: 'Playfair Display', serif;
    font-size: 42px;
    margin: 20px 0;
}

.contact p {
    color: #d5cfc2;
    line-height: 2.2;
}

.contact a {
    color: #dfc99d;
    text-decoration: none;
}

footer {
    background: #211f1a;
    color: #b9b2a6;
    text-align: center;
    padding: 25px;
    font-size: 12px;
}

@media(max-width: 850px) {
    .features {
        grid-template-columns: repeat(2, 1fr);
    }

    .package-grid,
    .reviews {
        grid-template-columns: 1fr 1fr;
    }

    nav {
        flex-direction: column;
        gap: 15px;
    }

    nav ul {
        flex-wrap: wrap;
        justify-content: center;
    }
}

@media(max-width: 550px) {
    .features,
    .package-grid,
    .reviews {
        grid-template-columns: 1fr;
    }

    section {
        padding: 60px 6%;
    }

    .booking-form {
        padding: 22px;
    }
}
</style>
</head>

<body>

<nav>
    <div class="logo">INDOME AGENCY</div>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#why">Why Us</a></li>
        <li><a href="#packages">Packages</a></li>
        <li><a href="#reviews">Reviews</a></li>
        <li><a href="#booking">Booking</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<header class="hero" id="home">
    <div>
        <small>YOUR JOURNEY BEGINS HERE</small>
        <h1>Discover Indonesia in Style.</h1>
        <p>Luxury escapes. Extraordinary adventures. Unforgettable memories.</p>
        <a href="#packages" class="btn">EXPLORE OUR PACKAGES</a>
    </div>
</header>

<section class="about" id="about">
    <div class="heading">
        <small>WELCOME TO INDOME</small>
        <h2>Travel Beyond Ordinary.</h2>
    </div>

    <div class="about-content">
        <p>
        At Indome Agency, we believe travelling should be more than
        simply visiting a destination. It should be an experience
        filled with unforgettable memories, extraordinary discoveries
        and exceptional comfort.
        </p>
        <br>
        <p>
        Specialising in Indonesian holidays, we offer carefully
        designed travel packages for every type of traveller.
        Whether you desire a luxurious city escape, an adventurous
        journey or a relaxing tropical getaway, we have the perfect
        holiday waiting for you.
        </p>
        <br>
        <h3 style="color:#98783e;font-family:Georgia;">
        Nothing beats an Indome Agency.
        </h3>
    </div>
</section>

<section id="why">
    <div class="heading">
        <small>THE INDOME EXPERIENCE</small>
        <h2>Why Choose Us?</h2>
        <p>Discover what makes travelling with Indome special.</p>
    </div>

    <div class="features">
        <div class="feature">
            <div class="icon">🏨</div>
            <h3>Luxury Hotels</h3>
            <p>Enjoy premium accommodation and exceptional comfort throughout your holiday.</p>
        </div>

        <div class="feature">
            <div class="icon">✨</div>
            <h3>Incredible Planning</h3>
            <p>Every itinerary is thoughtfully designed for a smooth and memorable experience.</p>
        </div>

        <div class="feature">
            <div class="icon">🌟</div>
            <h3>Top-Tier Guides</h3>
            <p>Explore Indonesia with knowledgeable and helpful travel guides.</p>
        </div>

        <div class="feature">
            <div class="icon">🌴</div>
            <h3>Unique Experiences</h3>
            <p>Discover extraordinary experiences beyond the ordinary.</p>
        </div>
    </div>
</section>

<section class="packages" id="packages">
    <div class="heading">
        <small>FIND YOUR PERFECT ESCAPE</small>
        <h2>Our Travel Packages</h2>
        <p>Three extraordinary journeys. One unforgettable destination.</p>
    </div>

    <div class="package-grid">

        <div class="package-card">
            <img src="https://images.unsplash.com/photo-1555899434-94d1368aa7af?w=900" alt="Jakarta city">

            <div class="package-info">
                <h3>City-Girl Holiday</h3>
                <p>Perfect for shopping lovers, foodies and those who enjoy luxury.</p>
                <div class="price">$3,500 <span>/ person</span></div>

                <button class="toggle" onclick="togglePlan('city',this)">
                    City-Girl Holiday ♡
                </button>
            </div>

            <div class="itinerary" id="city">
                <h4>Day 1 – Jakarta</h4>
                <p>✈️ Airport pickup<br>🏨 5-star hotel check-in<br>🍽️ Welcome dinner<br>🛍️ Grand Indonesia Mall</p>

                <h4>Day 2 – Jakarta</h4>
                <p>Plaza Indonesia shopping<br>Café hopping<br>Kota Tua (Old Town)<br>Sunset rooftop dinner</p>

                <h4>Day 3 – Bandung</h4>
                <p>Travel to Bandung<br>The Great Asia Africa<br>Factory outlets<br>Luxury spa</p>

                <h4>Day 4 – Bandung</h4>
                <p>Scenic café brunch<br>Floating Market Lembang<br>Souvenir shopping<br>Free evening</p>

                <h4>Day 5</h4>
                <p>Hotel breakfast<br>Airport transfer</p>

                <div class="includes">
                    <h4>Package Includes</h4>
                    <p>⭐ 5-star hotel<br>🚐 Airport transfers<br>🍽️ Breakfast daily<br>🛍️ Shopping guide<br>📸 Photo stops</p>
                </div>
            </div>
        </div>

        <div class="package-card">
            <img src="https://images.unsplash.com/photo-1596402184320-417e7178b2cd?w=900" alt="Yogyakarta">

            <div class="package-info">
                <h3>Urban Adventurer</h3>
                <p>Perfect for nature lovers and thrill seekers.</p>
                <div class="price">$1,999 <span>/ person</span></div>

                <button class="toggle" onclick="togglePlan('urban',this)">
                    Urban Adventurer ♡
                </button>
            </div>

            <div class="itinerary" id="urban">
                <h4>Day 1 – Yogyakarta</h4>
                <p>Airport pickup<br>Malioboro Street<br>Local food tasting</p>

                <h4>Day 2 – Sunrise Adventure</h4>
                <p>🌄 Borobudur Sunrise Tour<br>🎈 Hot-air balloon experience<br>Village cycling</p>

                <h4>Day 3 – Mount Merapi</h4>
                <p>Jeep adventure<br>Lava Museum<br>Campfire dinner</p>

                <h4>Day 4 – Nature Exploration</h4>
                <p>Waterfall trekking<br>Cave tubing<br>Cultural performance</p>

                <h4>Day 5</h4>
                <p>Souvenir shopping<br>Airport transfer</p>

                <div class="includes">
                    <h4>Package Includes</h4>
                    <p>🚙 Jeep tour<br>🎈 Hot-air balloon<br>🥾 Guided hikes<br>🍽️ Meals<br>🏨 Hotel stay</p>
                </div>
            </div>
        </div>

        <div class="package-card">
            <img src="https://images.unsplash.com/photo-1537996194471-e657df975ab4?w=900" alt="Bali tropical scenery">

            <div class="package-info">
                <h3>Chic Nomad</h3>
                <p>Perfect for relaxation lovers and beautiful scenery.</p>
                <div class="price">$2,950 <span>/ person</span></div>

                <button class="toggle" onclick="togglePlan('chic',this)">
                    Chic Nomad ♡
                </button>
            </div>

            <div class="itinerary" id="chic">
                <h4>Day 1 – Bali</h4>
                <p>Airport pickup<br>Beach resort check-in<br>Sunset dinner</p>

                <h4>Day 2 – Coastal Escape</h4>
                <p>Tanah Lot Temple<br>Beach picnic<br>Spa session</p>

                <h4>Day 3 – Nusa Penida</h4>
                <p>Island tour<br>Snorkelling<br>Crystal Bay</p>

                <h4>Day 4 – Luxury Glamping</h4>
                <p>Luxury glamping<br>Campfire<br>Stargazing<br>BBQ dinner</p>

                <h4>Day 5</h4>
                <p>Morning beach walk<br>Souvenir shopping<br>Airport transfer</p>

                <div class="includes">
                    <h4>Package Includes</h4>
                    <p>🏖️ Beach resort<br>⛺ Luxury glamping<br>🚤 Island tour<br>🤿 Snorkelling<br>🚐 Airport transfers</p>
                </div>
            </div>
        </div>

    </div>
</section>

<section id="reviews">
    <div class="heading">
        <small>HAPPY TRAVELLERS</small>
        <h2>Guest Reviews</h2>
        <p>Memories made. Experiences treasured.</p>
    </div>

    <div class="reviews">
        <div class="review">
            <div class="stars">★★★★★</div>
            <p>"My experience with Indome Agency was wonderful! The hotels were beautiful and everything was perfectly planned. I would definitely travel with them again!"</p>
            <h3>Emily Tan</h3>
            <small>City-Girl Holiday</small>
        </div>

        <div class="review">
            <div class="stars">★★★★★</div>
            <p>"The Urban Adventurer package was incredible! The activities were unforgettable and our guides were amazing!"</p>
            <h3>Daniel Lim</h3>
            <small>Urban Adventurer</small>
        </div>

        <div class="review">
            <div class="stars">★★★★★</div>
            <p>"Bali was breathtaking! The resort was gorgeous and the entire holiday felt so relaxing. Highly recommend!"</p>
            <h3>Sarah Wong</h3>
            <small>Chic Nomad</small>
        </div>
    </div>

    <p style="text-align:center;margin-top:20px;font-size:11px;color:#999;">
        Sample fictional reviews for website demonstration.
    </p>
</section>

<section class="booking" id="booking">
    <div class="heading">
        <small>YOUR NEXT ADVENTURE AWAITS</small>
        <h2>Book Your Holiday</h2>
        <p>Complete the form to send us your booking enquiry.</p>
    </div>

    <form class="booking-form" id="bookingForm">

        <div class="form-group">
            <label>Full Name</label>
            <input type="text" name="name" placeholder="Enter your full name" required>
        </div>

        <div class="form-group">
            <label>Email Address</label>
            <input type="email" name="email" placeholder="Enter your email" required>
        </div>

        <div class="form-group">
            <label>Phone Number</label>
            <input type="tel" name="phone" placeholder="Enter your phone number" required>
        </div>

        <div class="form-group">
            <label>Number of Travellers</label>
            <input type="number" name="people" min="1" placeholder="Number of people" required>
        </div>

        <div class="form-group">
            <label>Preferred Travel Date</label>
            <input type="date" name="date" required>
        </div>

        <div class="form-group">
            <label>Choose Your Package</label>
            <select name="package" required>
                <option value="">Select a package</option>
                <option>City-Girl Holiday - $3500</option>
                <option>Urban Adventurer - $1999</option>
                <option>Chic Nomad - $2950</option>
            </select>
        </div>

        <div class="form-group">
            <label>Special Requests</label>
            <textarea name="requests" placeholder="Tell us about any special requests..."></textarea>
        </div>

        <button type="submit" class="btn">SUBMIT BOOKING ENQUIRY</button>

        <p id="bookingMessage" style="text-align:center;margin-top:15px;color:#98783e;"></p>

    </form>
</section>

<section class="contact" id="contact">
    <small style="color:#dfc99d;letter-spacing:4px;">WE WOULD LOVE TO HEAR FROM YOU</small>
    <h2>Contact Us</h2>
    <p>Have questions? Our team would love to help you plan your next adventure.</p>

    <br>
    <p>📞 Phone: <a href="tel:+6588887987">+65 88887987</a></p>
    <p>✉️ Email: <a href="mailto:indomeagency@gmail.com">indomeagency@gmail.com</a></p>
    <p>🌏 Destination: Indonesia</p>
    <br>

    <a href="mailto:indomeagency@gmail.com" class="btn">GET IN TOUCH</a>
</section>

<footer>
    © 2026 Indome Agency. All Rights Reserved.
    <br><br>
    Nothing beats an Indome Agency.
</footer>

<script>

function togglePlan(id, button) {
    const plan = document.getElementById(id);

    plan.classList.toggle("show");
    button.classList.toggle("active");
}

document.getElementById("bookingForm").addEventListener("submit", function(event) {
    event.preventDefault();

    const data = new FormData(this);

    const subject = encodeURIComponent("New Indome Agency Booking Enquiry");

    const body = encodeURIComponent(
        "Name: " + data.get("name") + "\n" +
        "Email: " + data.get("email") + "\n" +
        "Phone: " + data.get("phone") + "\n" +
        "Number of travellers: " + data.get("people") + "\n" +
        "Travel date: " + data.get("date") + "\n" +
        "Package: " + data.get("package") + "\n" +
        "Special requests: " + data.get("requests")
    );

    document.getElementById("bookingMessage").textContent =
        "Opening your email app with your booking details...";

    window.location.href =
        "mailto:indomeagency@gmail.com?subject=" + subject + "&body=" + body;
});

</script>

</body>
</html>
