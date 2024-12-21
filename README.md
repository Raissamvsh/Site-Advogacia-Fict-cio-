<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moven Advogados Associados</title>
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #fff;
            line-height: 1.6;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }

        header {
            background: #1f1f1f;
            padding: 20px 0;
            border-bottom: 2px solid #444;
        }

        header h1 {
            color: #fff;
            font-size: 2rem;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        nav a {
            text-decoration: none;
            color: #bbb;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #fff;
        }

        #hero {
            background: linear-gradient(to right, #0a0a0a, #1f1f1f);
            text-align: center;
            padding: 100px 20px;
        }

        .hero-text h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        .hero-text .btn {
            display: inline-block;
            padding: 10px 20px;
            background: #e63946;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
        }

        .hero-text .btn:hover {
            background: #d62839;
        }

        section {
            padding: 50px 0;
        }

        h2 {
            text-align: center;
            margin-bottom: 20px;
            color: #e63946;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .service-card {
            background: #1f1f1f;
            padding: 20px;
            border-radius: 5px;
            text-align: center;
            transition: transform 0.3s;
        }

        .service-card:hover {
            transform: scale(1.05);
        }

        form input, form textarea, form button {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: none;
            border-radius: 5px;
        }

        form input, form textarea {
            background: #1f1f1f;
            color: #fff;
        }

        form button {
            background: #e63946;
            color: #fff;
            cursor: pointer;
            transition: background 0.3s;
        }

        form button:hover {
            background: #d62839;
        }

        footer {
            text-align: center;
            padding: 20px 0;
            background: #1f1f1f;
            border-top: 2px solid #444;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Moven Advogados Associados</h1>
            <nav>
                <ul>
                    <li><a href="#sobre">Sobre Nós</a></li>
                    <li><a href="#servicos">Serviços</a></li>
                    <li><a href="#contato">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section id="hero">
            <div class="hero-text">
                <h2>Soluções Jurídicas Personalizadas</h2>
                <p>Defendendo seus direitos com excelência e dedicação.</p>
                <a href="#contato" class="btn">Fale Conosco</a>
            </div>
        </section>

        <section id="sobre">
            <div class="container">
                <h2>Sobre Nós</h2>
                <p>A Moven Advogados Associados é um escritório comprometido com a justiça e a ética. Nossa equipe de especialistas oferece atendimento personalizado para garantir as melhores soluções jurídicas.</p>
            </div>
        </section>

        <section id="servicos">
            <div class="container">
                <h2>Serviços</h2>
                <div class="services-grid">
                    <div class="service-card">
                        <h3>Direito Trabalhista</h3>
                        <p>Protegemos seus direitos no ambiente de trabalho.</p>
                    </div>
                    <div class="service-card">
                        <h3>Direito Civil</h3>
                        <p>Atuamos em questões de contratos, bens e propriedades.</p>
                    </div>
                    <div class="service-card">
                        <h3>Direito Empresarial</h3>
                        <p>Consultoria para empresas e negociações corporativas.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="contato">
            <div class="container">
                <h2>Contato</h2>
                <p>Entre em contato pelo telefone <strong>(11) 98765-4321</strong> ou envie-nos uma mensagem.</p>
                <form id="contact-form">
                    <input type="text" id="name" placeholder="Seu Nome" required>
                    <input type="email" id="email" placeholder="Seu Email" required>
                    <textarea id="message" placeholder="Sua Mensagem" required></textarea>
                    <button type="submit" class="btn">Enviar</button>
                </form>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2024 Moven Advogados Associados. Todos os direitos reservados.</p>
        </div>
    </footer>

    <script>
        document.getElementById('contact-form').addEventListener('submit', function (e) {
            e.preventDefault();
            const name = document.getElementById('name').value.trim();
            const email = document.getElementById('email').value.trim();
            const message = document.getElementById('message').value.trim();

            if (name && email && message) {
                alert(`Obrigado pela mensagem, ${name}! Entraremos em contato em breve.`);
                this.reset();
            } else {
                alert('Por favor, preencha todos os campos.');
            }
        });
    </script>
</body>
</html>


                        <h3>Direito Internacional Cidadania e Imigração </h3>
                        <p>Consultoria especializada em cidadania e imigração.</p>
