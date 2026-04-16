# Predicción de ventas de una tienda

## Objetivo
Desarrollar un modelo de series de tiempo para predecir las ventas mensuales de una tienda, utilizando datos históricos y técnicas de modelamiento como ARIMA.

## Dataset
Datos históricos de ventas mensuales contenidos en el archivo `Sales_Data.xlsx`, correspondientes a varios años.

## Metodología
- Análisis de la serie de tiempo: descomposición en tendencia, estacionalidad y residuos
- Evaluación de estacionaridad: test de Dickey-Fuller, aplicación de diferenciación si es necesario
- Identificación de parámetros del modelo: análisis de ACF y PACF para determinar valores de p y q
- Modelamiento: entrenamiento de modelo ARIMA sobre datos históricos
- Evaluación: separación en conjunto de entrenamiento y prueba, y evaluación mediante métricas como MAE y MSE

## Resultados
- Identificación de componentes de tendencia y estacionalidad en las ventas
- Definición de un modelo ARIMA adecuado para la serie
- Predicciones consistentes sobre el conjunto de prueba

## Tecnologías utilizadas
Python, Pandas, NumPy, Matplotlib, Statsmodels
