# 🎮 Análisis de Ventas de Videojuegos — Ice Store

Este proyecto fue desarrollado para **Ice**, una tienda online que comercializa videojuegos a nivel mundial.  
El objetivo es **identificar patrones que determinan el éxito de un videojuego** en base a datos históricos de ventas, reseñas y clasificaciones, con el fin de **predecir qué títulos serán más prometedores** y optimizar las estrategias de marketing.

## 🎯 Objetivo del proyecto

El departamento comercial de Ice busca comprender qué factores influyen en el éxito de un videojuego, considerando:
- Género del juego  
- Plataforma (por ejemplo, Xbox, PlayStation, PC)  
- Calificaciones de críticos y usuarios  
- Clasificación por edades (ESRB)  
- Región de lanzamiento  

El análisis permite anticipar tendencias y planificar campañas publicitarias más efectivas para el siguiente año (simulando diciembre de 2016 y proyectando hacia 2017).

## 🧠 Contexto

Los datos incluyen **ventas globales y métricas de evaluación** de videojuegos lanzados hasta 2016.  
La tarea principal consiste en explorar el dataset, detectar correlaciones entre variables y analizar los factores que impulsan las ventas exitosas.

## 🧩 Descripción del dataset

| Columna | Descripción |
|----------|--------------|
| **Name** | Nombre del videojuego |
| **Platform** | Plataforma (Xbox, PlayStation, PC, etc.) |
| **Year_of_Release** | Año de lanzamiento |
| **Genre** | Género del juego (acción, deportes, rol, etc.) |
| **NA_sales** | Ventas en Norteamérica (millones USD) |
| **EU_sales** | Ventas en Europa (millones USD) |
| **JP_sales** | Ventas en Japón (millones USD) |
| **Other_sales** | Ventas en otros países (millones USD) |
| **Critic_Score** | Puntuación promedio de críticos (máx. 100) |
| **User_Score** | Puntuación promedio de usuarios (máx. 10) |
| **Rating** | Clasificación ESRB (E, T, M, etc.) |

## 🧰 Herramientas utilizadas

- **Python** 🐍  
- **Pandas**, **NumPy** — Limpieza y manipulación de datos  
- **Matplotlib**, **Seaborn** — Visualización y análisis exploratorio  
- **SciPy**, **Statsmodels** — Pruebas estadísticas y correlaciones  
- **Jupyter Notebook** — Desarrollo del análisis interactivo  

## 📈 Metodología

1. **Exploración inicial**  
   - Revisión del dataset, tipos de datos y valores faltantes.  
   - Detección de outliers y valores inconsistentes.

2. **Limpieza de datos**  
   - Normalización de nombres y categorías.  
   - Conversión de tipos (numéricos, fechas).  
   - Eliminación o imputación de valores nulos.

3. **Análisis exploratorio (EDA)**  
   - Identificación de plataformas y géneros más populares.  
   - Análisis de tendencias de ventas por región.  
   - Comparación entre puntuaciones de críticos y usuarios.  
   - Evaluación del impacto del **rating ESRB** en las ventas.

4. **Análisis estadístico**  
   - Correlaciones entre calificaciones y ventas.  
   - Detección de diferencias significativas entre géneros o plataformas.  
   - Prueba de hipótesis sobre factores de éxito.

5. **Visualización y comunicación de resultados**  
   - Gráficos comparativos (ventas, distribuciones, correlaciones).  
   - Insights clave presentados de forma visual y narrativa.

## 📊 Resultados esperados

- Identificación de los **géneros y plataformas más rentables**.  
- Determinación de la **relación entre críticas y ventas**.  
- Conocimiento de **patrones regionales** en el consumo de videojuegos.  
- Recomendaciones sobre **en qué tipo de juegos invertir** y cómo orientar el marketing.
