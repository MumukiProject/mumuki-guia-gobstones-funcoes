Queremos escrever a função `eLivreLados()`, que determine se a garra tem liberdade de se mover para os lados (ou seja, Leste e Oeste).

Antes de mais nada, pensemos... Que **tipo** deve denotar nossa função? Será...

* ... uma **cor**? Não.
* ... um **número**? Também não.
* ... uma **direção**? Poderia, mas não. Observe que o que se pede é _"saber se a garra pode se mover"_ e não para onde.
* ... um **booleano**? Sim! :tada: Como nos demos conta: o que está pedindo tem uma pinta de pergunta que é respondida com sim ou não, e isso é exatamente o que podemos representar com um valor booleano: **Verdadeiro** ou **Falso**.

Mas, ups, há um outro problema. Devem ser feitas DUAS perguntas: **Pode ser movida**  para o Leste? **E**, **pode ser movida** para o Oeste? :fearful:

Bom, existe o operador` && `que serve justamente para isso: utiliza duas expressões booleanas e devolve `True` apenas se **ambas** são verdadeiras. Se você sabe algo de lógica, isto é o que comumente se denomina **conjunção** e geralmente se representa com o símbolo ∧.

> Execute a função `eLivreLados()` que indique se a garra pode se mover tanto para o Leste como para o Oeste.
