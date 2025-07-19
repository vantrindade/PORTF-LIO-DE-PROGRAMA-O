# FUTURO PORTF-LIO-DE-PROGRAMA-O

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio | [matheus FT]</title>
    <link rel="stylesheet" href="estilo.css">
</head>
<body>
    <header>
        <div class="profile">
            <img src="foto-de-perfil.jpg">
            <h1>[Matheus ferreira trindade]</h1>
            <p class="tagline">[desenvolvedor inciante]</p>
        </div>
        
        <nav>
            <ul>
                <li><a href="#sobre">Sobre Mim</a></li>
                <li><a href="#habilidades">Habilidades</a></li>
                <li><a href="#projetos">Projetos</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="sobre">
            <h2>Sobre Mim</h2>
            <p>estou no 2º ano de analise e desenvolvimento de sistemas. <br>
 atualmento estou  me focando em desenvolvimento web
  treinando minhas habilidades em HTMl, CSS e JavaScript,
aspiro em me torna um desenvolvedor full stack </p>
        </section>

        <section id="habilidades">
            <h2>Habilidades</h2>
            <ul class="skills-list">
                <li>HTML5</li>
                <li>CSS3</li>
                <li>JavaScript</li>
                <li>python</li>

            </ul>
        </section>

        <section id="projetos">
            <h2>Projetos</h2>
            <article class="project">
                <h3>Projeto 1</h3>
                <p>clone do chat GPT.</p>
            </article>
            <article class="project">
                <h3>Projeto 2</h3>
                <p>site de edição de videos e fotos</p>
            </article>
        </section>

        <aside>
            <h3>Curiosidades</h3>
            <p>me sentindo ansioso</p>
            <div class="social-links">
                <a href="[seu-github]">GitHub</a>
                <a href="https://www.linkedin.com/in/matheus-ferreira-trindade-284308227/">LinkedIn</a>
            </div>
        </aside>
    </main>

    <footer>
        <section class="foot" id="Contato">
        <h4>Contato</h4>
        <p>gmail: <a>vantriande.matheus@gmail.com</a></p>
        <p>celular:<a>(11)999450057</a></p>
    </footer>
</body>
</html>

body {
        line-height: 1.6;
        color: #333;
        background-color: #c7c7c7;
    }

    header {
        background: linear-gradient(135deg, #316aa4, #022f3e);
        color: white;
        text-align: center;
        padding: 2rem 1rem;
    }

    .profile img {
        width: 150px;
        height: 150px;
        border-radius: 80%;
        object-fit: cover;
        border: 3px solid white;
        margin-bottom: 1rem;
    }

    .tagline {
        font-style: italic;
        margin: 0.5rem 0;
    }

    nav ul {
        display: flex;
        justify-content: center;
        list-style: none;
        margin-top: 1.5rem;
    }

    nav li {
        margin: 0 1rem;
    }

    nav a {
        color: white;
        text-decoration: none;
        font-weight: bold;
        padding: 0.5rem 1rem;
        border-radius: 5px;
        transition: background-color 0.3s;
    }

    nav a:hover {
        background-color: rgba(255, 255, 255, 0.2);
    }

    main {
        max-width: 1200px;
        margin: 2rem auto;
        padding: 0 1rem;
    }

    section {
        margin-bottom: 3rem;
        padding: 1.5rem;
        background: white;
        border-radius: 8px;
        box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    h2 {
        color: #2c3e50;
        margin-bottom: 1rem;
        padding-bottom: 0.5rem;
        border-bottom: 2px solid #3498db;
    }

    .skills-list {
        display: flex;
        flex-wrap: wrap;
        gap: 1rem;
        list-style: none;
    }

    .skills-list li {
        background: #3498db;
        color: white;
        padding: 0.5rem 1rem;
        border-radius: 20px;
    }

    .project {
        margin-bottom: 1.5rem;
        padding: 1rem;
        border-left: 4px solid #3498db;
    }

    .project h3 {
        color: #2c3e50;
    }

    /* Aside */
    aside {
        background: #e8f4fc;
        padding: 1.5rem;
        border-radius: 8px;
        margin-bottom: 2rem;
    }

    .social-links {
        display: flex;
        gap: 1rem;
        margin-top: 1rem;
    }

    .social-links a {
        color: #2980b9;
        text-decoration: none;
        font-weight: bold;
    }

.foot    {
        text-align: center;
        padding: 1.5rem;
        background: #2c3e50;
        color: white;
    }

    footer a {
        color: #3498db;
    }

