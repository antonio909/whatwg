# Como ler esta especificação

Esta especificação deve ser lida como todas as outras especificações. Primeiro,
deve ser lida de capa a capa, várias vezes. Depois, deve ser lida de trá para frente
pelo menos uma vez. Então, deve ser lida escolhendo seções aleatórias da lista de
conteúdos e seguindo todas as referências cruzadas.

Conforme descrito na seção de requisitos de conformidade abaixo, esta especificação
descreve critérios de conformidade para uma variedade de classes de conformidade.
Em particular, existem requisitos de conformidade que se aplicam aos **produtores** (por
exemplo, desenvolvedores e os documentos que eles criam) e requisitos que se aplicam aos
**consumidor** (por exemplo, navegadores web). Eles podem ser distinguidos pelo que estão
exigindo: um requisito sobre um produtor estabelece **o que é permitido**, enquanto um
requisito sobre um consumidor estabelece **como o software deve agir**.

**Exemplo**
  Por exemplo, 'o valor do atributo `foo` deve ser um número inteiro válido' é um requisito para
  **produtores**, pois define os valores permitidos; em contraste, o requisito 'o valor do atributo
  `foo` deve ser analisado utilisando as regras de análise de números inteiros' é um requisito
  para **consumidores**, pois descreve como processar o conteúdo.

**Requisitos sobre produtores não têm qualquer influência sobre os consumidores.**

**Exemplo**
  Dando continuidade ao exemplo anterior, um requisito que estabelece que o valor de um
  determinado atributo deve ser, obrigatoriamente, um número inteiro válido não implica, de
  forma alguma, qualquer requisito sobre os **consumidores** (os agentes que processam esses
  dados).
  Pode ser que os consumidores sejam, na verdade, obrigados a tratar o atributo como uma
  **string opaca**, totalmente indiferentes ao fato de o valor estar ou não em conformidade com as
  regras. Pode ser também (como no exemplo anterior) que os consumidores sejam obrigados a
  analisar o valor utilizando regras específicas que definem valores inválidos (neste caso,
  não numéricos) devem ser processados.
