<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MoneyFirst Enterprise</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }
    header, footer {
      background-color: #003366;
      color: #fff;
      padding: 1em;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      color: #fff;
      text-decoration: none;
    }
    .container {
      max-width: 1200px;
      margin: auto;
      padding: 2em;
    }
    h1, h2 {
      color: #003366;
    }
    .service-card {
      background: #fff;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 1em;
      margin: 1em 0;
    }
    form input, form textarea {
      width: 100%;
      padding: 0.8em;
      margin: 0.5em 0;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    form button {
      background-color: #003366;
      color: white;
      padding: 0.8em 1.5em;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    .product-listing {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
    }
    .product {
      background: white;
      border: 1px solid #ddd;
      padding: 1em;
      border-radius: 6px;
      flex: 1 1 calc(30% - 20px);
    }
    .product button {
      background-color: #007bff;
      color: white;
      border: none;
      padding: 0.5em 1em;
      border-radius: 4px;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>MoneyFirst Enterprise</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#shop">Shop</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>  <section id="home" class="container">
    <h2>Welcome to MoneyFirst Enterprise</h2>
    <p>Your trusted partner in fast, affordable microloans in Malawi.</p>
  </section>  <section id="about" class="container">
    <h2>About Us</h2>
    <p>MoneyFirst Enterprise is a licensed microfinance company based in Malawi. We specialize in providing fast, reliable loans with flexible repayment terms to help you meet your financial goals.</p>
  </section>  <section id="services" class="container">
    <h2>Our Loan Services</h2>
    <div class="service-card">
      <h3>Short-Term Loan - 2 Weeks</h3>
      <p>Interest: 25% | Minimum Amount: MK25,000</p>
    </div>
    <div class="service-card">
      <h3>Mid-Term Loan - 4 Weeks</h3>
      <p>Interest: 45% | Minimum Amount: MK25,000</p>
    </div>
  </section>  <section id="shop" class="container">
    <h2>Shop</h2>
    <p>Pay for loan application fees or buy collateral items (coming soon)</p>
    <div class="product-listing">
      <div class="product">
        <h3>Loan Application Fee</h3>
        <p>MK5,000</p>
        <button>Add to Cart</button>
      </div>
      <div class="product">
        <h3>Collateral Item - Phone</h3>
        <p>MK40,000</p>
        <button>Add to Cart</button>
      </div>
    </div>
  </section>  <section id="contact" class="container">
    <h2>Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" rows="5"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>  <footer>
    <p>&copy; 2025 MoneyFirst Enterprise. All rights reserved.</p>
  </footer>
</body>
</html>
