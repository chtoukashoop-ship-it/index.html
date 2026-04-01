# index.html
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Chtouka Shop</title>

  <style>
    body {
      margin: 0;
      font-family: Arial;
      background: white;
    }

    /* HEADER */
    header {
      display: flex;
      justify-content: space-between;
      padding: 15px 30px;
      background: black;
      color: white;
    }

    .menu a {
      margin: 0 10px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    /* HERO */
    .hero {
      background: url('https://images.unsplash.com/photo-1521335629791-ce4aec67dd47');
      height: 400px;
      background-size: cover;
      display: flex;
      align-items: center;
      padding-left: 50px;
      color: white;
    }

    .hero h1 {
      font-size: 40px;
    }

    .btn {
      background: black;
      color: white;
      padding: 10px 20px;
      text-decoration: none;
      margin-top: 10px;
      display: inline-block;
    }

    /* CATEGORIES */
    .categories {
      display: flex;
      justify-content: center;
      margin: 20px;
    }

    .categories div {
      margin: 10px;
      padding: 10px 20px;
      border: 1px solid black;
      cursor: pointer;
    }

    /* PRODUCTS GRID */
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .card {
      border: 1px solid #ddd;
      padding: 10px;
      text-align: center;
    }

    .card img {
      width: 100%;
    }

    footer {
      background: black;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>

<body>

<!-- HEADER -->
<header>
  <h2>Chtouka Shop</h2>
  <div class="menu">
    <a href="#">Hommes</a>
    <a href="#">Femmes</a>
    <a href="#">Accessoires</a>
  </div>
</header>

<!-- HERO -->
<div class="hero">
  <div>
    <h1>Nouvelle Collection</h1>
    <a class="btn" href="#">Acheter</a>
  </div>
</div>

<!-- CATEGORIES -->
<div class="categories">
  <div>Parfums</div>
  <div>Lunettes</div>
  <div>Bijoux</div>
</div>

<!-- PRODUCTS -->
<div class="products">

  <div class="card">
    <img src="product1.jpg">
    <h3>Parfum Homme</h3>
    <p>199 DH</p>
    <a class="btn" href="https://wa.me/212767559542">Acheter</a>
  </div>

  <div class="card">
    <img src="product2.jpg">
    <h3>Parfum Femme</h3>
    <p>179 DH</p>
    <a class="btn" href="https://wa.me/212767559542">Acheter</a>
  </div>

  <div class="card">
    <img src="product3.jpg">
    <h3>Lunettes</h3>
    <p>99 DH</p>
    <a class="btn" href="https://wa.me/212767559542">Acheter</a>
  </div>

</div>

<!-- FOOTER -->
<footer>
  <p>Contact: +212767559542</p>
</footer>

</body>
</html>
