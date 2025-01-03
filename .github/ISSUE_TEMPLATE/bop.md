---
name: Bop
about: Render
title: ''
labels: documentation
assignees: BopXtar

---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Static Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Static Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section id="home">
            <h2>Home</h2>
            <p>This is the home section of the website.</p>
        </section>
        
        <section id="about">
            <h2>About</h2>
            <p>This is the about section where we introduce the site or the author.</p>
        </section>
        /* Reset some default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
}

header {
    background-color: #007bff;
    padding: 20px;
    text-align: center;
    color: white;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

main {
    padding: 20px;
    max-width: 900px;
    margin: 0 auto;
    background-color: white;
}

h1, h2 {
    font-size: 2em;
    margin-bottom: 20px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}

section {
    margin-bottom: 30px;
}

        
        <section id="contact">
            <h2>Contact</h2>
            <p>Here you can find our contact information.</p>
        </section>
    </main>

    <footer>
        <p>© 2025 My Static Website</p>
    </footer>

    <script
