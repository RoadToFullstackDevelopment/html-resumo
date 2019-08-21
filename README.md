# HTML - Resumo

## O que é HTML?
HTML significa ***Hyper Text Markup Langage***. É a linguagem da **World Wide Web**. Trata-se de uma linguagem de marcação de texto padrão utlizada para criar e exibir páginas na **Web**, tornando o texto interativo e dinâmico. Essa linguagem pode transformar texto em imagens, tabelas, ***links***, etc.

```
<!-- Estrutura de um documento HMTL -->
<!DOCTYPE html>
   <html>
     <head>
       <title>HTML Tutorial</title>
     </head>
     <body>
       <h1>This is a heading</h1>
       <p>This is a paragraph.</p>
    </body>
</html>
```

## O que são marcadores (***tags***)?
Os marcadores HTML compõem-se de três elementos: marcador inicial, conteúdo e marcador final. Alguns marcadores não possuem fechamento. Os documentos HTML contém dois elementos:

* Conteúdo
* Marcadores

Quando o navegador lê um documento HTML, o faz de cima para baixo e da esquerda para a direita. Os marcadores HTML são usados para criar documentos HTML e reproduzir suas propriedades. Cada marcador HTML tem propriedades distintas.

### Sintaxe

```
<marcador>conteúdo</marcador>
```

O conteúdo localiza-se entre os marcadores para exibir dados na página **web**.

## Todos os marcadores HMTL têm um fechamento?
Não. Há alguns marcadores HTML que são vazios. Exemplo: `img`, `br`, `hr`.

## O que é a formatação no HTML?
A formatação no HTML é um processo no qual o texto sofre modificações para obter uma aparência melhor. Utiliza marcadores diferentes para deixar o texto em negrito, itálico, sublinhado, etc.

(Ju) A formatação também pode ser feita pelo CSS, inclusive recomendamos que seja feito dessa forma para que tudo que esteja relacionado ao estilo (inclusive negrito, itálico, etc) seja responsabilidade do CSS.

## Quantos tamanhos de título existem no HTML?
Existem no HTML seis tamanhos diferentes de títulos definidos de `h1` (maior) a `h6` (menor).

(Ju) Assim como a formatação, o tamanho da fonte (menor ou maior) normalmente deixamos para o CSS. Porém é importante usar o peso dos títulos (h1 para mais importante e etc) da forma correta para que as informações sejam indexadas da forma correta pelos motores de busca (ex Google) e para que seu HTML fique bem legível.


### Exemplo

```
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

## Como criar um hipertexto (***hyperlink***) no HTML?
O HTML fornece um marcador âncora para criar um hipertexto que vincula uma página a outra.

### Exemplo

```
<a href="url">link text</a>
```

Esses marcadores podem aparecer nas formas a seguir:

* ***Link*** **não visitado**: aparece sublinhado e com a cor azul.
* ***Link*** **visitado**: aparece sublinhado e com a cor púrpura.
* ***Link*** **ativo**: aparece sublinhado e com a cor vermelha.

## Qual marcador HTML é utilizado para exibir dados em forma de tabela?
O marcador `table` é utilizado para exibir dados em forma de tabela (linha * coluna). Esse marcador também controla o visual da página, por exemplo: cabeçalho, navegação, conteúdo, rodapé. Aqui está uma lista de marcadores utilizados que exibem os dados em forma de tabela.

* `table`: define uma tabela.
* `tr`: define uma linha em uma tabela.
* `th`: define uma célula de cabeçalho em uma tabela.
* `td`: define uma célula em uma tabela.
* `caption`: define uma legenda.
* `colgroup`: especifica um grupo de uma ou mais colunas em uma tabela para fins de formatação.
* `col`: utilizado com o marcador `colgroup` para especificar propriedades para cada coluna.
* `tbody`: usado para agrupar o conteúdo do corpo de uma tabela.
* `thead`: usado para agrupar o conteúdo do cabeçalho de uma tabela.
* `tfooter`: usado para agrupar o conteúdo do rodapé de uma tabela.

## Escreva uma tabela em HTML com os seguintes dados:
#### 50 pcs 100 500
#### 10 pcs 5 50

```
<table>
   <tr>
     <td>50 pcs</td>
     <td>100</td>
     <td>500</td>
   </tr>
   <tr>
     <td>10 pcs</td>
     <td>5</td>
     <td>50</td>
   </tr>
