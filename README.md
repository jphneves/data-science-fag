# Projeto de Machine Learning: Previsão de Doenças Cardíacas

Trabalho Ciencia dos Dados - FAG sobre aplicação de algoritmos de machine learning para previsão de doenças cardíacas. O projeto utiliza um dataset de doenças cardíacas para treinar e comparar modelos de classificação, incluindo Random Forest e SVM (Support Vector Machine), além de uma análise de clustering com K-Means.

## Estrutura do Repositório

- `MachineLearningDoencasCardiacas2.ipynb`: Notebook Jupyter com o código completo do projeto, incluindo carregamento de dados, pré-processamento, treinamento de modelos, avaliação e visualizações.
- `dados_doencas_cardiacas.csv`: Base de dados utilizada no projeto (dataset de doenças cardíacas).
- `README.md`: Este arquivo com instruções do projeto.
- `perfis_clusters_k_means.png`: Gráfico salvo do perfil dos clusters (gerado pelo notebook).

## Requisitos do Sistema

- Python 3.8 ou superior
- Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learn, joblib

## Como Executar o Projeto

1. Clone este repositório:
   ```
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Instale as dependências:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn joblib
   ```

3. Abra o notebook no Jupyter:
   ```
   jupyter notebook MachineLearningDoencasCardiacas2.ipynb
   ```

4. Execute todas as células do notebook para reproduzir os resultados.

## Algoritmos Utilizados

- **Random Forest**: Algoritmo de ensemble para classificação, com análise de importância das variáveis.
- **SVM (Support Vector Machine)**: Algoritmo de classificação baseado em margens.
- **Comparação**: Métricas de acurácia e AUC-ROC entre os dois modelos.
- **Clustering K-Means**: Análise não supervisionada para agrupamento dos dados.

## Resultados

- Random Forest: Acurácia 79.28%, AUC-ROC 0.489
- SVM: Acurácia 79.28%, AUC-ROC 0.529
- Detalhes completos no notebook.

## Referências

- Dataset: Heart Disease Dataset (https://www.kaggle.com/datasets/oktayrdeki/heart-disease).
- Bibliotecas: Scikit-learn, Pandas, etc.

## Alunos

- Joao Pedro H Neves, Davi Fiori, Diego Kotz, Igor Rosa