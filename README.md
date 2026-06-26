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
### 1. Skills más frecuentes en los post de Data Analyst
Las  dos Skills más presentes en los posts analizados fueron **Information Tecnology**  y **Analyst** esto era algo que me esperaba, lo que me sorprendio fue al momento de compararla con las skills en los post de **Data Scientist** pues no esperaba que en estos la skill de **Engineering** fuera tan dominante. Esto lo podemos ver en los gráficos siguientes:

![Skills Data Analyst](imagenes/skills_da.png)
![Skills Data Analyst](imagenes/skills_ds.png)

### 2. Herramientas más solicitadas (Matplotlib & Seaborn)
Aquí se identifican el volumen de menciones exactas de tecnologías core como SQL, Python, Excel y R mediante límites de palabras exactas. Primero lo analizamos en los post referentes a **Data Analyst**, obteniendo los siguientes resultados mostrados en la gráfica.
![Tools Data Analyst](imagenes/tools_da.png)
Podemos observar que Excel es sin duda la herramineta más pedida, sin embargo para los post de **Data Scientist** tenemos que Python se lleva la corona.
![Tools Data Scientist](imagenes/tools_ds.png)

### 2. Nube de Palabras Clave (WordCloud)
Resultado visual de los términos dominantes en los post.
Para **Data Analyst** tenemos que las palabras más presentes son Data, experience, bussines.
![Nube de Palabras](imagenes/wc_da.png)
De la misma forma para los pots de **Data Scientist** las palabras Data y experience estan presentes y aparece Machine Learning y Team con un numero conciderable de veces.
![Nube de Palabras](imagenes/wc_ds.png)

### 3. Top Industrias
Otro aspecto de interés surge al analizar el tipo de industrias que publican las ofertas de empleo, ya que también se observan diferencias entre los perfiles de **Data Analyst** y **Data Scientist**. En el caso de **Data Analyst**, la industria de servicios y consultoría en tecnologías de la información concentra el mayor número de publicaciones. En contraste, para **Data Scientist**, la industria de servicios financieros es la que ofrece más vacantes en comparación con el resto de los sectores analizados. Estas diferencias pueden apreciarse en los siguientes gráficos.

![top Industrias DA](imagenes/top_in_da.png)

![top Industrias DS](imagenes/top_in_ds.png)


## 🛠️ Tecnologías Utilizadas
- **Lenguaje:** Python 3.x
- **Manipulación de Datos:** Pandas
- **Visualización:** Matplotlib, Seaborn, WordCloud
- **Procesamiento de Texto (NLP):** NLTK, SpaCy (`en_core_web_sm`)

