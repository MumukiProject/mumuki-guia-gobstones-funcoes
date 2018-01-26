Para finalizar, vamos codificar a função `estouLimitada()`, que determina se há algum tipo de limite na hora de mover a garra.

O limite pode ser por algum dos dois fatores: porque **estou em uma borda** e então não posso me mover em alguma direção, ou porque **estou rodeado de pedras vermelhas** que impedem de que se mova. Se **alguma** dessas duas condições ocorre, quer dizer que estou limitada.

> Usando `estouEmUmaBorda` e `estouRodeadoDe`, escreva `estouLimitada`.
