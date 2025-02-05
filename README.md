# Sweet Lift Taxi: Taxi Order Prediction / Sweet Lift Taxi: Predicción de Pedidos de Taxis

## Descripción

El proyecto tiene como objetivo predecir la cantidad de pedidos de taxis en la próxima hora en aeropuertos, utilizando datos históricos de la compañía Sweet Lift Taxi. Esta predicción ayuda a optimizar la asignación de conductores durante las horas pico y mejorar la eficiencia del servicio. Se entrenan distintos modelos de machine learning, evaluados con la métrica RECM (objetivo: RECM ≤ 48).

## Datos

Conjunto de datos: [https://drive.google.com/drive/folders/18GOxZGPP8GXFYCT4BuUnarVFbr6hoink?usp=sharing]

## Pasos del Proyecto

1. **Preparación de los Datos:**  
   - Descarga de datos históricos.
   - Remuestreo de los datos para que cada punto corresponda a intervalos de una hora.

2. **Análisis de los Datos:**  
   - Exploración de tendencias y patrones.
   - Validación de la calidad de los datos para el modelado.

3. **Entrenamiento de Modelos:**  
   - Entrenamiento de diferentes modelos de machine learning con diversas configuraciones de hiperparámetros.

4. **Evaluación del Rendimiento:**  
   - Prueba del modelo utilizando un 10% de los datos.
   - Evaluación de la precisión mediante la métrica RECM, asegurando que su valor no supere 48.

## Uso

1. Clona el repositorio.
2. Descarga el conjunto de datos y colócalo en la ruta indicada.
3. Ejecuta el cuaderno o script principal para reproducir el análisis y entrenamiento del modelo.
