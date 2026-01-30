<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Geopherse</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #111;
      color: #fff;
      scroll-behavior: smooth;
    }

    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 20px 50px;
      background: #000;
      position: sticky;
      top: 0;
      z-index: 10;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: color 0.2s;
    }

    nav a:hover {
      color: #63CBEF;
    }

    section {
      padding: 100px 50px;
      min-height: 100vh;
    }

    #logo-section {
      display: flex;
      justify-content: center;
      align-items: center;
      background: #111;
      flex-direction: column;
    }

    #logo-section svg {
      max-width: 600px;
      width: 80%;
      height: auto;
    }

    h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
      color: #FF3A3A;
    }

    .section-content {
      max-width: 900px;
      margin: 0 auto;
      font-size: 1.2rem;
      line-height: 1.6;
    }

    .pricing-card {
      background: #222;
      padding: 20px;
      margin: 20px;
      border-radius: 12px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0,0,0,0.5);
    }

    .pricing-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    #contact a {
      color: #63CBEF;
      font-size: 1.5rem;
      margin-top: 20px;
      text-decoration: none;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #111;
      color: #888;
    }
  </style>
</head>
<body>

  <header>
    <div class="logo">
      <a href="#logo-section" style="color:#FF3A3A; font-weight:bold; font-size:1.5rem;">Geopherse</a>
    </div>
    <nav>
      <a href="#logo-section">Home</a>
      <a href="#models">3D Models</a>
      <a href="#animations">Animations</a>
      <a href="#pricing">Pricing</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Logo Section -->
  <section id="logo-section">
    <svg viewBox="0 0 1200 600" xmlns="http://www.w3.org/2000/svg">
      <rect width="1200" height="600" fill="#000"/>
      <circle cx="360" cy="300" r="210" fill="#63CBEF"/>
      <path d="M 360 90 A 210 210 0 1 0 570 300" fill="none" stroke="#FF3A3A" stroke-width="22" stroke-linecap="round"/>
      <line x1="570" y1="300" x2="360" y2="300" stroke="#FF3A3A" stroke-width="22" stroke-linecap="round"/>
      <polygon points="340,300 390,270 390,330" fill="#FF3A3A"/>
      <text x="600" y="325" font-size="96" font-weight="700" font-family="Arial, Helvetica, sans-serif" fill="#FF3A3A" text-anchor="start">eopherse</text>
      <circle cx="215" cy="300" r="42" fill="#B875E6"/>
      <rect x="195" y="280" width="40" height="40" fill="#E64B8C"/>
      <g stroke="#333" stroke-width="8" stroke-linecap="round">
        <line x1="270" y1="350" x2="270" y2="410"/>
        <line x1="240" y1="380" x2="300" y2="380"/>
      </g>
    </svg>
  </section>

  <!-- 3D Models Section -->
  <section id="models">
    <h2>3D Models</h2>
    <div class="section-content">
      <p>We create high-quality 3D models for any purpose: ads, presentations, or digital experiences. Clients can request custom designs, textures, and animations for their projects. Every model is optimized for smooth rendering and fast integration.</p>
    </div>
  </section>

  <!-- Animations Section -->
  <section id="animations">
    <h2>Animations</h2>
    <div class="section-content">
      <p>Our team provides professional 3D animations to make your brand pop. From product spins to complex scenes, we deliver animation files ready for ads, videos, or websites. Perfect for brands wanting high-end visuals without hiring full-time animators.</p>
    </div>
  </section>

  <!-- Pricing Section -->
  <section id="pricing">
    <h2>Pricing</h2>
    <div class="pricing-container">
      <div class="pricing-card">
        <h3>Basic Model</h3>
        <p>$50</p>
        <p>Single 3D model, low-poly, ready for use.</p>
      </div>
      <div class="pricing-card">
        <h3>Advanced Model</h3>
        <p>$120</p>
        <p>High-poly 3D model with textures and optional animation.</p>
      </div>
      <div class="pricing-card">
        <h3>Full Animation</h3>
        <p>$250</p>
        <p>Custom animation scene with lighting, textures, and rendered output.</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Us</h2>
    <div class="section-content">
      <p>For models, animations, or collaborations, reach out to us directly:</p>
      <a href="mailto:Geopherse@gmail.com">Geopherse@gmail.com</a>
    </div>
  </section>

  <footer>
    &copy; 2026 Geopherse. All rights reserved.
  </footer>

</body>
</html>
