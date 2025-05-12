# Minicurso: Introdução à Ciência de Dados com Python – Caso de Uso “Diabetes”

## Descrição:
Neste minicurso prático de 4 horas, você aprenderá o pipeline completo de um projeto de Ciência de Dados usando Python, tendo como estudo de caso a previsão de diabetes a partir do famoso conjunto de dados Pima Indians Diabetes (2000–2023).

## Conteúdo Programático:

### Preparação e Exploração de Dados

Importação do CSV diretamente do GitHub com pandas

Inspeção inicial (.head(), .info(), .describe())

Tratamento de valores zero como ausentes em colunas críticas

Filtragem e agregação para insights rápidos (médias por Outcome)

### Visualização e Análise

Histogramas e boxplots de todas as variáveis (matplotlib, seaborn)

Heatmap de correlação para entender relacionamentos entre features

Density plot de glicose por classe e count plot de Outcome

### Modelagem Preditiva com KNN

Separação em treino e teste (70/30)

Normalização de features com StandardScaler

Construção e treinamento de um KNeighborsClassifier

Avaliação de performance: acurácia, matriz de confusão e report

### Deploy Interativo

Criação de prompt em console para entrada de novos pacientes

Normalização “on-the-fly” e predição em tempo real

### Bibliotecas Utilizadas:

pandas, numpy

matplotlib, seaborn

scikit-learn (KNN, StandardScaler, train_test_split, métricas)

warnings para silenciar alertas irrelevantes

## Público-Alvo:
Profissionais e estudantes de TI, Estatística, Engenharia e áreas afins que queiram dominar, do começo ao fim, um workflow de Ciência de Dados em Python, incluindo EDA, visualizações, modelagem e deploy simples.

## Resultados Esperados:

Saber conduzir análises exploratórias detalhadas e criar visualizações informativas

Dominar a preparação de dados e normalização para algoritmos de Machine Learning

Implementar, avaliar e ajustar um modelo preditivo de classificação

Construir uma interface de linha de comando para tornar o modelo acessível a usuários finais

