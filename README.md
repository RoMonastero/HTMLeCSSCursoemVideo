Modulo 1:

Livros para aprender HTML5 e CSS3:

Material de apoio do Curso em Video - PDF do curso
Referencia MDN
Referencia W3C Standards
WHATWG Living Standard
W3Schools
HTML5 Entendendo e Executando
CSS Guia definitivo
Flexbox in CSS
Grid layout in CSS
HTML5 e CSS3
HTML&CSS projete e construa websites
HTML e CSS Use a Cabeça
Crie Seu Proprio Site
HTML5
CSS3
Fundamentos de HTML5 e CSS3
Css Grid Layout
Curso de design grafico
A psicologia das cores
design
pensar com tipos
Flexbox explained
Css grid explained
Smashing Html5
Smashing Css

Capitulo 2:

Dominio: é um endereço para o seu site que deve ter um nome unico, costuma ser pago e tem varios TLDs

Hospedagem: é o espaço para armazenar arquivos, costuma ser paga, deve ser escolhida com base em tamanho dos arquivos, tipos de linguagem, etc

URL: é um endereço que aponta para algum lugar

Capitulo 3:

Como funciona o HTML e o CSS
Não se programa em HTML e em CSS, se diz que se desenvolve em HTML e em CSS

O conteudo de um site é o HTML, o design da página é o CSS e as intercações vem do JavaScript

Capitulo 4:

Algumas tags em HTML:
<h1></h1> -> Titulo em HTML
<p></p> -> Paragrafo em HTML
<img src="foto.png" alt="Exemplo de foto"> -> Carregando uma imagem em HTML

Exemplos de estilo no CSS:
h1{
    font-family: Arial; -> Mudando a fonte da tag h1
    font-size: 20pt; -> Mudando o tamanho da fonte da tag h1
    color: blue; -> Mudando a cor da tag h1
}

Estrutura basica do HTML
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width,initial-scale=1.0"> -> O site vai ser iniciado de forma padrao (sem zoom nem nada)
        <title>Document</title>
    </head> -> Area de configurações
    <body>
        <h1>Olá, Mundo!</h1>
    </body> -> Area de corpo do site
</html>

Se digitar "html" no documento aparece a estrutura basica do HTMl, para nao precisar ficar escrevendo toda hora

Capitulo 5:

Tag <hr> cria uma linha horizontal no site
Tag <br> ele quebra uma linha
Para utilizar <> -> < = &lt; > = &gt;

É errado usar varios <br> em sequencia para quebrar varias linhas, o certo é usar o css pra controlar o tamanho do espacamento

Comentario em HTML <!-- Aqui vai o comentario -->

Para emojis é preciso pegar o código do emojipedia depois do U+ (qualquer duvida ver exercicio 002) e passar assim &#x1F914; onde depois do x vem o codigo do emoji

Capitulo 6:

Não se pode usar toda e qualquer imagem livremente

No google imagens vc pode pesquisar e entrar nas ferramentas e mudar o tipo de imagens para a segunda opção
Unsplash e pexels são alguns exemplos de sites com imagens sem direitos autorais 

GIMP -> photoshop gratuito 

O jpeg costuma ser o formato mais utilizado por não ser um formato pesado
O png é uma otima opçao tambem
Mas depende do que vc precisa tem um formato de arquivo que se encaixa melhor

O tamanho ideal para uma imagem na internet é de até 1500x1000 e a resoluçao é 72

No CSS é possivel mudar o tamanho da imagem tambem, mas nao muda o tamanho do arquivo. Sendo assim é preciso editar a imagem pra deixar um arquivo que pese pouco e então fazer as ediçoes necessarias com o CSS

Usando a tag img:
<img src="logo-html.png" alt="Logo HTML">
não é preciso digitar o src, se colocar o cursor dentro das aspas e utilicar o comando ctrl + espaco aparece as imagens na pasta

Para imagens da web é so passar o endereco da imagem da web no src

