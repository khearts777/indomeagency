

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Indome Agency | Discover Indonesia</title>

<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@400;500;600;700&display=swap" rel="stylesheet">

<style>
:root {
    --gold: #b49355;
    --dark-gold: #8e703d;
    --light-gold: #e8dcc2;
    --cream: #faf8f3;
    --white: #ffffff;
    --text: #38352f;
    --muted: #777168;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    font-family: 'DM Sans', sans-serif;
    background: var(--cream);
    color: var(--text);
    line-height: 1.7;
}

.container {
    width: 88%;
    max-width: 1200px;
    margin: auto;
}

/* NAVIGATION */

nav {
    background: white;
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: 0 3px 15px #00000008;
}

.nav-container {
    max-width: 1300px;
    width: 90%;
    margin: auto;
    min-height: 85px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 25px;
}

.logo {
    font-family: 'Playfair Display', serif;
    font-size: 25px;
    color: var(--dark-gold);
    font-weight: bold;
    letter-spacing: 2px;
    white-space: nowrap;
}

nav ul {
    display: flex;
    align-items: center;
    list-style: none;
    gap: 25px;
}

nav a {
    text-decoration: none;
    color: #514b40;
    font-size: 13px;
    font-weight: 500;
    transition: 0.3s;
}

nav a:hover {
    color: var(--gold);
}

/* HERO */

.hero {
    min-height: 650px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 80px 20px;

    background:
        linear-gradient(#17140c75, #17140c75),
        url('https://images.unsplash.com/photo-1537996194471-e657df975ab4?w=1800')
        center/cover;

    color: white;
}

.hero-content {
    max-width: 850px;
}

.hero small {
    color: var(--light-gold);
    letter-spacing: 5px;
    font-size: 12px;
    font-weight: 600;
}

.hero h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(45px, 7vw, 76px);
    line-height: 1.2;
    margin: 25px 0;
}

.hero p {
    font-size: 16px;
    line-height: 2;
    max-width: 650px;
    margin: 0 auto 30px;
}

.btn {
    display: inline-block;
    background: var(--gold);
    color: white;
    padding: 14px 30px;
    border: 1px solid var(--gold);
    text-decoration: none;
    font-family: inherit;
    font-size: 12px;
    font-weight: 600;
    letter-spacing: 1.5px;
    cursor: pointer;
    transition: 0.3s;
}

.btn:hover {
    background: var(--dark-gold);
    border-color: var(--dark-gold);
    transform: translateY(-2px);
}

/* GENERAL SECTIONS */

section {
    padding: 90px 0;
}

.section-heading {
    text-align: center;
    max-width: 700px;
    margin: 0 auto 55px;
}

.section-heading small {
    color: var(--gold);
    letter-spacing: 4px;
    font-size: 11px;
    font-weight: 600;
}

.section-heading h2 {
    font-family: 'Playfair Display', serif;
    color: var(--dark-gold);
    font-size: clamp(32px, 4vw, 43px);
    margin: 12px 0;
    line-height: 1.3;
}

.section-heading p {
    color: var(--muted);
    font-size: 14px;
}

/* ABOUT */

.about {
    background: white;
}

.about-content {
    max-width: 800px;
    margin: auto;
    text-align: center;
    color: var(--muted);
    font-size: 15px;
    line-height: 2.1;
}

.about-content strong {
    display: block;
    margin-top: 25px;
    font-family: 'Playfair Display', serif;
    font-size: 21px;
    color: var(--dark-gold);
}

/* WHY CHOOSE US */

.features {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 22px;
    align-items: stretch;
}

.feature-card {
    background: white;
    border: 1px solid #eee5d5;
    padding: 35px 23px;
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
    transition: 0.3s;
}

.feature-card:hover {
    transform: translateY(-6px);
    box-shadow: 0 10px 25px #0000000a;
}

.feature-icon {
    font-size: 35px;
    margin-bottom: 18px;
}

.feature-card h3 {
    font-family: 'Playfair Display', serif;
    color: var(--dark-gold);
    font-size: 19px;
    margin-bottom: 12px;
}

