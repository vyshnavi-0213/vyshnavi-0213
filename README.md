<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Editkaro Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">Editkaro.in</div>
        <nav>
            <ul>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
     <section class="hero">
        <h1>Transforming Your Vision into Reality</h1>
     </section>
    <section id="portfolio">
        <h2>Our Work</h2>
        <div class="categories">
            <button class="filter" data-category="all">All</button>
            <button class="filter" data-category="short">Short-form</button>
            <button class="filter" data-category="long">Long-form</button>
        </div>
        <div class="video-gallery">
            <div class="video-item" data-category="short">
                <video src="short_video.mp4" muted></video>
            </div>
            <div class="video-item" data-category="long">
                <video src="long_video.mp4" muted></video>
            </div>
        </div>
    </section>
    <section id="about">
        <h2>About Us</h2>
        <p>Editkaro.in specializes in social media marketing and video editing.</p>
    </section>
    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Editkaro.in</p>
        <div class="socials">
            <a href="#">Instagram</a>
            <a href="#">Facebook</a>
            <a href="#">Twitter</a>
        </div>
    </footer>
    <script src="script.js"></script>
</body>
</html>