Favicon é o icone que fica na frente das abas e é possivel mudar esse icone

Site para pegar icones: iconarchive (baixar como ico)

favicon.cc é um site para desenhar icones

favicon.io transforma varias coisas em icone

e para ter o favicon é so adicionar no head:
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">

Capitulo 7:
Podemos ter varios h1, h2, h3, h4, h5 ou h6, tudo depende da hierarquia desse titulo na pagina

para gerar um testo x no seu paragrafo é so escrever lorem dentro do <p></p> e dar enter

Certas tags não devem ser mais utilizadas no HTML5, como <center></center>. Agora é necessario usar o css para esse tipo de alterção

Capitulo 8:

Para utilizar o negrito: <b></b> ou <strong></strong>(Forma semantica)

Para utilizar o italico: <i></i> ou <em></em> (Forma semantica)

Marcando texto: <mark></mark>

mudando cor do mark: <mark style="background-color: lime;"></mark> (Dessa forma so muda a cor desse mark e nao de outros, para isso é preciso fazer de outra maneira (utilizando o css))
 utilizando o css para o mark:
 dentro do head: <style>
        mark{
            background-color: limegreen;
        }
    </style>

texto grande: <big></big> -> tag obsoleta (melhor alterar o tamanho da letra no css)
texto pequeno: <small></small>

texto excluido: <del></del>
texto inserido: <ins></ins>
texto sobrescrito: <sup></sup>
texto subscrito <sub></sub>

deixar o texto como codigo fonte: <code></code> (nao organiza o codigo com identacao para isso utilize a tag <pre></pre>)

shift + tab -> faz a funcao do tab, mas pra esquerda

para criar uma citacao simples: <q></q>
citacoes completas: <blockquote cite="aqui vai o link para a citacao da frase"></blockquote>
abreviacoes = <abbr title="Hypertext Markup Language">HTML</abbr>
texto invertido: <bdo dir="rtl"></bdo>

Capitulo 9:

Listas ordenadas (As listas que a ordem faz diferenca):
<ol type="A"> <!--Sem o type é uma lista numerada de 1 a X-->
    <li>lala</li>
    <li>aaa</li>
</ol>

listas nao ordenadas (a ordem nao importa):
<ul type="circle"> <!--Sem o type é uma lista com as bolinhas na frente-->
    <li>lala</li>
    <li>aaa</li>
</ul>

misturando tipos de listas:
    <ol>
        <li>NES</li>
        <ul>
            <li>Mario</li>
            <li>Zelda</li>
        </ul>
        <li>Super Nintendo</li>
        <ul>
            <li>Mario</li>
        <li>Zelda</li>
        </ul>
        <li>PlayStation</li>
        <ul>
            <li>Minecraft</li>
            <li>GTA</li>
        </ul>     
    </ol>

Lista de Definicao:
<dl>
    <dt>Termo</dt>
    <dd>Descricao</dd>
</dl>

Capitulo 10:

SEO - é uma otimização para os mecanismos de busca te encontrarem

link externo - aponta para um site q não é nosso
usando links:
<a href="www.aquivaiolink.com">teste</a>
ou
<a href="www.aquivaiolink.com" target="_blank" rel="external">teste</a> essas tags novas dizem que é um link externo e que será aberto uma nova janela quando o usuario clicar no link

link interno -> é uma ligação entre outra pagina que esta associada ao mesmo projeto, para isso é preciso ter mais de uma página no projeto
para um link interno:
<a href="nome do caminho do arquivo" rel="next">Segunda Pagina</a> -> ctrl + espço no href mostra a lista de arquivos que podem ser usados para uma nova pagina 

rel = "next" -> para navegar para a proxima pagina
rel = "prev" -> para navegar para a pagina anterior
rel = "nofollow" -> serve para links externos que não farao parte da indexação do site (ou não da um aval para o link)

navegando para arquivos dentro de outras pastas:
 <a href="noticias/page3.html" rel="next">pagina de noticias</a>

 target="_self" -> serve para falar que nao é para abrir outra pagina


