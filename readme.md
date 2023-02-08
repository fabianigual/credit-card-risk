# Detección de Fraude de Tarjetas de Crédito

Este repositorio contiene una solución para el problema de detección de fraude de tarjetas de crédito usando un dataset anonimizado de Kaggle (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).  Para el balanceo de datos se utlizó SMOTE,  y los modelos considerados son  regresión lógistica, random forest, SVC y XGboost. 

## Modelos

| **Modelo**  | **F1 Score** | **ROC AUC Score** |  
|-|-|-|
| Regresión lógistica | 0.97 |  96.49%|  
| Random Forest | 0.97 | 96.39%|  
| SVC | 0.98 | 96.80% |  
| XGBoost | 0.99| 98.53%|

XGBoost fue el que obtuvo los mejores resultados con un F1 Score de 0.99 y un ROC_AUC Score de 98,53%.

