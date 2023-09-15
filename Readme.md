Algoritmo "lanchonete do wislley"

Var
op , total , valor_item:real



Inicio

escreval("2 versao")
escreval("bem vindo a lanchonete do wislley ")
escreval("X-Salada 14,00" )
escreval("X-Bacon 16,00" )
escreval("X-Egg 13,00 ")
escreval("Refrigerante 9,00" )
escreval("Finalizar pedido" )

repita
escreval("digite op de 1 a 5" )
leia(op)

se op = 1 entao
valor_item <- 14.00
senao
se op = 2 entao
valor_item <- 16.00
senao
se op = 3 entao
valor_item <- 13.00
senao
se op = 4 entao
valor_item <- 9.00
senao
se op = 5 entao
escreval("finalizar pedido:", total)
 senao
 escreval("op invalida" )
fimse
fimse
fimse
fimse
fimse
  total<- (total+valor_item)
  ate op = 5

Fimalgoritmo



