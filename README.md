# Beta Bank — Customer Churn Prediction

## English

### Problem
Beta Bank customers are leaving little by little, every month. The bank found it's cheaper to save existing customers rather than to attract new ones. This project builds a classification model that predicts whether a customer will leave the bank soon, based on their transactional and demographic data.

### Approach
- Performed exploratory data analysis and identified class imbalance in the target variable (customers who churned vs. those who stayed).
- Addressed the imbalance using class weighting and upsampling techniques before model training.
- Trained and tuned a Random Forest Classifier, evaluating hyperparameters (`n_estimators`, `max_depth`) via cross-validation.
- Evaluated the final model using F1-score (the project's target metric) and AUC-ROC as a complementary measure of overall discrimination.

### Results
- **F1-score: 0.60** (exceeding the project's minimum threshold of 0.59)
- **AUC-ROC: 0.856**

### Stack
Python | pandas | scikit-learn | matplotlib | Jupyter Notebook

---

## Español

### Problema
Los clientes de Beta Bank se están yendo poco a poco, cada mes. El banco descubrió que resulta más barato retener a los clientes existentes que atraer nuevos. Este proyecto construye un modelo de clasificación que predice si un cliente abandonará el banco pronto, basado en sus datos transaccionales y demográficos.

### Enfoque
- Se realizó un análisis exploratorio de datos y se identificó un desbalance de clases en la variable objetivo (clientes que se fueron vs. los que permanecieron).
- Se abordó el desbalance mediante ponderación de clases y técnicas de sobremuestreo (upsampling) antes de entrenar el modelo.
- Se entrenó y ajustó un Random Forest Classifier, evaluando hiperparámetros (`n_estimators`, `max_depth`) mediante validación cruzada.
- Se evaluó el modelo final usando F1-score (la métrica objetivo del proyecto) y AUC-ROC como medida complementaria de la capacidad de discriminación general.

### Resultados
- **F1-score: 0.60** (superando el umbral mínimo del proyecto de 0.59)
- **AUC-ROC: 0.856**

### Stack
Python | pandas | scikit-learn | matplotlib | Jupyter Notebook

---

**Santiago Quintanilla** — Mechatronics Engineer | Data Science Student @ TripleTen
LinkedIn: https://www.linkedin.com/in/santiago-quintanilla-zurita
GitHub: https://github.com/borre3205
