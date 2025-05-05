# Guia Prático de HTML & CSS

### Aprenda os conceitos básicos para criar páginas web

### Desenvolvido para autodidatas e iniciantes

# Sumário
- [Introdução](#1-introducao)
- [O que é HTML](#2-o-que-é-html)
- [O que é CSS](#4-o-que-é-css)
- [Como criar uma página HTML](#como-criar-uma-página-html)
- [Estrutura básica de uma página HTML](#estrutura-básica-de-uma-página-html)
- [Parágrafos](#parágrafos)
- [Blocos](#blocos)
- [Listas com marcadores](#listas-com-marcadores)
- [Atributos e Elementos](#3-atributos-e-elementos)
- [Cores](#cores)
- [Links](#links)
- [Listas (Ordenadas e Não Ordenadas)](#listas-ordenadas-e-não-ordenadas)
- [Imagens](#imagens)
- [Tabelas](#tabelas)
- [Formulários](#formulários)
- [Inputs e Elementos de Formulário](#inputs-e-elementos-de-formulário)
- [Iframes](#iframes)
- [Introdução ao CSS](#introdução-ao-css)
- [Como aplicar CSS - Inline, Interno, Externo](#como-aplicar-css---inline-interno-externo)
- [Seletores CSS](#seletores-css)
- [Cores no CSS](#cores-no-css)
- [Fontes e Tipografia](#fontes-e-tipografia)
- [Background e Borda](#background-e-borda)
- [Margens e Preenchimento (Margin e Padding)](#margens-e-preenchimento-margin-e-padding)
- [Box Model (Modelo de Caixa)](#box-model-modelo-de-caixa)
- [Display e Visibilidade](#display-e-visibilidade)
- [Posicionamento (Position)](#posicionamento-position)
- [Flexbox (Layout Flexível)](#flexbox-layout-flexível)
- [Responsividade com Media Queries](#responsividade-com-media-queries)
- [Animações e Transições](#animações-e-transições)
- [Desenvolvimento Responsivo e Mobile First](#desenvolvimento-responsivo-e-mobile-first)

## 1. Introducao
- O HTML e CSS sao documentos programaveis que sao utilizados na criacao de Paginas Web, essas paginas compoem boa parte da internet que conhecemos hoje, quando utilizando um Navegador ele interpreta as informacoes que estao no servidor e apresenta em um formato amigavel para o usuario. Nesse livro vamos entender os conceitos de criacao de documentos no formato HTML e estilo em CSS que podera ser usados na sua proxima Pagina Web.

## 1.1 Pra quem e esse livro?
- Esse livro e destinado a estudantes de programacao web ou qualquer pessoa que tenha interesse em criar, organizar e/ou manter paginas web profissionalmente ou para uso pessoal.

## 1.2 Porque aprender HTML?
- O HTML e usado amplamente em quase todas as paginas web da atualidade, especialmente nos dias de hoje que as paginas feitas em Flash sumiram e os dispositivos moveis estao cada vez mais simples e organizadas. Seja em redes sociais, blog, site de compartilhamento de video ou sites empresariais o HTML esta presente e atualmente nao existe nenhuma nova tecnologia que venha a substituir.

## 1.3 Porque aprender CSS?
- Assim como HTML, CSS e fundamental para a criacao de uma pagina web, enquanto o HTML se preocupa em estruturar um documento e organizar o texto em apresentacoes simples e compacta o CSS esta comprometido em dar uma vida nas paginas trazendo cores, estilos de fontes e formatando, transformando completamente uma pagina simples em obras de arte.

## 1.4 Sobre essa serie de livros
- Essa e uma serie de livros desenvolvido para pessoas que queiram criar sites de maneira profissional, com modelos praticos e simples de ajustar. Com ele voce pode criar sites esteticos e servira de base para voce construir sua carreira como desenvolvedor web, alem deste livro existem outros que voce pode e deve ler e se aprofundar nessa incrivel area, entre eles temos o Guia pratico: Javascript, Guia pratico: PHP, Guia pratico: Android e Publique seu site hoje!

# Como Criar uma Página HTML

O **HTML (HyperText Markup Language)** é a linguagem de marcação padrão usada para criar páginas e conteúdos na web. Toda página que você acessa em um navegador, como o Google Chrome ou Firefox, é estruturada com HTML. Saber criar uma página HTML é o primeiro passo para quem deseja desenvolver sites, blogs, portfólios ou sistemas online.

Neste conteúdo, você vai aprender de forma simples e prática como criar a sua primeira página HTML do zero, usando apenas um editor de texto e um navegador.

---

## Passo a Passo para Criar uma Página HTML Simples

### 1. Abra um Editor de Texto  
Pode ser o **Bloco de Notas** (Windows), **TextEdit** (Mac) ou qualquer outro editor de código como **VS Code**, **Sublime Text** ou **Notepad++**.

### 2. Digite o Código HTML

Aqui está um exemplo básico de estrutura HTML:

```html
<!DOCTYPE html>
<html>
<head>
  <title>Minha Primeira Página</title>
</head>
<body>
  <h1>Bem-vindo à Minha Página HTML</h1>
  <p>Este é o meu primeiro site criado usando HTML!</p>
</body>
</html>
```

### 3. Salve o Arquivo

- Clique em **Arquivo > Salvar como...**
- Dê um nome ao arquivo, por exemplo: `index.html`
- No campo "Tipo", escolha **Todos os Arquivos**
- Certifique-se de que a extensão está `.html`
- Salve em qualquer pasta de sua preferência.

### 4. Abra no Navegador

- Vá até a pasta onde salvou o arquivo.
- Dê um clique duplo no arquivo `index.html`.
- Ele abrirá no navegador padrão e você verá sua página funcionando!

---

## 2. O que é HTML
- HTML e um editor de hipertextos, muito utilizado para criacao de paginas online e aplicacoes de web. Em conjunto com o CSS e Javascript, eles formam as pedras principais para a World Wide Web. Todos os navegadores atuais recebem documentos em HTML que sao processados renderizacao e apresentacao do conteudo online. O nome HTML e uma abreviacao para a expressao inglesa de HyperText Markup Language, que significa Linguagem de Marcacao de Hipertexto. O HTML e um documento que utiliza Tags para a construcao de paginas web, modelando e organizando a estrutura de apresentacao de textos, tabelas e imagens de maneira a facilitar a leitura de humanos ou robos.
- HTML significa Hyper Text Markup Language
- HTML descreve a estrutura das paginas da Web usando marcacao
- Elementos HTML sao os blocos de construcao de paginas HTML
- Elementos HTML sao representados por tags
- Tags de HTML marcam partes de conteudo, como "titulo", "paragrafo", "tabela" e assim por diante
- Os navegadores nao exibem as tags HTML, mas as usam para apresentar o conteudo da pagina

## 2.1. Historia
- O HTML foi criado para resolver um problema de comunicacao e disseminacao de pesquisas entre colegas de Universidade, criado por Tim Berners-Lee na decada de 90. No inicio era apenas um conjunto de ferramentas que ajudavam as pessoas a compartilhar informacoes de forma organizada, porem com o tempo foi se tornando uma linguagem com expressoes proprias e com uma padronizacao dissemina de facil acesso.

    | Versão   | Ano                  |
    |:----------|:---------------------|
    | HTML      | 1991                 |
    | HTML 2.0  | 1995                 |
    | HTML 3.2  | 1997                 |
    | HTML 4.01 | 1999                 |
    | XHTML     | 2000                 |
    | HTML5     | 2014                 |
    | HTML5.1   | 2016 e 2017 (2ª ed.) |
    | HTML5.2   | 2017                 |

## Estrutura básica de uma página HTML

- Basicamente uma página web pode ser criada da seguinte forma:

```html
        <!DOCTYPE html>
        <html>
        <head>
          <title>Titulo da Pagina</title>
        </head>
        <body>
          <h1>Cabecalho</h1>
          <p>Paragrafo</p>
        </body>
        </html>
```

- Essa estrutura de documento pode ser definida da seguinte forma:

- O
```html
<!DOCTYPE html>
``` 
- representa uma declaracao/Tag que define este documento como HTML.

- A Tag 
```html
<html>
``` 
- representa o elemento raiz de uma pagina HTML.

- A Tag 
```html
<head>
``` 
- contem informacoes de metadados sobre a pagina.

- A Tag
```html
<title>
``` 
- especifica um titulo para a pagina.

- A Tag
```html
<body>
``` 
- contem todo conteudo da pagina que estara visivel.

- A Tag
```html
<h1>
``` 
- define um cabecalho grande, podendo variar entre 1 e 6.

- A Tag
```html
<p>
``` 
- define um paragrafo.

- Como regra todas as Tags so serao interpretadas pelo navegador caso elas sejam iniciadas e fechadas utilizando colchetes angulares, da seguinte forma:


```md
|Abertura|Descricao|Fechamento|

|---|---|---|

|<TAG_EXEMPLO>|Escreve algo|</TAG_EXEMPLO>|
```
- Se essa regra nao for seguida alguns navegadores nao interpretarao corretamente e a pagina ficara mal estruturada.

## 2.3 Navegadores

- O objetivo de um navegador da Web (Chrome, IE, Firefox, Safari) e ler documentos HTML e exibi-los. Ele interpreta as tags HTML e utiliza para determinar como exibir o documento:
- ![Guia Prát_20250504_005119_1](foto/Guia%20Prát_20250504_005119_1.png)

- Na imagem acima utilizamos os mesmos codigos que consta na secao 2.2 Estrutura de uma pagina, ele apresenta apenas as informacoes entre tags sem apresentar os codigos em HTML.

## 2.4 Editores

- As paginas Web podem ser criadas e modificadas usando editores de texto simples, como o Notepad (PC), TextEdit (Mac) ou no Gedit (Linux), que podem ser utilizadas da seguinte forma:

- Abra o seu editor de texto;

- Escreva o seguinte texto:

```html
     <html>
     <head>
     <title>Titulo da Pagina</title>
     </head>
     <body>
     <h1>Cabecalho</h1>
     <p>Paragrafo</p>
     </body>
     </html>
```

- Salve o texto e modifique o nome para introducao.html, lembre-se que a extensao deve ser .html,

- informando assim que se trata de uma pagina web.

- Veja como ficou nossa pagina no editor de textos (Bloco de notas - PC):
![Guia Prát_20250504_005119_2](foto/Guia%20Prát_20250504_005119_2.png)

- OBS.: Se voce esta comecando a aprender a criar paginas web, eu aconselho voce digitar todo o texto, pois isso vai fazer voce aprender mais rapido. Note que ao escrever o nome da pagina, nao podemos usar acentos, pois a pagina nao pode ser interpretada pelos navegadores.

## 3. Atributos e Elementos

- Os atributos fornecem informacoes adicionais sobre cada elemento que utilizamos, todos os elementos podem ter atributos e deve ser especificados na TAG de inicio. Os atributos geralmente vem em pares NOME / VALOR como: name="value" Vamos abordar mais sobre atributos nos proximos capitulos e com exemplos praticos.

## 3.1. Head

- O Head elemento e destinado a armazenar metadados (dados sobre dados) e e colocado entre a tag **`<html>`** e a **`<body>`**. Metadados em HTML sao dados sobre o documento HTML eles nao sao exibidos e geralmente definem o titulo do documento, conjunto de caracteres, estilos, links, scripts e outras informacoes meta. As seguintes tags descrevem metadados:

```html
    <title>, 
    <style>, 
    <meta>, 
    <link> e 
    <script>.
``` 

- Title

- Esse elemento define o titulo do documento e e obrigatorio em todos os documentos HTML/XHTML. Como ele podemos:

- Definir um titulo na guia do navegador

- Fornecer um titulo para a pagina quando ela e adicionada aos favoritos

- Exibir um titulo para a pagina nos resultados do mecanismo de pesquisa

- Style

- E usado para definir informacoes de estilo dentro da pagina atual, esses estilos sao recursos CSS que aprenderemos no capitulo 4.

- Link

- Essa meta-tag e usado para vincular a folhas de estilo externas, ou seja, ele indica um arquivo fora da pagina com a extensao css, esses estilos sao recursos CSS que aprenderemos no capitulo 4.

- Meta

- E usado para especificar qual conjunto de caracteres e usado, descricao da pagina, palavras-chave, autor e outros metadados. Os metadados sao usados pelos navegadores (como exibir conteudo), pelos mecanismos de pesquisa (palavras-chave) e por outros servicos da Web.

- Alguns exemplos de meta:


```html
<meta charset="UTF-8">
``` 

```html
<meta name="description" content="Aprenda HTML com o livro Guia Pratico">
``` 

```html
<meta name="keywords" content="html, css, guiapratico, aprenda html">
``` 

```html
<meta name="author" content="Wallace Fragoso">
``` 

- Script
- E usado para definir comandos em Javascript do lado do cliente, permitindo assim uma interacao com o usuario.
- Um exemplo de script que voce pode testar em seu documento e:

```html
<script>
alert(Ola eu sou uma notificacao da sua pagina web!);
</script>
``` 

## 3.2. Heading

- Os mecanismos de pesquisa usam os cabecalhos para indexar a estrutura e o conteudo de suas paginas da web, procurando seus titulos e utilizando eles como referencia de tema-chave da pagina. Os cabecalhos sao definidos com as tags **`<h1>`** ate **`<h6>`**, definindo assim seu grau de importancia, sendo os mais importantes os textos que estao entre a tag **`<h1>`** e o menos importante entre a tag **`<h6>`**. Normalmente utilizamos o **`<h1>`** para apresentar os principais cabecalhos seguidos por **`<h2>`** para seus subtitulos e assim por diante.
- Um exemplo bem comum sao os usados em Blogs, por exemplo o Wordpress que utiliza essa tag nesse esquema a seguir:

```html
<h1>Como usar elementos HTML</h1>
<h3>3 Tags mais usadas</h3>
<p>1. Ancoras</p>
```
## Parágrafos

- Os paragrafos sao usados para dividirmos o texto em secoes separando assim as informacoes entre eles, e na web nao e diferente, podemos dividir um documento da web de varias formas, entre eles temos as tags **`<p>`**, **`<br/>`** e **`<pre>`**.
- P
- Esse elemento define e delimita um paragrafo, veja um bom exemplo:
![Guia Prát_20250504_005119_4](foto/Guia%20Prát_20250504_005119_4.png)
![Guia Prát_20250504_005119_3](foto/Guia%20Prát_20250504_005119_3.png)
- Veja que na 1 figura podemos notar que separamos todos os textos entre eles, porem quando o navegador interpreta essa informacao apenas o texto que contem a tag correspondente ao paragrafo e separada das demais.
- BR
- O elemento BR define uma quebra de linha (uma nova linha) sem iniciar um novo paragrafo, podendo ser usada para organizar melhor o nosso texto de acordo com o que queremos.
![Guia Prát_20250504_005119_5](foto/Guia%20Prát_20250504_005119_5.png)
-  Note que agora o texto ficou como imaginamos.
- PRE
- Define o texto pre-formatado que e exibido em uma largura fixa e preserva os espacos e as quebras de linha que definimos em nosso editor de texto.
![Guia Prát_20250504_005119_6](foto/Guia%20Prát_20250504_005119_6.png)
![Guia Prát_20250504_005119_7](foto/Guia%20Prát_20250504_005119_7.png)

## Blocos

- Um dos elementos mais utilizado atualmente e a DIV, que sempre inicia o texto em uma nova linha e ocupa toda a largura disponivel (estende-se para a esquerda e para a direita o maximo possivel).
![Guia Prát_20250504_005119_8](foto/Guia%20Prát_20250504_005119_8.png)

## Listas (Ordenadas e Não Ordenadas)

- As listas sao utilizadas comumente para fazer uma selecao de informacoes que queremos compartilhar, e nas paginas web podemos defini-las de diversas maneiras, vamos ver algumas.
- 
### Listas com marcadores
- Uma lista com marcadores comeca com a tag **`<ul>`** e cada item da lista comeca com a tag **`<li>`**, ao ser processado, por padrao os marcadores serao apresentados como pequenos circulos pretos de forma padrao.
![Guia Prát_20250504_005119_10](foto/Guia%20Prát_20250504_005119_10.png)
![Guia Prát_20250504_005119_9](foto/Guia%20Prát_20250504_005119_9.png)
- Dentre as opcoes que temos para personalizar temos Disc, Circle, Square e None.
- O Disc e o formato padrao, esse da imagem acima;
- O Circle e um circulo sem o preenchimento do circulo;
- O Square e um quadrado com o centro preenchido;
- E o None faz as imagens sumirem, ou seja, mantem o recuo e nao apresenta nenhuma forma.
- Para aplicar esses tipos de formatos e preciso usar o atributo style="list-style-type:square" na tag ul, da seguinte forma:

```html
  <ul style="list-style-type:square">
  <li>Feijao</li>
  <li>Arroz</li>
  <li>Sal</li>
  <li>Acucar</li>
  </ul>
```
### Lista com ordenacao
- Uma lista ordenada comeca com a tag **`<ol>`** e transforma cada item da lista em uma numeracao usando a tag **`<li>`**.
![Guia Prát_20250504_005119_11](foto/Guia%20Prát_20250504_005119_11.png)
- Dentre as opcoes que temos para personalizar temos o tipo 1, A, a, I e i.
- O tipo 1 e a numeracao basica que e o exemplo da lista a cima;
- O tipo A e uma lista com o alfabeto em letra maiuscula;
- O tipo a e uma lista com o alfabeto em letra minuscula;
- O tipo I e uma lista com o alfabeto romano em letra maiuscula;
- O tipo i e uma lista com o alfabeto romano em letra minuscula;
- Para aplicar esses tipos de formatos e preciso usar o atributo type="A" na tag ol, da seguinte forma:

```html
    <ol type="A">
    <li>Feijao</li>
    <li>Arroz</li>
    <li>Sal</li>
    <li>Acucar</li>
    </ol>
```

- Sugiro que voce personalize sua lista e crie uma lista no seu computador, dessa forma voce vai ver o resultado de cada alteracao.

## Tabelas

- Uma tabela e composta de Colunas e Linhas, e a intersecao da coluna e da linha e chamado de celula, assim como e em qualquer planilha eletronica. Para construir uma tabela usamos o elemento **`<table>`** e para cada linha que desejamos criar usamos a tag **`<tr>`**, e cada coluna e criada usando a tag **`<td>`**, vejamos o exemplo:
![Guia Prát_20250504_005119_13](foto/Guia%20Prát_20250504_005119_13.png)
![Guia Prát_20250504_005119_12](foto/Guia%20Prát_20250504_005119_12.png)
- As tabelas foram usadas massivamente nos periodos de 2003 ate 2011, nessa epoca toda a estrutura da pagina era pensada em uma tabela, um dos programas que mais ajudou a disseminar esse aspecto era o Dreamweaver. O Google ajudou a acabar com esse padrao, pois as paginas que usavam esse tipo de abordagem foram caindo nas pesquisas e o robo deixavam de priorizar as tabelas como fontes de informacoes importantes. Atualmente as tabelas sao mais usadas para agrupar informacoes.
- Outro ponto importante da tabela e a possibilidade de manipula-las de maneira a apresentar certas informacoes em formatos mais elegantes, como e feita nas planilhas eletronicas. Dentre essas opcoes podemos mesclar varias linhas usando o atributo colspan; Outra opcao e mesclar varias colunas usando o atributo rowspan;

## Imagens

- As imagens podem melhorar o design e a aparencia de uma pagina da web, as imagens sao definidas com a tag **`<img>`** sem utilizar o fechamento. E possivel carregar uma imagem diretamente do seu computador ou em site especifico.
- Nesse exemplo abaixo vamos salvar uma imagem qualquer no computador:
![Guia Prát_20250504_005119_14](foto/Guia%20Prát_20250504_005119_14.png)
- E estando na mesma area do arquivo, voce pode carrega-lo da seguinte forma:
![Guia Prát_20250504_005119_16](foto/Guia%20Prát_20250504_005119_16.png)
![Guia Prát_20250504_005119_15](foto/Guia%20Prát_20250504_005119_15.png)
- Agora vamos pegar outra imagem e referenciar em um site:
![Guia Prát_20250504_005119_18](foto/Guia%20Prát_20250504_005119_18.png)
![Guia Prát_20250504_005119_17](foto/Guia%20Prát_20250504_005119_17.png)
- No site fica assim:
- No capitulo 6: Criando paginas simples, vamos ter mais exemplos usando e ajustando a imagem em um site.

## Iframes

- Um Iframe e usado para exibir uma pagina web dentro da sua pagina web, e e bastante usado para incorporar partes de um site com algum recurso especifico no seu site principal. Um dos usos mais comuns hoje em dia e inserir um video no seu site.
- Nesse exemplo usaremos o site com a tabela que criamos no capitulo 3.6:
![Guia Prát_20250504_005120_20](foto/Guia%20Prát_20250504_005120_20.png)
![Guia Prát_20250504_005119_19](foto/Guia%20Prát_20250504_005119_19.png)
- Agora vamos incorporar um video do YouTube:
![Guia Prát_20250504_005120_22](foto/Guia%20Prát_20250504_005120_22.png)
![Guia Prát_20250504_005120_21](foto/Guia%20Prát_20250504_005120_21.png)

## 3.9. Elementos de codigo

- Algumas vezes voce vai precisar apresentar algumas informacoes destinadas a conceitos computacionais ou apenas mostrar um comando de atalho e normalmente exibido na fonte mono espacada, veja o exemplo:

### KBD
- Representa a entrada do usuario, como entrada de teclado ou comandos de voz.
```html 
<p>Para salvar um texto, pressione <kbd>Ctrl + S</kbd></p>
```
### CODE
- Representa um trecho de codigo de alguma programacao.
```html
<p>Escreva o trecho a seguir <code>x = 1 + 2;</code></p>
```
### VAR
- A variavel poderia ser uma variavel em uma expressao matematica ou uma variavel no contexto de programacao.

```html
<p>Principio da Relatividade: <var>E</var> = <var>mc</var><sup>2</sup>. </p>
```
- Vejamos como ficam:
![Guia Prát_20250504_005120_23](foto/Guia%20Prát_20250504_005120_23.png)
![Guia Prát_20250504_005120_24](foto/Guia%20Prát_20250504_005120_24.png)

## 3.10. Caracteres especial em HTML

- Ao construir paginas web inevitavelmente precisaremos usar algum recurso que sao reservados ao interpretador do navegador, e ao tentar usar a pagina vai ser apresentado algum erro ou ficara mal formatado. Se voce usar os sinais de menor que **`(<)`** ou maior que **`(>)`** em seu texto, o navegador podera mistura-los com tags. Para resolver esse problema utilizaremos carateres especias para formar esse texto:

| Descrição       | Resultado | Comando     |
|----------------|-----------|-------------|
| Espaço vazio   |           | `&nbsp;`    |
| Menor que      | <         | `&lt;`      |
| Maior que      | >         | `&gt;`      |
| E comercial    | &         | `&amp;`     |
| Aspas simples  | '         | `&apos;`    |
| Aspas duplas   | "         | `&quot;`    |
| Copyright      | ©         | `&copy;`    |
| Sinal registrado | ®       | `&reg;`     |

## 3.11. Simbolos em HTML

- Alguns simbolos sao bastantes utilizados nas paginas, assim como os caracteres especiais podemos inclui-los com os comandos especiais.

| **Descrição**       | **Resultado** | **Comando**   |
|---------------------|---------------|----------------|
| **Setas**           | ←             | `&larr;`       |
|                     | ↑             | `&uarr;`       |
|                     | →             | `&rarr;`       |
|                     | ↓             | `&darr;`       |
| **Moedas**          | €             | `&euro;`       |
| **Marca registrada**| ™             | `&trade;`      |
| **Baralho**         | ♠             | `&spades;`     |
|                     | ♣             | `&clubs;`      |
|                     | ♥             | `&hearts;`     |
|                     | ♦             | `&diams;`      |

## Formulários

- Um formulario web e um conjunto de elementos que selecionamos e enviamos para uma outra pagina de recebimento, essa pagina de recebimento e responsavel por realizar o processamento dos dados que enviamos atraves do formulario. Para iniciar um formulario usamos a tag **`<form>`** e definimos a pagina que recebera as informacoes no atributo action="URL Destino".

## Inputs e Elementos de Formulário

- Os elementos de formulario com a tag input tem como objetivo armazenar as informacoes que escrevemos nele, um exemplo simples e a entrada de login de um site, porem temos varios tipos de inputs, segue alguns:
- Entrada de texto simples 

```md
<input type="text">;
```
- Entrada de texto, escondendo o que digitamos 

```md
<input type="password">;
```
- Selecao de uma opcao 

```md
<input type="radio">;
```
- Selecao de multiplas opcoes 

```md
<input type="checkbox">;
```
- Reiniciar o formulario 

```md
<input type="reset">;
```
- Enviar o formulario 

```md
<input type="submit">;
```
- Vejamos como fica cada um deles preenchido:
![Guia Prát_20250504_005120_26](foto/Guia%20Prát_20250504_005120_26.png)
![Guia Prát_20250504_005120_25](foto/Guia%20Prát_20250504_005120_25.png)

## 3.12.2. Fieldset

- Os Fieldset sao usados para agrupar dados relacionados em um formulario usando a tag **`<fieldset>`** e adicionamos um titulo com a tag **`<legend>`**. 
![Guia Prát_20250504_005120_28](foto/Guia%20Prát_20250504_005120_28.png)
![Guia Prát_20250504_005120_27](foto/Guia%20Prát_20250504_005120_27.png)
- É como ficara o nosso formulario:

## 3.12.3. Select

- O Select tem funcao bem parecida com as do radio, porem ele cria uma lista agrupada em um unico ponto, para iniciar o select usamos a tag **`<select>`** e para cada item que quisermos que esteja presente usamos o elemento com a tag **`<option>`**. Vamos ver como fica:
![Guia Prát_20250504_005120_30](foto/Guia%20Prát_20250504_005120_30.png)
![Guia Prát_20250504_005120_29](foto/Guia%20Prát_20250504_005120_29.png)

## 3.12.4. TextArea

- O textarea e uma opcao elegante quando precisamos adicionar uma entrada de dados que tenha uma informacao muita extensa, ela pode ser inciada usando a tag **`<textarea>`**. 
![Guia Prát_20250504_005120_31](foto/Guia%20Prát_20250504_005120_31.png)
![Guia Prát_20250504_005120_32](foto/Guia%20Prát_20250504_005120_32.png)
- Ela sera apresentando nesse formado:

## Links

- Os links ou ancoras sao encontrados em quase todas as paginas web, elas permitem que o usuario seja levado para um ponto especifico da pagina ou para uma outra pagina, quando voce move o mouse sobre um link, a seta do mouse se transformara em uma pequena mao. 
![Guia Prát_20250504_005120_34](foto/Guia%20Prát_20250504_005120_34.png)
![Guia Prát_20250504_005120_33](foto/Guia%20Prát_20250504_005120_33.png)
- No exemplo acima eu criei um link para acessar a minha pagina do Facebook, e quando o navegador processa a informacao o usuario nao ver para onde vai ser direcionado ate que ele clique.

# Introdução ao CSS

## 4. O que é CSS

- O CSS (Cascending Style Sheets) descreve como os elementos HTML devem ser exibidos na tela, no papel ou em outras midias. Ele pode controlar e criar estilos em todos os elementos do HTML, seja de apenas para um elemento ou de varios de uma so vez, dessa forma economiza muito trabalho.

- CSS pode ser adicionado aos elementos HTML de 3 maneiras:
    - **Inline** - usando o atributo style em elementos HTML
    - **Interno** - usando um **`<style>`** elemento na **`<head>`** secao
    - **Externo** - usando um arquivo CSS externo
- A maneira mais comum de adicionar CSS e manter os estilos em arquivos CSS separados.

## 4.1. Sintaxe CSS

- Um conjunto de regras CSS consiste em um seletor e um bloco de declaracao:

    - **H1 {color: Blue; font-size: 12px;}**

- Vamos ver os conceitos:
    - H1 Seletor;
    - {} - Declaracao;
    - Color Propriedade do seletor, que nesse caso e a mudanca da cor;
    - Blue Representa o valor da propriedade, que nesse caso e a indicacao da Cor Azul.
- O seletor aponta para o elemento HTML que voce deseja estilizar. O bloco de declaracao contem uma ou mais declaracoes separadas por ponto e virgula. Cada declaracao inclui um nome de propriedade CSS e um valor, separados por dois pontos. Uma declaracao CSS sempre termina com um ponto-e-virgula e os blocos de declaracao sao cercados por chaves.

# Seletores CSS

## 4.2. Tipos de seletores

- Os seletores podem ser todo e qualquer elemento HTML, um elemento especifico que possui um atributo ID ou um atributo CLASS.

## 4.3. Atributo ID

- Ele e a criacao de um ID exclusivo para um elemento HTML (o valor deve ser exclusivo dentro do documento HTML). Caso voce use o mesmo ID em mais de um elemento voce pode causar um problema de referencia ao tentar manipular o elemento.
- Em CSS, para selecionar um elemento com um ID especifico, escreva um caractere hash (#), seguido pelo id do elemento:
![Guia Prát_20250504_005120_35](foto/Guia%20Prát_20250504_005120_35.png)
![Guia Prát_20250504_005120_36](foto/Guia%20Prát_20250504_005120_36.png)
- Agora em execucao:

## 4.4. Atributo Class

- Esse atributo especifica um ou mais nomes de classe para um elemento HTML. Diferente do ID a Class pode e deve ser usado em mais de um elemento, permitindo assim a estilizacao de varios elementos ao mesmo tempo.
- Em CSS, para selecionar elementos com uma classe especifica, escreva um caractere de ponto (.), Seguido do nome da classe:
![Guia Prát_20250504_005120_37](foto/Guia%20Prát_20250504_005120_37.png)
![Guia Prát_20250504_005120_38](foto/Guia%20Prát_20250504_005120_38.png)
- Agora em execucao:

## 4.5. Agrupando seletores

- Em alguns casos precisamos usar as mesmas definicoes para elementos diferentes, como por exemplo:

```md
H1 {
color: white;
}
p {
color: white;
}
- Entao podemos fazer isso:
H1,
p {
color: white;
}
```
# Como aplicar CSS - Inline, Interno, Externo
## 4.6. Estilos Inline

- Um estilo inline pode ser usado para aplicar um estilo exclusivo para um unico elemento. Para usar estilos in-line, adicione o atributo style ao elemento relevante. O atributo style pode conter qualquer propriedade CSS.
- Vejamos um exemplo:

```md
<p style="color:blue;">Iniciando um paragrafo</p>
```
## 4.7. Estilo Interno

- Uma folha de estilos interna pode ser usada se uma unica pagina tiver um estilo exclusivo. Estilos internos sao definidos dentro do elemento **`<style>`**, dentro da secao **`<head>`** de uma pagina HTML, vejamos um exemplo:
```html
    <head>
    <style>
    body {
    background-color: linen;
    }
    </style>
    </head>
```
## 4.8. Estilo Externo

- Com uma folha de estilos externa, voce pode alterar a aparencia de um site inteiro alterando apenas um arquivo. Cada pagina deve incluir uma referencia ao arquivo da folha de estilo externa dentro do elemento **`<link>`**. O elemento **`<link>`** entra na secao **`<head>`**:
- Arquivo externo:
- meus_estilos.css
- OBS.: Toda pagina de estilo deve ter a extensao CSS.
- Agora no nosso site principal:

```html
    <head>
    <link rel="stylesheet" type="text/css" href="mystyle.css">
    </head>
```
# Cores no CSS

## Cores

- Propriedade COLOR
- As cores sao especificadas usando nomes de cores predefinidos ou valores RGB, HEX entre outros, vamos ver alguns nomes predefinidos:
- Tomate
- laranja
- Trapaceiro azul
- MediumSeaGreen
- cinzento
- Azul ardosia
- Tolet
- Cinza claro

# Background e Borda

## 4.10. Cor de fundo

- Propriedade BACKGROUND-COLOR
- Podemos usar os mesmos dados de cores predefinidas que usamos na propriedade COLOR. Alem de usar cores podemos usar imagens como fundo.
- Propriedade BACKGROUND-IMAGE - 

```md
background-image: url("imagem.jpg");
```

## Fontes e Tipografia

- Propriedade FONT-FAMILY
- Essa propriedade define a familia de fontes.
- Fontes genericas
- Arial
- Verdana
- Helvetica
- Calibri
- Impact
- Tahoma
- Trebuchet MS
- Fontes do tipo serif
- Times New Roman
- Georgia
- Garamond
- Cambria
- Palatino
- Lucida Bright
- Fontes mono espacadas
- Courier
- Courier New
- Monaco
- Consolas
- Lucida Console
- Lista completa nesse .

## 4.12. Estilo de fonte

- Propriedade FONT-STYLE
- E usada principalmente para especificar o texto em italico. Esta propriedade tem tres valores:
- normal - O texto e mostrado normalmente
- italico - O texto e mostrado em italico
- obliquo - O texto e "inclinado" (obliquo e muito semelhante ao italico, mas menos suportado)

## 4.13. Tamanho da fonte

- Propriedade FONT-SIZE
- Permite gerenciar o tamanho do texto que e um recurso importante no design da web, pode ser ajustado usando Pixel, EM e Porcentagem:
- font-size: 16px;
- font-size: 1em;
- font-size: 100%;

## 4.14. Espessura da fonte

- Propriedade FONT-WEIGHT
- E usada para especificar o peso de uma fonte, seria uma especie de Negrito.
- font-weight: normal;
- font-weight: bold;
- font-weight: 25%;

## 4.15. Tamanho da Fonte Responsivo

- O tamanho do texto pode ser definido com uma VW unidade, o que significa a largura da janela de visualizacao. Viewport e o tamanho da janela do navegador. 1vw = 1% da largura da janela de visualizacao. Se a janela de visualizacao tiver 50 cm de largura, 1vw e de 0,5 cm. Dessa forma, o tamanho do texto seguira o tamanho da janela do navegador.

```md
<h1 style="font-size:10vw">Ola Mundo!</h1>
```
 ## 4.16. Alinhamento de texto

- Propriedade TEXT-ALIGN
- E usada para definir o alinhamento horizontal de um texto. Um texto pode ser alinhado a esquerda ou a direita, centrado ou justificado.
text-align: center;
text-align: left;
text-align: right;
text-align: justify;

## 4.17. Sombra de texto

- Propriedade TEXT-SHADOW
- E usada para adicionar sombra ao texto. O exemplo a seguir especifica a posicao da sombra horizontal (3px), a posicao da sombra vertical (2px) e a cor da sombra (vermelho):

```md
H1 {
text-shadow: 3px 2px red;
}
```
- Espaco interno
- Propriedade PADDING
- Adiciona um espacamento entre as bordas e seu conteudo.
- Espaco Externo
- Propriedade MARGIN
- Adiciona um espacamento para fora das bordas.

# Margens e Preenchimento (Margin e Padding)

Em CSS, **margin** e **padding** são propriedades fundamentais para o controle do espaçamento entre e dentro dos elementos HTML. Compreender a diferença entre essas propriedades e como utilizá-las corretamente é essencial para criar layouts organizados e visualmente agradáveis.

---

## Diferença entre Margin e Padding

| Propriedade | Função | Afeta o quê? |
|-------------|--------|--------------|
| `margin`    | Espaço **externo** ao redor do elemento | A distância entre o elemento e outros elementos |
| `padding`   | Espaço **interno** dentro do elemento | A distância entre o conteúdo e a borda do elemento |

---

## Representação Visual

Imagine uma caixa representando um elemento HTML:

```
+------------------------------+
|          margin              |
|  +------------------------+  |
|  |       padding          |  |
|  |  +------------------+  |  |
|  |  |     conteúdo     |  |  |
|  |  +------------------+  |  |
|  +------------------------+  |
+------------------------------+
```

---

## Como Definir Margin e Padding

Você pode definir essas propriedades de forma individual (por lado) ou abreviada.

### Exemplo de uso individual:

```css
.elemento {
  margin-top: 10px;
  margin-right: 15px;
  margin-bottom: 10px;
  margin-left: 5px;

  padding-top: 5px;
  padding-right: 10px;
  padding-bottom: 5px;
  padding-left: 10px;
}
```

### Exemplo com shorthand (forma abreviada):

```css
.elemento {
  margin: 10px 15px 10px 5px;   /* topo, direita, baixo, esquerda */
  padding: 5px 10px;            /* topo e baixo: 5px, direita e esquerda: 10px */
}
```

**Atalhos possíveis:**

- `margin: 10px;` → aplica 10px em todos os lados.
- `margin: 10px 20px;` → topo/baixo: 10px, esquerda/direita: 20px.
- `margin: 10px 20px 30px;` → topo: 10px, lados: 20px, baixo: 30px.
- `margin: 10px 20px 30px 40px;` → topo, direita, baixo, esquerda (sentido horário).

---

## Valores Especiais

- `auto`: muito usado em `margin` para centralizar elementos, especialmente com `margin: 0 auto;`.
- `0`: zera o espaçamento.
- Pode ser usado com unidades como `px`, `em`, `%`, `rem`, etc.

---

## Exemplo Prático

```html
<div class="caixa">
  Texto dentro da caixa
</div>
```

```css
.caixa {
  width: 300px;
  background-color: lightblue;
  margin: 20px auto;
  padding: 15px;
}
```

Neste exemplo:
- `margin: 20px auto;` aplica 20px de margem vertical e centraliza horizontalmente.
- `padding: 15px;` adiciona espaço interno entre o conteúdo e as bordas da caixa.

---

## Conclusão

Usar `margin` e `padding` corretamente é essencial para o controle de espaçamentos e para a criação de layouts responsivos e bem estruturados. Eles são simples, mas poderosos, e dominá-los pode fazer uma grande diferença na aparência e usabilidade de uma página.

---

**Dica:** Use ferramentas como o *inspecionar elemento* dos navegadores para visualizar margens e preenchimentos de forma gráfica enquanto desenvolve.

# Box Model (Modelo de Caixa)

## O que é o Box Model?

O **Box Model** (Modelo de Caixa) é um conceito fundamental do CSS que descreve como os elementos HTML são representados visualmente como caixas retangulares. Todo elemento renderizado em uma página é envolvido por caixas que controlam sua largura, altura e espaçamento.

---

## Estrutura do Box Model

Um elemento no modelo de caixa é composto por quatro partes, de dentro para fora:

```
+------------------------------+
|          margin              |
|  +------------------------+  |
|  |        border          |  |
|  |  +------------------+  |  |
|  |  |     padding      |  |  |
|  |  |  +------------+  |  |  |
|  |  |  | conteúdo   |  |  |  |
|  |  |  +------------+  |  |  |
|  |  +------------------+  |  |
|  +------------------------+  |
+------------------------------+
```

### As partes do Box Model:

1. **Content (Conteúdo):** O conteúdo real do elemento, como texto ou imagens.
2. **Padding (Preenchimento):** Espaço interno entre o conteúdo e a borda.
3. **Border (Borda):** A linha que envolve o conteúdo + padding.
4. **Margin (Margem):** Espaço externo entre o elemento e outros elementos.

---

## Exemplo Prático de Box Model

```css
.caixa {
  width: 200px;
  padding: 20px;
  border: 5px solid black;
  margin: 10px;
}
```
Neste exemplo:
- A **largura do conteúdo** é 200px.
- O **padding** adiciona 20px em cada lado → 40px no total.
- A **borda** adiciona 5px em cada lado → 10px no total.
- A **margem** de 10px é externa ao elemento.

**Largura total ocupada:** `200px (content) + 40px (padding) + 10px (border) = 250px` (sem contar a margem).

---

## Calculando o Tamanho Total da Caixa

O tamanho **real** de um elemento depende do `box-sizing`:

### 1. `box-sizing: content-box` (padrão)

- `width` define apenas o conteúdo.
- Padding e borda **são adicionados** ao tamanho final.

### 2. `box-sizing: border-box` (recomendado)

- `width` **inclui** padding e borda.
- O navegador ajusta o conteúdo para caber dentro da largura definida.

```css
.caixa {
  box-sizing: border-box;
}
```

---

## Visualizando com Ferramentas de Desenvolvimento

Use a ferramenta *Inspecionar Elemento* do navegador para ver visualmente o box model de qualquer elemento. Lá é possível ver claramente as dimensões de `margin`, `border`, `padding` e `content`.

---

## Conclusão

O **Box Model** é essencial para entender como os elementos se comportam na página. Dominar esse conceito ajuda a controlar o layout, o espaçamento e a sobreposição de elementos com precisão. Use sempre `box-sizing: border-box` para uma abordagem mais previsível no controle das dimensões.

---

**Dica:** A propriedade `box-sizing: border-box` evita muitos problemas de layout, especialmente em projetos responsivos.

# Display e Visibilidade

As propriedades `display` e `visibility` em CSS são usadas para controlar como os elementos aparecem (ou não) na página. Elas são fundamentais para manipular o layout e o comportamento visual de elementos HTML.

---

## Propriedade `display`

A propriedade `display` define como um elemento é exibido na página. Ela afeta o **tipo de caixa** gerada pelo elemento e como ele interage com os outros ao seu redor.

### Principais valores de `display`:

| Valor           | Descrição |
|-----------------|-----------|
| `block`         | Exibe o elemento como um bloco (ocupa toda a largura). Ex: `<div>`, `<p>` |
| `inline`        | Exibe o elemento na mesma linha que os vizinhos. Ex: `<span>`, `<a>` |
| `inline-block`  | Combina comportamentos de `inline` e `block`: fica na linha, mas permite definir largura/altura |
| `none`          | Remove completamente o elemento do layout e da renderização |
| `flex`          | Ativa o modelo de layout flexível para organização de filhos |
| `grid`          | Ativa o modelo de layout baseado em grades (linhas e colunas) |
| `inline-flex`   | Flexbox em linha |
| `inline-grid`   | Grid em linha |

### Exemplo:

```css
.ocultar {
  display: none;
}
```

```html
<p class="ocultar">Este parágrafo não será exibido.</p>
```

---

## Propriedade `visibility`

A propriedade `visibility` controla se o elemento é **visível ou oculto**, mas **mantém o espaço** ocupado por ele no layout.

### Valores:

| Valor        | Descrição |
|--------------|-----------|
| `visible`    | (Padrão) O elemento é visível |
| `hidden`     | O elemento é oculto, mas ainda ocupa espaço |
| `collapse`   | Usado principalmente em células de tabela (sem efeito em outros elementos) |

### Exemplo:

```css
.invisivel {
  visibility: hidden;
}
```

```html
<p class="invisivel">Este parágrafo está invisível, mas o espaço dele ainda existe.</p>
```

---

## Diferença entre `display: none` e `visibility: hidden`

| Propriedade           | Elemento renderizado? | Espaço ocupado? |
|-----------------------|------------------------|------------------|
| `display: none`       | Não                    | Não              |
| `visibility: hidden`  | Não                    | Sim              |

---

## Exemplos Práticos

### Exemplo com `display`

```css
.menu {
  display: flex;
  justify-content: space-between;
}
```

### Exemplo com `visibility`

```css
.banner {
  visibility: hidden;
}
```

---

## Conclusão

Tanto `display` quanto `visibility` são essenciais para controlar a renderização e o layout dos elementos em uma página web. Use `display: none` para remover completamente o elemento do fluxo da página e `visibility: hidden` para apenas escondê-lo mantendo o espaço.

---

**Dica:** Combine `display` com outras propriedades como `position`, `opacity`, e `z-index` para criar efeitos visuais avançados, como menus, animações e transições.

# Posicionamento (Position)

A propriedade `position` no CSS define como um elemento é posicionado no layout da página. Com ela, é possível tirar um elemento do fluxo normal do documento e posicioná-lo em qualquer lugar da tela ou dentro de um contêiner.

---

## Tipos de posicionamento

### 1. `static` (padrão)
- Valor padrão.
- Os elementos são posicionados conforme a ordem do documento.
- Propriedades como `top`, `left`, `right` e `bottom` **não funcionam**.

```css
.elemento {
  position: static;
}
```

---

### 2. `relative` (relativo)
- O elemento **mantém seu espaço original**, mas pode ser deslocado em relação a ele.
- As propriedades `top`, `right`, `bottom`, `left` **movem o elemento**, sem afetar os outros ao redor.

```css
.elemento {
  position: relative;
  top: 10px;
  left: 20px;
}
```

---

### 3. `absolute` (absoluto)
- Remove o elemento do fluxo do documento.
- O posicionamento é **relativo ao primeiro ancestral com `position: relative`, `absolute`, ou `fixed`**.
- Se nenhum ancestral for posicionado, será relativo ao `body` (ou `html`).

```css
.pai {
  position: relative;
}

.filho {
  position: absolute;
  top: 0;
  right: 0;
}
```

---

### 4. `fixed` (fixo)
- O elemento é posicionado **em relação à janela de visualização (viewport)**.
- Permanece fixo no lugar mesmo com o scroll da página.

```css
.header {
  position: fixed;
  top: 0;
  width: 100%;
}
```

---

### 5. `sticky` (grudento)
- Funciona como `relative` até que o scroll atinja um ponto específico.
- A partir daí, passa a se comportar como `fixed`.

```css
.menu {
  position: sticky;
  top: 0;
}
```

---

## Propriedades auxiliares

- `top`, `right`, `bottom`, `left`: definem o deslocamento de um elemento posicionado.
- `z-index`: define a ordem de sobreposição (quem fica na frente ou atrás).

```css
.elemento {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 10;
}
```

---

## Exemplo prático

```html
<div class="container">
  <div class="caixa1">Relativo</div>
  <div class="caixa2">Absoluto</div>
</div>
```

```css
.container {
  position: relative;
}

.caixa1 {
  position: relative;
  top: 10px;
  left: 10px;
}

.caixa2 {
  position: absolute;
  top: 0;
  right: 0;
}
```

---

## Conclusão

Dominar o posicionamento com `position` é essencial para criar layouts avançados em CSS. Com ele, é possível posicionar elementos de forma precisa e criar interfaces responsivas, fixas e dinâmicas.

---

> Dica: Use `position: relative` nos elementos-pai para facilitar o controle do posicionamento dos elementos-filhos com `absolute`.

# Flexbox (Layout Flexível)

Flexbox é um modelo de layout do CSS projetado para organizar elementos em **uma dimensão** (linha ou coluna). Ele facilita a criação de layouts mais responsivos, alinhados e com espaçamento controlado, sem a necessidade de usar floats ou posicionamento complexo.

---

## Como ativar o Flexbox

Para usar Flexbox, aplicamos `display: flex` em um contêiner. Todos os elementos filhos diretos se tornam **itens flexíveis**.

```css
.container {
  display: flex;
}
```

---

## Eixo principal e eixo cruzado

- **Eixo principal (main axis)**: a direção onde os itens são organizados (`row` ou `column`)
- **Eixo cruzado (cross axis)**: perpendicular ao eixo principal

---

## Principais propriedades do contêiner

### `flex-direction`
Define a direção dos itens no eixo principal.

| Valor         | Descrição                     |
|---------------|-------------------------------|
| `row`         | (padrão) Da esquerda para a direita |
| `row-reverse` | Da direita para a esquerda    |
| `column`      | De cima para baixo            |
| `column-reverse` | De baixo para cima        |

```css
.container {
  flex-direction: row;
}
```

---

### `justify-content`
Alinha os itens ao longo do eixo principal.

| Valor               | Descrição                          |
|---------------------|------------------------------------|
| `flex-start`        | Alinha ao início                   |
| `flex-end`          | Alinha ao fim                      |
| `center`            | Centraliza                         |
| `space-between`     | Espaço igual entre os itens        |
| `space-around`      | Espaço igual ao redor dos itens    |
| `space-evenly`      | Espaçamento uniforme em todos os lados |

```css
.container {
  justify-content: space-between;
}
```

---

### `align-items`
Alinha os itens no eixo cruzado.

| Valor         | Descrição                 |
|---------------|---------------------------|
| `stretch`     | (padrão) Estica os itens  |
| `flex-start`  | Alinha ao início          |
| `flex-end`    | Alinha ao final           |
| `center`      | Centraliza verticalmente  |
| `baseline`    | Alinha pelas linhas de base do texto |

```css
.container {
  align-items: center;
}
```

---

### `flex-wrap`
Define se os itens devem quebrar a linha.

| Valor         | Descrição                     |
|---------------|-------------------------------|
| `nowrap`      | (padrão) Todos na mesma linha |
| `wrap`        | Permite que os itens quebrem linha |
| `wrap-reverse`| Quebra em sentido reverso     |

```css
.container {
  flex-wrap: wrap;
}
```

---

## Propriedades dos itens

### `flex`
Atalho para `flex-grow`, `flex-shrink` e `flex-basis`.

```css
.item {
  flex: 1;
}
```

### `align-self`
Permite sobrepor o `align-items` individualmente para um item.

```css
.item-especial {
  align-self: flex-end;
}
```

### `order`
Controla a ordem visual dos itens.

```css
.item-a {
  order: 2;
}

.item-b {
  order: 1;
}
```

---

## Exemplo Prático

```html
<div class="container">
  <div class="item">1</div>
  <div class="item">2</div>
  <div class="item">3</div>
</div>
```

```css
.container {
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 200px;
}
.item {
  background: #ccc;
  padding: 20px;
}
```

---

## Conclusão

O Flexbox oferece uma maneira poderosa, simples e responsiva de organizar layouts em uma única dimensão. É ideal para alinhamento de menus, galerias, componentes centrais, entre outros.

---

> Dica: Para layouts bidimensionais (linhas e colunas), considere usar o CSS Grid.

# Responsividade com Media Queries

As media queries (consultas de mídia) permitem adaptar o layout de uma página a diferentes tamanhos de tela, dispositivos e orientações. São fundamentais para criar **sites responsivos** — que funcionam bem em celulares, tablets, notebooks e monitores grandes.

---

## Sintaxe básica

```css
@media (condição) {
  /* Regras CSS aqui */
}
```

Exemplo:

```css
@media (max-width: 768px) {
  body {
    background-color: lightgray;
  }
}
```

Neste exemplo, o fundo será cinza claro apenas em telas com **largura máxima de 768px**.

---

## Exemplos comuns de Media Queries

### Por largura da tela

```css
/* Telas pequenas (celulares) */
@media (max-width: 480px) {
  .menu { display: none; }
}

/* Telas médias (tablets) */
@media (min-width: 481px) and (max-width: 1024px) {
  .menu { display: block; font-size: 18px; }
}

/* Telas grandes (notebooks e desktops) */
@media (min-width: 1025px) {
  .menu { font-size: 20px; }
}
```

---

### Por orientação da tela

```css
@media (orientation: portrait) {
  body {
    flex-direction: column;
  }
}

@media (orientation: landscape) {
  body {
    flex-direction: row;
  }
}
```

---

## Breakpoints comuns

Breakpoints são larguras de tela onde o layout muda:

| Tipo de dispositivo | Largura (aproximada)  |
|---------------------|------------------------|
| Celular pequeno     | até 480px              |
| Celular grande      | até 768px              |
| Tablet              | até 1024px             |
| Laptop/PC           | 1025px ou mais         |

---

## Uso com layout flexível

```css
.container {
  display: flex;
  flex-direction: row;
}

@media (max-width: 768px) {
  .container {
    flex-direction: column;
  }
}
```

Nesse exemplo, os elementos se alinham em linha em telas maiores e em coluna nas telas menores.

---

## Dicas

- Sempre teste em múltiplos dispositivos ou use o modo responsivo do navegador.
- Utilize unidades relativas (`em`, `%`, `vw`, `vh`) sempre que possível.
- Evite definir muitos breakpoints: use os essenciais para seu layout.

---

## Conclusão

Media Queries são a base da responsividade em CSS moderno. Elas permitem personalizar a aparência de uma página conforme o tamanho ou características do dispositivo, melhorando a experiência do usuário em qualquer plataforma.

---

> Dica: Combine Media Queries com Flexbox ou Grid para criar layouts totalmente adaptáveis.

# Animações e Transições

O CSS oferece dois recursos principais para criar efeitos visuais dinâmicos: **transições** e **animações**. Ambos ajudam a melhorar a experiência do usuário ao tornar as interações mais suaves e visuais.

---

## Transições (`transition`)

As transições permitem que mudanças em propriedades CSS ocorram de forma suave, em vez de instantaneamente.

### Sintaxe básica

```css
.seletor {
  transition: propriedade duração função-tempo atraso;
}
```

### Exemplo

```css
.botao {
  background-color: blue;
  transition: background-color 0.3s ease-in-out;
}

.botao:hover {
  background-color: darkblue;
}
```

### Propriedades comuns utilizadas

- `transition-property`
- `transition-duration`
- `transition-timing-function`
- `transition-delay`

---

## Animações (`@keyframes` e `animation`)

As animações permitem controlar as mudanças de estilo em múltiplos estágios.

### Definindo uma animação com `@keyframes`

```css
@keyframes exemplo {
  0% { transform: translateX(0); }
  100% { transform: translateX(100px); }
}
```

### Aplicando a animação

```css
.elemento {
  animation: exemplo 1s ease-in-out infinite alternate;
}
```

### Propriedades da animação

- `animation-name`
- `animation-duration`
- `animation-timing-function`
- `animation-delay`
- `animation-iteration-count`
- `animation-direction`
- `animation-fill-mode`
- `animation-play-state`

---

## Diferença entre Transições e Animações

| Característica        | Transições                    | Animações                         |
|-----------------------|-------------------------------|-----------------------------------|
| Disparo automático    | Não (precisa de evento)       | Sim                               |
| Etapas                | Início e fim                  | Múltiplas etapas                  |
| Controle              | Limitado                      | Completo com `@keyframes`         |
| Repetição             | Não                           | Sim (com `animation-iteration`)  |

---

## Exemplo prático de animação contínua

```css
@keyframes rotacionar {
  0% { transform: rotate(0deg); }
  100% { transform: rotate(360deg); }
}

.icone {
  animation: rotacionar 2s linear infinite;
}
```

---

## Dicas importantes

- Prefira `transform` e `opacity` para melhor desempenho.
- Utilize `ease-in`, `ease-out`, `ease-in-out` ou `linear` para controlar o ritmo.
- Teste os efeitos em navegadores diferentes para garantir compatibilidade.

---

## Conclusão

As transições e animações CSS tornam os sites mais modernos e envolventes. Quando bem utilizadas, contribuem para uma experiência de navegação mais intuitiva, sem comprometer o desempenho.

---

> Dica: use ferramentas como o DevTools para depurar e visualizar animações em tempo real.

# Desenvolvimento Responsivo e Mobile First

O desenvolvimento responsivo é uma abordagem do design web que visa criar páginas que se adaptam a diferentes tamanhos de tela e dispositivos. Já o conceito **Mobile First** significa começar o design e o desenvolvimento **priorizando dispositivos móveis** (menores) antes de adaptá-lo para telas maiores.

---

## O que é Desenvolvimento Responsivo?

Um site responsivo utiliza técnicas de layout fluido, media queries e unidades flexíveis para garantir que o conteúdo seja legível e funcional em qualquer dispositivo: smartphones, tablets, notebooks ou monitores grandes.

### Características principais:

- Layouts que se ajustam dinamicamente ao tamanho da tela
- Elementos redimensionáveis
- Tipografia flexível
- Imagens e mídias adaptativas
- Navegação simplificada em telas pequenas

---

## O que é Mobile First?

O Mobile First é uma filosofia que recomenda **começar o desenvolvimento para dispositivos móveis**, com telas e capacidades limitadas, e então expandir para telas maiores com media queries.

### Vantagens do Mobile First:

- Melhor performance em dispositivos móveis
- Experiência de usuário otimizada desde o início
- Facilita a priorização de conteúdo
- Promove simplicidade no design

---

## Exemplo de abordagem Mobile First com CSS

```css
/* Estilos base para mobile */
body {
  font-size: 16px;
  padding: 10px;
}

/* Estilos para tablets e desktops maiores */
@media (min-width: 768px) {
  body {
    font-size: 18px;
    padding: 20px;
  }
}

@media (min-width: 1024px) {
  body {
    font-size: 20px;
    max-width: 1200px;
    margin: auto;
  }
}
```

Neste exemplo, os estilos são definidos primeiro para dispositivos móveis e vão sendo ajustados para telas maiores com `@media`.

---

## Boas práticas no desenvolvimento responsivo

- Use **unidades relativas** como `%`, `em`, `rem`, `vw`, `vh`
- Priorize layouts com **Flexbox** ou **CSS Grid**
- Use **media queries** para adaptar estilos
- Otimize **imagens e fontes** para carregamento rápido
- Teste em múltiplos dispositivos ou com ferramentas de simulação (DevTools)

---

## Ferramentas úteis

- Google Chrome DevTools (modo responsivo)
- Frameworks: Bootstrap, Tailwind CSS, Foundation
- Testes: BrowserStack, Responsively App

---

## Conclusão

Desenvolver de forma responsiva com abordagem Mobile First é essencial para garantir que seu site funcione bem em qualquer dispositivo. Isso melhora a acessibilidade, usabilidade e a performance geral, oferecendo uma experiência consistente ao usuário.

---

> Lembre-se: um bom design mobile normalmente resulta em um bom design para desktop — o contrário nem sempre é verdade.

## 4.18 Elementos flutuantes

- Propriedade FLOAT
- E usada para mover um elemento para uma posicao de forma que ele fique agrupada na mesma estrutura, o elemento fica livre ou flutuante. A propriedade FLOAT pode ser:
- none - Ao definir a propriedade com esse valor o elemento nao pode flutuar, esse e o padrao de todo elemento;
- left - Ao definir a propriedade com esse valor o elemento flutua para o lado Esquerdo;
- right - Ao definir a propriedade com esse valor o elemento flutua para o lado Direito;
- inherit - Ao definir a propriedade com esse valor o elemento flutua de acordo com o elemento pai;
- O exemplo a seguir mostra como ajustar 3 elementos em uma mesma linha:

```md
<div class="coluna">
<div style="float:left; width: 33%;">Texto a esquerda</div>
<div style="float:left; width: 33%;">Texto no centro</div>
<div style="float:right; width: 33%;">Texto a direita</div>
</div>
```
## 5. Layout do site

- Os layouts sao estruturas de formato da pagina, cada pagina segue um esquema que pode favorecer a leitura
- Guia Pratico de HTML & CSS - Pagina 15
- e consulta. Um site e frequentemente dividido em cabecalhos, menus, conteudo e rodape:
![Guia Prát_20250504_005120_39](foto/Guia%20Prát_20250504_005120_39.png)

## 5.1. Templates

- Os templates sao modelos organizados de paginas web que podem ser usados como base para quaisquer paginas que precisamos criar.

## 5.2. Modelando o Cabecalho

- A primeira peca que vamos criar e o Cabecalho, vamos escrever o seguinte cabecalho:
```md
<style>
.header {
padding: 30px;
text-align: center;
background: white;
}
</style>
<div class="header">
<h1>Meu Template de Site</h1>
<p>Uma breve descricao do meu template</p>
</div>
```
![Guia Prát_20250504_005120_40](foto/Guia%20Prát_20250504_005120_40.png)
## 5.3. Modelando o Menu

- Assim como todo site vamos criar uma barra de LINKS para facilitar o acesso aos recursos do nosso site. Nesse modelo vamos criar os seguintes links:
- Principal Vai nos levar a pagina principal index.html;
- Blog Vamos direcionar para um blog, na mesma pagina;
- Sobre Vamos direcionar para um blog, na mesma pagina;
- Login Vamos abrir outra pagina para realizar o login.

```md
<html>
<head>
<title>Exemplos Layout</title>
<style>
/* Organizando todo o site em caixa */
{
box-sizing: border-box;
}
/* Ajustes em todo site */
body {
font-family: Arial;
padding: 10px;
background: #f1f1f1;
}
/* Ajustes no cabecalho principal */
.header {
padding: 30px;
text-align: center;
background: white;
}
/* Ajustando o tamanho do cabecalho */
.header h1 {
font-size: 50px;
}
/* Ajustando a cor e escondendo o conteudo excedido */
.topnav {
overflow: hidden;
background-color: #333;
}
/* Ajuste nos LINKS do Menu principal */
.topnav a {
float: left;
display: block;
color: #f2f2f2;
text-align: center;
padding: 14px 16px;
text-decoration: none;
}
/* Mude a cor ou passar o mouse */
.topnav a:hover {
background-color: #ddd;
color: black;
}
</style>
</head>
<body>
<div class="header">
<h1>Meu Template de Site</h1>
<p>Uma breve descricao do meu template</p>
</div>
<div class="topnav">
<a href="#">Principal</a>
<a href="#">Blog</a>
<a href="#">Sobre</a>
<a href="#" style="float:right">Login</a>
</div>
</body>
</html>
```
![Guia Prát_20250504_005120_41](foto/Guia%20Prát_20250504_005120_41.png)

## 5.4. Modelando as colunas centrais

- Nesse local deve ficar as informacoes principais do seu site, nesse caso vamos dividi-la em 2 colunas:

```md
<div class="row">
<div class="leftcolumn">
<div class="card">
<h2>Titulo da informacao principal</h2>
<h5>Uma breve descricao da noticia ou informacao, Algum lugar 30/09/2018.</h5>
<div class="fakeimg" style="height:200px;">Imagem</div>
<p>Um breve resumo ...</p>
<p>Mais algumas informacoes sobre o que voce quer falar.</p>
</div>
</div>
<div class="rightcolumn">
<div class="card">
<h2>Sobre</h2>
<div class="fakeimg" style="height:100px;">Imagem</div>
<p>Em breve resumo da sua vida.</p>
</div>
<div class="card">
<h3>Informacoes principais</h3>
<div class="fakeimg"><p>Imagem</p></div>
<div class="fakeimg"><p>Imagem</p></div>
<div class="fakeimg"><p>Imagem</p></div>
</div>
<div class="card">
<h3>Siga-me</h3>
<p>Adicione suas redes sociais favoritas</p>
</div>
</div>
</div>
```
## 5.5. Modelando o Rodape

- E por fim adicionamos o rodape para que possamos adicionar informacoes de contatos, mapas e um pequeno resumo da pagina web.

```md
<div class="footer">
<h2>Rodape</h2>
</div>
```
- Agora o codigo completo:

```md
<html>
<head>
<title>Exemplos Layout</title>
<style>
/* Organizando todo o site em caixa */
{
box-sizing: border-box;
}
/* Ajustes em todo site */
body {
font-family: Arial;
padding: 10px;
background: #f1f1f1;
}
/* Ajustes no cabecalho principal */
.header {
padding: 30px;
text-align: center;
background: white;
}
/* Ajustando o tamanho do cabecalho */
.header h1 {
font-size: 50px;
}
/* Ajustando a cor e escondendo o conteudo excedido */
.topnav {
overflow: hidden;
background-color: #333;
}
/* Ajuste nos LINKS do Menu principal */
.topnav a {
float: left;
display: block;
color: #f2f2f2;
text-align: center;
padding: 14px 16px;
text-decoration: none;
}
/* Mude a cor ou passar o mouse */
.topnav a:hover {
background-color: #ddd;
color: black;
}
/* Left column */
.leftcolumn {
float: left;
width: 75%;
}
/* Right column */
.rightcolumn {
float: left;
width: 25%;
background-color: #f1f1f1;
padding-left: 20px;
}
.fakeimg {
background-color: #aaa;
width: 100%;
padding: 20px;
}
/* Add a card effect for articles */
.card {
background-color: white;
padding: 20px;
margin-top: 20px;
}
/* Clear floats after the columns */
.row:after {
content: "";
display: table;
clear: both;
}
/* Rodape */
.footer {
padding: 20px;
text-align: center;
background: #ddd;
margin-top: 20px;
}
/* Transformando em um Layout responsivo - telas medias */
@media screen and (max-width: 800px) {
.leftcolumn,
.rightcolumn {
width: 100%;
padding: 0;
}
}
/* Transformando em um Layout responsivo - telas menores */
@media screen and (max-width: 400px) {
.topnav a {
float: none;
width: 100%;
}
}
</style>
</head>
<body>
<div class="header">
<h1>Meu Template de Site</h1>
<p>Uma breve descricao do meu template</p>
</div>
<div class="topnav">
<a href="#">Principal</a>
<a href="#">Blog</a>
<a href="#">Sobre</a>
<a href="#" style="float:right">Login</a>
</div>
<div class="row">
<div class="leftcolumn">
<div class="card">
<h2>Titulo da informacao principal</h2>
<h5>Uma breve descricao da noticia ou informacao, Algum lugar 30/09/2018.</h5>
<div class="fakeimg" style="height:200px;">Imagem</div>
<p>Um breve resumo ...</p>
<p>Mais algumas informacoes sobre o que voce quer falar.</p>
</div>
</div>
<div class="rightcolumn">
<div class="card">
<h2>Sobre</h2>
<div class="fakeimg" style="height:100px;">Imagem</div>
<p>Em breve resumo da sua vida.</p>
</div>
<div class="card">
<h3>Informacoes principais</h3>
<div class="fakeimg"><p>Imagem</p></div>
<div class="fakeimg"><p>Imagem</p></div>
<div class="fakeimg"><p>Imagem</p></div>
</div>
<div class="card">
<h3>Siga-me</h3>
<p>Adicione suas redes sociais favoritas</p>
</div>
</div>
</div>
<div class="footer">
<h2>Rodape</h2>
</div>
</body>
</html>
```
- Esse e outros codigos voce pode baixar clicando [AQUI](https://drive.google.com/file/d/1185bjNk50vo_X6AjbGNlfpMlghXQ1ey9/view?usp=drivesdk)
- Veja o site:
![Guia Prát_20250504_005120_42](foto/Guia%20Prát_20250504_005120_42.png)

## 6. Lista de exercicios para praticar

- E hora de praticar! Nesse capitulo voce vai baixar um pacote de exercicios sem formatacao e seu trabalho e deixa-los igual a imagem que ficara exposto em cada capitulo exemplo. Em cada pasta esta o exercicio sem formatacao e com formatacao, e importante que voce nao use o exercicio resolvido e sim tente construir seguindo sua intuicao e tudo que aprendeu no decorrer desse livro.
- Baixe os exercicios nesse .

## [Link](https://drive.google.com/file/d/1185bjNk50vo_X6AjbGNlfpMlghXQ1ey9/view?usp=drivesdk)

## 6.1. Exercicio - Crie um site de Loja

- A criacao de uma loja ou e-commerce e um dos principais recursos que todo web design deve aprender, e
- nesse exercicio vou guiar voce a construi-lo descrevendo os principais recursos que deve utilizar para construir e fique igual ao que esta na imagem.
- Abra a pasta Loja;
- Utilizando seu editor de texto abra o arquivo exercicio.html;
- Comece pelo HEAD:

## 3.1. Adicione um tag head e um title, que deve esta escrito a seguinte mensagem Meu primeiro e-commerce

- Ajustando o cabecalho da Loja, modifique a div com a classe header da seguinte forma:

## 4.1. O texto deve ficar centralizado;
## 4.2. Adicione um espaco entre a borda e o conteudo no tamanho 30;
## 4.3. Altere a cor de fundo para branco;
- Vamos ajustar a barra de navegacao, modifique a div com a classe topnav da seguinte forma:
## 5.1. Na ancora (tag a) com o texto carrinho de compras adicione um estilo inline para ele flutuar a direita;
## 5.2. Insira a image compra.png da pasta imagens ao lado do elemento span do carrinho de compras;
## 5.3. Essa imagem deve ter o tamanho 22 e com alinhamento vertical do tipo middle;
## 5.4. A class topnav deve flutuar a esquerda;
## 5.5. A class topnav deve ter um alinhamento centralizado;
## 5.6. A class topnav deve ter uma cor escura, usando o codigo #f2f2f2;
## 5.7. A class topnav deve ter a decoracao do texto com valor NONE;
## 5.8. A class topnav deve ter o espaco interno (padding) com valor de esquerda de 14 e direita 16;
- Agora vamos ajustar os cartoes de venda, modifique a div com a classe sellcard da seguinte forma:
## 6.1. A class sellcard deve flutuar a esquerda;
## 6.2. A class sellcard deve ter a largura (width) de 23.40%;
## 6.3. A class sellcard deve ter um espaco externo (propriedade margin) de tamanho 10;
## 6.4. A class sellcard img deve ter a largura (width) de 80%;
## 6.5. A class sellcard img deve ter a o espaco externo (propriedade margin) com valor auto;
- Agora vamos ajustar a descricao do nosso cartao, modifique a p com a classe descricao da seguinte forma:
## 7.1. Deve ter o alinhamento de texto centralizado;
## 7.2. Deve ter o tamanho da fonte no valor de 15;
## 7.3. Deve ter a familia da fonte Helvetica;
## 7.4. Deve ter o estilo de fonte normal;
## 7.5. Deve ter a espessura da fonte no valor de 400;
- Agora vamos ajustar a descricao do nosso cartao, modifique a p com a classe valor da seguinte forma:
## 8.1. Deve ter o alinhamento de texto centralizado;
## 8.2. Deve ter o tamanho da fonte no valor de 0.8 proporcional;
## 8.3. Deve ter a espessura da fonte no valor de
- Guia Pratico de HTML & CSS - Pagina 21
- bold;
## 9. Agora vamos ajustar a descricao do nosso cartao, modifique a p com a classe compra da seguinte forma:
## 9.1. Deve ter o alinhamento de texto centralizado;
- Tente executar cada item passo a passo, consultando o livro quando voce nao lembrar o nome do elemento ou da propriedade. E o mais importante NAO DESISTA!
![Guia Prát_20250504_005120_43](foto/Guia%20Prát_20250504_005120_43.png)
## 6.2. Crie um site de Pizzaria
- Nesse exercicio voce tera que criar a pagina que esta na imagem sem nenhuma instrucao. Utilize o que voce aprendeu no exercicio anterior e tente construir essa pagina sem recorrer ao exercicio resolvido.
![Guia Prát_20250504_005120_45](foto/Guia%20Prát_20250504_005120_45.png)
![Guia Prát_20250504_005120_44](foto/Guia%20Prát_20250504_005120_44.png)
## 7. O que fazer agora?
- Agora que voce ja conhece uma parte importante para iniciar sua carreira como web design ou desenvolvedor web e necessario voce aprender a criar paginas mais bonitas e buscar fazer o usuario interagir com elas, e para isso eu indico a voce continuar seus estudos com os seguintes livros:
- Guia pratico Javascript
- Esse livro mostra os primeiros passo para voce construir paginas que respondem ao usuario e podemos criar um site vivo, com interacoes e com animacoes!
- Guia pratico PHP
- Esse livro apresenta seu primeiro contato com uma estrutura de sistema web, permitindo assim voce armazenar informacoes na web, criar sistemas de controle de estoque, criar um jogo simples e muito mais.
## 8. Como ganhar dinheiro?
- Com o que aprendi nesse livro e possivel ganhar dinheiro? A resposta e sim! Muitos site que temos na internet hoje em dia nao precisa de nenhuma estrutura complexa, apenas de um site estatico onde algumas informacoes importantes possam ser divulgadas! Quer um exemplo de site que faz sucesso sem ter nenhuma interacao usando Javascript (front-end) ou PHP (back-end)? Entre no site da esse site tem a premissa de que qualquer um pode criar um site para chamar de seu e todas as paginas sao estaticas. Entre os planos que eles oferecem variam entre R$ 10 e R$ 60 por mes, porem nem todo mundo quer ficar mantendo e atualizando esse site. Ou nem todo mundo aprende como funciona esse site, porque nao tem conhecimento basico de HTML e CSS e e ai que voce entra. Isso quer dizer que VOCE pode fazer isso para eles!
- Por isso vou te dar algumas dicas de ouro. Utilize o conhecimento que voce adquiriu nesse livro para criar uma pagina simples PARA VOCE e mostre a todos que voce e capaz de fazer! A partir daqui voce cria uma pagina gratuita nesse site e divulga no seu Instagram/Facebook, monte uma pagina profissional para que outras pessoas tenham interesse de querer ver.
- Guia Pratico de HTML & CSS - Pagina 22
- Depois veja algum estabelecimento perto da sua casa, pode ser um mercado pequeno, uma loja de roupas, um acougue, uma vendedora porta a porta, etc.
- Fale com o dono(a) e ofereca seu servico, diga a ele que voce pode construir uma pagina web para ele por apenas R$ 50 por mes; Diga que ela pode atrair muito mais clientes com essa pagina e que com essa pagina ela pode colocar o no do Whatsapp, facebook e muito mais. Fale com pelo menos 100 estabelecimentos, na media voce recebera cerca de 80% de NAO! Com apenas esses 20%, que podem ser 20 lojas cada uma voce cobra R$ 50 e voce tera em 1 mes R$ 2.000,00 !!!! Voce nunca mais vai precisar trabalhar em outro lugar.
- O mais importante nao e o dinheiro que pode fazer e sim que voce PODE FAZER, independente de como fara a maior dica que eu te dou e, FACA!! Nao perca tempo.
## 9. Agradecimentos
- Obrigado por se interessar no conteudo desse livro, espero que ele tenha atendido sua expectativa sobre como funciona uma estrutura HTML e CSS e seus principais recursos, e que tenha aprendido ou ampliando seus conhecimentos nessa area. Espero ter facilitado sua caminhada e aproveito para deixar essa ultima dica, nao pare de aprender, pois o maior recurso do mundo e o conhecimento e com ele podemos transformar todos ao nosso redor.
- Um pedido especial
- Se voce gostou desse livro, eu gostaria de te pedir apenas mais um minuto do seu tempo para ir na pagina desse livro no Site da Amazon e clicar no botao Escreva uma Avaliacao e deixar uma avaliacao, pois isso vai me ajudar a identificar os meus acertos e minhas falhas.
- Peco tambem que me acompanhe no .
- E me envie um e-mail (devacademybr@gmail.com) caso tenha alguma critica ou sugestao.
- E por fim indique esse livro para um amigo, se voce gostou ele tambem deve gostar e aproveitar esse conteudo e voces podem ate fazer alguma parceria.
- Espero que esta conversao para Markdown seja útil! Se precisar de algo mais ou tiver outras instruções para "melhorar" o conteúdo, é só dizer.
-
