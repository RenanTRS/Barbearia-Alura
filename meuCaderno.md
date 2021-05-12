# Parte 1
<strong> - serve para dar importância
<en> - serve para deixar em itálico
<p> - para fazer parágrafo
<h1> - serve para fazer título.
<!DOCTYPE html> - serve para passar ao navegador qual versão de html estamos usando.
<meta charset="UTF-8"> - serve para informar o navegador sobre os caracteres.
<html lang="pt-br"> - além de identificar o que é html, está dizendo o idioma do conteúdo
<title> - serve para por o título da página na aba do navegador
<head> - serve como a cabeça, lá vai tudo que quero passar para o navegador
<body> - serve como o corpo, lá vai tudo que quero mostrar para o usuário.

## Aula 3 - CSS
font-size:20px;- serve para esta tag, aumentar o tamanho da font de 16 para 20 px
text-align : center; - serve para alinhar o texto no centro.
<style> - serve para por o css.
<link rel="stylesheet" href="style.css"> - serve para linkar um arquivo css.
background-color:#CCCCCC; - serve para a cor do background
color:red; - serve para escolher a cor do texto

## Aula 04
id - serve como identificador. (<p id="nomeDoId">)
#nomeDoId - serve para chamar o id no css.
<img src="caminhoDaImagem.jpg"> - serve para por uma imgem no html.
width:100%;  - serve para modificar a largura
height:120px;  - serve para modificar a altura
border:; - serve para modificar a borda
padding:; - serve para modificar o espaço interno
margin:; - serve para modificar a margem externa
Aula 5
<ul> - lista não ordenada
<ol> - lista ordenada
<li> - linha de cada lista
class="nomeDaClasse" - serve como o id porém marca vários itens
.nomeDaClasse - forma de chamar a classe no css.
font-style:italic; - código css para deixar em itálico.
<div> - serve para fazer uma divisão
veritical-align:top; - serve para alinhar pela forma vertical
<header> - cabeçalho do site

#Parte 2
##Aula01 - Criando uma nova página.
## Nova página:
	- Apenas criou um arquivo html e css.

### Novo cabeçalho:
	- Inseri a imagem da logo como <h1> dentro de <header> junto com uma <ul> para menu.
Ex:
	<header>
		<h1><img src="logo.png"></h1>
		<ul>
			<li>HOME</li>
			<li>PRODUTOS</li>
			<li>CONTATOS</li>
		</ul>
	</header>

##Aula02 - Navegação entre páginas
### Estruturando a navegação:
	- Foi criado links usando <a> em cada um dos <li>
Ex:
	<li><a href="index.html">Home</a></li>

### Arrumando a lista:
	- Acrescentou a tag <nav> para especificar que é o nav menu e dentro ficou as tags <ul>.
	- No arquivo css: Foi usado text-decoration:none; para tirar a decoração com o parâmetro none.
	- No arquivo css: Foi usado display:inline; para colocar a lista em uma linha.
	 - Css: Foi usado font-weight:22px; como peso da fonte "negrito".
	- Css: Foi usado text-transform:uppercase; para deixar o texto em caixa alta.

## Aula03 - Posicionamento dos elementos
### Limpando o CSS:
	- Add arquivo reset.css, é um arquivo padrão para limpar as formatações que vem por padrão no navegador, e o seu link deve ser posto antes do link da página que estamos trabalhando.

### Posicionando o Cabeçalho:
CSS:
	position: ; -> posição que terá no seu ponto inicial.
		- absolute -> movimentação livre;
		- relative -> preso dentro do campo da tag;
		- static -> parado;
	top : px; -> altera a altura
	right: px; -> ajusta a direita
	left: ; -> ajusta a esquerda
	*Dica:* Quando for necessário inserir os quatro valores no sentido horário como em margin: 0 0 0 0; e houver um valor padrão pode-se fazer margin:10 20; primeiro valor é para cima e baixo e o segundo valor é para os lados.

## Aula04
### Divisões Semânticas:
-HTML: 
	<main> -> assim como o menu tem a tag <nav>, o contetúdo principal possui sua própria tag.

### Reforçando o inline-block:
CSS: 
	vertical-align: ; -> serve para alinhar o conteúdo de forma vertical
		- top
		- middle
		- bottom
		- auto

## Aula 05
### Aplicando bordas:
- CSS
```
border: 2px solid #000000;
```
###Bordas arredondadas:
- CSS
```
border-radius: 10x;
```