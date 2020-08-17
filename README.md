# http://rafaela-ahlert.github.io
Vinculação com APIs


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <meta name="author" content="Rafaela Ahlert">
    <meta name="description" content="Busca Livros">

    <title>Busca Livros</title>
    
    <link rel="stylesheet" href="assets/css/style.css">
    <link rel="stylesheet" href="vendor/font-awesome/css/all.css">

    <script type="text/javascript" src="https://www.google.com/books/jsapi.js"></script>
    <script type="text/javascript">
      google.books.load();

      function initialize() {
        var viewer = new google.books.DefaultViewer(document.getElementById('viewerCanvas'));
      }

      google.books.setOnLoadCallback(initialize);</script>
    
</head>

<body>

    <div class="navbar">
        <i class="fas fa-bars"></i>
    </div>


    <header>
        <img src="assets/img/logo livro.jpg" alt="logotipo do Visual Studio Code">
        <h1>Busca Livros</h1>
        <h2> Clique na imagem para receber seu link</h2>
    </header>

    <main>

 

    <section id="Book">
        <a href="https://books.google.com.br/"><img src="assets/img/livro2.jfif" alt="Link da àrea de Navegação"> </a>    
    </section>
    </main>


    <footer> <!--footer = rodapé, tag semantica-->
        <p>Busca Livros 2020</p>
    </footer>
    
    <script src="assets/js/script.js"></script>
</body>
</html>
