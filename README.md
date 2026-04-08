<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Figuras de Linguagem - 7º Ano D</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Figuras de Linguagem</h1>
        <p>Seminário de Língua Portuguesa - 7º Ano D</p>
        <a href="seu-arquivo.pdf" class="btn-download" target="_blank">Baixar PDF Completo</a>
    </header>

    <main>
        <section class="intro">
            <h2>O que são?</h2>
            [span_1](start_span)<p>São recursos expressivos que tornam a comunicação mais criativa e emocionante[span_1](end_span). [span_2](start_span)Elas aparecem em músicas, poesias e até no nosso dia a dia[span_2](end_span).</p>
        </section>

        <section class="grid">
            <div class="card">
                <h3>Metonímia</h3>
                [span_3](start_span)<p>Substitui uma palavra por outra com relação direta, como o autor pela obra[span_3](end_span).</p>
                [span_4](start_span)<span>Ex: "Li todo Machado de Assis"[span_4](end_span).</span>
            </div>
            <div class="card">
                <h3>Antítese</h3>
                [span_5](start_span)<p>Aproxima palavras ou ideias de sentidos opostos para criar contraste[span_5](end_span).</p>
                [span_6](start_span)<span>Ex: "Luz e Escuridão"[span_6](end_span).</span>
            </div>
            <div class="card">
                <h3>Hipérbole</h3>
                [span_7](start_span)<p>Um exagero intencional para enfatizar uma ideia ou emoção[span_7](end_span).</p>
                [span_8](start_span)<span>Ex: "Morrendo de calor"[span_8](end_span).</span>
            </div>
            <div class="card">
                <h3>Personificação</h3>
                [span_9](start_span)<p>Atribui características humanas a seres inanimados ou animais[span_9](end_span).</p>
                [span_10](start_span)<span>Ex: "O vento sussurrou segredos"[span_10](end_span).</span>
            </div>
        </section>
    </main>

    <footer>
        [span_11](start_span)<p>Conteúdo baseado no seminário do 7º Ano D[span_11](end_span).</p>
    </footer>
</body>
</html>
body {
    font-family: 'Segoe UI', sans-serif;
    line-height: 1.6;
    margin: 0;
    background-color: #f4f4f9;
    color: #333;
}

header {
    background: linear-gradient(135deg, #2c3e50, #3498db);
    color: white;
    text-align: center;
    padding: 3rem 1rem;
}

.btn-download {
    display: inline-block;
    margin-top: 15px;
    padding: 10px 20px;
    background: #e74c3c;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

main {
    max-width: 1000px;
    margin: 20px auto;
    padding: 20px;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    margin-top: 30px;
}

.card {
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    transition: transform 0.3s;
}

.card:hover {
    transform: translateY(-5px);
}

.card h3 {
    color: #3498db;
    margin-top: 0;
}

footer {
    text-align: center;
    padding: 20px;
    font-size: 0.9rem;
    color: #666;
}
