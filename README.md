# Javascript

### Identificadores

- Podem começar com letra, $ ou _
- Não podem começar com números.
- É possível usar letras ou números.
- É possível usar acentos e símbolos.
- Não podem conter espaços.
- Não podem ser palavras reservadas.

### Dicas

- Maiúsculas e minúsculas fazem diferença.
- Tente escolher nomes coerentes para as variáveis.
- Evite se tornar um 'programador alfabeto' ou um 'programador contador'.

### Tipos primitivos (Data types)

- number
infinity
NaN
- string
- boolean
- null
- undefined
- object
Array
-function

- typeof: mostra qual o tipo da variavel.

Number.parseInt(n) - converte para numero inteiro.
Number.parseFloat(n) - converte para numero real.
Number - deixa o próprio js decidir.
String(n) ou n.toString() - converte de número para string.

Exemplo:

var n1 = 1543.5

**Formatação de número**

n1.toFixed(n) - Alterando o 'n', você irá alterar a quantidade de casas depois da ','. EX: n1.toFixed(2) - o resultado será: 1543.50 pois está dizendo para deixar com duas casas decimais depois da virgula.

.replace('1','2') - Altera de um para o outro. Usando o código em questão todo numero '1' seria alterado para o numero '2'.

n1.toLocalString('pt-BR', {style: 'currency', currency: 'BRL'}) - irá localizar o valor e mostrar R$ 1.543,50

Exemplo:
    var s = 'Javascript'
    'Eu estou aprendendo s' // Não faz interpolação
    'Eu estou aprendendo ' + s // Usa concatenação
    `Eu estou aprendendo ${s}` // Usa template string

**Formatação de texto**

s.length - quantos caracteres a string tem.
s.toUpperCase() - tudo para 'MAIÚSCULAS'
s.toLowerCase() - tudo para 'minúsculas'

### Operadores

**Aritméticos**

Adição (+), Subtração (-), Multiplicação (*), Divisão (/), Resto da divisão inteira(%) e Potencia (**)
- Ordem de precedência: parenteses->potencia->multiplicação, divisão e resto da divisão->adição e subtração

**Atribuição**

![](C:\Users\alvar\OneDrive\Ambiente de Trabalho\Programação\javascript\cev-javascript\atribuição simples.png)


**Relacionais**
**Lógicos**
**Ternário**

