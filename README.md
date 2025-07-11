# 📊 Proyecto Final – Dashboard & Análisis de Datos - The Power

## Descripción del proyecto
Este proyecto forma parte del módulo "Dashboard & Análisis de Datos" del programa de formación de The Power Business School. Su objetivo es explorar la evolución salarial del sector tecnológico entre 2020 y 2024 a partir de un dataset real.
A través de un proceso de limpieza, normalización, análisis y visualización, se han desarrollado múltiples KPIs utilizando exclusivamente **tablas dinámicas en Google Sheets**, cumpliendo con los requisitos metodológicos del proyecto.
---

## Fuente de los datos
- Dataset: [Global Tech Salary Dataset (Kaggle)](https://www.kaggle.com/datasets/yaaryiitturan/global-tech-salary-dataset)
- Periodo: 2020 – 2024
- Registros: ~4.600 filas
- Columnas clave: `salary_in_usd`, `remote_ratio`, `experience_level`, , `job_title`, `work_year`, `employment_type`

---

## Herramienta utilizada
- **Google Sheets**
---


## ✅ 1. Transformación y limpieza de datos

Antes del análisis, se realizó un proceso exhaustivo de preparación del dataset, incluyendo:

- 🔎 **Eliminación de duplicados**
- ✅ **Normalización de campos clave**, como `employment_type` (→ `tipo_empleo`) y `remote_ratio` (→ `tipo_remoto`)
- ⚠️ **Detección y tratamiento de valores vacíos o inconsistentes**
- 📐 **Validación de tipos de datos** (`salary_in_usd`, `work_year`, etc.)
- 🧽 Revisión de estructura y formato general para garantizar la fiabilidad de los KPIs posteriores

---

## 📊 2. Análisis descriptivo – KPIs construidos

El análisis se ha estructurado en torno a los siguientes indicadores clave:

1. **Salario promedio global en USD por año**
2. **Crecimiento salarial interanual**
3. **Porcentaje de crecimiento anual respecto al total**
4. **Top 5 países con mayor salario promedio**
5. **Salario promedio por nivel de experiencia**
6. **Evolución salarial por rol**
7. **Distribución por tipo de empleo** (Full-time, Part-time, Contract, Freelance)
8. **Top 5 roles mejor pagados y peor pagados por año**
9. **Identificación de roles nuevos en 2024**
10. **Cruce entre roles nuevos y extremos salariales**
11. **Top 5 nuevos roles mejor pagados en 2024**
12. **Evolución del tipo de trabajo remoto (presencial, híbrido, remoto total)**
13. **Relación entre modalidad de trabajo y salario promedio**

Cada uno ha sido construido mediante **tablas dinámicas**, y en algunos casos se ha recurrido a **tablas auxiliares filtradas** para facilitar la visualización o análisis comparativo.

---

## 📌 3. Visualización – Construcción del dashboard

El dashboard se ha diseñado en Google Sheets con una estructura clara y visualmente equilibrada:

- 📈 Gráficos de líneas y columnas para la evolución temporal de salarios
- 📊 Gráficos circulares y de barras para distribución por categorías
- 🧠 Bloques de insights redactados a partir del análisis visual y numérico
- 🔍 Secciones diferenciadas para KPIs principales y secundarios

Todas las visualizaciones están conectadas a datos dinámicos filtrados por año, tipo de trabajo y otras variables clave.

---

## ✍️ Autoría

Trabajo desarrollado por **Eva María Mera Vivar**  
Máster en Análisis de Datos – Proyecto Final
## Acceso al dashboard
🔗 **[Ver dashboard en Google Sheets]([https://docs.google.com/spreadsheets/d/TU_ENLACE_AQUI](https://docs.google.com/spreadsheets/d/1_J309v4AuZ8Dk3OCAvlzgJwF8kTV2X038X2gSJac3PI/edit?usp=sharing)
**

---
