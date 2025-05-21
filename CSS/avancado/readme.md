Qual é o formato da água?

![foto1](img/1.PNG)

Se eu por no jarro, é um formato de um jarro
Se eu por na garrafa é um formato de uma garrafa
Se eu por no copo é o formato de um copo

A forma da água vai depender do recepiente em que ela estiver

![foto2](img/2.PNG) 

O flexbox é para resolver problemas onde as caixas não estão se encaixando. Ele cria um layout mega flexível para adaptar o conteúdo

![foto3](img/3.PNG)

No flexbox nós não conseguimos dizer efetivamente o tamanho da caixa, o conteúdo da caixa e o contener nela, vão definir o tamanho e formato dela.

![foto4](img/4.PNG)
Dentro dessas caixas flexíveis nós podemos criar caixas dentro que chamamos de **itens**

Oque acontece se eu não usar o Flex Box Module?

![foto6](img/6.PNG)

Se eu alterar o formato do contener de fora, o contener de dentro não irá se adaptar, gerando um transbordamento

![foto7](img/7.PNG)

Agora com o Flex Box:

![foto8](img/8.PNG)


a grande maioria dos celular e computadores suportam flexbox hoje em dia, entretanto, algumas smarTvs antigas podem não suportar

Se eu der uma reduzida na caixa de fora:

![foto9](img/9.PNG)

elas se tornaram **fluídas**

Eu posso escolher a posição dos itens

![foto9](img/10.PNG)

![foto9](img/11.PNG)

Quando usamos o flexbox a propriedade **stech** ja vem ligada que estica e encolhe dinamicamente

Também podemos configurar pra ter um deslocamento inferior
![foto9](img/12.PNG)

Podemos fazer com que essa caixa que quebrou fique adaptável ao contenner

![foto9](img/13.PNG)

Também podemos reconfigurar o flexbox para trabalhar com caixas verticalmente alinhadas

![foto9](img/14.PNG)

E que também podem se adaptar

![foto9](img/15.PNG)

**Só colocamos o display flex no contenner**

**Os itens não vão receber a configuração do display flex, eles vão receber outras configurações**

Flex-container = Pai
Flex-items = filhos

![foto9](img/17.PNG)

![foto9](img/16.PNG)

# Direções e Eixos

## Direções
As configurações de direções são realizadas no pai

### Propriedades do flex-direction

Por padrão a propriedade é **flex-direction: row;**
da esquerda pra direita (diração da leitura)
![foto9](img/18.PNG)


**flex-direction: row-reverse;** - Modo reverso, os elementos serão postos da direita pra esquerda

![foto9](img/19.PNG)

**flex-direction: row-column;** - Elementos serão postos de cima pra baixo muito utilizado pra celulares

![foto9](img/20.PNG)

**flex-direction: column-reverse;** - Os elementos serão postos de baixo para cima

![foto9](img/21.PNG)

## Eixos

### Propriedades do main-axis

O primeiro eixo que é criado é o eixo principal, conhecido como **main-axis**. Cada eixo possui dois pontos, o ponto inicial e o ponto final, **main-start** e **main-end**

![foto9](img/22.PNG)

### Propriedades do eixo transversal cross-axis

O principal eixo transversal que é criado é conhecido como **cross-axis**. Cada eixo possui dois pontos, o ponto inicial e o ponto final, **cross-start** e **cross-end**

![foto9](img/23.PNG)

![foto9](img/24.PNG)
> Quando o flex direction row estiver configurado por padrão no nosso idioma

![foto9](img/25.PNG)

> Quando o flex direction row-reverser estiver configurado o main-axis inverte e o cross-axis não tem inversão

![foto9](img/26.PNG)
> Quando o flex direction column estiver configurado o main-axis vai de cima pra baixo e o cross-axis segue a direção padrão que é da esquerda pra direita

![foto9](img/27.PNG)
> Quando o flex direction column-reverse estiver configurado o main-axis vai de baixo pra cima e o cross-axis segue a direção padrão que é da esquerda pra direita