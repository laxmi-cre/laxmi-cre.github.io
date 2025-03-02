
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saadhbahadhur Bungur Premium Pig Farm</title>
    <meta name="description" content="Premium quality pig breeding and farming services. Saadhbahadhur Bungur offers healthy, well-bred pigs with complete documentation and certification.">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            background-color: #f5f5f5;
            line-height: 1.6;
        }

        .header {
            background-color: #8B4513;
            color: black;
            padding: 1rem;
            text-align: center;
        }

        .nav {
            background-color: #A0522D;
            padding: 1rem;
            text-align: center;
        }

        .nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
        }

        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), 
                        url('https://images.unsplash.com/photo-1587923623987-c7e4083beb23?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            height: 60vh;
            background-size: cover;
            background-position: center;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1rem;
            padding: 2rem;
        }

        .pig-card {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .pig-card img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }

        .pig-info {
            padding: 1rem;
        }

        .contact-form {
            max-width: 600px;
            margin: 2rem auto;
            padding: 2rem;
            background: white;
            border-radius: 10px;
        }

        footer {
            background: #8B4513;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }

        .section {
            padding: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        h1 { font-size: 2.5rem; margin-bottom: 1rem; }
        h2 { color: #8B4513; margin: 2rem 0; text-align: center; }
        .highlight { color: #8B4513; font-weight: bold; }
    </style>
</head>
<body>
    <header class="header">
        <h1>Saadhbahadhur Bungur Pig Farm</h1>
        <p>Premium Quality Pig Breeding Since 1995</p>
    </header>

    <nav class="nav">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#pigs">Available Pigs</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="hero">
        <div>
            <h2>Healthy • Well-Bred • Certified</h2>
            <p>Get premium quality pigs with complete health certification</p>
        </div>
    </section>

    <main class="section">
        <section id="about">
            <h2>About Our Farm</h2>
            <p>At <span class="highlight">Saadhbahadhur Bungur</span>, we specialize in breeding high-quality pigs with:</p>
            <ul>
                <li>✔️ Full veterinary certification</li>
                <li>✔️ Organic feeding program</li>
                <li>✔️ 24/7 professional care</li>
                <li>✔️ GPS-tracked health monitoring</li>
            </ul>
        </section>

        <section id="pigs">
            <h2>Available Pigs</h2>
            <div class="gallery">
                <!-- Repeat this card for each pig -->
                <div class="pig-card">
                    <img src="pig1.jpg" alt="Premium Yorkshire Boar - 6 months old">
                    <div class="pig-info">
                        <h3>Yorkshire Boar</h3>
                        <p>Age: 6 months</p>
                        <p>Weight: 120 kg</p>
                        <p>Vaccination: Complete</p>
                    </div>
                </div>
                <!-- Add more pig cards here -->
            </div>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <div class="contact-form">
                <form>
                    <div>
                        <label>Name:</label>
                        <input type="text" required>
                    </div>
                    <div>
                        <label>Email:</label>
                        <input type="email" required>
                    </div>
                    <div>
                        <label>Message:</label>
                        <textarea rows="4" required></textarea>
                    </div>
                    <button type="submit" style="background: #8B4513; color: white; padding: 10px 20px; border: none; margin-top: 1rem;">Send Inquiry</button>
                </form>
            </div>
        </section>
    </main>

    <footer>
        <p>© 2023 Saadhbahadhur Bungur Pig Farm. All rights reserved.</p>
        <p>Contact: +9840074818 | Email: saadhbahadhurpigfarm16@gmail.com</p>
    </footer><!-- Add this in head section -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Farm",
  "name": "Saadhbahadhur Bungur Pig Farm",
  "image": "your-logo.jpg",
  "@id": "",
  "url": "sadhbahadhur.com",
  "telephone": "+9840074818",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "Manthali-3, Ramechhap",
    "addressLocality": "Manthali",
    "postalCode": "05400",
    "addressCountry": "Nepal"
  },
  "geo": {
    "@type": "GeoCoordinates",
    "latitude": 40.7128,
    "longitude": -74.0060
  },
  "openingHoursSpecification": {
    "@type": "OpeningHoursSpecification",
    "dayOfWeek": [
      "Monday",
      "Tuesday",
      "Wednesday",
      "Thursday",
      "Friday"
    ],
    "opens": "09:00",
    "closes": "18:00"
  }
}
</script>
</body>
</html>
