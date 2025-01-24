# Proyecto4_Clasificacion_de_Reseñas_de_peliculas

# Film Junky Union: Clasificación Automática de Reseñas de Películas  

**Film Junky Union** es una comunidad innovadora para los amantes del cine clásico. Este proyecto tuvo como objetivo desarrollar un sistema de clasificación automática de reseñas de películas utilizando aprendizaje automático, permitiendo identificar críticas negativas de forma eficiente.  

## Objetivo  
Entrenar un modelo de clasificación capaz de diferenciar reseñas positivas y negativas con un valor F1 de al menos **0.85**, utilizando un conjunto de datos de IMDB con polaridad etiquetada.  

## Proceso de Desarrollo  
1. **Preprocesamiento de Datos**:  
   - Limpieza del texto para eliminar ruido (caracteres no alfabéticos, mayúsculas y stopwords).  
   - Vectorización de las reseñas mediante TF-IDF, para transformar texto en representaciones numéricas.  

2. **Modelado**:  
   - Se entrenaron y evaluaron tres modelos: Regresión Logística, Árbol de Decisión y Bosques Aleatorios.  
   - La Regresión Logística obtuvo el mejor desempeño con un **F1-Score** de 0.88, superando el objetivo establecido.  

3. **Evaluación**:  
   - Los modelos fueron evaluados con métricas como precisión, recall y F1-Score, asegurando la confiabilidad de los resultados.  

4. **Clasificación de Nuevas Reseñas**:  
   - El sistema fue probado con reseñas simuladas, demostrando su capacidad para identificar críticas negativas y positivas con alta precisión.  

## Conclusiones  
La Regresión Logística demostró ser la mejor opción debido a su balance entre simplicidad y rendimiento. Este modelo cumple con los requisitos del proyecto y es altamente escalable para futuros desarrollos.  
