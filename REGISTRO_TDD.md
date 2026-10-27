# Registro do ciclo de TDD

## Comportamento escolhido

Cobrar uma taxa de entrega de R$ 5,00 para uma distância de 2 km, quando o pedido custa R$ 50,00

## Red

**Teste criado:** test_entrega_2_km_pedido_50

**Motivo da falha:** A função calcular_taxa_entrega ainda não estava implementada, portanto, não era possível calcular a taxa de entrega esperada

## Green

**Implementacao realizada:** Foi criada a função calcular_taxa_entrega, utilizando uma condição para verificar se a distância é de até 3 km e retornar uma taxa de R$ 5,00

## Refactor

**Melhoria realizada:** Foi criada a variavel taxa_base, no qual facilitara caso seja necessário alterar o seu valor

**Resultado final:** Todos os três testes da suíte passaram, confirmando que a implementação atende aos comportamentos testados
