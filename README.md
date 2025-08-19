<!DOCTYPE html>
<html lang="ro">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>The Triangle Club Menu</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #111;
      color: #f5f5f5;
    }

    header {
      text-align: center;
      padding: 20px;
      background-color: #000;
    }

    header img {
      max-width: 150px;
      height: auto;
    }

    h1 {
      margin-top: 10px;
      font-size: 1.8em;
      color: gold;
    }

    section {
      max-width: 800px;
      margin: 30px auto;
      padding: 0 20px;
    }

    h2 {
      border-bottom: 1px solid gold;
      padding-bottom: 5px;
      margin-top: 40px;
      color: gold;
    }

    ul {
      list-style: none;
      padding: 0;
    }

    li {
      display: flex;
      justify-content: space-between;
      padding: 8px 0;
      border-bottom: 1px solid #333;
    }

    .item-name {
      flex: 2;
    }

    .item-size {
      flex: 1;
      text-align: center;
    }

    .item-price {
      flex: 1;
      text-align: right;
    }
  </style>
</head>
<body>

  <header>
    <img src="YOUR_LOGO_PATH_HERE.jpeg" alt="The Triangle Club Logo">
    <h1>The Triangle Club</h1>
  </header>

  <section>
    <h2>Băuturi Răcoritoare</h2>
    <ul>
      <li><span class="item-name">Pepsi Cola</span><span class="item-size">0.25L</span><span class="item-price">10.00 RON</span></li>
      <li><span class="item-name">Mirinda Orange</span><span class="item-size">0.25L</span><span class="item-price">10.00 RON</span></li>
      <li><span class="item-name">Evervess Tonic</span><span class="item-size">0.25L</span><span class="item-price">10.00 RON</span></li>
      <!-- Add remaining items similarly -->
    </ul>

    <h2>Cafea</h2>
    <ul>
      <li><span class="item-name">Esspreso</span><span class="item-size">—</span><span class="item-price">7.00 RON</span></li>
      <li><span class="item-name">Cappucino</span><span class="item-size">—</span><span class="item-price">8.00 RON</span></li>
      <li><span class="item-name">Café latte</span><span class="item-size">—</span><span class="item-price">9.00 RON</span></li>
    </ul>

    <h2>Bere Lager la Sticlă</h2>
    <ul>
      <li><span class="item-name">Peroni Nastro Azzurro</span><span class="item-size">0.5L</span><span class="item-price">14.00 RON</span></li>
      <!-- Continue with other beers -->
    </ul>

    <h2>Specialități de Bere</h2>
    <ul>
      <li><span class="item-name">Ursus India Pale Ale</span><span class="item-size">0.33L</span><span class="item-price">12.00 RON</span></li>
      <!-- Continue with others -->
    </ul>

    <h2>Fără Alcool</h2>
    <ul>
      <li><span class="item-name">Ursus Fără Alcool</span><span class="item-size">0.5L</span><span class="item-price">10.00 RON</span></li>
      <!-- Continue with others -->
    </ul>
  </section>

</body>
</html>
