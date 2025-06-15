# munchies<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Morlyf Muchines - Food Truck</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fff6e9;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #fff3d1;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 40px;
    }
    header h1 {
      margin: 0;
    }
    nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    .hero {
      text-align: center;
      padding: 60px 20px;
      background-color: #fde9cc;
    }
    .hero h2 {
      font-size: 32px;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 18px;
    }
    .buttons a {
      display: inline-block;
      margin: 10px;
      padding: 10px 20px;
      border-radius: 6px;
      font-weight: bold;
      color: white;
      text-decoration: none;
    }
    .doordash { background-color: #d94100; }
    .ubereats { background-color: #000000; }
    .chownow { background-color: #d35400; }
    .gallery, .menu, .about {
      padding: 40px 20px;
      text-align: center;
    }
    .gallery img, .about img {
      width: 200px;
      height: auto;
      border-radius: 10px;
      margin: 10px;
    }
    .menu-item {
      margin: 20px 0;
    }
    footer {
      background-color: #f8d89f;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Morlyf Muchines</h1>
    <nav>
      <a href="#menu">Menu</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to Morlyf Muchines!</h2>
    <p>Authentic flavors, served fresh from our food truck.<br>Now taking online orders for pickup or delivery.</p>
    <div class="buttons">
      <a class="doordash" href="#">Order on DoorDash</a>
      <a class="ubereats" href="#">Order on Uber Eats</a>
      <a class="chownow" href="#">Order on ChowNow</a>
    </div>
  </section>

  <section class="gallery">
    <img src="https://via.placeholder.com/200x150?text=Jerk+Chicken+Wrap" alt="Jerk Chicken Wrap" />
    <img src="https://via.placeholder.com/200x150?text=Plantain+Fries" alt="Plantain Fries" />
    <img src="https://via.placeholder.com/200x150?text=Hibiscus+Tea" alt="Hibiscus Tea" />
  </section>

  <section class="menu" id="menu">
    <h2>Menu Highlights</h2>
    <div class="menu-item">
      <strong>🔥 Jerk Chicken Wrap</strong><br>
      Tender, spicy, island flavor in every bite.
    </div>
    <div class="menu-item">
      <strong>🍟 Loaded Plantain Fries</strong><br>
      Drizzled in aioli, herbs & cheese.
    </div>
    <div class="menu-item">
      <strong>🥤 Housemade Hibiscus Tea</strong><br>
      Fresh, sweet, and refreshing.
    </div>
  </section>

  <section class="about">
    <h2>About Us</h2>
    <p>Morlyf Muchines is a mobile kitchen bringing bold Caribbean-American fusion to the streets of Deerfield Beach, Florida.<br>
    Our main location before going mobile is 855 W Sample Rd, Deerfield Beach, FL 33064.<br>
    We believe in fresh flavors, fast service, and feeding the community.</p>
    <img src="https://via.placeholder.com/200x150?text=Our+Truck" alt="Food Truck" />
  </section>

  <footer id="contact">
    <p>📧 Email: morlyfmuchines@gmail.com | 📞 (555) 123-4567</p>
    <p>📍 Based in: Deerfield Beach, FL</p>
    <p>📍 Main Location: 855 W Sample Rd, Deerfield Beach, FL 33064</p>
  </footer>
</body>
</html>
