# 🎬 Projeto - CRIANDO UM SISTEMA DE RECOMENDAÇÃO DE FILMES
by Victor Tintel
🌟 Visão Geral
Este projeto implementa um sistema de recomendação de filmes utilizando técnicas de Machine Learning, similar aos algoritmos usados por plataformas como Netflix e Spotify. O sistema pode ser adaptado para recomendar outros produtos como músicas, livros ou itens de e-commerce.

Tecnologias utilizadas:

- Python (Pandas, NumPy, Scikit-learn)

- Algoritmo KNN (K-Nearest Neighbors)

- Processamento e análise de dados

📌 Principais Etapas do Projeto
1️⃣ Coleta e Pré-processamento de Dados:
- Carregamento e limpeza do dataset (movies.csv, ratings.csv).

- Tratamento de valores ausentes (missing values).

- Engenharia de features para análise.

2️⃣ Análise Exploratória (EDA):
- Visualização da distribuição de avaliações.

- Correlação entre gêneros de filmes.

- Popularidade de filmes por ano.

3️⃣ Construção do Sistema de Recomendação:
- Filtro baseado em conteúdo (Content-Based Filtering):

- Utiliza similaridade de gêneros/diretores.

- Filtro colaborativo (Collaborative Filtering - KNN):

- Recomenda filmes com base nas avaliações de usuários similares.

4️⃣ Avaliação do Modelo:
- Métricas de desempenho (RMSE, precisão nas recomendações).

- Testes com diferentes valores de k no KNN.

5️⃣ Interface de Recomendação:
- Função que recebe um filme e retorna sugestões similares.

🛠️ Como Executar o Projeto?
- Pré-requisitos
- Python 3.8+

Bibliotecas: pandas, numpy, scikit-learn, matplotlib
