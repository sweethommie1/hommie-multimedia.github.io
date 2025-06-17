body {
  font-family: sans-serif;
  margin: 0;
  background: linear-gradient(to bottom, #0d4fff, #ffffff);
  color: #111;
}
header {
  text-align: center;
  padding: 2rem;
}
.tagline {
  font-style: italic;
  color: gold;
}
nav a {
  margin: 0 1rem;
  text-decoration: none;
  font-weight: bold;
  color: white;
}
section {
  padding: 2rem;
}
img {
  width: 100%;
  max-width: 600px;
  margin: 1rem 0;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}
footer {
  text-align: center;
  padding: 1rem;
  background: #000;
  color: white;
}<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Hommie Multimedia</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Hommie Multimedia</h1>
    <p class="tagline">Iamrichhommie</p>
    <nav>
      <a href="#weddings">Weddings</a>
      <a href="#portraits">Portraits</a>
      <a href="#nature">Nature</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="weddings">
    <h2>Weddings</h2>
    <img src="images/wedding1.jpg" alt="Wedding 1" />
    <!-- Add more photos -->
  </section>

  <section id="portraits">
    <h2>Portraits</h2>
    <img src="images/portrait1.jpg" alt="Portrait 1" />
  </section>

  <section id="nature">
    <h2>Nature</h2>
    <img src="images/nature1.jpg" alt="Nature 1" />
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>📱 WhatsApp: <a href="https://wa.me/233XXXXXXXXX">Chat Now</a></p>
    <p>📧 Email: yourname@example.com</p>
  </section>

  <footer>
    <p>© 2025 Hommie Multimedia</p>
  </footer>
</body>
</html>
