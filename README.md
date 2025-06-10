<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Health & Beauty</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #fffaf8;
      color: #333;
    }

    header {
      background-color: #f3c8c8;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    header h1 {
      margin: 0;
      color: #80393e;
      font-size: 1.8rem;
    }

    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #80393e;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      text-align: center;
      padding: 3rem 2rem;
      background: #fff0f5;
    }

    .hero img {
      max-width: 100%;
      height: auto;
      border-radius: 1rem;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }

    .hero h2 {
      margin-top: 2rem;
      font-size: 2rem;
    }

    .content {
      padding: 2rem;
      max-width: 800px;
      margin: auto;
    }

    .contact-form {
      background: #ffffff;
      padding: 2rem;
      border-radius: 1rem;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }

    .contact-form h3 {
      margin-top: 0;
    }

    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 0.8rem;
      margin-top: 0.5rem;
      margin-bottom: 1rem;
      border: 1px solid #ccc;
      border-radius: 0.5rem;
      font-size: 1rem;
    }

    .contact-form button {
      background-color: #e79ca4;
      color: white;
      padding: 0.7rem 1.5rem;
      border: none;
      border-radius: 0.5rem;
      font-size: 1rem;
      cursor: pointer;
    }

    .contact-form button:hover {
      background-color: #cf7d85;
    }

    footer {
      text-align: center;
      padding: 1rem;
      color: #777;
      margin-top: 3rem;
      font-size: 0.9rem;
    }

    @media (max-width: 600px) {
      nav a {
        margin: 0 0.5rem;
      }

      .hero h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Health & Beauty</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#about">Über uns</a>
      <a href="#contact">Kontakt</a>
    </nav>
  </header>

  <section class="hero">
    <img src="https://via.placeholder.com/800x400?text=Health+%26+Beauty" alt="Health & Beauty">
    <h2>Wohlfühlen. Schön sein. Gesund leben.</h2>
  </section>

  <section class="content" id="about">
    <h2>Über uns</h2>
    <p>Willkommen auf unserer Seite rund um Gesundheit, Schönheit und Wohlbefinden! Wir teilen Tipps, Inspirationen und Wissen für dein körperliches und mentales Gleichgewicht.</p>
  </section>

  <section class="content" id="contact">
    <div class="contact-form">
      <h3>Kontaktiere uns</h3>
      <form action="mailto:deine-email@example.com" method="post" enctype="text/plain">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">E-Mail:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Nachricht:</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit">Senden</button>
      </form>
    </div>
  </section>

  <footer>
    &copy; 2025 Natalie – Health & Beauty
  </footer>

</body>
</html>
