# 📊 Telecom X – Predicción de Cancelación de Clientes (Churn)

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar un modelo predictivo capaz de anticipar la cancelación de clientes (churn) en Telecom X mediante técnicas de Machine Learning.

A partir de un dataset previamente depurado y estandarizado, se construyó un pipeline completo que abarca desde la preparación de datos hasta la evaluación comparativa de modelos de clasificación, con el fin de identificar los factores que influyen en la pérdida de clientes y proponer estrategias de retención basadas en datos.

---

## 🎯 Objetivos

- Preparar los datos para modelado (limpieza, codificación y normalización).
- Analizar correlaciones y patrones asociados al churn.
- Entrenar y comparar modelos de clasificación.
- Evaluar el rendimiento mediante métricas cuantitativas.
- Identificar variables clave que influyen en la cancelación.
- Formular recomendaciones estratégicas basadas en los resultados.

---

## ⚙️ Pipeline del Proyecto

1. **Análisis Exploratorio de Datos (EDA)**
   - Distribución del churn
   - Comparaciones por contrato, antigüedad y cargos
   - Análisis de correlación

2. **Preprocesamiento**
   - Eliminación de identificadores irrelevantes
   - One-Hot Encoding de variables categóricas
   - Normalización de variables numéricas
   - División Train/Test

3. **Modelado**
   - Regresión Logística
   - Random Forest

4. **Evaluación**
   - Accuracy
   - Precision & Recall
   - F1-score
   - ROC-AUC

5. **Interpretación**
   - Importancia de variables
   - Análisis estratégico de factores de riesgo

---

## 📈 Visualizaciones Clave

### 🔹 Antigüedad vs Cancelación

<img width="613" height="414" alt="image" src="https://github.com/user-attachments/assets/e3326a6e-fd2c-4c30-9ba9-bb55a1333d98" />


El análisis muestra que los clientes con menor antigüedad presentan mayor probabilidad de cancelar el servicio, evidenciando que el riesgo es mayor en las primeras etapas del ciclo de vida del cliente.

---

### 🔹 Curva ROC – Comparación de Modelos

<img width="551" height="413" alt="image" src="https://github.com/user-attachments/assets/b1b6f21f-5d1f-476b-b63d-65cd623e10d3" />


El modelo Random Forest demuestra mejor capacidad de discriminación frente a la Regresión Logística, reflejado en un mayor valor de ROC-AUC.

---

## 🧠 Principales Hallazgos

- Los contratos mensuales presentan mayor tasa de cancelación.
- La baja antigüedad es uno de los factores más determinantes.
- Cargos mensuales elevados aumentan el riesgo de churn.
- Clientes con servicios adicionales muestran mayor fidelidad.
- El modelo Random Forest obtuvo mejor desempeño predictivo.

---

## 🚀 Recomendaciones Estratégicas

- Implementar campañas de retención durante los primeros meses.
- Incentivar contratos de mayor duración.
- Revisar estructura de precios en planes de alto costo.
- Promover servicios adicionales como estrategia de fidelización.
- Integrar el modelo predictivo en el sistema comercial para generar alertas tempranas.

---

## 🛠️ Tecnologías Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

👤 Autor

Luis Alberto Huamaní Cahuana 📧 [albert052592@gmail.com] 📍 Proyecto de análisis y visualización de datos para el programa Oracle Next Education (ONE) - Alura LATAM.
