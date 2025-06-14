# tags html mais utilizadas

## estrutura básica

  * `<!doctype html>`: declara o tipo de documento.
  * `<html>`: raiz do documento html.
  * `<head>`: contém metadados e informações sobre o documento.
  * `<title>`: define o título da página.
  * `<body>`: contém o conteúdo visível da página.
  * `<meta>`: especifica metadados como charset, viewport, etc.
  * `<link>`: vincula recursos externos (css, icones).
  * `<script>`: incorpora ou referencia scripts.
  * `<style>`: define estilos css dentro do documento.
  * `<noscript>`: fornece alternativa quando javascript está desabilitado.

## texto e links

  * `<h1>` a `<h6>`: títulos de diferentes níveis.
  * `<p>`: parágrafo.
  * `<br>`: quebra de linha.
  * `<hr>`: linha horizontal (separador).
  * `<a>`: hiperlink.
  * `<strong>`: texto em negrito (semântico).
  * `<em>`: texto em itálico (semântico).
  * `<mark>`: texto destacado.
  * `<small>`: texto menor (ex: disclaimers).
  * `<blockquote>`: citação longa.
  * `<q>`: citação curta.
  * `<cite>`: título de obra.
  * `<abbr>`: abreviação com título.
  * `<address>`: informações de contato.
  * `<b>`: texto em negrito (sem semântica).
  * `<i>`: texto em itálico (sem semântica).

## imagens e mídia

  * `<img>`: insere uma imagem.
  * `<svg>`: desenho vetorial.
  * `<canvas>`: área para gráficos dinâmicos.
  * `<video>`: incorpora conteúdo de vídeo.
  * `<audio>`: incorpora conteúdo de áudio.
  * `<source>`: especifica múltiplas fontes para mídia.
  * `<track>`: texto de legenda ou outros para mídia.
  * `<iframe>`: incorpora documento html externo.

## formulários

  * `<form>`: contém elementos de formulário.
  * `<input>`: entrada de dados (text, password, etc.).
  * `<button>`: botão interativo.
  * `<select>`: lista de opções (dropdown).
  * `<textarea>`: área de texto multilinha.
  * `<label>`: rótulo associado a um elemento de formulário.
  * `<fieldset>`: agrupa elementos relacionados de formulário.
  * `<legend>`: legenda para um fieldset.
  * `<output>`: resultado de uma ação de usuário.
  * `<meter>`: medidor dentro de um intervalo.
  * `<progress>`: indica progresso de uma tarefa.

## tabelas

  * `<table>`: define uma tabela.
  * `<tr>`: linha de tabela.
  * `<td>`: célula de dados.
  * `<th>`: célula de cabeçalho.
  * `<thead>`: cabeçalho da tabela.
  * `<tbody>`: corpo da tabela.
  * `<tfoot>`: rodapé da tabela.
  * `<caption>`: título da tabela.

## listas

  * `<ul>`: lista não ordenada.
  * `<ol>`: lista ordenada.
  * `<li>`: item de lista.
  * `<dl>`: lista de definição.
  * `<dt>`: termo da lista de definição.
  * `<dd>`: descrição do termo.

## semântica

  * `<article>`: conteúdo independente.
  * `<section>`: seção temática.
  * `<nav>`: navegação principal.
  * `<aside>`: conteúdo lateral.
  * `<header>`: cabeçalho de página ou seção.
  * `<footer>`: rodapé de página ou seção.
  * `<main>`: conteúdo principal da página.
  * `<figure>`: conteúdo autônomo (imagem, diagrama).
  * `<figcaption>`: legenda para uma figura.
  * `<time>`: data/hora.

## layout

  * `<div>`: contêiner genérico.
  *span `<>`: contêiner genérico em linha.
  * `<ins>`: texto inserido.
  * `<del>`: texto deletado.
  * `<pre>`: texto pré-formatado.
  * `<code>`: código de computador.
  * `<var>`: variável.
  * `<samp>`: saída de programa.
  * `<kbd>`: entrada de teclado.
  * `<ruby>`: suporte para caracteres ruby (asiáticos).
  * `<rt>`: explicação de um caracteres ruby.
  * `<rp>`: parênteses para browsers que não suportam ruby.
  * `<bdi>`: texto isolado em direção diferente.
  * `<wbr>`: ponto de quebra opcional.

## scripts e estilos

  * `<style>`: define estilos css dentro do documento.
  * `<script>`: incorpora ou referencia scripts.
  * `<noscript>`: fornece alternativa quando javascript está desabilitado.
  * `<template>`: contêiner para conteúdo a ser clonado.

## semântica avançada

  * `<dialog>`: diálogo ou janela.
  * `<details>`: conteúdo adicional exibível/collapsível.
  * `<summary>`: título para detalhes.
  * `<menu>`: lista de comandos.
  * `<command>`: comando para invocar ações.
  * `<datalist>`: lista de opções para entrada de dados.
  * `<slot>`: ponto de inserção para conteúdo.
  * `<custom>`: elemento personalizado (web components).


