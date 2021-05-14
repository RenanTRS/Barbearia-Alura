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
- **HTML**  
```<p id="nomeDoID">``` **id** Serve como identificador.  
```#nomeDoId``` Serve para chamar o id no css.  
```<img src="caminhoDaImagem.jpg">``` Serve para por uma imgem no html.  
- **CSS**  
```width:100%;``` Serve para modificar a largura.  
```height:120px;``` Serve para modificar a altura.  
```border:2px solid #000000;``` Serve para modificar a borda.  
```padding:;``` Serve para modificar o espaço interno.  
```margin:;``` Serve para modificar a margem externa.  

## Aula 5
- **HTML**  
```<ul>``` Lista não ordenada.  
```<ol>``` Lista ordenada.  
```<li>``` Linha de cada lista.  
```<p class="nomeDaClasse>"``` Serve como o id porém marca vários itens.  
```<header>``` Cabeçalho do site.  
```<div>``` Serve para fazer uma divisão.  
- **CSS**  
```.nomeDaClasse``` Forma de chamar a classe no css.  
```font-style:italic;``` Código css para deixar em itálico.  
```veritical-align:top;``` Serve para alinhar pela forma vertical.  

# Parte 2
## Aula02 - Navegação entre páginas
### Estruturando a navegação:
- **HTML**  
```<a>``` Tag de acoragem, basicamente cria links.  
**Ex:** ```<li><a href="index.html">Home</a></li>```  

### Arrumando a lista:
- **HTML**  
- ```<nav>``` Tag para especificar que é um menu navigator.  
- **CSS**  
```text-decoration: underline;``` Serve para decoração como sublinhado.  
```display: inline;``` Serve para colocar a lista em linha.  
```font-weight: bold;``` Serve para colocar em negrito.  
```text-transform: uppercase;``` Serve para deixar em caixa alta.  

## Aula03 - Posicionamento dos elementos
### Limpando o CSS:
- Add arquivo **reset.css**, é um arquivo padrão para limpar as formatações que vem por padrão no navegador, e o seu link deve ser posto antes do link da página que estamos trabalhando.  

### Posicionando o Cabeçalho:
- **CSS:**  
```position: ;``` Posição que terá no seu ponto inicial, **absolute** para movimentação livre, **relative** para a tag pai do absolute, **static** parado.  
```top: px;``` Altera a altura.  
```right: px;``` Ajusta a direita.  
```left: px;``` Ajusta a esquerda.  
- **Dica:** Quando for necessário inserir os quatro valores no sentido horário como em ```margin: 0 0 0 0;``` e houver um valor padrão pode-se fazer ```margin:10 20;``` primeiro valor é para cima e baixo e o segundo valor é para os lados.

## Aula04
### Divisões Semânticas:
- **HTML:** 
```<main>``` Assim como o menu tem a tag ```<nav>```, o contetúdo principal possui sua própria tag.

### Reforçando o inline-block:
- **CSS:**  
```vertical-align: ;``` -> serve para alinhar o conteúdo de forma vertical **top, middle, bottom, auto**.  

## Aula 05
### Aplicando bordas:
- **CSS**
```
border: 2px solid #000000;
```
### Bordas arredondadas:
- **CSS**
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

## Aula07
### Rodapé:
- **HTML**  
```<footer>``` Serve para fazer o rodapé.  
- **CSS**  
```background: url(endereco.jpg);``` Serve para mostrar uma imagem de fundo.  

### Caracteres especiais:
- **HTML**  
```&copy;``` Serve para mostrar aquel símbolo de copyright.  

# Parte 3
## Aula01 - Criando uma nova página  
### Começando a página de contato:  
- Apenas copiou e colou de produtos.html para contatos.html e renomeou arquivos .css.  

## Aula02 - Começando um formulário:
### Campos básicos:
```<form>``` Tag para criar um formulário.  
```<label for="">``` Tag que serve como etiqueta para o input.  
```<input type="" id="">``` Tag que irá receber os valores.  
```<input type="submit" value="">``` Tag para criar um botão.  

- **Ex:**
```
<form>
	<label for="nome">Nome</label>
	<input type="text" id="nome">
	
	<label for="email">Email</label>
	<input type="text" id="email">

	<input type="submit" value="Enviar">
<form>
```
### Estilos para o formulário:  
- Apenas foi adicionado estilo ao formulário com comandos css que já sabemos.  

## Aula03 - Tipos de campos diferentes
### Formulários mais completos:  
```<textarea>``` Tag de campo de texto para mensagem.  
```<input type="radio" name="nomeName" value="" id="">```  Input tipo **radio** são como lugares para marcar uma opção, **name** é como se fosse a class do input, serve para quando marcar um radio automaticamente vai desmarcar o outro que pertence ao mesmo name.  

- Outra forma de fazer um **input** seria por a tag ```<input>``` dentro da tag ```<label>```.  
```
<label><input type="">Texto</label>
```
- ```<input type="checkbox">``` Serve para criar um 
checkbox.  
```
<label><input="checkbox">Gostaria de receber nossas novidades por email?</label>
```
- **Ex:**
```
<label for="radioEmail">Email:</label>
<input type="radio" name="radioContato" id="radioEmail">

<label for="radioPhone">Phone:</label>
<input type="radio" name="radioContato" id="radioEmail">

<label><input="checkbox">Gostaria de receber nossas novidades por email?</label>
```

