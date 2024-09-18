# pagina-web-com-as-img
![WhatsApp Image 2024-09-18 at 09 38 58 (1)](https://github.com/user-attachments/assets/16f062ef-bfd6-4498-8632-817724a643be)
![WhatsApp Image 2024-09-18 at 09 38 58](https://github.com/user-attachments/assets/2f390635-b836-4cd1-aedf-3a56b68a03e4)
![WhatsApp Image 2024-09-17 at 15 19 39](https://github.com/user-attachments/assets/fd161748-2c1f-43a7-89a9-2878e7b26ed2)
:root {
    --branco-principal: #FFFFFF;
    --cinza-secundario: #C0C0C0;
    --botao-azul: #167BF7;
    --cor-de-fundo: #00030C;
    --fonte-principal: 'Inter';
    --botao-azul-efeito: #3c92fa;
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

.secundario__botao {
    display: inline-block;
    margin-top: 1em;
}

.container__descricao {
    padding: 2em;
}

.dispositivos__lista {
    display: flex;
    justify-content: center;
    list-style-type: none;
    margin: 5em 0;
}

.dispositivos {
    text-align: center;
}

.dispositivos__titulo {
    font-size: 48px;
    color: var(--branco-principal);
}

.lista__item {
    font-size: 32px;
    color: var(--branco-principal);
}

.rodape {
    text-align: center;
    margin: 5em 3em;
}

.rodape__lista {
    display: flex;
    justify-content: center;
    list-style-type: none;
    margin-top: 1em;
}

.lista__link a{
    text-decoration: none;
    color: var(--branco-principal);
    margin-left: 1em;
}

.rodape__texto {
    margin: 1em 0;
    color: var(--cinza-secundario);
    font-size: 14px;
}

.lista__link a:hover {
    color: var(--botao-azul);
}

.lista__link a:active {
    color: purple;
}

.container__botao:hover {
    background-color: var(--botao-azul-efeito);
    color: var(--cor-de-fundo);
}
essa pagina mostra os personagem que sao muito fortes e tops nas animaçoes 
Com o Combo+, você pode aproveitar a Alura+ e o Alura Língua por um preço único.
O combo+ é a junção do alura+ e o alura língua Assine por 12x de R$ 120,00* Assinar somente o Alura+
*O preço pode variar caso a assinatura seja feita em outros planos.

<section class="container secundario">
    <img src="img/Plataformas.png" alt="Um monitor e um celular com a alura plus aberta" class="secundario__imagem">
    <div class="container__descricao">
        <h2 class="descricao__titulo">Assista do seu jeito</h2>
        <p class="descricao__texto">Aproveite a tela grande da TV ou assista no tablet, laptop, celular e outros
            aparelhos. Nossa seleção de cursos não para de crescer.</p>
    </div>
</section>

<section class="container secundario">
    <div class="container__descricao">
        <p class="descricao__texto">
            Só o Combo+ oferece Alura+ e Alura Língua juntos para você ter acesso a cursos de diversas áreas da
            tecnologia e aprender inglês ou espanhol, onde e como quiser.
        </p>
        <a href="www.alura.com.br" class="container_botao secundario_botao" container>Assine o Combo+</a>
    </div>
    <img src="img/Telas.png" alt="Tela do alura+ e alura língua" class="secundario__imagem">
</section>

<section class="container secundario">
    <img src="img/Notebook.png" alt="Notebook com a página do curso HTML5 e CSS3 da Alura aberta"
        class="secundario__imagem">
    <div class="container__descricao">
        <h2 class="descricao__titulo">Baixe seus cursos</h2>
        <p class="descricao__texto">Baixe e assista quando e onde quiser. Assim, seus favoritos estão sempre com
            você, até mesmo sem internet.</p>
    </div>
</section>

<section class="dispositivos">
    <h2 class="dispositivos__titulo">Disponível nos seus dispositivos favoritos</h2>
    <ul class="dispositivos__lista">
        <li>
            <img src="img/tv.png" alt="Ícone de televisão">
            <h3 class="lista__item">TV</h3>
        </li>
        <li>
            <img src="img/computador.png" alt="Ícone de computador">
            <h3 class="lista__item">Computador</h3>
        </li>
        <li>
            <img src="img/celular.png" alt="Ícone de celular">
            <h3 class="lista__item">Celular</h3>
        </li>
    </ul>
</section>

<footer class="rodape">
    <img src="img/Logo.png" alt="Alura+" class="rodape__logo">
    <ul class="rodape__lista">
        <li class="lista__link">
            <a href="#">Idioma</a>
        </li>
        <li class="lista__link">
            <a href="#">Dispositivos compatíveis</a>
        </li>
        <li class="lista__link">
            <a href="#">Contrato de assinatura</a>
        </li>
        <li class="lista__link">
            <a href="#">Politica de privacidade</a>
        </li>
        <li class="lista__link">
            <a href="#">Proteção de dados no Brasil</a>
        </li>
        <li class="lista__link">
            <a href="#">Anuncios personalizados</a>
        </li>
        <li class="lista__link">
            <a href="#">Ajuda</a>
        </li>
    </ul>
    <p class="rodape__texto">® 2021 Alura, Alura+ e Alura Língua. Todos os direitos reservados. Serviço de
        assinatura paga. Conteúdo sujeito a disponibilidade.</p>
    <p class="rodape__texto">Alura+ é um serviço pago, baseado em assinatura e sujeito a termos e condições. O
        serviço Alura+ é comercializado por Aovs Sistemas de Informática S.A., Rua Vergueiro, 3185 - Liberdade, São
        Paulo - SP, 04101-300, Brasil e CNPJ 05.555.382/0001-33</p>
</footer>