</table>
```

## Quais são os tipos de lista usados ao desenhar uma página?
Existem alguns tipos de lista usados para desenhar uma página. Você pode escolher qualquer tipo de lista a seguir:

* ***Lista ordenada***: exibe elementos em formato numerado. É representada pelo marcador `ol`.

```
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>
```

* ***Lista não ordenada***: exibe elementos em formato de ponto. É representada pelo marcador `ul`.

```
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```

* ***Lista de definição***: exibe elementos como se fosse um dicionário. Os marcadores `dl`, `dt` e `dd` são usados para configurar a lista de definição.

```
<dl>
  <dt>Item</dt>
  <dd>Definition</dd>
  <dt>Item</dt>
  <dd>Definition</dd>
</dl>
```

## Qual é a diferença entre elementos e marcadores no HMTL?
Elementos HTML comunicam-se com o navegador para reproduzir texto. Quando um elemento está contido entre colchetes angulares `<>`, forma um marcador HTML. Na maioria das vezes, os marcadores vêm em pares e rodeiam o conteúdo.

## O que é o HTML semântico?
HTML semântico é um estilo de código. É a utilização de marcação HTML para reforçar a semântica ou o significado do conteúdo. Exemplo: no HTML semântico o marcador `b` não é utilizado para textos em negrito, nem o marcador `i` é utilizado para textos em itálico. Em vez desses marcadores, utilizamos `strong` e `em`.

(Ju) É importante utilizar os marcadores de conteúdo como `<section>`, `<main>`, `<article>`, entre outros, para que o as seções de seu site/aplicativo sejam facilmente identificáveis tanto pelas pessoas quanto pelos leitores de tela. 

## O que é um mapa de imagem?
O mapa de imagem facilita o vínculo a várias páginas diferentes com o uso de uma única imagem. É representado pelo marcado `map`. Você pode definir formas em imagens que você quer que façam parte do mapa.

```
<map name="planetmap">
  <area shape="rect" coords="0,0,82,126" href="sun.htm" alt="Sun">
  <area shape="circle" coords="90,58,3" href="mercur.htm" alt="Mercury">
  <area shape="circle" coords="124,58,8" href="venus.htm" alt="Venus">
</map>
```

## Como inserir um símbolo de *copyright* em uma página HTML?
Você pode inserir um símbolo de *copyright* usando `&copy;` ou `&#169;` em um arquivo HTML.

## Qual é o propósito do atributo *alt* em imagens?
O atributo `alt` fornece informações alternativas com relação à imagem, quando um usuário não consegue vê-la. Esse atributo deve ser utilizado para descrever qualquer imagem, com exceção das imagens que servem somente para fins de decoração.

```
<img src="img.jpg" alt="montanha">
```

O "alt" também serve para fins de acessibilidade, então a descrição da imagem deve ser bem pensada para isso também.

## Explique o uso do marcador *meta* no HTML
O marcador `meta` descreve metadados dentro de um documento HTML. Estes metadados não aparecerão na página, porém serão analisados pela máquina. Este marcador especifica a descrição da página, palavras-chave (***keywords***), autor do documento, última modificação e outros metadados.

```
<head>
  <meta charset="UTF-8">
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML,CSS,XML,JavaScript">
  <meta name="author" content="John Doe">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
```

## Para que serve o marcador *iframe*?
O marcador `iframe` serve para exibir uma página dentro de outra página.

```
<iframe src="https://www.google.com"></iframe>
```

## Descreva alguns dos objetivos e motivações principais da especificação HTML5
O HTML5 foi criado para substituir HTML4, XHTML e HTML DOM Nível 2. Os objetivos e motivações principais por trás da especificação HTML5 eram:

* Entrega de um rico conteúdo (gráficos, vídeos, etc.) sem a necessidade de *plugins* adicionais como o Flash.
* Fornecimento de um suporte semântico melhor para a página *web* por meio de marcadores de elementos estruturais.
* Fornecimento de um padrão de análise (***parse***) mais preciso de modo a simplificar o manuseio de erros, além de garantir um comportamento entre navegadores mais consistente e simplificar a compatibilidade com documentos escritos em outros padrões.
* Fornecimento de um melhor suporte entre plataformas, quer a pessoa utilize um PC, um *tablet* ou um *smartphone*.

## Como posso conseguir uma colocação melhor nas páginas de busca?
É possível obter melhores colocações ao incluir as seguintes declarações no `head` do documento:

```
<meta name="keywords" content="keyword keyword keyword keyword">
<meta name="description" content="description of your site">
```

Ambas declarações podem conter até 1022 caracteres. Se uma palavra-chave for utilizada mais de 7 vezes, o marcador de palavras-chave será totalmente ignorado. Além disso, você também não pode incluir marcação (além de entidades) na descrição ou lista de palavras-chave.

