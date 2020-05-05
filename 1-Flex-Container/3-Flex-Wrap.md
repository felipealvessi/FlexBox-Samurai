# 3 • flex-wrap

Define se os itens devem quebrar ou não a linha. Por padrão eles não quebram linha, isso faz com que os **flex itens** sejam compactados além do limite do conteúdo.

Essa é geralmente uma propriedade que é quase sempre definida como flex-wrap: wrap; Pois assim quando um dos flex itens atinge o limite do conteúdo, o último item passa para a coluna debaixo e assim por diante.

```js
flex-wrap: nowrap;
// Valor padrão, não permite a quebra de linha.
flex-wrap: wrap;
// Quebra a linha assim que um dos flex itens não puder mais ser compactado.
flex-wrap: wrap-reverse;
// Quebra a linha assim que um dos flex itens não puder mais ser compactado. A quebra é na direção contrária, ou seja para a linha acima
}
```

<img width="700px" src="https://user-images.githubusercontent.com/57417305/81071567-4708a980-8ebb-11ea-812d-5f6d450d19a0.png" />

## Veja também em:
<img width="200px" src="https://user-images.githubusercontent.com/57417305/80937857-23573d80-8dad-11ea-8473-123454e87187.png"/>

[• LINK AQUI](https://codepen.io/Gohara/pen/LYpeQWN)