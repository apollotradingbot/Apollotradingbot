<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Apollo Trading Bot</title>
  <style>
    /* General Styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      color: #333;
      line-height: 1.6;
      background-color: #f9f9f9;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    button, a.button {
      padding: 10px 20px;
      color: white;
      background-color: #007bff;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1rem;
      text-align: center;
      display: inline-block;
    }

    button:hover, a.button:hover {
      background-color: #0056b3;
    }

    h1, h2 {
      margin-bottom: 20px;
    }

    p {
      margin-bottom: 15px;
    }

    /* Navbar */
    .navbar {
      background-color: #000;
      color: white;
      padding: 15px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .navbar h1 {
      font-size: 1.5rem;
    }

    .navbar nav a {
      margin-left: 15px;
      color: white;
      font-weight: bold;
    }

    .navbar nav a:hover {
      text-decoration: underline;
    }

    /* Hero Section */
    .hero {
      background: url('https://via.placeholder.com/1920x600') no-repeat center center/cover;
      padding: 100px 20px;
      text-align: center;
      color: white;
    }

    .hero h1 {
      font-size: 3rem;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 30px;
    }

    .hero .cta-buttons a {
      margin: 5px;
    }

    /* About Section */
    .about {
      background-color: #fff;
      padding: 50px 20px;
      text-align: center;
    }

    .about h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    .about ul {
      list-style: none;
      padding: 0;
      text-align: left;
      max-width: 600px;
      margin: 20px auto;
    }

    .about ul li {
      font-size: 1.1rem;
      margin-bottom: 10px;
      padding-left: 20px;
      position: relative;
    }

    .about ul li::before {
      content: "✅";
      position: absolute;
      left: 0;
      color: #007bff;
    }

    /* Video Section */
    .video {
      padding: 50px 20px;
      background-color: #f4f4f4;
      text-align: center;
    }

    .video iframe {
      max-width: 100%;
      border: none;
      margin-top: 20px;
    }

    /* Footer */
    footer {
      background-color: #000;
      color: white;
      text-align: center;
      padding: 20px 0;
    }

    footer a {
      color: #0dcaf0;
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      .hero h1 {
        font-size: 2rem;
      }

      .hero p {
        font-size: 1rem;
      }

      .about ul {
        padding: 0 20px;
      }
    }
  </style>
</head>
<body>
  <!-- Navbar -->
  <header class="navbar">
    <h1>Apollo Trading Bot</h1>
    <nav>
      <a href="#about">About</a>
      <a href="https://apollobots.io/?id=TCSERJ" target="_blank">Sign Up</a>
      <a href="https://apollobots.io/login" target="_blank">Login</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Welcome to Apollo Trading Bot</h1>
    <p>Automate your trading and maximize your profits effortlessly with Apollo.</p>
    <div class="cta-buttons">
      <a href="https://apollobots.io/?id=TCSERJ" target="_blank" class="button">Sign Up Now</a>
      <a href="#about" class="button">Learn More</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="about">
    <h2>About Apollo Trading Bot</h2>
    <p>Discover the power of automated profit with Apollo Trading Bot!</p>
    <ul>
      <li>Smart Automation: Save time with intelligent trading strategies tailored to market conditions.</li>
      <li>24/7 Performance: Never miss an opportunity with round-the-clock trading.</li>
      <li>User-Friendly Interface: Easy to use, even for beginners.</li>
      <li>Maximized Profits: Optimize every trade with precision analytics.</li>
    </ul>
    <p>Turn your trading goals into reality with Apollo Trading Bot. Start today and watch your investments grow effortlessly.</p>
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
    <p>Need help? <a href="https://wa.link/asy4t2" target="_blank">Contact Customer Care</a>.</p>
    <p>&copy; 2024 Apollo Trading Bot. All rights reserved.</p>
  </footer>
</body>
</html>
