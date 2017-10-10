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
  deputado -- votacao;
  evento -- orgao;
  orgao -- tramitacao;
  tramitacao -- proposicao;
  tramitacao -- votacao;
  papel -- mesa;
  mesa -- orgao;
  legislatura -- mesa;
  legislatura -- bloco;
  bloco -- partido;
}
```

![http://www.webgraphviz.com/](https://user-images.githubusercontent.com/823150/31394315-64058a98-adb4-11e7-9825-9d65515098bb.png)
