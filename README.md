<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Portfólio - Kelly Landgraf</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        :root {
            --cor-principal: #ffe0f0;
            --cor-secundaria: #af358a;
        }
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff;
            color: #333;
        }

        header {
            background-color: var(--cor-principal);
            padding: 20px;
            text-align: center;
        }

        h2.titulo-boas-vindas {
            color: var(--cor-secundaria);
            font-size: 2.4em;
            text-align: center;
            margin-top: 50px;
            margin-bottom: 30px;
            text-shadow: 2px 2px 4px rgba(146, 118, 118, 0.1);
        }

        @media (max-width: 768px) {
            h2.titulo-boas-vindas {
                font-size: 2.2em;
                margin-top: 30px;
            }
        }

        @media (max-width: 480px) {
            h2.titulo-boas-vindas {
                font-size: 1.8em;
                padding: 0 10px;
            }
        }

        section {
            padding: 40px 20px;
            max-width: 900px;
            margin: auto;
        }

        .projeto {
            background-color: #f3eef1;
            border: 1px solid #eee;
            border-radius: 8px;
            padding: 25px;
            text-align: center;
            margin-bottom: 30px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .projeto:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 15px rgba(48, 47, 47, 0.15);
        }

        .projeto img {
            max-width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 4px;
            margin-bottom: 15px;
        }

        .projeto a {
            display: inline-block;
            background-color: var(--cor-principal);
            color: var(--cor-secundaria);
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
        }

        .projeto a:hover {
            background-color: var(--cor-secundaria);
            color: white;
        }

        form {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        form label {
            font-weight: bold;
            color: var(--cor-secundaria);
        }

        form input[type="text"],
        form input[type="email"],
        form textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #ccc;
            border-radius: 6px;
            font-size: 1em;
        }

        form button[type="submit"] {
            background-color: var(--cor-principal);
            color: var(--cor-secundaria);
            padding: 14px 25px;
            border: none;
            border-radius: 6px;
            font-size: 1.1em;
            cursor: pointer;
            align-self: flex-start;
        }

        form button[type="submit"]:hover {
            background-color: var(--cor-secundaria);
            color: #fff;
        }
    </style>
</head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
<body>

    <header class="cabecalho-destaque">
        <div class="container-cabecalho">
            <h1>Bem-vindo</h1>
            <h2 class="titulo-boas-vindas">Conheça meu portfólio!</h2>
        </div>
    </header>
    ,<style>
        .cabecalho-destaque {
    background: linear-gradient(135deg, #ffe0f0, #f5d2ea);
    padding: 80px 20px 60px;
    text-align: center;
    color: var(--cor-secundaria);
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.05);
    border-bottom: 4px solid #eacbe3;
    position: relative;
    overflow: hidden;
}

.container-cabecalho {
    max-width: 900px;
    margin: 0 auto;
    z-index: 2;
    position: relative;
}

/* Nome principal */
.cabecalho-destaque h1 {
    font-family: 'arial', serif;
    font-size: 3.5em;
    font-weight: 700;
    margin: 0;
    color: #74165d;
    text-shadow: 1px 1px 3px rgba(0,0,0,0.08);
}

.titulo-boas-vindas {
    font-family: 'Arial', serif;
    font-size: 1.6em;
    margin-top: 10px;
    color: #af358a;
    opacity: 0;
    animation: fadeInUp 1.2s ease forwards;
}

@keyframes fadeInUp {
    0% {
        opacity: 0;
        transform: translateY(20px);
    }
    100% {
        opacity: 1;
        transform: translateY(0);
    }
}

.cabecalho-destaque::after {
    content: "";
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 80px;
    background: url('https://www.svgrepo.com/show/30961/wave.svg') no-repeat bottom center;
    background-size: cover;
    opacity: 0.07;
}

.container-cabecalho {
    max-width: 900px;
    margin: auto;
}

.cabecalho-destaque h1 {
    font-size: 3em;
    margin-bottom: 10px;
    font-family: 'Arial', serif;
    letter-spacing: 2px;
    text-shadow: 2px 2px 5px rgba(0,0,0,0.1);
}

.titulo-boas-vindas {
    font-size: 1.8em;
    margin-top: 0;
    font-family: 'Arial', serif;
    color: #74165d;
    opacity: 0;
    animation: fadeInUp 1s ease forwards;
}

