### Adicionando float para nosso pacote (free)

* Para que o pacote do plano __free__ ficasse a direita da tela, foi usado a propriedade *float* com o valor *right* para que ele fosse colocado a direita.

* Lembrando que o float ele funciona tirando o elemento do fluxo normal da página e colando ele a extrema direita ou esquerda, com isso os elementos que são irmãos desse elemento flutuantes ficarão embaixo dele e o que for texto ficará ao lado.

* Para resolver esse problema do elemento irmão ficar embaixo do elemento flutuante, podemos usar a propriedade *clear* que especifica se pode haver elementos flutuantes ao lado do elemento irmão que não é flutuante ou se esse elemento irmão do flutuante deve ir para baixo do elemento flutuante, que foi o que fizemos ali com a \<div> que tem a classe *fix-free*.
  
* Foi interessante ver sobre float, mas tenho a opinião que nesse caso que não foi usado __flexbox__ para alinhar o elemento a direita, poderia ter sido usado *margin-left: auto* que resolveria, tirando isso é interessante o uso de float no conjunto de texto e imagens ou um bloco e texto para que o texto circunde a imagem ou bloco.

* Um pequeno adendo, quando aplicado *clear* em elemento não flutuante, sua margem superior entra em colapso com a margem inferior do elemento flutuante, por isso que foi usado a \<div>, para que a margem do elemento flutuante não colapsasse com a do pacote premium.

