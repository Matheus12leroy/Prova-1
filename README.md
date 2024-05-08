# Prova-1
codigo 1 da prova 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja de Equipamentos para Gamers</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 20px;
            font-size: 18px;
        }
        nav a:hover {
            color: #ffd700;
        }
        .banner {
            background-image: url('banner.jpg');
            background-size: cover;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            text-align: center;
        }
        .banner h1 {
            font-size: 48px;
            margin: 0;
        }
        .banner p {
            font-size: 24px;
            margin: 20px 0 0;
        }
        .products {
            padding: 20px;
            text-align: center;
        }
        .product {
            display: inline-block;
            width: 250px;
            margin: 20px;
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 10px;
        }
        .product img {
            max-width: 100%;
            border-radius: 5px;
        }
        .product h2 {
            margin-top: 10px;
            font-size: 20px;
        }
        .product p {
            margin-top: 5px;
            font-size: 16px;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            position: absolute;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Loja de Equipamentos para Gamers</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#">Produtos</a>
            <a href="#">Contato</a>
        </nav>
    </header>
    <div class="banner">
        <div>
            <h1>Equipamentos de alta performance para gamers!</h1>
            <p>Encontre os melhores produtos para sua experiência de jogo.</p>
        </div>
    </div>
    <div class="products">
        <div class="product">
            <img src="mouse.jpg" alt="Mouse Gamer">
            <h2>Mouse Gamer</h2>
            <p>R$ 99,99</p>
        </div>
        <div class="product">
            <img src="teclado.jpg" alt="Teclado Gamer">
            <h2>Teclado Gamer</h2>
            <p>R$ 149,99</p>
        </div>
        <div class="product">
            <img src="headset.jpg" alt="Headset Gamer">
            <h2>Headset Gamer</h2>
            <p>R$ 199,99</p>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Loja de Equipamentos para Gamers</p>
    </footer>
</body>
</html>
