# Desafio da semana #2

Nesse exercício, você está livre para escolher os nomes para suas variáveis e funções! :smile:

```js
// Crie uma função que receba dois argumentos e retorne a soma dos mesmos.
function Soma (a, b){
return = a + b;
}

// Declare uma variável que receba a invocação da função criada acima, passando dois números quaisquer por argumento, e somando `5` ao resultado retornado da função.
return Tsoma= Soma (4, 7) + 5;
// Qual o valor atualizado dessa variável?
16

// Declare uma nova variável, sem valor.
var nulo;

/*
Crie uma função que adicione um valor à variável criada acima, e retorne a string:
    O valor da variável agora é VALOR.
Onde VALOR é o novo valor da variável.
*/
function Agregar (){
  nulo = 20;
  return "O valor da variábel é " + nulo;
}

// Invoque a função criada acima.
Agregar ();

// Qual o retorno da função? (Use comentários de bloco).
/* O valor da variábel é 20 */

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos;
2. Se qualquer um dos três argumentos não estiverem preenchidos, a função deve retornar a string:
    Preencha todos os valores corretamente!
3. O retorno da função deve ser a multiplicação dos 3 argumentos, somando `2` ao resultado da multiplicação.
*/
functio multiplicacao (valor1, valor2, valor3) {
  if (valor1 === undefined || valor2 === undefined || valor3 === undefined){
    return "Preencha todos os valores corretamente!";
  } else {
    return (valor1*valor2*valor3)+2;
  }
}

// Invoque a função criada acima, passando só dois números como argumento.
multiplicacao (1,2);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
// "Preencha todos os valores corretamente!"

// Agora invoque novamente a função criada acima, mas passando todos os três argumentos necessários.
multiplicacao (1,3,5);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
17

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos.
2. Se somente um argumento for passado, retorne o valor do argumento.
3. Se dois argumentos forem passados, retorne a soma dos dois argumentos.
4. Se todos os argumentos forem passados, retorne a soma do primeiro com o segundo, e o resultado, dividido pelo terceiro.
5. Se nenhum argumento for passado, retorne o valor booleano `false`.
6. E ainda, se nenhuma das condições acima forem atendidas, retorne `null`.
*/
function Valores (var1, var2, var3) {
  if (var1 !== undefined  && var2 === undefined && var3 === undefined) {
    return var1;
  } 
  else if (var1 !== undefined  && var2 !== undefined && var3 !== undefined) {
    return var1+var2;
  }
  else if (var1 !== undefined  && var2 !== undefined && var3 !== undefined) {
    return (var1 + var2) / var3;
  }
  else if (var1 === undefined  && var2 === undefined && var3 === undefined) {
    return fale;
  }
  else {
    return 'null';
  }
}

// Invoque a função acima utilizando todas as possibilidades (com nenhum argumento, com um, com dois e com três.) Coloque um comentário de linha ao lado da função com o resultado de cada invocação.
Valore (1); // 1
Valore (2,3); // 5
Valore (3,4,2); // 6 
Valore (); // false
```
