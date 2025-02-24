# interface-de-desenvolvimento





primeira pagina 





<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página</title>
    <link rel="stylesheet" href="layout1.css">
</head>
<body>
    <header>
        
        <div class="imagens-cabecalho">
            <img src="Imagens/campo.jfif" alt="Imagem do campo" width="100">
            <img src="Imagens/litoral.webp" alt="Imagem do litoral de uma cidade" width="100">
            <img src="Imagens/praia.jfif" alt="Imagem de uma praia" width="100">
            <img src="Imagens/montanha.jpg" alt="Imagem de uma montanha" width="100">
        </div>

        <nav>
            <ul>
                <li><a href="index.html">Início</a></li>
                <li><a href="sobre.html">Sobre</a></li>
                <li><a href="servicos.html">Serviços</a></li>
                <li><a href="contato.html">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <div class="mapa-container">
            <h3>Fênix Turismo</h3>
            <img src="imagens/mapa.png" alt="Mapa" class="mapa-imagem">
        </div>
    </main>

    <footer>
        <div class="footer-content">
            <p>&copy; 2025 Fênix Turismo. Sempre pensando em você.</p>
            <p>Endereço: Avenida Senador Salgado Filho, 1092 - Natal, Rn</p>
            <p>Telefone: (00) 1234-5678</p>
            <p>Email: contato@fenixturismo.com.br</p>
            <div class="social-media">
                <a href="#" target="_blank">Facebook</a> |
                <a href="#" target="_blank">Instagram</a> |
                <a href="#" target="_blank">Twitter</a>
            </div>
        </div>
    </footer>

    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #000; 
            line-height: 1.6;
            display: flex;
            flex-direction: column;
            min-height: 100vh; 
        }

        h1 {
            font-size: 2em;
            margin-bottom: 0.5em;
            color: #000; 
        }

        h2, h3 {
            color: #000; 
        }

        p {
            margin-bottom: 1em;
            color:white;
        }

        a {
            color: #007BFF;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        header {
            background-color: #007BFF;
            padding: 1em 0;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline-block;
            margin-right: 15px;
        }

        nav ul li a {
            color: #fff;
            font-size: 16px;
        }

        nav ul li a:hover {
            color: #e0e0e0; 
        }

        
        .imagens-cabecalho {
            display: flex; 
            justify-content: center; 
            margin-top: 10px; 
        }

        .imagens-cabecalho img {
            width: 100px; 
            height: auto; 
            margin: 0 10px; 
            border-radius: 5px; 
        }

        main {
            max-width: 800px;
            margin: 2em auto;
            padding: 0 20px;
            flex-grow: 1; 
        }

        footer {
            text-align: center;
            padding: 1em 0;
            background-color: #333;
            color: white; 
        }

        .social-media {
           margin-top: 10px; 
           font-size: 14px; 
           color:white;

       }
.mapa-container h3 {
    text-align: center;
}

.mapa-container {
    border: 1px solid #000;
    padding: 10px;
}

    </style>
</body>
</html>




    segunda pagina




<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página</title>
    <link rel="stylesheet" href="layout1.css">
</head>
<body>
    <header>
        
        <div class="imagens-cabecalho">
            <img src="imagens/campo.jfif" alt="Descrição da Imagem 1" width="100">
            <img src="imagens/litoral.webp" alt="Descrição da Imagem 2" width="100">
            <img src="imagens/praia.jfif" alt="Descrição da Imagem 3" width="100">
            <img src="imagens/montanha.jpg" alt="Descrição da Imagem 4" width="100">
        </div>

        <nav>
            <ul>
                <li><a href="index.html">Início</a></li>
                <li><a href="sobre.html">Sobre</a></li>
                <li><a href="servicos.html">Serviços</a></li>
                <li><a href="contato.html">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <div class="conteudo-main">
            <div class="texto-main">
                <h2>Fênix Turismo: 15 Anos de Excelência no Setor de Viagens</h2>
                <h3>A Fênix Turismo completa 15 anos de existência, marcando uma jornada incrível no setor de viagens. Fundada em [ano], a empresa sempre se destacou pela paixão em oferecer experiências inesquecíveis aos seus clientes. Com uma equipe dedicada e especializada, a Fênix Turismo tem sido sinônimo de confiabilidade e satisfação para milhares de viajantes ao longo dos anos.</h3>
                
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed sit amet nulla auctor, vestibulum magna sed, convallis ex.</p>
            </div>
            <img src="Imagens/Õnibus.jpg" alt="Mapa" class="imagem-main">
        </div>
    </main>
    

    <footer>
        <div class="footer-content">
            <p>&copy; 2025 Fênix Turismo. Sempre pensando em você.</p>
            <p>Endereço: Avenida Senador Salgado Filho, 1092 - Natal, Rn</p>
            <p>Telefone: (00) 1234-5678</p>
            <p>Email: contato@fenixturismo.com.br</p>
            <div class="social-media">
                <a href="#" target="_blank">Facebook</a> |
                <a href="#" target="_blank">Instagram</a> |
                <a href="#" target="_blank">Twitter</a>
            </div>
        </div>
    </footer>

    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #000;
            line-height: 1.6;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        h1 {
            font-size: 2em;
            margin-bottom: 0.5em;
            color: #000;
        }

        h2, h3 {
            color: #000;
        }

        p {
            margin-bottom: 1em;
            color: white;
        }

        a {
            color: #007BFF;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        header {
            background-color: #007BFF;
            padding: 1em 0;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline-block;
            margin-right: 15px;
        }

        nav ul li a {
            color: #fff;
            font-size: 16px;
        }

        nav ul li a:hover {
            color: #e0e0e0; 
        }

        
        .imagens-cabecalho {
            display: flex; 
            justify-content: center; 
            margin-top: 10px; 
        }

        .imagens-cabecalho img {
            width: 100px; 
            height: auto; 
            margin: 0 10px; 
            border-radius: 5px; 
        }

        main {
            max-width: 800px;
            margin: 2em auto;
            padding: 0 20px;
            flex-grow: 1; 
        }

        footer {
            text-align: center;
            padding: 1em 0;
            background-color: #333;
            color: white; 
        }

        .social-media {
           margin-top: 10px; 
           font-size: 14px; 
           color:white;
       }
       .conteudo-main{
    display: flex;
    align-items: center; 
    justify-content: space-between;
}

