# 🧠 Detección de Phishing con Redes Neuronales Artificiales  

Este proyecto implementa una **Red Neuronal Artificial (ANN)** para detectar sitios de phishing a partir de un dataset con características relacionadas al comportamiento y estructura de los sitios web.  

## 🔍 Objetivos del Proyecto  
- Identificar patrones clave en sitios de phishing.  
- Construir y entrenar un modelo de ANN con **Keras** para clasificar sitios web como phishing o no phishing.  
- Evaluar el rendimiento del modelo utilizando métricas clave como **precisión**, **recall** y **F1-Score**.  

---

## 📂 Contenido del Proyecto  
1. **Preprocesamiento de Datos**  
   - Análisis exploratorio del dataset.  
   - Generación de visualizaciones para entender la distribución de clases y la correlación entre variables.  

2. **Construcción del Modelo**  
   - Creación de una Red Neuronal Artificial con capas densas, activaciones optimizadas y técnicas de regularización (Dropout).  
   - Entrenamiento del modelo con los datos procesados.  

3. **Evaluación y Resultados**  
   - Cálculo de métricas como **precisión**, **recall** y **F1-Score**.  
   - Visualización de la matriz de confusión para análisis detallado de las predicciones.  

---

## 🚀 Tecnologías Utilizadas  
- **Python 3.12**  
- **Pandas** y **NumPy** para el manejo y análisis de datos.  
- **Seaborn** y **Matplotlib** para visualización de datos.  
- **Keras** para construir y entrenar la red neuronal.  

---

## 📊 Resultados Visuales  
### Distribución de Clases  
![Distribución de Clases](distribucion-de-clases.png)  

### Matriz de Correlación  
![Matriz de Correlación](matriz-de-correlacion.png)  

### Matriz de Confusión  
![Matriz de Confusión](matriz-de-confusion.png)  

---

## 🎯 Métricas del Modelo  
- **Precisión:** 94%  
- **Recall:** 92%  
- **F1-Score:** 93%  

---

## 💡 Futuras Mejoras  
- Implementar técnicas de **balanceo de clases** para mejorar la representación en datasets desbalanceados.  
- Realizar una búsqueda de hiperparámetros más exhaustiva para optimizar el rendimiento del modelo.  

---

## 📁 Estructura del Proyecto  
```plaintext
phishing-detection/
├── data/
│   └── phishing-dataset.arff
├── notebooks/
│   └── model_training.ipynb
├── results/
│   ├── distribucion-de-clases.png
│   ├── matriz-de-correlacion.png
│   └── matriz-de-confusion.png
└── README.md
