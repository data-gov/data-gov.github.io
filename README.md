# data-gov.github.io

# Dados publicos abertos e transparentes
A ideia do projeto é facilitar o acesso aos dados de transparencia dos portais brasileiros. Atualmente temos essas informaçoes disponiveis de uma maneira dificil de usar as informaçoes.
O objetivo principal do projeto é criar uma camada de abstraçao em cima dos portais transparencia, para que as pessoas possam acessar essas informaçoes de maneira simplificada, com isso facilitando a criacao de aplicacoes que tenham por objetivo fazer analise ou pubilcacao destes dados.

## Agente conversacional
O primeiro projeto que fez uso desses dados foi um agente conversacional que responde perguntas sobre dados historicos de eleicoes.
A representaçāo dos sistemas que compuseram esta aplicacao é a seguinte:
![datagov-diagrama](https://user-images.githubusercontent.com/823150/31866407-b20a35ce-b75d-11e7-921d-5138c98eb504.png)
Mais informaçoes em:
[data-gov/wheeljack](https://github.com/data-gov/wheeljack)

## [Representaçāo dos dados de deputados](https://dadosabertos.camara.leg.br/)
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
