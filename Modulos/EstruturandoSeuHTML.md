# Estruturando Seu HTML + Formatações

## Aula 00 - Apresentção
Entende e formatar alguns textos pensando também em acessibilidade. Estruturar melhor seu HTML, preparando ele para aplicar o CSS. Conhecer mais sobre como funcionam cores HTML.

## Aula 01 - Formatando Textos: ```<strong>```, ```<i>```, ```<b>```, ```<b>```
### Parte 1 - Fromatação básica

| Tags | Descrição | exemplo |
| ------ | ----------- | -------- |
| ```<b></b>``` | deixa o texro Bold ( Negrito ) | <b>negrito</b> |
|```<i></i>``` | deixa o texto em itálico | <i>Itálico </i> |
|```<u></u>```| deixa o texto underline ( sublinhado )| Sublinhado |
| ```<mark></mark>``` | deixa o texto com efeito de marcador | <mark> marcador </mark> |
| ```<Blocote></blocote>``` | usado para destaca citações |
|```<sup></sup>``` | deixa o testo supescrito |
|```<sub></sub>```| deixa o testo subescrito |

### Parte 2 - valor semântico
Na linguagem humana, muitas vezes enfatizamos certas palavras para alterar o significado de uma frase, e muitas vezes queremos marcar certas palavras como importantes ou diferentes de alguma forma. O HTML fornece vários elementos semânticos que nos permitem marcar o conteúdo textual com esses efeitos.
Além de tornar o documento mais interessante de ler, eles são reconhecidos pelos leitores de tela e falados em um tom de voz diferente. 

| Tags | Descrição | 
| ------ | ----------- | 
| ```<strong></strong>``` | define texto de grande importância. O conteúdo normalmente é exibido em negrito. |
|```<em></em>``` | define o texto como enfatizado. O conteúdo interno normalmente é exibido em itálico. | 
|```<article></article>```| elemento especifica conteúdo independente, Um artigo deve fazer sentido por si só.|  
| ```<section></section>``` | define uma seção em uma página, um agrupamento temático de conteúdo |  
| ```<header></header>``` | Usado para marcar o cabeçario da página, um contêiner para um conteúdo introdutório. | 
|```<main></main>```| especifica o conteúdo principal de um documento | 
|```<footer></footer>``` | define um rodapé para um documento ou seção.| 
|```<nav></nav>```| define um conjunto de links de navegação. | 
|```<aside></aside>``` | define algum conteúdo além do conteúdo (como uma barra lateral). | 
|```<nav></nav>```| define um conjunto de links de navegação. | 
|```<figure></figure>```| especifica conteúdo independente, como ilustrações, diagramas, fotos, listagens de códigos, etc. | 
|```<figcaption></figcaption>```| define uma legenda para um <figure>elemento. | 


## Aula 02 - Formatando Textos: ```<font>``` (NÃO COMPATÍVEL COM HTML5)
A tag <font> era usada no HTML4 para especificar o tipo da fonte, o tamanho e a sua cor.

| Atrubutos | Descrição |
|-----------|-----------|
| color | muda a cor do texto |
| size | tamano da fonte |
| face | tipo de fonte |


## Aula 03 - Tag ```<div>```, e ```<span>```
### ```<div>``` Definição e uso:
- define uma divisão ou seção em um documento HTML.
- é usada como um contêiner para elementos HTML – que são então estilizados com CSS ou manipulados com JavaScript.
- é facilmente estilizada usando o atributo class ou id.
- Qualquer tipo de conteúdo pode ser colocado dentro da ```<div>```
- Nota: Por padrão, os navegadores sempre colocam uma quebra de linha antes e depois do <div>elemento.

### ```<span>``` Definição e uso:
- é um contêiner embutido usado para marcar uma parte de um texto ou parte de um documento.
- é facilmente estilizada por CSS ou manipulada com JavaScript usando o atributo class ou id.
- é muito parecida com o elemento ```<div>``` , mas ```<div>``` é um elemento de nível de bloco e ```<span>``` é um elemento embutido.

## Aula 04 - Tag ```<fieldsets>```
#### Definição e usos
- é usada para agrupar elementos relacionados em um formulário.
- Ela desenha uma caixa ao redor dos elementos relacionados.
- A tag ```<legend>``` é usada para definir uma legenda para o <fieldset>elemento.

| Atributos | Value	| Description |
|-----------|-------|-------------|
| disabled	| disabled	| especifica um grupo de elementos de um formulario que devem ser desabilitados. |
| form	| form_id	| especifica a qual formulario o fildsets pertence. |
| name	| text	| Especifica um nome para o fildset. |

## Aula 05 - Tag ```<embeds>```

## Aula 07 - Tag ```<iframe>```

## Aula 08 - Resenha Sobre Cores