.feature-card p {
    color: var(--muted);
    font-size: 13px;
    line-height: 1.8;
}

/* PACKAGES */

.packages {
    background: white;
}

.package-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 25px;
    align-items: start;
}

.package-card {
    background: var(--cream);
    border: 1px solid #e8dfcf;
    display: flex;
    flex-direction: column;
    overflow: hidden;
    transition: 0.3s;
}

.package-card:hover {
    box-shadow: 0 12px 30px #00000010;
    transform: translateY(-4px);
}

.package-card img {
    width: 100%;
    height: 225px;
    object-fit: cover;
    display: block;
}

.package-info {
    padding: 27px 24px;
    display: flex;
    flex-direction: column;
    flex: 1;
}

.package-info h3 {
    font-family: 'Playfair Display', serif;
    color: var(--dark-gold);
    font-size: 23px;
    margin-bottom: 10px;
}

.package-info .description {
    color: var(--muted);
    font-size: 13px;
    min-height: 65px;
}

.price {
    color: var(--gold);
    font-size: 27px;
    font-weight: 700;
    margin: 18px 0;
}

.price span {
    font-size: 12px;
    color: #89847a;
    font-weight: 400;
}

.toggle {
    width: 100%;
    padding: 14px;
    background: white;
    border: 1px solid var(--gold);
    color: var(--dark-gold);
    font-family: inherit;
    font-weight: 600;
    font-size: 13px;
    cursor: pointer;
    transition: 0.3s;
    margin-top: auto;
}

.toggle:hover,
.toggle.active {
    background: var(--gold);
    color: white;
}

.itinerary {
    display: none;
    padding: 25px;
    background: white;
    border-top: 1px solid #eee5d5;
    font-size: 13px;
    line-height: 1.9;
}

.itinerary.show {
    display: block;
    animation: fadeIn 0.3s ease;
}

