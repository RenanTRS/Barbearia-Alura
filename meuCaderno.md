# Parte 1
```<strong>``` Serve para dar importância.  
```<en>``` Serve para deixar em itálico.  
```<p>``` Para fazer parágrafo.  
```<h1>``` Serve para fazer título.  
```<!DOCTYPE html>``` Serve para passar ao navegador qual versão de html estamos usando.  
```<meta charset="UTF-8">``` Serve para informar o navegador sobre os caracteres.  
```<html lang="pt-br">``` Além de identificar o que é html, está dizendo o idioma do conteúdo.  
```<title>``` Serve para por o título da página na aba do navegador.  
```<head>``` Serve como a cabeça, lá vai tudo que quero passar para o navegador.  
```<body>``` Serve como o corpo, lá vai tudo que quero mostrar para o usuário.  

## Aula 3 - CSS
```font-size:20px;``` Serve para esta tag, aumentar o tamanho da font de 16 para 20 px.  
```text-align : center;``` Serve para alinhar o texto no centro.  
```<style>``` Serve para por o css.  
```<link rel="stylesheet" href="style.css">``` Serve para linkar um arquivo css.  
```background-color:#CCCCCC;``` Serve para a cor do background.  
```color:red;``` Serve para escolher a cor do texto.  

## Aula 04
- HTML  
```<p id="nomeDoID">``` **id** Serve como identificador.  
```#nomeDoId``` Serve para chamar o id no css.  
```<img src="caminhoDaImagem.jpg">``` Serve para por uma imgem no html.  
- CSS  
```width:100%;``` Serve para modificar a largura.  
```height:120px;``` Serve para modificar a altura.  
```border:2px solid #000000;``` Serve para modificar a borda.  
```padding:;``` Serve para modificar o espaço interno.  
```margin:;``` Serve para modificar a margem externa.  

## Aula 5
- HTML  
```<ul>``` Lista não ordenada.  
```<ol>``` Lista ordenada.  
```<li>``` Linha de cada lista.  
```<p class="nomeDaClasse>"``` Serve como o id porém marca vários itens.  
```<header>``` Cabeçalho do site.  
```<div>``` Serve para fazer uma divisão.  
- CSS  
```.nomeDaClasse``` Forma de chamar a classe no css.  
```font-style:italic;``` Código css para deixar em itálico.  
```veritical-align:top;``` Serve para alinhar pela forma vertical.  

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
- Acrescentou a tag ```<nav>``` para especificar que é o nav menu e dentro ficou as tags ```<ul>```.  
- No arquivo css: Foi usado text-decoration:none; para tirar a decoração com o parâmetro none.  
- No arquivo css: Foi usado display:inline;  para colocar a lista em uma linha.  
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
- **HTML:** 
	<main> -> assim como o menu tem a tag <nav>, o contetúdo principal possui sua própria tag.

### Reforçando o inline-block:
**CSS:**  
```vertical-align: ;``` -> serve para alinhar o conteúdo de forma vertical
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

## Aula06  
### Pseudo-classes de Estado:  
- **CSS**  
- ```:hover``` Serve para informar um comportamento sempre que o mouse passar por cima.  
```
nav a:hover{
	color: #C78C19;
	text-decoration: underline;
}
```  
### Aplicando hover e active:  
- **CSS**  
- ```:active``` Serve para informar um comportamento sempre que o mouse clicar.  
```
nav li:active{
	border-color: white;
}
```  