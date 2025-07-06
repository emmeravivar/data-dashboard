# 📊 Proyecto Final – Dashboard & Análisis de Datos - The Power

## Descripción del proyecto
Este proyecto forma parte del módulo "Dashboard & Análisis de Datos" del programa de formación de The Power Business School. Su objetivo es aplicar técnicas de limpieza, transformación y visualización de datos a partir de un conjunto real del sector tech internacional.

Se han desarrollado diferentes KPIs para identificar tendencias en modalidades de trabajo, analizar salarios por experiencia, tipo de jornada y divisa, así como detectar extremos salariales a nivel global.

---

## Fuente de los datos
- Dataset: [Global Tech Salary Dataset (Kaggle)](https://www.kaggle.com/datasets/yaaryiitturan/global-tech-salary-dataset)
- Periodo: 2020 – 2024
- Registros: ~4.600 filas
- Columnas clave: `salary_in_usd`, `remote_ratio`, `experience_level`, `company_location`, `job_title`, `work_year`, `salary_currency`, `company_size`, `employment_type`

---

## Herramienta utilizada
- **Google Sheets**
- **Gráficos utilizados**:
  - Gráfico circular (distribución de modalidad laboral global)
  - Gráfico de líneas (tendencia de modalidad por año)
  - Gráfico de burbujas (presencialidad y tamaño de la empresa)
  - Gráfico de columnas (salario medio por experiencia)
  - Gráficos de tarjetas visuales (país mejor/peor pagador)
  - Gráfico radar (comparativa de salario mensual por tipo de jornada y divisa)
- **Funciones aplicadas**:
  - `SI` para transformar campos como `remote_ratio`
  - `INDICE` y `COINCIDIR` para localizar país con salario máximo y mínimo
  - `MAX` y `MIN` para detectar extremos salariales
  - `PROMEDIO.SI` para calcular medias por condición

---

## Transformación y limpieza de datos
- Se creó una variable `type_modality` a partir de `remote_ratio`
- Se normalizaron los niveles de experiencia y tipo de empleo
- Se creó una variable de comparación entre país del empleado y país de la empresa
- Se agregó una columna para salario mensual calculado desde `salary_in_usd`
- Se filtraron los datos por año y experiencia para identificar extremos salariales

---

## Proceso seguido para la construcción del dashboard
1. En primer lugar, se seleccionó una fuente de datos sencilla y conocida (dataset de Kaggle).
2. Se diseñaron inicialmente tres KPIs base que sirvieron como guía para comenzar a construir el dashboard.
3. El resto de los KPIs surgieron de forma progresiva, en función de las conclusiones visuales y gráficas que se iban obteniendo.
4. El proceso para cada KPI ha sido consistente:
   - Interpretación directa del dataset
   - Análisis del valor que puede aportar cada columna
   - Cruce de variables según lógica de negocio o patrón observable
   - Creación de una tabla dinámica adaptada
   - Aplicación de fórmulas auxiliares si era necesario
   - Diseño del gráfico correspondiente y extracción de conclusiones
5. Según mi experiencia, la mayor dificultad ha sido definir correctamente los KPIs. No por la parte técnica, sino por la parte conceptual: tener un objetivo claro y medible sobre el que construir cada visualización.
6. Una vez definido el KPI, trabajar con los datos ha sido mucho más fluido y sistemático.

---

## Análisis descriptivo (KPIs)

### 🔶 KPI 1 – Modalidad de trabajo en el sector tech

1. **Distribución Global (2020–2024)**
   - Gráfico circular que muestra que el 66,3% de los trabajadores trabajan en modalidad on-site

2. **Tendencia anual por modalidad (2020–2024)**
   - Gráfico de líneas con evolución de trabajo remoto, híbrido y presencial

3. **Relación con tamaño de empresa**
   - Gráfico de burbujas: las empresas medianas concentran el 93,8% de la modalidad presencial

---

### 🔶 KPI 2 – Salario y experiencia profesional

4. **Comparativa de salario medio por experiencia (2020 vs 2024)**
   - Gráfico de columnas que muestra clara progresión de salario desde Junior a Senior

5. **País mejor pagador a Juniors (2020–2024)**
   - Tarjeta visual que destaca que `US` tiene el salario medio más alto para perfiles Junior: 107.703,63 USD

6. **País peor pagador a Juniors (2020–2024)**
   - Tarjeta visual que destaca que `RO` tiene el salario medio más bajo: 26.000 USD

---

### 🔶 KPI 3 – Jornada laboral y divisa

7. **Comparativa de salario mensual por tipo de jornada y moneda**
   - Gráfico radar que compara `Full-time`, `Part-time` y `Otro` en divisas como `USD`, `EUR`, `GBP`, `CAD`
   - Se observan diferencias claras en retribución mensual entre monedas

---

## Conclusiones
- La presencialidad sigue siendo dominante, impulsada principalmente por empresas medianas
- El salario medio crece significativamente con el nivel de experiencia, especialmente entre perfiles Senior
- Las diferencias por moneda y tipo de jornada muestran brechas relevantes en la retribución según ubicación o condiciones laborales

---

## Acceso al dashboard
- https://docs.google.com/spreadsheets/d/1o_wwuJYMVcMho8WRNHhP61Ng2oaePybhxCkofsn0opE/edit?usp=sharing
