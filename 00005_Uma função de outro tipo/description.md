Como você já sabe, as expressões não servem apenas para operar com números. Vamos construir agora uma função que denota um valor **booleano** (`True`/ `False`).

O que queremos averiguar é se a cor Vermelha é dominante dentro de uma célula. Para que seja dominante, deve cumprir que a quantidade de pedras deverá **ser maior** que a soma das pedras de outras cores.

Por exemplo, se executamos `vermelhoEDominante()` sobre uma célula com...

* ...2 vermelhas, 1 verde, 3 pretas, 4 azuis, **denota** `False` (há 2 pedras vermelhas contra 8 de outras cores)
* ...9 vermelhas, 1 verde, 3 pretas, 4 azuis, **denota** `True` (há 9 pedras vermelhas contra 8 de outras cores)

> Escreva a função `vermelhoEDominante()`.
