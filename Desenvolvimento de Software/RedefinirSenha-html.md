## **Recuperar senha**
<img width="1462" height="783" alt="image" src="https://github.com/user-attachments/assets/9ab41e55-8147-47ec-9de5-56f5d2e07be9" />

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alterar Senha</title>
    <style>
        .banner {
            background-color: #999999;
            width: 100%;
            padding: 20px 0;
            text-align: left;
            position: fixed;
            top: 0;
            left: 0;
            z-index: 1000; /* Z-index alto para garantir que fique acima de outros elementos */
        }
        .banner h1 {
            font-size: 36px;
            margin: 0;
            color: rgb(0, 0, 0);
        }
        .voltar {
            background-color: #999999;
            color: rgb(0, 0, 0);
            font-size: 18px;
            font-weight: bold;
            text-transform: uppercase;
            text-decoration: none; /* Removendo sublinhado padrão */
            padding: 10px 20px; /* Ajustando espaçamento interno */
            position: absolute; /* Posicionamento absoluto em relação ao elemento pai */
            top: 50%; /* Alinha o topo do elemento ao meio do banner */
            transform: translateY(-50%); /* Ajusta a posição verticalmente */
            right: 20px; /* Distância do lado direito */
            }
        body {
            background-color: rgb(92, 9, 170);
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            font-family: Arial, sans-serif;
            color: rgb(255, 255, 255);
        }
        .login-message {
            font-size: 24px;
            text-align: center;
            margin-bottom: 20px;
        }
        .login-form {
            width: 300px;
            background-color: #999999;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
        }
        .input-field {
            width: 100%;
            height: 40px;
            margin-bottom: 10px;
            padding: 5px;
            font-size: 16px;
            border: none;
            border-radius: 4px;
        }
        .confirm-button {
            width: 100%;
            height: 50px;
            background-color: #666666;
            border: none;
            color: white;
            font-size: 18px;
            font-weight: bold;
            text-align: center;
            text-transform: uppercase;
            cursor: pointer;
            margin-top: 20px;
            border-radius: 8px;
        }
        .fundo {
        position: fixed;
        top: 0;
        left: 0;
        width: 100vw;
        height: 100vh; 
        opacity: 0.4; /* Transparência de 40% */
        z-index: -1; /* Envia para o fundo */
        }
        .fundo img {
        width: 100%;
        height: 100%;
        object-fit: cover; /* Garante que a imagem cubra todo o espaço da div */
    }
    </style>
    </head>
    <body>
        <div class="banner">
            <h1>Vorge`Sport</h1>
            <a href="LoginJogador.html" class="voltar">Voltar</a>
        </div>
        <div class="login-message">Jogador</div>
        
</head>
<body>
    <div class="login-form">
        <form action="#">
            <input type="email" class="input-field" placeholder="Digite uma nova senha">
            <input type="password" class="input-field" placeholder="Digite novamente">
            <button type="submit" class="confirm-button" onclick="redirectToPage()">Confirmar</button>
        </form>
    </div>
    
    <div class="fundo">
        <img src="imagens/FundoJ.png" alt="">
    </div>

    <script>
        function redirectToPage() {
            // Redirecionar para a página PagIniTreinador.html
            window.location.href = "PagIniJogador.html";
        }
        </script>

</body>
</html>
