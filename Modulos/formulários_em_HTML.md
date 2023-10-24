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

## Button e Seus Tipos

## Select e Seus Tipos

## Tesxr Área
