#Problema
Identificar todas as possíveis soluções do "quadrado mágico".

>Uma solução inclui a disposição de todos os números inteiros naturais de 1 a 16, inclusive, em uma matriz 4x4 de tal forma que as somas dos números em cada uma das linhas, em cada uma das colunas e em cada uma das diagonais seja 34.

Na ilustração abaixo o “quadrado”, “matriz” ou “tabuleiro” está parcialmente preenchido, restando o acréscimo dos números 2, 3, 4, 6, 10, 12 e 13. Observe que este preenchimento parcial não é parte de uma solução, pois a linha contendo 14 e 9, o que perfaz 23, precisa nas duas outras posições de números cuja soma deve perfazer 11, o que não é possível com os números ainda não empregados.

<img src="https://github.com/kyriosdata/desafio4x4/blob/main/imagens/4x4.png" width="300">

####Proposta de solução:
>Para a resolução do quadrado mágico, seria necessário desenvolver um programa com o máximo de performance, utilizando boas práticas para conseguir ter uma otimização boa. Nesse software, que claramente teria problema com desempenho, ele faria a mudança de posição de todos os 16 números, até obter o(s) resultado(s) que atende ao que foi especificado (que a soma de cada uma das linhas, de cada uma das colunas e de cada uma diagoanais seja 34), armazenando em uma matriz e mostrando a mesma no final da execução.