# Flex Box

- *Flex container* - De forma simplista é uma maneira de organizar elementos dentro de uma caixa, tipo um container recheado de elementos mesmo, onde esses elementos passam a responder pela classe desse container.

  **Display Flex** - Para iniciar, devemos atrelar uma classe *flex* e outra *item* no style do nosso html, com os parâmetros desejados, sendo que a flex se direciona ao container em si e item aos elementos que compõem o container.

  Na parte **body** nos iniciaremos nosso container. Usando *div* elas já trazem um comportamento padrão de block

  Ex.: Como foi adicionado uma tag *style* dentro do html, nela vamos adicionar as classes: 

  < style> 

  .flex{

  max-widith: 100%;

  border: 3px solid black;

  display: flex;

  }

  .item{ 

  background-color: aqua;

  border: 3px solid black;

  

  }

  < / style>
  
  No nosso body adicionaremos nossas div 
  < body>

  ​     < div class: "flex"> 

  < div class: "item" > Item 1 < / div>

  < div class: "item" > Item 2 < / div>

  < div class: "item" > Item 3 < / div>

  ​      < / div> 

  

  </ body> 

  Com isso nossos itens ficaram dispostos no container de modo a ocupar todo ele, e no sentido horizontal, para mudar o sentido de ocupação, devemos aplicar a propriedade *direction*.

  **Flex Direction** - Vai estabelecer o eixo principal do container, que basicamente se divide em dois *column* (coluna) e *row* (linha) que por padrão é horizontal.

  ***row*** - Linha da esquerda para direita.

  ***row-reverse*** - Linha da direita para esquerda.

  ***column*** - Ordenação de cima para baixo.

  ***column-reverse*** - Baixo para cima.

  **Flex wrap** - Define ou não a quebra de linha do container, mas por padrão não quebram linha, isso faz com que o conteúdo seja comprimido, quando o container não comportar mais elementos, acaba vazando.

  **wrap** - Quebra automática de linha.

  **wrap-reverse** - Quebra automática de linha no sentido oposto.

  **Flex flow** - De forma simplista é um atalho para as duas propriedades anteriores.

  **Justify content** - Se encarrega do alinhamento dos itens no container e o espaçamento entre eles.

  ***flex-start*** - Início do container

  ***flex-end*** - Final do container

  ***flex-center*** - Ao centro do container

  ***space-between*** - Cria um espaçamento igual entre os elementos

  ***space-around*** - Os espaçamentos do meio são 2x maiores que o inicial e final.  

  

  

   
  
  