# Propriedades css mais utilizadas:

### layout e posicionamento

  * **display** : controla como o elemento é renderizado (block, inline, flex, etc.).
  * **position** : define o posicionamento (relative, absolute, fixed, sticky).
  * **float** : especifica se o elemento deve flutuar (left, right).
  * **clear** : controla o posicionamento em relação a elementos flutuantes (left, right, both).
  * **flex** : propriedades relacionadas ao layout flexível (flex-direction, justify-content, etc.).
  * **grid** : propriedades para criar layouts de grade (grid-template-columns, grid-template-rows, etc.).
  * **column** : cria colunas em um elemento (column-count, column-gap).
  * **overflow** : controla o que acontece quando o conteúdo excede as dimensões (visible, hidden, scroll, auto).
  * **min-width**, **max-width**, **min-height**, **max-height** : definem limites de largura e altura.
  * **width** e **height** : definem a largura e altura exatas.
  * **margin** e **padding** : espaçamento externo e interno.
  * **border** : aplica bordas.
  * **box-sizing** : define como a largura e altura são calculadas (content-box, border-box).
  * **vertical-align** : alinhamento vertical de elementos inline ou tabela.
  * **z-index** : ordem de sobreposição de elementos.
  * **top**, **right**, **bottom**, **left** : posicionamento exato com position.
  * **transform** : realiza transformações (rotate, scale, translate).
  * **transition** : define transições entre estados.
  * **animation** : controla animações (keyframes, animation-name, etc.).
  * **grid-column-gap**, **grid-row-gap** : espaçamento entre colunas e linhas de grade.
  * **grid-template-areas** : nomeia áreas em uma grade.

### texto e fonte

  * **color** : define a cor do texto.
  * **font-family** : especifica a fonte.
  * **font-size** : tamanho do texto.
  * **font-weight** : espessura do texto (normal, bold, 100-900).
  * **font-style** : estilo do texto (normal, italic).
  * **letter-spacing** : espaçamento entre letras.
  * **line-height** : espaçamento entre linhas.
  * **text-align** : alinhamento do texto (left, right, center, justify).
  * **text-decoration** : decorações (underline, overline, line-through).
  * **text-shadow** : sombra ao texto.
  * **word-spacing** : espaçamento entre palavras.
  * **text-transform** : formatação (uppercase, lowercase, capitalize).
  * **white-space** : controle de espaços em branco (normal, nowrap, pre).

### fundo e imagem

  * **background-color** : cor de fundo.
  * **background-image** : imagem de fundo.
  * **background-repeat** : repetição da imagem de fundo.
  * **background-position** : posição da imagem de fundo.
  * **background-size** : tamanho da imagem de fundo.
  * **background-attachment** : movimento da imagem com scroll.
  * **clip-path** : região a ser exibida.
  * **mask** : máscara para o elemento.
  * **object-fit** : ajuste de elementos filhos (img) ao contêiner.
  * **object-position** : posição inicial de elementos dentro do contêiner.

### bordas e sombras

  * **border-radius** : arredonda as bordas.
  * **box-shadow** : sombra ao elemento.
  * **outline** : contorno ao redor do elemento.
  * **outline-offset** : distância do contorno em relação ao elemento.
  * **border-collapse** : colapso de bordas em tabelas.
  * **border-spacing** : espaçamento entre bordas de células de tabela.

### interação e evento

  * **cursor** : tipo de cursor ao passar o mouse.
  * **user-select** : controle de seleção de texto.
  * **resize** : redimensionamento pelo usuário.
  * **appearance** : aparência em relação ao estilo padrão do navegador.
  * **overflow-wrap** : quebra de palavras longas.
  * **word-break** : controle de quebra de palavras.
  * **text-overflow** : comportamento quando o texto não cabe (ellipsis).
  * **animation-delay** : atraso antes da animação.
  * **animation-direction** : direção da animação.
  * **animation-duration** : duração da animação.
  * **animation-fill-mode** : comportamento antes, depois e durante a animação.
  * **animation-iteration-count** : número de reproduções da animação.
  * **animation-name** : nome da chave de animação.
  * **animation-play-state** : execução ou pausa da animação.
  * **animation-timing-function** : velocidade da animação ao longo do tempo.

### outros

  * **opacity** : opacidade do elemento.
  * **filter** : efeitos de filtro (blur, brightness, etc.).
  * **mix-blend-mode** : mistura com o fundo.
  * **backdrop-filter** : efeitos de filtro ao fundo.
  * **isolation** : isolamento em nova camada de composição.
  * **shape-outside** : forma que o conteúdo ao redor deve fluir.
  * **shape-margin** : espaçamento entre o elemento e o conteúdo que flui ao redor.
  * **shape-image-threshold** : opacidade da imagem usada para definir a forma.
  * **shape-border-box**, **shape-padding-box**, **shape-margin-box**, **shape-clip-box** : áreas usadas para calcular a forma.
  * **shape-inside** : forma que o conteúdo dentro deve fluir.
