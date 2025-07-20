<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>babaBundle – Newborn Gift Sets</title>
  <style>
    :root {
      --pink: #f8d5e4;
      --grey: #f0f0f0;
      --text: #444;
      --accent: #e89cb4;
      --white: #ffffff;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--white);
      color: var(--text);
    }

    header {
      background-color: var(--grey);
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 1.8rem;
      font-weight: bold;
      color: var(--accent);
    }

    .nav-links {
      list-style: none;
      display: flex;
      gap: 1.2rem;
    }

    .nav-links a {
      text-decoration: none;
      color: var(--text);
      font-weight: 500;
    }

    .hero {
      text-align: center;
      padding: 3rem 2rem;
      background: var(--pink);
    }

    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }

    .btn {
      display: inline-block;
      padding: 0.75rem 1.5rem;
      background-color: var(--accent);
      color: white;
      border: none;
      border-radius: 5px;
      text-decoration: none;
      margin-top: 1rem;
    }

    .featured-bundles {
      padding: 2rem;
    }

    .bundle-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      justify-content: center;
    }

    .bundle-card {
      background-color: var(--grey);
      border-radius: 8px;
      padding: 1rem;
      width: 300px;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
      text-align: center;
    }

    .bundle-card img {
      width: 100%;
      border-radius: 5px;
    }

    .footer {
      text-align: center;
      padding: 1.5rem;
      background-color: var(--grey);
      font-size: 0.9rem;
      color: #888;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">babaBundle</div>
    <nav>
      <ul class="nav-links">
        <li><a href="#">Home</a></li>
        <li><a href="#">Gift Sets</a></li>
        <li><a href="#">About Us</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">FAQs</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero">
    <h1>Thoughtfully Curated Newborn Gift Sets</h1>
    <p>Beautiful bundles for little blessings, wrapped with love.</p>
    <a href="#" class="btn">Shop Bundles</a>
  </section>

  <section class="featured-bundles">
    <h2 style="text-align:center;">Popular Gift Sets</h2>
    <div class="bundle-grid">
      <div class="bundle-card">
        <img src="https://placehold.co/300x200?text=Mini+Snuggle+Bundle" alt="3-item Bundle">
        <h3>Mini Snuggle Bundle</h3>
        <p>Baby Grow, Bib, Blanket</p>
        <span>R299</span>
      </div>
      <div class="bundle-card">
        <img src="https://placehold.co/300x200?text=Deluxe+Cuddle+Box" alt="6-item Bundle">
        <h3>Deluxe Cuddle Box</h3>
        <p>Grow, Swaddle, Teddy, Bib, Socks, Hat</p>
        <span>R599</span>
      </div>
      <div class="bundle-card">
        <img src="https://placehold.co/300x200?text=Ultimate+babaBundle" alt="10-item Bundle">
        <h3>Ultimate babaBundle</h3>
        <p>10-piece set with personalized blanket</p>
        <span>R999</span>
      </div>
    </div>
  </section>

  <footer class="footer">
    <p>&copy; 2025 babaBundle. All rights reserved.</p>
  </footer>
</body>
</html>
