# 📊 Riesgo Materno: Regresión Logística Binaria

Este proyecto implementa un modelo de regresión logística binaria para predecir el **riesgo materno** a partir de variables socio-demográficas y de salud. Se basa en un conjunto de datos disponible en el [UCI Machine Learning Repository](https://archive.ics.uci.edu/), relacionado con salud materna en zonas rurales.

## 🎯 Objetivo

Desarrollar un modelo predictivo que permita clasificar a las pacientes según su nivel de riesgo (alto o bajo) utilizando variables como edad, presión arterial, nivel de hemoglobina, número de embarazos, entre otras.

## 📁 Contenido del notebook

- Exploración inicial del conjunto de datos.
- Limpieza y transformación de variables.
- Análisis exploratorio de datos (EDA).
- Ajuste del modelo de regresión logística.
- Evaluación del desempeño del modelo:
  - Matriz de confusión
  - Métricas: accuracy, precision, recall, F1-score
  - Curva ROC y AUC
- Visualización de resultados.
- Interpretación de coeficientes.

## 📚 Datos

- Dataset: *Maternal Health Risk Data Set*
- Fuente: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Maternal+Health+Risk+Data+Set)
- Variables:
  - Age
  - SystolicBP
  - DiastolicBP
  - BS (nivel de azúcar)
  - BodyTemp
  - HeartRate
  - RiskLevel (bajo, medio, alto — recodificado como binario)

## 🛠️ Tecnologías y librerías utilizadas

- Python 3.11
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

## ▶️ Cómo ejecutar

1. Clona este repositorio:
   ```bash
   git clone https://github.com/fabianbarrioss/Regresi-nLog-sticaBinaria.git
   cd Regresi-nLog-sticaBinaria
