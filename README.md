<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rizwan Khan | Fitness & Design</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #ffffff;
      color: #333;
    }
    header {
      background: #111;
      color: white;
      padding: 30px;
      text-align: center;
    }
    nav {
      background: #222;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    h2, h3 {
      color: #007BFF;
    }
    .hero {
      text-align: center;
    }
    .buttons a {
      background: #007BFF;
      color: white;
      padding: 12px 24px;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      margin: 10px;
      display: inline-block;
    }
    .ebook img {
      width: 100%;
      max-width: 300px;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }
    .portfolio-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .portfolio-grid img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.2);
    }
    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 50px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Rizwan Khan</h1>
    <p>Fitness Coach & Graphic Designer</p>
  </header>

  <nav>
    <a href="#ebook">Ebook</a>
    <a href="#design">Design</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero">
    <h2>Transform Your Body & Brand from Home</h2>
    <p>Download my ebook or hire me for stunning design work</p>
    <div class="buttons">
      <a href="#ebook">📘 Buy My Ebook</a>
      <a href="#design">🎨 Design Services</a>
    </div>
  </section>

  <section id="ebook" class="ebook">
    <h3>📘 Fit at Home - Fitness Ebook</h3>
    <img src="https://i.postimg.cc/wMjshFC5/ebook-cover.jpg" alt="Ebook Cover">
    <p><strong>Author:</strong> Rizwan Khan</p>
    <p>Learn how to stay fit from the comfort of your home with easy workouts, meal tips, and a 7-day challenge. Perfect for beginners!</p>
    <ul>
      <li>No gym required</li>
      <li>7-day transformation plan</li>
      <li>Basic nutrition guide</li>
    </ul>
    <a href="https://your-buy-link.com" class="buttons" target="_blank">💳 Buy Now</a>
  </section>

  <section id="design">
    <h3>🎨 Graphic Design Portfolio</h3>
    <p>I create eye-catching designs for:</p>
    <ul>
      <li>Product Packaging</li>
      <li>Ebook Covers</li>
      <li>Thumbnails & Posters</li>
    </ul>

    <div class="portfolio-grid">
      <img src="https://i.postimg.cc/dt9ddfBk/facewash.jpg" alt="Face Wash">
      <img src="https://i.postimg.cc/gJQrTxgF/perfume.jpg" alt="Perfume Jarva">
      <img src="https://i.postimg.cc/4dyYQ4nJ/skincare.jpg" alt="Skincare Tube">
      <img src="https://i.postimg.cc/wMjshFC5/ebook-cover.jpg" alt="Ebook Cover">
    </div>
  </section>

  <section id="contact">
    <h3>📞 Contact Me</h3>
    <p><strong>Email:</strong> kingkingobaloch@gmail.com</p>
    <p><strong>WhatsApp:</strong> 03192995990</p>
    <a href="https://wa.me/923192995990" target="_blank" class="buttons">📲 Message on WhatsApp</a>
  </section>

  <footer>
    &copy; 2025 Rizwan Khan — All rights reserved.
  </footer>

</body>
</html>
