luxrolls-website/
├── index.html
└── style.css

// index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LuxRolls - Premium Toilet Paper</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>LuxRolls</h1>
    <p>Luxury & Eco-Friendly Toilet Paper Rolls</p>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#benefits">Benefits</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home">
    <h2>Welcome to LuxRolls</h2>
    <p>Experience the softest and most luxurious toilet paper ever made. With our bumper deal – buy 1 and get 4 unique rolls absolutely free!</p>
  </section>

  <section id="products">
    <h2>Our Products</h2>
    <div class="product">
      <div class="product-item">
        <h3>Ultra Soft Classic</h3>
        <p>Triple-ply, embossed, and soothing comfort in every wipe.</p>
      </div>
      <div class="product-item">
        <h3>Eco Bamboo Roll</h3>
        <p>Made from 100% sustainable bamboo, gentle on skin and planet.</p>
      </div>
      <div class="product-item">
        <h3>Scented Rolls Pack</h3>
        <p>Lavender and rose scented toilet paper for a spa-like bathroom feel.</p>
      </div>
    </div>
  </section>

  <section id="benefits">
    <h2>Why Choose Us?</h2>
    <ul>
      <li>One-time buy, no need to restock frequently</li>
      <li>Luxurious feel, skin-friendly and soft</li>
      <li>Eco-conscious production and packaging</li>
      <li>Buy 1 Get 4 Free unique roll designs</li>
    </ul>
  </section>

  <section id="about">
    <h2>About LuxRolls</h2>
    <p>We started LuxRolls with one mission – to bring elegance and comfort to your bathroom. Our unique toilet paper designs are both environmentally friendly and wonderfully soft, turning an everyday need into a premium experience.</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: contact@luxrolls.com</p>
    <p>Phone: +1 (800) 123-4567</p>
    <p>Address: 20255 Kurta County, Dingdong, Destiny</p>
  </section>

  <footer>
    <p>&copy; 2025 LuxRolls. All rights reserved.</p>
  </footer>
</body>
</html>

// style.css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f5f5f5;
  color: #333;
}
header {
  background-color: #fff;
  padding: 20px;
  text-align: center;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}
header h1 {
  margin: 0;
  color: #4CAF50;
}
nav {
  background-color: #4CAF50;
  padding: 10px;
  text-align: center;
}
nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
}
section {
  padding: 40px 20px;
  max-width: 1000px;
  margin: auto;
  background-color: white;
  margin-top: 20px;
}
footer {
  text-align: center;
  padding: 20px;
  background-color: #ddd;
}
.product {
  display: flex;
  justify-content: space-between;
  margin-top: 20px;
  flex-wrap: wrap;
}
.product-item {
  width: 30%;
  background-color: #f0f0f0;
  margin: 10px 0;
  padding: 15px;
  border-radius: 10px;
}
@media (max-width: 768px) {
  .product-item {
    width: 100%;
