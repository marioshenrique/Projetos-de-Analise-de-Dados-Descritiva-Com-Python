# Projeto de Análise de Dados Financeiros

Este projeto tem como objetivo realizar uma análise descritiva dos dados financeiros de uma organização. A base de dados utilizada para a análise contém as seguintes colunas:

- **Tipo**: Uma variável categórica que representa o tipo de fluxo de caixa, podendo ser 'Receitas' ou 'Despesas'.
- **Componente**: Uma variável categórica que identifica o componente específico de despesa ou receita. Para receitas, os componentes podem ser aluguel, franquias, investimentos, licenciamento, publicidade e vendas. Para despesas, os componentes podem ser administrativo, impostos, marketing, salários, segurança e tecnologia.
- **Data**: Uma variável de data que denota o mês e ano de cada fluxo de caixa, cobrindo o período de janeiro de 2019 até dezembro de 2022.
- **Valor**: Esta coluna representa o valor monetário associado a cada tipo de receita ou despesa para cada mês.

## Questões de Negócio

A análise teve como objetivo responder as seguintes perguntas:

1. Qual é a tendência geral das receitas e despesas da organização ao longo do tempo?
2. Qual componente gera mais receita para a organização?
3. Quais são os maiores componentes de despesa da organização?
4. Como a receita e as despesas variam ao longo do ano? Existe alguma sazonalidade?
5. Qual é o fluxo de caixa líquido (receitas menos despesas) da organização em cada mês/ano?
6. Qual é a proporção de cada componente de receita em relação à receita total? E para as despesas?

## Resultados

Os insights extraídos da análise foram representados através de um dashboard interativo no Power BI, facilitando a visualização e a compreensão das respostas às perguntas de negócio.

## Ferramentas Utilizadas

Para a análise de dados, foram utilizadas as seguintes ferramentas:

- **Python**: para limpeza e preparação dos dados.
- **Pandas**: para manipulação de dados e análise exploratória.
- **Matplotlib** e **Seaborn**: para visualização de dados.
- **Power BI**: para a construção de um dashboard interativo.
