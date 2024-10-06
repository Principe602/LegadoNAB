<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio Emanuel José</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #ffffff;
            color: #333;
        }
        header {
            background-color: #000000;
            color: #ffffff;
            padding: 20px;
            text-align: center;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            margin-top: 10px;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: #ffffff;
            text-decoration: none;
            font-size: 18px;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #ff0000;
        }
        section {
            padding: 40px;
            text-align: center;
        }
        .cta {
            background-color: #ff0000;
            color: #ffffff;
            padding: 15px 30px;
            border: none;
            font-size: 18px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .cta:hover {
            background-color: #d40000;
        }
        .projects {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-top: 40px;
        }
        .project-item {
            background-color: #f5f5f5;
            padding: 20px;
            margin: 10px;
            border: 1px solid #ddd;
            width: 30%;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        .project-item:hover {
            transform: scale(1.05);
        }
        footer {
            background-color: #000000;
            color: #ffffff;
            padding: 20px;
            text-align: center;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Emanuel José - Portfólio e Vendas</h1>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre Mim</a></li>
                <li><a href="#projetos">Projetos</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="sobre">
        <h2>Sobre Mim</h2>
        <p>Bem-vindo à minha página pessoal! Sou Emanuel José, artista especializado em manga, cartoon e comics. Aqui você pode encontrar os meus projetos e adquirir diretamente as minhas obras.</p>
        <button class="cta">Comprar Agora</button>
    </section>

    <section id="projetos">
        <h2>Meus Projetos</h2>
        <div class="projects">
            <div class="project-item">
                <h3>Projeto 1</h3>
                <p>Descrição do Projeto 1. Um trabalho inovador que mistura elementos tradicionais com um toque moderno.</p>
                <button class="cta">Ver Mais</button>
            </div>
            <div class="project-item">
                <h3>Projeto 2</h3>
                <p>Descrição do Projeto 2. Inspirado nos hábitos e costumes de Angola, trazendo uma nova perspectiva artística.</p>
                <button class="cta">Ver Mais</button>
            </div>
            <div class="project-item">
                <h3>Projeto 3</h3>
                <p>Descrição do Projeto 3. Uma obra que explora a cultura e tradições angolanas com detalhes impressionantes.</p>
                <button class="cta">Ver Mais</button>
            </div>
        </div>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>Quer saber mais sobre os meus projetos ou adquirir uma das minhas obras? Entre em contacto comigo!</p>
        <p>Email: <a href="mailto:emanuel.jose@email.com">emanuel.jose@email.com</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Emanuel José. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
