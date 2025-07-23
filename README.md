# 📉 Customer Churn Analysis - Telecom Dataset

Este proyecto realiza un análisis exploratorio y visual del abandono de clientes (churn) en una compañía de telecomunicaciones. Se identifican patrones de comportamiento y variables clave asociadas a la evasión de clientes, con el objetivo de generar insights valiosos para estrategias de retención.

## 📁 Dataset

- Nombre: `df_normalizado_final.csv`
- Total de registros: **7,043 clientes**
- Fuente: Dataset provisto para prácticas de análisis de churn en empresas de telecomunicaciones.
- Variables: Datos demográficos, servicios contratados, tipo de contrato, método de pago, cargos mensuales, permanencia en la empresa, y variable de churn (abandono).

## 🧠 Objetivo

Identificar características comunes en los clientes que abandonan la empresa y generar recomendaciones basadas en datos que permitan reducir la tasa de churn.

## 📌 Principales hallazgos

- **Tasa general de evasión:** 26.5%
- **Contratos mensuales** concentran el mayor número de evasores.
- Clientes que **pagan con cheque electrónico** y **presentan cargos mensuales elevados** tienden a abandonar más.
- El **primer mes** es crítico: 61.99% de churn.
- **Clientes de largo plazo (72 meses)** tienen una tasa de evasión casi nula (1.65%).
- Los clientes que abandonan tienen **cargos mensuales más altos en promedio**, según análisis con boxplots.

## 📊 Visualizaciones destacadas

- Boxplot comparativo de cargos mensuales por grupo (evasores vs no evasores).
- Gráficos de barras de métodos de pago, tipos de contrato y distribución de edad.
- Línea temporal de churn por mes de antigüedad.
- Matriz de correlaciones (heatmap) para identificar relaciones entre variables numéricas.

## 🧪 Herramientas utilizadas

- `Python`
- `Pandas`
- `Plotly`
- `Matplotlib`
- `Google Colab`

## 📂 Estructura del proyecto

Telecom_X_MC/
- `Telecom_X_MC.ipynb` # Notebook con el análisis completo
- `df_normalizado_final.csv` # Dataset limpio y procesado
- `README.md` # Este archivo

## 📎 Recomendaciones generales

1. Diseñar un programa sólido de bienvenida y acompañamiento en los **primeros 3 meses**.
2. Fomentar migración a **contratos anuales o bianuales** mediante incentivos.
3. Revisar la estructura de precios y la percepción de valor de los clientes con **cargos altos**.
4. Detectar clientes con métodos de pago propensos a churn y segmentarlos para acciones específicas.

## 📬 Contacto

Proyecto desarrollado por **Miguel Castillo**  
Contacto profesional: [LinkedIn](https://www.linkedin.com/miguelct89)

---

> Este análisis forma parte de un portafolio de proyectos de ciencia de datos con enfoque en negocios y experiencia del cliente
