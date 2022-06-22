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

- **Box model** : Divide-se em 4 partes, margin, border, padding e content. 

Onde *margin* é o espaçamento entre os elementos, *border* vai circundar 

o padding e os elementos, nessa parte podemos alterar coisas como largura e cor, já o *padding* é o espaçamento entre a borda e o conteúdo.

Para inserir uma box, vamos adicionar uma classe no html e modificar no CSS.

Há como personalizar o padding e margin de maneira a diferenciar os lados, o primeiro modo é colocando valores para as partes, superior e inferior e depois para os lados, esquerdo e direito. O segundo modo de fazer isso, é inserir propriedades específicas para cada lado.
Ex1 - .post{ 

margin: 15px 10px

}

Ex2 - .post {

margin-top: 10px;

margin-right: 15px;

margin-botton: 10px;

margin-left: 0;

}

**TODOS SEGIRÃO A ORDEM: TOPO, DIREITA, INFERIOR E ESQUERDA**

***Background*** - Tem a função de alterar a cor, posição e adicionar uma imagem.

.post{

background-color: red 

background-position: top;

background-image: url("sk.png")

}

***Border*** - Pode ter 3 valores, largura, cor e estilo.

.post {

border: 3px solid blue;

border-top: 2px dotted green; // Topo da borda pontilhado verde

border-right: 4px dashed pink; // lado esquerdo da borda tracejado rosa

}

Com o ***border-radius***, arredondamos os cantos das bordas:

border-radius: 10% 15% 10% 15%

**Texto** :

#title{ 

font-family: Arial;

font-size: 10px

font-style: normal; ou italic;

font-weight: bold; //peso do texto, negrito

text-decoration: underline; ou overline; ou line-throught//Insere abaixo da palavra, uma linha acima do texto, uma linha cortando a palavra

text-transform: uppercase; ou lowercase; ou capitalize; //maiúsculo, minúsculo e toda primeira letra maiúscula 

}

**Listas** : 

ul {

list-style-type: square; //lista não ordenada alterando o símbolo para um quadrado

list-style-type: "1F44D"; //alterando para um emogi

list-style-type: list-style-image: url("rocket.png")//alterando para uma imagem 

}

ol{ 

list-style-type: upper-roman; //lista ordenada alterando para algarismos romanos maiúsculos

}

- **Dimensão e alinhamento** 

  *Width* - Largura

  *Height* - Altura

*Max-Width* - Largura máxima (Porcentagem)

*Max-Height* - Altura máxima (Porcentagem)

 *Margin* - Alinha, se deixar margin: auto; alinha automático

Text alingn - Alinha o texto.
