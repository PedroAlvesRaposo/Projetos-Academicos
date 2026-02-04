## **Pagina principal**
<img width="1458" height="793" alt="image" src="https://github.com/user-attachments/assets/5e19794b-967d-4cde-972d-983c3f4c74f0" />

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pagina Jogador</title>
    <style>
        /* Estilos CSS existentes */
        .banner {
            background-color: #999999;
            width: 100%;
            padding: 20px;
            text-align: left;
            position: fixed;
            top: 0;
            left: 0;
            z-index: 1000;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .banner h1 {
            font-size: 36px;
            margin: 0;
            color: rgb(0, 0, 0);
        }
        body {
            background-color: rgb(92, 9, 170);
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: flex-start; /* Alinhar os botões no topo */
            min-height: 100vh; /* Para garantir que a altura da tela seja preenchida */
            font-family: Arial, sans-serif;
            color: white;
            flex-direction: column; /* Empilhar elementos verticalmente */
            position: relative; /* Importante para posicionamento dos pseudoelementos */
        }
        .button-container {
            margin-top: 80px; /* Espaço acima dos botões */
            display: flex;
            flex-direction: column;
            align-items: flex-start; /* Alinhar os botões à esquerda */
        }
        .button {
            width: 300px;
            height: 75px;
            background-color: #999999;
            border: none;
            color: rgb(0, 0, 0);
            font-size: 18px;
            font-weight: bold;
            text-align: center;
            text-transform: uppercase;
            cursor: pointer;
            margin-bottom: 10px; /* Espaço entre os botões */
        }
        .message {
            width: 100%;
            color: rgb(255, 255, 255);
            padding: 100px; /* Espaço entre mensagem e borda do*/
            font-size: 18px;
            text-align: left;
            margin-bottom: -100px; /* Espaço abaixo da mensagem */
        }
        .overlay {
            position: absolute;
            top: 0;
            left: 55%; /* Posiciona no centro horizontalmente */
            transform: translateX(-50%);
            width: 1000px; /* Largura do retângulo central */
            height: 180vh; /* Altura do retângulo central*/
            background-color: rgba(223, 223, 223, 0.7); /* Cor com 70% de transparência */
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
    .imagem1 {
            position:absolute;
            top: 20vh;
            left: 30%; /* Posiciona no centro horizontalmente */
        }
        .imagem2 {
            position:absolute;
            top: 100vh;
            left: 30%; /* Posiciona no centro horizontalmente */
        }
    </style>
</head>
<body>
    <div class="overlay"></div>

    <div class="banner">
        <h1>Vorge`Sport</h1>
        <a href="LoginJogador.html" class="button">Sair</a>
    </div>
    <div class="message">
        <p>Bem-vindo</p>
        <p>Jogador</p>
    </div>

    <div class="fundo">
        <img src="imagens/FundoP.png" alt="">
    </div>
    <div class="imagem1">
        <img src="imagens/TesteM.png" alt="">
    </div>
    <div class="imagem2">
        <img src="imagens/TesteG.png" alt="">
    </div>

    <div class="button-container">
        <button class="button" onclick="openEquipePage()">Equipe</button>
        <button class="button" onclick="openTreinosPage()">Treinos</button>
        <button class="button" onclick="openAnalyticsPage()">Analytics</button>
        <button class="button" onclick="openConfiguracaoPage()">Configuração</button>
    </div>
    <script>
        function openEquipePage() {
            window.location.href = 'PagEquJogador.html'; // Redireciona para a página de equipe do Jogador
        }
        function openTreinosPage() {
            window.location.href = 'PagTreJogador.html'; // Redireciona para a página de treinos do jogador
        }
        function openAnalyticsPage() {
            window.location.href = 'PagAnalJogador.html'; // Redireciona para a página de Análise do Jogador
        }
        function openConfiguracaoPage() {
            window.location.href = 'PagConfigJogador.html'; // Redireciona para a página de Configuração do jogador
        }
    </script>
</body>
</html>
