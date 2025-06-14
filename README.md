# html, css, js, python, flask, django, linux, git e github mais utilizados

## html

### estrutura básica

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

### texto e links

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

### imagens e mídia

  * `<img>`: insere uma imagem.
  * `<svg>`: desenho vetorial.
  * `<canvas>`: área para gráficos dinâmicos.
  * `<video>`: incorpora conteúdo de vídeo.
  * `<audio>`: incorpora conteúdo de áudio.
  * `<source>`: especifica múltiplas fontes para mídia.
  * `<track>`: texto de legenda ou outros para mídia.
  * `<iframe>`: incorpora documento html externo.

### formulários

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

### tabelas

  * `<table>`: define uma tabela.
  * `<tr>`: linha de tabela.
  * `<td>`: célula de dados.
  * `<th>`: célula de cabeçalho.
  * `<thead>`: cabeçalho da tabela.
  * `<tbody>`: corpo da tabela.
  * `<tfoot>`: rodapé da tabela.
  * `<caption>`: título da tabela.

### listas

  * `<ul>`: lista não ordenada.
  * `<ol>`: lista ordenada.
  * `<li>`: item de lista.
  * `<dl>`: lista de definição.
  * `<dt>`: termo da lista de definição.
  * `<dd>`: descrição do termo.

### semântica

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

### layout

  * `<div>`: contêiner genérico.
  * `<span>`: contêiner genérico em linha.
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

### scripts e estilos

  * `<style>`: define estilos css dentro do documento.
  * `<script>`: incorpora ou referencia scripts.
  * `<noscript>`: fornece alternativa quando javascript está desabilitado.
  * `<template>`: contêiner para conteúdo a ser clonado.

### semântica avançada

  * `<dialog>`: diálogo ou janela.
  * `<details>`: conteúdo adicional exibível/collapsível.
  * `<summary>`: título para detalhes.
  * `<menu>`: lista de comandos.
  * `<command>`: comando para invocar ações.
  * `<datalist>`: lista de opções para entrada de dados.
  * `<slot>`: ponto de inserção para conteúdo.
  * `<custom>`: elemento personalizado (web components).

## css

### layout e posicionamento

  * `display`: controla como o elemento é renderizado (block, inline, flex, etc.).
  * `position`: define o posicionamento (relative, absolute, fixed, sticky).
  * `float`: especifica se o elemento deve flutuar (left, right).
  * `clear`: controla o posicionamento em relação a elementos flutuantes (left, right, both).
  * `flex`: propriedades relacionadas ao layout flexível (flex-direction, justify-content, etc.).
  * `grid`: propriedades para criar layouts de grade (grid-template-columns, grid-template-rows, etc.).
  * `column`: cria colunas em um elemento (column-count, column-gap).
  * `overflow`: controla o que acontece quando o conteúdo excede as dimensões (visible, hidden, scroll, auto).
  * `min-width`, `max-width`, `min-height`, `max-height`: definem limites de largura e altura.
  * `width` e `height`: definem a largura e altura exatas.
  * `margin` e `padding`: espaçamento externo e interno.
  * `border`: aplica bordas.
  * `box-sizing`: define como a largura e altura são calculadas (content-box, border-box).
  * `vertical-align`: alinhamento vertical de elementos inline ou tabela.
  * `z-index`: ordem de sobreposição de elementos.
  * `top`, `right`, `bottom`, `left`: posicionamento exato com position.
  * `transform`: realiza transformações (rotate, scale, translate).
  * `transition`: define transições entre estados.
  * `animation`: controla animações (keyframes, animation-name, etc.).
  * `grid-column-gap`, `grid-row-gap`: espaçamento entre colunas e linhas de grade.
  * `grid-template-areas`: nomeia áreas em uma grade.

### texto e fonte

  * `color`: define a cor do texto.
  * `font-family`: especifica a fonte.
  * `font-size`: tamanho do texto.
  * `font-weight`: espessura do texto (normal, bold, 100-900).
  * `font-style`: estilo do texto (normal, italic).
  * `letter-spacing`: espaçamento entre letras.
  * `line-height`: espaçamento entre linhas.
  * `text-align`: alinhamento do texto (left, right, center, justify).
  * `text-decoration`: decorações (underline, overline, line-through).
  * `text-shadow`: sombra ao texto.
  * `word-spacing`: espaçamento entre palavras.
  * `text-transform`: formatação (uppercase, lowercase, capitalize).
  * `white-space`: controle de espaços em branco (normal, nowrap, pre).

### fundo e imagem

  * `background-color`: cor de fundo.
  * `background-image`: imagem de fundo.
  * `background-repeat`: repetição da imagem de fundo.
  * `background-position`: posição da imagem de fundo.
  * `background-size`: tamanho da imagem de fundo.
  * `background-attachment`: movimento da imagem com scroll.
  * `clip-path`: região a ser exibida.
  * `mask`: máscara para o elemento.
  * `object-fit`: ajuste de elementos filhos (img) ao contêiner.
  * `object-position`: posição inicial de elementos dentro do contêiner.

### bordas e sombras

  * `border-radius`: arredonda as bordas.
  * `box-shadow`: sombra ao elemento.
  * `outline`: contorno ao redor do elemento.
  * `outline-offset`: distância do contorno em relação ao elemento.
  * `border-collapse`: colapso de bordas em tabelas.
  * `border-spacing`: espaçamento entre bordas de células de tabela.

### interação e evento

  * `cursor`: tipo de cursor ao passar o mouse.
  * `user-select`: controle de seleção de texto.
  * `resize`: redimensionamento pelo usuário.
  * `appearance`: aparência em relação ao estilo padrão do navegador.
  * `overflow-wrap`: quebra de palavras longas.
  * `word-break`: controle de quebra de palavras.
  * `text-overflow`: comportamento quando o texto não cabe (ellipsis).
  * `animation-delay`: atraso antes da animação.
  * `animation-direction`: direção da animação.
  * `animation-duration`: duração da animação.
  * `animation-fill-mode`: comportamento antes, depois e durante a animação.
  * `animation-iteration-count`: número de reproduções da animação.
  * `animation-name`: nome da chave de animação.
  * `animation-play-state`: execução ou pausa da animação.
  * `animation-timing-function`: velocidade da animação ao longo do tempo.

### outros

  * `opacity`: opacidade do elemento.
  * `filter`: efeitos de filtro (blur, brightness, etc.).
  * `mix-blend-mode`: mistura com o fundo.
  * `backdrop-filter`: efeitos de filtro ao fundo.
  * `isolation`: isolamento em nova camada de composição.
  * `shape-outside`: forma que o conteúdo ao redor deve fluir.
  * `shape-margin`: espaçamento entre o elemento e o conteúdo que flui ao redor.
  * `shape-image-threshold`: opacidade da imagem usada para definir a forma.
  * `shape-border-box`, `shape-padding-box`, `shape-margin-box`, `shape-clip-box`: áreas usadas para calcular a forma.
  * `shape-inside`: forma que o conteúdo dentro deve fluir.

## js

### manipulação do dom

  * `document.getElementById()`: obtém um elemento pelo id.
  * `document.querySelector()`: obtém o primeiro elemento que combina com um seletor css.
  * `document.querySelectorAll()`: obtém todos os elementos que combinam com um seletor css.
  * `element.innerHTML`: obtém ou define o conteúdo html de um elemento.
  * `element.innerText`: obtém ou define o conteúdo de texto de um elemento.
  * `element.setAttribute()`: define o valor de um atributo.
  * `element.getAttribute()`: obtém o valor de um atributo.
  * `element.classList.add()`: adiciona uma classe a um elemento.
  * `element.classList.remove()`: remove uma classe de um elemento.
  * `element.classList.toggle()`: inverte a presença de uma classe.
  * `element.style`: define estilos css inline.
  * `element.appendChild()`: adiciona um nó filho ao final da lista de filhos.
  * `element.removeChild()`: remove um nó filho.
  * `element.insertBefore()`: insere um nó filho antes de um nó existente.
  * `element.replaceChild()`: substitui um nó filho.

