<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Game Shop - A sua loja de games</title>
        <link rel="stylesheet" href="style.css">
        <!--Fontes Google-->
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Bungee+Spice&family=Bungee&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">


    </head>
<body>
    <header>
        <div class="container">
            <h1>Game Shop</h1>
            <nav>
                <ul>
                    <li>
                        <a href="#sobre">Sobre a loja</a>
                    </li>
                    <li>
                        <a href="#contact">Contato</a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
    <section id="sobre">
        <div class="container">
            <img class="store-Front" src="./Imagens/loja.jpg" alt="logo da nitendo">
            <div>
                <h2>Sobre a loja</h2>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Non corrupti, blanditiis, delectus veritatis, distinctio voluptate optio reprehenderit et placeat unde id voluptatum. Repellendus recusandae reprehenderit earum perspiciatis iure id mollitia.</p>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Animi eligendi ipsam ratione alias asperiores rerum veniam. Ad asperiores ipsam placeat, quod iusto quae aliquid doloribus officiis illo et magni rem!</p>
                <ul class="brands-list">
                    <li><img src="./Imagens/playstation (1).png" alt="playstation"></li>
                    <li><img src="./Imagens/xbox.png" alt="xbox"></li>
                    <li><img src="./Imagens/nintendo (1).png" alt="nintendo"></li>
                </ul>
            </div>
        </div>
    </section>
    <section id="contact">
        <div class="container">
            <h2>Contato</h2>
            <div class="contact-methods">
                <div class="">
                    <h3>Fale Conosco</h3>
                    <form action="">
                        <input type="text" placeholder="Seu nome" required>
                        <input type="email" placeholder="Seu e-mail" required>
                        <input type="tel" placeholder="Seu telefone">
                        <textarea placeholder="Deixe sua mensagem!" name="" id="" cols="30" rows="10" required></textarea>
                        <button type="submit">Enviar</button>
                    </form>
                </div>
                <div>
                    <h3>Nos Acompanhe</h3>
                    <ul class="social-links">
                        <li>
                            <a href="#instagram" title="logo instagram">
                            <img src="./Imagens/instagram.png">
                            </a>
                        </li>
                        <li>
                            <a href="#facebook" title=" logo facebook">
                            <img src="./Imagens/facebook.png" alt="facebook">
                            </a>
                        </li>
                        <li>
                            <a href="#youtube" title="logo youtube">
                            <img src="./Imagens/youtube.png" alt="youtube">
                            </a>
                        </li>
                    </ul>
                </div>
                <div>
                    <h3>Venha até nós</h3>
                        <p>
                            Rua do Conhecimento, nº 7, Front-End, Ebac-Brazil.
                        </p>
                </div>
            </div>
        </div>
    </section>
    <footer>
        <div class="container">
            <p>
                &copy Games Shop - Todos os direitos reservados - 2024
            </p>
        </div>
    </footer>
</body>
</html>
