Olá, bem vindo.

Essa é a explicação do código calc.sh.

o código é simples, trata-se de um script em python criado dentro do Linux.
sua função ? Uma calculadora.
no início o script perguntará o nome do usuário, em seguida, pedirá ao mesmo para que escolha dois números de sua vontade.
Após isso, ele executa diversas operações matemáticas ao mesmo tempo, usando as seguintes linhas de código:

num1 = float(input("digite um número")) -- serve para perguntar ao usuário qual o primeiro número de sua escolha
num2 = float(input("digite um número"))-- serve para perguntar ao usuário o segundo número de sua escolha 

Feita a escolha, o script então começa a fazer as operações: 

soma = num1 + num2 -- soma
sub = num1 - num2 -- subtração
div = num1 / num2 -- divisão
mult = num1 * num2 -- multiplicação
porc = num1 % num2 -- porcentagem

Feitas as operações o script então entrega ao usuário a resposta de cada operação simultaneamente, como visto nas linhas:

print(soma, "Essa é a soma de suas operações," , nome)
print(sub, "Essa é a subtração de suas operações", nome)
print(mult, "Essa é a multiplicação de suas operações", nome)
print(div, "Essa é a divisão de suas operações", nome)
print(porc, "Essa é a porcentagem de suas operações", nome)

O script é finalizado com um agradecimento por tê-lo usado, usando a linha de código:

print("Obrigado por usar este script", nome)
