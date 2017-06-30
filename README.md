# Estudo de Flex-box
---

## Introdução

### O que é flex-box?

O CSS **Flexible Box Layout Model** ou para os mais intimos **Flexbox**, faz parte da especificação do CSS3 que pretende organizar elementos na página sem o uso do nosso querido **float** *(ironia)* e também resolve mais alguns problemas que temos atualmente em relação ao tamanho dos elementos, onde apelamos para o **box-sizing"**.

### Como ele funciona?

Os filhos de um elemento com a propriedade **flexbox** podem se posicionados em qualquer direção e se necessário podem ter tamanhos flexíveis para se adaptar. Um dos problemas do float é a sua dependência com os demais elementos na estrutura do HTML, os elementos devem estar em uma direção específica ou o layout irá quebrar. Com o uso do flexbox não precisamos nos preocupar com isso, os elementos irão se ajustar ao layout dinamicamente.

### Declaração

Basicamente as propriedades do flexbox são adicionadas no elemento pai para que os filhos sejam afetados.

**CSS**
```css
.pai {
  display: flex;
 }
 
 .filho {
  ...
 }
```

**HTML**
```html
<div class="pai">
  <div class="filho">
    1
  </div>
  <div class="filho">
    2
  </div>
</div>
```

[Exemplo](https://codepen.io/tunadao1/pen/weyrQQ "Exemplo no Codepen")

### Utilização

Suponho que você já tenha lido a introdução, se não leia clicando [aqui](#introdução)
