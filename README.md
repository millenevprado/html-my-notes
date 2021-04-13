

![capa](imagens/capa.png)

<h2 align = "justify"> Este repositório é um compilado do conhecimento que estou adquirindo ao estudar HTML. Ele contém minhas anotações pessoais, exercícios, insights e resumos sobre HTML e serve como um guia para auxiliar e direcionar os meus estudos! &#x1F4DA </h2>

<h4 align = "justify">CURSOS QUE ESTOU FAZENDO/FIZ E QUE SERVEM DE BASE PARA O DESENVOLVIMENTO DESSE COMPILADO: </h4> 

* CS50's Introduction to Computer Science - Harvard University
* CS50's Web Programming with Python and JavaScript - Harvard University
* HTML5 e CSS3 - Curso em Vídeo 
* HTML Web Developer - Digital Innovation One
* Avanade Angular Developer - Digital Innovation One



> OBSERVAÇÃO: algumas partes deste material foram traduzidas diretamente do Tutorial HTML da [w3schools.com](https://www.w3schools.com/html/default.asp). As referências completas estão disponíveis [aqui](#references).



# ÍNDICE 

- [INTRODUÇÃO](#introduction)
- [TEXTO](#text)
- [LISTAS](#lists)

<hr>


<h1> <a name = "introduction"></a>INTRODUÇÃO</h1>

<p align = "justify">HTML (HyperText Markup Language ou Linguagem de Marcação de HiperTexto) é uma linguagem de marcação usada para criar páginas web. É o bloco de construção mais básico da web que define o significado e a estrutura do conteúdo da página. Elementos HTML são empregados para descrever a <strong>estrutura</strong> da página, informando ao navegador como exibir o <strong>conteúdo</strong>. Esses elementos identificam partes do conteúdo como "título", "parágrafo", "link" etc.</p>

<p align = "justify"> O conteúdo de uma página web é criado em HTML. A organização e o visual desse conteúdo, posição dos componentes, cores dos textos e tudo mais é definido em CSS (Cascading Style Sheets ou Folhas de Estilo em Cascata). O menu de navegação e as interações em geral da página, por sua vez, são desenvolvidos em JavaScript.</p>

![funcionamento_pag_web](imagens/introduction/pagweb_func.png)



## ELEMENTOS HTML

<p align = "justify"> Os elementos são definidos por uma tag (marcação) de abertura, algum conteúdo, e uma tag de fechamento.  As tags agem como containers, dizendo algo sobre as informações que estão entre suas tags de abertura e fechamento (DUCKETT, 2011). </p>

![elemento_html](imagens/introduction/elemento_html.png)

> <strong>OBSERVAÇÃO:</strong> alguns elementos HTML não têm conteúdo. Eles são chamados de elementos vazios e não   possuem tag de fechamento.

### Atributos dos Elementos HTML

<p align = "justify">Os elementos HTML podem ter atributos, que irão fornecer informações adicionais sobre eles. Esses atributos são sempre especificados na tag de abertura e, geralmente, vêm em pares de nome/valor: <strong>nome = "valor"</strong>. </p>

![atributo_elemento_html](imagens/introduction/atributo_elemento_html.png)

## ESTRUTURA DA PÁGINA HTML

Uma página HTML possui a seguinte estrutura:

![](imagens/introduction/estrutura_html.png)

Código básico de um documento HTML:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

<ol align = "justify">
    <li> <code>!DOCTYPE html</code>: define que é um documento HTML5. </li> 
    <li> <code>html</code>: é o "elemento raiz" de uma página HTML e envolve o conteúdo da página inteira (aqui, estamos indicando também que o conteúdo da página será no idioma Português do Brasil).</li>
    <li> <code>head</code>: é o elemento que contém meta informações sobre a página HTML, ele atua como container para todo o conteúdo da página que não é visível para o usuário.</li>
    <li> <code>meta charset="UTF-8"</code>:é o elemento define o tipo da codificação dos caracteres que o documento deve usar, neste caso, para o tipo UTF-8, que inclui a maioria dos caracteres das línguas humanas escritas. </li>
    <li> <code>meta name="viewport" content="width=device-width, initial-scale=1.0"</code>: indica que o conteúdo aparecerá, por padrão, ocupando todo o espaço disponível da tela e com uma escala de 1:1.</li>
    <li> <code>tittle</code>: é o elemento que especifica um título para a página HTML (mostrado na barra de título do navegador ou na guia da página).</li>
    <li> <code>body</code>: é o elemento que vai definir o corpo do documento. É um container para todo o conteúdo visível, como títulos, parágrafos, imagens, hiperlinks, tabelas, listas, etc. </li>
</ol>


## CRIANDO MINHA PRIMEIRA PÁGINA

Seguindo a estrutura básica do documento HTML, mostrado acima, podemos criar a nossa primeira página web:

![](imagens/introduction/primeira_pag.png)

<strong>VER CÓDIGO:</strong> [minha primeira página web](https://github.com/millenevprado/html-my-notes/blob/main/exemplos/index.html).

<hr>

<h1> <a name = "text"></a>TEXTO</h1>

<p align = "justify"> Como vimos, para criar páginas web, nós adicionamos tags (marcação) ao conteúdo da página. Essas tags fornecem significado extra e permitem que os navegadores mostrem aos usuários a estrutura apropriada para a página. Existem dois tipos de marcação: 
<ul align = "justify">
    <li>marcação estrutural: elementos utilizados para descrever títulos e parágrafos dos textos (foco na forma);</li>
    <li>marcação semântica: fornece informações extras, como onde a ênfase é colocada em uma frase, que algo que você escreveu é uma citação, o significado das siglas, etc. (foco no significado) (DUCKET, 2011).</li>
</ul></p>

> A maior mudança do HTML4 para o HTML5 foi o acréscimo da semântica aos elementos!

## TÍTULOS (<em>HEADINGS</em>)

<p align = "justify"> Títulos em HTML (conhecidos como <em>headings</em>) possuem <strong>SEIS NÍVEIS</strong> de hierarquia que são definidos com as tags &lt;h1&gt; a &lt;h6&gt;.  Um &lt;h1&gt; significa que esse é um assunto principal, &lt;h2&gt; é um sub-assunto do &lt;h1&gt; e assim sucessivamente.</p>

```html
<h1>TÍTULO PRINCIPAL</h1>
<h2>TÍTULO NÍVEL 2</h2>
<h3>TÍTULO NÍVEL 3</h3>
<h4>TÍTULO NÍVEL 4</h4>
<h5>TÍTULO NÍVEL 5</h5>
<h6>TÍTULO NÍVEL 6</h6>
```

<strong>VER CÓDIGO:</strong> [exemplo empregando títulos](https://github.com/millenevprado/html-my-notes/blob/main/exemplos/titulos.html).

## PARÁGRAFOS

<p align = "justify">Para criar um parágrafo, basta colocar o conteúdo dentro da tag &lt;p&gt;&lt;/p&gt;. Um parágrafo sempre começa em uma nova linha. Com HTML, você não pode alterar a exibição adicionando espaços extras ou linhas extras em seu código HTML. O navegador removerá automaticamente quaisquer espaços e linhas extras quando a página for exibida. Por exemplo: </p>

```html
<p>
    Esse parágrafo
    contém várias linhas
    e    vários espaços
    no      código-fonte
    mas o navegador os
    ignora. 
</p>
```

![](imagens/text/espaco.png)

### Inserindo quebra de linha

<p align = "justify">Para  quebrar uma linha (criar uma nova linha), sem começar um novo parágrafo, podemos usar a tag &lt;br&gt;, que é uma tag vazia, ou seja, não tem tag de fechamento. A tag &lt;br&gt; significa literalmente "quebre a linha" (break row). Por exemplo: </p>

```html
<p>
    Para quebrar o texto em algum lugar específico <br> 
    como esse aqui, por exemplo, podemos usar a tag &lt;br&gt;.
</p>
```

![](imagens/text/usando_tag_br.png)

> <strong>OBSERVAÇÃO:</strong>  &lt e &gt são usados no código acima para representar os caracteres (<) e (>) reservados em HTML e são conhecidos como HTML entities. Saiba mais em: [HTML Entities](https://www.w3schools.com/html/html_entities.asp).

### Inserindo uma linha horizontal

<p align = "justify">Podemos também usar a tag &lt;hr&gt; para definir uma quebra temática em uma página HTML, que exibe uma linha horizontal:</p> 


![](imagens/text/usando_tag_hr.png)

### Mantendo a formatação do texto

<p align = "justify">E se, por exemplo, eu quisesse escrever um poema, com espaços em branco e quebras de linhas, como proceder nesse caso? É simples, podemos utilizar, o elemento &lt;pre&gt;  que define o texto pré-formatado. Por exemplo: </p>



```html
<pre>
    Rosas são vermelhas
    
    Violetas são azuis
    
    Eu preciso aprender HTML
    
    em nome de Jesus.
</pre>
```

![usando_tag_pre](imagens/text/usando_tag_pre.png)

<strong>VER CÓDIGO:</strong> [exemplos de parágrafos, quebra de linha, linha horizontal e texto pré-formatado](https://github.com/millenevprado/html-my-notes/blob/main/exemplos/paragrafos.html).

## ELEMENTOS SEMÂNTICOS

<p align = "justify">Elementos semânticos são elementos que possuem significado. O objetivo deles é descrever o conteúdo de páginas da web, tanto para o browser quanto para o desenvolvedor, com mais precisão (focar no significado). Não devemos usá-los para alterar a aparência do texto (forma), para isso temos o CSS. </p>

![](imagens/text/pq_elementos_semanticos.png)

### Strong e Emphasis

<p align = "justify">O elemento HTML &lt;strong&gt; define o texto com grande importância. O conteúdo interno é normalmente exibido em negrito. </p>

```html
<strong>Este texto é importante</strong>   

<p>Este brinquedo pode ter peças pequenas e <strong>não</strong>
   é adequado para crianças menores de 5 anos.</p>
```

![](imagens/text/usando_tag_strong.png)



<p align = "justify">O elemento HTML &lt;em&gt; define o texto enfatizado. O conteúdo interno é normalmente exibido em itálico. Por exemplo, um leitor de tela pronunciará as palavras em &lt;em&gt; com ênfase, usando ênfase verbal. </p>

```html
<em>Este texto é enfatizado</em>
```

![](imagens/text/usando_tag_em.png)



### Citações

<p align = "justify">O elemento HTML &lt;blockquote&gt; define uma seção citada de outra fonte. Os navegadores geralmente recuam os elementos &lt;blockquote&gt;:    

```html
<p>
    Os navegadores geralmente identam os elementos &lt;blockquote&gt;,
    como podemos nesse exemplo:
</p>

<blockquote cite = "http://www.worldwildlife.org/who/index.html">
    Há 50 anos, o WWF protege o futuro da natureza.
    A principal organização de conservação do mundo,
    WWF trabalha em 100 países e é apoiado por
    1,2 milhão de membros nos Estados Unidos e
    perto de 5 milhões globalmente.
</blockquote>
```

![](imagens/text/usando_blockquote.png)

<p align = "justify">A tag HTML &lt;q&gt; define uma citação curta. Os navegadores normalmente inserem aspas entre a citação. </p>

```html
<p>
    Como disse o mestre jedi Obi Wan Kenobi para Luke Skywalker, 
    no Episódio IV, <q>may the force be with you.</q>
</p>
```

![](imagens/text/usando_q.png)

<p align = "justify">O elemento HTML &lt;abb&gt; é empregado para definir uma abreviatura ou acrônimo, como "HTML", "CSS". Essas abreviações de marcação podem fornecer informações úteis para navegadores, sistemas de tradução e mecanismos de pesquisa.</p>

```html
<p>
    Este compilado contém informações, resumos e exemplos 
    de todo conhecimento que estou adquirindo ao estudar
    <abbr title="Hyper Text Markup Language">HTML.</abbr>
</p>
```



<p align = "justify">Quando estamos referenciando um trabalho como um livro, filme ou artigo de pesquisa, o elemento &lt;cite&gt; pode ser usado para indicar a origem da citação. O texto no elemento &lt;cite&gt; geralmente é renderizado em itálico. </p>

> <strong>OBSERVAÇÃO:</strong> &lt;cite&gt; não deve ser usado para o nome de uma pessoa. 



```html
<p>
    <cite>Batman Begins</cite> é o melhor filme do Batman feito até hoje.
</p>
```

![](imagens/text/usando_tag_cite.png)

<p align = "justify">O elemento &lt;address&gt; é utilizado para definir as informações de contato do autor/proprietário de um documento ou artigo. Essas informações podem ser um endereço de e-mail, URL, endereço físico, número de telefone, etc. Os navegadores geralmente mostram o conteúdo do elemento &lt;address&gt; em itálico. </p>

```html
<adress>
    Escrito por Millene Prado <br />
    <a href="mailto:">meuemail@hotmail.com</a> <br />
    Goiânia - GO
</adress>
```

![](imagens/text/usando_tag_address.png)

<strong>VER CÓDIGO:</strong> [exemplos elementos semânticos](https://github.com/millenevprado/html-my-notes/blob/main/exemplos/elementos-semanticos.html).

<hr>

<h1> <a name = "lists"></a>LISTAS</h1>

