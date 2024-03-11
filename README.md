# PDD-Project0

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Healthcare Website</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to your CSS file -->
</head>
<body>
    <header>
        <h1>Healthcare Website</h1>
        <!-- Navigation links -->
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Us</h2>
        <p>Place your information about your healthcare services here.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Service 1</li>
            <li>Service 2</li>
            <li>Service 3</li>
            <!-- Add more services as needed -->
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Include contact information here.</p>
    </section>

    <footer>
        <p>&copy; 2024 Healthcare Website</p>
    </footer>
</body>
</html>

















/* styles.css */

/* Global styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #4CAF50;
    color: #fff;
    padding: 20px;
    text-align: center;
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

section {
    padding: 50px;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}

/* Specific styles */
h1, h2 {
    margin-bottom: 20px;
}

section#about {
    background-color: #f2f2f2;
}

section#services {
    background-color: #ddd;
}

section#contact {
    background-color: #f2f2f2;
}
