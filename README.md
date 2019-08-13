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

## Quantos tamanhos de título existem no HTML?
Existem no HTML seis tamanhos diferentes de títulos definidos de `h1` (maior) a `h6` (menor).

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

