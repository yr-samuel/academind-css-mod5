### Estilizando botão de ação

* Foi criado a classe .button para estilizar os botões de forma generica.
* Foram definidas cores de background e texto, tanto para um estado normal quanto para :hover e :active.
* A fonte foi definida como *inherit*, pois no meio do caminho o browser definia alguns estilos para o botão e perdiamos a herança para esse elemento, como no caso a fonte, e queriamos que continuasse com o que era pra ser herdado (que vinha la do body), então aplicamos o valor *inherit* para a propriedade font, assim fazendo haver herança dos estilos.