Viu que não fez BOOM no caso em que não podia se mover? Isso é porque Gobstones conta com um mecanismo chamado **curto circuito**, que evita que **se calculem expressões desnecessárias**.

Se o `podeMover` dá falso **não é necessário computar** o que vem depois do `&&`, porque já sabemos que o conjunto será falso. É por isso que `haPedrasAo` não chega a ser executado (e então nos safamos do BOOM). :grin:
