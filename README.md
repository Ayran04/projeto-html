<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Tag Aside</title>
    <link rel="stylesheet" href="./css/style.css">
</head>

<body>
    <header>
        <h1>Header</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Sobre</a></li>
            <li><a href="#">Serviços</a></li>
            <li><a href="./contato.html">Contato</a></li>
        </ul>
    </nav>
    <main>

        <h2>Main Content</h2>
        <p>testando testando testando testando.</p>
        <section>
            <h2>Section 1</h2>
            <section>
                <div class="slider">
    
                    <div class="slides">
                        <input type="radio" name="radio-btn" id="radio1">
                        <input type="radio" name="radio-btn" id="radio2">
                        <input type="radio" name="radio-btn" id="radio3">
    
                        <div class="slide first">
                            <img src="https://i.stack.imgur.com/8Ynld.jpg"
                                alt="">
                        </div>
                        <div class="slide">
                            <img src="https://i.pinimg.com/originals/7a/67/03/7a670363bbf825d15481ecb18e684400.jpg" alt="">
                        </div>
                        <div class="slide">
                            <img src="https://i.pinimg.com/originals/d5/c0/6e/d5c06ee6e4bf452db2255cc36f600384.jpg" alt="">
                        </div>
                    </div>
    
                    <div class="navigation-bar">
                        <label class="manual-btn" for="radio1"></label>
                        <label class="manual-btn" for="radio2"></label>
                        <label class="manual-btn" for="radio3"></label>
                    </div>
    
                </div>
            </section>
        </section>

    </main>
    <aside>
        <h2>Topicos</h2>
        <ul class="menu-aside">
            <li><a class="item-aside" href="#">Topico 1</a></li>
            <li><a class="item-aside" href="#">Topico 2</a></li>
            <li><a class="item-aside" href="#">Topico 3</a></li>
        </ul class="menu-aside">
        <h2>Links Importantes</h2>
        <ul class="menu-aside">
            <li><a class="item-aside" href="#">Link 1</a></li>
            <li><a class="item-aside" href="#">Link 2</a></li>
            <li><a class="item-aside" href="#">Link 3</a></li>
        </ul class="menu-aside">
    </aside>
    <footer>
        <h2>Footer</h2>
        <p>This is the footer of the page.</p>
    </footer>
</body>

</html>
