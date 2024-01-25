# Predicción Musical en Spotify

## Objetivo

Este proyecto tiene como objetivo construir y evaluar modelos de aprendizaje automático para predecir las canciones TOP 10 en la lista de reproducción de Spotify. Se utiliza un conjunto de datos que incluye información detallada sobre artistas y canciones.

## Introducción

### Spotify

Spotify es una plataforma líder en la industria de la música digital que ofrece acceso a un extenso catálogo de música, podcasts y contenido de audio. Desde su lanzamiento en 2008, ha revolucionado la forma en que las personas consumen música.

### Conjunto de Datos

El conjunto de datos proviene de Kaggle y se basa en extracciones de la base de datos de Spotify a través de su API. Incluye información sobre artistas, géneros, popularidad, seguidores, canciones, álbumes y más.

## Estructura del Proyecto

- `1_Data_Cleaning.ipynb`: Cuaderno de Jupyter utilizado para la limpieza de datos.
- `2_EDA.ipynb`: Cuaderno de Jupyter que realiza un análisis exploratorio de los datos.
- `3_Preprocessing_ML.ipynb'`: Cuaderno de Jupyter donde se implementan los modelos de aprendizaje automático.
- `README.md`: Documentación principal del proyecto.

## Limpieza de Datos

En este paso se trataron NaNs, datos duplicados y se realizaron ajustes en las categorías de datos según fuera necesario.

## Análisis Exploratorio de Datos (EDA)

Se exploraron diversas métricas, como los géneros musicales más reproducidas, número de seguidores de los artistas, popularidad de las canciones, etc.

## Machine Learning

Se entrenaron varios modelos de aprendizaje automático y se ajustaron hiperparámetros utilizando GridSearchCV. Los mejores modelos se utilizaron para hacer predicciones.

## Conclusiones

Los mejores modelos se identificaron como el Random Forest. 

## Cómo Ejecutar el Proyecto

1. Clona el repositorio: `git clone https://github.com/tu_usuario/tu_proyecto.git`
2. Instala las dependencias: `pip install -r requirements.txt` (si es necesario).
3. Ejecuta los cuadernos de Jupyter en el orden mencionado.

---

*Este proyecto fue desarrollado como parte de un bootcamp de Data Science.*

