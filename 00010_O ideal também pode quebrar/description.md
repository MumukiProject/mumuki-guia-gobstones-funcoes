Como na definição de `haPedrasAo` se usa `Mover`, é obvio que há casos em que ela poderia quebrar: basta posicionar a garra na origem e perguntar se `haPedras` de alguma cor ao Oeste.

Mas... não era que as funções eram **puras** e **não tinham efeito real**? O que acontece se uma função **faz BOOM**?

> Façamos o teste: escreva outra vez a função `haPedrasAo` do exercício anterior, desta vez testaremos a função com casos onde a garra não pode se mover.
