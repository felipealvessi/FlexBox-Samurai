# 5 • justify-content [row]

Alinha os itens flex no container de acordo com a direção. A propriedade só funciona se os itens atuais não ocuparem todo o container. Isso significa que ao definir flex: 1; ou algo similar nos itens, a propriedade não terá mais função

Excelente propriedade para ser usada em casos que você deseja alinhar um item na ponta esquerda e outro na direita, como em um simples header com marca e navegação.

```js
justify-content: flex-start;
// Alinha os itens ao início do container.
justify-content: flex-end;
// Alinha os itens ao final do container.
justify-content: center;
// Alinha os itens ao centro do container.
justify-content: space-between;
// Cria um espaçamento igual entre os elementos. Mantendo o primeiro grudado no início e o último no final.
justify-content: space-around;
// Cria um espaçamento entre os elementos. Os espaçamentos do meio são duas vezes maiores que o inicial e final.
```

<img width="700px" src="https://user-images.githubusercontent.com/57417305/81176516-a0381200-8f7b-11ea-8181-b9893ae69d9f.png" />

## Veja também em:
<img width="200px" src="https://user-images.githubusercontent.com/57417305/80937857-23573d80-8dad-11ea-8473-123454e87187.png"/>

[• LINK AQUI](https://codepen.io/Gohara/pen/bGVLeEz)

# 5 • justify-content - [column]

O eixo principal também pode ficar na vertical. Nesse caso, flex-direction é definido como coluna. Veja como os flex items serão alinhados nessa instância.

<img width="700px" src="https://user-images.githubusercontent.com/57417305/81215092-2e79bb80-8faf-11ea-811a-495d01734d19.png" />

## Veja também em:
<img width="200px" src="https://user-images.githubusercontent.com/57417305/80937857-23573d80-8dad-11ea-8473-123454e87187.png"/>

[• LINK AQUI](https://codepen.io/Gohara/pen/ZEbrOdK)
