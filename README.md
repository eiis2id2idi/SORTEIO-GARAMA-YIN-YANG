<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sorteio Garama Yin Yang</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            background: white;
            border-radius: 20px;
            padding: 50px 40px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            max-width: 600px;
            width: 100%;
            text-align: center;
            animation: fadeIn 0.5s ease-in;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        h1 {
            color: #333;
            font-size: 2.5em;
            margin-bottom: 40px;
            text-transform: uppercase;
            letter-spacing: 2px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .btn-participar {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            border: none;
            padding: 20px 60px;
            font-size: 1.4em;
            font-weight: bold;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 10px 30px rgba(102, 126, 234, 0.4);
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .btn-participar:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 40px rgba(102, 126, 234, 0.6);
        }

        .btn-participar:active {
            transform: translateY(-2px);
        }

        .instrucoes {
            margin-top: 50px;
            text-align: left;
            background: #f8f9fa;
            padding: 30px;
            border-radius: 15px;
            border-left: 5px solid #667eea;
        }

        .instrucoes h2 {
            color: #333;
            font-size: 1.5em;
            margin-bottom: 20px;
            text-align: center;
        }

        .instrucoes ul {
            list-style: none;
            padding: 0;
        }

        .instrucoes li {
            color: #555;
            font-size: 1.1em;
            margin-bottom: 15px;
            padding-left: 30px;
            position: relative;
            line-height: 1.6;
        }

        .instrucoes li:before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #667eea;
            font-weight: bold;
            font-size: 1.3em;
        }

        .premio {
            background: linear-gradient(135deg, #ffd89b 0%, #19547b 100%);
            color: white;
            padding: 15px;
            border-radius: 10px;
            margin-top: 20px;
            font-size: 1.2em;
            font-weight: bold;
        }

        @media (max-width: 600px) {
            h1 {
                font-size: 1.8em;
            }

            .btn-participar {
                padding: 15px 40px;
                font-size: 1.2em;
            }

            .container {
                padding: 30px 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>SORTEIO GARAMA YIN YANG</h1>
        
        <button class="btn-participar" onclick="participar()">
            CLICK PARA PARTICIPAR
        </button>

        <div class="instrucoes">
            <h2>INSTRUÇÕES</h2>
            <ul>
                <li>Click no botão</li>
                <li>E participe</li>
                <li>Todos que participarem ganham secret de 50m pra casa</li>
            </ul>
            <div class="premio">
                🎁 SECRET DE 50M PARA TODOS! 🎁
            </div>
        </div>
    </div>

    <script>
        function participar() {
            window.location.href = 'https://www.roblox.com/share?code=79127649cd21f84fb622655801eac4e4&type=Server';
        }
    </script>
</body>
</html>
