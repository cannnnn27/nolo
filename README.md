<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>nolo – Glutenfreie Bäckerei Köln</title>
  <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Quicksand', sans-serif;
      margin: 0;
      background: #fff8f0;
      color: #333;
    }
    header {
      background: #ffcf99;
      padding: 6rem; /* Verdreifacht */
      text-align: center;
      background-image: url('https://images.unsplash.com/photo-1565958011703-44f9829ba187');
      background-size: cover;
      background-position: center;
      color: white;
    }
    header h1 {
      font-size: 12rem; /* Verdreifacht */
      margin: 0;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.3);
    }
    section {
      padding: 2rem;
    }
    .about {
      background: #fff;
      border-radius: 1rem;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      margin: 2rem auto;
      max-width: 800px;
    }
    .products, .order, .contact {
      max-width: 1000px;
      margin: auto;
    }
    .products-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }
    .product {
      background: #fff;
      padding: 1rem;
      border-radius: 1rem;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 0.5rem;
    }
    footer {
      background: #ffe5b4;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
    button {
      background: #ffa07a;
      border: none;
      padding: 0.5rem 1rem;
      font-size: 1rem;
      border-radius: 0.5rem;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>nolo – Deine glutenfreie Bäckerei in Köln</h1>
  </header>

  <section class="about">
    <h2>Über uns</h2>
    <p>Willkommen bei <strong>nolo</strong> – deiner innovativen, glutenfreien Bäckerei mitten im Herzen der Kölner Innenstadt! Ab Juni 2025 versorgen wir dich mit frischen, liebevoll gebackenen Köstlichkeiten – ganz ohne Gluten, aber mit ganz viel Geschmack. Bei uns findest du nicht nur Klassiker wie Brötchen und Brotleibe, sondern auch feine Muffins, Croissants, saisonale Highlights und heiße Getränke wie Kaffee, Kakao und Matcha. Und das Beste: Wir liefern auch direkt zu dir nach Hause!</p>
  </section>

  <section class="products">
    <h2>Unsere Produktpalette</h2>
    <div class="products-grid">
      <div class="product">
        <img src="https://images.unsplash.com/photo-1585238342029-83d63b33c3c1" alt="Brötchen">
        <h3>Normale Brötchen – 1,30 €</h3>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1585238341704-fd2edb33619b" alt="Körnerbrötchen">
        <h3>Körner Brötchen – 1,90 €</h3>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1608198093002-ad4e005484dc" alt="Brotleibe">
        <h3>Brotleibe – 10,00 €</h3>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1565958011703-44f9829ba187" alt="Kuchen">
        <h3>Kuchen – 4,50 €</h3>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1589641266466-997f6f6df779" alt="Muffins">
        <h3>Muffins – 2,50 €</h3>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1618244973378-96f214e3eb57" alt="Saisonware">
        <h3>Saisonware</h3>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1607273175791-0f9a2632cf26" alt="Croissants">
        <h3>Croissants – 3,00 €</h3>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1590080876844-caf665bcec8f" alt="Kekse">
        <h3>Kekse (250g) – 3,50 €</h3>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1587049352841-4b347c9a7b74" alt="Kaffee">
        <h3>Kaffee – 4,50 €</h3>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1611788121052-b452a70767b6" alt="Kakao">
        <h3>Kakao – 3,50 €</h3>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1606335543042-945b4425f5f9" alt="Matcha">
        <h3>Matcha – 4,50 €</h3>
      </div>
    </div>
  </section>

  <section class="order">
    <h2>Bestellen & Liefern lassen</h2>
    <p>Du möchtest deine Lieblingsprodukte nach Hause geliefert bekommen? Kein Problem! Nutze einfach unseren Online-Bestellservice:</p>
    <button onclick="orderNow()">Jetzt bestellen</button>
  </section>

  <section class="contact">
    <h2>Kontakt</h2>
    <p>📍 Ehrenstraße 25, 50672 Köln<br>
    📞 0221 1234567<br>
    ✉️ kontakt@nolo-koeln.de</p>
  </section>

  <footer>
    <p>&copy; 2025 nolo – Glutenfreie Bäckerei Köln</p>
  </footer>

  <script>
    function orderNow() {
      alert("Der Bestellservice wird ab Juni 2025 verfügbar sein. Schau bald wieder vorbei!");
    }
  </script>
</body>
</html>
