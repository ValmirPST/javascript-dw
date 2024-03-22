# Tipos de Dados JavaScript - Primitivos, Objeto e Array.

## Tipos Primitivos

### boolean
Representa um valor verdadeiro(True) ou falso(False).

``` JavaScript
const isTrue = True;
const isFalse = False;
```

### number
Representa valores numéricos, inteiros ou do tipo Float (pontos flutuantes).

``` JavaScript
const n1 = 50;
const n2 = 1.52;
```


### string
Representa uma sequência (linha) de caracteres. É definida entre aspas simples ou duplas.


``` JavaScript
const name = "Valmir";
const name2 = 'Matheus';
```

### undefined
Indica que uma variável foi declarada mas está sem nenhum valor atribuído à ela.

``` JavaScript
const variavelSemValor;
```


### null
Indica que uma variável não possui nenhum valor.

``` JavaScript
const variavel = null;
```

## Tipos de dados - Objeto e Array
### Objeto
Representa uma estrutura de dados mais complexa que pode conter diversos valores e métodos relacionados. É uma maneira de utilizar uma coleção de pares chave-valor, onde cada chave é única e possui um valor atribuído à ela.
O objeto é declarado entre chaves { }.

``` JavaScript
const pessoa = {
    nome: 'Valmir',
    idade: 17,
    falar: () => {
        console.log('Valmir está falando Oi');
    }
}
```

### Array
Arrays são estruturas de dados que armazenam uma coleção de elementos. Também podem ser chamados de lista, por conter uma sequência de valores, de qualquer tipo (objeto, string, number...), dentro dela.

O tipo Array pode ser definido utilizando colchetes [ ], onde os elementos irão dentro deles, e então são organizados de maneira sequencial, começando do 0:
``` JavaScript
const myArray = ['elemento01', 'elemento02'];
myArray[0] // primeiro elemento;
myArray[1] // segundo elemento...
```

Também podemos manipular o Array, alterando ou modificando seus dados:
``` JavaScript
myArray[2] = 'terceiro elemento';
```

Além de tudo isso, o array possui diversos métodos muito úteis, como push(), para adicionar um elemento, pop() para apagar o último elemento e diversos outros.
