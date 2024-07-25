# Análise de Trading com Dados Fundamentalistas do InvestSite usando FinRL e Selenium
Este projeto se concentra na aplicação da biblioteca FinRL para modelagem de estratégias de trading com base em dados fundamentalistas obtidos do site InvestSite utilizando a biblioteca Selenium.

# Descrição

Neste repositório, exploramos a utilização da biblioteca FinRL para realizar análises de trading com ênfase em dados fundamentalistas coletados do site [InvestSite](https://www.investsite.com.br/). Utilizamos a biblioteca Selenium para realizar o web scraping desses dados, obtendo informações fundamentais essenciais para a análise de ações e tomada de decisões no mercado financeiro.

# Funcionalidades

Web Scraping com Selenium: Implementação de scripts Python para extrair dados fundamentalistas, como balanço patrimonial, demonstrações de resultados e indicadores financeiros do InvestSite.

Integração com FinRL: Utilização da biblioteca FinRL para modelagem preditiva e implementação de estratégias de trading baseadas nos dados fundamentalistas coletados.

Análise de Dados Fundamentalistas: Exploração e visualização dos dados obtidos do InvestSite para identificar tendências, padrões e insights relevantes para decisões de trading.

Dados Finais: Os arquivos trade_fund.rar e treino_fund.rar contêm os dados finais para utilização no modelo desenvolvido.

# Notebooks:
`[talib_ambiente_ml4t.ipynb](Finrl_reinforcement_learning/Finrl_fundamentalist_trader/talib_ambiente_ml4t.ipynb)`
   
Neste notebook, são realizadas as seguintes etapas: 
Uso da biblioteca TALib para criar características baseadas em indicadores técnicos.
Utilização das bibliotecas SHAP e Random Forest para identificar as características mais relevantes, listando-as com seus respectivos softmax.

2. Trader_reforce_learning_fundamentalista.ipynb

Neste notebook, são treinados os seguintes algoritmos de aprendizado por reforço da biblioteca Stable Baselines3:
A2C, DDPG, PPO,SAC e TD3.


3. Avaliando_fundamentalista.ipynb
   
Neste notebook, são realizadas avaliações dos algoritmos treinados utilizando:
Sã0 usados os Benchmarks de Carteira de otimização de variância média, Índice Ibovespa e o CDI.
Além disso, é utilizada a biblioteca Quantstats para avaliação.

# Observacao

Alguns dados sao muito grandes entao foi colocado no google colab:

[df_setor.csv](https://drive.google.com/drive/folders/12m2qOYl1IgM2V86C98r_9AxPPUSLJOhZ)

[dados_fun_tec.csv](https://drive.google.com/drive/folders/1-5DRxE261IGvzDC0N2Dw7BVJ1TkzRz8j)

[dados_fundamentalistas_final.csv](https://drive.google.com/drive/folders/1-5DRxE261IGvzDC0N2Dw7BVJ1TkzRz8j)
