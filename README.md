📘 Sistema de Gestão de Vendas — Banco de Dados (SQL Server)
---
📌 Visão Geral do Projeto

O Sistema de Gestão de Vendas é um projeto de banco de dados desenvolvido em SQL Server, com o objetivo de praticar e demonstrar conceitos de modelagem relacional, consultas SQL, regras de negócio, integridade de dados e lógica no nível do banco de dados.
O projeto simula um ambiente real de vendas, envolvendo clientes, produtos, categorias, vendas e itens de venda, focando na implementação de regras diretamente no banco, sem dependência de aplicação.

---
🎯 Objetivos do Projeto
- Praticar SQL Server e T-SQL
- Aplicar regras de negócio no banco de dados
- Garantir integridade e consistência dos dados
- Utilizar views, procedures e triggers
- Criar um projeto de portfólio profissional
---
🗂️ Estrutura do Banco de Dados

O banco de dados é composto pelas seguintes tabelas:
- CLIENT -> cadastro de clientes e controle de status (ativo/inativo)
- CATEGORY -> categorias dos produtos
- PRODUCT -> produtos e controle de estoque
- SALE -> registros de vendas
- SALE_ITEM -> itens detalhados das vendas
---
🔍 Consultas SQL (SELECT & JOIN)

Foram desenvolvidas diversas consultas utilizando:
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- GROUP BY e HAVING
- Funções de agregação (SUM, AVG, COUNT)

Exemplos de consultas:
- Clientes que não realizaram compras
- Total de vendas por cliente
- Produtos vendidos e não vendidos
- Média das vendas por método de pagamento
---
👁️ Views

Views criadas para facilitar a visualização de dados importantes:
- Sales Detail View –> vendas com informações de clientes e produtos
- Low Stock View –> produtos com estoque abaixo do limite definido
---
⚙️ Stored Procedures

Procedures implementadas para centralizar regras de negócio:
- Inserir novas vendas
- Inserir novas categorias
- Atualizar estoque de produtos
- Calcular o valor total da venda com base nos itens
- Bloquear venda para clientes inativos
- Validar estoque antes de inserir itens de venda
---
🔔 Triggers

Triggers desenvolvidas para garantir integridade e auditoria:
- Bloquear vendas para clientes inativos
- Impedir exclusão de clientes com vendas
- Impedir exclusão de produtos já vendidos
- Impedir alteração de preço de produtos já vendidos
---
🛡️ Integridade de Dados e Regras de Negócio

As regras de negócio são aplicadas diretamente no banco de dados através de:
- Chaves estrangeiras
- Stored procedures
- Triggers
Essa abordagem garante consistência dos dados independentemente da aplicação que consuma o banco.
---
🧪 Tecnologias Utilizadas
- SQL Server
- T-SQL
- Views
- Stored Procedures
- Triggers
---
🚀 Como Executar o Projeto
1) Criar o banco de dados
2) Executar os scripts de criação das tabelas
3) Executar os scripts de inserção de dados
4) Executar os scripts de queries e joins, views, procedures e triggers
--- 
💼 Objetivo Profissional

Esse projeto foi desenvolvido com foco em aprendizado e portifólio, demonstrando habilidades práticas em banco de dados, lógica de negócio e desenvolvimento backend.

---
✍️ Autora

[@LivAristides](https://github.com/LivAristides)

<img width="1915" height="830" alt="Captura de tela 2026-01-15 210010" src="https://github.com/user-attachments/assets/67f43fad-c2a7-4ba9-9d1a-12de50157f99" />
<img width="1918" height="834" alt="Captura de tela 2026-01-15 205947" src="https://github.com/user-attachments/assets/a513ebe2-35f7-4b7a-8caf-3459a1100257" />
<img width="1907" height="831" alt="Captura de tela 2026-01-15 205636" src="https://github.com/user-attachments/assets/e283f83c-3aa5-454b-af0a-4b520414dc61" />
<img width="1911" height="785" alt="Captura de tela 2026-01-15 205538" src="https://github.com/user-attachments/assets/ed17b832-51d6-4729-96bd-cca146811880" />
<img width="899" height="687" alt="Captura de tela 2026-01-15 210211" src="https://github.com/user-attachments/assets/fcd5b1f7-aaec-439a-a648-0b8eb310d5e1" />
