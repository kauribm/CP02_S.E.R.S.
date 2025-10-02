# Datasets - Parte 01:

Este repositório reúne fluxos de trabalho no **Orange Data Mining** e um **notebook em Python** para análise de dados de energias renováveis.  
O objetivo é demonstrar técnicas de **classificação** (solar) e **regressão** (eólica) aplicadas a datasets reais.

---

## 📂 Arquivos incluídos
- **energias_renovaveis_notebook.ipynb** → Notebook em Python (Jupyter/Colab) com exploração dos dados, gráficos e modelos de Machine Learning.  
- **classificacao_solar.ows** → Fluxo Orange para **classificação da radiação solar**.  
- **regressao_eolica.ows** → Fluxo Orange para **regressão da potência eólica**.  

---

## ⚙️ Modelos Utilizados
### Classificação Solar
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  

### Regressão Eólica
- Regressão Linear  
- Árvore de Regressão  
- Random Forest  

---

## 📊 Saídas e Avaliações
- **No Notebook (Python):** gráficos exploratórios, matriz de confusão, curva ROC, métricas de regressão (MAE, RMSE).  
- **No Orange:** comparação de modelos, tabelas de desempenho e visualizações automáticas.  

---

## 🚀 Como usar
### Opção 1: Notebook
1. Abra o `energias_renovaveis_notebook.ipynb` no **Jupyter Notebook** ou **Google Colab**.  
2. Ajuste os caminhos para os datasets (baixe do Kaggle ou outras fontes públicas).  
3. Execute célula por célula para reproduzir os experimentos.  

### Opção 2: Orange
1. Abra o **Orange Data Mining**.  
2. Vá em **File → Open** e carregue `classificacao_solar.ows` ou `regressao_eolica.ows`.  
3. Conecte seus próprios dados (solar ou eólico).  
4. Execute o fluxo e visualize os resultados.  

---

## 🔋 Objetivo
Este projeto demonstra como técnicas de **mineração de dados e aprendizado de máquina** podem apoiar previsões e análises no setor de **energias renováveis**.

---

# Datasets - Parte 02:
Acesse o notebook aqui: [SERS_Exercicios.ipynb](SERS_Exercicios.ipynb)
---

## ⚡ Exercício 1 – Classificação (Solar)

**Título:** Previsão de nível de radiação solar  
**Dataset:** [Solar Radiation Prediction Dataset – Kaggle](https://www.kaggle.com/datasets/dronio/SolarEnergy)

### Objetivos
- Criar variável-alvo (Alta vs Baixa radiação, usando a mediana como limiar).  
- Treinar os modelos:  
  - Decision Tree  
  - Random Forest  
  - SVM  
- Avaliar com **Acurácia e Matriz de Confusão**.

---

## 🌬️ Exercício 2 – Regressão (Eólica)

**Título:** Previsão de potência de turbinas eólicas  
**Dataset:** [Wind Turbine Scada Dataset – Kaggle](https://www.kaggle.com/datasets/berkerisen/wind-turbine-scada-dataset)

### Objetivos
- Prever a potência (kW) a partir de variáveis operacionais (velocidade do vento, ângulo do rotor, densidade do ar, etc).  
- Treinar os modelos:  
  - Regressão Linear  
  - Árvore de Regressão  
  - Random Forest Regressor  
- Avaliar com **RMSE e R²**.

 ---
 
## Integrantes
- Nelson Troccoli Santos Neto (RM562815)
- Guilherme Willians de Souza Inácio (RM565319)
- Isabella Piñeiro Santana (RM562779)
- Kauã da Silva Lazarim (RM564625) 
- Kauany Ribeiro de Moura (RM564576)
