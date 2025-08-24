<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AZAD AUDIO - Electronics & Sound Shop</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #111;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      margin: 5px 0 0;
      font-size: 1.2rem;
    }
    nav {
      background: #222;
      text-align: center;
      padding: 10px;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1511379938547-c1f69419868d') no-repeat center/cover;
      color: white;
      text-align: center;
      padding: 100px 20px;
    }
    .hero h2 {
      font-size: 2.5rem;
    }
    .section {
      padding: 50px 20px;
      max-width: 1100px;
      margin: auto;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .product {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      padding: 20px;
      text-align: center;
    }
    .product img {
      width: 100%;
      border-radius: 10px;
      height: 180px;
      object-fit: cover;
    }
    .contact {
      text-align: center;
    }
    .btn {
      display: inline-block;
      padding: 12px 20px;
      margin: 10px;
      background: #111;
      color: white;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    .btn:hover {
      background: #e63946;
    }
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>AZAD AUDIO</h1>
    <p>Your Trusted Sound & Electronics Shop</p>
  </header>

  <nav>
    <a href="#products">Products</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h2>Powerful Sound. Quality Electronics.</h2>
    <p>Speakers • Amplifiers • Microphones • Headphones</p>
  </section>

  <section id="products" class="section">
    <h2>Our Products</h2>
    <div class="products">
      <div class="product">
        <img src="https://images.unsplash.com/photo-1580894741223-6c4b2c8f5f05" alt="Speaker">
        <h3>High Bass Speaker</h3>
        <p>₹4,999</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1519671482749-fd09be7ccebf" alt="Amplifier">
        <h3>Professional Amplifier</h3>
        <p>₹7,499</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1581276879432-15a19d654956" alt="Microphone">
        <h3>Studio Microphone</h3>
        <p>₹2,199</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1512058564366-18510be2db19" alt="Headphones">
        <h3>Noise-Cancel Headphones</h3>
        <p>₹3,299</p>
      </div>
    </div>
  </section>

  <section id="about" class="section">
    <h2>About Us</h2>
    <p>
      At <b>AZAD AUDIO</b>, we provide top-quality sound equipment and electronics.  
      From high-bass speakers to professional amplifiers, microphones, and headphones —  
      we ensure our customers get the best audio experience at affordable prices.
    </p>
  </section>

  <section id="contact" class="section contact">
    <h2>Contact Us</h2>
    <p>We’d love to hear from you! Reach us on WhatsApp or Email.</p>
    <a class="btn" href="https://wa.me/918949743963" target="_blank">💬 WhatsApp Us</a>
    <a class="btn" href="mailto:HR.Azadaudio@gmail.com">📧 Email Us</a>
  </section>

  <footer>
    <p>© 2025 AZAD AUDIO. All Rights Reserved.</p>
  </footer>

</body>
</html>
