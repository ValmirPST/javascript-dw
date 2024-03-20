# Variáveis JavaScript - var, let e const

## var
O tipo "var" já foi um dos mais utilizados no JS antigamente. Declarações com var tem escopo global ou escopo de função. O escopo é global quando uma variável var é declarada fora de uma função, e tem escopo de função quando declarado dentro do bloco de uma função, fazendo com que a variável esteja disponível apenas neste bloco.

## let
O tipo "let" possui escopo de bloco (um pedaço de código cercado por "{}") e, sua principal diferença é que a variável com let pode ser redeclarada novamente.

## const
Diferentemente do let, variáveis do tipo "const" não podem ser redeclaradas. Porém, também são variáveis com escopo de bloco

## escopo Global
Inclui todas as variáveis e funções que são definidas fora de qualquer função ou bloco de código.

## escopo de Bloco
É quando as variáveis são declaradas dentro de um bloco de código, delimitado por chaves {}.

## escopo de Função
Todas as variáveis declaradas dentro de uma função possuem escopo de função. Ou seja, só podem ser acessadas dentro do bloco da função.

<hr>Código de Exemplo<br>

``` JavaScript
if (true) {
    var name = 'Valmir';
}
console.log(name);

if (true) {
    let name2 = 'Matheus';
    name2 = 'Amanda';
}
console.log(name2)
// erro pois a variável definida com let só pode ser acessada dentro do escopo "if" acima.

const name3 = 'Roberto';
name3 = 5;
// Erro pois a variável const não pode ser redeclarada.
```