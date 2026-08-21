#<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Card Curiosidade</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .card {
            background-color: #ffffff;
            width: 380px;
            padding: 40px 30px;
            border-radius: 4px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.15);
            text-align: center;
            box-sizing: border-box;
        }

        .card-icon {
            /* Como é um ícone 3D na imagem original, você pode colocar o caminho da sua imagem aqui */
            width: 70px;
            height: auto;
            margin-bottom: 25px;
        }

        .card-title {
            color: #123e66;
            font-size: 1.5rem;
            margin: 0 0 15px 0;
            line-height: 1.3;
        }

        .card-author {
            color: #123e66;
            font-weight: 700;
            font-size: 1rem;
            margin: 0 0 20px 0;
        }

        .card-text {
            color: #3b5c7a;
            font-size: 0.95rem;
            line-height: 1.5;
            margin: 0 0 20px 0;
        }

        .card-source {
            color: #3b5c7a;
            font-size: 0.95rem;
            margin: 0 0 25px 0;
        }

        .card-source a {
            color: #0000ee;
            text-decoration: underline;
        }

        .reactions {
            display: flex;
            justify-content: center;
            gap: 10px;
        }

        .reaction-btn {
            background-color: #f9f9f9;
            border: 1px solid #c0c0c0;
            border-radius: 3px;
            padding: 4px 12px;
            font-size: 0.9rem;
            cursor: pointer;
            display: flex;
            align-items: center;
            gap: 6px;
            color: #333;
        }

        .reaction-btn:hover {
            background-color: #e9e9e9;
        }
    </style>
</head>
<body>

    <div class="card">
        <!-- Substitua 'icone.png' pelo arquivo da imagem da caixinha 3D se você a tiver salva -->
        <img src="https://em-content.zobj.net/source/microsoft-teams/363/wood_1fab5.png" alt="Ícone de Madeira" class="card-icon">
        
        <h2 class="card-title">O primeiro mouse não era de plástico</h2>
        
        <p class="card-author">Por: Giulliana Cestari</p>
        
        <p class="card-text">
            Antes do design ergonômico e das luzes RGB, o primeiro mouse do mundo foi construído em madeira! Criado por Douglas Engelbart em 1964, ele tinha o formato de uma caixa quadrada e apenas um botão.
        </p>
        
        <p class="card-source">
            Fonte: <a href="#">TecMundo</a>
        </p>
        
        <div class="reactions">
            <button class="reaction-btn">💗 0</button>
            <button class="reaction-btn">👍 0</button>
        </div>
    </div>

</body>
</html>
