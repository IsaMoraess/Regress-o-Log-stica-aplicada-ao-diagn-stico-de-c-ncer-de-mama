# Regressão Logística para Classificação de Câncer de Mama

Este repositório contém um projeto de Machine Learning que utiliza o algoritmo de **Regressão Logística** para classificar tumores como malignos (M) ou benignos (B) com base em dados de biópsia.

---

### **Tecnologias e Bibliotecas**

* **Python:** Linguagem de programação principal.
* **Pandas:** Usado para manipulação e análise dos dados.
* **Scikit-learn:** Biblioteca de aprendizado de máquina para construir e treinar o modelo de Regressão Logística.
* **mlxtend:** Utilizado para visualização da matriz de confusão.

---

### **Sobre o Projeto**

O projeto segue as seguintes etapas:

1.  **Carregamento dos Dados:** O conjunto de dados `breast-cancer.csv` é lido usando Pandas.
2.  **Preparação dos Dados:** Os dados são divididos em conjuntos de treino e teste.
3.  **Treinamento do Modelo:** Uma instância do modelo de Regressão Logística é criada e treinada com os dados de treino.
4.  **Avaliação:** O modelo é avaliado usando uma matriz de confusão e um relatório de classificação para verificar sua precisão, recall e F1-score.

📊 Resultados do Modelo

O modelo de Regressão Logística foi avaliado utilizando métricas de classificação no conjunto de teste, obtendo os seguintes resultados:

Acurácia geral: 97%
Classe Benigna (B): Precisão = 97%, Recall = 98%, F1-score = 97%
Classe Maligna (M): Precisão = 96%, Recall = 94%, F1-score = 95%
Esses resultados demonstram que o modelo possui alto desempenho na tarefa de diagnóstico de câncer de mama, apresentando equilíbrio entre as métricas de precisão e recall para ambas as classes.

---

### **Como Executar o Notebook**

Para executar este projeto localmente, siga os passos abaixo:

1.  Certifique-se de ter o [Jupyter Notebook](https://jupyter.org/) e as bibliotecas necessárias instaladas.
2.  Instale as bibliotecas que podem estar faltando:
    ```bash
    pip install pandas scikit-learn mlxtend
    ```
3.  Faça o download ou clone este repositório.
4.  Abra o Jupyter Notebook na pasta do projeto e execute o arquivo `RegressaoLogistica.ipynb`.

---

### **Resultados**

Os resultados do modelo, incluindo a matriz de confusão e o relatório de classificação, estão visíveis no próprio notebook. A matriz de confusão ajuda a visualizar o desempenho do modelo, enquanto o relatório detalha as métricas de precisão, recall e F1-score para cada classe.
