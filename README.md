Análise de Ativos Financeiros (Python, Excel e Power BI)
Sobre o Projeto

Este projeto tem como objetivo analisar a evolução de diferentes ativos financeiros brasileiros (ações, dólar e índice IBOV) ao longo de 2023 e 2024.

A solução foi desenvolvida em três etapas principais:

1-ETL em Python → Extração, tratamento e transformação de dados históricos via yfinance.

2-Análise Exploratória no Excel → Criação de gráficos e tabelas dinâmicas para observar retornos e acumulados.

3-Dashboard em Power BI → Construção de cenários visuais, como a evolução de R$1000 investidos em cada ativo ao longo de 2 anos.

Tecnologias Utilizadas:

-Python 3.1
-yfinance → Coleta de cotações históricas
-pandas → Limpeza e transformação dos dados
-Excel
-Tabelas dinâmicas
-Gráficos comparativos de acumulado e retornos médios
-Power BI
-Medidas DAX para simulação de investimentos
-Gráficos de linhas e colunas para comparar evolução patrimonial

 Como Funciona:

Coleta de Dados
O script em Python baixa cotações do Dólar, IBOV e ações (PETR4, VALE3, ITUB4, BBDC4, ABEV3).
Os dados são ajustados para incluir fins de semana/feriados (mantendo última cotação válida) e exportados para Excel.

Tratamento e Métricas
Retorno diário
Retorno acumulado
Simulação de carteira inicial (ex.: R$1000 investidos)

Visualização
Excel → Tabelas dinâmicas + gráficos mensais
Power BI → Dashboard interativo com evolução patrimonial

 Resultados Obtidos:
Comparação clara da valorização dos ativos ao longo de 2 anos.
Identificação do ativo com melhor performance e o com pior desempenho.
Criação de cenários fictícios (“Se você tivesse investido R$1000 em cada ativo...”).

 Próximos Passos
Incluir métricas de risco (ex.: volatilidade, desvio padrão).
Simular diferentes carteiras de investimento.
Implementar relatórios automatizados.

Desenvolvido por Caio Hernandes
