📌 Análisis de Sentimientos con Procesamiento de Lenguaje Natural (NLP)
Este repositorio contiene un proyecto de análisis de sentimientos utilizando Procesamiento de Lenguaje Natural (NLP). Se ha trabajado con un corpus de reseñas, aplicando diferentes técnicas de preprocesamiento, entrenamiento de modelos y visualización de resultados.

📂 Estructura del Proyecto
El proyecto está dividido en varias etapas, cada una con su propio notebook:

1️⃣ Descarga y Exploración del Corpus
📌 Análisis inicial de los datos, incluyendo:

Cardinalidad del vocabulario
Distribución de reviews por número de estrellas
Número de reseñas positivas y negativas
📊 Visualizaciones Incluidas:
N-grams más frecuentes
Nubes de palabras
Representación de word embeddings en 2D con Word2Vec

2️⃣ Preprocesado de Texto
🛠 Se aplican técnicas de limpieza y transformación del texto:
Eliminación de caracteres especiales y normalización
Tokenización y lematización
Eliminación de stopwords
Vectorización con CountVectorizer y TfidfVectorizer

3️⃣ Entrenamiento y Testeo del Modelo
🎯 Modelos utilizados:
Regresión Logística
K-Vecinos
Cada modelo se entrena con diferentes configuraciones de vectorización para comparar su rendimiento.
Reporte de Métricas y Conclusiones
📊 Se presentan métricas como precisión, recall, F1-score y matriz de confusión, junto con conclusiones sobre el rendimiento de cada modelo.

4️⃣ Pruebas con el Preprocesado Corregido
🔍 Se realizan ajustes en el preprocesamiento para mejorar la calidad del modelo y se vuelven a evaluar los resultados.

