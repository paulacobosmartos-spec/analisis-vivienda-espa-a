# 🏠 Análisis del mercado de la vivienda en España (2014–2026)

## 📌 Descripción del proyecto

Este proyecto realiza un análisis exploratorio de datos (EDA) sobre la evolución del Índice de Precios de Vivienda (IPV) en España, utilizando información oficial del Instituto Nacional de Estadística (INE).

El objetivo es identificar tendencias, comparar el comportamiento de la vivienda nueva y de segunda mano y analizar las diferencias entre Andalucía, Madrid y Cataluña.

## 🛠️ Herramientas utilizadas

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Visual Studio Code

## 📊 Principales resultados

**Evolución regional (2014T1–2026T2):**

| Comunidad autónoma | Crecimiento acumulado del IPV |
|---|---:|
| Madrid | +138,50 % |
| Cataluña | +118,14 % |
| Andalucía | +108,01 % |

Madrid presenta el mayor crecimiento relativo del índice entre las tres comunidades analizadas.

**Comparación por tipo de vivienda:**

En el análisis nacional, la vivienda nueva registra un crecimiento acumulado del 132,82 %, frente al 102,18 % de la vivienda de segunda mano, tomando como referencia el segundo trimestre de 2014.

## 🔎 Calidad de los datos

Se identificaron 1.248 valores ausentes en el dataset original, concentrados en Ceuta y Melilla para las categorías de vivienda nueva y de segunda mano.

Las series utilizadas en las comparaciones principales no presentan valores ausentes.

## 📁 Estructura del proyecto

- `data/79563.csv`: datos originales del INE.
- `NOTEBOOKS/eda.ipynb`: análisis exploratorio, cálculos y visualizaciones.
- `README.md`: documentación del proyecto.

## 📚 Fuente

Instituto Nacional de Estadística (INE) — Índice de Precios de Vivienda.

**Nota:** el IPV representa la evolución relativa de los precios, no los precios de las viviendas en euros.

## 🎯 Conclusión

El análisis muestra un crecimiento significativo del índice de precios de la vivienda durante el periodo estudiado, con diferencias entre comunidades autónomas y tipos de vivienda.

Este proyecto demuestra competencias en limpieza de datos, análisis exploratorio, transformación de datos y visualización con Python.