# Documentação: 

## Exercício 1: Manipulação de Arrays

### 1.1 Criação do Array `numbers`
Neste exercício, foi criado um array chamado `numbers`, contendo os valores `[10, 20, 30, 40, 50]`.

### 1.2 Usando o método `.push()` para adicionar 60 ao final do array
Foi utilizado o método `.push()` para adicionar o número `60` ao final do array `numbers`. Após a adição, o array é impresso para mostrar o resultado.

### 1.3 Usando o método `.pop()` para remover o último elemento do array
O método `.pop()` foi utilizado para remover o último elemento do array. O valor removido é armazenado em uma variável e impresso no console. Em seguida, o array resultante é mostrado sem o último elemento.

### 1.4 Usando o método `.indexOf()` para encontrar o índice do número 30
O método `.indexOf()` foi empregado para encontrar o índice do número `30` no array. Esse índice é então impresso no console.

---

## Exercício 2: Estruturas Condicionais

### 2.1 Criação da variável `temperature`
Foi criada uma variável chamada `temperature` que armazena um valor numérico que representa a temperatura.

### 2.2 Estrutura condicional para verificar a temperatura
Foi implementada uma estrutura condicional `if-else` que verifica o valor de `temperature`:
- Se a temperatura for maior que `40`, imprime "Está muito quente!".
- Se a temperatura for maior que `30` e menor ou igual a `40`, imprime "Está quente!".
- Se a temperatura for menor ou igual a `30`, imprime "Está frio!".

Essa estrutura permite ajustar a resposta conforme o valor da temperatura.

---

## Exercício 3: Loops e Manipulação de Strings

### 3.1 Criação da variável `phrase`
Foi criada uma variável chamada `phrase` com o valor `"JavaScript is fun!"`.

### 3.2 Usando um loop `for` para imprimir cada caractere da string
Foi utilizado um loop `for` para percorrer cada caractere da string armazenada em `phrase` e imprimi-los individualmente no console.

### 3.3 Contagem de ocorrências das letras 'a' e 'A'
Foi implementado um contador para contar quantas vezes as letras 'a' ou 'A' aparecem na string `phrase`. O contador foi incrementado a cada vez que uma dessas letras foi encontrada.

### 3.4 Usando um loop `while` para imprimir números de 1 a 10
Foi utilizado um loop `while` para imprimir os números de 1 a 10 no console, incrementando a variável a cada iteração até atingir 10.

---

## Exercício 4: Escopo de Variáveis

### 4.1 Declaração da variável `x` no escopo global
Uma variável chamada `x` foi declarada no escopo global com o valor `100`.

### 4.2 Declaração de variável `x` dentro da função `testScope`
Dentro de uma função chamada `testScope`, uma nova variável `x` foi declarada com o valor `50`. Isso cria uma nova instância da variável `x`, que é diferente da variável `x` do escopo global. O valor dessa variável local foi impresso dentro da função.

### 4.3 Declaração de variável `x` dentro do bloco `if`
Dentro de um bloco `if` dentro da função, uma nova variável `x` foi declarada com o valor `30`. Isso mostra como as variáveis podem ser declaradas em diferentes blocos, com valores específicos que só são acessíveis dentro daquele bloco.

### 4.4 Imprimindo o valor de `x` fora da função
Após a execução da função `testScope`, o valor da variável `x` foi impresso fora da função. Isso demonstrou o conceito de escopo, pois a variável `x` fora da função permaneceu com o valor `100`, que é o valor da variável global.

---

