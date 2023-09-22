# Exercício 02 \(exerc02.py\)

> Faça um programa, em Python, que leia o nome do usuário e mostre a mensagem: "Olá, ***\<nome\>***!!!".

Uma tarefa muito comum em vários programas, é a necessidade de solicitar que o usuário entre com algum dado para que o programa possa processá-lo e gerar uma saída.

A entrada de dados por parte do usuário pode acontecer de várias formas: através da digitação dos dados  no terminal... através de campos em uma janela gráfica... através de campos em uma página HTML em um navegador... 

Nesse exercício será usada a função `input()` que permite que o usuário digite os dados através do terminal. 

### Sintaxe da função `input()`
```
variavel = input('mensagem: ')
```

A mensagem passada como argumento para a função `input()` é opcional. Caso a mensagem seja passada como argumento da função, ela será impressa na saída padrão \(normalmente a tela do terminal\) sem o caractere de nova linha. 

O sistema aguardará que o usuário digite algo e precione a tecla \[Enter\]. O valor digitado pelo usuário será armazenado, como uma string, na `variavel`. O caracter de nova linha \(tecla \[Enter\]\) será removido da string final armazenada na `variavel`.  

Na solução desse exercício, será usada a função `input()` para solicitar o nome do usuário e depois a função `print()` para mostrar a mensagem de saudação.

A mensagem de saudação será composta de três partes: o texto: "Olá, ", o nome digitado pelo usuário e o texto: "!!!". Nesse exercício, será usado o caracter ` + ` para concatenar \(juntar\) as três partes da mensagem. Em exercícios futuros, serão usadas outras formas de conseguir o mesmo resultado.