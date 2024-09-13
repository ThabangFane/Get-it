<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Affiliate Marketing Site</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>GET IT</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#blog">Blog</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to My Affiliate Marketing Site</h2>
        <p>Discover valuable content and recommendations on products and services.</p>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Learn more about our mission and how we provide valuable information to help you make informed decisions.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send</button>
        </form>
    </section>

    <section id="blog">
        <h2>Blog</h2>
        <article>
            <h3>Latest Post</h3>
            <p>Check out our latest blog post <a href="#">here</a>!</p>
        </article>
    </section>

    <footer>
        <p>&copy; 2024 My Affiliate Marketing Site. <a href="#">Privacy Policy</a></p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
