<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="hero">
        <div class="hero-content">
            <h1>My Portfolio</h1>
            <p>Welcome to my portfolio website</p>
        </div>
    </section>
    
    <section id="about">
        <h2>About Me</h2>
        <p>Write something about yourself here.</p>
    </section>
    
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project Title 1</h3>
            <p>Description of project 1</p>
            <img src="project1.jpg" alt="Project 1">
        </div>
        <div class="project">
            <h3>Project Title 2</h3>
            <p>Description of project 2</p>
            <img src="project2.jpg" alt="Project 2">
        </div>
        <!-- Add more project sections as needed -->
    </section>
    
    <footer id="contact">
        <p>Contact me:</p>
        <ul>
            <li>Email: example@example.com</li>
            <li>Phone: 123-456-7890</li>
        </ul>
    </footer>
</body>
</html>
body {
    margin: 0;
    font-family: Arial, sans-serif;
}

header {
    background-color: #333;
    padding: 10px 0;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    text-align: center;
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
    background-image: url('hero-bg.jpg'); /* Replace 'hero-bg.jpg' with your image */
    background-size: cover;
    color: #fff;
    text-align: center;
    padding: 100px 0;
}

.hero-content h1 {
    font-size: 36px;
}

.hero-content p {
    font-size: 18px;
}

#about, #projects, #contact {
    padding: 50px 0;
    text-align: center;
}

.project {
    margin-bottom: 40px;
}

.project h3 {
    font-size: 24px;
}

.project p {
    font-size: 18px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}
