<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SKE – Bus Seat Manufacturing</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f4f4f4;
      color: #333;
    }

    /* NAVBAR */
    nav {
      background: #003366;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px;
      color: #fff;
    }

    nav a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
      font-weight: bold;
    }

    /* HERO */
    .hero {
      background: url('https://images.unsplash.com/photo-1570129477492-45c003edd2be?auto=format&fit=crop&w=1600&q=80')
          center/cover no-repeat;
      height: 450px;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: white;
      padding: 20px;
    }

    .hero h1 {
      font-size: 3rem;
      background: rgba(0,0,0,0.5);
      padding: 20px;
      border-radius: 8px;
    }

    /* SECTIONS */
    section {
      padding: 60px 10%;
    }

    h2 {
      color: #003366;
      margin-bottom: 20px;
    }

    /* PRODUCTS GRID */
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }

    .card img {
      width: 100%;
      border-radius: 8px;
    }

    /* CONTACT FORM */
    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 500px;
    }

    input, textarea {
      padding: 12px;
      border-radius: 6px;
      border: 1px solid #ccc;
    }

    button {
      background: #003366;
      color: white;
      padding: 12px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-size: 1rem;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #002244;
      color: white;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <!-- NAVBAR -->
  <nav>
    <div class="logo"><strong>SKE</strong></div>
    <div>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#products">Products</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <!-- HERO -->
  <div class="hero" id="home">
    <h1>Premium Bus Seats for Modern Transportation</h1>
  </div>

  <!-- ABOUT -->
  <section id="about">
    <h2>About SKE</h2>
    <p>
      SKE is a leading manufacturer of high-quality bus seating solutions.
      We specialize in designing ergonomic, durable, and cost-effective seats 
      for public transportation, school buses, touring buses, and luxury coaches.
      With advanced engineering and strict quality standards, SKE ensures superior safety
      and comfort for passengers worldwide.
    </p>
  </section>

  <!-- PRODUCTS -->
  <section id="products">
    <h2>Our Products</h2>

    <div class="products">
      <div class="card">
        <img src="https://images.unsplash.com/photo-1581091870632-2f75a3d3e0f6?auto=format&fit=crop&w=800&q=80" alt="Standard Bus Seat">
        <h3>Standard Bus Seats</h3>
        <p>Durable and comfortable seating designed for daily city transportation.</p>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1525909002-1b05e0c869d2?auto=format&fit=crop&w=800&q=80" alt="Luxury Bus Seat">
        <h3>Luxury Coach Seats</h3>
        <p>Premium reclining seats engineered for long-distance comfort.</p>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1535909339361-9b1d76f7e5b6?auto=format&fit=crop&w=800&q=80" alt="School Bus Seat">
        <h3>School Bus Seats</h3>
        <p>Safe and reinforced seating built to meet strict school-transport standards.</p>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <h2>Contact Us</h2>
    <p>Have inquiries or want to request a quote? Send us a message.</p>

    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    © 2025 SKE Bus Seat Manufacturing. All rights reserved.
  </footer>

</body>
</html>
