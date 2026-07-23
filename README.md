# sprint7-final-project

# Proyecto 6 - Análisis de una empresa de telecomunicaciones

## Objetivo del proyecto

El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia. Para ello se realiza un proceso de exploración, limpieza y análisis estadístico de los datos con el fin de detectar patrones de uso, identificar valores atípicos y segmentar a los clientes para apoyar la toma de decisiones del negocio.

## Datasets utilizados

El proyecto utiliza los siguientes conjuntos de datos:

- `users_latam.csv`: información de los clientes (edad, ciudad, plan y fecha de registro).
- `plans.csv`: información de los planes de telefonía disponibles.
- `usage.csv`: registros de uso de llamadas, mensajes y otros servicios por cliente.

## Etapas del análisis realizadas

- Carga de los datos.
- Exploración inicial de los datasets.
- Identificación y tratamiento de valores faltantes.
- Corrección de valores centinela y fechas inválidas.
- Conversión de tipos de datos.
- Análisis estadístico descriptivo.
- Detección de valores atípicos mediante el método IQR.
- Creación de segmentos de clientes según su nivel de uso y edad.
- Visualización de resultados mediante histogramas, boxplots y gráficos de barras.
- Elaboración de conclusiones finales.

## Cómo ejecutar el notebook

1. Descargar el repositorio.
2. Abrir el archivo `.ipynb` en Google Colab o Jupyter Notebook.
3. Colocar los archivos `users_latam.csv`, `plans.csv` y `usage.csv` en la carpeta indicada por el notebook.
4. Ejecutar todas las celdas en orden utilizando **Run All** o **Restart Kernel and Run All Cells**.

## Guía de reproducción

1. Clonar o descargar este repositorio.
2. Abrir el notebook.
3. Verificar que los datasets estén disponibles.
4. Ejecutar todas las celdas desde el inicio.
5. Revisar las tablas, gráficos y conclusiones generadas al finalizar el análisis.