# Sistema de Gerenciamento de Biblioteca

Este é um sistema simples de gerenciamento de biblioteca feito em Python, que permite o cadastro de livros, clientes, e a realização de vendas. O projeto foi desenvolvido para uma aula de revisão de logica de progamação utilizando de lista e dicionarios

## Funcionalidades

### Livros
- **Cadastrar Livro**: Adiciona um novo livro ao sistema, solicitando título, autor, preço e quantidade em estoque.
- **Exibir Todos os Livros**: Lista todos os livros cadastrados com suas respectivas informações.
- **Editar Livro**: Permite editar as informações de um livro específico, como título, autor e preço.
- **Alterar Estoque do Livro**: Atualiza a quantidade em estoque de um livro.
- **Pesquisar Livro por Código**: Pesquisa um livro a partir do código único.
- **Alterar Disponibilidade do Livro**: Alterna a disponibilidade de um livro para venda (disponível ou não disponível).
- **Aplicar Desconto no Livro**: Aplica um desconto percentual no preço de um livro.
- **Buscar Livro por Autor**: Permite buscar livros cadastrados a partir do nome do autor.
- **Filtrar Livros por Preço**: Filtra livros com preço acima ou abaixo de um valor informado pelo usuário.

### Clientes
- **Cadastrar Cliente**: Adiciona um novo cliente ao sistema.
- **Listar Clientes**: Lista todos os clientes cadastrados.
- **Realizar Venda**: Permite que um cliente compre um ou mais exemplares de um livro. Verifica a disponibilidade em estoque e o total da compra.

## Estrutura do Projeto

O código está dividido em diversas funções para facilitar a organização e a leitura. Essas funções são chamadas dentro dos menus principais, que dividem as operações entre Livros e Clientes.

### Estrutura Principal

- **Main Menu**: O menu inicial permite escolher entre a seção de Livros ou de Clientes.
- **Seção de Livros**: Onde estão disponíveis todas as operações relacionadas a livros.
- **Seção de Clientes**: Onde estão disponíveis as operações de cadastro e listagem de clientes.
