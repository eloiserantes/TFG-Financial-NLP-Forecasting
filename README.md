# TFG - Trading Algorítmico y Análisis de Sentimiento con Noticias Financieras

**Autor:** Eloi Serantes Abal

## 1. Descripción
Este repositorio contiene los notebooks desarrollados para predecir series temporales financieras mediante técnicas de trading algorítmico. El sistema integra históricos de precios con análisis de sentimiento extraído de noticias mediante FinBERT, utilizando redes neuronales LSTM para la toma de decisiones y simulando estrategias de inversión (Long-Only, Long/Short y Buy & Hold) frente a índices de referencia del mercado.

### Estructura del proyecto:
* **01_Comparativa_datasets_y_FinBERT.ipynb:** Análisis comparativo entre datasets e inferencia con FinBERT del dataset FNSPID.
* **02_Experimentación_Trading.ipynb:** Experimentación y medidas de mitigación para el *lagging* (retraso predictivo).
* **03_FNSPID_VS_FinMultiTime_Resumen.ipynb:** Comparativa de caracteres y palabras por noticia en ambos datasets.
* **04_FinMultiTime.ipynb:** Resumen de noticias, inferencia con FinBERT y experimentación con el dataset FinMultiTime.
* **05_Optimizacion_parametros.ipynb:** Optimización de parámetros con un *Grid Search* para ambos conjuntos de datos.
* **06_Experimentación_final.ipynb:** Últimos experimentos realizados.

## 2. Instalación y Ejecución
Para ejecutar el código, simplemente se deben descargar los notebooks de este repositorio y ejecutarlos. Se recomienda seguir el orden secuencial (del `01` al `06`). 

Los tests y las gráficas de evaluación de las distintas estrategias implementadas se pueden visualizar ejecutando directamente los notebooks enfocados en la experimentación y resultados (`02` y `06`).
