# PROJETO DE DESENVOLVIMENTO DE SOFTWARE

## 1.INTRODUÇÃO
Este projeto tem como objetivo desenvolver um sistema de banco de dados relacional para a livraria "Books&Co". A empresa necessita de uma solução para gerenciar eficientemente suas operações, incluindo o cadastro de livros, controle de vendas, gerenciamento de clientes e fornecedores. A proposta apresentada visa implementar um banco de dados que suportará essas funcionalidades, proporcionando uma base estruturada e segura para as operações diárias da livraria.

# 2.OBJETIVO
# 2.1 Objetivo Geral:
O objetivo geral do projeto é projetar e implementar um banco de dados relacional para a livraria "Books&Co", de forma a permitir o gerenciamento eficiente de livros, clientes, vendas e fornecedores, facilitando o controle do estoque, registro de vendas e manutenção de informações dos clientes e fornecedores.

# 2.2 Objetivo Específico:
•	Desenvolver um sistema de cadastro de livros com informações sobre título, autor, preço e quantidade em estoque.
•	Criar um módulo para registro de clientes, contendo nome, e-mail e telefone.
•	Implementar o registro de fornecedores, incluindo dados como nome, CNPJ e contato.
•	Projetar a funcionalidade de registro de vendas, incluindo a data, cliente envolvido, livros vendidos e o total da venda.
•	Gerar relatórios que listem as vendas realizadas por cliente, facilitando a análise de desempenho e o gerenciamento das operações de vendas.

# 3. RESULTADO
O desenvolvimento do projeto foi realizado em etapas, conforme descrito abaixo:

# Modelagem Conceitual e Lógica do Banco de Dados:
Foi criado um Diagrama Entidade-Relacionamento (ER) que inclui as entidades Livros, Clientes, Fornecedores e Vendas, com seus respectivos atributos e relacionamentos. Um relacionamento "muitos para muitos" foi estabelecido entre Vendas e Livros, enquanto um relacionamento "um para muitos" foi definido entre Clientes e Vendas, e outro entre Fornecedores e Livros.

# Conceitual:
![](Model.%20Conceitual.PNG)

# Lógica:
![](Model.%20Lógica.PNG)

# Conversão para Modelo Relacional:
O diagrama ER foi convertido em um modelo relacional, resultando na criação de tabelas que representam as entidades do sistema. Foram definidas chaves primárias e estrangeiras para garantir a integridade dos dados.

# Criação do Banco de Dados e Tabelas:
Utilizando o MySQL, foram executadas instruções SQL para criar as tabelas do banco de dados. A integridade referencial foi garantida por meio da definição de chaves estrangeiras que conectam as tabelas de forma lógica e coerente.

# Implementação e Testes:
O banco de dados foi populado com dados fictícios para testes, permitindo a validação das funcionalidades implementadas, como o cadastro de novos livros, registro de clientes e vendas, e geração de relatórios.

# 4.DISCUSSÃO
Durante o desenvolvimento do projeto, foram realizados ajustes na modelagem dos dados para atender às necessidades específicas da livraria "Books&Co". A definição dos relacionamentos entre as entidades foi um passo crucial para garantir que o sistema fosse capaz de lidar com as operações diárias de forma eficiente. Além disso, a implementação das tabelas no MySQL mostrou a necessidade de considerar otimizações de consultas e índices para garantir a performance do sistema.

# 5.CONCLUSÃO
O projeto foi desenvolvido com o objetivo de atender os requisitos propostos, resultando em um banco de dados funcional que suporta as operações básicas da livraria "Books&Co". A estrutura criada permite fácil manutenção e expansão futura, podendo ser adaptada conforme as necessidades do cliente evoluam.

# BIBLIOGRAFIA
SILBERSCHATZ, Abraham; KORTH, Henry F.; SUDARSHAN, S. Sistemas de Banco de Dados. 6. ed. São Paulo: Pearson, 2019.

DATE, C. J. Introdução a Sistemas de Bancos de Dados. 8. ed. Rio de Janeiro: Elsevier, 2006.

ELMASRI, Ramez; NAVATHE, Shamkant B. Sistemas de Banco de Dados. 7. ed. São Paulo: Pearson, 2017.

