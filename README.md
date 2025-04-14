# automacaoeeletronica.github.co
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pagina teste</title>
    <style>

        body {
            background-color: chocolate;
        }
        .header {
            /*justify-content: space-between;*/
            position: light;
            padding: 0px; 
            background-color: #050e8f;
        }
        .header.navbar-brand {
            /*display: flex;
            align-items: center;*/
            justify-content: center;
            /*text-align: center;
            padding: 10px;*/
        }
            
        .header1 {
            justify-content: space-between;
            align-items: center;
            text-align: center;
            padding: 10px;
            background-color: #57a571;
            margin-top: 20px;
            margin-bottom: 20px;

        }
        .header1 h1 {
            color: white;
            text-size: 30px
            font-size: 30px;
            text-emphasis-position: center;
        }
        /* Estilos CSS para os cards */
        .card-container {
            display: flex;
            justify-content: space-around;
            padding: 20px;
        }
        .card {
            width: 300px;
            border: 3px solid #ddd;
            border-radius: 5px;
            overflow: hidden;
            /*box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);*/
        }

        .card img {
            width: 100%;
            max-height: auto;
        }

        .card-content {
            padding: 2px;
        }

        .card-content h3 {
            margin-top: center center;
        }
        .card-content {
            background-color: white;
        }
        .EscreverTexto {
            justify-content: space-between;
            text-align: center;
            padding: 20px;
            background-image: url('C:\Users\alema\Documents\TRABALHOS\SERVICOS DE SITE\SITE MENDES AUTOMACAO\img\aperto-de-mão IHM.jpg');
            background-size: cover; /* Para cobrir toda a tela */
            background-repeat: no-repeat; /* Para evitar repetição da imagem */
            background-position: center; /* Para centralizar a imagem */
            background-size: auto; /* Para manter a proporção da imagem */

            /* Outras propriedades de background podem ser adicionadas aqui */
            background-color: #242323;

        }
        .footer{
            background-color: #050e8f; 
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
        .footer p {
            margin: 0;
            color: white;
            font-size: 14px;
        }

    </style>
</head>
<body >
    <div class="header">
        <nav class="navbar bg-body-tertiary">
            <div class="header">
              <a class="navbar-brand" href="#">
                <img src="C:\Users\alema\Documents\TRABALHOS\SERVICOS DE SITE\SITE MENDES AUTOMACAO\img\logo mendes mini 1.jpg" alt="..." width="270" height="150">
              </a>
            </div>
        </nav>
    </div>
    <div class="header1">
        <h1>Bem-vindo ao nosso site!</h1>
        <p>Estamos felizes em tê-lo aqui.</p>
        <p>Explore nossos serviços e entre em contato conosco para mais informações.</p>
        <p>Esta página está em construção</p>
    </div>
    <div class="conteiner-fluid">
        <div class="card-container">

        <div class="card">
            <img src="C:\Users\alema\Documents\TRABALHOS\SERVICOS DE SITE\SITE MENDES AUTOMACAO\img\automlink 1.jpg" alt="...">
            <div class="card-content">
                <h3>Automação</h3>
                <p>Automação Industrial </p>
                <p>Automação Residencial</p>
                <p>Automação Comercial</p>
            </div>
        </div>

        <div class="card">
            <img src="C:\Users\alema\Documents\TRABALHOS\SERVICOS DE SITE\SITE MENDES AUTOMACAO\img\Manutencao placa 1.jpg"  alt="...">
            <div class="card-content">
                <h3>Reparo eletrônico</h3>
                <p>Reparo em placas eletrônicas e circuitos digitais SMD.</p>
            </div>
        </div>

        <div class="card">
            <img src="C:\Users\alema\Documents\TRABALHOS\SERVICOS DE SITE\SITE MENDES AUTOMACAO\img\logo mendes 3.jpg" alt="Imagem 3">
            <div class="card-content">
                <h3>Serviço 3</h3>
                <p>Descrição do Card 3.</p>
            </div>
        </div>
    </div>
</div>
<div class="EscreverTexto" img src="C:\Users\alema\Documents\TRABALHOS\SERVIÇOS DE SITE\SITE MENDES AUTOMACAO\img\aperto-de-mão IHM.jpg" alt="...">
    <p> Escrever aqui texto de conhecimento geral</p>
</div>
<footer>
    <div class="footer" >
        <p >&copy; 2025 Mendes Automação. Todos os direitos reservados.</p>
        <p >E-mail: <E-mail>mendesbreuer21@gmail.com</E-mail></p>
        <p >Whatsapp: (51) 98298.6139</p>
    </div>      
</footer>
</body>
</html>