### eventos

  * `addEventListener()`: adiciona um ouvinte de evento a um elemento.
  * `removeEventListener()`: remove um ouvinte de evento.
  * `event.preventDefault()`: impede o comportamento padrão de um evento.
  * `event.stopPropagation()`: impede a propagação do evento.
  * `element.onclick`: manipulador de evento para cliques.
  * `element.onchange`: manipulador de evento para alterações em elementos de formulário.
  * `element.onsubmit`: manipulador de evento para submissão de formulário.
  * `element.onmouseover` e `element.onmouseout`: manipuladores de evento para movimento do mouse.

### armazenamento e requisições

  * `localStorage.setItem()`: armazena dados no armazenamento local.
  * `localStorage.getItem()`: recupera dados do armazenamento local.
  * `localStorage.removeItem()`: remove dados do armazenamento local.
  * `sessionStorage.setItem()`: armazena dados na sessão atual.
  * `sessionStorage.getItem()`: recupera dados da sessão atual.
  * `sessionStorage.removeItem()`: remove dados da sessão atual.
  * `fetch()`: realiza requisições http.

### arrays e objetos

  * `array.map()`: cria um novo array aplicando uma função a cada elemento.
  * `array.filter()`: cria um novo array com elementos que passam em um teste.
  * `array.reduce()`: reduz um array a um único valor.
  * `array.forEach()`: executa uma função para cada elemento.
  * `array.push()`: adiciona elementos ao final do array.
  * `array.pop()`: remove o último elemento do array.
  * `array.shift()`: remove o primeiro elemento do array.
  * `array.unshift()`: adiciona elementos ao início do array.
  * `array.splice()`: adiciona/remova elementos em um índice específico.
  * `array.indexOf()`: retorna o índice do primeiro elemento com um valor especificado.
  * `array.includes()`: verifica se um array contém um determinado valor.
  * `object.keys()`: retorna um array com as chaves de um objeto.
  * `object.values()`: retorna um array com os valores de um objeto.
  * `object.entries()`: retorna um array com os pares chave-valor de um objeto.
  * `object.hasOwnProperty()`: verifica se um objeto possui uma propriedade própria.

### strings e números

  * `string.split()`: divide uma string em um array de substrings.
  * `string.replace()`: substitui uma substring por outra.
  * `string.includes()`: verifica se uma string contém um determinado valor.
  * `string.trim()`: remove espaços em branco no início e no final de uma string.
  * `string.toUpperCase()` e `string.toLowerCase()`: converte strings para maiúsculas ou minúsculas.
  * `number.toFixed()`: formata um número usando notação de ponto fixo.
  * `number.toLocaleString()`: retorna uma string com a representação localizada do número.
  * `parseInt()` e `parseFloat()`: converte strings para números inteiros ou de ponto flutuante.

### datas e tempo

  * `new Date()`: cria um objeto data.
  * `date.getFullYear()`: obtém o ano.
  * `date.getMonth()`: obtém o mês.
  * `date.getDate()`: obtém o dia do mês.
  * `date.getHours()`: obtém as horas.
  * `date.getMinutes()`: obtém os minutos.
  * `date.getSeconds()`: obtém os segundos.
  * `date.getTime()`: obtém o número de milissegundos desde 1/1/1970.
  * `date.setDate()`: define o dia do mês.
  * `date.setFullYear()`: define o ano.
  * `date.setHours()`: define as horas.
  * `date.setMinutes()`: define os minutos.
  * `date.setSeconds()`: define os segundos.

