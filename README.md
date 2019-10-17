# Meu-site
Aqui postarei meus códigos do projeto de Programação Básica para Web
Aqui começo o meu projeto. Nesse primeiro momento, irei fazer só o html básicao. Botar os Navs., H1, H2's, <p>'s, o footer e etc...

Coloquei os links dos jogos que vou falar e um pouco sobre eles.

Botei também o conteúdo.
-----------------------------------------------------------------------------
2° edit: 
Aqui deixei melhor a visualização do código.
Dividi o conteúdo com sections e divs, onde por meio das classes ficará mais fácil pra por o CSS futuramente.
Divide o conteúdo nos articles, coloquei as targets nos links navegaveis.
Inclui a lingaguem e o meta no inicio do código para ficar melhor o entendimento do navegador.
2° edit em cima ->
---------------------------------------------------------------------------------------
3edit ->
Aqui já é o código HTML com CSS inserido externamente.
Fiz algumas alterações no código quanto a classe e divs.
Inseri uma img da logo que nos próximos passos vou ta melhorando ela ou possivelmente até trocando ela.
--------------------------------------------------------------------------
4edit ->
Nesse edit eu mudei algumas coisas no CSS.
Mudei também algumas coisas do código como tirar algumas divs. Tirar algumas classes pra se adaptar melhor ao CSS.

5°edit - Nele eu inclui as imagens do restante do texto.
Comecei a organizar essas imagens pelo CSS, logo terminarei.
Coloquei classe nas figures pra facilitar a estruturar melhor no CSS; Possivelmente eu tire ou adc de forma diferente elas depois.
--------------------------------------------------------------------------------------------------------------------
6° edit - Nessa edição eu fiz uma modificação GERAL.
Alterei a fonte dos textos.
Por descobrir que eu teria que criar as outras páginas do zero, eu tive que tirar o conteúdo da página principal
e dividir ele nas outras páginas. Além de adc mais conteúdo nelas.
Mudei o CSS melhorando o rodapé.
Tirei a imagem de logo e deixei apenas o nome.
Alterei o nome que apareceria na guia do navegador, botando o nome certo de cada uma.
Tirei algumas classes que não eram necessárias.
O código tava apresentando um erro, pq o footer tava sendo lido com o Class Geral, nisso eu descobri que
foi pq eu nao fechei a Div. Fechei ela e corrigi o erro.
--------------------------------------------------------------------------------------------------------------------


<!DOCTYPE html>
<html>
<head>
	<html lang="pt-br">
	<meta charset="utf-8">
	<title>Início</title>
</head>
<link href="https://fonts.googleapis.com/css?family=Roboto&display=swap" rel="stylesheet">
<link rel="stylesheet" type="text/css" href="estilo.css" />
<link rel="stylesheet" type="text/css" href="normalize.css" />
<body>
<!--Será a barra de navegação horizontal do site-->
	<nav>
		<ul>
			<li><a href="index.html">Início</a></li>
			<li><a href="six.html">Rainbow Six Siege</a></li>
			<li><a href="runescape.html">RuneScape</a></li>
			<li><a href="cf.html"> CrossFire AL</a></li>
			<li><a href="formulario.html">Formulário</a></li>
		</ul>
	</nav>
	<!-- Daqui pra baixo é o conteúdo do site.
	*Lembrando que falta organizar todo o código. 
	*Por as sections, articles, divs, class e etc...-->
	<header class="titulo">
		<h1>JGamers</h1>
	</header>
	<div class="geral">
		<section>
			<h2>Conhecendo o mundo dos jogos</h2>
			<article>
				<p>A história dos jogos digitais teve início quando os acadêmicos começaram a projetar jogos simples, simuladores e programas de inteligência artificial, como parte de suas pesquisas em ciência da computação. Somente a partir das décadas de 1970 e 1980 é que os jogos eletrônicos se tornaram populares, quando jogos de arcade, console de jogos eletrônicos e jogos de computador foram introduzidos ao público em geral. Desde então, os jogos eletrônicos tornaram-se uma forma popular de entretenimento e uma parte da cultura moderna em diversas regiões do mundo.</p>
				<p>E é bem verdade que, nos últimos anos, cada vez menos pessoas compartilham o senso comum de que jogar videogames é um assunto restrito para os nerds ou para o público infanto-juvenil. Mas são em eventos como na <b>Brasil Game Show (BGS)</b> que se constata a força e o alcance do mercado dos jogos digitais.</p>
			</article>
			<h3>Jogos eletrônicos também é esporte</h3>
			<article>
				<p>O eSports, ou esporte eletrônico, veio para ficar. A modalidade de competição profissional com videogames não é muito nova, mas cresce a cada ano, sempre na cola de jogos de sucesso, como League of Legends, DotA 2, Counter-Strike, Starcraft e outros. Entenda melhor essa febre e alguns de seus principais torneios:</p>
			</article>
			<article>
				<h3>Origem</h3>
					<p>As origens do esporte eletrônico estão, possivelmente, na Coreia do Sul e em alguns pontos da Ásia e Europa. Os jogos do gênero de estratégia em tempo real cresceram nesses locais, além de levarem ainda popularidade aos jogadores profissionais que surgiram na onda. Na Coreia do Sul, por exemplo, o eSport é uma modalidade competitiva reconhecida oficialmente desde o ano 2000.</p>
					<p>Hoje, além da Ásia, outros grandes territórios do eSport são América do Norte e o restante da Europa que ainda não tinha sido apanhada pela “febre” nos primeiros momentos. Há até mesmo jogadores que conseguem visto de viagem para modalidades esportivas, o que mostra a evolução das competições. Os maiores torneios possuem transmissões ao vivo via Internet, etapas presenciais com milhares de pessoas na plateia e até mesmo narradores oficiais.</p>
			</article>
			<article>
				<h3>Jogadores Profissionais</h3>
					<p>Jogadores profissionais como todo esporte tradicional, os esportes eletrônicos também possuem times e jogadores oficiais. É normal que uma equipe de eSport seja patrocinada por uma grande marca relacionada com games, por exemplo, além de existirem jogadores que possuem suas próprias marcas, fama e, claro, uma legião de fãs.</p>
			</article>
		</section>
	</div>
	<!--o rodapé ficará aqui em baixo com dados dos criadores-->
	<section>
		<footer>
			<span>&copy; 2019 - JGamers - Todos os direitos reservados</span>
		</footer>
	</section>
</body>
</html>
