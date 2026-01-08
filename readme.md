# 🏡 Predicción Inmobiliaria: Machine Learning vs. Deep Learning

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

## 📊 Resumen del Proyecto
Este proyecto utiliza el dataset de **Boston Housing** para predecir precios de viviendas. El enfoque principal fue realizar un análisis comparativo entre la **Regresión Lineal clásica** (Scikit-Learn) y una **Red Neuronal Artificial** (Keras/TensorFlow), demostrando cómo el Deep Learning puede capturar patrones complejos no lineales para mejorar la precisión.

---

## 🚀 Decisiones Técnicas y Optimización

Para elevar el rendimiento del modelo, apliqué estrategias avanzadas de pre-procesamiento:

* **🔍 Tratamiento de Outliers:** Identifiqué y eliminé valores atípicos (como el tope artificial de 50k en el dataset) que introducían ruido en las predicciones.
* **⚖️ Escalado de Datos:** Implementé `StandardScaler` para normalizar las magnitudes de variables tan distintas como la tasa de criminalidad y el número de habitaciones.
* **🧠 Entrenamiento Inteligente (Deep Learning):**
    * **EarlyStopping:** Para detener el entrenamiento en el punto óptimo y evitar el sobreajuste (overfitting).
    * **ReduceLROnPlateau:** Ajuste dinámico de la tasa de aprendizaje cuando el modelo se estanca en una meseta.
    * **ModelCheckpoint:** Asegurando el guardado automático de los mejores pesos obtenidos.

---

## 📈 Resultados: La diferencia del Deep Learning

El modelo de Deep Learning superó significativamente al modelo lineal en todas las métricas clave:

| Métrica | Regresión Lineal (ML) | Red Neuronal (Keras) | Impacto |
| :--- | :---: | :---: | :---: |
| **R2 Score (Precisión)** | 0.80 | **0.91** | **+11% mejor** |
| **MAE (Error Promedio)** | 2.61 | **1.87** | **-28% de error** |

---

## 🛠️ Habilidades Destacadas
* **Data Wrangling:** Limpieza y transformación de datos con Pandas.
* **Feature Engineering:** Escalado y análisis de correlación.
* **Deep Learning:** Diseño de arquitecturas de redes neuronales densas.
* **Evaluación:** Análisis de residuos y métricas de error (MSE, MAE, R2).

---

## 📧 Contacto

👤 **LinkedIn:** [linkedin.com/in/ichbinzeed](https://www.linkedin.com/in/ichbinzeed)
