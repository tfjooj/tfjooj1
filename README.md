<!DOCTYPE html>
<html>

<head>
    <title>Alura Plus</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="styles.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
</head>

<body>
    <section class="principal container">
        <div>
            <h1 class="container__titulo">Com o Combo+, você pode aproveitar a Alura+ e o Alura Língua por um preço
                único.</h1>
            <img src="img/Combo.png" alt="O combo+ é a junção do alura+ e o alura língua" class="container__imagem">
            <a href="www.alura.com.br" class="container__botao">Assine por 12x de R$ 120,00*</a>
            <a href="www.alura.com.br" class="container__botao botao_secundario">Assinar somente o Alura+</a>
            <p class="container__aviso">*O preço pode variar caso a assinatura seja feita em outros planos.</p>
        </div>
    </section>

    <section class="container secundario">
    <img src="img/Plataformas.png" alt="Um monitor e um celular com a alura plus aberta" class="secundario__imagem">
    <div class="container__descricao">
        <h2 class="descricao__titulo">Assista do seu jeito</h2>
        <p class="descricao__texto">Aproveita a tela grande da TV ou assista no Tablet, Laptop, Celular e outros aparelhos. Nossa seleção de cursos não para de crescer.</p>
     </div> </section>
</body>

</html>








:root {
    --branco-principal: #FFFFFF;
    --cinza-secundario: #C0C0C0;
    --botao-azul: #167BF7;
    --cor-de-fundo: #00030C;
    --fonte-principal: 'Inter';
}

body {
    background-color: var(--cor-de-fundo);
    color: var(--branco-principal);
    font-family: var(--fonte-principal);
    font-size: 16px;
    font-weight: 400;
}

* {
    margin: 0;
    padding: 0;
}

.principal {
    background-image: url("img/Background.png");
    background-repeat: no-repeat;
    background-size: contain;
    align-items: center;
    text-align: center;
}

.container {
    height: 100vh;
    display: grid;
    grid-template-columns: 50% 50%;
}

.container__botao {
    background-color: var(--botao-azul);
    border-radius: 5px;
    padding: 1em;
    color: var(--branco-principal);
    display: block;
    text-decoration: none;
    margin-bottom: 1em;
}

.botao_secundario {
    background-color: transparent;
    border: 2px solid var(--branco-principal)
}

.container__aviso {
    font-size: 12px;
    color: var(--cinza-secundario);
}

.container__titulo {
    font-size: 28px;
    font-weight: 700;
}

.container__imagem {
    margin: 1em 0 2em 0;
}

.container__caixa {
    margin: 0 6em;
}

.secundario__imagem {
    width: 80%;
}

.secundario {
    align-items: center;
    margin: 0 10em;
}

.descricao__titulo {
    font-weight: 700;
    font-size: 48px;
    color: var(--branco-principal);
    margin-bottom: 0.1em;
}

.descricao__texto {
    color: var(--cinza-secundario);
}
