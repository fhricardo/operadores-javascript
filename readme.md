# Operadores em JavaScript
## Operadores de Atribuição
### Operador de atribuição simples
`=`
`var brinquedo = "bola"`
### Operadores de atribuição reduzida
`+=` soma um determinado valor ao valor atual da variável
`var numero = 5`
`numero += 2`
`//atribui o valor 7 à variável`
`-=` subtrai um deteeminado valor do valor atual da variável
`*=` multiplica por um determinado valor o valor atual da variável
`/=` divive por um determiinado valor o valor atual da variável
`%=` retorna o módulo da divisão do valor atual da variável por um determinado número
## Operadores Aritméticos
`+` **soma / adição**
`-` **subtração**
`*` **multiplicação**
`/` **divisão**
`%` **módulo / resto**
`**` **exponenciação**

**NOTA:**
O operador aritmético `+` também é o **operador de concatenação** para variáveis de tipos diferentes *(números e strings)* e para strings
Exemplo:
`var numero = 1`
`var texto = 'bola'`
`texto + numero`
`//resultado = bola1`
Para compor frases utilizando concatenação, podemos utiulizar trechos de texos entre aspas (simples ou duplas).
Exemplo:
`var numero = 1`
`var texto = 'bola'`
`var frase = 'Eu comprei ' + numero + ' ' + texto + ' nova'`
*O resultado para esta variável retorna o valor:*
**Eu comprei 1 bola nova**
## Operadores de Incremento e Decremento
#### Pós-incremento
`var numero = 1`
`numero++`
`//retorna o valor da variável e depois incrementa`
#### Pré-incremento
`var numero = 1`
`++numero`
`//incrementa e retorna o valor da variável`
#### Pós-decremento
`var numero = 1`
`numero--`
`//retorna o valor da variável e depois decrementa`
#### Pré-decremento
`var numero = 1`
`--numero`
`//decrementa e retorna o valor da variável`

## Operadores Relacionais
São os operadores que vão realizar a comparação entre valores de variáveis.
*Os operadores relacionais sempre retornam resultados booleanos (verdadeiro ou falso)*
`==` é igual a
`<` é menor que
`>` é maior que
`>=` maior ou igual a
`<=` menor ou igual a
`!=` não igual (diferente)
`===` igualdade estrita *(compara valor e tipo da variável)*

**NOTA:**
Quando comparamos valores numéricos *(inteiro, float, double)* é possível utilizar qualquer um dos operadores.
Quando comparamos valores textuais *(strings)* os operadores relacionais diferentes de `==`,`!=` e `===` irão comparar o comprimento das strings e sua ordem alfabética