

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Apollo Trading Bot</title>
  <style>
    /* General Styles */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      line-height: 1.6;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* Navbar */
    .navbar {
      background-color: #000;
      color: #fff;
      padding: 15px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .navbar a {
      color: #fff;
      margin-left: 15px;
      font-weight: bold;
    }

    .navbar a:hover {
      text-decoration: underline;
    }

    /* Hero Section */
    .hero {
      background: url('https://via.placeholder.com/1920x600') no-repeat center center/cover;
      text-align: center;
      color: white;
      padding: 100px 20px;
    }

    .hero h1 {
      font-size: 3rem;
      margin-bottom: 15px;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }

    .hero .btn {
      background-color: #007bff;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
    }

    .hero .btn:hover {
      background-color: #0056b3;
    }

    /* About Section */
    .about {
      padding: 50px 20px;
      background-color: #f4f4f4;
    }

    .about h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    .about ul {
      list-style: none;
      padding: 0;
    }

    .about ul li {
      margin-bottom: 10px;
      font-size: 1.1rem;
    }

    /* Features Section */
    .features {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      text-align: center;
      padding: 50px 20px;
    }

    .features img {
      width: 150px;
      margin: 10px;
    }

    .features p {
      margin-top: 10px;
      font-size: 1rem;
    }

    /* Video Section */
    .video {
      padding: 50px 20px;
      text-align: center;
    }

    .video iframe {
      max-width: 100%;
      border: none;
    }

    /* Footer */
    footer {
      background-color: #000;
      color: #fff;
      text-align: center;
      padding: 20px 0;
    }

    footer a {
      color: #0dcaf0;
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <header class="navbar">
    <h1>Apollo Trading Bot</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="https://apollobots.io/?id=TCSERJ" target="_blank" class="btn">Sign Up</a>
      <a href="https://apollobots.io/login" target="_blank" class="btn">Login</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <h1>Welcome to Apollo Trading Bot</h1>
    <p>Automate your trading and maximize your profits effortlessly.</p>
    <button class="btn" onclick="window.location.href='#about'">Learn More</button>
  </section>

  <!-- About Section -->
  <section id="about" class="about">
    <h2>About Apollo Trading Bot</h2>
    <p>Discover the Power of Automated Profit with Apollo Trading Bot!</p>
    <ul>
      <li>✅ Smart Automation: Save time with intelligent trading strategies tailored to market conditions.</li>
      <li>✅ 24/7 Performance: Never miss an opportunity with round-the-clock trading.</li>
      <li>✅ User-Friendly Interface: Easy to use, even for beginners.</li>
      <li>✅ Maximized Profits: Optimize every trade with precision analytics.</li>
    </ul>
    <p>
      Turn your trading goals into reality with Apollo Trading Bot! Start today and watch your investments grow effortlessly.
    </p>
  </section>

  <!-- Features Section -->
  <section class="features">
    <div>
      <img src="https://via.placeholder.com/150" alt="Feature 1">
      <p>Smart Automation</p>
    </div>
    <div>
      <img src="https://via.placeholder.com/150" alt="Feature 2">
      <p>24/7 Performance</p>
    </div>
    <div>
      <img src="https://via.placeholder.com/150" alt="Feature 3">
      <p>User-Friendly Interface</p>
    </div>
    <div>
      <img src="https://via.placeholder.com/150" alt="Feature 4">
      <p>Maximized Profits</p>
    </div>
  </section>

  <!-- Video Section -->
  <section class="video">
    <h2>Watch Our Introductory Video</h2>
    <iframe 
      width="560" 
      height="315" 
      src="https://www.youtube.com/embed/7CYkLisZ9FI?si=ZT5itE5HhymdG-6J" 
      title="Apollo Trading Bot Intro"
      allowfullscreen>
    </iframe>
  </section>

  <!-- Footer -->
  <footer>
    <p>For support, <a href="https://wa.link/asy4t2" target="_blank">contact customer care</a>.</p>
    <p>&copy; 2024 Apollo Trading Bot. All rights reserved.</p>
  </footer>
</body>
</html>

