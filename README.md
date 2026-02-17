Análise de Ativos Financeiros (Python, Excel e Power BI)
Sobre o Projeto

Este projeto tem como objetivo analisar a evolução de diferentes ativos financeiros brasileiros (ações, dólar e índice IBOV) ao longo de 2023 e 2024.

A solução foi desenvolvida em três etapas principais:

1-ETL em Python → Extração, tratamento e transformação de dados históricos via yfinance.

2-Análise Exploratória no Excel → Criação de gráficos e tabelas dinâmicas para observar retornos e acumulados.

3-Dashboard em Power BI → Construção de cenários visuais, como a evolução de R$1000 investidos em cada ativo ao longo de 2 anos.

## Exportação para Excel
![Excel](/Excel.png)

Tecnologias Utilizadas:

1-Python 3.1

2-yfinance → Coleta de cotações históricas

3-pandas → Limpeza e transformação dos dados

4-Excel

5-Power BI

6-Medidas DAX para simulação de investimentos

7-Gráficos de linhas e colunas para comparar evolução patrimonial

 Como Funciona:

Coleta de Dados
O script em Python baixa cotações do Dólar, IBOV e ações (PETR4, VALE3, ITUB4, BBDC4, ABEV3).
Os dados são ajustados para incluir fins de semana/feriados (mantendo última cotação válida) e exportados para Excel.

Tratamento e Métricas
Despivotização da tabela inicial para padronização dos dados
Modelo estrela de modelagem de dados
Retorno diário
Retorno acumulado
Simulação de carteira inicial (ex.: R$1000 investidos)

Visualização
Excel → Tabelas dinâmicas + gráficos mensais
Power BI → Dashboard interativo com evolução patrimonial
## Star Schema
![Schema](/Schema.png)

## 📊 Visual do Dashboard

![Dashboard](/Dashboard_de_Ativos.png)


 Resultados Obtidos:
Comparação clara da valorização dos ativos ao longo de 2 anos.
Identificação do ativo com melhor performance e o com pior desempenho.
Criação de cenários fictícios (“Se você tivesse investido R$1000 em cada ativo...”).

 Próximos Passos
Incluir métricas de risco (ex.: volatilidade, desvio padrão).
Simular diferentes carteiras de investimento.
Implementar relatórios automatizados.

Desenvolvido por Caio Hernandes
