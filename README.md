<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Barbershop</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, sans-serif;
      background: #0f0f0f;
      color: #f2f2f2;
    }
    nav {
      position: sticky;
      top: 0;
      background: #000;
      padding: 16px;
      text-align: center;
      z-index: 100;
    }
    nav a {
      color: #f2f2f2;
      text-decoration: none;
      margin: 0 14px;
      font-weight: 600;
    }
    header {
      min-height: 90vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      background: linear-gradient(rgba(0,0,0,.6), rgba(0,0,0,.6)),
        url('https://images.unsplash.com/photo-1517836357463-d25dfeac3438') center/cover no-repeat;
    }
    header h1 {
      font-size: clamp(2.5rem, 6vw, 4rem);
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.2rem;
      opacity: .9;
    }
    section {
      padding: 80px 10%;
    }
    h2 {
      text-align: center;
      margin-bottom: 50px;
      font-size: 2.2rem;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 24px;
    }
    .box {
      background: #1a1a1a;
      border-radius: 14px;
      padding: 30px;
      text-align: center;
    }
    .box img {
      width: 100%;
      border-radius: 14px;
    }
    footer {
      background: #000;
      text-align: center;
      padding: 24px;
      opacity: .8;
    }
  </style>
</head>
<body>

<nav>
  <a href="#home">Home</a>
  <a href="#services">Services</a>
  <a href="#gallery">Gallery</a>
  <a href="#contact">Contact</a>
</nav>

<header id="home">
  <div>
    <h1>Barbershop</h1>
    <p>Clean cuts. Sharp style.</p>
  </div>
</header>

<section id="services">
  <h2>Services</h2>
  <div class="grid">
    <div class="box">
      <h3>Haircut</h3>
      <p>Modern and classic styles</p>
    </div>
    <div class="box">
      <h3>Beard Trim</h3>
      <p>Precision shaping</p>
    </div>
    <div class="box">
      <h3>Shave</h3>
      <p>Hot towel finish</p>
    </div>
  </div>
</section>

<section id="gallery">
  <h2>Gallery</h2>
  <div class="grid">
    <div class="box"><img src="https://images.unsplash.com/photo-1503951914875-452162b0f3f1" /></div>
    <div class="box"><img src="https://images.unsplash.com/photo-1519699047748-de8e457a634e" /></div>
    <div class="box"><img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9" /></div>
  </div>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p style="text-align:center">Main Street · +212 6 00 00 00 00 · Mon–Sat 9:00–20:00</p>
</section>

<footer>
  <p>© 2025 Barbershop</p>
</footer>

</body>
</html>






