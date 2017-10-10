# data-gov.github.io

# Dados abertos de deputados
## Representaçāo dos dados
[LINK API](https://dadosabertos.camara.leg.br/)

```
graph dados_abertos {
  deputado -- despesa;
  deputado -- evento;
  deputado -- orgao;
  deputado -- papel;
  deputado -- partido;
  deputado -- legislatura;
  evento -- orgāo;
  orgao -- tramitacao;
  tramitacao -- proposicao;
  papel -- mesa;
  mesa -- legislatura;
}
```

![http://www.webgraphviz.com/](https://user-images.githubusercontent.com/823150/31393023-1b0285ec-adb1-11e7-9300-5d1fa8fb0ca7.png)
