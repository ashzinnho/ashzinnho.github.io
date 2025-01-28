<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Barra de Navegação</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
    </style>
</head>
<body>

    <nav>
        <a href="#home">Início</a>
        <a href="#sobre">Sobre</a>
        <a href="#contato">Contato</a>
    </nav>

    <div id="home">
        <h1>Bem-vindo ao Início!</h1>
    </div>
    <div id="sobre">
        <h1>Sobre nós</h1>
    </div>
    <div id="contato">
        <h1>Contato</h1>
    </div>

</body>
</html>
