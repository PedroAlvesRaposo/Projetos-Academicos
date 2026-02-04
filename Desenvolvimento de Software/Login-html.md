## **Login**
<img width="1450" height="820" alt="image" src="https://github.com/user-attachments/assets/f0356271-aa75-4527-ac65-58d6e7e9fe32" />

"<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login - Vorge`Sport</title>
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
            <a href="Principal.html" class="voltar">Voltar</a>
        </div>
        <div class="login-message">Jogador</div>
        
</head>
<body>
    <div class="login-form">
        <form action="#">
            <input type="email" class="input-field" placeholder="Digite seu e-mail">
            <input type="password" class="input-field" placeholder="Digite sua senha">
            <button type="submit" class="confirm-button" onclick="redirectToPage()">Confirmar</button>
            <br><br>
            <a href="EsqueciSenhaJ.html" target="_blank">Esqueci a Senha</a>
        </form>
    </div>

    <div class="fundo">
        <img src="imagens/FundoJ.png" alt="">
    </div>

        <script>
        function redirectToPage() {
        // Redirecionar para a página PagIniJogador.html
        window.location.href = "PagIniJogador.html";
        }
</script>
</body>
</html>"
