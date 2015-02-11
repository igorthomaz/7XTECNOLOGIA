# 7XTECNOLOGIA
site oficial da 7X
<!DOCTYPE html>
<html lang="pt-br">
<head><!--CABEÇALHO-->
	<meta charset="UTF-8"/>
	<title>7X Tecnologia</title>
	<style>
		p{
			text-alingn: justify;
			text-indent: 50px;
		}
	</style>
	<link rel="stylesheet" href="_css/estilo.css"/>
</head>
<body style="background-color: black;"><!--cor do fundo da página Outra opção é body 
{
background-color:...;
color:...;
}-->
<body><!--CORPO-->
<div id="interface">

	<header id="cabeçalho">
	<br>
	<hgroup><!--AGRUPA OS TÍTULOS (GRUPO DE TÍTULOS)-->
	<h1>7X Tecnologias
	<style>
		h1{
			font-family: Arial;
			font-size: 30pt;
			color: green;
			text-shadow: 2px 10px 40px #00ff00;
		}
	</style></h1>
	<!--<h4>Tecnologia
	<style>
	h4{
			font-family: Arial;
			font-size: 40pt;
			color: #008B00;
			text-shadow: 2px 10px 40px #00ff00;
		}
	</style>-->
	</h4>
	<style>
		h3{
			font-family: Arial;
			font-size: 20pt;
			color: green;
			text-shadow: 2px 10px 40px black;
		}
	</style>
<style>
		h5{
			font-family: Arial;
			font-size: 15pt;
			color: green;
			text-shadow: 2px 10px 40px #7FFF00;
		}
	</style>
	</hgroup>
     
	<!--AQUI ENTRA UMA FOTO,SEMPRE DANDO O CAMINHO DE ONDE ELA VEM!-->
	<nav id="menu"><!--parte de navegação para as páginas-->
	<h1>Menu Principal</h1>
	<ul type="disc">
		<li><a href="index.html">Home</a></li>
		<li><a href="specs.html">Nossa História</a></li>
		<li><a href="fotos.html">Portifólio</a></li>
		<li><a href="multimidea.html">Parceiros</a></li>
		<li><a href="fale-sonosco.html">Fale conosco</a></li>
	</ul>
	</nav>
</header>

<hgroup><!--<br/>significa quebra de linha, para baixo. &nbsp; significa quebra de espaço para o lado.-->
<h3>Tecnologia >  Inovações</h3>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<h5>(21) 3124-2966</h5>
<h5>www.7xtecnologia.com.br</h5>
</hgroup>
<br>
<br>
</div>
</body>
</html>

estilo.css3
@charset "UTF-8";
body {
	background-color: #dddddd;
	color: rgba(0,0,0,1);
}
div#interface{
	width: 900px;
	background-color:black;
	margin: -20px auto 0px auto;
	box-shadow: 0px 0px 10px rgba(0,0,0,.5);
	padding: 10px 10px 10px 10px;
}
p {
	text-align: justify;
	text-indent: 50px;
}
header#cabecalho img#icone {
	position: absolute;
	left: 800px;
	top: 50px;
}
 /*formatação de imagens com legendas*/

figure.foto-legenda {
	position: relative;
	border: 8px solid white;
	box-shadow: 1px 1px 4px black;
}
figure.foto-legenda img{
	width: 100%;
	height: 100%;
}
figure.foto-legenda figcaption {
	opacity: 0;
	position : absolute;
	top: 0px;
	background-color: rgba(0,0,0,.4);
	color: white;
	width: 100%;
	height: 100%;
	padding: 10px;
	box-sizing: border-box;
	transition: opscity 1s;
}

figure.foto-legenda:hover figcaption {
	opacity: 1;
}
/* Formatação do menu*/ 
nav#menu {
	display: block;
	
}
nav#menu ul {
	list-style: none;
	text-transform:uppercase;
	position:absolute;
	top:-30px;
	left:450px;
}
nav#menu li {
	display: inline-block;
	background-color: #000000;
	padding:10px;
	margin:2px;
	-webkit-transition: background-color 1s;/*mudança de cor por 1s p/ safari*/
	-moz-transition: background-color 1s;/*mudança de cor por 1s p/ firefox*/
	-o-transition: background-color 1s;/*mudança de cor por 1s p/ opera*/
	-ms-transition: background-color 1s;/*mudança de cor por 1s p/ navegadores da microsoft*/
	transition: background-color 1s;/*mudança de cor por 1s*/
	
}
nav#menu li:hover {
	background-color: #00ff00;
}
nav#menu h1{
	display: none; /*esconde um menu sem ter que tirar do programa!*/
}
nav#menu a {
	color: #009900;
	text-decoration: none;
}
nav#menu a:hover {
	color: #000000;
	text-decoration: underline;
}
	

	
	
	
	
	
	
	
	
	
	
	