.texto-main {
    flex-grow: 1;
    width: 60%;
}

.imagem-main {
    width: 300px; 
    height: auto;
    margin-left: 20px;
}

.texto-main h2 {
    text-transform: uppercase;
    margin-bottom: -10px;
}

.texto-main h3 {
    text-transform: lowercase;
}
    </style>
</body>
</html>





terceira pagina


<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página</title>
</head>
<body>
    <header>
        
        <div class="imagens-cabecalho">
            <img src="Imagens/campo.jfif" alt="Imagem do campo" width="100">
            <img src="Imagens/litoral.webp" alt="Imagem do litoral de uma cidade" width="100">
            <img src="Imagens/praia.jfif" alt="Imagem de uma praia" width="100">
            <img src="Imagens/montanha.jpg" alt="Imagem de uma montanha" width="100">
        </div>

        <nav>
            <ul>
                <li><a href="index.html">Início</a></li>
                <li><a href="sobre.html">Sobre</a></li>
                <li><a href="servicos.html">Serviços</a></li>
                <li><a href="contato.html">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h1>Escolha o seu motorista</h1>
        <a href="#mulher-negra">Aline</a> | 
        <a href="#menina">Letícia</a> | 
        <a href="#tio">Paulo</a>

        <div id="tio" class="imagem-e-texto">
            <h3>Paulo</h3>
            <img src="imagens/tio.png" alt="Imagem do tio" width="150">
            <p>Motorista há 20 anos da empresa</p>
            <button class="botao-selecionar">Confirmar</button>
            <p>Confirmado</p>
        </div>

        <div id="mulher-negra" class="imagem-e-texto">
            <h3>Aline</h3>
            <img src="imagens/mulher-negra.png" alt="Imagem da mulher negra" width="150">
            <p>Motorista há 9 anos da empresa</p>
            <button class="botao-selecionar">Confirmar</button>
            <p>Confirmado</p>
        </div>

        <div id="menina" class="imagem-e-texto">
            <h3>Letícia</h3>
            <img src="imagens/menina.png" alt="Imagem da menina" width="150">
            <p>Motorista recém contratada da empresa</p>
            <button class="botao-selecionar">Confirmar</button>
            <p>Confirmado</p>
        </div>
    </main>

    <footer>
        <div class="footer-content">
            <p>&copy; 2025 Fênix Turismo. Sempre pensando em você.</p>
            <p>Endereço: Avenida Senador Salgado Filho, 1092 - Natal, Rn</p>
            <p>Telefone: (00) 1234-5678</p>
            <p>Email: contato@fenixturismo.com.br</p>
            <div class="social-media">
                <a href="#" target="_blank">Facebook</a> |
                <a href="#" target="_blank">Instagram</a> |
                <a href="#" target="_blank">Twitter</a>
            </div>
        </div>
    </footer>

    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #000; 
            line-height: 1.6;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        h1 {
            font-size: 2em;
            margin-bottom: 0.5em;
            color: #000;
            text-align: center;
        }

        h2, h3 {
            color: #000;
            text-align: center;
        }

        p {
            margin-bottom: 1em;
            color: black;
            text-align: center;
        }

        a {
            color: #007BFF;
            text-decoration: none;
            margin: 10px;
            cursor: pointer;
        }

        a:hover {
            text-decoration: underline;
        }

        header {
            background-color: #007BFF;
            padding: 1em 0;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline-block;
            margin-right: 15px;
        }

        nav ul li a {
            color: #fff;
            font-size: 16px;
        }

        nav ul li a:hover {
            color: #e0e0e0; 
        }

        
        .imagens-cabecalho {
            display: flex; 
            justify-content: center; 
            margin-top: 10px; 
        }

        .imagens-cabecalho img {
            width: 100px; 
            height: auto; 
            margin: 0 10px; 
            border-radius: 5px; 
        }

        main {
            max-width: 800px;
            margin: 2em auto;
            padding: 0 20px;
            flex-grow: 1; 
            text-align: center;
        }

        footer {
            text-align: center;
            padding: 1em 0;
            background-color: #333;
            color: white; 
        }

        .social-media {
           margin-top: 10px; 
           font-size: 14px; 
           color:white;

       }
       .imagem-e-texto {
           text-align: center;
           margin: 20px;
       }

       .imagem-e-texto:not(:target) {
           display: none;
       }


       .botao-selecionar {
           background-color: #34C759;
           color: white;
           padding: 10px 20px;
           border: none;
           border-radius: 5px;
           cursor: pointer;
           margin-top: 10px;
       }

       .imagem-e-texto p:last-child {
           display: none;
       }

       .botao-selecionar:focus + p {
           display: block;
       }
       footer p{
        color: white;
       }
        
       
    </style>
