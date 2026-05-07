<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Andys Store</title>

  <style>
    body{
      font-family: Arial, sans-serif;
      margin:0;
      background:#fff5ee;
      color:#333;
    }

    nav{
      background:orange;
      padding:15px;
      text-align:center;
      color:white;
      font-size:28px;
      font-weight:bold;
    }

    h1{
      text-align:center;
      margin-top:30px;
    }

    .kategori{
      padding:20px;
    }

    .kategori h2{
      color:orange;
      margin-bottom:15px;
    }

    .menu{
      display:flex;
      flex-wrap:wrap;
      gap:20px;
      justify-content:center;
    }

    .card{
      background:white;
      width:220px;
      padding:15px;
      border-radius:12px;
      box-shadow:0 3px 10px rgba(0,0,0,0.1);
      text-align:center;
    }

    .card img{
      width:100%;
      border-radius:10px;
    }

    .harga{
      color:orange;
      font-weight:bold;
      margin-top:8px;
    }

    button{
      margin-top:10px;
      padding:10px 15px;
      border:none;
      background:orange;
      color:white;
      border-radius:8px;
      cursor:pointer;
    }

    footer{
      background:#222;
      color:white;
      text-align:center;
      padding:15px;
      margin-top:30px;
    }
  </style>
</head>
<body>

  <nav>Andys Store</nav>

  <h1>American Food Menu</h1>

  <!-- MAKANAN -->
  <section class="kategori">
    <h2>Makanan</h2>

    <div class="menu">

      <div class="card">
        <img src="https://via.placeholder.com/220">
        <h3>Burger</h3>
        <p class="harga">$8</p>
        <button>Order</button>
      </div>

      <div class="card">
        <img src="https://via.placeholder.com/220">
        <h3>Cheese Cake</h3>
        <p class="harga">$6</p>
        <button>Order</button>
      </div>

    </div>
  </section>

  <!-- MINUMAN -->
  <section class="kategori">
    <h2>Drinks</h2>

    <div class="menu">

      <div class="card">
        <img src="https://via.placeholder.com/220">
        <h3>Cola</h3>
        <p class="harga">$3</p>
        <button>Order</button>
      </div>

      <div class="card">
        <img src="https://via.placeholder.com/220">
        <h3>Milkshake</h3>
        <p class="harga">$5</p>
        <button>Order</button>
      </div>

    </div>
  </section>

  <footer>
    © 2026 Andys Store
  </footer>

</body>
</html>
