<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Venda de Velas Espirituais</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #4a4a4a;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px 0;
        }
        .vela {
            display: flex;
            flex-wrap: wrap;
            margin-bottom: 20px;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .vela img {
            width: 200px;
            height: auto;
            margin-right: 20px;
        }
        .vela-info {
            flex: 1;
        }
        .vela-info h2 {
            margin: 0 0 10px 0;
        }
        .vela-info p {
            margin: 5px 0;
        }
        .vela-info .preco {
            font-weight: bold;
            color: #d9534f;
        }
        .frete-link {
            display: block;
            text-align: center;
            margin: 20px 0;
            padding: 10px 20px;
            background-color: #5bc0de;
            color: white;
            text-decoration: none;
            border-radius: 8px;
        }
        footer {
            background-color: #4a4a4a;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Venda de Velas Espirituais</h1>
</header>

<div class="container">
    <div class="vela">
        <img src="vela-perfumada.jpg" alt="Vela Perfumada">
        <div class="vela-info">
            <h2>Vela Perfumada</h2>
            <p>Descrição: Vela com aroma suave e relaxante.</p>
            <p class="preco">R$ 15,00</p>
        </div>
    </div>

    <div class="vela">
        <img src="vela-orixa.jpg" alt="Vela Consagrada aos Orixás">
        <div class="vela-info">
            <h2>Vela Consagrada aos Orixás</h2>
            <p>Descrição: Vela consagrada a diversos Orixás.</p>
            <p class="preco">R$ 25,00</p>
        </div>
    </div>

    <div class="vela">
        <img src="vela-ervas.jpg" alt="Vela com Ervas">
        <div class="vela-info">
            <h2>Vela com Ervas</h2>
            <p>Descrição: Vela com ervas especiais para purificação.</p>
            <p class="preco">R$ 20,00</p>
        </div>
    </div>

    <div class="vela">
        <img src="vela-personalizada.jpg" alt="Vela Personalizada">
        <div class="vela-info">
            <h2>Vela Personalizada</h2>
            <p>Descrição: Vela personalizada conforme sua necessidade.</p>
            <p class="preco">R$ 30,00</p>
        </div>
    </div>

    <a href="calcular-frete.html" class="frete-link">Calcular Frete</a>
</div>

<footer>
    <p>&copy; 2024 Venda de Velas Espirituais. Todos os direitos reservados.</p>
</footer>

</body>
</html>
