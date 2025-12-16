# 🚨 Modelo de Detección de Fraude en E-commerce

Proyecto end to end de **Machine Learning** orientado a la detección y prevención de fraude en un contexto de comercio electrónico.  
El trabajo está inspirado en una prueba técnica real y cubre todo el ciclo de vida de un modelo: desde la transformación de datos hasta su despliegue y consumo mediante una interfaz gráfica.

---

## 🎯 Objetivo

Construir un modelo de clasificación basado en **Random Forest** para predecir comportamientos fraudulentos a partir de perfiles de clientes ficticios de una empresa de e-commerce, utilizando datos en formato JSON.

El modelo devuelve una de las siguientes predicciones:
- **No**
- **Sí**
- **Warning**

---

## 📊 Dataset

El dataset contiene perfiles de clientes en formato **JSON**, incluyendo información sobre:
- Órdenes
- Transacciones
- Métodos de pago
- Datos del cliente
- Etiqueta de fraude

Este formato es común en procesos de **ETL**, donde los datos suelen obtenerse directamente desde APIs.

---

## 🔄 Proceso

1. **Transformación de datos**
   - Conversión de JSON a CSV
   - Limpieza y adaptación de variables
   - Tratamiento de valores poco frecuentes

2. **Análisis Exploratorio (EDA)**
   - Análisis univariado y bivariado
   - Correlaciones e identificación de patrones relevantes

3. **Preparación de datos**
   - Discretización de variables
   - Manejo de valores faltantes
   - Normalización y selección de features

4. **Modelado**
   - Clustering con **K-Means** y **HDBSCAN**
   - Clasificación con **Random Forest**
   - Evaluación mediante matriz de confusión
   - Tracking de experimentos con **MLflow**

5. **Despliegue**
   - API desarrollada con **FastAPI**
   - Contenerización con **Docker**
   - Interfaz gráfica con **Gradio**, desplegada en **Hugging Face Spaces**

---

## 🛠️ Tecnologías Utilizadas

- **Python**
- Pandas, NumPy
- Scikit-learn
- HDBSCAN
- MLflow
- FastAPI
- Docker
- Gradio
- Hugging Face Spaces

---


