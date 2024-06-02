<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bolões Loterias da Caixa</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #121212;
            color: #FFFFFF;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        header {
            background-color: #1E1E1E;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
            color: #76FF03;
        }
        main {
            flex: 1;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .bolao {
            background-color: #1E1E1E;
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
            width: 100%;
            max-width: 600px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .bolao:hover {
            transform: translateY(-5px);
        }
        .bolao h2 {
            margin-top: 0;
            color: #BB86FC;
        }
        .bolao p {
            margin: 10px 0;
        }
        footer {
            background-color: #1E1E1E;
            text-align: center;
            padding: 20px;
            box-shadow: 0 -4px 6px rgba(0, 0, 0, 0.1);
        }
        footer p {
            margin: 0;
            color: #76FF03;
        }
        @media (max-width: 600px) {
            header h1 {
                font-size: 2em;
            }
            .bolao {
                padding: 15px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Bolões Loterias da Caixa</h1>
    </header>
    <main>
        <section class="bolao">
            <h2>Bolão Mega-Sena</h2>
            <p>Participe do nosso bolão da Mega-Sena e tenha mais chances de ganhar! Sorteio em 15/06/2024. Valor da cota: R$ 10,00.</p>
        </section>
        <section class="bolao">
            <h2>Bolão Quina</h2>
            <p>Junte-se ao nosso bolão da Quina e aumente suas chances! Sorteio em 20/06/2024. Valor da cota: R$ 5,00.</p>
        </section>
        <!-- Adicione mais seções para outros bolões aqui -->
    </main>
    <footer>
        <p>&copy; 2024 Bolões Loterias da Caixa. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
