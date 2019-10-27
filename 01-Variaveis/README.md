# 01 - Variaveis

![Imagem de uma caixa de papelão aberta e vazia](http://www.desouzabrown.com/wp-content/uploads/2014/07/wpid-boxes.png)

## O que é uma variavel?

Sem querer usar termos tecnicos demais, variavel é como uma caixa onde vc pode guardar algo dentro.

No python não existe a nessecidade de expecificar o que sera colocado dentro, só colocar diretamente como no exemplo a seguir:

>caixa = "sapatos"

*Nesse exemplo, criamos uma variavel chamada **caixa** e dentro colocamos a palavra **sapatos***

## Regras das variaveis

Mesmo sendo extremamente simples criar uma variavel, isso daqui não é bagunça, existem regas a serem seguidas...

* Variaveis não podem ter o nome com numeros no inicio

* Variaveis precisam ser inicializadas antes de serem utilizadas

* Variaves não podem conter caracteres especias nem a letra "ç" em seu nome

* Não é permitido o uso de nomes reservados para gerar variaveis

## Imprimindo e recebendo variaveis

Podemos imprimir no terminal uma variavel de maneira muito facil, vou exemplificar de dois modos:

>print(caixa)
*Desse modo, sera impresso o valor da variavel de maneira simples*
>print("O conteudo da caixa é: " + caixa)
*Desse modo, estamos concatenando o valor da variavel com uma frase, para isso utilizamos o sinal "+"*

Igualmente é possivel receber o valor de uma variavel atravez do terminal, onde o usuario ira digitar, o modo mais simples é:

>caixa = input()
*simplismente ira captar o que o usuario digitar e apertar enter para enviar
>caixa = input("Digite algo")
*Desse modo, o usuario recebera a mensagem antes de captar o valor digitado, desse modo é possivel expecificar o que se deseja receber*

## Manipulações

Podemos fazer operações matematicas com variaveis

>resultado = a + b  
>resultado = a - b  
>resultado = a / b  
>resultado = a * b

Podemos concatenar variaveis

>a = "Ola"  
>b = "Mundo"  
>resultado = a + b

*ou*

>a = a + b

## Tipos de conteudo

Podemos receber em uma variavel os seguintes tipos

* int - Numeros Interios
* float - Numeros quebrados
* double - Numeros com virgula (similar ao float)
* string - Conjunto de caracteres, frases, palavras e tals
* char - Caracteres unitarios, somente uma letra
* bool - Booleanos, basicamente Verdadeiro e falso

*existem muitos outros, mas vamos começar com esses ;P*

## Fim !!1
