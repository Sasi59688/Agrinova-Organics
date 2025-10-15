<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Agrinova Organics</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Roboto', sans-serif; margin:0; padding:0; }
    header { background-color: #2E7D32; color: #fff; padding: 40px 20px; text-align: center; }
    header h1 { margin:0; font-size: 2.5em; }
    header p { font-size: 1.2em; }
    section { padding: 40px 20px; }
    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    .product { border: 1px solid #ddd; border-radius: 8px; padding: 20px; text-align: center; }
    .product img { max-width: 100%; border-radius: 8px; }
    footer { background-color: #1B5E20; color: #fff; text-align: center; padding: 20px; }
    .btn { background-color: #4CAF50; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; display: inline-block; margin-top: 10px; }
  </style>
</head>
<body>

<header>
  <h1>Agrinova Organics</h1>
  <p>Fresh, Organic & Fertilized Produce Direct From Farmers to Your Home</p>
  <a href="#products" class="btn">Explore Products</a>
</header>

<section id="products">
  <h2 style="text-align:center;">Our Products</h2>
  <div class="products">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1582515073490-399813c2a3b5" alt="Organic Vegetables">
      <h3>Organic Vegetables</h3>
      <p>Fresh, chemical-free vegetables directly from trusted farmers.</p>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1574226516831-e1dff420e9a6" alt="Organic Fruits">
      <h3>Organic Fruits</h3>
      <p>Sweet and nutritious fruits harvested at peak ripeness.</p>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1607082349394-592dcf6cda36" alt="Fertilized Produce">
      <h3>Fertilized Produce</h3>
      <p>High-quality non-organic produce to encourage farmers’ transition.</p>
    </div>
  </div>
</section>

<section style="background-color:#E8F5E9;">
  <h2 style="text-align:center;">Why Choose Agrinova?</h2>
  <p style="max-width:800px;margin:20px auto;text-align:center;">
    We connect farmers directly with consumers, ensuring fair pricing, fresh produce, and sustainable farming practices. Enjoy transparency and quality with every order.
  </p>
</section>

<footer>
  <p>&copy; 2025 Agrinova Organics | Follow us on social media for updates!</p>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agrinova Organics</title>
    <style>
        body { font-family: Arial, sans-serif; margin:0; padding:0; background-color:#f6f6f6; color:#333; }
        header { background-image: url('images/hero.jpg'); background-size: cover; color:white; padding:60px 20px; text-align:center; }
        header h1 { font-size: 3em; margin:0; }
        header p { font-size: 1.2em; }
        nav { background-color:#4CAF50; overflow:hidden; }
        nav a { float:left; display:block; color:white; text-align:center; padding:14px 16px; text-decoration:none; font-weight:bold; }
        nav a:hover { background-color:#ddd; color:black; }
        section { padding:40px 20px; }
        h1,h2 { margin-top:0; }
        footer { background-color:#4CAF50; color:white; text-align:center; padding:20px; }
        .container { max-width: 1000px; margin: auto; }
        .card { background-color:white; padding:20px; margin:20px 0; border-radius:8px; box-shadow:0 4px 8px rgba(0,0,0,0.2); }
        .services img { width:100%; border-radius:8px; margin-bottom:15px; }
        .btn { display:inline-block; padding:10px 20px; background-color:#4CAF50; color:white; text-decoration:none; border-radius:5px; margin-top:10px; }
        .btn:hover { background-color:#45a049; }
    </style>
</head>
<body>

<header>
    <h1>Agrinova Organics</h1>
    <p>Empowering farmers, connecting directly with consumers</p>
</header>

<nav>
    <a href="#mission">Mission</a>
    <a href="#services">Our Services</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    <section id="mission" class="card">
        <h2>Our Mission</h2>
        <img src="images/mission.jpg" alt="Mission Image">
        <p>We aim to eliminate middlemen, ensuring farmers earn fair prices while providing fresh, high-quality produce to consumers. We support both organic and conventional farming and foster a sustainable agricultural ecosystem.</p>
        <a class="btn" href="#contact">Join Us</a>
    </section>

    <section id="services" class="card">
        <h2>Our Services</h2>
        <img src="images/services.jpg" alt="Services Image">
        <ul>
            <li>Direct marketplace for farmers to sell produce</li>
            <li>Guidance and tools for organic farming</li>
            <li>Fertilizer supply and farm support</li>
            <li>Fast and reliable delivery to consumers</li>
        </ul>
        <a class="btn" href="#contact">Explore Services</a>
    </section>

    <section id="contact" class="card">
        <h2>Contact Us</h2>
        <img src="images/contact.jpg" alt="Contact Image">
        <p>Email: support@agrinovaorganics.com</p>
        <p>Phone: +91-XXXXXXXXXX</p>
        <a class="btn" href="mailto:support@agrinovaorganics.com">Email Us</a>
    </section>
</div>

<footer>
    <p>&copy; 2025 Agrinova Organics</p>
</footer>

</body>
</html>
