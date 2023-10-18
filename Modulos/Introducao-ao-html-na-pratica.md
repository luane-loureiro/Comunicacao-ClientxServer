# Aprendendo HTML na Prática
## Aula 00 - Introdução e Objetivos Gerais

## Aula 01 - Ferramentas Utilizadas
- Instalando o Visual Studio Code.
- Instalando o pluguin do Vusial studio code live server.


  ### links
  - [Visual Studio](https://code.visualstudio.com/)
  - [Docs Visual Studio](https://code.visualstudio.com/docs)
  

## Usando inspetor de Elementos
- para abrir no google chrome basta apertar F12
- essa ferramenta seve apenas para estudos, você pode manipular os elementos de uma pagina ou ver como eles foram implementados.

## Estrutúra Básica de HTML
- Um arquivo básico de HTML consiste básicamente de três partes:
- HTML
- Head
- body

Estrutura básica:
```bash
<html>
    <head> </head>
    
    <body> </body>
</html>
```
- As tag HTML marcam o início e o final da página.
- Tudo que estiver entre as tags Head são coisas que vão ser carregadas antes de exibir para o usuário.
- Tudo que estiver dentro da tag <Body> é o que de fato vai aparecer para o usuário.

## Falando Sobre Tags
- as tagas funcioan na maioria das vezes em pares tem uma taga de avertura <tag>, e uma de fechamento </tag>, tudo que estiver ente elas recebe aquela marcação.

  ### Glossario de Tags
- ```<i> </i>``` - deixa o texto entre elas em itálico.
- ```<strong> </Satrong>``` - Deixa o texto em Negrito.
- ```<input type="text">```- adiciona uma caixa de texto, perceba que ela é uma taga que nao precisa de fechamento.

## Atributos Básicos
- São palavras especiais usadas dentro da tag de abertura para controlar o comportamento do elemento. Os atributos HTML são um modificador de um tipo de elemento HTML.
#### Exemplos de Atributos Genéricos:
- id -> cia um identificador para a tag.
- style -> atribui um comando css direto no HTML para estilizar uma Tag.
- class -> cria uma classe, um grupo, de elementos dentro do html
- width -> altera a largura da imagem.
- height > altera a altura da imagem.

#### Exemplos de Atributos Específcos:
- Type - > epecífico da taga <imput>, alterna o tipo de informacao pode ser preenchida no campo. Pode ser usado como Test, number, color...
- src -> utilizado para indicar para a tag qual arquivo ou mídia utilizar. Recebe valores como links (https://google.com/minhaimagem.jpeg) ou o nome de um arquivo já presente no projeto (/minhaimagem.jpeg)
- alt -> Específico para a tag <Img>, fornece informações alternativas para uma imagem se um usuário por algum motivo não puder visualizá-la.
- href -> Específico Para a tag <a>, o atributo href especifica a URL da página para a qual o link vai.
- target=”blank” -> Específico Para a tag <a>, Esse atributo abre o link do documento em uma nova janela ou aba.
  
## Textos
- h -> taga utilizada para marcar títulos. depois do h se usa um numero de 1 a 6, quanto maior o numero, menor o texto.
- P -> Paragrafo, texto em corrido, corpo do texto
- Blockquote -> cria uma citacão
- Strong -> forte, negrito
- U -> underlien, sublinhado
- i -> itálico
- mark -> marca texto
- sub -> coloca o testo sub escrito, para baixo
- sup -> coloca texto super ecrito, para cima (como marca registrada)

## Listas ordenadas e Não Ordenadas
- ol -> lista ordenada. essa taga precisa se uma tag "filha" para funcionar, cara item dentro da lista deve estar dentro de uma tag li
- ul -> Lista não ordenada. essa taga precisa se uma tag "filha" para funcionar, cara item dentro da lista deve estar dentro de uma tag li.
- li -> item da lista

```
        <p>minha lista</p>
        <ol>
            <li>item 1</li>
            <li>item 2</li>
            <li>item 3</li>
        </ol>
```

## Link
- a -> ancora, link.
  
#### Atributos para a tag ```<a>```
- title -> colaca um texto dentro de um "balão"ao passa o mouse sobre o link.
- target -> escolhe se ao clicar no link a pagina vai abrir na memsa aba (```"_self"```) ou em um aba diferente (```_blank"```)

