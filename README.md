# Análisis y Visualización de Datos Médicos con Herramientas de Inteligencia Artificial

## 1. Introducción

Este proyecto académico tiene como objetivo aplicar herramientas y técnicas para la recolección, análisis y presentación de datos relacionados con la Inteligencia Artificial, utilizando como caso de estudio datos médicos de pacientes. Se emplean dos fuentes de datos: un archivo CSV y una base de datos SQLite, integrando ambos para un análisis conjunto y visualización de resultados relevantes.

## 2. Marco teórico de las tecnologías/librerías usadas

- **Jupyter Notebook**: Plataforma interactiva que permite combinar código, visualizaciones y texto explicativo en un solo documento, ideal para análisis exploratorio de datos.
- **Pandas**: Librería de Python especializada en manipulación y análisis de datos, facilitando la lectura, combinación y procesamiento de datasets.
- **Matplotlib**: Herramienta de visualización en Python que permite crear gráficos estáticos y personalizables para el análisis de datos.
- **SQLite**: Sistema de gestión de bases de datos relacional, ligero y de fácil integración con Python, utilizado para almacenar y consultar datos estructurados.

## 3. Descripción de los datasets usados

- **heart_data.csv**: Archivo CSV que contiene registros médicos de pacientes, incluyendo variables como edad, género, frecuencia cardíaca, presión arterial, glucosa, marcadores cardíacos y resultado del test.
- **medical_heart_data.db**: Base de datos SQLite con una tabla `medical_data` que almacena información similar a la del CSV, permitiendo demostrar la integración de diferentes fuentes de datos.
- **FinalDataSet.csv**: Archivo CSV resultante de la combinación de los datos provenientes de `heart_data.csv` y la tabla `medical_data` de la base de datos SQLite. Este archivo representa el dataset final unificado utilizado para el análisis y las visualizaciones presentadas en el proyecto.

Ambos datasets contienen las siguientes columnas principales:
- Age (Edad)
- Gender (Género)
- Heart rate (Frecuencia cardíaca)
- Systolic blood pressure (Presión sistólica)
- Diastolic blood pressure (Presión diastólica)
- Blood sugar (Glucosa en sangre)
- CK-MB (Marcador cardíaco)
- Troponin (Marcador cardíaco)
- Result (Resultado del test)

## 4. Descripción de los pasos realizados en el proyecto

1. **Consumo de datos**: Se leen los datos desde el archivo CSV y la base de datos SQLite utilizando Pandas.
2. **Combinación de fuentes**: Ambos datasets se concatenan en un único DataFrame para un análisis integral.
3. **Análisis exploratorio y visualización**: Se generan visualizaciones para explorar la distribución de variables clave y la relación entre ellas.

### 4.1 Visualizaciones generadas
- **Distribución de edades**: Histograma que muestra la frecuencia de pacientes por grupo etario.
- **Distribución de frecuencia cardíaca**: Histograma de los valores de frecuencia cardíaca registrados.
- **Dispersión presión sistólica vs. diastólica**: Gráfico de dispersión que permite observar la relación entre ambas presiones.
- **Conteo de resultados**: Gráfico de barras que muestra la cantidad de resultados positivos y negativos en los tests médicos.

## 5. Conclusiones

El proyecto demuestra la capacidad de integrar y analizar datos provenientes de diferentes fuentes utilizando herramientas modernas de ciencia de datos. La visualización facilita la identificación de patrones y posibles anomalías en los datos médicos, sentando las bases para aplicaciones más avanzadas en el ámbito de la inteligencia artificial y la salud.

## 6. Bibliografía

- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [SQLite Documentation](https://www.sqlite.org/index.html)
- [Jupyter Project](https://jupyter.org/)