Links para download:
<a href="#">lalal</a> -> a # diz que é um link que não existe ainda (link vazio)
<a href="livro/Currículo.zip" download="Currículo.pdf" type="application/zip">Baixar livro em ZIP</a> -> o type pode ser encontrado no site que esta no pdf da aula 10

Dependendo do navegador o pdf nao será baixado com esses parametros, será apenas aberto

<li title="Use a tag &lt;p&gt;">Parágrafos</li> -> esse title serve para quando o mouse é passado em algum item da lista mostrar oq esta escrito dentro do title
 
Capitulo 11:

É muito importante entender que o usuario pode acessar o site por varias plataformas diferentes, sendo assim podem ter imagens de varios tamanhos, dependendo da tela do usuario

tag <picture></picuture> -> existe uma tag img dentro tambem, mas permite a criacao de varias tags sources para ter varias imagens diferentes

utilizando o picture e o source:
    <picture>
        <source media="(max-width: 750px)" srcset="imagens/p.png" type="image/png">
        <source media="(max-width: 1050px)" srcset="imagens/m.png" type="image/png">
        <img src="imagens/g.png" alt="foto-g">
    </picture>

Colocando um audio no site:
<audio src="media/happy-mistake.mp3" controls autoplay></audio> -> o autoplay serve para o audio ja comecar tocando (Maneira simplificada de criar o audio)

Nem todo navegador vai aceitar o .mp3, mas existem alguns outros arquivos, como o wav e o ogg

<audio preload="metadata" controls loop> -> loop faz o audio tocar em looping
    <source src="media/happy-mistake.mp3" type="audio/mpeg">
    <source src="media/happy-mistake.ogg" type="audio/ogg">
    <source src="media/happy-mistake.wav" type="audio/wav">
    <p>Infelizmente o seu navegador não consegue ouvit audio</p>
</audio> -> jeito mais complexo de criar o audio no navegador, porem garante uma tratativa de erro caso não seja compativel com os tipos de audio

Para baixar videos é so usar o pexels tambem
handbreak -> software de video parecido com o gimp

Colocando video localmente:
<video src="media/meu-video.mp4" controls></video> -> colocando de forma simplificada

<video controls poster="images/limoes-capa.png"> -> poster é a tamb do video
        <source src="media/meu-video.mp4" type="video/mp4">
        <source src="media/Meu-Video.m4v" type="video/mp4">
        <source src="media/Meu-Video.webm" type="video/webm">
        <p>Seu navegador nao tem compatibilidade com reproducao de videos</p>

</video> -> Videos de forma mais complexa

Videos hospedados localmente é algo que deixa mega caro a hospedagem do site

Videos hospedados remotamente:
No youtube é so clicar em compartilhar, clicar em incorporar e copiar o codigo que é passado no seu site
outra opcao é o vimeo que funciona de forma parecida com o youtube

Capitulo 12:

css inline -> é mudar as tags direto nas tags html
A desvantagem é que é preciso mudar tag por tag o estilo da tag e o codigo fica super confuso

css internos -> é utilizando o <style></style> no head do html sem utilizar outro arquivo
A vantagem é que nap precisa mudar o estilo em cada uma das tags e caso nao for mudar o estilo em outras paginas é so usar localmente, ao inves de gerar outro arquivo
A desvantagem é incomoda pq o estilo costuma ser bem longo e vai ocupar muito espaco e nao da para replicar os estilos em mais de uma pagina

css externo -> é utilizado criando outro arquivo e chamando ele da seguinte forma:
<link rel="stylesheet" href="style.css">

@charset "UTF-8"; -> no arquivo css bem no inicio pode ser usado essa tag para dizer q o utf 8 sera utilizado

É possivel utilizar mais de um arquivo css por pagina html

É possivel utilizar as 3 formas de css ao mesmo tempo

FIM MODULO 1


