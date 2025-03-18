# Projeto E-commerce

Este repositório contém um modelo conceitual simplificado para um sistema de e-commerce, com um foco na estruturação essencial dos dados e na relação entre entidades fundamentais.

## Sobre o Projeto

O diagrama elaborado apresenta as principais entidades e suas interações dentro de um sistema de vendas online. Busquei simplificar os termos e atributos ao máximo, mantendo uma estrutura clara e objetiva.

## Estrutura do Modelo

O esquema conceitual inclui as seguintes entidades:

- **Cliente**: Contém informações como CPF, CNPJ, Nome, Razão Social e Endereço.
- **Pedido**: Registra ID do pedido, status, estorno, descrição e quantidade.
- **Produto**: Inclui ID do produto, descrição, valor e categoria.
- **Estoque**: Controla disponibilidade, local e quantidade de produtos.
- **Fornecedor**: Armazena informações como ID, razão social, CNPJ, local e quantidade de produtos fornecidos.
- **Financeiro**: Suporta formas de pagamento como crédito, débito, PIX, boleto e estorno.
- **Entrega**: Inclui detalhes sobre frete, endereço, código de rastreio e status da entrega.
- **Venda de Produtos**: Entidade central que conecta pedidos, estoque, fornecedor e entrega.
- **Vendedor Terceirizado**: Representa vendas realizadas por terceiros.

## Tecnologias Utilizadas

Este modelo foi criado com base em diagramas visuais utilizando a ferramenta (Draw.io), permitindo edição fácil e colaboração.

## Melhorias Futuras

- Refinamento dos atributos e regras de negócio.
- Expansão do modelo para incluir relacionamento com usuários e funcionalidades adicionais.
- Implementação de um banco de dados real baseado neste modelo conceitual.

Criado por **Hektor Ignacio**.

