# 📊 LinkedIn Job Postings Analytics (2023 - 2024)

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Data_Analytics](https://img.shields.io/badge/Focus-Data_Analysis-green.svg)

## 📝 Descripción del Proyecto
Este proyecto analiza un conjunto de datos de ofertas de empleo de LinkedIn para identificar cuáles son las habilidades, herramientas y tecnologías más demandadas para el rol de **Data Analyst** como también **Data Scientist**. 

El objetivo principal es transformar descripciones de puestos de trabajo en formato de texto masivo (*unstructured text*) en insights visuales.

## 🚀 Características Clave
- **Limpieza de Datos con Regex:** Procesamiento de texto eliminando caracteres especiales, normalización a minúsculas y estandarización.
- **NLP (Procesamiento de Lenguaje Natural):** Remoción de *stopwords* y tokenización avanzada.
- **Lematización con SpaCy:** Consolidación de palabras complejas a su raíz morfológica en inglés/español utilizando modelos avanzados de NLP (`en_core_web_sm`).

## 📊 Visualizaciones Incluidas
### 1. Herramientas más solicitadas (Matplotlib & Seaborn)
Aquí se identifican el volumen de menciones exactas de tecnologías core como SQL, Python, Excel y R mediante límites de palabras exactas (`\b`).
`![Gráfico de Barras](images/grafico_barras.png)`

### 2. Nube de Palabras Clave (WordCloud)
Resultado visual de los términos dominantes tras el pipeline de lematización.
`![Nube de Palabras](images/wordcloud.png)`

## 🛠️ Tecnologías Utilizadas
- **Lenguaje:** Python 3.x
- **Manipulación de Datos:** Pandas
- **Visualización:** Matplotlib, Seaborn, WordCloud
- **Procesamiento de Texto (NLP):** NLTK, SpaCy (`en_core_web_sm`)

