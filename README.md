# Algoritimo Bubble Sort

```Johnny Carvalho```
```30 de agosto de 2025```


## Introdução

Esse documento aborda os testes feitos em múltiplas execuções feitas utilizando o método algoritmo ```Bubble Sort```. Para isso foi desenvolvido um programa em Java que contempla esses testes.
Os cenários testados foram os seguintes:
- Executar o algoritmo Bubble Sort de forma natural (sem interrupções personalizadas)
- Executar o algoritmo Bubble Sort de forma natural adaptada (com interrupção personalizada)

A ideia é mostrar a diferença de performance entre um modelo e outro, dessa forma conseguimos extrair uma média de execução de ambos os cenários e eleger o melhor entre eles. O programa em Java funciona da seguinte maneira, o usuário escolhe quantas execuções quer testar (para esse testes usamos 10 conforme pedido no enunciado da atividade), depois disso o programa vai executar ainda na classe Main um método estático de uma classe chamada BubbleSortExecuteService no método printResult( ) {...}. Após isso o programa faz uma série de execuções, dentre ela a criação radnom de um array com 5000 inteiros, depois disso ele executa 2 classes separadas que são BubbleSortWithStop que o nome já diz, a execução do  algoritmo Bubble Sorte com parada personalizada, e depois a classe BubbleSort que essa por sua vez, executa o algoritmo na sua forma natural, ou seja, mesmo com a lista já ordenada ele continua a execução. Os resultados podemos ver a seguir.

## Relatório
O programa printa na tela os vencedores de cada execução, nesse caso podemos ver que o Bubble Sort com parada sempre vence

A média podemos ver abaixo das execuções

Como essa execução é muito mais eficaz e sempre vence, para vermos as outras fizemos com que o programa ao final da execução mostrasse o array com todos os times das execuções perdedoras bem como a média dessas execuções, aqui dá pra ver bem nítido a diferença.

## Conclusão
Com base nos dados acima, podemos notar que essa adaptação que é feita nesse algoritmo, faz com que a performance na execução do mesmo seja muito superior à original. Isso nos faz refletir que ao programar uma solução sempre podemos fazer uma analise lógica para verificar se não existe uma forma mais eficaz e performática de chegar a mesma solução, economizando recursos como poder computacional dentre outros.
