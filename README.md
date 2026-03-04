<h1 align="center"> 📊 Challenge — Alura: Telecom X – Análisis de Evasión de Clientes (Churn) </h1>

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-ffffff?style=for-the-badge&logo=python&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-4C4C4C?style=for-the-badge&logo=python&logoColor=white)

</div>

---

## 📋 Tabla de contenidos
1. [📖 Descripción](#-descripción)
2. [🏁 Estado del proyecto](#-estado-del-proyecto)
3. [⚙️ Desarrollo del proyecto](#️-desarrollo-del-proyecto)
4. [✅ Tecnologías utilizadas](#-tecnologías-utilizadas)
5. [📊 Resultados destacados](#-resultados-destacados)
6. [📈 Conclusiones](#-conclusiones)
7. [👤 Autor](#-autor)


## 📖 Descripción

Este proyecto desarrolla un análisis exhaustivo sobre la evasión de clientes (churn) en la empresa Telecom X. Mediante un enfoque de ciencia de datos, no solo se identificó qué usuarios cancelan el servicio, sino también los factores operativos y conductuales que influyen en su decisión de abandono.

---

## 🏁 Estado del proyecto
✅ **Proyecto finalizado**  

---

## ⚙️ Desarrollo del proyecto

1.  **ETL y Limpieza:** 
Extracción desde API JSON, aplanamiento de datos anidados y corrección de errores de formato en cargos financieros.
2.  **Ingeniería de Datos:** 
Traducción total al español y creación de métricas personalizadas como el gasto diario y perfiles de hogar.
3.  **Visualizaciones:** 
Diseñadas para identificar estructuras repetitivas y señales predictivas
4. **Análisis Exploratorio de Datos (EDA):**
Ejecutar un análisis exploratorio y documentar los principales insights obtenidos.
5.  **Análisis Multivariable:** 
Cruce de factores demográficos con métodos de pago y niveles de soporte técnico.

---
## ✅ Tecnologías utilizadas

### 💬 Lenguaje
- **Python 3.12.12**

### 📚 Librerías principales
- `pandas`
- `numpy`
- `matplotlib`
- `Seaborn`

### 🧩 Entorno de desarrollo
- **Google Colab**

---

## 📊 Resultados destacados

Limpieza y tratamientos de Datos

- Se realizó la carga de archivo JSON desde API
- Dado que el archivo JSON poseía información anidada, se realizó la normalización para acceder a todas las columnas
- Se realizó una revisión inicial de los datos, que incorporaba mirar el DataFrame, conocer sus columnas y el tipo de dato que almacenaban, revisar los datos únicos, duplicados, nulos y vacíos.
- Se realizó una modificación de los tipos de datos donde correspondían, y una nueva limpieza de datos para eliminar todo dato que pudiera restar valor del análisis.
- Se incorporó una columna para costo diario

Análisis exploratorio de Datos

- Se realizó una exploración inicial del dataset utilizando el método .describe() tanto para variables numéricas como categóricas, con el objetivo de obtener una primera aproximación a la estructura y comportamiento de los datos.
- Posteriormente, el análisis se centró en la variable objetivo Churn. Se identificó que aproximadamente el 26.6% de los clientes de Telecom X han cancelado el servicio, lo que representa un nivel de evasión considerable.
- Al analizar la evasión según género, no se observan diferencias significativas entre hombres y mujeres, lo que sugiere que esta variable no parece ser un factor determinante en la cancelación del servicio. *En cuanto al tipo de contrato, se detecta una concentración notable de evasión en clientes con contrato mensual. Esto indica que, a menor plazo de permanencia contractual, mayor es la probabilidad de cancelación.
- Respecto al método de pago, se observa una mayor proporción de churn en clientes que utilizan cheque electrónico, lo que podría estar asociado a perfiles con menor nivel de compromiso o estabilidad en el servicio.
- Al analizar el tipo de internet, se identifica una mayor concentración de cancelaciones en usuarios con fibra óptica, lo que sugiere la necesidad de profundizar en posibles factores asociados a este segmento.
- El análisis por tiempo de permanencia (tenure) muestra un patrón claro: la mayoría de las cancelaciones se concentran en clientes con pocos meses de antigüedad. Esto indica que el riesgo de evasión es más alto en las primeras etapas del ciclo de vida del cliente.
- De manera similar, al revisar el gasto total acumulado, se observa que aproximadamente el 50% de las cancelaciones corresponden a clientes con un gasto total igual o inferior a 500, lo cual está directamente relacionado con una menor permanencia en la empresa.
- Finalmente, se identifica un patrón combinado entre el tipo de contrato y el tipo de internet, lo que sugiere que la interacción entre variables podría estar influyendo en la probabilidad de evasión.

---

## 📈 Conclusiones

El análisis de evasión de clientes en Telecom X muestra que el churn no se distribuye de manera aleatoria, sino que sigue patrones claros asociados principalmente al nivel de compromiso contractual y al tiempo de permanencia. La tasa general de evasión (26.6%) es relevante y representa una oportunidad importante de mejora en retención.

Los principales hallazgos indican que:

- El género no es un factor determinante en la cancelación del servicio.
- Los clientes con contrato mensual presentan la mayor probabilidad de evasión, lo que sugiere que la flexibilidad contractual reduce el compromiso.
- Existe una alta concentración de churn en clientes con pocos meses de permanencia, lo que indica que el riesgo es mayor en las primeras etapas del ciclo de vida.
- Los clientes con menor gasto acumulado (≤ 500) concentran aproximadamente la mitad de las cancelaciones, reforzando la relación entre baja antigüedad y mayor riesgo. *El cheque electrónico como método de pago muestra mayor proporción de evasión.
- Se observa un patrón entre tipo de contrato y tipo de internet, lo que sugiere que ciertas combinaciones podrían estar elevando el riesgo de cancelación.
- En conjunto, los resultados indican que el churn está más relacionado con el nivel de compromiso y la etapa temprana del cliente que con variables demográficas.

---
## 👤 Autor

**[Adriana Flores](https://github.com/addyfloe)**  
📅 Año: 2026  
📍 Proyecto educativo — *Análisis de Evasión de Clientes (Churn)*  
