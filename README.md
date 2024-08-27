# hosp
pedido
 <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pedido de Namoro</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-image: url('https://th.bing.com/th/id/OIP.UEc87z74e8RlA1nGPyN76AHaHa?w=174&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7');
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-size: 50%; /* Ajusta a imagem para 50% do tamanho original */
            background-position: center center;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 10px;
        }
        h1 {
            color: #333;
            animation: bounce 2s infinite alternate;
        }
        @keyframes bounce {
            0% {
                transform: translateY(0);
            }
            100% {
                transform: translateY(-10px);
            }
        }
        .btn-container {
            margin-top: 20px;
        }
        .btn {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            margin: 10px;
            display: inline-block;
            position: relative;
            transition: transform 0.3s ease;
        }
        .btn:hover {
            transform: translate(5px, -5px);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Quer namorar comigo?</h1>
        <div class="btn-container">
            <button class="btn" onclick="redirecionar()">Sim</button>
            <button class="btn" onmousemove="fugirNao()">Não</button>
        </div>
    </div>

    <script>
        function redirecionar() {
            window.location.href = "https://youtu.be/1W4ss8HqKlM?si=Z2AvDpjFtH3VgJP7";
        }

        function fugirNao() {
            const naoBtn = document.querySelector(".btn:last-child");
            const randomX = Math.random() * 80;
            const randomY = Math.random() * 80;
            naoBtn.style.left = randomX + "vw";
            naoBtn.style.top = randomY + "vh";
        }
    </script>
</body>
</html>

