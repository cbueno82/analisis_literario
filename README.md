<h1 align="center">Análisis Literario</h1>
<h3 align="center">Procesamiento del Lenguaje Natural (PLN) y Análisis de Datos aplicados a literatura inglesa</h3>

<p align="center">
  <img src="https://img.shields.io/badge/estado-en%20progreso-yellow?style=flat-square">
  <img src="https://img.shields.io/badge/licencia-open--source-green?style=flat-square">
  <img src="https://img.shields.io/badge/python-3.10-blue?style=flat-square">
  <img src="https://img.shields.io/badge/NLP-spaCy%20%7C%20NLTK%20%7C%20BERTopic-purple?style=flat-square">
</p>

---

# Índice

- [Índice](#índice)
- [Descripción general](#descripción-general)
- [Objetivos del proyecto](#objetivos-del-proyecto)
- [Dependencias](#dependencias)
- [Pipeline del proyecto](#pipeline-del-proyecto)
  - [6.1 Limpieza del texto](#61-limpieza-del-texto)
  - [6.2 Procesamiento lingüístico](#62-procesamiento-lingüístico)
  - [6.3 Exploración del DataFrame](#63-exploración-del-dataframe)
  - [6.4 Métricas estilísticas](#64-métricas-estilísticas)
  - [6.5 Topic modeling](#65-topic-modeling)
- [Hoja de ruta](#hoja-de-ruta)
- [Estado del proyecto](#estado-del-proyecto)
- [Licencia y atribuciones](#licencia-y-atribuciones)

---

# Descripción general

Este repositorio contiene un proyecto abierto y en expansión dedicado al análisis cuantitativo y cualitativo de textos literarios mediante Data Analysis (DA) y Natural Language Processing (NLP).

Aunque la primera autora analizada es Sylvia Townsend Warner (*Lolly Willowes*, 1926), la estructura está diseñada para escalado horizontal hacia:

- literatura inglesa del siglo XIX (Austen, Brontë, Hardy),  
- modernismo del siglo XX (Woolf, Mansfield),  
- literatura fantástica escrita por mujeres (Walton, Warner),  
- textos medievales y renacentistas (Malory, Shakespeare).

---

# Objetivos del proyecto

- Implementar un *pipeline* reproducible para análisis literario computacional.  
- Estandarizar la limpieza de textos provenientes de Project Gutenberg.  
- Realizar procesamiento lingüístico avanzado mediante spaCy.  
- Analizar métricas estilísticas: longitud de palabra, riqueza léxica, hapaxes, distribución temática.  
- Aplicar técnicas de topic modeling (LDA y BERTopic).  
- Proveer visualizaciones interpretables para humanistas digitales.  
- Facilitar comparaciones entre autoras, obras y períodos.

---

# Pipeline del proyecto

## 6.1 Limpieza del texto

- limpiar_gutenberg()  
- limpiar_gutenberg_y_metadatos()  
- limpiar_gutenberg_completo()  

## 6.2 Procesamiento lingüístico

- Tokenización  
- Lematización  
- Stopwords personalizadas  
- Generación de tokens finales  

## 6.3 Exploración del DataFrame

- Frecuencias léxicas  
- Hapax legomena  
- Longitud de palabra  
- Muestreo aleatorio  
- Visualización exploratoria  

## 6.4 Métricas estilísticas

- Longitud media y percentiles  
- Comparativa entre autoras  
- Distribuciones léxicas  
- Riqueza léxica y variación  

## 6.5 Topic modeling

- LDA (gensim)  
- BERTopic (UMAP + HDBSCAN + c-TF-IDF)  

# Hoja de ruta

- [ ] Análisis de sentimiento (VADER y transformer-based)  
- [ ] Comparación entre capítulos  
- [ ] Clasificación temática por autora  
- [ ] Limpieza avanzada para textos medievales  
- [ ] Dashboards
- [ ] Embeddings semánticos (spaCy, SentenceTransformers)  
- [ ] Análisis estilístico comparado -> longitud de palabras, categorías gramaticales

---

# Estado del proyecto

<p align="left">
  <img src="https://img.shields.io/badge/estado-en%20progreso-yellow?style=flat-square"> </p>

Este proyecto está activo y continuará ampliándose.

---

# Licencia y atribuciones

- Textos originales obtenidos de Project Gutenberg.  
- Código disponible bajo licencia abierta.  
