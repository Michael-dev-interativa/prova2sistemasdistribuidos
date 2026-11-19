# prova-pratica-sistemas-distribuidos

Para alterar o limite de processamento simultâneo eu apenas alterei o valor da linha do código:

MAXIMO_SIMULTANEO = 3
================================================================================================
O código já está sincronizando normalmente:

print(
    "Replica antes:",
    replica["estoque"]

)

Estoque principal: 7
Replica antes: 10
Replicar depois: 7
================================================================================================
