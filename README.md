!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elegant Hair Salon</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #e91e63;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            padding: 5px 10px;
        }
        nav a:hover {
            background-color: #e91e63;
            border-radius: 5px;
        }
        .container {
            width: 80%;
            margin: 0 auto;
        }
        .hero {
            text-align: center;
            padding: 50px 0;
            background-image: url('path-to-your-image.jpg');
            background-size: cover;
            color: #fff;
        }
        .hero h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 1.5em;
        }
        .services, .about, .contact {
            padding: 40px 0;
            text-align: center;
        }
        .services h2, .about h2, .contact h2 {
            margin-bottom: 20px;
        }
        .services p, .about p, .contact p {
            margin-bottom: 10px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bacon and Egg-drew.com</h1>
        <p>Your beauty is our passion</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="hero" id="home">
        <h1>Welcome to Bacon and Egg-drew.com!</h1>
        <p>Where style meets elegance</p>
    </div>
    <div class="container">
        <section class="services" id="services">
            <h2>Our Services</h2>
            <p>Haircuts</p>
            <p>Coloring</p>
            <p>Styling</p>
            <p>Treatments</p>
        </section>
        <section class="about" id="about">
            <h2>About Us</h2>
            <p>At Bacon and Egg-drew.com, we offer a range of services to keep your hair looking its best.</p>
            <p>Our team of professional stylists is here to provide you with a personalized experience.</p>
        </section>
        <section class="contact" id="contact">
            <h2>Contact Us</h2>
            <p>Email: info@eleganthairsalon.com</p>
            <p>Phone: (123) 456-7890</p>
            <p>Address: 1234 Beauty St, Style City, SC 56789</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Elegant Hair Salon</p>
    </footer>
</body>
</html>
