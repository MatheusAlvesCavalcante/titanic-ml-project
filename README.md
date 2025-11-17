#  Titanic Survival Prediction – Machine Learning Project

Este repositório contém meu projeto completo de Machine Learning usando o famoso dataset **Titanic – Machine Learning from Disaster** do Kaggle.

O objetivo foi criar um pipeline de ML capaz de prever quais passageiros sobreviveram ao naufrágio, utilizando técnicas modernas de pré-processamento, análise exploratória e modelos de classificação.

---

##  Estrutura do Projeto

* **titanic.ipynb / titanic.py** – Código completo do projeto, incluindo:

  * Limpeza e tratamento de dados
  * Análise exploratória (EDA)
  * Engenharia de atributos
  * Codificação de variáveis categóricas
  * Testes com diversos modelos (RandomForest, GradientBoosting, CatBoost, Logistic Regression etc.)
  * GridSearchCV para ajuste automático de hiperparâmetros
  * Geração do arquivo final de submissão

* **submission.csv** – Arquivo final gerado pelo modelo, pronto para envio ao Kaggle.

---

##  Técnicas e Modelos Utilizados

* **Pré-processamento**:

  * Tratamento de valores faltantes (Age, Fare, Cabin, Embarked)
  * Transformação de variáveis categóricas
  * Criação de novas features

* **Modelos de Machine Learning**:

  * Logistic Regression
  * RandomForestClassifier
  * GradientBoostingClassifier
  * CatBoostClassifier
  * KNN, Naive Bayes, Decision Tree, SVM

* **Validação e Ajuste**:

  * Divisão Train/Test
  * Cross-validation (k-fold)
  * GridSearchCV

---

##  Resultados

* Pipeline completo construído do zero
* Comparação de diversos modelos
* Modelo final treinado e exportado para submissão
* Submissão gerada com todos os requisitos do Kaggle

---

##  Como Executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
   ```
2. Instale as dependências (se necessário):

   ```bash
   pip install -r requirements.txt
   ```
3. Execute o notebook ou o arquivo Python:

   ```bash
   python titanic.py
   ```

---

##  Dependências Principais

* Python 3.x
* Pandas
* NumPy
* Scikit-Learn
* CatBoost
* Seaborn / Matplotlib

---

##  Sobre o Projeto

Este projeto foi desenvolvido para fins de estudo e prática de modelagem supervisionada. O Titanic é um dos datasets mais usados em competições e cursos de Data Science.

Ele demonstra:

* raciocínio analítico
* domínio de bibliotecas de ML
* capacidade de transformar dados brutos em previsões reais
* organização de workflow de Data Science

---


