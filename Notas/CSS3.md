# Introdção ao CSS3 - Anotações Básicas.

- CSS é a linguagem de estilo, ou seja, o conteúdo que moldamos com o HTML fica no padrão do navegador e o CSS surgiu para suprir a necessidade de formatação das mensagens, com ele definimos  regras de estilo para página, modificando através de seletores e declarações, ou seja, eu posso selecionar vários elementos HTML e modificar todos de uma vez, como podemos usar elementos de maneira em que ele possa se repetir, nos vamos criar **classes** e **ID** identificando e diferenciando estes elementos.
- **ID** - No HTML declaramos com **id** e no CSS com **#**, só se usa uma vez na página.
- **Classe** - No HTML declaramos com **class** e no CSS com **.** precedendo o elemento.

### Exemplos de uso: 

- **HTML** : Alterando os títulos de uma página, como pode-se imaginar, o elemento HTML qe indica o título pode se repetir por várias vezes, então devemos aplicar uma **id** ao título principal e uma **class** aos demais. 

  Para linkar o nosso CSS com HTML, no head teremos que adicionar o seguinte comando:

  < link rel = "stylesheet" href = "nome_arquivo"> onde o *rel* identifica o tipo de arquivo e o *href* o caminho para o arquivo.

< h1 id= "title"> Caio César Maciel < h1/>

< h2 class= "subtitle"> Posts < h2/>

< h3 class= "post_title"> Posts #1 < h3/>  

- **CSS** : Com o seletor, iremos personalizar nossos elementos HTML através de comandos.

  #tittle, .subtitle, .post_title {

  color: blue;

  }

  post_title {

  font-size: 16px;

  font-style: italic;

  }

no primeiro seletor, mudamos a cor dos nossos títulos para azul e no segundo mudamos o tamanho da fonte e colocamos em itálico nosso post title.  