
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Meu Portfólio</title>
    <link rel="stylesheet" href="re/css">
</head>
<body>

<header>
    <h1>Meu Portfólio</h1>
    <nav>
        <a href="#sobre">Sobre</a>
        <a href="#interesses">Interesses</a>
        <a href="#tecnologias">Tecnologias</a>
        <a href="#contato">Contato</a>
    </nav>
</header>

<section id="sobre">
    <h2>Sobre Mim</h2>
    <p>Olá! Meu nome é Nicolas. Sou estudante de programação e estou aprendendo desenvolvimento web.</p>
    <p>Estou em busca de estagio para ampliar mais meus conhecimentos em tecnologia.</p>
</section>

<section id="interesses">
    <h2>Áreas de Interesse</h2>
    <ul>
        <li>Desenvolvimento Web</li>
        <li>Programação em C</li>
        <li>Estruturas de dados</li>
        <li>Lógica de programação</li>
    </ul>
</section>

<section id="tecnologias">
    <h2>Tecnologias que Domino</h2>
    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
        <li>Linguagem C</li>
    </ul>
</section>

<section id="contato">
    <h2>Contato</h2>
    <p>LinkedIn: <a href="#">Seu LinkedIn</a></p>
    <p>GitHub: <a href="https://github.com/nick0-glitch" target="_blank">nick0-glitch</a></p>
</section>

<button onclick="mostrarMensagem()">Clique em mim</button>

<script src="script.js"></script>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #f4f4f4;
    color: #333;
}


header {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
}


nav a {
    color: white;
    margin: 10px;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    color: #00bcd4;
}


section {
    background: white;
    margin: 20px auto;
    padding: 20px;
    max-width: 800px;
    border-radius: 8px;
}


h2 {
    border-bottom: 2px solid #ddd;
}


ul {
    padding: 0;
}

li {
    margin: 5px 0;
}


button {
    display: block;
    margin: 20px auto;
    padding: 10px;
    background-color: #00bcd4;
    color: white;
    border: none;
    border-radius: 5px;
}

button:hover {
    background-color: #0097a7;
}
