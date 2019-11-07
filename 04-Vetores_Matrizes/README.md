# 04 - Vetores, Matrizes e Arrary

![Arquivo de metal](https://img.kalunga.com.br/FotosdeProdutos/030850d.jpg)

## Vetores

No python ultilizamos list no lugar de vetores, são a mesma coisa, porem a list tem metodos MUITO uteis, não precisamos declarar tipo ou tamanho, pois é dinamico e aceita tipos primitivos diferentes na mesma list

Declaração de list:  

>lista = [1, 2, 3, 4]

>lista = []  

*este ultimo é a declaração de uma list vazia*

Alguns metodos:

Append(): usado para adicionar um novo elemento a list na ultima posição

>lista.append("xxx")  

Insert(): Acrescenta um elemento em uma posição expecifica

>lista.insert(4, "yyy")

Sum(): soma os elementos da lista e retorna o tamanho

>soma = sum(lista)

Len(): Retorna o tamanho da lista (quantidade de elementos)

>tamanho = len(lista)  

Count(): retorna quantas ocorrencias do termo passado tem dentro da lista

>ocorrencias = lista.count(1)

Index(): retorna o indice da primeira ocorrencia do termo dentro da lista

>x = lista.index(1)  
>x = list.index(2, 1, 4)

*nesse ultimo, o index recebe o termo a ser pesquisado (2), o inicio do dentro da faixa que sera pesquisado (1) e o fim (4)*

Pop(): remove e retorna o elemento do indice informado e caso não seja informado, ele remove o ultimo elemento

>prit(list.pop())

Del(): deleta o elemento da lista e indice informado

>del lista[0]

Remove(): remove o elemento informado

>list.remove(2)
