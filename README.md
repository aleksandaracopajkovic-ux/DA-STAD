<!DOCTYPE html>
<html lang="sv">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DA Städ – Din städfirma</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      color: #333;
      background: url('https://images.unsplash.com/photo-1581574202744-059b3b0e15df?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80') no-repeat center center fixed;
      background-size: cover;
    }

    header {
      background-color: rgba(0, 150, 200, 0.85);
      padding: 20px;
      text-align: center;
      color: white;
    }

    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      background: rgba(255, 255, 255, 0.95);
      margin: 20px auto;
      padding: 20px;
      max-width: 900px;
      border-radius: 10px;
    }

    h2 {
      color: #0096c8;
      text-align: center;
      margin-bottom: 20px;
    }

    .services {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
    }

    .service-box {
      background: #f0f9ff;
      padding: 15px;
      border-radius: 8px;
      text-align: center;
      transition: transform 0.3s;
    }

    .service-box img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 8px;
      margin-bottom: 10px;
    }

    .service-box:hover {
      transform: scale(1.05);
    }

    form {
      display: flex;
      flex-direction: column;
    }

    form input, form textarea {
      margin: 10px 0;
      padding: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }

    form button {
      padding: 12px;
      background-color: #0096c8;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }

    form button:hover {
      background-color: #007a9e;
    }

    footer {
      text-align: center;
      padding: 15px;
      background-color: rgba(0, 150, 200, 0.85);
      color: white;
      margin-top: 30px;
    }

    @media(max-width: 700px) {
      .services {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>DA Städ</h1>
  <p>Professionell städning för hem, företag och lokaler</p>
  <nav>
    <a href="#tjanster">Tjänster</a>
    <a href="#kontakt">Kontakt</a>
  </nav>
</header>

<section id="tjanster">
  <h2>Våra tjänster</h2>
  <div class="services">
    <div class="service-box">
      <img src="https://images.unsplash.com/photo-1581574202744-059b3b0e15df?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Hemstäd">
      <h3>Hemstäd</h3>
      <p>Rent och fräscht hem varje vecka eller vid behov.</p>
    </div>
    <div class="service-box">
      <img src="https://images.unsplash.com/photo-1588776814546-71c0d0b4a6b7?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Företagsstäd">
      <h3>Företagsstäd</h3>
      <p>Kontorsstädning som skapar en trivsam arbetsmiljö.</p>
    </div>
    <div class="service-box">
      <img src="https://images.unsplash.com/photo-1602080755396-7fef7b2ad00c?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Lager & lokalstäd">
      <h3>Lager & lokalstäd</h3>
      <p>Effektiv rengöring av lager och lokaler för bästa hygien.</p>
    </div>
    <div class="service-box">
      <img src="https://images.unsplash.com/photo-1581574194847-070bc0c1a5b7?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Trappstäd">
      <h3>Trappstäd</h3>
      <p>Fräscha trapphus som ger ett välkomnande intryck.</p>
    </div>
  </div>
</section>

<section id="kontakt">
  <h2>Kontakta oss</h2>
  <p>Fyll i formuläret nedan (demo) eller maila oss på <b>DAStäd@info.se</b></p>
  <form onsubmit="alert('Tack! Detta är en demo. Inga meddelanden skickas.'); return false;">
    <input type="text" placeholder="Ditt namn" required>
    <input type="email" placeholder="Din e-post" required>
    <textarea rows="5" placeholder="Ditt meddelande"></textarea>
    <button type="submit">Skicka</button>
  </form>
</section>

<footer>
  <p>© 2025 DA Städ – Alla rättigheter förbehållna</p>
</footer>

</body>
</html>
