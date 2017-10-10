# data-gov.github.io

# Dados abertos de deputados
## [Representaçāo dos dados](https://dadosabertos.camara.leg.br/)

```
graph dados_abertos {
  deputado -- partido;
  deputado -- despesa;
  deputado -- evento;
  deputado -- orgao;
  deputado -- papel;
  deputado -- legislatura;
  evento -- orgāo;
  orgao -- tramitacao;
  tramitacao -- proposicao;
  papel -- mesa;
  mesa -- legislatura;
}
```

![http://www.webgraphviz.com/](https://user-images.githubusercontent.com/823150/31393719-c3defba4-adb2-11e7-8f75-8d2b6e87fc5b.png)
