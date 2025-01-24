# Preveja-os-usuarios-com-alta-chance-de-deixar-seu-Streaming
## Desafio 6 - Formação Cientista de Dados - DNC
Sugestão de Texto README para o GitHub
## Desafio 6 - Formação Cientista de Dados - DNC

Objetivo:

Desenvolver um modelo de classificação capaz de prever a churn (cancelamento) de assinaturas em uma plataforma de streaming. A partir de um dataset que contém informações sobre as contas dos clientes, o objetivo é identificar os fatores que mais influenciam na decisão de cancelar a assinatura.

Dataset:

Os dados fornecidos possuem informações sobre as contas dos clientes na plataforma de streaming, divididos entre contas Basic, Standard e Premium, onde cada uma oferece uma gama maior de serviços que a anterior.
Etapas:

Análise Exploratória:

Carregamento do dataset.
Descrição estatística dos dados (média, mediana, desvio padrão, etc.).
Verificação dos tipos de dados (numéricos, categóricos).
Identificação de valores faltantes.
Tratamento de Dados:

Imputação de valores faltantes (substituição por 0 em colunas específicas).
Remoção de linhas com valores nulos em colunas relevantes.
Transformação de valores (churn, tipos numéricos).
Modelagem - Regressão Logística:

Definição das variáveis independentes (X) e dependente (y).
Ajustamento do modelo à base de dados de treino.
Divisão dos dados em treino e teste.
Avaliação do modelo (matriz de confusão, métricas).
Modelagem - Tunagem:

Pré-processamento de variáveis categóricas.
Divisão dos dados em treino e teste.
Treinamento do modelo.
Realização de predições.
Avaliação do modelo.
Modelagem - Random Forest:

Configuração do grid search.
Ajustamento do modelo à base de dados de treino.
Tunagem dos hiperparâmetros.
Avaliação do modelo (matriz de confusão, métricas).
Conclusão:

Após a aplicação dos modelos de Regressão Logística e Random Forest, observou-se que o Random Forest apresentou o melhor desempenho na tarefa de predição de churn.
