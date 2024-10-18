<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Your Real Estate Business</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Your Real Estate Agency</h1>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#listings">Listings</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="hero">
        <div class="hero-text">
            <h2>Find Your Dream Home</h2>
            <p>Your trusted real estate agent in [City]</p>
        </div>
    </section>

    <section id="about" class="container">
        <h2>About Me</h2>
        <p>Hi, I'm [Your Name], a real estate agent specializing in homes in [City]. With [X] years of experience, I can help you buy or sell your property with confidence.</p>
    </section>

    <section id="listings" class="container">
        <h2>Featured Listings</h2>
        <div class="listing-grid">
            <div class="listing">
                <img src="house1.jpg" alt="House 1">
                <h3>Beautiful Family Home</h3>
                <p>Price: $500,000</p>
                <p>3 Beds, 2 Baths, 2,000 sqft</p>
            </div>
            <div class="listing">
                <img src="house2.jpg" alt="House 2">
                <h3>Modern Apartment</h3>
                <p>Price: $350,000</p>
                <p>2 Beds, 1 Bath, 1,200 sqft</p>
            </div>
            <!-- Add more listings here -->
        </div>
    </section>

    <section id="contact" class="container">
        <h2>Contact Me</h2>
        <form action="mailto:youremail@example.com" method="post" enctype="text/plain">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>© 2024 Your Real Estate Agency | Designed by You</p>
    </footer>
</body>
</html>
