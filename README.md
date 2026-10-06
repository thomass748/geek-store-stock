Clientes (id, nome, número, data_nascimento)
 |
 |
/|\
Vendas (id, total_gasto, FK(id_cliente)
 |
 |
/|\
 itens_venda (id_venda, id_produto)
\|/
 |
 |
Produtos (id, preco, descricao)
