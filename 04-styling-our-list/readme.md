### Estilizando a lista

* Com a classe .plan__features, foram aplicados estilos para a tag \<ul>, assim resetando seus estilos que já vem por padrão, ressaltando aqui que para remover os ::markers é só usar a propriedade *list-style* e passar none que ja remove os marcadores (vulgo bolinhas);

* Para cada item dentro da lista foi usado a classe .plan__feature, nela foi aplicado uma margem de 8px na vertical e 0 na horizontal.
  * Para que não precisasse criar margem em cima e embaixo do elemento, eu faria de algumas outras formas:

        .plan__features li + li {
            margin-top: 8px;
        } // caso não tivesse criado as classes para as <li>
       
        .plan__feature + plan__feature   {
            margin-top: 8px;
        } 
        
        .plan__feature:not(:last-child) {
            margin-bottom: 8px;
        }