### funções e callbacks

  * `function(){}): define uma função.
  * `arrow function ( () => {} )`: define uma função de seta.
  * `setTimeout()`: executa uma função após um determinado número de milissegundos.
  * `setInterval()`: executa uma função periodicamente.
  * `clearTimeout()`: cancela um timeout definido com setTimeout().
  * `clearInterval()`: cancela um intervalo definido com setInterval().
  * `Promise()`: representa uma operação assíncrona.
  * `then()`: define a função de callback para quando a promessa for resolvida.
  * `catch()`: define a função de callback para quando a promessa for rejeitada.

### outros

  * `JSON.parse()`: converte uma string json em um objeto javascript.
  * `JSON.stringify()`: converte um objeto javascript em uma string json.
  * `Math.random()`: retorna um número pseudoaleatório entre 0 e 1.
  * `Math.floor()`: arredonda um número para baixo.
  * `Math.ceil()`: arredonda um número para cima.
  * `console.log()`: exibe uma mensagem no console.
  * `try...catch`: captura e trata exceções.
  * `typeof`: determina o tipo de uma variável.
  * `instanceof`: verifica se um objeto é uma instância de uma classe.

## python

### estrutura básica

  * `print()`: imprime um valor na saída padrão.
  * `input()`: lê uma linha de entrada do usuário.
  * `len()`: retorna o número de itens de um objeto.
  * `range()`: retorna um iterador de números.
  * `list()`: cria uma lista.
  * `tuple()`: cria uma tupla.
  * `dict()`: cria um dicionário.
  * `set()`: cria um conjunto.
  * `str()`: converte um valor para string.
  * `int()`: converte um valor para inteiro.
  * `float()`: converte um valor para ponto flutuante.
  * `bool()`: converte um valor para booleano.

### controle de fluxo

  * `if`, `elif`, `else`: estruturas condicionais.
  * `for`: loop para iterar sobre uma sequência.
  * `while`: loop enquanto uma condição for verdadeira.
  * `break`: interrompe o loop.
  * `continue`: pula para a próxima iteração do loop.
  * `pass`: uma operação nula.

### funções e módulos

  * `def`: define uma função.
  * `return`: retorna um valor de uma função.
  * `lambda`: define uma pequena função anônima.
  * `import`: importa um módulo.
  * `from...import`: importa partes específicas de um módulo.
  * `as`: define um alias para um módulo ou função.

### manipulação de arquivos

  * `open()`: abre um arquivo.
  * `read()`: lê o conteúdo de um arquivo.
  * `write()`: escreve no arquivo.
  * `close()`: fecha um arquivo.
  * `with`: gerenciador de contexto para arquivos.

### listas e dicionários

  * `append()`: adiciona um elemento ao final da lista.
  * `remove()`: remove um elemento da lista.
  * `pop()`: remove e retorna o último elemento da lista.
  * `keys()`: retorna as chaves de um dicionário.
  * `values()`: retorna os valores de um dicionário.
  * `items()`: retorna os pares chave-valor de um dicionário.
  * `get()`: retorna o valor de uma chave no dicionário.
  * `update()`: atualiza o dicionário com elementos de outro dicionário.

### exceções

  * `try`: bloco de código a ser testado para exceções.
  * `except`: bloco de código a ser executado se uma exceção ocorrer.
  * `finally`: bloco de código a ser executado independentemente do resultado.
  * `raise`: lança uma exceção.
  * `assert`: verifica se uma condição é verdadeira.

## flask

### aplicação básica

  * `Flask()`: cria uma instância do aplicativo flask.
  * `app.route()`: decoraador para associar uma função a uma url.
  * `render_template()`: renderiza um template.
  * `request`: objeto que contém os dados da requisição.
  * `redirect()`: redireciona o usuário para outra url.
  * `url_for()`: gera a url para uma função de visualização.
  * `flash()`: envia uma mensagem para a próxima solicitação.
  * `session`: objeto para armazenar dados entre solicitações.
  * `g`: objeto para variáveis globais do contexto da aplicação.
  * `app.config()`: configura variáveis de configuração da aplicação.

### bancos de dados

  * `SQLAlchemy()`: cria uma instância do orm sqlalchemy.
  * `db.create_all()`: cria todas as tabelas no banco de dados.
  * `db.session.add()`: adiciona um objeto ao banco de dados.
  * `db.session.commit()`: salva as alterações no banco de dados.
  * `db.session.rollback()`: desfaz as alterações não salvas.
  * `db.session.delete()`: remove um objeto do banco de dados.
  * `query.all()`: retorna todos os resultados da consulta.
  * `query.filter_by()`: filtrar resultados com base em critérios.
  * `query.get()`: obtém um objeto pelo id.
  * `query.first()`: retorna o primeiro resultado da consulta.

### autenticação

  * `LoginManager()`: gerencia o login do usuário.
  * `login_user()`: registra o usuário como logado.
  * `logout_user()`: desloga o usuário.
  * `login_required`: decoraador para proteger rotas.
  * `current_user`: objeto que representa o usuário atualmente logado.
  * `UserMixin`: classe base para objetos de usuário.
  * `user_loader()`: carrega o usuário pelo id.

## django

### aplicação básica

  * `django-admin startproject`: cria um novo projeto django.
  * `python manage.py startapp`: cria um novo aplicativo dentro do projeto.
  * `python manage.py runserver`: inicia o servidor de desenvolvimento.
  * `python manage.py makemigrations`: cria migrações para alterações no modelo.
  * `python manage.py migrate`: aplica migrações ao banco de dados.
  * `python manage.py createsuperuser`: cria um usuário administrador.
  * `urls.py`: define as rotas da aplicação.
  * `views.py`: contém as funções ou classes que lidam com as solicitações.
  * `templates/`: diretório para arquivos de template.
  * `static/`: diretório para arquivos estáticos (css, js, imagens).
  * `settings.py`: configurações do projeto django.
  * `wsgi.py`: ponto de entrada wsgi para o projeto.
  * `asgi.py`: ponto de entrada asgi para o projeto.

### modelos

  * `models.Model`: classe base para modelos.
  * `CharField()`: campo de texto com limite de caracteres.
  * `TextField()`: campo de texto sem limite.
  * `IntegerField()`: campo de número inteiro.
  * `FloatField()`: campo de número de ponto flutuante.
  * `BooleanField()`: campo booleano.
  * `DateField()`: campo de data.
  * `DateTimeField()`: campo de data e hora.
  * `ForeignKey()`: relação muitos-para-um.
  * `ManyToManyField()`: relação muitos-para-muitos.
  * `OneToOneField()`: relação um-para-um.
  * `save()`: salva o objeto no banco de dados.
  * `delete()`: remove o objeto do banco de dados.
  * `objects.all()`: retorna todos os objetos do modelo.
  * `objects.filter()`: retorna objetos que correspondem aos critérios.
  * `objects.get()`: retorna um único objeto que corresponde aos critérios.
  * `objects.create()`: cria um novo objeto e o salva no banco de dados.

### formulários

  * `forms.Form`: classe base para formulários.
  * `forms.ModelForm`: cria um formulário a partir de um modelo.
  * `CharField()`: campo de texto.
  * `EmailField()`: campo de e-mail.
  * `IntegerField()`: campo de número inteiro.
  * `BooleanField()`: campo booleano.
  * `DateField()`: campo de data.
  * `DateTimeField()`: campo de data e hora.
  * `ChoiceField()`: campo de seleção.
  * `ModelChoiceField()`: campo de seleção baseado em um modelo.
  * `form.is_valid()`: verifica se o formulário é válido.
  * `form.cleaned_data`: dados do formulário validados.
  * `form.save()`: salva o formulário no banco de dados.

### autenticação

  * `User`: modelo padrão de usuário.
  * `authenticate()`: verifica as credenciais do usuário.
  * `login()`: registra o usuário como logado.
  * `logout()`: desloga o usuário.
  * `LoginRequiredMixin`: decoraador para proteger views.
  * `logout_then_login()`: desloga o usuário e redireciona para a página de login.
  * `password_change()`: view para alterar a senha.
  * `password_reset()`: view para redefinir a senha.

### administração

  * `admin.site.register()`: registra um modelo no admin.
  * `admin.ModelAdmin`: classe para personalizar a aparência do admin.
  * `list_display`: define os campos exibidos na lista de objetos.
  * `search_fields`: define os campos pesquisáveis.
  * `list_filter`: define os campos para filtragem.
  * `fieldsets`: organiza os campos na página de edição.

### templates

  * `{% extends %}`: herda um template base.
  * `{% block %}`: define um bloco que pode ser sobrescrito.
  * `{% include %}`: inclui um template dentro de outro.
  * `{% for %}`: loop para iterar sobre uma sequência.
  * `{% if %}`: condição para exibir conteúdo.
  * `{{ variable }}`: exibe o valor de uma variável.
  * `{% static %}`: retorna a url de um arquivo estático.
  * `{% url %}`: gera a url para uma view nomeada.
  * `{% csrf_token %}`: token de proteção contra csrf em formulários.

###中间件

  * `MIDDLEWARE`: lista de middlewares configurados no projeto.
  * `AuthenticationMiddleware`: gerencia a autenticação do usuário.
  * `SessionMiddleware`: gerencia sessões de usuário.
  * `CommonMiddleware`: manipula redirecionamentos e cabeçalhos comuns.
  * `CsrfViewMiddleware`: protege contra ataques csrf.
  * `SecurityMiddleware`: adiciona cabeçalhos de segurança.

### configurações

  * `DEBUG`: ativa ou desativa o modo de depuração.
  * `ALLOWED_HOSTS`: lista de hosts permitidos.
  * `INSTALLED_APPS`: lista de aplicativos instalados.
  * `DATABASES`: configurações do banco de dados.
  * `TEMPLATES`: configurações dos templates.
  * `STATICFILES_DIRS`: diretórios de arquivos estáticos.
  * `MEDIA_ROOT`: diretório para arquivos de mídia.
  * `MEDIA_URL`: url base para arquivos de mídia.

### sinalização

  * `signals.pre_save`: sinal enviado antes de salvar um objeto.
  * `signals.post_save`: sinal enviado após salvar um objeto.
  * `signals.pre_delete`: sinal enviado antes de excluir um objeto.
  * `signals.post_delete`: sinal enviado após excluir um objeto.
  * `signals.m2m_changed`: sinal enviado quando um relacionamento muitos-para-muitos é alterado.
  * `@receiver()`: decorador para receber um sinal.
  * `send()`: envia um sinal.

### serialização

  * `serializers.serialize()`: serializa objetos django em json.
  * `serializers.deserialize()`: desserializa json em objetos django.
  * `serializers.Serializer`: classe base para serializadores.
  * `serializers.ModelSerializer`: serializador baseado em modelos.
  * `is_valid()`: verifica se os dados são válidos.
  * `save()`: salva os dados serializados.

### api (django rest framework)

  * `APIView`: classe base para views de api.
  * `APIView.get()`, `APIView.post()`, etc.: métodos http para views de api.
  * `APIView.mixins`: mixins para operações de api.
  * `generics.ListAPIView`: view genérica para listar objetos.
  * `generics.CreateAPIView`: view genérica para criar objetos.
  * `generics.RetrieveAPIView`: view genérica para exibir um objeto.
  * `generics.UpdateAPIView`: view genérica para atualizar um objeto.
  * `generics.DestroyAPIView`: view genérica para excluir um objeto.
  * `generics.ListCreateAPIView`: view genérica para listar e criar objetos.
  * `generics.RetrieveUpdateAPIView`: view genérica para exibir e atualizar um objeto.
  * `generics.RetrieveDestroyAPIView`: view genérica para exibir e excluir um objeto.
  * `generics.RetrieveUpdateDestroyAPIView`: view genérica para exibir, atualizar e excluir um objeto.
  * `permissions.IsAuthenticated`: permissão para usuários autenticados.
  * `permissions.IsAdminUser`: permissão para usuários administradores.
  * `permissions.AllowAny`: permissão para qualquer usuário.
  * `authentication.SessionAuthentication`: autenticação baseada em sessão.
  * `authentication.BasicAuthentication`: autenticação básica.
  * `authentication.TokenAuthentication`: autenticação por token.
  * `pagination.PageNumberPagination`: paginação baseada em números de página.
  * `pagination.LimitOffsetPagination`: paginação com limite e offset.
  * `filters.SearchFilter`: filtro de pesquisa.
  * `filters.OrderingFilter`: filtro de ordenação.
  * `serializers.ModelSerializer`: serializador baseado em modelos.
  * `serializers.HyperlinkedModelSerializer`: serializador com links hiperreferenciados.
  * `serializers.PrimaryKeyRelatedField`: campo para objetos relacionados por chave primária.
  * `serializers.StringRelatedField`: campo para objetos relacionados como string.
  * `serializers ReadOnlyField`: campo somente leitura.
  * `serializers.HiddenField`: campo oculto.
  * `serializers.SerializerMethodField`: campo definido por um método da classe serializer.

### cache

  * `cache.get()`: obtém um valor do cache.
  * `cache.set()`: define um valor no cache.
  * `cache.delete()`: remove um valor do cache.
  * `cache.clear()`: limpa todo o cache.
  * `cache.add()`: adiciona um valor ao cache se ele não existir.
  * `cache.get_or_set()`: obtém um valor do cache ou define um novo se ele não existir.
  * `@cache_page()`: decoraador para cache de views.
  * `CACHE_MIDDLEWARE_ALIAS`: alias do cache para o middleware.
  * `CACHE_MIDDLEWARE_SECONDS`: tempo de vida do cache em segundos.
  * `CACHE_MIDDLEWARE_KEY_PREFIX`: prefixo para a chave do cache.

### testes

  * `TestCase`: classe base para testes.
  * `TransactionTestCase`: classe base para testes que requerem controle de transações.
  * `Client`: simula um cliente http para testes.
  * `RequestFactory`: cria instâncias de request para testes.
  * `assertEqual()`: verifica se dois valores são iguais.
  * `assertNotEqual()`: verifica se dois valores são diferentes.
  * `assertTrue()`: verifica se um valor é verdadeiro.
  * `assertFalse()`: verifica se um valor é falso.
  * `assertIs()`: verifica se dois valores são o mesmo objeto.
  * `assertIsNot()`: verifica se dois valores não são o mesmo objeto.
  * `assertIsNone()`: verifica se um valor é none.
  * `assertIsNotNone()`: verifica se um valor não é none.
  * `assertIn()`: verifica se um valor está em uma sequência.
  * `assertNotIn()`: verifica se um valor não está em uma sequência.
  * `assertGreater()`: verifica se um valor é maior que outro.
  * `assertGreaterEqual()`: verifica se um valor é maior ou igual a outro.
  * `assertLess()`: verifica se um valor é menor que outro.
  * `assertLessEqual()`: verifica se um valor é menor ou igual a outro.
  * `assertRegex()`: verifica se uma string corresponde a uma regex.
  * `assertNotRegex()`: verifica se uma string não corresponde a uma regex.
  * `assertAlmostEqual()`: verifica se dois valores são quase iguais.
  * `assertNotAlmostEqual()`: verifica se dois valores não são quase iguais.
  * `assertRaises()`: verifica se uma exceção é levantada.
  * `assertRedirects()`: verifica se uma resposta é um redirecionamento.
  * `assertContains()`: verifica se uma resposta contém um certo conteúdo.
  * `assertNotContains()`: verifica se uma resposta não contém um certo conteúdo.
  * `assertTemplateUsed()`: verifica se um template foi usado na resposta.
  * `assertTemplateNotUsed()`: verifica se um template não foi usado na resposta.

### signals

  * `pre_init`: sinal enviado antes de inicializar um objeto.
  * `post_init`: sinal enviado após inicializar um objeto.
  * `pre_save`: sinal enviado antes de salvar um objeto.
  * `post_save`: sinal enviado após salvar um objeto.
  * `pre_delete`: sinal enviado antes de excluir um objeto.
  * `post_delete`: sinal enviado após excluir um objeto.
  * `m2m_changed`: sinal enviado quando um relacionamento muitos-para-muitos é alterado.
  * `class_prepared`: sinal enviado quando uma classe é preparada.
  * `request_started`: sinal enviado no início de uma solicitação.
  * `request_finished`: sinal enviado no final de uma solicitação.
  * `got_request_exception`: sinal enviado quando uma exceção ocorre durante uma solicitação.
  * `setting_changed`: sinal enviado quando uma configuração é alterada.
  * `template_rendered`: sinal enviado quando um template é renderizado.
  * `response_returned`: sinal enviado quando uma resposta é retornada.
  * `connect()`: conecta uma função a um sinal.
  * `disconnect()`: desconecta uma função de um sinal.
  * `send()`: envia um sinal.

### middleware

  * `AuthenticationMiddleware`: gerencia a autenticação do usuário.
  * `SessionMiddleware`: gerencia sessões de usuário.
  * `CommonMiddleware`: manipula redirecionamentos e cabeçalhos comuns.
  * `CsrfViewMiddleware`: protege contra ataques csrf.
  * `SecurityMiddleware`: adiciona cabeçalhos de segurança.
  * `process_request()`: método chamado antes de processar a solicitação.
  * `process_view()`: método chamado antes de chamar a view.
  * `process_template_response()`: método chamado após a view retornar uma resposta de template.
  * `process_response()`: método chamado após a view retornar uma resposta.
  * `process_exception()`: método chamado se uma exceção ocorrer durante a view.

### decorators

  * `login_required()`: decoraador para views que requerem autenticação.
  * `permission_required()`: decoraador para views que requerem permissão específica.
  * `staff_member_required()`: decoraador para views que requerem usuários staff.
  * `cache_page()`: decoraador para cache de views.
  * `never_cache()`: decoraador para evitar cache de views.
  * `gzip_page()`: decoraador para comprimir a resposta.
  * `require_http_methods()`: decoraador para restringir métodos http.
  * `csrf_exempt()`: decoraador para isentar a view do csrf.
  * `vary_on_cookie()`: decoraador para adicionar cabeçalho vary com base no cookie.
  * `vary_on_headers()`: decoraador para adicionar cabeçalho vary com base em cabeçalhos específicos.
  * `etag()`: decoraador para adicionar cabeçalho etag.
  * `last_modified()`: decoraador para adicionar cabeçalho last-modified.
  * `condition()`: decoraador para adicionar cabeçalhos etag e last-modified.
  * `xframe_options_exempt()`: decoraador para isentar a view do x-frame-options.
  * `xframe_options_sameorigin()`: decoraador para configurar x-frame-options como sameorigin.
  * `xframe_options_deny()`: decoraador para configurar x-frame-options como deny.

### utilities

  * `reverse()`: retorna a url para uma view nomeada.
  * `reverse_lazy()`: versão lazy de reverse.
  * `get_object_or_404()`: retorna um objeto ou levanta um erro 404.
  * `get_list_or_404()`: retorna uma lista de objetos ou levanta um erro 404.
  * `redirect()`: redireciona o usuário para outra url.
  * `render()`: renderiza um template e retorna uma resposta.
  * `resolve()`: resolve uma url e retorna a view associada.
  * `is_safe_url()`: verifica se uma url é segura para redirecionamento.
  * `lazy()`: permite a chamada preguiçosa de uma função.
  * `format_html()`: formata strings com html.
  * `format_html_join()`: junta múltiplas strings html.
  * `mark_safe()`: marca uma string como segura para html.
  * `mark_for_escaping()`: marca uma string para escape.
  * `conditional_escape()`: escapa uma string condicionalmente.
  * `escape()`: escapa uma string para html.
  * `linebreaks()`: converte quebras de linha em tags html.
  * `truncatechars()`: truncada uma string em um certo número de caracteres.
  * `truncatewords()`: truncada uma string em um certo número de palavras.
  * `urlize()`: converte urls em links.
  * `urlencode()`: codifica uma string para url.
  * `slugify()`: converte uma string em um slug.
  * `timesince()`: retorna uma string indicando quanto tempo se passou desde uma data.
  * `timeuntil()`: retorna uma string indicando quanto tempo falta para uma data.
  * `localize()`: formata uma data, hora ou número para o formato local.
  * `unlocalize()`: remove a formatação local de uma data, hora ou número.
  * `date()`: formata uma data.
  * `time()`: formata uma hora.
  * `number_format()`: formata um número.
  * `intcomma()`: adiciona vírgulas a números inteiros.
  * `intword()`: converte números grandes em expressões como 1.5 milhão.
  * `apnumber()`: converte números em expressões como "um", "dois", etc.
  * `ordinal()`: converte números em ordinais como "1º", "2º", etc.
  * `widthratio()`: calcula a porcentagem de uma razão.
  * `default()`: retorna o valor se ele não for vazio.
  * `default_if_none()`: retorna o valor se ele não for none.
  * `divisibleby()`: verifica se um valor é divisível por outro.
  * `yesno()`: exibe "sim" ou "não" com base em um valor booleano.
  * `filesizeformat()`: formata um tamanho de arquivo em bytes para uma string legível.
  * `pluralize()`: adiciona sufixos de pluralização com base no valor.
  * `phone2android()`: converte números de telefone para o formato android.
  * `iri_to_uri()`: converte uma iri para uri.
  * `uri_to_iri()`: converte uma uri para iri.
  * `get_random_string()`: gera uma string aleatória.
  * `constant_time_compare()`: compara duas strings de maneira segura contra ataques de tempo.
  * `make_password()`: cria um hash de senha.
  * `check_password()`: verifica se uma senha corresponde a um hash.
  * `is_password_usable()`: verifica se um hash de senha é usável.
  * `password_changed()`: sinal enviado quando uma senha é alterada.
  * `password_reset()`: sinal enviado quando uma senha é redefinida.
  * `user_logged_in()`: sinal enviado quando um usuário é logado.
  * `user_logged_out()`: sinal enviado quando um usuário é deslogado.
  * `user_login_failed()`: sinal enviado quando uma tentativa de login falha.
  * `generate_jwt()`: gera um token jwt.
  * `decode_jwt()`: decodifica um token jwt.
  * `get_jwt_secret()`: retorna a chave secreta para jwt.
  * `get_jwt_expiration()`: retorna o tempo de expiração para jwt.
  * `get_jwt_algorithm()`: retorna o algoritmo para jwt.
  * `get_jwt_issuer()`: retorna o emissor para jwt.
  * `get_jwt_audience()`: retorna a audiência para jwt.
  * `get_jwt_payload()`: retorna o payload para jwt.
  * `get_jwt_header()`: retorna o cabeçalho para jwt.
  * `get_jwt_signature()`: retorna a assinatura para jwt.
  * `get_jwt_token()`: retorna o token jwt.
  * `get_jwt_user()`: retorna o usuário associado ao token jwt.
  * `get_jwt_expiry()`: retorna a data de expiração do token jwt.
  * `get_jwt_issued_at()`: retorna a data de emissão do token jwt.
  * `get_jwt_nonce()`: retorna o nonce do token jwt.
  * `get_jwt_iat()`: retorna o tempo de emissão do token jwt.
  * `get_jwt_exp()`: retorna o tempo de expiração do token jwt.
  * `get_jwt_nbf()`: retorna o tempo antes do qual o token jwt não é válido.
  * `get_jwt_jti()`: retorna o identificador do token jwt.
  * `get_jwt_aud()`: retorna a audiência do token jwt.
  * `get_jwt_iss()`: retorna o emissor do token jwt.
  * `get_jwt_sub()`: retorna o assunto do token jwt.
  * `get_jwt_typ()`: retorna o tipo do token jwt.
  * `get_jwt_cty()`: retorna o tipo de conteúdo do token jwt.
  * `get_jwt_kid()`: retorna o identificador da chave do token jwt.
  * `get_jwt_x5c()`: retorna a cadeia de certificados x509 do token jwt.
  * `get_jwt_x5t()`: retorna o identificador thumbprint do certificado x509 do token jwt.
  * `get_jwt_x5u()`: retorna a url do certificado x509 do token jwt.
  * `get_jwt_jku()`: retorna a url da chave json do token jwt.
  * `get_jwt_jwk()`: retorna a chave json do token jwt.

### management commands

  * `python manage.py runserver`: inicia o servidor de desenvolvimento.
  * `python manage.py shell`: inicia um shell interativo.
  * `python manage.py dbshell`: inicia um shell do banco de dados.
  * `python manage.py migrate`: aplica migrações ao banco de dados.
  * `python manage.py makemigrations`: cria migrações para alterações no modelo.
  * `python manage.py createsuperuser`: cria um usuário administrador.
  * `python manage.py changepassword`: altera a senha de um usuário.
  * `python manage.py createsuperuser`: cria um usuário administrador.
  * `python manage.py reset_password`: redefine a senha de um usuário.
  * `python manage.py sendtestemail`: envia um email de teste.
  * `python manage.py check`: verifica o projeto para problemas.
  * `python manage.py diffsettings`: exibe as configurações diferentes das padrões.
  * `python manage.py dumpdata`: exporta dados do banco de dados para json.
  * `python manage.py loaddata`: importa dados do json para o banco de dados.
  * `python manage.py flush`: remove todos os dados do banco de dados.
  * `python manage.py sqlflush`: exibe o sql para flush do banco de dados.
  * `python manage.py sqlmigrate`: exibe o sql para uma migração.
  * `python manage.py sqlsequencereset`: exibe o sql para redefinir sequências.
  * `python manage.py squashmigrations`: squash migrations.
  * `python manage.py test`: executa testes.
  * `python manage.py testserver`: inicia um servidor de teste.
  * `python manage.py collectstatic`: coleta arquivos estáticos.
  * `python manage.py findstatic`: encontra arquivos estáticos.
  * `python manage.py runfcgi`: inicia um servidor fastcgi.
  * `python manage.py startapp`: cria um novo aplicativo.
  * `python manage.py startproject`: cria um novo projeto.
  * `python manage.py syncdb`: antigo comando para sincronizar o banco de dados.
  * `python manage.py inspectdb`: inspeciona o banco de dados e gera modelos.
  * `python manage.py shell_plus`: inicia um shell interativo com modelos carregados.
  * `python manage.py createcachetable`: cria uma tabela de cache.
  * `python manage.py clearcache`: limpa o cache.
  * `python manage.py compilemessages`: compila arquivos de mensagem.
  * `python manage.py makemessages`: cria arquivos de mensagem.
  * `python manage.py runscript`: executa um script.
  * `python manage.py send_mail`: envia um email.
  * `python manage.py sql`: exibe o sql para modelos.
  * `python manage.py validate`: antigo comando para validar modelos.
  * `python manage.py graph_models`: gera um diagrama de modelos.
  * `python manage.py show_urls`: exibe as urls definidas.
  * `python manage.py show_template_tags`: exibe os template tags disponíveis.
  * `python manage.py show_settings`: exibe as configurações atuais.
  * `python manage.py show_migrations`: exibe as migrações disponíveis.
  * `python manage.py show_migration_sql`: exibe o sql para migrações.
  * `python manage.py show_schema`: exibe o schema do banco de dados.
  * `python manage.py show_staticfiles`: exibe os arquivos estáticos coletados.
  * `python manage.py show_media`: exibe os arquivos de mídia.
  * `python manage.py show_fixture`: exibe os dados de um fixture.
  * `python manage.py show_template`: exibe o conteúdo de um template.
  * `python manage.py show_context`: exibe o contexto de um template.
  * `python manage.py show_serializers`: exibe os serializadores disponíveis.
  * `python manage.py show_views`: exibe as views disponíveis.
  * `python manage.py show_forms`: exibe os formulários disponíveis.
  * `python manage.py show_models`: exibe os modelos disponíveis.
  * `python manage.py show_admin`: exibe as configurações do admin.

### sitemaps

  * `Sitemap`: classe base para sitemaps.
  * `GenericSitemap`: sitemap genérica para objetos de modelo.
  * `views.sitemap()`: view para gerar um sitemap.
  * `urls.py`: define as urls para sitemaps.
  * `SITEMAPITEMS`: configuração para sitemaps.
  * `sitemap_index()`: view para gerar um índice de sitemaps.
  * `sitemap_section()`: view para gerar uma seção de sitemap.
  * `sitemap_lastmod()`: view para gerar a última modificação de um sitemap.
  * `sitemap_location()`: view para gerar a localização de um sitemap.
  * `sitemap_priority()`: view para gerar a prioridade de um sitemap.
  * `sitemap_changefreq()`: view para gerar a frequência de mudança de um sitemap.
  * `sitemap_alternate()`: view para gerar sitemaps alternativos.
  * `sitemap_ping()`: view para pingar o google para atualizar o sitemap.
  * `Sitemap.ping_google()`: método para pingar o google.

### syndication

  * `Feed`: classe base para feeds.
  * `views.feed()`: view para gerar um feed.
  * `feeds.RssFeed`: feed rss.
  * `feeds.AtomFeed`: feed atom.
  * `Item`: classe para itens de feed.
  * `item_title()`: retorna o título de um item.
  * `item_description()`: retorna a descrição de um item.
  * `item_link()`: retorna o link de um item.
  * `item_author_name()`: retorna o nome do autor de um item.
  * `item_author_email()`: retorna o email do autor de um item.
  * `item_author_link()`: retorna o link do autor de um item.
  * `item_pubdate()`: retorna a data de publicação de um item.
  * `item_updateddate()`: retorna a data de atualização de um item.
  * `item_categories()`: retorna as categorias de um item.
  * `item_enclosure()`: retorna a encilose de um item.
  * `item_guid()`: retorna o guid de um item.
  * `item_comments()`: retorna o link para comentários de um item.
  * `item_comment_link()`: retorna o link para comentários de um item.
  * `item_comment_count()`: retorna o número de comentários de um item.
  * `item_comments_feed()`: retorna o feed de comentários de um item.
  * `item_comments_atom()`: retorna o feed atom de comentários de um item.
  * `item_comments_rss()`: retorna o feed rss de comentários de um item.
  * `item_comment_form()`: retorna o formulário de comentários de um item.
  * `item_comment_posted()`: retorna se um comentário foi postado para um item.
  * `item_comment_moderated()`: retorna se um comentário foi moderado para um item.
  * `item_comment_approved()`: retorna se um comentário foi aprovado para um item.
  * `item_comment_spam()`: retorna se um comentário foi marcado como spam para um item.
  * `item_comment_ham()`: retorna se um comentário foi marcado como ham para um item.
  * `item_comment_deleted()`: retorna se um comentário foi deletado para um item.
  * `item_comment_hidden()`: retorna se um comentário foi oculto para um item.
  * `item_comment_blocked()`: retorna se um comentário foi bloqueado para um item.
  * `item_comment_unblocked()`: retorna se um comentário foi desbloqueado para um item.
  * `item_comment_read()`: retorna se um comentário foi lido para um item.
  * `item_comment_unread()`: retorna se um comentário foi não lido para um item.
  * `item_comment_flagged()`: retorna se um comentário foi flagrado para um item.
  * `item_comment_unflagged()`: retorna se um comentário foi desflaggado para um item.
  * `item_comment_moved()`: retorna se um comentário foi movido para um item.
  * `item_comment_sticky()`: retorna se um comentário foi definido como sticky para um item.
  * `item_comment_unsticky()`: retorna se um comentário foi removido como sticky para um item.
  * `item_comment_status()`: retorna o status de um comentário para um item.
  * `item_comment_status_changed()`: retorna se o status de um comentário foi alterado para um item.
  * `item_comment_status_set()`: retorna se o status de um comentário foi definido para um item.
  * `item_comment_status_unset()`: retorna se o status de um comentário foi removido para um item.
  * `item_comment_status_approved()`: retorna se o status de um comentário foi aprovado para um item.
  * `item_comment_status_spam()`: retorna se o status de um comentário foi spam para um item.
  * `item_comment_status_ham()`: retorna se o status de um comentário foi ham para um item.
  * `item_comment_status_deleted()`: retorna se o status de um comentário foi deletado para um item.
  * `item_comment_status_hidden()`: retorna se o status de um comentário foi oculto para um item.
  * `item_comment_status_blocked()`: retorna se o status de um comentário foi bloqueado para um item.
  * `item_comment_status_unblocked()`: retorna se o status de um comentário foi desbloqueado para um item.
  * `item_comment_status_read()`: retorna se o status de um comentário foi lido para um item.
  * `item_comment_status_unread()`: retorna se o status de um comentário foi não lido para um item.
  * `item_comment_status_flagged()`: retorna se o status de um comentário foi flagrado para um item.
  * `item_comment_status_unflagged()`: retorna se o status de um comentário foi desflaggado para um item.
  * `item_comment_status_moved()`: retorna se o status de um comentário foi movido para um item.
  * `item_comment_status_sticky()`: retorna se o status de um comentário foi definido como sticky para um item.
  * `item_comment_status_unsticky()`: retorna se o status de um comentário foi removido como sticky para um item.
  * `item_comment_status_moderated()`: retorna se o status de um comentário foi moderado para um item.
  * `item_comment_status_approved()`: retorna se o status de um comentário foi aprovado para um item.
  * `item_comment_status_spam()`: retorna se o status de um comentário foi spam para um item.
  * `item_comment_status_ham()`: retorna se o status de um comentário foi ham para um item.
  * `item_comment_status_deleted()`: retorna se o status de um comentário foi deletado para um item.
  * `item_comment_status_hidden()`: retorna se o status de um comentário foi oculto para um item.
  * `item_comment_status_blocked()`: retorna se o status de um comentário foi bloqueado para um item.
  * `item_comment_status_unblocked()`: retorna se o status de um comentário foi desbloqueado para um item.
  * `item_comment_status_read()`: retorna se o status de um comentário foi lido para um item.
  * `item_comment_status_unread()`: retorna se o status de um comentário foi não lido para um item.
  * `item_comment_status_flagged()`: retorna se o status de um comentário foi flagrado para um item.
  * `item_comment_status_unflagged()`: retorna se o status de um comentário foi desflaggado para um item.
  * `item_comment_status_moved()`: retorna se o status de um comentário foi movido para um item.
  * `item_comment_status_sticky()`: retorna se o status de um comentário foi definido como sticky para um item.
  * `item_comment_status_unsticky()`: retorna se o status de um comentário foi removido como sticky para um item.
  * `item_comment_status_moderated()`: retorna se o status de um comentário foi moderado para um item.
  * `item_comment_status_approved()`: retorna se o status de um comentário foi aprovado para um item.
  * `item_comment_status_spam()`: retorna se o status de um comentário foi spam para um item.
  * `item_comment_status_ham()`: retorna se o status de um comentário foi ham para um item.
  * `item_comment_status_deleted()`: retorna se o status de um comentário foi deletado para um item.
  * `item_comment_status_hidden()`: retorna se o status de um comentário foi oculto para um item.
  * `item_comment_status_blocked()`: retorna se o status de um comentário foi bloqueado para um item.
  * `item_comment_status_unblocked()`: retorna se o status de um comentário foi desbloqueado para um item.
  * `item_comment_status_read()`: retorna se o status de um comentário foi lido para um item.
  * `item_comment_status_unread()`: retorna se o status de um comentário foi não lido para um item.
  * `item_comment_status_flagged()`: retorna se o status de um comentário foi flagrado para um item.
  * `item_comment_status_unflagged()`: retorna se o status de um comentário foi desflaggado para um item.
  * `item_comment_status_moved()`: retorna se o status de um comentário foi movido para um item.
  * `item_comment_status_sticky()`: retorna se o status de um comentário foi definido como sticky para um item.
  * `item_comment_status_unsticky()`: retorna se o status de um comentário foi removido como sticky para um item.
  * `item_comment_status_moderated()`: retorna se o status de um comentário foi moderado para um item.
  * `item_comment_status_approved()`: retorna se o status de um comentário foi aprovado para um item.
  * `item_comment_status_spam()`: retorna se o status de um comentário foi spam para um item.
  * `item_comment_status_ham()`: retorna se o status de um comentário foi ham para um item.
  * `item_comment_status_deleted()`: retorna se o status de um comentário foi deletado para um item.
  * `item_comment_status_hidden()`: retorna se o status de um comentário foi oculto para um item.
  * `item_comment_status_blocked()`: retorna se o status de um comentário foi bloqueado para um item.
  * `item_comment_status_unblocked()`: retorna se o status de um comentário foi desbloqueado para um item.
  * `item_comment_status_read()`: retorna se o status de um comentário foi lido para um item.
  * `item_comment_status_unread()`: retorna se o status de um comentário foi não lido para um item.
  * `item_comment_status_flagged()`: retorna se o status de um comentário foi flagrado para um item.
  * `item_comment_status_unflagged()`: retorna se o status de um comentário foi desflaggado para um item.
  * `item_comment_status_moved()`: retorna se o status de um comentário foi movido para um item.
  * `item_comment_status_sticky()`: retorna se o status de um comentário foi definido como sticky para um item.
  * `item_comment_status_unsticky()`: retorna se o status de um comentário foi removido como sticky para um item.
  * `item_comment_status_moderated()`: retorna se o status de um comentário foi moderado para um item.
  * `item_comment_status_approved()`: retorna se o status de um comentário foi aprovado para um item.
  * `item_comment_status_spam()`: retorna se o status de um comentário foi spam para um item.
  * `item_comment_status_ham()`: retorna se o status de um comentário foi ham para um item.
  * `item_comment_status_deleted()`: retorna se o status de um comentário foi deletado para um item.
  * `item_comment_status_hidden()`: retorna se o status de um comentário foi oculto para um item.
  * `item_comment_status_blocked()`: retorna se o status de um comentário foi bloqueado para um item.
  * `item_comment_status_unblocked()`: retorna se o status de um comentário foi desbloqueado para um item.
  * `item_comment_status_read()`: retorna se o status de um comentário foi lido para um item.
  * `item_comment_status_unread()`: retorna se o status de um comentário foi não lido para um item.
  * `item_comment_status_flagged()`: retorna se o status de um comentário foi flagrado para um item.
  * `item_comment_status_unflagged()`: retorna se o status de um comentário foi desflaggado para um item.
  * `item_comment_status_moved()`: retorna se o status de um comentário foi movido para um item.
  * `item_comment_status_sticky()`: retorna se o status de um comentário foi definido como sticky para um item.
  * `item_comment_status_unsticky()`: retorna se o status de um comentário foi removido como sticky para um item.
  * `item_comment_status_moderated()`: retorna se o status de um comentário foi moderado para um item.
  * `item_comment_status_approved()`: retorna se o status de um comentário foi aprovado para um item.
  * `item_comment_status_spam()`: retorna se o status de um comentário foi spam para um item.
  * `item_comment_status_ham()`: retorna se o status de um comentário foi ham para um item.
  * `item_comment_status_deleted()`: retorna se o status de um comentário foi deletado para um item.
  * `item_comment_status_hidden()`: retorna se o status de um comentário foi oculto para um item.
  * `item_comment_status_blocked()`: retorna se o status de um comentário foi bloqueado para um item.
  * `item_comment_status_unblocked()`: retorna se o status de um comentário foi desbloqueado para um item.
  * `item_comment_status_read()`: retorna se o status de um comentário foi lido para um item.
  * `item_comment_status_unread()`: retorna se o status de um comentário foi não lido para um item.
  * `item_comment_status_flagged()`: retorna se o status de um comentário foi flagrado para um item.
  * `item_comment_status_unflagged()`: retorna se o status de um comentário foi desflaggado para um item.
  * `item_comment_status_moved()`: retorna se o status de um comentário foi movido para um item.
  * `item_comment_status_sticky()`: retorna se o status de um comentário foi definido como sticky para um item.
  * `item_comment_status_unsticky()`: retorna se o status de um comentário foi removido como sticky para um item.
  * `item_comment_status_moderated()`: retorna se o status de um comentário foi moderado para um item.
  * `item_comment_status_approved()`: retorna se o status de um comentário foi aprovado para um item.
  * `item_comment_status_spam()`: retorna se o status de um comentário foi spam para um item.
  * `item_comment_status_ham()`: retorna se o status de um comentário foi ham para um item.
  * `item_comment_status_deleted()`: retorna se o status de um comentário foi deletado para um item.
  * `item_comment_status_hidden()`: retorna se o status de um comentário foi oculto para um item.
  * `item_comment_status_blocked()`: retorna se o status de um comentário foi bloqueado para um item.
  * `item_comment_status_unblocked()`: retorna se o status de um comentário foi desbloqueado para um item.
  * `item_comment_status_read()`: retorna se o status de um comentário foi lido para um item.
  * `item_comment_status_unread()`: retorna se o status de um comentário foi não lido para um item.
  * `item_comment_status_flagged()`: retorna se o status de um comentário foi flagrado para um item.
  * `item_comment_status_unflagged()`: retorna se o status de um comentário foi desflaggado para um item.
  * `item_comment_status_moved()`: retorna se o status de um comentário foi movido para um item.
  * `item_comment_status_sticky()`: retorna se o status de um comentário foi definido como sticky para um item.
  * `item_comment_status_unsticky()`: retorna se o status de um comentário foi removido como sticky para um item.
  * `item_comment_status_moderated()`: retorna se o status de um comentário foi moderado para um item.
  * `item_comment_status_approved()`: retorna se o status de um comentário foi aprovado para um item.
  * `item_comment_status_spam()`: retorna se o status de um comentário foi spam para um item.
  * `item_comment_status_ham()`: retorna se o status de um comentário foi ham para um item.
  * `item_comment_status_deleted()`: retorna se o status de um comentário foi deletado para um item.
  * `item_comment_status_hidden()`: retorna se o status de um comentário foi oculto para um item.
  * `item_comment_status_blocked()`: retorna se o status de um comentário foi bloqueado para um item.
  * `item_comment_status_unblocked()`: retorna se o status de um comentário foi desbloqueado para um item.
  * `item_comment_status_read()`: retorna se o status de um comentário foi lido para um item.
  * `item_comment_status_unread()`: retorna se o status de um comentário foi não lido para um item.
  * `item_comment_status_flagged()`: retorna se o status de um comentário foi flagrado para um item.
  * `item_comment_status_unflagged()`: retorna se o status de um comentário foi desflaggado para um item.
  * `item_comment_status_moved()`: retorna se o status de um comentário foi movido para um item.
  * `item_comment_status_sticky()`: retorna se o status de um comentário foi definido como sticky para um item.
  * `item_comment_status_unsticky()`: retorna se o status de um comentário foi removido como sticky para um item.
  * `item_comment_status_moderated()`: retorna se o status de um comentário foi moderado para um item.
  * `item_comment_status_approved()`: retorna se o status de um comentário foi aprovado para um item.
  * `item_comment_status_spam()`: retorna se o status de um comentário foi spam para um item.
  * `item_comment_status_ham()`: retorna se o status de um comentário foi ham para um item.
  * `item_comment_status_deleted()`: retorna se o status de um comentário foi deletado para um item.
  * `item_comment_status_hidden()`: retorna se o status de um comentário foi oculto para um item.
  * `item_comment_status_blocked()`: retorna se o status de um comentário foi bloqueado para um item.
  * `item_comment_status_unblocked()`: retorna se o status de um comentário foi desbloqueado para um item.
  * `item_comment_status_read()`: retorna se o status de um comentário foi lido para um item.
  * `item_comment_status_unread()`: retorna se o status de um comentário foi não lido para um item.
  * `item_comment_status_flagged()`: retorna se o status de um comentário foi flagrado para um item.
  * `item_comment_status_unflagged()`: retorna se o status de um comentário foi desflaggado para um item.
  * `item_comment_status_moved()`: retorna se o status de um comentário foi movido para um item.
  * `item_comment_status_sticky()`: retorna se o status de um comentário foi definido como sticky para um item.
  * `item_comment_status_unsticky()`: retorna se o status de um comentário foi removido como sticky para um item.
  * `item_comment_status_moderated()`: retorna se o status de um comentário foi moderado para um item.
  * `item_comment_status_approved()`: retorna se o status de um comentário foi aprovado para um item.
  * `item_comment_status_spam()`: retorna se o status de um comentário foi spam para um item.
  * `item_comment_status_ham()`: retorna se o status de um comentário foi ham para um item.
  * `item_comment_status_deleted()`: retorna se o status de um comentário foi deletado para um item.
  * `item_comment_status_hidden()`: retorna se o status de um comentário foi oculto para um item.
  * `item_comment_status_blocked()`: retorna se o status de um comentário foi bloqueado para um item.
  * `item_comment_status_unblocked()`: retorna se o status de um comentário foi desbloqueado para um item.
  * `item_comment_status_read()`: retorna se o status de um comentário foi lido para um item.
  * `item_comment_status_unread()`: retorna se o status de um comentário foi não lido para um item.
  * `item_comment_status_flagged()`: retorna se o status de um comentário foi flagrado para um item.
  * `item_comment_status_unflagged()`: retorna se o status de um comentário foi desflaggado para um item.
  * `item_comment_status_moved()`: retorna se o status de um comentário foi movido para um item.
  * `item_comment_status_sticky()`: retorna se o status de um comentário foi definido como sticky para um item.
  * `item_comment_status_unsticky()`: retorna se o status de um comentário foi removido como sticky para um item.
  * `item_comment_status_moderated()`: retorna se o status de um comentário foi moderado para um item.
  * `item_comment_status_approved()`: retorna se o status de um comentário foi aprovado para um item.
  * `item_comment_status_spam()`: retorna se o status de um comentário foi spam para um item.
  * `item_comment_status_ham()`: retorna se o status de um comentário foi ham para um item.
  * `item_comment_status_deleted()`: retorna se o status de um comentário foi deletado para um item.
  * `item_comment_status_hidden()`: retorna se o status de um comentário foi oculto para um item.
  * `item_comment_status_blocked()`: retorna se o status de um comentário foi bloqueado para um item.
  * `item_comment_status_unblocked()`: retorna se o status de um comentário foi desbloqueado para um item.
  * `item_comment_status_read()`: retorna se o status de um comentário foi lido para um item.
  * `item_comment_status_unread()`: retorna se o status de um comentário foi não lido para um item.
  * `item_comment_status_flagged()`: retorna se o status de um comentário foi flagrado para um item.
  * `item_comment_status_unflagged()`: retorna se o status de um comentário foi desflaggado para um item.
  * `item_comment_status_moved()`: retorna se o status de um comentário foi movido para um item.
  * `item_comment_status_sticky()`: retorna se o status de um comentário foi definido como sticky para um item.
  * `item_comment_status_unsticky()`: retorna se o status de um comentário foi removido como sticky para um item.
  * `item_comment_status_moderated()`: retorna se o status de um comentário foi moderado para um item.
  * `item_comment_status_approved()`: retorna se o status de um comentário foi aprovado para um item.
  * `item_comment_status_spam()`: retorna se o status de um comentário foi spam para um item.
  * `item_comment_status_ham()`: retorna se o status de um comentário foi ham para um item.
  * `item_comment_status_deleted()`: retorna se o status de um comentário foi deletado para um item.
  * `item_comment_status_hidden()`: retorna se o status de um comentário foi oculto para um item.
  * `item_comment_status_blocked()`: retorna se o status de um comentário foi bloqueado para um item.
  * `item_comment_status_unblocked()`: retorna se o status de um comentário foi desbloqueado para um item.
  * `item_comment_status_read()`: retorna se o status de um comentário foi lido para um item.
  * `item_comment_status_unread()`: retorna se o status de um comentário foi não lido para um item.
  * `item_comment_status_flagged()`: retorna se o status de um comentário foi flagrado para um item.
  * `item_comment_status_unflagged()`: retorna se o status de um comentário foi desflaggado para um item.
  * `item_comment_status_moved()`: retorna se o status de um comentário foi movido para um item.
  * `item_comment_status_sticky()`: retorna se o status de um comentário foi definido como sticky para um item.
  * `item_comment_status_unsticky()`: retorna se o status de um comentário foi removido como sticky para um item.
  * `item_comment_status_moderated()`: retorna se o status de um comentário foi moderado para um item.
  * `item_comment_status_approved()`: retorna se o status de um comentário foi aprovado para um item.
  * `item_comment_status_spam()`: retorna se o status de um comentário foi spam para um item.
  * `item_comment_status_ham()`: retorna se o status de um comentário foi ham para um item.
  * `item_comment_status_deleted()`: retorna se o status de um comentário foi deletado para um item.
  * `item_comment_status_hidden()`: retorna se o status de um comentário foi oculto para um item.
  * `item_comment_status_blocked()`: retorna se o status de um comentário foi bloqueado para um item.
  * `item_comment_status_unblocked()`: retorna se o status de um comentário foi desbloqueado para um item.
  * `item_comment_status_read()`: retorna se o status de um comentário foi lido para um item.
  * `item_comment_status_unread()`: retorna se o status de um comentário foi não lido para um item.
  * `item_comment_status_flagged()`: retorna se o status de um comentário foi flagrado para um item.
  * `item_comment_status_unflagged()`: retorna se o status de um comentário foi desflaggado para um item.
  * `item_comment_status_moved()`: retorna se o status de um comentário foi movido para um item.
  * `item_comment_status_sticky()`: retorna se o status de um comentário foi definido como sticky para um item.
  * `item_comment_status_unsticky()
