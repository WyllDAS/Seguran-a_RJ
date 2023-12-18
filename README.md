# Seguran-a_RJ
Análise e Tentativa de Previsão dos Roubos no Rio de Janeiro (2003-2022)

Objetivo:

O objetivo deste projeto foi analisar o número total de roubos ocorridos na cidade do Rio de Janeiro de 2003 a 2022, utilizando dados disponíveis no portal DATARio, que disponibiliza informações abertas pela prefeitura do RJ. A análise teve como intuito determinar a viabilidade de prever esses números com base nas variáveis disponíveis (Total de roubos e ano) e a tentativa de aplicar modelos de regressão para realizar essa previsão.

Metodologia:

Coleta de Dados:

Os dados sobre o número total de roubos foram obtidos do portal DATARio, que disponibiliza conjuntos de dados abertos fornecidos pela prefeitura do Rio de Janeiro.
Análise Descritiva Inicial:

Foram conduzidas análises descritivas dos dados utilizando bibliotecas como Pandas e Seaborn em Python. O objetivo foi compreender a distribuição dos dados ao longo do tempo (de 2003 a 2022) e determinar a possível relação entre o total de roubos e o ano.
Escolha e Aplicação de Modelos de Regressão:

Com base na análise inicial, foram aplicados modelos de regressão, incluindo regressão linear e polinomial, utilizando a biblioteca Scikit-learn (sklearn) para tentar prever o número total de roubos. Entretanto, foi observado que as variáveis disponíveis não eram suficientes para prever com precisão esses números.
Avaliação e Conclusão:

Mesmo sem obter sucesso na previsão, a aplicação dos modelos de regressão serviu para evidenciar a dificuldade de prever o número total de roubos com base apenas nas variáveis disponíveis. A discrepância entre os dados reais e as previsões geradas pelos modelos foi analisada e documentada detalhadamente no arquivo do Jupyter Notebook.
Resultados e Limitações:

Os resultados obtidos destacaram a limitação de tentar prever o número total de roubos apenas com as variáveis disponíveis (Total de roubos e ano), demonstrando que esses dados podem não ser suficientes para criar um modelo de previsão preciso. As tentativas de aplicar modelos de regressão, mesmo sem sucesso, forneceram insights sobre a complexidade dos dados e a dificuldade de predição neste contexto específico.

Conclusão:

Este projeto ressaltou a importância de considerar a relevância das variáveis disponíveis e a complexidade na criação de modelos de previsão precisos. A discrepância entre os dados reais e as previsões geradas pelos modelos de regressão evidenciou a necessidade de explorar e incluir mais variáveis ou utilizar abordagens mais sofisticadas para a previsão dos roubos na cidade do Rio de Janeiro.

Referências:

DATARio: [(https://www.data.rio/)]
Pandas: [https://pandas.pydata.org/]
Seaborn: [https://seaborn.pydata.org/]
Scikit-learn: [https://scikit-learn.org/stable/]
Numpy: [https://numpy.org/pt/]
Matplotlib [https://matplotlib.org/]
