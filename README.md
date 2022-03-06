# SITE-RESPONSIVO-HTML-CSS

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="imagens/favicon.ico" type="image/x-icon">
    <link rel="stylesheet" href="style.css">
    <title>Site Android</title>
        
</head>
<body>
    <header>
        <h1>CURIOSIDADES DE TECNOLOGIA</h1>
        <p>Tudo aquilo que você sempre quis saber sobre o mundo Tech, em um único lugar</p>
        <!--nav é usado quando for colocar links-->        
    </header>
    
    <nav>
        <a href="#" id="home">Home</a>
        <a href="#" id="noticias">Noticias</a>
        <a href="#" id="curiosidades">Curiosidades</a>
        <a href="#" id="faleconosco">Fale Conosco</a>
    </nav>

    <main>
        <article>
            <h1>HISTORIA DO MASCOTE DO ANDROID</h1>
                <p>Provavelmente você sabe que o sistema operacional <a href="#">Android</a>, mantido pelo <a href="#">Google</a> é um dos mais ultilizados para dispositivos móveis em todo o mundo. Mas talvez você não saiba que seu simpatico mascote tem um nome e uma historia muito curiosa? Pois acompanhe essa artigo para aprender varias coisas sobre esse robozinho.</p> 
            <h2>A PRIMEIRA VERSÃO</h2>
                <p>A primeira tentativa de criar um mascote surgiu em 2007 e veio de um desenvolvedor chamado <a href="#">Dan Morrill</a>. Ele conta que abriu o <a href="#">Inkscape</a> (Software livre para vetorização de imagens) e criou sua propria versão do robô. O objetivo era apenas personificar o sistema apenas para a sua equipe, não existia nenhuma solicitação da empresa para criação de um mascote</p>
                
                <picture>
                    <!--So FUNCIONA SE TIVER DENTRO DA TAG PICTURE-->
                    <source media="(max-width:800px)" srcset="imagens/dan-droids-pq.png">
                    <img src="imagens/dan-droids.png" alt="android">
                </picture>
                
                <p>Essa primeira versão bizarra até foi batizada em homenagem ao seu criador, seriam os <span>Dandroids</span></p>

            <h2>SURGE UM NOVO MASCOTE</h2>
                <p>A ideia de ter um mascote foi amadurecendo e a missão foi passada para um profissional da área. A ilustradora Russa <a href="#">Irina Blok</a>, também funcionária do Google, ficou com a missão de representar o pequeno robô de uma maneira mais agradável.</p>

            <picture>
                <!--Fotos da Irinna-->
                <source media="(max-width:600px)" srcset="imagens/irina-blok-pq.jpg">
                <img src="imagens/irina-blok.jpg" alt="android">
            </picture>
            
                <p>A ideia Principal de Irina era repersentar tudo graficamente com poucos traços e de forma mais chapada. O desenho também deveria gerar indetificação rápida com quem o olha. Surgiu emntão o Bugdroid, o novo mascote do Android.</p>
            
            <picture>
                <!--Fotos do BugDroid-->
                <img src="imagens/bugdroid.png" class="pequeno" alt="bugdroid">
            </picture>
            
                <p>A principal inspiração para os traços do novo BugDroid veio daqueles bonequinhos que ilustram portas de banheiro para indicar o gênero de cada porta. Conta a lenda que a artista estava criando em sua mesa no escritorio do <span>Google</span> e olhou para o lado dos banheiros e a indentificação foi imediata: simples, limpo e objetivo.</p>

                <div class="video"><iframe width="560" height="315" src="https://www.youtube.com/embed/l2UDgpLz20M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
            <aside>
                <h2>Quer aprender mais?</h2>
                <p>Outro assunto curioso em relação ao Android é que cada versão sempre foi nomeada em homenagem a um doce, em ordem alfabética a partir da versão 1.5 até a 9.0.</p>   

                <!--Abbr deixa um nome com a descrição-->
                <ul>
                    <li>1.5 - <abbr title="Cupcake">Cupcake</abbr></li>
                    <li>1.6 - Donut</li>
                    <li>3.0 - Eclair</li>
                    <li>2.2 - Froyo</li>
                    <li>2.3 - Gingerbread</li>
                    <li>3.0 - Honeycomb</li>
                    <li>4.0 Ice Cream</li>
                </ul>
                <ul>
                    <li>4.1 - Jelly Bean</li>
                    <li>4.4 - KitKat</li>
                    <li>5.0 - lolipop</li>
                    <li>6.0 - Marshmallow</li>
                    <li>7.0 - Nougat</li>
                    <li>8.0 Oreo</li>
                    <li>9.0 Pie</li>
                </ul>

                <p>Infelizmente, o <span>Android Q</span> não existiu, pois o Google resolveu por fim a essa divertida prática e começou a usar numerações, o que deu origem ao <span>Android 10</span></p>
                <p>Acesse aqui o site <a href="#">Android History</a> para conhecer a sequência das versões "adocicadas" e o que cada uma trouxe para o sistema Android.</p>
                <p>Então é isso! Espero que você tenha gostado do nosso artigo com essa curiosidade sobre o sistema <span>Android</span> e seu simpático mascote.</p>
            </aside>
    </article>
    </main>

    <footer>
        <p>Site criado por Matheus Pessoa para o CursoemVideo</p>
    </footer>
</body>
</html>
