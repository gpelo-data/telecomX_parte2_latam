# Telecom X - Parte 2: Predicción de Churn

Este repositorio contiene la segunda parte del proyecto **Telecom X**, enfocado en el análisis y predicción de la cancelación de clientes (churn) mediante técnicas de Machine Learning.

## 🚀 Objetivo del Proyecto

El principal objetivo es identificar los factores clave que influyen en la decisión de los clientes de abandonar el servicio y construir un modelo predictivo capaz de anticipar estos casos para implementar estrategias de retención efectivas.

## 🛠️ Tecnologías Utilizadas

*   **Lenguaje:** Python
*   **Análisis de Datos:** Pandas, NumPy
*   **Visualización:** Matplotlib, Seaborn
*   **Machine Learning:** Scikit-learn (RandomForestClassifier)

## 📊 Estructura del Proyecto

*   `notebooks/telecomX_ml.ipynb`: Notebook principal con todo el flujo de trabajo (EDA, Preprocesamiento, Modelado y Evaluación).
*   `data/raw/df_telecom.csv`: Dataset original utilizado para el entrenamiento.

## 📈 Metodología y Resultados

### 1. Preprocesamiento de Datos
*   Eliminación de variables no informativas (`customer_id`).
*   Transformación de variables categóricas mediante **One-Hot Encoding**.
*   División del dataset en conjuntos de entrenamiento (80%) y prueba (20%).

### 2. Modelo Predictivo
Se utilizó un modelo de **Random Forest Classifier** con los siguientes resultados en el conjunto de prueba:

| Métrica | Resultado |
| :--- | :--- |
| **Accuracy** | 79.56% |
| **Precisión** | 78.33% |
| **Recall** | 79.56% |
| **F1-Score** | 78.45% |

### 3. Factores más Influyentes (Feature Importance)
Las variables que más impacto tuvieron en la predicción del churn fueron:
1.  **Total Charges:** 15.1%
2.  **Tenure (Antigüedad):** 14.3%
3.  **Monthly Charges:** 10.6%
4.  **Contract (Month-to-month):** 10.5%
5.  **Cuentas Diarias:** 10.1%

## 💡 Conclusiones y Recomendaciones

El análisis reveló que los clientes con menor antigüedad, cargos mensuales elevados y contratos mes a mes son los más propensos a cancelar el servicio. Como estrategias de negocio se sugieren:
*   Incentivar la transición a contratos de largo plazo (1 o 2 años).
*   Implementar planes de fidelización para clientes nuevos durante sus primeros meses.
*   Fomentar métodos de pago automáticos para reducir la fricción en la facturación.

## 👤 Contacto / Redes

*   **GitHub:** [gpelo-data](https://github.com/gpelo-data)
*   **LinkedIn:** [gpelo-data](https://www.linkedin.com/in/gpelo-data)

---
*Proyecto realizado como parte del desafío Telecom X.*