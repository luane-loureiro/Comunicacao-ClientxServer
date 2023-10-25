# Trabalhando com formulários em HTML
## apresentação

## Tags Form
O formulario é prenchido pelo lado do cliente, enviado para o servidror e eh guardado no banco de Dados.

[![](https://mermaid.ink/img/pako:eNp9kc9Kw0AQxl9lmJOB9gVyKKj1HyiIPXhwe5hmpzaQ7IbNRCylN4-C4sVjj948Cz6UfQSnSSyxiHtYlm9-833DzgITbxljhNtAxQzOr4wDPfs369XLJ2RUiC_G0O8P4GhvvXp9-Pp4gsvg7-dRA-6qoKzCbf9hlrKThjz2Ia8yCqkvx41S38b9GKnT4zOcOeHgWKJIfU627tc8gRGHOw5t8J-lOrx1arCO3z992nW61YckNKGSoezmbepv73BALvFgWSnry98zduczDnuYc8gptfq9i41oUGacs8FYn5anVGVi0LilolSJH81dgrGEintYFZaEhynpXnKMp5SVqrJNxYeLZmX15pbf_T6jOA?type=png)](https://mermaid.live/edit#pako:eNp9kc9Kw0AQxl9lmJOB9gVyKKj1HyiIPXhwe5hmpzaQ7IbNRCylN4-C4sVjj948Cz6UfQSnSSyxiHtYlm9-833DzgITbxljhNtAxQzOr4wDPfs369XLJ2RUiC_G0O8P4GhvvXp9-Pp4gsvg7-dRA-6qoKzCbf9hlrKThjz2Ia8yCqkvx41S38b9GKnT4zOcOeHgWKJIfU627tc8gRGHOw5t8J-lOrx1arCO3z992nW61YckNKGSoezmbepv73BALvFgWSnry98zduczDnuYc8gptfq9i41oUGacs8FYn5anVGVi0LilolSJH81dgrGEintYFZaEhynpXnKMp5SVqrJNxYeLZmX15pbf_T6jOA)

O formulário HTML é representado pela tag de abertura <form> e a de fechamento </form>. Dentro dessas tags, serão colocados todos os elementos que compõem este formulário

### Atributosn da Tag Form
#### - Action
O atributo action define o local (através de uma URL) ao qual serão enviados todos os dados recolhidos do formulário.

#### - method
O atributo method define o método HTTP com que o formulário HTML irá lidar com os dados recebidos. São eles: o método GET e o método POST.

- O método GET 
    - O método GET é usado pelo navegador para solicitar que o servidor envie de volta um determinado recurso. Portanto, é como se falássemos ao servidor “Servidor, eu quero obter este recurso.”
    - Nesse caso, o navegador envia um corpo vazio. Portanto, já que o corpo fica vazio, se um formulário for enviado através do método GET, os dados serão reconhecidos pelo servidor através da URL.
    - Dessa forma, podemos perceber que ao enviar um formulário com os campos Nome e Idade, a URL iria se parecer com algo como: url?nome=valor&idade=value.
    - Esse é o método padrão do formulário HTML. Caso não seja declarado o atributo method, o formulário funcionará através do método GET.

    - Vejamos então, algumas observações a respeito do método GET:
        - O tamanho de uma URL é limitado a cerca de 3000 caracteres;
        - Nunca use o GET para enviar dados confidenciais, pois esses dados ficarão visíveis na URL;
        - É útil para envios de formulários em que um usuário deseja marcar o resultado;
        - GET é melhor para dados não seguros, como strings de consulta no Google.
     
```
  <!--Formulário HTML através do método GET -->
<form method="get" action="/receber_dados.php"> 
    ... 
</form>
```


- O método POST

    - O método POST é utilizado no navegador para conversar com o servidor. Os dados são enviados ao servidor através do corpo da solicitação HTTP.
    - Também é realizada uma solicitação de resposta. Portanto, é como se falássemos ao servidor “Servidor, verifique esses dados e me retorne um resultado adequado”.
    - Dessa forma, ao enviar um formulário através do método POST, os dados serão anexados ao corpo da solicitação HTTP.
    - Diferentemente do método GET, explicado anteriormente, o método POST não inclui o corpo na URL. Portanto, os dados enviados não ficarão visíveis na URL.
    - Vejamos então, algumas observações a respeito do método POST:
        - Anexa dados de formulário dentro do corpo da solicitação de HTTP. Portanto, os dados não são mostrados na URL;
        - Não tem limitações de tamanho;
        - Os envios de formulários com o POST não podem ser marcados.
     
```
<!--Formulário HTML através do método POST-->
<form method="post" action="/receber_dados.php">
    ...
</form>
```

## Tag Imput e Seus Tipos
A tag ```<input>``` é uma das mais utilizadas dentro de um formulário HTML e considerada a principal. Esta tag representa os campos de entrada de dados de um formulário. Existem diversos tipos, principalmente após a atualização do HTML para a versão HTML5, que trouxe diversos tipos novos de <input>.

O atributo mais importante da tag ```<input>``` é o atributos type. Esse atributo representa o tipo de campo de entrada ao qual essa tag pertence e como ele se comporta. Portanto, declarar o atributo type é um pré-requisito para utilizar a tag ```<input>```.

Um atributo Também importante para a tag ```<input>``` é o atributo name, que define um nome para o campo de entrada. Este recurso é muito útil para conseguir identificar os campos através dos métodos GET e POST.

Outro atributo que é muito utilizado, o atributo ```value```. Esse atributo define um valor inicial para o campo de entrada.

Um atributo que também merece destaque é o ```placeholder```, pois esse atributo permite digitarmos uma “descrição” que será visualizada enquanto o campo de entrada não possuir nenhum valor.

Há ainda um atributo bastante utilizado, que garante que aquele campo tenha seu preenchimento obrigatório para validar e permitir o envio do formulário: o atributo ```required```. Portanto, sempre que precisar manter o preenchimento de um campo obrigatório, basta utilizar este atributo.

### - type
o principal atributo da tag <input> é o atributo type. Esse atributo é capaz de definir o comportamento do campo de entrada. Ao todo, existem 22 valores para esse atributo, ou seja, 22 tipos de atributo type.
 | Type | Descrição |
 |-------|-----|
| button	| Define um botão	|
| checkbox |	Define uma caixa de checagem|
| color	| Define uma caixa de cores	|
| date	| Define um campo de data |
| datetime-local	| Define um campo de data e horário |
email	| Define um campo de e-mail	
file	| Define uma campo para upload de arquivos	
hidden	| Define um campo oculto	
image	| Define uma imagem como botão de envio do formulário HTML	
month	| Define um controle de mês e ano	
number	| Define um campo de intervalo de número	
password	| Define um campo de senha (mascarando-a)	
radio	| Define um campo de opção (radio)	
range	| Define um controle de intervalo	
reset	| Define um botão para reiniciar aos valores iniciais	
search	| Define um campo de pesquisa	
submit	| Define um botão de envio do formulário HTML	
tel	| Define um campo de telefone	
text	| Define um campo de texto	
time	| Define um campo de controle de horário	
url	| Define um campo de URL	
week	| Define um campo de controle de semana

## Check Box e Radio
### Check Box ```<input type=”checkbox”>```
O input  do tipo checkbox define uma caixa de seleção. 

A caixa de seleção é mostrada como uma caixa quadrada que pode ser marcada quando é ativada. 

As caixas de seleção permitem que o usuário possa marcar uma ou mais opções. 

###  Radio ```<input type=”radio”>```
O input do tipo “radio” define um botão de opção. Muito utilizados em formas de grupos, ou seja, um conjunto de opções relacionadas. Dessa forma, o usuário poderá selecionar apenas um botão do tipo radio pertencente a um mesmo grupo.

Para manter um grupo, o nome dos radios devem ser o mesmo, portanto, receberá o mesmo valor no atributo name. Dessa forma, ao selecionar qualquer botão do tipo radio, qualquer outro botão radio do mesmo grupo será desmarcado automaticamente.

Para definir um valor exclusivo para cada botão radio pertencente a um mesmo grupo, basta utilizar o atributo value. Esse valor não será mostrado para o usuário, mas será enviado para o servidor. Portanto, ao enviar um formulário que contenha um grupo de radio, o valor desse grupo será o valor do atributo value do radio selecionado.


## Button e Seus Tipos
O elemento ```<button>```, como o nome sugere, corresponde a um botão em que a pessoa usuária pode clicar para executar uma determinada ação. 
Por padrão, sua aparência é semelhante a um botão retangular como os utilizados em aplicações para desktop. Entretanto, ela pode ser alterada por meio de estilos CSS ou também substituída por imagem e textos.
É importante dizer que o elemento ```<input>``` tem um tipo definido como button que tem o mesmo objetivo do botão, ou seja, executar uma ação ao ser clicado. 
A principal diferença entre eles é que o ```<input>``` não pode ter imagens ou outros elementos HTML inseridos – o que é possível com a tag ```<button>```.

### Atributos do Elemento HTML ```<button>```
| Atributo | Descriçao |
|----------|-----------|
| Disable | desativa um botão |
| Name | nomeia um Botão |
| Form | define o formulario que o botão pertence |
| Type | define o  tipo de Botão |

#### ```< button type="#" >``` 
- Determina qual a função que o elemento ```<button>``` terá em um formulário.
- Existem três possibilidades para esse atributo, são elas:

| Type | Descrção |
| -------| --------|
| button | Tem a finalidade de executar uma determinada função, sem a necessidade de enviar o formulário para o servidor |
| Reset |  Tem a função de limpar os dados do formulário |
| Submit |Tem a função de enviar os dados do formulário para o servidor |


## Select e Seus Tipos
A tag HTML ```<select>``` representa um controle que apresenta um menu de opções. 
As opções dentro do menu são representadas pelo elemento ```<option>```, que podem ser agrupados por elementos ```<optgroup>```. 
As opções podem ser pré-selecionadas para o usuário.

| Atributo | Descrição |
|------ |-----------|
| Autofocus | permite especificar que um controle de formulário deve ter foco de entrada quando a página é carregada. |
| Disabled | o usuário não pode interagir com o controle. |
| Form | O elemento form ao qual o elemento select é associado. Se este atributo for especificado, seu valor deve ser o ID de um elemento form no mesmo documento. |
| Multiple | indica que várias opções podem ser selecionadas na lista. |
| Name | O nome do controle |
| Required | indica que uma opção com um valor de string que não esteja vazia deve ser selecionada.|
| size | Se o controle é apresentado como uma list box com scroll, este atributo representa o número de linhas na list box que devem estar visíveis num determinado momento. | 

## Tesxt Área
O elemento HTML ```<textarea>``` representa um controle de edição para uma caixa de texto, útil quando você quer permitir ao usuário informar um texto extenso em formato livre, como um comentário ou formulário de retorno.

| Atributos | Descrção | valores possíveis |
|-----------|----------|----------------|
| O rows e cols | permitem especificar um tamanho exato para o ```<textarea>``` pegar.| |
| maxlength | especifica um número máximo de caracteres que o ```<textarea>``` tem permissão para conter. | |
| minlength | Define um comprimento mínimo considerado válido usando |  |
| required | Este atributo especifica que o usuário deve preencher um valor antes de enviar um formulário. | |
| wrap | Indica como o controle quebra o texto.| hard e soft |
| autocapitalize | controla se e como o valor do texto deve ser automaticamente capitalizado quando é inserido | none, sentences, words, characters |
| autocomplete | Este atributo indica se o valor do controle pode ser preenchido automaticamente pelo navegador.| on ou off |
| autofocus | Esse atributo booleano permite especificar que um controle de formulário tenha foco de entrada quando a página for carregada. | |
| cols | A largura visível do controle de texto, em larguras médias de caracteres. Se for especificado, deve ser um número inteiro positivo. Se não for especificado, o valor padrão é 20 | |
| form | O elemento do formulário que o <textarea> elemento está associado (seu "proprietário do formulário"). O valor do atributo deve ser o id de um elemento de formulário no mesmo documento. | |
| placeholder | Uma dica para o usuário sobre o que pode ser inserido no controle. | |
| spellcheck | Especifica se o <textarea>está sujeito a verificação ortográfica pelo navegador | true, defout , false |

