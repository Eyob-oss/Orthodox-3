<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ethiopian Orthodox Tewahedo Church</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #2c3e50;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #34495e;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
        }
        .section h2 {
            color: #2c3e50;
            border-bottom: 2px solid #2c3e50;
            padding-bottom: 10px;
        }
        footer {
            background-color: #2c3e50;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .gallery img {
            width: 100%;
            max-width: 300px;
            margin: 10px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Ethiopian Orthodox Tewahedo Church</h1>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#liturgy">Liturgy</a>
        <a href="#scripture">Scripture</a>
        <a href="#art">Art & Architecture</a>
        <a href="#festivals">Festivals</a>
        <a href="#monasticism">Monasticism</a>
        <a href="#global">Global Presence</a>
        <a href="#resources">Resources</a>
        <a href="#news">News</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="about" class="section">
            <h2>About the Ethiopian Orthodox Tewahedo Church</h2>
            <p>The Ethiopian Orthodox Tewahedo Church is one of the oldest Christian churches in the world. It has a rich history and unique traditions that have been preserved for centuries.</p>
        </section>

        <section id="liturgy" class="section">
            <h2>Liturgy and Worship</h2>
            <p>The liturgy of the EOTC is deeply spiritual and involves various sacraments, prayers, and hymns that are central to the faith.</p>
        </section>

        <section id="scripture" class="section">
            <h2>Scripture and Teachings</h2>
            <p>The EOTC follows a unique canon of the Bible, which includes 81 books. The teachings of the church are rooted in both scripture and tradition.</p>
        </section>

        <section id="art" class="section">
            <h2>Art and Architecture</h2>
            <p>Ethiopian church architecture and religious art are renowned for their beauty and symbolism. The churches of Lalibela are a prime example.</p>
        </section>

        <section id="festivals" class="section">
            <h2>Festivals and Traditions</h2>
            <p>The EOTC celebrates numerous festivals throughout the year, each with its own unique traditions and significance.</p>
        </section>

        <section id="monasticism" class="section">
            <h2>Monasticism</h2>
            <p>Monasticism plays a vital role in the EOTC, with many monasteries serving as centers of spiritual life and learning.</p>
        </section>

        <section id="global" class="section">
            <h2>Global Presence</h2>
            <p>The EOTC has a growing presence around the world, with diaspora communities establishing churches in many countries.</p>
        </section>

        <section id="resources" class="section">
            <h2>Resources</h2>
            <p>Find books, videos, and other resources to learn more about the Ethiopian Orthodox Tewahedo Church.</p>
        </section>

        <section id="news" class="section">
            <h2>News and Events</h2>
            <p>Stay updated with the latest news and events from the EOTC.</p>
        </section>

        <section id="contact" class="section">
            <h2>Contact and Community</h2>
            <p>Get in touch with the church and join the online community.</p>
        </section>

        <section id="gallery" class="section">
            <h2>Multimedia Gallery</h2>
            <div class="gallery">
                <img src="ethio.jpg" alt="Church Image">
                <img src="ethio2.jpg" alt="Festival Image">
                <img src="ethio3.jpg" alt="Art Image">
     <img src="ethio4.jpg" alt="Art Image">
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2023 Ethiopian Orthodox Tewahedo Church. All rights reserved.</p>
    </footer>

    <script>
        // Simple JavaScript for smooth scrolling
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>

</body>
</html>
