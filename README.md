# Reto: Modelación Estadística para la Toma de Decisiones 📊

Proyecto realizado como parte de la materia **Modelación Estadística para la Toma de Decisiones**  
Semestre **Agosto–Diciembre 2025**
Autores: 
- Laurie C. Hernández Pacheco
- Hugo E. Gamboa Sesma
- Emilio A. González Huerta
- Jacqueline Peña San Juan
- Pablo A. Robles Nava
---

## Descripción

Este reto consiste en aplicar herramientas de análisis **descriptivo e inferencial** para responder una pregunta de investigación basada en los datos de la **Encuesta MOLEC**.  
El objetivo principal es explorar las relaciones entre el **nivel educativo** y los **motivos de lectura** de distintos tipos de material (libros, revistas y medios digitales).

El análisis se llevó a cabo en **R**, utilizando técnicas como:

- Limpieza y transformación de datos.  
- Análisis descriptivo mediante visualizaciones (gráficos jitter, tablas de frecuencias, etc.).  
- Pruebas de hipótesis con **Chi-cuadrado** y **Fisher’s Exact Test**.  
- Simulación de Monte Carlo para estimar valores *p* en tablas de contingencia grandes.  
- Modelos de **regresión logística** (binomial y multinomial) para exploración predictiva.

---
```
## Estructura del proyecto
📁 Reto-Modelacion-Estadistica/
├── data/ # Bases de datos (MOLEC y derivadas)
├── scripts/ # Código en R (.R)
│ ├── limpieza_datos.R
│ ├── analisis_descriptivo.R
│ ├── pruebas_inferenciales.R
│ └── regresiones_logisticas.R
├── reporte/
│ └── Reto_Final.pdf # Reporte final con resultados
└── README.md # Este archivo
```
---

## Requisitos
- **R ≥ 4.2**
- Paquetes principales:
  - `tidyverse`
  - `ggplot2`
  - `dplyr`
  - `car`
  - `stats`
  - `DescTools`
