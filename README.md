<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chimoio Estudos</title>
    <style>
        body {
            font-family: "Times New Roman", Times, serif;
            background-color: #FFFFFF;
            color: #000000;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #000000;
            color: #FFFFFF;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background-color: #000000;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #0000FF;
            margin: 0 15px;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .content {
            padding: 20px;
        }
        .card {
            background-color: #f4f4f4;
            padding: 20px;
            margin: 20px 0;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            background-color: #000000;
            color: #FFFFFF;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Chimoio Estudos</h1>
        <p>Por Jossefa Samuel Mateus</p>
    </header>

    <nav>
        <a href="#exames">Exames</a>
        <a href="#livros">Livros</a>
        <a href="#contato">Contato</a>
    </nav>

    <div class="container">
        <section id="exames" class="content">
            <h2>Exames</h2>
            <div class="card">
                <h3>Exame de Matemática</h3>
                <a href="link_do_exame_matematica.pdf" download>Baixar</a>
            </div>
            <div class="card">
                <h3>Exame de Português</h3>
                <a href="link_do_exame_portugues.pdf" download>Baixar</a>
            </div>
        </section>

        <section id="livros" class="content">
            <h2>Livros</h2>
            <div class="card">
                <h3>Livro de Física</h3>
                <a href="link_do_livro_fisica.pdf" download>Baixar</a>
            </div>
            <div class="card">
                <h3>Livro de Química</h3>
                <a href="link_do_livro_quimica.pdf" download>Baixar</a>
            </div>
        </section>

        <section id="contato" class="content">
            <h2>Contato</h2>
            <div class="card">
                <p>Chamadas e mensagens: +258861945094 ou +258841150888</p>
                <p>WhatsApp e Telegram: +258861945094</p>
                <p>Facebook e Instagram: Jolayson o el Mazza</p>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Chimoio Estudos. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
