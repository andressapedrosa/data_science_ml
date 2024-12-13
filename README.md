# Previsão da Expectativa de Vida

Bem-vindo ao repositório **Data Science & Machine Learning**! Este repositório tem como destaque o notebook **Previsão da Expectativa de Vida**, que aplica técnicas de aprendizado de máquina para prever a expectativa de vida de populações com base em indicadores socioeconômicos e de saúde.

---

## 📋 Visão Geral
O objetivo principal deste projeto é explorar modelos de regressão para realizar previsões precisas sobre a expectativa de vida, utilizando dados históricos de vários países. O notebook aborda as etapas de:

1. Análise exploratória de dados (EDA);
2. Pré Processamento dos dados;
3. Treinamento de modelos de regressão;
4. Avaliação do desempenho dos modelos.

---

## 📂 Estrutura do Repositório
- **`Previsao_Expectativa_Vida.ipynb`**: O notebook principal do projeto, contendo todas as etapas descritas acima.
- **`Life_Expectancy_Data.csv`**: Conjunto de dados utilizado no projeto.

---

## 🚀 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/andressapedrosa/data_science_ml.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd data_science_ml
   ```
3. Abra o notebook no Jupyter Notebook ou Google Colab:
   ```bash
   jupyter notebook Previsao_Expectativa_Vida.ipynb
   ```

---

## 🔧 Tecnologias Utilizadas
- **Linguagens:** Python
- **Bibliotecas:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Ferramentas:** Google Colab

---

## 📊 Principais Resultados
- **Modelos de regressão utilizados:**
  - Regressão Linear
  - Random Forest Regressor
  - Ridge
  - Lasso
  - KNN
  - CART
  - SVM
- **Métrica de avaliação:**
  - Negative Mean Absolute Error (Negative MAE)

Os resultados do melhor modelo indicam que Random Forest Regressor apresenta o melhor desempenho:

| Modelo | Configuração | Negative MAE |
|--------|--------------|--------------|
| Random Forest | Dataset original e hiperparâmetros default | -1,142 |
| Random Forest | Dataset normalizado e hiperparâmetros alterados | -1,246 |
| Random Forest | Dataset padronizado e hiperparâmetros default | -1,296 |
