# Modelo Predictivo Orientado a Estrategias de Marketing en Agencia de Viajes
## Ciencia de Datos · Machine Learning · Marketing Analytics
Proyecto de ciencia de datos orientado al desarrollo de un modelo predictivo que permita estimar la probabilidad de compra de productos turísticos (boletos) y utilizar esa información para diseñar estrategias de marketing más eficientes. 

Este proyecto abarca todas las etapas del proceso de ciencia de datos: desde la exploración y limpieza del dataset hasta la implementación y comparación de diversos modelos de clasificación. Entre los modelos evaluados se incluyen la Regresión Logística, Árboles de Decisión, Random Forest y XGBoost.

## Contexto
Las agencias de viajes necesitan identificar a los potenciales compradores para orientar sus campañas comerciales y aprovechar mejor sus recursos de marketing. 

Sin un modelo predictivo, las acciones pueden dirigirse a usuarios con diferentes intenciones de compra sin priorizar a aquellos que presentan una mayor probabilidad de conversión. 

El desafío consiste en utilizar los datos disponibles para anticipar el comportamiento de compra y generar información útil para la toma de decisiones comerciales.
## Objetivo
Construir un modelo de clasificación que asigne una probabilidad de compra a cada usuario según sus características y comportamientos.

A partir de las probabilidades estimadas, se busca identificar segmentos de usuarios y proponer acciones de marketing diferenciadas, priorizando los esfuerzos comerciales según la probabilidad de conversión.
## Herramientas utilizadas

**Lenguaje:** Python

**Análisis y manipulación de datos:**
- Pandas
- NumPy

**Visualización:**
- Matplotlib
- Seaborn

**Machine Learning:**
- Scikit-learn
- XGBoost

**Entorno de trabajo:**
- Google Colab

## Metodología
### 1. Preparación de datos

Se realizaron las transformaciones necesarias para tratar errores tipográficos, valores nulos y outliers.

La variable objetivo, `Taken_product`, representa si un usuario adquirió un producto turístico:

- `Yes`: realizó una compra.
- `No`: no realizó una compra.

### 2. Análisis exploratorio de datos (EDA)

Se realizó un análisis inicial del conjunto de datos para comprender la distribución de las variables y explorar su relación con la compra de boletos.

Entre las principales actividades se incluyen:

- Exploración de variables numéricas y categóricas.
- Análisis de distribuciones y valores atípicos.
- Comparación entre compradores y no compradores.
- Elaboración de tablas de contingencia.
- Identificación de posibles patrones relacionados con la conversión.

### 3. Entrenamiento de modelos

Se desarrollaron y compararon tres algoritmos de clasificación:

- Regresión Logística
- Árbol de Decisión
- Random Forest
- XGBoost

Se utilizaron procedimientos de entrenamiento y evaluación para comparar su capacidad predictiva.

### 4. Evaluación de modelos

El desempeño se analizó mediante métricas de clasificación, incluyendo:

- F1-score
- ROC-AUC
- Precision y Recall
- Matriz de confusión

También se analizaron los errores de clasificación para comprender sus posibles implicancias en decisiones comerciales.

## Resultados y aplicación al negocio

El análisis permitió comparar diferentes enfoques de clasificación y explorar la utilidad de las probabilidades estimadas para identificar usuarios con distinta propensión de compra.

Desde una perspectiva comercial, estas predicciones podrían utilizarse para:

- Priorizar potenciales clientes en campañas de marketing.
- Diseñar comunicaciones según la probabilidad de conversión.
- Identificar segmentos que requieren acciones diferenciadas.
- Reducir contactos comerciales de bajo rendimiento esperado.
- Evaluar estrategias considerando los costos de los falsos positivos y falsos negativos.

## Documentación completa

Para consultar la documentación completa de los análisis realizados, la interpretación de los resultados y las recomendaciones comerciales:

[Ver documentación del proyecto en Notion](https://app.notion.com/p/Modelo-Predictivo-Orientado-a-Estrategias-de-Marketing-en-Agencia-de-Viajes-3fc3ae5b14c280d19431c26ccf297201?source=copy_link)


