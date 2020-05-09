# 1 • flex-grow

Define a habilidade de um flex item crescer. Por padrão o valor é zero, assim os flex itens</br>
ocupam um tamanho máximo relacionado ao conteúdo interno deles ou ao width definido.

Ao definir 1 para todos os Flex itens, eles tentarão ter a mesma largura e vão ocupar 100% do container.</br> Digo tentarão pois caso um elemento possua um conteúdo muito lardo, ele ira respeitar o mesmo.

Se você tiver uma linha com quatro itens, onde três são flex-grow: 1 e um flex-grow:2, o flex-grow:2</br>
tentará ocupar 2 vezes mais espaço extra do que os outros elementos.

OBS: justify-content não funciona em items com flex-grow definido.

```js
flex-grow: número;
// Basta definir um número
flex-grow: 0;
// Obedece o width do elemento ou o flex-basis.
```

<img width="700px" src="https://user-images.githubusercontent.com/57417305/81484395-71d86200-921b-11ea-86c0-d16851069e32.png" />

## Veja também em:
<img width="200px" src="https://user-images.githubusercontent.com/57417305/80937857-23573d80-8dad-11ea-8473-123454e87187.png"/>

[• LINK AQUI](https://codepen.io/Gohara/pen/JjYvbmg)