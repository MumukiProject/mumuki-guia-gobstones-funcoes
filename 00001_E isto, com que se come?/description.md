Tome alguns minutos e tente entender o que faz este procedimento:

``` gobstones
procedure MoverConformePedras() {
  if (nroPedras(Azul) + nroPedras(Preto) + nroPedras(Vermelho) + nroPedras(Verde) > 10) {
    Mover(Leste)
  } else {
    Mover(Norte)
  }
}
```

Quando conseguir interpretar (ou se cansar), pressione Enviar e veja o resultado.