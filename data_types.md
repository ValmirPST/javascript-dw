# Tipos de Dados JavaScript - Primitivos e Objeto.

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

## Tipo de Variável - Objeto
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
