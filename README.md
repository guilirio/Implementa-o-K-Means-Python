# Trabalho Prático 02 - K-Means 🤖

**Disciplina:** GCC 128 - Inteligência Artificial  
**Instituição:** Universidade Federal de Lavras (UFLA)  
**Professor:** Ahmed Ali Abdalla Esmin  

## 👥 Integrantes
* Arthur Soares Marques
* Guilherme Lirio Miranda

---

## 🎯 Objetivo do Projeto
Este projeto consiste no desenvolvimento de uma aplicação de aprendizado não supervisionado utilizando o algoritmo K-Means para agrupar (clustering) dados. O objetivo é compreender, na prática, como o algoritmo forma os grupos e como a escolha do número de clusters (K) afeta o resultado final. O trabalho foi aplicado sobre a base de dados Iris.

## 🚀 Etapas Implementadas
O desenvolvimento do algoritmo seguiu os seguintes passos estruturados:
* **Pré-processamento:** Remoção de rótulos prévios e padronização dos atributos contínuos utilizando Z-Scoring.
* **Definição do K ótimo:** Aplicação do Método do Cotovelo (Elbow Method) e cálculo da Inércia (WCSS) para justificar a escolha da quantidade de clusters.
* **Avaliação do Agrupamento:** Avaliação da qualidade e coesão dos clusters gerados utilizando a métrica *Silhouette Score*.
* **Visualização de Dados:** Utilização da técnica PCA (Análise de Componentes Principais) para redução de dimensionalidade e plotagem gráfica dos grupos.

## 🛠️ Tecnologias e Bibliotecas Utilizadas
* **Linguagem:** Python
* **Ambiente:** Jupyter Notebook
* **Bibliotecas:** Pandas, NumPy, Matplotlib e Scikit-learn

## 📂 Estrutura e Execução
1. Certifique-se de ter as bibliotecas acima instaladas no seu ambiente Python.
2. Mantenha a base de dados `Iris.csv` no mesmo diretório do arquivo executável.
3. Execute as células do notebook sequencialmente para reproduzir a limpeza, o treinamento, as métricas e a visualização gráfica.
