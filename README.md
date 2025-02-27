<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Moshate wa Thuto Youth Upliftment</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- Header -->
    <header>
        <h1>Moshate wa Thuto Youth Upliftment</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="hero">
        <h2>Empowering Youth Through Education and Social Awareness</h2>
        <p>Building a future where education is a tool for self-determination and societal progress.</p>
        <button class="cta-button" onclick="window.location.href='#about'">Learn More</button>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Us</h2>
        <p>Moshate wa Thuto Youth Upliftment is a transformative initiative dedicated to empowering young people through education, social awareness, and essential support programs. Rooted in the belief that education is a pillar of liberation, we aim to create change and encourage youth development.</p>
        <h3>Our Objectives:</h3>
        <ul>
            <li>Enhance School Retention and Performance</li>
            <li>Raise Social Awareness on issues such as teenage pregnancy and gangsterism</li>
            <li>Empower Matriculants for Higher Education</li>
            <li>Strengthen Community Engagement</li>
        </ul>
    </section>

    <!-- Services Section -->
    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Workshops on Social Issues</li>
            <li>Educational Resources for Teachers</li>
            <li>Matriculant Empowerment Programs</li>
            <li>Advocacy for Better Educational Policies</li>
        </ul>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio">
        <h2>Our Work</h2>
        <div class="gallery">
            <img src="hero-banner.jpg" alt="Community Engagement" width="300" height="200">
            <img src="hero-banner.jpg" alt="Education Program" width="300" height="200">
            <img src="hero-banner.jpg" alt="Workshop" width="300" height="200">
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <form action="mailto:donaldkamogelo85@gmail.com" method="post" enctype="text/plain">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Send Message</button>
        </form>
        <div id="social-media">
            <a href="https://facebook.com" target="_blank">Facebook</a>
            <a href="https://twitter.com" target="_blank">Twitter</a>
            <a href="https://instagram.com" target="_blank">Instagram</a>
        </div>
    </section>

</body>

</html>
