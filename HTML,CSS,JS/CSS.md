# CSS

**CSS** é chamado de linguagem *Cascading Style Sheet* e é usado para estilizar elementos escritos em uma linguagem de marcação como HTML. O CSS separa o conteúdo da representação visual do site.

Uma regra CSS é representada por um seletor ou um grupo de seletores, então dentro de um par de chaves adicionamos as declarações, as declarações são formadas por uma propriedade e um valor.

## ID x Classe

ID: é representado pelo símbolo # (hash) seguido de um nome para esse ID.

Classe: a classe é representada de forma parecida do ID, mas é precedida por um ponto em vez do hash.

E a diferença mais importante entre eles é a forma como devem ser usados: o ID só pode ser usado uma vez em uma página HTML enquanto a classe não tem restrições.

## Box-model

Quando estamos criando o layout de um site o navegador representa cada elemento HTML  como uma caixa retangular, isso é o box-model. E com CSS nós alteramos a aparência dessa caixa (largura, altura, cor de fundo, etc.). Essa caixa é composta por 4 áreas: o conteúdo, o padding, a borda e a margem.

## Padding e Margin

### Margin

Adiciona uma margem ao elemento, podemos usar qualquer medida.

### Padding

Funcionamento parecido com o margin, porém ao invés de dar espaçamento externo, ele da um interno.

## Border

A propriedade *border* pode ter 3 valores: a largura, a cor e o estilo, mas existem algumas particularidades nisso.

 **solid** : mostra uma borda simples e reta;

 **dotted** : são bolinhas com um pequeno espaçamento entre elas;

 **dashed** : forma uma linha tracejada.

## Texto

### font-family

Com o font-family podemos alterar a fonte dos nossos textos, como uma fonte da internet ou uma que esteja instalada no nosso computador, mas vamos nos ater às fontes seguras, chamadas de web safe fonts.

Essas fontes são chamadas assim pois são encontradas em quases todos os sistemas e podem ser usadas sem preocupação.

### font-size

O font-size nos ajuda a mudar o tamanho do texto, existem algumas unidades de medida para ele mas por enquanto os pixels são suficientes para nós.

### font-style

Usamos o font-style para tornar um texto itálico, na maioria das vezes você usará apenas o valor *italic* para ele, mas se precisar tirar o itálico de um texto você pode usar o valor  *normal* .
