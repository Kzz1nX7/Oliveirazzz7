<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meus Produtos na Temu</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f9f9f9;
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #ff6f61;
            color: white;
            padding: 20px 0;
        }
        h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        .container {
            padding: 20px;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .product-card {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
            transition: transform 0.3s ease;
        }
        .product-card:hover {
            transform: translateY(-10px);
        }
        .product-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .product-card h3 {
            margin: 15px 0;
            font-size: 1.2rem;
        }
        .product-card p {
            padding: 0 15px;
            font-size: 0.9rem;
            color: #666;
        }
        .product-card a {
            display: inline-block;
            margin: 15px;
            padding: 10px 20px;
            background-color: #ff6f61;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }
        .product-card a:hover {
            background-color: #e65a50;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 10px 0;
            margin-top: 20px;
        }
        footer a {
            color: #ff6f61;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Meus Produtos na Temu</h1>
        <p>Confira os produtos que eu recomendo!</p>
    </header>

    <div class="container">
        <div class="product-grid">
            <!-- Produto 1 -->
            <div class="product-card">
                <img src="https://via.placeholder.com/250" alt="Produto 1">
                <h3>Produto 1</h3>
                <p>Descrição breve do Produto 1. Ideal para quem busca qualidade e estilo.</p>
                <a href="https://www.temu.com/link-do-produto-1" target="_blank">Comprar Agora</a>
            </div>

            <!-- Produto 2 -->
            <div class="product-card">
                <img src="https://via.placeholder.com/250" alt="Produto 2">
                <h3>Produto 2</h3>
                <p>Descrição breve do Produto 2. Perfeito para o seu dia a dia.</p>
                <a href="https://www.temu.com/link-do-produto-2" target="_blank">Comprar Agora</a>
            </div>

            <!-- Produto 3 -->
            <div class="product-card">
                <img src="https://via.placeholder.com/250" alt="Produto 3">
                <h3>Produto 3</h3>
                <p>Descrição breve do Produto 3. Design moderno e funcional.</p>
                <a href="https://www.temu.com/link-do-produto-3" target="_blank">Comprar Agora</a>
            </div>

            <!-- Adicione mais produtos conforme necessário -->
        </div>
    </div>

    <footer>
        <p>&copy; 2023 Meus Produtos na Temu. Todos os direitos reservados.</p>
        <p><a href="https://www.tiktok.com/@seu_perfil" target="_blank">Siga-me no TikTok</a></p>
    </footer>
</body>
</html>