@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(-8px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

.itinerary h4 {
    font-family: 'Playfair Display', serif;
    color: var(--dark-gold);
    font-size: 17px;
    margin: 17px 0 6px;
}

.includes {
    border-top: 1px solid #eee5d5;
    margin-top: 18px;
    padding-top: 10px;
}

/* REVIEWS */

.reviews {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
    align-items: stretch;
}

.review-card {
    background: white;
    border: 1px solid #eee5d5;
    padding: 32px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.stars {
    color: var(--gold);
    letter-spacing: 3px;
    font-size: 17px;
    margin-bottom: 17px;
}

.review-card p {
    font-size: 14px;
    line-height: 1.9;
    color: var(--muted);
    margin-bottom: 25px;
}

.review-card h3 {
    font-family: 'Playfair Display', serif;
    color: var(--dark-gold);
    font-size: 18px;
}

.review-card small {
    color: #999;
    font-size: 12px;
}

/* BOOKING */

.booking {
    background: white;
}

.booking-form {
    max-width: 750px;
    margin: auto;
    padding: 40px;
    background: var(--cream);
    border: 1px solid #e8dfcf;
}

.form-row {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
}

.form-group {
    margin-bottom: 22px;
    text-align: left;
}

.form-group label {
    display: block;
    font-size: 13px;
    font-weight: 600;
    color: #514b40;
    margin-bottom: 9px;
}

.form-group input,
.form-group select,
.form-group textarea {
    width: 100%;
    padding: 14px;
    border: 1px solid #dfd4c1;
    background: white;
    font-family: inherit;
    font-size: 13px;
    color: var(--text);
    outline: none;
    transition: 0.2s;
}

.form-group input:focus,
.form-group select:focus,
.form-group textarea:focus {
    border-color: var(--gold);
}

.form-group textarea {
    min-height: 120px;
    resize: vertical;
}

.booking-form .btn {
    width: 100%;
}

#bookingMessage {
    text-align: center;
    color: var(--dark-gold);
    margin-top: 15px;
    font-size: 13px;
}

/* CONTACT */

.contact {
    background: #302c24;
    color: white;
    text-align: center;
}

.contact .section-heading h2 {
    color: white;
}

.contact .section-heading p {
    color: #d5cfc2;
}

.contact-details {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 12px;
    margin-bottom: 30px;
}

.contact-details p {
    color: #d5cfc2;
    font-size: 14px;
}

.contact-details a {
    color: var(--light-gold);
    text-decoration: none;
}

.contact-details a:hover {
    text-decoration: underline;
}

/* FOOTER */

footer {
    background: #211f1a;
    color: #b9b2a6;
    text-align: center;
    padding: 28px 20px;
    font-size: 12px;
}

footer strong {
    color: var(--light-gold);
    font-family: 'Playfair Display', serif;
    font-size: 17px;
}

/* RESPONSIVE DESIGN */

@media (max-width: 950px) {
    .features {
        grid-template-columns: repeat(2, 1fr);
    }

    .package-grid {
        grid-template-columns: repeat(2, 1fr);
    }

    .reviews {
        grid-template-columns: repeat(2, 1fr);
    }

    .nav-container {
        flex-direction: column;
        padding: 18px 0;
    }

    nav ul {
        flex-wrap: wrap;
        justify-content: center;
        gap: 15px;
    }
}

@media (max-width: 600px) {
    section {
        padding: 65px 0;
    }

    .container {
        width: 90%;
    }

    .features,
    .package-grid,
    .reviews {
        grid-template-columns: 1fr;
    }

    .form-row {
        grid-template-columns: 1fr;
        gap: 0;
    }

    .booking-form {
        padding: 23px;
    }

    .hero {
        min-height: 520px;
    }

    .logo {
        font-size: 22px;
    }

    nav ul {
        gap: 12px;
    }

    nav a {
        font-size: 11px;
    }
}
</style>
</head>

<body>

<!-- NAVIGATION -->

<nav>
    <div class="nav-container">
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
    </div>
</nav>

<!-- HERO -->

<header class="hero" id="home">
    <div class="hero-content">
        <small>YOUR JOURNEY BEGINS HERE</small>

        <h1>Discover Indonesia in Style.</h1>

        <p>
            Luxury escapes. Extraordinary adventures.
            Unforgettable memories.
            Experience the beauty of Indonesia with Indome Agency.
        </p>

        <a href="#packages" class="btn">
            EXPLORE OUR PACKAGES
        </a>
    </div>
</header>

<!-- ABOUT -->

<section class="about" id="about">
    <div class="container">

        <div class="section-heading">
            <small>WELCOME TO INDOME</small>
            <h2>Travel Beyond Ordinary.</h2>
        </div>

        <div class="about-content">
            <p>
                At Indome Agency, we believe travelling should be
                more than simply visiting a destination. It should
                be an experience filled with unforgettable memories,
                extraordinary discoveries and exceptional comfort.
            </p>

            <p>
                Specialising in Indonesian holidays, we offer
                carefully designed travel packages for every type
                of traveller. Whether you desire a luxurious city
                escape, an adventurous journey or a relaxing
                tropical getaway, we have the perfect holiday
                waiting for you.
            </p>

            <strong>Nothing beats an Indome Agency.</strong>
        </div>

    </div>
</section>

<!-- WHY CHOOSE US -->

<section id="why">
    <div class="container">

        <div class="section-heading">
            <small>THE INDOME EXPERIENCE</small>
            <h2>Why Choose Us?</h2>
            <p>Discover what makes travelling with Indome special.</p>
        </div>

        <div class="features">

            <div class="feature-card">
                <div class="feature-icon">🏨</div>
                <h3>Luxury Hotels</h3>
                <p>
                    Enjoy premium accommodation and exceptional
                    comfort throughout your holiday.
                </p>
            </div>

            <div class="feature-card">
                <div class="feature-icon">✨</div>
                <h3>Incredible Planning</h3>
                <p>
                    Every itinerary is thoughtfully designed
                    to create a smooth and memorable experience.
                </p>
            </div>

            <div class="feature-card">
                <div class="feature-icon">🌟</div>
                <h3>Top-Tier Guides</h3>
                <p>
                    Explore Indonesia with knowledgeable and
                    helpful travel guides.
                </p>
            </div>

            <div class="feature-card">
                <div class="feature-icon">🌴</div>
                <h3>Unique Experiences</h3>
                <p>
                    Discover extraordinary experiences beyond
                    the ordinary.
                </p>
            </div>

        </div>
    </div>
</section>

<!-- TRAVEL PACKAGES -->

<section class="packages" id="packages">
    <div class="container">

        <div class="section-heading">
            <small>FIND YOUR PERFECT ESCAPE</small>
            <h2>Our Travel Packages</h2>
            <p>
                Three extraordinary journeys.
                One unforgettable destination.
            </p>
        </div>

        <div class="package-grid">

            <!-- CITY GIRL -->

            <div class="package-card">

                <img
                    src="https://images.unsplash.com/photo-1555899434-94d1368aa7af?w=900"
                    alt="Jakarta city skyline">

                <div class="package-info">
                    <h3>City-Girl Holiday</h3>

                    <p class="description">
                        Perfect for shopping lovers, foodies
                        and those who enjoy luxury.
                    </p>

                    <div class="price">
                        $3,500 <span>/ person</span>
                    </div>

                    <button class="toggle"
                        onclick="togglePlan('city',this)">
                        City-Girl Holiday ♡
                    </button>
                </div>

                <div class="itinerary" id="city">

                    <h4>Day 1 – Jakarta</h4>
                    <p>
                        Airport pickup<br>
                        5-star hotel check-in<br>
                        Welcome dinner<br>
                        Grand Indonesia Mall
                    </p>

                    <h4>Day 2 – Jakarta</h4>
                    <p>
                        Plaza Indonesia shopping<br>
                        Café hopping<br>
                        Kota Tua (Old Town)<br>
                        Sunset rooftop dinner
                    </p>

                    <h4>Day 3 – Bandung</h4>
                    <p>
                        Travel to Bandung<br>
                        The Great Asia Africa<br>
                        Factory outlets<br>
                        Luxury spa
                    </p>

                    <h4>Day 4 – Bandung</h4>
                    <p>
                        Scenic café brunch<br>
                        Floating Market Lembang<br>
                        Souvenir shopping<br>
                        Free evening
                    </p>

                    <h4>Day 5 – Departure</h4>
                    <p>
                        Hotel breakfast<br>
                        Airport transfer
                    </p>

                    <div class="includes">
                        <h4>Package Includes</h4>
                        <p>
                            ⭐ 5-star hotel<br>
                            🚐 Airport transfers<br>
                            🍽️ Breakfast daily<br>
                            🛍️ Shopping guide<br>
                            📸 Photo stops
                        </p>
                    </div>

                </div>
            </div>

            <!-- URBAN ADVENTURER -->

            <div class="package-card">

                <img
                    src="https://images.unsplash.com/photo-1596402184320-417e7178b2cd?w=900"
                    alt="Indonesian temple">

                <div class="package-info">
                    <h3>Urban Adventurer</h3>

                    <p class="description">
                        Perfect for nature lovers and thrill seekers.
                    </p>

                    <div class="price">
                        $1,999 <span>/ person</span>
                    </div>

                    <button class="toggle"
                        onclick="togglePlan('urban',this)">
                        Urban Adventurer ♡
                    </button>
                </div>

                <div class="itinerary" id="urban">

                    <h4>Day 1 – Yogyakarta</h4>
                    <p>
                        Airport pickup<br>
                        Malioboro Street<br>
                        Local food tasting
                    </p>

                    <h4>Day 2 – Sunrise Adventure</h4>
                    <p>
                        Borobudur Sunrise Tour<br>
                        Hot-air balloon experience<br>
                        Village cycling
                    </p>

                    <h4>Day 3 – Mount Merapi</h4>
                    <p>
                        Jeep adventure<br>
                        Lava Museum<br>
                        Campfire dinner
                    </p>

                    <h4>Day 4 – Nature Exploration</h4>
                    <p>
                        Waterfall trekking<br>
                        Cave tubing<br>
                        Cultural performance
                    </p>

                    <h4>Day 5 – Departure</h4>
                    <p>
                        Souvenir shopping<br>
                        Airport transfer
                    </p>

                    <div class="includes">
                        <h4>Package Includes</h4>
                        <p>
                            🚙 Jeep tour<br>
                            🎈 Hot-air balloon<br>
                            🥾 Guided hikes<br>
                            🍽️ Meals<br>
                            🏨 Hotel stay
                        </p>
                    </div>

                </div>
            </div>

            <!-- CHIC NOMAD -->

            <div class="package-card">

                <img
                    src="https://images.unsplash.com/photo-1537996194471-e657df975ab4?w=900"
                    alt="Bali tropical scenery">

                <div class="package-info">
                    <h3>Chic Nomad</h3>

                    <p class="description">
                        Perfect for relaxation lovers and
                        beautiful scenery.
                    </p>

                    <div class="price">
                        $2,950 <span>/ person</span>
                    </div>

                    <button class="toggle"
                        onclick="togglePlan('chic',this)">
                        Chic Nomad ♡
                    </button>
                </div>

                <div class="itinerary" id="chic">

                    <h4>Day 1 – Bali</h4>
                    <p>
                        Airport pickup<br>
                        Beach resort check-in<br>
                        Sunset dinner
                    </p>

                    <h4>Day 2 – Coastal Escape</h4>
                    <p>
                        Tanah Lot Temple<br>
                        Beach picnic<br>
                        Spa session
                    </p>

                    <h4>Day 3 – Nusa Penida</h4>
                    <p>
                        Island tour<br>
                        Snorkelling<br>
                        Crystal Bay
                    </p>

                    <h4>Day 4 – Luxury Glamping</h4>
                    <p>
                        Luxury glamping<br>
                        Campfire<br>
                        Stargazing<br>
                        BBQ dinner
                    </p>

                    <h4>Day 5 – Departure</h4>
                    <p>
                        Morning beach walk<br>
                        Souvenir shopping<br>
                        Airport transfer
                    </p>

                    <div class="includes">
                        <h4>Package Includes</h4>
                        <p>
                            🏖️ Beach resort<br>
                            ⛺ Luxury glamping<br>
                            🚤 Island tour<br>
                            🤿 Snorkelling<br>
                            🚐 Airport transfers
                        </p>
                    </div>

                </div>
            </div>

        </div>
    </div>
</section>

<!-- REVIEWS -->

<section id="reviews">
    <div class="container">

        <div class="section-heading">
            <small>HAPPY TRAVELLERS</small>
            <h2>Guest Reviews</h2>
            <p>Memories made. Experiences treasured.</p>
        </div>

        <div class="reviews">

            <div class="review-card">
                <div>
                    <div class="stars">★★★★★</div>
                    <p>
                        "My experience with Indome Agency was
                        wonderful! The hotels were beautiful
                        and everything was perfectly planned.
                        I would definitely travel with them again!"
                    </p>
                </div>
                <div>
                    <h3>Emily Tan</h3>
                    <small>City-Girl Holiday</small>
                </div>
            </div>

            <div class="review-card">
                <div>
                    <div class="stars">★★★★★</div>
                    <p>
                        "The Urban Adventurer package was incredible!
                        The activities were unforgettable and our
                        guides were amazing!"
                    </p>
                </div>
                <div>
                    <h3>Daniel Lim</h3>
                    <small>Urban Adventurer</small>
                </div>
            </div>

            <div class="review-card">
                <div>
                    <div class="stars">★★★★★</div>
                    <p>
                        "Bali was breathtaking! The resort was
                        gorgeous and the entire holiday felt
                        so relaxing. Highly recommend!"
                    </p>
                </div>
                <div>
                    <h3>Sarah Wong</h3>
                    <small>Chic Nomad</small>
                </div>
            </div>

        </div>

        <p style="text-align:center;color:#999;font-size:11px;margin-top:20px;">
            Sample fictional reviews for website demonstration.
        </p>

    </div>
</section>

<!-- BOOKING -->

<section class="booking" id="booking">
    <div class="container">

        <div class="section-heading">
            <small>YOUR NEXT ADVENTURE AWAITS</small>
            <h2>Book Your Holiday</h2>
            <p>
                Complete the form below to send us your booking enquiry.
            </p>
        </div>

        <form class="booking-form" id="bookingForm">

            <div class="form-row">

                <div class="form-group">
                    <label for="name">Full Name</label>
                    <input type="text" id="name" name="name"
                        placeholder="Enter your full name" required>
                </div>

                <div class="form-group">
                    <label for="email">Email Address</label>
                    <input type="email" id="email" name="email"
                        placeholder="Enter your email" required>
                </div>

            </div>

            <div class="form-row">

                <div class="form-group">
                    <label for="phone">Phone Number</label>
                    <input type="tel" id="phone" name="phone"
                        placeholder="Enter your phone number" required>
                </div>

                <div class="form-group">
                    <label for="people">Number of Travellers</label>
                    <input type="number" id="people" name="people"
                        min="1" placeholder="Number of people" required>
                </div>

            </div>

            <div class="form-group">
                <label for="date">Preferred Travel Date</label>
                <input type="date" id="date" name="date" required>
            </div>

            <div class="form-group">
                <label for="package">Choose Your Package</label>

                <select id="package" name="package" required>
                    <option value="">Select your package</option>
                    <option>City-Girl Holiday - $3500</option>
                    <option>Urban Adventurer - $1999</option>
                    <option>Chic Nomad - $2950</option>
                </select>
            </div>

            <div class="form-group">
                <label for="requests">Special Requests</label>
                <textarea id="requests" name="requests"
                    placeholder="Tell us about any special requests..."></textarea>
            </div>

            <button type="submit" class="btn">
                SUBMIT BOOKING ENQUIRY
            </button>

            <p id="bookingMessage"></p>

        </form>
    </div>
</section>

<!-- CONTACT -->

<section class="contact" id="contact">
    <div class="container">

        <div class="section-heading">
            <small style="color:#dfc99d;">
                WE WOULD LOVE TO HEAR FROM YOU
            </small>
            <h2>Contact Us</h2>
            <p>
                Have questions or need assistance planning your trip?
                Get in touch with our team!
            </p>
        </div>

        <div class="contact-details">

            <p>
                📞 Phone:
                <a href="tel:+6588887987">+65 88887987</a>
            </p>

            <p>
                ✉️ Email:
                <a href="mailto:indomeagency@gmail.com">
                    indomeagency@gmail.com
                </a>
            </p>

            <p>🌏 Destination: Indonesia</p>

        </div>

        <a href="mailto:indomeagency@gmail.com" class="btn">
            GET IN TOUCH
        </a>

    </div>
</section>

<!-- FOOTER -->

<footer>
    <strong>INDOME AGENCY</strong>
    <p>© 2026 Indome Agency. All Rights Reserved.</p>
    <p>Nothing beats an Indome Agency.</p>
</footer>

<!-- JAVASCRIPT -->

<script>

function togglePlan(id, button) {
    const plan = document.getElementById(id);

    plan.classList.toggle("show");
    button.classList.toggle("active");
}

document.getElementById("bookingForm")
.addEventListener("submit", function(event) {

    event.preventDefault();

    const data = new FormData(this);

    const subject = encodeURIComponent(
        "New Indome Agency Booking Enquiry"
    );

    const body = encodeURIComponent(
        "Name: " + data.get("name") + "\n" +
        "Email: " + data.get("email") + "\n" +
        "Phone: " + data.get("phone") + "\n" +
        "Travellers: " + data.get("people") + "\n" +
        "Travel Date: " + data.get("date") + "\n" +
        "Package: " + data.get("package") + "\n" +
        "Special Requests: " + data.get("requests")
    );

    document.getElementById("bookingMessage").textContent =
        "Opening your email app with your booking details...";

    window.location.href =
        "mailto:indomeagency@gmail.com?subject=" +
        subject + "&body=" + body;

});

</script>

</body>
</html>
