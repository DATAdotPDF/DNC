README

# Desafio DNC: Preveja os resultados de um e-commerce utilizando o Power BI

# 🚀 Desafio

[Base de dados desafio.xlsx](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d5d21dd8-4c11-4e13-8821-b7dacab4f189/Base_de_dados_desafio.xlsx)

Neste desafio proposto pela escola de Engenharia de Dados DN, previ os resultados de um e-commerce utilizando o Power BI

Apliquei meus conhecimentos de Excel e de Power BI para construir um modelo de regressão linear capaz de prever os resultados de faturamento de um e-commerce. 
> 

## **Contexto**

Neste desafio, tive que construir um painel gerencial para um e-commerce que almeja estudar as suas vendas e assim, traçar a melhor estratégia para alavancar seus resultados.
Usando duas bases de dados, uma com dados das vendas e outra com informações dos clientes. Com isso, criei duas páginas para que os analistas possam visualizar as métricas.
Criei as determinadas métricas: Quantidade total e valor total de vendas, Cotagem e valor total de vendas por data, quantidade e valor total por categoria e criei os filtros necessários para fornecer ao usuário a melhor experiência. 

Com base no contexto fornecido, criei dashboards para permitir que a equipe de negócios desenvolva planos de ação com o objetivo de aumentar o número de usuários cadastrados e impulsionar o crescimento da empresa.

1. Importei as duas bases para o Power BI
2. Criei uma coluna na base cliente de faixa de rendas, clusterizando entre os seguintes valores
    1. Até 10000
    2. Até 7500
    3. Até 5000
    4. Até 2500
    5. Até 1750
3. Criei 2 páginas: Visão do clientes e Visão Compra

# 🎯 Etapas de Desenvolvimento

## **Etapa 01) Tipo de gráfico: Cartões**

1. **Primeiro analisei as tabelas recebidos no Excel, olhei as colunas, entendi os valores que possuem nela e a definição para o negócio**
2. Criei um card de quantidade de vendas
3. Criei um card de valor total de vendas sem frete ($)
4. Criei um card de valor total de vendas com frete ($)
5. Criei um card de quantidade de clientes
6. Criei um card de média de renda dos clientes

## **Etapa 02) Tipo de gráfico: Gráfico de linhas**

1. Adicionei a contagem de vendas por mês
2. Adicionei o valor total de vendas por mês

## **Etapa 03) Tipo de gráfico: Gráfico de Barras**

1. Adicionei quantidade de vendas por categoria
2. Adicionei valor total de vendas por categoria
3. Adicionei distribuição de idades dos clientes
4. Adicionei distribuição de renda dos clientes

## **Etapa 04) Filtro**
Adicionei as seguintes categorias;
1. Bandeira
2. Estado
3. Canal de venda
4. Departamento
5. Idade
6. Faixa de renda
7. Estado de nascimento

# 📝 Critérios de Avaliação

Os critérios de avaliação mostram como fui avaliado em relação ao desafio. 

# **Critérios de Avaliação:**

| **Critérios** | **Atendeu às Especificações** | **Pontos** |
| --- | --- | --- |
| **Tipo de gráfico: Cartão** | Elabore 5 gráficos tipo cartão utilizando as simbologias de moeda para representar indicadores financeiros | 20 |
| **Tipo de gráfico: Linhas** | Crie 2 gráficos de linhas, onde o eixo x deve ser uma série temporal (datas), representando tendências ao longo do tempo  | 30 |
| **Tipo de gráfico*:* Barras** | Crie 4 gráficos de barras: 2 gráficos comparando vendas por categoria (um em quantidade de vendas e outro em valor de vendas), 1 histograma de idades dos clientes, e 1 gráfico de barras para a distribuição de rendas dos clientes | 30 |
| **Filtro** | Crie filtros interativos para as seguintes categorias: bandeira, estado, canal de venda, departamento, idade, faixa de renda, e estado de nascimento | 20 |

Nota final: 10
