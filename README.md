<html lang="en">
<head>
    <style>
        /* Global styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000;
            color: #fff;
            box-sizing: border-box;
        }

        h2, h3 {
            color: #FFD700; /* Yellow color for all section headings */
        }

        .stars {
            color: #FFD700;
            font-size: 1.2em;
        }

        header {
            background: linear-gradient(90deg, #000, #333);
            color: #FFD700;
            padding: 20px 0;
            text-align: center;
        }

        .header-container img {
            height: 300px;
            width: auto;
            display: block;
            margin: 0 auto;
        }

        nav {
            background-color: #FFD700;
            padding: 10px 0;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: #000;
            font-weight: bold;
            font-size: 1.1em;
            padding: 10px 15px;
            border-radius: 5px;
            background-color: rgba(255, 215, 0, 0.2);
            transition: background-color 0.3s ease;
        }

        nav ul li a:hover {
            background-color: rgba(255, 215, 0, 0.5);
        }

        #about-us {
            padding: 40px 20px;
            text-align: center;
            max-width: 800px;
            margin: 0 auto;
        }

        #about-us h2 {
            color: #FFD700;
            margin-bottom: 15px;
            font-size: 1.8em;
        }

        #about-us p {
            color: #fff;
            font-size: 1.1em;
        }

        #about-us p strong {
            color: #FFD700;
        }

        /* Slider styles */
        .slider, .gutter-slider, .review-slider {
            width: 100%;
            max-width: 1000px;
            margin: 0 auto;
            overflow: hidden;
            position: relative;
            background-color: #000;
            border: none;
        }

        .slides, .review-slides {
            display: flex;
            transition: transform 0.6s ease-in-out;
            flex-shrink: 0;
        }

        .slides img, .review-slides div {
            width: 100%;
            flex-shrink: 0;
        }

        .hidden {
            display: none;
        }

        .prev, .next {
            cursor: pointer;
            position: absolute;
            top: 50%;
            width: auto;
            margin-top: -22px;
            padding: 16px;
            color: white;
            font-weight: bold;
            font-size: 18px;
            transition: 0.6s ease;
            border-radius: 0 3px 3px 0;
            user-select: none;
        }

        .next {
            right: 0;
            border-radius: 3px 0 0 3px;
        }

        .prev:hover, .next:hover {
            background-color: rgba(255, 215, 0, 0.8);
        }

        footer {
            background: linear-gradient(90deg, #000, #333);
            color: #FFD700;
            padding: 20px 0;
            text-align: center;
            max-width: 800px;
            margin: 0 auto;
        }

        footer h3 {
            margin-bottom: 10px;
            font-size: 1.5em;
        }

        footer p {
            margin: 5px 0;
            font-size: 1.1em;
            color: #fff;
        }

        footer a {
            color: #FFD700;
            text-decoration: underline;
        }

        footer a:hover {
            text-decoration: underline;
        }

        .review-bubble {
            background: rgba(255, 215, 0, 0.2);
            border-radius: 15px;
            padding: 20px;
            margin: 10px auto;
            position: relative;
            max-width: 90%;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
            height: 275px;
        }

        @media (max-width: 800px) {
            section, footer {
                padding: 15px;
            }

            section h2 {
                font-size: 1.5em;
            }
        }

        @media (max-width: 600px) {
            nav ul li {
                display: block;
                margin: 5px 0;
            }
        }
    </style>
</head>

<body>
    <header>
        <div class="header-container">
            <img src="DP MEDIA/logo.png" alt="Dimension Powerwash Logo" loading="lazy">
            <h1>Dimension Powerwash</h1>
            <p>Exterior Cleaning Specialists - Sheffield</p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#driveway-patio">Drive & Patio Cleaning</a></li>
            <li><a href="#gutter-cleaning">Gutter Cleaning</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about-us">
        <h2>About Us</h2>
        <p>Welcome to <strong>Dimension Powerwash</strong>! We are dedicated to providing high-quality exterior cleaning services, specializing in <strong>pressure washing</strong>, <strong>drive cleaning</strong>, <strong>patio cleaning</strong>, and <strong>gutter cleaning</strong>. Based in <strong>Sheffield</strong>, we proudly serve both residential and commercial clients across the city and surrounding areas.</p>
    </section>

    <section id="customer-reviews">
        <h2>What Our Customers Say About Us</h2>
        <div class="review-slider">
            <div class="review-slides">
                <div class="review-bubble">
                    <p>"Had gutters cleaned out. 3 story house and high gutters but Joe did a great job with the sky vac and was really nice to deal with - highly recommend!"</p>
                    <p><strong>Clare</strong> <span class="stars">★★★★★</span></p>
                </div>
                <div class="review-bubble hidden">
                    <p>"Great communication and great job done. Gutters now clear of gunk - thanks Joe!"</p>
                    <p><strong>Peter</strong> <span class="stars">★★★★★</span></p>
                </div>
                 <div class="review-bubble hidden">
                    <p>"Gave a great service, cleaning our blocked gutters. The price was good and also very friendly, would highly recommend!"</p>
                    <p><strong>Keneth</strong> <span class="stars">★★★★★</span></p>
                </div>
                 <div class="review-bubble hidden">
                    <p>"Great service from Joe getting my driveway clean, looks amazing thank you!"</p>
                    <p><strong>Sam</strong> <span class="stars">★★★★★</span></p>
                </div>
                 <div class="review-bubble hidden">
                    <p>"Excellent service with a fair price! Joe cleaned our gutters, driveway and patio, I highly recommend and I will be booking in the near future!"</p>
                    <p><strong>M</strong> <span class="stars">★★★★★</span></p>
                     <div class="review-bubble hidden">
                    <p>"Had Joe round to check our gutters, very friendly professional service, Procedure clearly explained and camera footage provided, highly recommend!"</p>
                    <p><strong>Morag</strong> <span class="stars">★★★★★</span></p>
                </div>
                </div>
        </div>

    <section id="driveway-patio">
        <h2>Drive & Patio Cleaning</h2>
        <p>Remove ingrained dirt, moss, algae, lichen, and black spots with our professional cleaning services.</p>

        <div class="slider">
            <div class="slides">
                <img src="DP MEDIA/Block paving before after.png" alt="Block paving before after" loading="lazy">
                <img src="DP MEDIA/Patio before after.png" alt="Patio before after" loading="lazy">
            </div>
        </div>
    </section>

    <section id="gutter-cleaning">
        <h2>Gutter Cleaning</h2>
        <p>Prevent expensive repairs caused by blockages, leaks, and debris.</p>

        <div class="gutter-slider">
            <div class="slides">
                <img src="DP MEDIA/Free Gutter CHECK.png" alt="Free Gutter Check" loading="lazy">
                <img src="DP MEDIA/Fascia Cleaning.png" alt="Fascia Cleaning" loading="lazy">
            </div>
        </div>
    </section>

    <footer id="contact">
        <h3>Contact Us</h3>
        <a href="https://calendly.com/dimensionpowerwash/free-quote" target="_blank">Get your free gutter check here, or book your free quote today!</a>
        <p>Phone: 0114 457 3009</p>
        <a href="https://facebook.com/dimensionpowerwash" target="_blank">Follow us on Facebook!</a><br />
    </footer>

    <script>
        let slideIndex = [0, 0]; // For different sliders
        let reviewIndex = 0;

        function showSlides(sliderClass, index) {
            let slides = document.querySelectorAll(sliderClass + ' .slides img');
            slides.forEach(slide => slide.classList.add('hidden'));
            slideIndex[index] = (slideIndex[index] + 1) % slides.length;
            slides[slideIndex[index]].classList.remove('hidden');
        }

        function showReviewSlides() {
            let reviews = document.querySelectorAll('.review-slides .review-bubble');
            reviews.forEach(review => review.classList.add('hidden'));
            reviewIndex = (reviewIndex + 1) % reviews.length;
            reviews[reviewIndex].classList.remove('hidden');
        }

        // Show the first slide initially for all sliders
        document.querySelectorAll('.slider .slides img').forEach(slide => slide.classList.add('hidden'));
        document.querySelectorAll('.slider .slides img')[0].classList.remove('hidden');

        document.querySelectorAll('.gutter-slider .slides img').forEach(slide => slide.classList.add('hidden'));
        document.querySelectorAll('.gutter-slider .slides img')[0].classList.remove('hidden');

        document.querySelectorAll('.review-bubble').forEach(review => review.classList.add('hidden'));
        document.querySelectorAll('.review-bubble')[0].classList.remove('hidden');

        // Set intervals for the sliders
        setInterval(() => showSlides('.slider', 0), 3000);   // Driveway & Patio Slider
        setInterval(() => showSlides('.gutter-slider', 1), 3000); // Gutter Slider
        setInterval(showReviewSlides, 5000); // Review Slider
    </script>
</body>
</html>
