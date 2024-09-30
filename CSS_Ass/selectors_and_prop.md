html..
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Web Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to My Web Page</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section id="home">
            <h2>Home</h2>
            <p class="intro">This is the home section.</p>
        </section>
        <section id="about">
            <h2>About</h2>
            <p class="intro">This is the about section.</p>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p class="intro">This is the contact section.</p>
        </section>
    </main>
    <footer>
        <p>© 2024 My Web Page</p>
    </footer>
</body>
</html>

css..
        /* Element selector */

p {
    font-size: 16px;
    color: #333;
}

/* Class selector */
.intro {
    font-style: italic;
    color: #555;
}

/* ID selector */
#home {
    background-color: #f9f9f9;
    padding: 20px;
}

/* Attribute selector */
a[href^="#"] {
    color: #007BFF;
    text-decoration: none;
}

/* Pseudo-class selector */
a:hover {
    text-decoration: underline;
}

/* Pseudo-element selector */
h1::after {
    content: " 🌟";
    color: gold;
}
