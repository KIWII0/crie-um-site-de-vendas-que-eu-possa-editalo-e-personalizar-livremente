<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Loja Online</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 1rem;
            background-color: white;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        .product {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
        }
        .product-item {
            flex: 1 1 calc(33.333% - 2rem);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            overflow: hidden;
            background-color: #fff;
            text-align: center;
        }
        .product-item img {
            max-width: 100%;
            height: auto;
        }
        .product-item h3 {
            margin: 0.5rem 0;
        }
        .product-item p {
            color: #555;
        }
        .product-item .price {
            color: #4CAF50;
            font-size: 1.2rem;
            font-weight: bold;
        }
        .product-item button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            cursor: pointer;
            border-radius: 4px;
            margin: 1rem 0;
        }
        .product-item button:hover {
            background-color: #45a049;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #333;
            color: white;
            margin-top: 2rem;
        }
    </style>
</head>
<body>

<header>
    <h1>Minha Loja Online</h1>
    <p>Os melhores produtos ao melhor preço!</p>
</header>

<div class="container">
    <div class="product">
        <!-- Produto 1 -->
        <div class="product-item">
            <img src="https://via.placeholder.com/300" alt="Produto 1">
            <h3>Produto 1</h3>
            <p>Descrição breve do produto.</p>
            <p class="price">R$ 99,90</p>
            <button>Comprar Agora</button>
        </div>
        <!-- Produto 2 -->
        <div class="product-item">
            <img src="https://via.placeholder.com/300" alt="Produto 2">
            <h3>Produto 2</h3>
            <p>Descrição breve do produto.</p>
            <p class="price">R$ 149,90</p>
            <button>Comprar Agora</button>
        </div>
        <!-- Produto 3 -->
        <div class="product-item">
            <img src="https://via.placeholder.com/300" alt="Produto 3">
            <h3>Produto 3</h3>
            <p>Descrição breve do produto.</p>
            <p class="price">R$ 199,90</p>
            <button>Comprar Agora</button>
        </div>
    </div>
</div>

<footer>
    <p>&copy; 2025 Minha Loja Online. Todos os direitos reservados.</p>
</footer>

</body>
</html>