</body>
</html>





quarta pagina

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página</title>
</head>
<body>
    <header>
        
        <!-- Imagens no Cabeçalho -->
        <div class="imagens-cabecalho">
            <img src="Imagens/campo.jfif" alt="Imagem do campo" width="100">
            <img src="Imagens/litoral.webp" alt="Imagem do litoral de uma cidade" width="100">
            <img src="Imagens/praia.jfif" alt="Imagem de uma praia" width="100">
            <img src="Imagens/montanha.jpg" alt="Imagem de uma montanha" width="100">
        </div>

        <nav>
            <ul>
                <li><a href="index.html">Início</a></li>
                <li><a href="sobre.html">Sobre</a></li>
                <li><a href="servicos.html">Serviços</a></li>
                <li><a href="contato.html">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <div class="imagens-container">
            <img src="imagens/suporte-ao-cliente.png" alt="Suporte ao Cliente" class="imagem-destaque">
            <img src="imagens/reclamar.png" alt="Reclamar" class="imagem-destaque">
        </div>
        <p>Texto abaixo das imagens.</p>
    </main>

    <footer>
        <div class="footer-content">
            <p>&copy; 2025 Fênix Turismo. Sempre pensando em você.</p>
            <p>Endereço: Avenida Senador Salgado Filho, 1092 - Natal, Rn</p>
            <p>Telefone: (00) 1234-5678</p>
            <p>Email: contato@fenixturismo.com.br</p>
            <div class="social-media">
                <a href="#" target="_blank">Facebook</a> |
                <a href="#" target="_blank">Instagram</a> |
                <a href="#" target="_blank">Twitter</a>
            </div>
        </div>
    </footer>

    <style>
        /* Estilos Globais */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #000; /* Cor do texto global definida como preto */
            line-height: 1.6;
            display: flex;
            flex-direction: column;
            min-height: 100vh; /* Garante que o body tenha pelo menos a altura da tela */
        }

        h1 {
            font-size: 2em;
            margin-bottom: 0.5em;
            color: #000; /* Cor do h1 definida como preto */
        }

        h2, h3 {
            color: #000; /* Cor dos títulos definida como preto */
        }

        p {
            margin-bottom: 1em;
            color: black; /* Cor dos parágrafos definida como preto */
            text-align: center; /* Centraliza os parágrafos */
        }

        a {
            color: #007BFF; /* Cor dos links padrão */
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Estilos do Header */
        header {
            background-color: #007BFF; /* Define a cor de fundo azul para o cabeçalho */
            padding: 1em 0;
            text-align: center; /* Centraliza o texto no cabeçalho */
        }

        /* Navegação */
        nav ul {
            list-style-type: none; /* Remove marcadores da lista */
            padding: 0; /* Remove padding padrão */
        }

        nav ul li {
            display: inline-block; /* Alinha os itens em linha (horizontalmente) */
            margin-right: 15px; /* Espaçamento entre os itens de navegação */
        }

        nav ul li a {
            color: #fff; /* Cor dos links no cabeçalho definida como branco para contraste com o fundo azul */
            font-size: 16px;
        }

        nav ul li a:hover {
            color: #e0e0e0; 
        }

        
        .imagens-cabecalho {
            display: flex; 
            justify-content: center; 
            margin-top: 10px; 
        }

        .imagens-cabecalho img {
            width: 100px; 
            height: auto; 
            margin: 0 10px; 
            border-radius: 5px; 
        }

        main {
            max-width: 800px;
            margin: 2em auto;
            padding: 0 20px;
            flex-grow: 1; 
            text-align: center; /* Centraliza todo o conteúdo do main */
        }

        footer {
            text-align: center;
            padding: 1em 0;
            background-color: #333;
            color: white; 
        }

        .social-media {
           margin-top: 10px; 
           font-size: 14px; 
           color:white;

       }
       /* Estilos para a seção de imagens */
       .imagens-container {
           display: flex;
           justify-content: space-around; /* Espaçamento entre as imagens */
           margin-bottom: 20px; /* Espaçamento entre as imagens e o texto */
       }

       .imagem-destaque {
           width: 150px; /* Ajusta o tamanho da imagem */
           height: auto; /* Mantém a proporção da imagem */
           margin: 0 20px; /* Espaçamento entre as imagens */
       }
    </style>
</body>
</html>
