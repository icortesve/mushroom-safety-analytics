# 🍄 Mushroom Risk Analytics & Safety Decision Framework

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Library-Pandas-150458.svg)](https://pandas.pydata.org/)
[![Data Analytics](https://img.shields.io/badge/Focus-Risk%20Analysis-orange.svg)]()

Análisis exploratorio de datos (EDA) y marco analítico de evaluación de riesgo desarrollado en Python con **Pandas** para identificar patrones físicos y firmas biológicas que permiten diferenciar hongos comestibles de venenosos, eliminando la ambigüedad en la clasificación de toxicidad.

---

## 🎯 Objetivos y Evaluación de Hipótesis

- **Objetivo Principal:** Construir un protocolo analítico de seguridad basado en datos para clasificar el nivel de riesgo según atributos físicos observables (olor y color de la esporada).
- **Hipótesis 1 (H1):** *El olor es el mecanismo biológico de advertencia más fuerte.* Evaluado mediante la agrupación de 'Grupos Sensoriales' y la cuantificación matemática de riesgo proporcional por cada aroma.
- **Hipótesis 2 (H2):** *El color de las esporas completa la información para resolver zonas ambiguas.* Evaluado agrupando los 9 colores de esporas en bloques de peligrosidad (Seguros, Ambiguos y Tóxicos).

---

## 🛠 Metodología de Análisis y Limpieza de Datos

1. **Auditoría y Limpieza:** Identificación y tratamiento de falsos nulos (`'?'` en la columna `stalk-root`) y verificación de registros duplicados.
2. **Estandarización de Variables:** Creación de diccionarios de traducción para mapear los códigos originales del dataset a términos estandarizados en español.
3. **Análisis Multivariable de Riesgo:** Cruce de grupos sensoriales con categorías de esporas para resolver casos ambiguos (ej. hongos sin olor).
4. **Matriz de Decisión y Protocolo Operativo:** Síntesis de un manual técnico estructurado en **5 escenarios de riesgo**, proporcionando acciones claras de seguridad orientadas a la toma de decisiones.

---

## 📁 Estructura del Repositorio

- `Analisis con Panda y Kaggle.ipynb`: Notebook con el flujo analítico completo y EDA.
- `mushrooms.csv`: Dataset original.
- `README.md`: Documentación y síntesis del proyecto.
- `requirements.txt`: Dependencias del proyecto.

---

## 🚀 Instalación y Ejecución

1. **Clonar el repositorio:**
   git clone [https://github.com/icortesve/mushroom-risk-analytics.git](https://github.com/icortesve/mushroom-risk-analytics.git)
   cd mushroom-risk-analytics

2. **Instalar dependencias:**
   pip install -r requirements.txt

3. **Ejecutar el Jupyter Notebook:**
   jupyter notebook "Analisis con Panda y Kaggle.ipynb"

---

## 👤 Autor

**Iván Cortés Venegas** — Ingeniero Civil Químico | Data & BI Analyst
- LinkedIn: [https://www.linkedin.com/in/iván-cortés-venegas-48a12378/](https://www.linkedin.com/in/iván-cortés-venegas-48a12378/)
- GitHub: [https://github.com/icortesve](https://github.com/icortesve)
