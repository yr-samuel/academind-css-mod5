### Adicionando estilos para os planos

* Foi alinhado o texto do elemento h1 ao centro, usando a propriedade text-align

* Para os elementos com a classe .plan, foram estilizados da seguinte forma:
  * Background com essa cor <span style="background-color: #d5ffdc; text-align: center;">____</span>.
  * Todos os textos dentro do article foram alinhados ao centro com text-align.
  * Padding foi definido com 16px, todos os lados.
  * Margin foi definida com 8px, todos os lados.
  * A propriedade display foi definida como inline-block, para que os elementos ficassem todos na mesma linha.
  * Foi definida a propriedade vertical-align para middle, para que todos os elementos fiquem alinhados ao centro da linha no eixo Y.
  * A largura de cada elemento na aula foi definida com 300px, porém eu quis usar calc() para definir o tamanho de cada um conforme o tamanho do elemento pai, então ficou assim -> calc(100% / 3 - 19px), dividido pois queria que ele calculasse para 3 elementos na linha, subtraindo 19px que seria a soma das margem horizontal (left e right) + o tamanho do espaço criado entre os elementos inline devido a se comportarem como texto. O padding e o border não entram nessa conta, pois o elemento esta com box-sizing: border-box.
  * Como eu calculei o tamanho dessa forma, basicamente o conteúdo sempre vai ficar alinhado ao centro, por causa que os elementos vão ocupar todo o espaço da linha, mas caso não fosse feito isso, era só colocar um text-align: center, para alinhá-los ao centro da section.