@keyframes fadeInUp {
    0% {
        opacity: 0;
        transform: translateY(20px);
    }
    100% {
        opacity: 1;
        transform: translateY(0);
    }
}
    </style>
   <section id="sobre-mim" class="bloco-destaque">
    <h2>👩‍💻 Sobre Mim</h2>
    <p>Oi! Sou a Kelly, estudante de Análise e Desenvolvimento de Sistemas e apaixonada por criar novas experiências digitais. Gosto de transformar ideias em soluções funcionais e visualmente atraentes!</p>
</section>

<section id="formacao" class="bloco-destaque">
    <h2>🎓 Formação e Idiomas</h2>

    <div class="formacao-bloco">
        <h3>📚 Formação Acadêmica</h3>
        <ul>
            <li>
                <strong>Análise e Desenvolvimento de Sistemas</strong> – UNINTER
                <p><em>2025 - 2027</em></p>
                <p>Principais áreas: Lógica de Programação, Análise de Sistemas e Dados.</p>
            </li>
        </ul>
    </div>

    <div class="idiomas-bloco">
        <h3>🌍 Idiomas</h3>
        <ul>
            <li>🇧🇷 Português: Nativo</li>
            <li>🇺🇸 Inglês: Intermediário</li>
        </ul>
    </div>
</section>
,<style>
    .bloco-destaque {
    background-color: #fff8fb;
    border-left: 5px solid var(--cor-secundaria);
    padding: 30px 25px;
    margin: 40px auto;
    max-width: 900px;
    border-radius: 10px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
    transition: transform 0.3s ease;
}

.bloco-destaque:hover {
    transform: translateY(-3px);
}

.bloco-destaque h2 {
    color: var(--cor-secundaria);
    margin-bottom: 20px;
    font-size: 1.8em;
    display: flex;
    align-items: center;
    gap: 10px;
}

.bloco-destaque h3 {
    margin-top: 20px;
    color: #555;
    font-size: 1.3em;
}

.bloco-destaque p {
    line-height: 1.6;
    font-size: 1em;
    color: #444;
}

.bloco-destaque ul {
    list-style: none;
    padding-left: 0;
}

.bloco-destaque ul li {
    margin-bottom: 10px;
    font-size: 1em;
    color: #333;
}

.formacao-bloco, .idiomas-bloco {
    margin-top: 25px;
}
</style>

    <section id="portfolio">
        <h2>Meu Portfólio</h2>
        <div class="projeto">
            <h3>Análise de dados da Premier League</h3>
            <img src="5560491.png" alt="Miniatura Projeto 1">
            <p>Projeto em Python que analisa tendências do futebol.</p>
            <a href="https://link-para-o-projeto.com" target="_blank">Ver Projeto</a>
        </div>
        <div class="projeto">
            <h3>Otimização da receita de varejo de esportes on-line</h3>
            <img src="5681267.png" alt="Miniatura Projeto 2">
            <p>Projeto desenvolvido no Mysql, visando a análise exploratória de dados. </p>
            <a href="https://link-para-o-projeto2.com" target="_blank">Ver Projeto</a>
        </div>
    </section>

    <section id="contato">
        <h2>Vamos nos conectar!</h2>
        <form>
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="mensagem">Mensagem:</label>
            <textarea id="mensagem" name="mensagem" rows="5" required></textarea>

            <button type="submit">Enviar Mensagem</button>
        </form>

        <p>Você também pode me encontrar em:</p>
        <div class="contato-links">
            <div class="contato-item">
                <span>📧</span>
                <a href="mailto:kellylandgraf@outlook.com">Me mande um e-mail</a>
            </div>
            <div class="contato-item">
                <span>💼</span>
                <a href="https://www.linkedin.com/in/seu-perfil" target="_blank">Envie uma solicitação no LinkedIn</a>
            </div>
        </div>
        ,<style>
            .contato-links {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-top: 20px;
            padding-left: 0;
        }
        
        .contato-item {
            display: flex;
            align-items: center;
            background-color: var(--cor-principal);
            border-left: 4px solid var(--cor-secundaria);
            padding: 12px 20px;
            border-radius: 8px;
            transition: background-color 0.3s ease;
        }
        
        .contato-item span {
            font-size: 1.5em;
            margin-right: 12px;
        }
        
        .contato-item a {
            color: var(--cor-secundaria);
            font-weight: bold;
            text-decoration: none;
            transition: color 0.3s ease;
        }
        
        .contato-item:hover {
            background-color: #fce9f5;
        }
        
        .contato-item a:hover {
            color: #74165d;
        }
        </style>
        
