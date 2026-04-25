# TP2 - Procesamiento de Lenguaje Natural

## Alumno

Alex Martín CURELLICH - SIU a2214

## Descripción

Trabajo práctico sobre representación semántica de texto utilizando **embeddings de palabras (Word2Vec)** entrenados sobre un corpus de letras de canciones.  
Se aplican técnicas de preprocesamiento, aprendizaje de representaciones vectoriales y análisis de similaridad semántica.

---

## Contenido

El trabajo incluye los siguientes puntos:

1. **Preprocesamiento del corpus**

   * Normalización de texto
   * Tokenización
   * Eliminación de stopwords (opcional)

2. **Entrenamiento de embeddings**

   * Modelo Word2Vec
   * Ajuste de hiperparámetros (window, vector_size, min_count)

3. **Análisis de similaridad**

   * Palabras más similares
   * Exploración de relaciones semánticas

4. **Visualización de embeddings**

   * Reducción de dimensionalidad (PCA / t-SNE)
   * Análisis de agrupamientos de palabras

---

## Requisitos

El proyecto utiliza **Poetry** para la gestión de dependencias.

Instalación:

```bash
poetry install
```


Ejecución:

```bash
poetry run jupyter notebook