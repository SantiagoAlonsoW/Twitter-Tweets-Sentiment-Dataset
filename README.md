# 📊 Análisis de Sentimientos en Tweets: Del Token al Tensor

Este proyecto consiste en el desarrollo de una red neuronal para la clasificación de sentimientos en una base de datos de tweets (27,480 registros). Se aplicaron técnicas avanzadas de **Procesamiento de Lenguaje Natural (NLP)** y **Deep Learning**.

## 🚀 Resumen del Proyecto
El objetivo principal fue transformar texto crudo en representaciones numéricas capaces de alimentar una red neuronal multicapa para predecir si un tweet es **Positivo, Neutral o Negativo**.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Deep Learning:** PyTorch
* **NLP:** NLTK / spaCy
* **Vectorización:** Scikit-Learn (TF-IDF)
* **Visualización:** Matplotlib / Seaborn

## 🧠 Fases del Desarrollo

1. **Análisis Exploratorio (EDA):** Estudio de la distribución de clases y limpieza inicial de datos.
2. **Preprocesamiento:** * Normalización de texto (limpieza de URLs, menciones y puntuación).
   * Comparativa de lematización entre **NLTK** y **spaCy** (optando por NLTK por eficiencia en grandes volúmenes).
3. **Vectorización:** Implementación de **TF-IDF** con un vocabulario de 5,000 rasgos para resaltar palabras clave con carga emocional.
4. **Modelado:** * Arquitectura de Red Neuronal Profunda con capas Lineales y Dropout.
   * Optimización mediante `CrossEntropyLoss` y `Adam`.
   * Implementación de **Early Stopping** para prevenir el sobreajuste (Overfitting).

## 📈 Resultados
El modelo alcanzó un alto nivel de precisión, validado mediante una matriz de confusión y un reporte de clasificación detallado. La red demostró una capacidad robusta para diferenciar sentimientos polares (Positivo/Negativo).

## 📂 Cómo utilizar este repositorio
1. Clonar el repositorio.
2. Abrir el archivo `.ipynb` en **Google Colab**.
3. Cargar el dataset (incluido en el repositorio) y ejecutar las celdas en orden.
