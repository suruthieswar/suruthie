<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Salon</title>

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em;
        }

        nav {
            background-color: #444;
            color: #fff;
            text-align: center;
            padding: 1em;
        }

        section {
            padding: 20px;
        }

        .carousel-item img {
            max-width: 100%;
            height: auto;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>My Salon</h1>
        <p>Your Beauty, Our Passion</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="home">
        <!-- Bootstrap Carousel -->
        <div id="carouselExample" class="carousel slide" data-ride="carousel">
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="your-carousel-image1.jpg" class="d-block w-100" alt="Carousel Image 1" >
                </div>
                <div class="carousel-item">
                    <img src="your-carousel-image2.jpg" class="d-block w-100" alt="Carousel Image 2">
                </div>
                <!-- Add more carousel items as needed -->
            </div>
            <a class="carousel-control-prev" href="#carouselExample" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="carousel-control-next" href="#carouselExample" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
            </a>
        </div>
    </section>

    <section id="services">
        <h2>Services</h2>
        <!-- Your services content goes here -->
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Our salon is dedicated to providing top-notch beauty services in a relaxing and comfortable environment.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Reach out to us for appointments and inquiries.</p>
        <p>Email: info@mysalon.com</p>
        <p>Phone: (123) 456-7890</p>
    </section>

    <footer>
        <p>&copy; 2024 My Salon. All rights reserved.</p>
    </footer>

    <!-- Bootstrap JS and Popper.js -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
