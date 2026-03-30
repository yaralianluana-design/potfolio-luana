<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio - Luana Yaralian</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #0f172a, #1e3a5f);
            color: #fff;
        }

        header {
            text-align: center;
            padding: 60px 20px;
            animation: fadeInDown 1s ease;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        header p {
            color: #cbd5f5;
        }

        section {
            max-width: 900px;
            margin: 40px auto;
            padding: 20px;
        }

        h2 {
            margin-bottom: 15px;
            border-left: 4px solid #38bdf8;
            padding-left: 10px;
        }

        .card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            padding: 20px;
            margin-bottom: 15px;
            border-radius: 10px;
            transition: transform 0.3s, box-shadow 0.3s;
            animation: fadeInUp 1s ease;
        }

        .card:hover {
            transform: translateY(-5px) scale(1.02);
            box-shadow: 0 10px 20px rgba(0,0,0,0.3);
        }

        ul {
            margin-top: 10px;
            padding-left: 20px;
        }

        footer {
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            background: rgba(0,0,0,0.3);
        }

        /* Animações */
        @keyframes fadeInDown {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Responsivo */
        @media (max-width: 600px) {
            header h1 {
                font-size: 1.8rem;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Luana Rodrigues Yaralian</h1>
    <p>Estudante de Engenharia de Software | Analista de Cobrança Júnior</p>
</header>

<section>
    <h2>Sobre mim</h2>
    <div class="card">
        <p>Profissional em início de carreira, com interesse na área de tecnologia e desenvolvimento de software. Atualmente cursando Engenharia de Software e atuando como Analista de Cobrança Júnior, com experiência em análise de dados, comunicação e organização de processos.</p>
    </div>
</section>

<section>
    <h2>Experiência</h2>
    <div class="card">
        <h3>Analista de Cobrança Júnior - Aval</h3>
        <ul>
            <li>Atendimento ao cliente e negociação</li>
            <li>Análise de dados financeiros</li>
            <li>Organização de processos</li>
            <li>Elaboração de relatórios</li>
        </ul>
    </div>
</section>

<section>
    <h2>Projetos</h2>
    <div class="card">
        <h3>ASCOM - Projeto de TCC</h3>
        <p>Projeto com foco em organização de processos, análise de dados e mobilização comunitária.</p>
    </div>

    <div class="card">
        <h3>Desenvolvimento Web</h3>
        <p>Criação de páginas utilizando HTML e CSS com foco em estrutura, estilo e responsividade básica.</p>
    </div>
</section>

<section>
    <h2>Habilidades</h2>
    <div class="card">
        <ul>
            <li>HTML e CSS</li>
            <li>Pacote Office</li>
            <li>Análise de dados</li>
            <li>Comunicação</li>
            <li>Organização</li>
            <li>Trabalho em equipe</li>
        </ul>
    </div>
</section>

<section>
    <h2>Contato</h2>
    <div class="card">
        <p>Email: yaralianluana@gmail.com</p>
        <p>Telefone: (11) 99338-5838</p>
    </div>
</section>

<footer>
    <p>© 2026 - Luana Yaralian</p>
</footer>

</body>
</html>
