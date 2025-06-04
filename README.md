
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Lucy Anne Hair Care</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #fdf6f0;
      color: #3c3c3c;
    }
    header {
      background-color: #a4cbb7;
      color: white;
      padding: 20px 10px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
      font-weight: bold;
    }
    header p {
      font-size: 1.1rem;
      font-style: italic;
      margin-top: 5px;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #7aa78d;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: 600;
      font-size: 1.1rem;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 15px;
    }
    section {
      margin-bottom: 50px;
    }
    section h2 {
      font-size: 2rem;
      border-bottom: 2px solid #a4cbb7;
      padding-bottom: 10px;
      margin-bottom: 20px;
      color: #567a6f;
    }
    .product-list {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
    }
    .product {
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      flex: 1 1 250px;
      padding: 15px;
      text-align: center;
    }
    .product img {
      max-width: 100%;
      border-radius: 8px;
    }
    .product h3 {
      margin: 15px 0 10px;
      color: #3c3c3c;
    }
    .product p {
      font-size: 0.95rem;
      line-height: 1.4;
      color: #555;
    }
    footer {
      background-color: #a4cbb7;
      color: white;
      text-align: center;
      padding: 15px 10px;
      font-size: 0.9rem;
    }
    .contact-info {
      margin-top: 10px;
      font-style: italic;
    }
  </style>
</head>
<body>
  <header>
    <h1>Lucy Anne Hair Care</h1>
    <p>Regain your hairfidence with natural, effective hair growth products.</p>
  </header>
  <nav>
    <a href="#about">About</a>
    <a href="#products">Products</a>
    <a href="#contact">Contact</a>
  </nav>
  <main>
    <section id="about">
      <h2>About Lucy Anne Hair Care</h2>
      <p>At Lucy Anne Hair Care, we believe everyone deserves healthy, beautiful hair. Our natural, science-backed formulas help you regain your confidence by promoting hair growth and scalp health without harsh chemicals.</p>
      <p>All our products are cruelty-free and made with love for your hair’s unique needs.</p>
    </section>

    <section id="products">
      <h2>Our Products</h2>
      <div class="product-list">
        <div class="product">
          <img src="https://via.placeholder.com/250x250.png?text=Hair+Growth+Oil" alt="Hair Growth Oil" />
          <h3>Hair Growth Oil</h3>
          <p>Rich in natural oils and vitamins, this formula nourishes your scalp and stimulates hair growth.</p>
        </div>
        <div class="product">
          <img src="https://via.placeholder.com/250x250.png?text=Strengthening+Shampoo" alt="Strengthening Shampoo" />
          <h3>Strengthening Shampoo</h3>
          <p>Gentle yet effective shampoo that cleanses while strengthening hair from root to tip.</p>
        </div>
        <div class="product">
          <img src="https://via.placeholder.com/250x250.png?text=Moisturizing+Conditioner" alt="Moisturizing Conditioner" />
          <h3>Moisturizing Conditioner</h3>
          <p>Hydrates and smooths your hair, reducing breakage and improving manageability.</p>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <p>Have questions or want to learn more? Reach out to us!</p>
      <p class="contact-info">
        Email: <a href="mailto:info@lucyannehaircare.com">info@lucyannehaircare.com</a><br />
        Instagram: <a href="https://instagram.com/luan_naturals" target="_blank">@luan_naturals</a>
      </p>
    </section>
  </main>
  <footer>
    &copy; 2025 Lucy Anne Hair Care. All rights reserved.
  </footer>
</body>
</html>