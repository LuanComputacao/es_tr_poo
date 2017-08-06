# Trabalho de Pós Graduação em Engenharia de Software

Trabalho prático Swing e JDBC



## O sistema terá os seguintes requisitos:

1. Uma tela para manter (incluir, atualizar, excluir e listar) os clientes da empresa (Nome, sobre nome, CPF)
  - Nesta tela deve ser possível listar todos os clientes (Use AbstractTableModel)
  - Deve ser possível atualizar os dados de um cliente.
  - Deve ser possível excluir um cliente que não possua pedidos. Se houver uma tentativa de exclusão de clientes com pedidos uma mensagem do sistema deve informar ao usuário que o cliente não pode ser excluído.
2. Uma tela simples para manter os produtos disponíveis.
3. Uma tela para incluir os pedidos novos quando são comprados
  - Um campo para informar o CPF do cliente (O CPF deve ser único)
  - Uma lista de produtos (descrição)
  - Uma maneira para selecionar um produto
d. Um botão para incluir o produto selecionado no pedido do cliente, informando a quantidade do produto.
4. Uma tela para listar o pedido de um cliente.
  - Um campo para informar o CPF do cliente.
  - Um botão para listar os itens do pedido do cliente
  - Uma tabela para mostrar os itens do pedido:

|Produto                  |Quantidade|
| ----------------------- | -------- |
|Papel A4                 |2         |
|Caneta esferográfica azul|20        |
|Pasta                    |2         |

5. Considere as seguintes tabelas do banco de dados e crie as classes DAO necessárias para persistência:

## O programa acima deve utilizar as seguintes tecnologias:
  - Java Swing
  - JDBC para persistência em banco de dados. Utilize o Design Pattern “Data Access Object” para persistência.
## Itens para serem entregues:
1. Projeto na IDE Eclipse ou Netbeans com código fonte
2. Script para criação do banco de dados
3. Arquivo .jar executável

## Avaliação:
 - Material entregue
 - Qualidade do software (bugs encontrados na defesa)
 - Defesa do código e a nota será individual, considerando a defesa
