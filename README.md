# 📊 Optimización del Customer Lifetime Value (LTV)

## 🎯 Objetivo

Desarrollar un modelo de Machine Learning que permita predecir el Customer Lifetime Value (LTV) de los clientes, con el fin de optimizar estrategias comerciales y de marketing.

## 📂 Dataset

El dataset utilizado corresponde al sector seguros y contiene 9.134 registros con 24 variables, incluyendo información demográfica, comportamiento del cliente y características de las pólizas.

## 🧠 Metodología

Se aplicó la metodología CRISP-DM, siguiendo las siguientes etapas:

* Análisis exploratorio de datos (EDA)
* Limpieza y preparación de datos
* Feature engineering
* Modelado y evaluación

## 📊 Análisis Exploratorio (EDA)

Se identificaron los siguientes hallazgos:

* El LTV presenta una distribución sesgada
* Un pequeño grupo de clientes concentra alto valor
* Existe relación positiva entre LTV y la prima mensual
* Variables como ingresos no presentan fuerte relación con el LTV

## 🤖 Modelos utilizados

Se implementaron y compararon los siguientes modelos:

* Regresión Lineal
* Árbol de Decisión
* Random Forest

## 📈 Resultados

El modelo Random Forest obtuvo el mejor desempeño:

* R² ≈ 0.68
* Menor error (RMSE)

Esto indica una mejor capacidad para capturar relaciones no lineales en los datos.

## 💼 Impacto de negocio

El modelo permite:

* Identificar clientes de alto valor
* Optimizar la inversión en marketing
* Comparar LTV vs CAC
* Mejorar la rentabilidad y el ROI

## ▶️ Cómo ejecutar

1. Descargar el notebook
2. Cargar el dataset
3. Ejecutar las celdas en orden

---

Proyecto realizado como parte de la Diplomatura en Ciencia de Datos.
