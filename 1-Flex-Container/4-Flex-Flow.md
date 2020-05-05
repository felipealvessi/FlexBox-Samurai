# 4 • flex-flow

O flex-flow é um atalho para as propriedades flex-direction e flex-wrap. Você não verá muito o seu uso,
pois geralmente quando mudamos o flex-direction para column, mantemos o padrão do flex-wrap que é nowrap.</br>
E quando mudamos o flex-wrap para wrap, mantemos o padrão do flex-direction que é row.

```js
flex-flow: row nowrap;
// Coloca o conteúdo em linha e não permite a quebra de linha.
flex-flow: row wrap;
// Coloca o conteúdo em linha e permite a quebra de linha.
flex-flow: column nowrap;
// Coloca o conteúdo em coluna e não permite a quebra de linha.
}
```

<img width="700px" src="https://user-images.githubusercontent.com/57417305/81118043-899fa580-8efe-11ea-90ce-9d37d8512b97.png" />

## Veja também em:
<img width="200px" src="https://user-images.githubusercontent.com/57417305/80937857-23573d80-8dad-11ea-8473-123454e87187.png"/>

[• LINK AQUI](https://codepen.io/Gohara/pen/qBOpvZX)