## Qual é a diferença entre *span* e *div*?

* `div` é um elemento em bloco (***block element***).
* `span` é um elemento em linha (***inline element***).

## O que é codificador de caracteres (*Character Encoding*)?
Para exibir uma página HTML corretamente, um navegador precisa saber qual conjunto de caracteres (codificador de caracteres) deve usar, o que está especificado no marcador.

```
<head>
   <meta charset="UTF-8">
</head>
```

## É possível destacar um texto no HTML?
Se você estiver trabalhando com uma página no padrão HTML5, o marcador `mark` pode ser uma forma fácil e rápida de destacar um texto na página.

```
<p>Do not forget to buy <mark>milk</mark> today.</p>
```

Para destacar um texto no padrão HTML que seja suportado por todos os navegadores, utilize o estilo de cor de fundo dentro do marcador HTML.

```
<p>Do not forget to buy <span style="background-color: yellow;">milk</span> today.</p>
```

(Ju) Esse exemplo utiliza estilo inserido diretamente no HTML. É recomendado que isso seja feito pelo CSS e, ao invés de utilizar `style="etc"`, utilizar uma classe para chamar o estilo correspondente.

## O que é um marcador vazio?
Os marcadores vazios são elementos que não tem necessidade de possuir fechamento. Exemplo: `img`, `br`, `hr`.

## Descreva brevemente o uso correto dos seguintes elementos semânticos do HTML5: *header*, *article*, *section*, *footer*, *nav*, *aside*, *main*

* `header`: cabeçalho do documento ou seção
* `nav`: menu de navegação
* `main`: conteúdo principal de um documento
* `aside`: conteúdo localizado na parte lateral de uma página
* `article`: conteúdo independente
* `section`: seção do documento
* `footer`: rodapé da página

## Explique a diferença entre elementos em bloco (*block elements*) e elementos em linha (*inline elements*)
***Elementos em bloco*** formam um bloco visível na página. Eles aparecerão em uma nova linha logo após qualquer elemento que venha antes dele, e qualquer conteúdo depois de um elemento em bloco também aparecerá em uma nova linha. São elementos em bloco: `p`, `ol`, `ul`, `nav`, `footer`, etc.
***Elementos inline (em linha)*** são aqueles que estão contidos dentro de elementos em bloco, envolvem apenas pequenas partes do conteúdo do documento e não parágrafos inteiros ou agrupamentos de conteúdo. São elementos em linha: `a`, `strong`, `em`. 

```
<!-- Cabeçalhos de títulos e legendas (elemento block) -->
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

```
<!-- Link (elemento inline) -->
<a href=”http://www.google.com”>Acesse o Google</a>
```

```
<!-- Tabela (elemento block) -->
<table>
   <thead>
     <tr>
      <th>Month</th>
      <th>Savings</th>
    </tr>
   </thead>
   <tbody>
     <tr>
       <td>January</td>
       <td>$100</td>
     </tr>
     <tr>
       <td>February</td>
       <td>$150</td>
     </tr>
    </tbody>
</table>
```

```
<!-- Lista ordenada (elemento block) -->
<ol>
   <li>Item</li>
   <li>Item</li>
   <li>Item</li>
   <li>Item</li>
</ol>
```

```
<!-- Lista não ordenada (elemento block) -->
<ul>
   <li>Item</li>
   <li>Item</li>
   <li>Item</li>
   <li>Item</li>
</ul>
```

```
<!-- Imagem (elemento inline) -->
<img src=”image.jpg” alt=”imagem da igreja”>
```

```
<!-- Linha divisória (elemento inline) -->
<hr>
```

```
<!-- Data (elemento inline) -->
<input type=”date”>
```

```
<!-- Realçar um texto (elemento inline) -->
<p>Este texto está <mark>realçado</mark></p>
```

## O que significa criar um HTML semântico? Por que é importante?
O HTML semântico permite a criação de seções de conteúdo baseadas na funcionalidade, para que tecnologias assistivas e leitores de tela possam reconhecer esses elementos e ajudar em tarefas como "encontrar o menu de navegação" ou "encontrar o conteúdo principal". Também é importante para que qualquer pessoa que vá ler o seu código consiga identificar facilmente as partes da aplicação/site.

## Por que se diz que o HTML está aninhado?
“Aninhamento” é quando um elemento está dentro de outro elemento. Por exemplo, o elemento `title` está dentro do elemento `head`, ou o elemento `p` está dentro do elemento `body`.
