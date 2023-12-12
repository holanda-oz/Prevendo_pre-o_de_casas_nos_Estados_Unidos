Resumo do Projeto:

Objetivo: Prever os preços futuros de casas usando dados do Federal Reserve, juntamente com dados de preços de casas da Zillow. O projeto envolve a fusão e combinação desses dados, seguida pelo treinamento de um modelo de Random Forest. O modelo prevê se os preços das casas aumentam ou diminuem no futuro. A avaliação do modelo será feita usando backtesting, e serão feitos aprimoramentos com novos dados e métricas de Machine Learning.

Personalização: Este projeto pode ser adaptado para prever os preços das casas em sua área metropolitana, caso você esteja nos EUA.

Passos do Projeto:

Carregar os dados: Importar os conjuntos de dados necessários.
Limpar e mesclar os dados: Realizar a limpeza e fusão dos dados.
Criar um modelo inicial de machine learning e estimar a precisão: Desenvolver um modelo inicial e avaliar sua precisão.
Aprimorar a precisão do modelo: Fazer melhorias no modelo.
Executar diagnósticos: Analisar diagnósticos para identificar maneiras de melhorar ainda mais.
Código: O código para o projeto pode ser encontrado no arquivo prices.ipynb, que é um notebook Jupyter contendo todo o código.
Configuração Local:

Instalação:
Para seguir este projeto, instale localmente:

JupyterLab
Python 3.8+
Pacotes Python: pandas, yfinance, scikit-learn
Dados:
Faça o download de alguns arquivos CSV para executar este projeto. Esses arquivos estão incluídos no repositório. Se você deseja obter versões mais recentes:

Dados do Federal Reserve:

Dados de inflação dos Estados Unidos (inflacao.csv)
Taxa de vacância para aluguel (casas_vagas.csv)
Taxas de juros de hipoteca hipoteca.csv)
Dados da Zillow:

ZHVI (bruto, semanal) - data_1.csv
Preço médio de venda (bruto, todas as casas, semanal) - data_2.csv




