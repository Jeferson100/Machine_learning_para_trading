# Reinforcement Learning para Trading

Este projeto é uma exploração de técnicas de Reinforcement Learning (Aprendizado por Reforço) aplicadas ao mundo do trading. Utiliza algoritmos de aprendizado de máquina, especificamente os algoritmos A2C (Advantage Actor-Critic), PPO (Proximal Policy Optimization) e DQN (Deep Q-Network) da biblioteca `stable_baselines3`. O objetivo é desenvolver estratégias de negociação automatizadas e otimizadas por meio do treinamento de agentes de RL.

## Algoritmos

- A2C (Advantage Actor-Critic)
- PPO (Proximal Policy Optimization)
- DQN (Deep Q-Network)

## Variáveis Preditivas

Para a construção de modelos preditivos, o projeto utiliza uma variedade de variáveis preditivas calculadas a partir dos dados de mercado. Algumas dessas variáveis incluem:

- Lags (atrasos): As últimas observações dos preços de fechamento são utilizadas como entradas para os modelos.
- RSI (Relative Strength Index): Índice de Força Relativa calculado com janelas de 10 e 100 períodos.
- SMA (Simple Moving Average): Média Móvel Simples dos preços de fechamento.
- OBV (On-Balance Volume): Volume em equilíbrio calculado a partir dos preços de fechamento.
- VWAP (Volume Weighted Average Price): Preço Médio Ponderado pelo Volume.
- EMA (Exponential Moving Average): Média Móvel Exponencial dos preços de fechamento.
- ATR (Average True Range): Média da Amplitude Real calculada a partir dos preços de mercado.
- MACD (Moving Average Convergence Divergence): Indicador de Convergência e Divergência de Médias Móveis.
- Ano, Mês e Dia da Semana: Variáveis de data para análise temporal.

## Gym AnyTrading

Este projeto também faz uso do ambiente de treinamento do Gym AnyTrading, que fornece um ambiente de simulação para treinar agentes de Reinforcement Learning em tarefas relacionadas ao trading. Você pode encontrar mais informações sobre o Gym AnyTrading [aqui](https://github.com/AminHP/gym-anytrading).

Sinta-se à vontade para explorar o código-fonte, experimentar com diferentes configurações e algoritmos de RL, e contribuir para o desenvolvimento de estratégias de negociação automatizadas mais eficazes.

