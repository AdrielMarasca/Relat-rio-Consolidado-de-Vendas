# Relatorio-Consolidado-de-Vendas
Este projeto apresenta um dashboard interativo desenvolvido no Power BI para análise de desempenho de vendas, utilizando dados provenientes de um banco de dados SQL Server (SSMS).  A solução foi construída com base em um modelo dimensional no formato Star Schema, garantindo alta performance nas consultas e organização eficiente dos dados.


🔗 Fonte dos dados
Banco de dados relacional (SQL Server - SSMS) contendo informações de vendas, clientes, produtos e localização - Dados Fictícios gerados a partir de prompt de IA (Deepseek).


Tecnologias utilizadas
SQL Server (SSMS) → armazenamento e consulta dos dados
Power BI → visualização e construção do dashboard
DAX (Data Analysis Expressions) → criação de métricas e indicadores
Modelagem Dimensional (Star Schema) → estruturação dos dados


Informações disponíveis no dashboard
📈 Indicadores principais (KPIs)
Faturamento Total
Ticket Médio
Número de Vendas
Maior Venda
Menor Venda

📦 Análises disponíveis
Vendas por grupo de estoque
Ranking de vendedores
Produtos com maior volume de descontos
Tabela detalhada de vendas

🎛️ Filtros interativos
Tipo de Pessoa
UF (Unidade Federativa)
Grupo de Estoque


Modelagem de dados

O projeto utiliza um modelo estrela (Star Schema), composto por:

🔹 Tabela Fato
Vendas → contém métricas como valor bruto, desconto e valor líquido
🔹 Tabelas Dimensão
Produto (Item)
Cliente (Cadastro)
Tipo de Pessoa
Localização (Cidade/UF)
Grupo de Estoque

Essa estrutura permite análises rápidas, consistentes e escaláveis.


🎯 Objetivo do projeto
Demonstrar a construção de um pipeline completo de análise de dados, desde a modelagem no banco relacional até a criação de dashboards interativos, com foco em apoiar a tomada de decisão baseada em dados.

