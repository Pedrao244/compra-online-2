# compra-online-2

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lojas do Pedrão</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e6f7ff;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #007acc;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        .container {
            display: flex;
            justify-content: space-between;
            padding: 10px 20px;
            align-items: center;
            background-color: #005c99;
        }
        .container input[type="text"] {
            padding: 5px;
            width: 60%;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .container button {
            background-color: #007acc;
            color: white;
            border: none;
            padding: 5px 10px;
            border-radius: 5px;
            cursor: pointer;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
            padding: 20px;
        }
        .product {
            background: white;
            border: 1px solid #ccc;
            border-radius: 10px;
            width: 200px;
            padding: 10px;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        footer {
            background-color: #007acc;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Lojas do Pedrão</h1>
        <p>Os melhores produtos pelos menores preços!</p>
    </header>

    <div class="container">
        <input type="text" placeholder="Busque um produto...">
        <button>Buscar</button>
        <button>Carrinho</button>
    </div>

    <main>
        <div class="products">
            <!-- Produto 1 -->
            <div class="product">
                <img src="bicicleta.jpg" alt="Bicicleta">
                <h3>Bicicleta</h3>
                <p>Preço: R$ 1.200,00</p>
            </div>
            <!-- Produto 2 -->
            <div class="product">
                <img src="celular.jpg" alt="Celular">
                <h3>Celular</h3>
                <p>Preço: R$ 800,00</p>
            </div>
            <!-- Produto 3 -->
            <div class="product">
                <img src="bola.jpg" alt="Bola de Futebol">
                <h3>Bola de Futebol</h3>
                <p>Preço: R$ 500,00</p>
            </div>
            <!-- Produto 4 -->
            <div class="product">
                <img src="videogame.jpg" alt="Video Game">
                <h3>Video Game</h3>
                <p>Preço: R$ 1.500,00</p>
            </div>
            <!-- Produto 5 -->
            <div class="product">
                <img src="tv.jpg" alt="TV">
                <h3>TV</h3>
                <p>Preço: R$ 1.800,00</p>
            </div>
            <!-- Produto 6 -->
            <div class="product">
                <img src="tenis.jpg" alt="Tênis Nike">
                <h3>Tênis Nike</h3>
                <p>Preço: R$ 600,00</p>
            </div>
            <!-- Produto 7 -->
            <div class="product">
                <img src="sapato.jpg" alt="Sapato Social">
                <h3>Sapato Social</h3>
                <p>Preço: R$ 700,00</p>
            </div>
            <!-- Produto 8 -->
            <div class="product">
                <img src="geladeira.jpg" alt="Geladeira">
                <h3>Geladeira</h3>
                <p>Preço: R$ 2.500,00</p>
            </div>
        </div>
    </main>

    <footer>
        <p>Contato: (11) 98765-4321 | Email: contato@lojasdopedrao.com.br</p>
        <p>&copy; 2024 Lojas do Pedrão. Todos os direitos reservados.</p>
    </footer>
</body>
</html>