<!DOCTYPE html>
<html>
<head>
    <title>ATELIÊ</title>
    <style>
        /* Estilos de formatação básica para a página */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #a8e9f1;
            color: #070606;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #af7676;
            text-align: right;clear
            padding: 5px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin-right: 10px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .tabs {
            background-color: #faf9f9;
            display: flex;
            justify-content: space-around;
            padding: 10px;
        }
        .tab {
            padding: 5px 10px;
            border: 1px solid #0e0303;
            border-radius: 5px;
        }
        .featured-products {
            text-align: center;
            margin-top: 20px;
        }
        .product {
            display: inline-block;
            margin: 0 20px;
            text-align: center;
        }
        .product img {
            max-width: 200px;
            max-height: 200px;
        }
    </style>
</head>
<body>
    <header>
        <h1>ATELIÊ</h1>
    </header>
    <nav>
        <a href="conta.html" target="_blank"><strong>Minha Conta</strong></a>/
        <a href="entrar.html" target="_blank"> <strong>Entrar</strong></a> /
        <a href="cadastro.html" target="_blank"><strong>Cadastrar</strong></a>


    </nav>
    <div class="tabs">
        <div class="tab">Presente</div>
        <div class="tab">Organizadores</div>
        <div class="tab">Agenda</div>
        <div class="tab">Kit Festas</div>
        <div class="tab">Decoração</div>
    </div>
    <div class="featured-products">
        <h2>Produtos Mais Vendidos</h2>
        <div class="product">
            <img src="data:image/jpeg;base64,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" alt="Produto 1">
            <p>Nome do Produto 1</p>
            <p>R$ 50,00</p>
            <p>Descrição do Produto 1</p>
        </div>
        <div class="product">
            <img src="data:image/jpeg;base64,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" alt="Produto 2">
            <p>Nome do Produto 2</p>
            <p>R$ 40,00</p>
            <p>Descrição do Produto 2</p>
        </div>
        <div class="product">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTdFKkJ7OSR6J9ATvJT1ZDEJz4vCdEXhRg80w&usqp=CAU" alt="Produto 3">
            <p>Nome do Produto 3</p>
            <p>R$ 60,00</p>
            <p>Descrição do Produto 3</p>
        </div>
    </div>
    <div class="faq">
        <h2>PERGUNTAS MAIS FREQUENTES</h2>
        <div class="faq-buttons">
            <button class="faq-button">Qual o prazo de projetos?</button>
            <button class="faq-button">Vocês fazem visita?</button>
            <button class="faq-button">Onde fica o escritório?</button>
        </div>
        <div class="faq-buttons">
            <button class="faq-button">Quais áreas de projetos que vocês atuam?</button>
            <button class="faq-button">Qual a área de cobertura?</button>
            <button class="faq-button">Quais as formas de pagamento?</button>
        </div>
    <!-- Conteúdo da página aqui -->
</body>
</html>
