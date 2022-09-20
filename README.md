<h1> Ecommerce_dio</h1>


-------

<h2>Vendas de produtos, uma aplicação que vai fazer uso do banco de dados para poder vender produtos, fornecendo valores e dados para o e-commerce. Contem nesse projeto, Produto, Estoque, Fornecedor, Pedido e Cliente</h2>

-------


Cliente faz o pedido, dentro do pedido tem o produto que pode estar em estoque ou não, e o produto está associado ao fornecedor.

<b>Cliente:</b> se cadastra no site, pode ser pessoa jurídica ou física, endereço determina frete, solicita um ou mais pedidos. Pedido: solicitado por um cliente e vai ter um ou mais produtos(s) 

<b>Produto:</b> categoria, associado ao fornecedor, estoque , não é exclusivo de um pedido, diferentes clientes podem comprar vários produtos, podem ter vendedores distintos (terceiros)

<b>Pedido:</b> são criados por clientes, possui informações do Cliente, um produto ou mais compõem o pedido , pedido pode ser cancelado, devolução do produto

Produto_pedido : relacionamento de  produto e pedido

<b>Fornecedor:</b> disponibiliza o produto

Disponibilizando o produto : relacionamento produto e fornecedor

<b>Estoque:</b> local, estoque distintos

Produto_estoque : mais de um estoque criar um relacionamento colocando a quantidade que e colocada no relacionamento

<b>Pagamento:</b> forma de pagamento relacionada ao pedido

Terceiro_vendedor : vende mais que um produto, relacionado a produto, terceirizado

<b>Objetivo:</b>

Refine o modelo apresentado acrescentando os seguintes pontos:

Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
R: na entidade Cliente criei um atributo numeroDocumento

Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
R: criei um entidade Pagamento com atributo forma de pagamento, relacionado a pedido

Entrega – Possui status e código de rastreio;
R:foi criado um atributo na entidade Pedido

Observações:
Foi meu primeiro contato com Banco de dados e modelagem de dados, nesse projeto tive a oportunidade de replicar o que foi ensinado pela mentora Juliana Mascarenhas.
Há alguns erros mesmo assim optei por entregar o projeto da forma que está.

![ecommerce_suellen_dio](https://user-images.githubusercontent.com/102911341/191230701-cb06646f-00dc-4711-9ad5-e2864c2a5777.png)

### Curso feito na Dio.me com a mentora Juliana Mascarenhas -Tech Education Especialist Dio/Owner- na  Dio 

## links úteis

[Dio.me](https://www.dio.me/)


