# PDD-Project

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LAW AND JUSTICE</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to your CSS file -->
</head>
<body>
    <header>
        <h1>Law And Justice</h1>
        <!-- Navigation links -->
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#procedure">procedure</a></li>
                <li><a href="#documentation">documentation</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Us</h2>
        <p>DETAILS ABOUT CASE.</p>
    </section>

    <section id="PROCEDURE">
        <h2>DESCRIBING THE CASES</h2>
        <ul>
            <li>CASE DETAILS 1</li>
            <li>CASE DETAILS 2</li>
            <li>CASE DETAILS 3</li>
            <!-- Add more services as needed -->
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>CLINT DETAILS.</p>
    </section>

    <footer>
        <p>&copy; 2024 LAWS</p>
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





<?php
if ($_SERVER["REQUEST_METHOD"] == "POST") {
    $name = $_POST["name"];
    $email = $_POST["email"];
    $message = $_POST["message"];

    // Here you can add code to send the email or save the message to a database
    // For example, sending an email using the mail() function:
    $to = "your_email@example.com";
    $subject = "Message from $name";
    $body = "Name: $name\nEmail: $email\nMessage: $message";
    mail($to, $subject, $body);

    // Redirect to a thank you page
    header("Location: thank_you.html");
    exit;
}
?>
