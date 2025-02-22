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
        <!-- Seção com a imagem e o texto -->
        <div class="mapa-container">
            <h3>Fênix Turismo</h3> <!-- Texto acima da imagem -->
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
            color:white; /* Cor dos parágrafos definida como preto */
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
       /* Alinha o texto ao centro */
.mapa-container h3 {
    text-align: center;
}

/* Adiciona borda preta em volta do conteúdo da seção mapa-container */
.mapa-container {
    border: 1px solid #000; /* Cor da borda definida como preto */
    padding: 10px; /* Espaçamento interno para melhor visualização da borda */
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
        
        <!-- Imagens no Cabeçalho -->
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
            <img src="Imagens/Õnibus.jpg" alt="Mapa" class="imagem-main">
            <div class="texto-main">
                <h2>Fênix Turismo: 15 Anos de Excelência no Setor de Viagens</h2>
                <h3>A Fênix Turismo completa 15 anos de existência, marcando uma jornada incrível no setor de viagens. Fundada em [ano], a empresa sempre se destacou pela paixão em oferecer experiências inesquecíveis aos seus clientes. Com uma equipe dedicada e especializada, a Fênix Turismo tem sido sinônimo de confiabilidade e satisfação para milhares de viajantes ao longo dos anos.</h3>
                
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed sit amet nulla auctor, vestibulum magna sed, convallis ex.</p>
            </div>
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
            color:white; /* Cor dos parágrafos definida como preto */
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
    justify-content:center;
}



.imagem-main {
    width: 300px; 
    height: auto;
    margin-right: 20px;
}

.texto-main {
    flex-grow: 1; /* Ocupa todo espaço disponível */
}
.texto-main h2 {
    text-transform: uppercase; /* Transforma o texto em caixa alta */
    margin-bottom: -10px; /* Ajusta a margem inferior para que fique mais perto do h3 */
}

.texto-main h3 {
    text-transform: lowercase; /* Transforma o texto em caixa baixa */
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
    <title>Serviços - Meu Site</title>
    <link rel="stylesheet" href="layout3.css">
</head>
<body>
    <header>
        <h1><a href="index.html"><img src="imagens/layout3.PNG" alt=""></a></h1>
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
        <h2></h2>
        <p></p>

        <!-- Lista de Serviços -->
        <ul class="servicos">
            <li>Consultoria especializada</li>
            <li>Desenvolvimento web</li>
            <li>Marketing digital</li>
            <li>Suporte técnico</li>
        </ul>

    </main>

    <footer>
        <p>&copy; 2025 Meu Site. Todos os direitos reservados.</p>
    </footer>

    <style>
           /* Estilos Globais */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
}

h1 {
    font-size: 2em;
    margin-bottom: 0.5em;
}

p {
    margin-bottom: 1em;
}

a {
    color: #007BFF;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

/* Estilos do Header */
header {
    background-image: url('imagens/cabeçalho.jpg'); /* Substitua pelo nome da sua imagem */
    background-size: cover; /* Faz a imagem cobrir todo o cabeçalho */
    background-position: center; /* Centraliza a imagem */
    color:black; /* Cor do texto */
    padding: 1em 0;
    text-align: center; /* Centraliza o texto no cabeçalho */
}

/* Navegação */
nav ul {
    list-style-type: none; /* Remove marcadores da lista */
    padding: 0; /* Remove padding padrão */
}

nav ul li {
    display: inline; /* Alinha os itens em linha */
    margin: 0 15px; /* Adiciona espaçamento entre os itens de navegação */
}

nav ul li a {
    color: #fff; /* Cor dos links no cabeçalho */
}

/* Estilos do Main */
main {
    max-width: 800px;
    margin: 2em auto;
    padding: 0 20px;
}

/* Estilos do Footer */
footer {
    text-align: center;
    padding: 1em 0;
    background-color: #333;
    color: #fff;
}

/* Estilos de Imagens */
img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 0 auto;
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
    <title>Contato - Meu Site</title>
    <link rel="stylesheet" href="layout4.css">
</head>
<body>
    <header>
        <h1><a href="index.html"><img src="imagens/layout4.PNG" alt=""></a></h1>
        <nav>
            <ul>
                <li><a href="index.html">Início</a></li>
                <li><a href="sobre.html">Sobre</a></li>
                <li><a href="servicos.html">Serviços</a></li>
                <li><a href="contato.html">Contato</a></li> 
            </ul> 
        </nav> 
     </header>

     <!-- Formulário Simples -->
     <!-- Corpo -->
<main>  
<form action="#">
<label for="">

    <style>
           /* Estilos Globais */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
}

h1 {
    font-size: 2em;
    margin-bottom: 0.5em;
}

p {
    margin-bottom: 1em;
}

a {
    color: #007BFF;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

/* Estilos do Header */
header {
    background-image: url('imagens/cabeçalho.jpg'); /* Substitua pelo nome da sua imagem */
    background-size: cover; /* Faz a imagem cobrir todo o cabeçalho */
    background-position: center; /* Centraliza a imagem */
    color: black; /* Cor do texto */
    padding: 1em 0;
    text-align: center; /* Centraliza o texto no cabeçalho */
}

/* Navegação */
nav ul {
    list-style-type: none; /* Remove marcadores da lista */
    padding: 0; /* Remove padding padrão */
}

nav ul li {
    display: inline; /* Alinha os itens em linha */
    margin: 0 15px; /* Adiciona espaçamento entre os itens de navegação */
}

nav ul li a {
    color: #fff; /* Cor dos links no cabeçalho */
}

/* Estilos do Main */
main {
    max-width: 800px;
    margin: 2em auto;
    padding: 0 20px;
}

/* Estilos do Footer */
footer {
    text-align: center;
    padding: 1em 0;
    background-color: #333;
    color: #fff;
}

/* Estilos de Imagens */
img {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 0 auto;
}

        </style>







    
