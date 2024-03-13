<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Graphic Design Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 36px;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        #hero {
            background-image: url('hero-bg.jpg'); /* Replace with your image */
            background-size: cover;
            color: #fff;
            text-align: center;
            padding: 150px 0;
        }

        #hero h2 {
            font-size: 48px;
            margin-bottom: 20px;
        }

        #hero p {
            font-size: 24px;
            margin-bottom: 40px;
        }

        section {
            padding: 50px 0;
        }

        section h2 {
            text-align: center;
            margin-bottom: 40px;
            font-size: 36px;
        }

        .portfolio-item {
            text-align: center;
            margin-bottom: 40px;
        }

        .portfolio-item img {
            max-width: 100%;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out;
        }

        .portfolio-item img:hover {
            transform: scale(1.1);
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 50px 0;
        }

        footer p {
            margin: 0;
            font-size: 18px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Graphic Design Portfolio</h1>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="hero">
        <div class="container">
            <h2>Welcome to My Graphic Design Portfolio</h2>
            <p>Explore my creative works below.</p>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Your introduction goes here.</p>
        </div>
    </section>

    <section id="portfolio">
        <div class="container">
            <h2>Portfolio</h2>
            <div class="portfolio-item">
                <img src="portfolio-item1.jpg" alt="Portfolio Item 1">
                <p>Project Title 1</p>
            </div>
            <div class="portfolio-item">
                <img src="portfolio-item2.jpg" alt="Portfolio Item 2">
                <p>Project Title 2</p>
            </div>
            <!-- Add more portfolio items as needed -->
        </div>
    </section>

    <footer id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <p>Email: your.email@example.com</p>
        </div>
    </footer>
</body>
</html>


