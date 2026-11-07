# 📊 Proyecto Integrador de Estadística: Movilidad en Bogotá D.C.

Análisis estadístico descriptivo, probabilístico y ajuste de distribuciones sobre los desplazamientos diarios registrados en la **Encuesta de Movilidad de Bogotá** ($n = 147,251$ viajes).

## 🎯 Objetivo del Proyecto
Determinar la distribución de los medios de transporte predominantes (`MEDIO_PREDOMINANTE`) según el motivo de viaje (`MOTIVOVIAJE`), caracterizar estadísticamente los tiempos de caminata (`TIEMPO_CAMINO`) y estimar mediante un modelo binomial la probabilidad de uso del transporte público masivo.

## 📁 Contenido del Repositorio
* `Proyecto_Movilidad_Bogota.ipynb`: Cuaderno de Jupyter/Colab ejecutado con todo el código en Python, tablas de frecuencia, tablas de contingencia, Teorema de Bayes y visualizaciones.
* `graficos_etapa2_descriptiva.png`: Diagrama de barras, histograma (Regla de Sturges), polígono de frecuencias y diagrama de caja.
* `graficos_etapa4_binomial.png`: Comparación de la distribución empírica vs. modelo teórico $\text{Binomial}(n=10, p=0.3567)$ y función acumulada $F(x)$.

## 🛠️ Herramientas Utilizadas
* **Python 3** (`pandas`, `numpy`, `scipy.stats`, `matplotlib`, `seaborn`)
* **Google Colab**

## 👤 Autor
* **Juan Diego Díaz Borda** — Ingeniería Industrial, Universidad EAN (2026)
