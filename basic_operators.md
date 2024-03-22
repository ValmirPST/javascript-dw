# Operadores Básicos JavaScript - Aritméticos, De Comparação, Lógicos e typeof

## Aritméticos
São utilizados para realizar operações matemáticas em valores.
- "+" para adição
- "-" para subtração
- "*" para multiplicação
- "/" para divisão
- "%" para o operador de módulo (resto da divisão)
- "++" para incremento
- "--" para decremento

``` JavaScript
const sum = 5 + 5; // sum == 10
const sub = 5 - 5; // sub == 0
const mult = 5 * 5; // mult == 25
const div = 5 / 5; // div == 1
const remainder = 23 % 4; // remainder = 3
const num1 = 0;
num1++; // num1 passa a valer 1
num1++; // num1 passa a valer 2
num1--; // num1 passa a valer 1 novamente
```

## Comparação
São usados para comparar dois valores e retornar um resultado verdadeiro ou falso (booleano).

- "==" para igualdade de valor (sem verificar o tipo)
- "===" para igualdade de valor E tipo
- "!=" para diferença de valor (sem verificar o tipo)
- "!==" para diferença de valor ou tipo
- ">" para maior que
- "<" para menor que
- ">=" para maior ou igual a
- "<=" para menor ou igual a

``` JavaScript
console.log(5 == 5)
// output: true
console.log(23 === '23')
// output: false
console.log(10 >= 10)
// output: true
console.log(5 < 2.5)
// output: false
```

## Lógicos
Utilizados para realizar operações lógicas em valores booleanos ou expressões que retornam booleanos. Alguns exemplos são:
"&&" para "E" lógico (AND)
"||" para "OU" lógico (OR)
"!" para "NÃO" lógico (NOT)

``` JavaScript
const age = 19;
const height = 1.60;
const isHappy = true;
console.log(age > 18 && height > 1.70) // retorna false pois apenas uma condição é satisfeita
console.log(age == 12 && height > 1.55) // retorna true pois a condição da direita é satisfeita
console.log(!isHappy) // retorna false pois inicialmente a variável isHappy é true, mas com o sinal "!", ela é invertida, tornando-se falsa.
```

## typeof
O typeof é um tipo de operador que retorna uma string com o tipo do valor que está sendo analisado.
``` JavaScript
console.log(typeof 5);
// output: "number"

console.log(typeof 'Valmir');
// output: "string"

console.log(typeof true);
// output: "boolean"
```
