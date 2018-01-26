Como vimos, o problema do exercício anterior foi a falta da **divisão em subtarefas**: a **expressão** que conta a quantidade de pedras que há na célula é bastante **complexa**, e leva tempo entender de maneira simples o que ela  faz.

Então, o que está faltando é algum mecanismo que possa **dar um nome** a essa **expressão complexa**; algo semelhante aos **procedimentos** mas que sirva para encapsular expressões.

A boa notícia é que Gobstones nos permite fazer isso, e a ferramenta para isso é construir uma **função**, que seja escrita assim:

``` gobstones
function nroPedrasTotal() {
  return (nroPedras(Azul) + nroPedras(Preto) + nroPedras(Vermelho) + nroPedras(Verde))
}
```

> Cole o código anterior no editor e observe o resultado.
