# Previsão de Estoque Inteligente na AWS com SageMaker Canvas
## Visão Geral
Este projeto visa criar um modelo de previsão de tráfego de páginas usando o SageMaker Canvas. Utilizei um dataset de tráfego com 1000 dados aleatórios criados em Python para treinar e testar o modelo. O objetivo é prever quais páginas serão mais acessadas nos próximos dias.

## Pré-requisitos
Conta AWS

SageMaker Canvas

Conhecimento básico em Python e Machine Learning

## Dataset
O dataset utilizado contém informações sobre o tráfego de páginas da web e foi gerado aleatoriamente usando Python. As principais colunas do dataset são:

Data: Data da visita.

Visitas: Número de visitas registradas.

Fonte_trafego: Origem do tráfego (e.g., busca orgânica, social media).

Dia_da_semana: Dia da semana da visita.

Hora: Hora do dia da visita.

Passo a Passo

#### 1. Selecionar Dataset
Dataset Utilizado: Dataset de tráfego com 1000 dados aleatórios.
Processo: O dataset foi criado utilizando Python e contém informações sobre visitas às páginas da web.
#### 2. Construir/Treinar
Importação: O dataset foi importado para o SageMaker Canvas.

Configuração: O modelo foi configurado para prever a página mais acessada. As variáveis de entrada e saída foram configuradas conforme as colunas mais impactantes:

Data

Visitas

Fonte_trafego

Dia_da_semana

Hora

Treinamento: O treinamento do modelo foi iniciado com o dataset configurado.

#### 3. Analisar
Métricas de Desempenho: Após o treinamento, foram analisadas as métricas de desempenho do modelo para avaliar sua eficácia.
Características de Impacto: As colunas identificadas como mais impactantes foram:
Data
Visitas
Fonte_trafego
Dia_da_semana
Hora
Ajustes: Ajustes foram feitos no modelo para melhorar a precisão das previsões.
#### 4. Prever
Previsão: O modelo previu que a página 9 será a mais acessada nos próximos dias.
Análise dos Resultados: Os resultados foram exportados e analisados para confirmar a previsão.
Conclusões
O modelo demonstrou ser eficaz na previsão do tráfego de páginas, com a previsão indicando que a página 9 será a mais acessada nos próximos dias. O processo de criação e treinamento do modelo no SageMaker Canvas foi bem-sucedido e forneceu insights úteis sobre o tráfego das páginas.
