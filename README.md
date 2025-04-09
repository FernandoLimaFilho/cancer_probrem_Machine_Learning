# 🧬 Classificação de Câncer de Mama com Machine Learning

Este projeto aplica algoritmos de **aprendizado de máquina supervisionado** para classificar tumores mamários como **benignos ou malignos**, utilizando o dataset real `breast_cancer` da biblioteca `scikit-learn`.

---

## 📌 Objetivos

- 🔍 Selecionar features mais relevantes para o diagnóstico.
- ⚙️ Treinar e comparar diferentes algoritmos de ML.
- 📊 Avaliar desempenho usando métricas como acurácia e curva ROC.
- 🧪 Testar o modelo com novos dados manuais e reais.

---

## 🧠 Features Selecionadas

Foram utilizadas **apenas 5 variáveis** entre as 30 disponíveis no dataset original:

- `mean radius`
- `mean concave points`
- `mean concavity`
- `worst perimeter`
- `worst concave points`

Essas features apresentam forte correlação com o diagnóstico clínico.

---

## 🤖 Algoritmos Utilizados

- ✅ Logistic Regression  
- 📉 Linear Regression (comparativo)  
- 🌲 Random Forest Classifier  
- 📍 K-Nearest Neighbors (KNN)  
- 🧭 Support Vector Machine (SVC)  
- 🧪 Naive Bayes (GaussianNB)

---

## 📈 Avaliação dos Modelos

- 📌 Acurácia  
- 🧮 Matriz de confusão  
- 📉 Curva ROC (Receiver Operating Characteristic)

---

## ⚠️ Observações

Durante os testes, foi observada uma queda de performance (de ~96% para ~50%) nos modelos de regressão logística e KNN. Isso evidenciou um possível **overfitting** de tais modelos. O experimento reforça a importância de:

- 🔁 Validação cruzada  
- 📦 Balanceamento das classes  
- 📐 Seleção e padronização de features
