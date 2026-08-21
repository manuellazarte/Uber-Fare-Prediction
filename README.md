# Predicción de Tarifas de Uber

## Descripción General

El objetivo de este trabajo práctico es desarrollar modelos de regresión para predecir el costo de viajes de Uber a partir de características como la cantidad de pasajeros, fecha y hora, y las coordenadas geográficas de origen y destino.

## Preprocesamiento y Análisis

Se realiza un análisis exploratorio del dataset, tratamiento de datos faltantes y atípicos, escalado de variables y generación de nuevas características a partir de la fecha, hora y ubicación de los viajes.

## Modelos

Se implementan y comparan:

- Regresión Lineal Múltiple.
- Descenso por Gradiente.
- Ridge.
- Lasso.
- Elastic Net.

Los modelos se evalúan mediante **R², RMSE y MAE**, complementando el análisis con gráficos de residuos.

## Resultados

La Regresión Lineal utilizada como baseline obtuvo:

- **R²:** 0.7306
- **RMSE:** 4.7547
