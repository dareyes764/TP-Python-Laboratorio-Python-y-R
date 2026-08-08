# TP-Python-Laboratorio-Python-y-R
Integra las herramientas vistas a lo largo del módulo Python: implementación manual de estimadores, simulaciones Monte Carlo, bootstrap y visualización de datos.

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dareyes764/TP-Python-Laboratorio-Python-y-R/blob/main/TP_Python.ipynb)

### Maestría en Econometría — Universidad Torcuato Di Tella
Laboratorio de Programación en Python y R — Docente: Ian Evangelos Bounos

## Descripción

El trabajo se divide en tres partes:

- *Parte 1 — Robustez ante contaminación de muestras*
  - 1.1: Comparación de sesgo y ECM empírico de la media y la mediana bajo distintos niveles de contaminación por outliers.
  - 1.2: Estimación de una regresión lineal contaminada usando OLS (implementado a mano, con la fórmula matricial) y LAD (Least Absolute Deviations, minimizado con scipy.optimize.minimize).

- *Parte 2 — Paradoja de Simpson y variables omitidas*
  Simulación de un modelo causal donde una variable X no tiene efecto directo sobre Y, pero el sesgo por variables omitidas hace que su coeficiente estimado cambie de signo según qué controles se incluyan en la regresión.

- *Parte 3 — Análisis empírico con Gapminder*
  Análisis de convergencia hacia el promedio mundial y de atipicidad respecto al continente, para el país Honduras, usando el dataset Gapminder (1952-2007).

## Cómo ejecutar

1. Abrir el notebook TP_Python.ipynb en [Google Colab](https://colab.research.google.com/) (subiéndolo directamente o con el botón "Abrir en Colab" de arriba).
2. Ejecutar *Entorno de ejecución → Reiniciar y ejecutar todo*.
3. El notebook corre de principio a fin sin modificaciones ni dependencias externas más allá de las librerías estándar de ciencia de datos en Python (numpy, pandas, matplotlib, seaborn, statsmodels, scipy), todas preinstaladas en Colab.

## Estructura del repositorio

## Autor(es)
- Aarón David Reyes Rubio
