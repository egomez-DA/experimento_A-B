# 💡 Validando hipótesis de negocio con pruebas estadísticas

![Estado](https://img.shields.io/badge/Estado-Completado-2ea44f?style=for-the-badge)
![Tipo](https://img.shields.io/badge/Proyecto-Análisis_de_datos-295F98?style=for-the-badge)
![Enfoque](https://img.shields.io/badge/Enfoque-Pruebas_de_hipótesis-295F98?style=for-the-badge)

> Análisis estadístico de un experimento A/B en la página de inicio (landing page) de un ecommerce, para decidir qué versión mejora la tasa de conversión y el valor económico por usuario.

---

## 📌 Contexto y objetivo

El equipo de marketing digital de un **ecommerce** ejecutó un experimento A/B en su landing page, comparando dos versiones (A y B), y necesita una decisión basada en datos sobre cuál implementar.

🎯 **Objetivo:** explorar, validar y analizar estadísticamente el experimento para identificar diferencias significativas entre ambas páginas y traducir los resultados en recomendaciones de negocio.

## ❓ Preguntas clave

1. ¿Qué versión de la página (A o B) genera mayor tasa de conversión?
2. ¿Existe una diferencia significativa en el gasto promedio por usuario convertido entre ambas versiones?
3. ¿La conversión depende de la fuente de tráfico?
4. ¿El tipo de usuario (nuevo o recurrente) influye en la conversión?
5. ¿Qué hallazgos permiten optimizar la estrategia de marketing y el diseño de la landing page?

## 🛠️ Herramientas

![Python](https://img.shields.io/badge/Python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-357ebd?style=for-the-badge&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-357ebd?style=for-the-badge&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-357ebd?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**Habilidades aplicadas:** limpieza de datos · análisis exploratorio · pruebas de hipótesis (t, z y chi-cuadrado) · experimentación A/B · visualización de datos · comunicación de insights

## 🗺️ Flujo del proyecto

1. 📥 **Carga y validación de datos**
2. 🎯 **Comparación de la tasa de conversión** (A vs. B) con prueba z
3. 💰 **Comparación del gasto promedio** (A vs. B) con prueba t
4. 🚦 **Análisis de fuente de tráfico y conversión** con chi-cuadrado
5. 👥 **Análisis de tipo de usuario y conversión** con chi-cuadrado
6. 📈 **Visualización de resultados**
7. 📊 **Insights ejecutivos y recomendaciones**

## 📂 Dataset

| Archivo | Uso |
|---|---|
| `landing_experiment.csv` | Preparación y validación de datos, y análisis del experimento A/B |

## 🔍 Resultados del análisis

### 1. Preparación y calidad de datos
Cargué y validé los datos en un notebook estructurado, claro y reproducible, revisando su calidad antes de cualquier análisis para asegurar la confiabilidad del experimento.

### 2. Tasa de conversión (prueba z)
Comparé la conversión de ambas páginas para determinar cuál es más efectiva.

- 🎯 La conversión de la página **B es 3.38 % mayor** que la de la página A.

### 3. Gasto promedio (prueba t)
Comparé el gasto promedio por usuario para identificar qué página genera más valor.

- 💰 El gasto promedio en la página **B es 7.65 unidades mayor** que en la página A.

### 4. Fuente de tráfico y tipo de usuario (chi-cuadrado)
Analicé si la conversión depende del canal de adquisición y del tipo de usuario.

- 📧 **Email** tiene la mayor tasa de conversión (**14.99 %**).
- 👥 La compra **no depende del tipo de usuario** (nuevo o recurrente).

## ✅ Recomendaciones accionables

1. **Implementar la página B y monitorear su desempeño.** Las pruebas muestran diferencias significativas, pero no explican qué elementos del diseño (contenido, distribución, llamadas a la acción, velocidad de carga) generan la mejora.
2. **Profundizar en el análisis de los canales de adquisición.** No evalué posibles variables de confusión (tipo de dispositivo, horario de acceso o campañas específicas), por lo que futuros análisis deberían incorporarlas para obtener conclusiones más sólidas.


## 📁 Contenido del repositorio

- `S9 Version_Student_Proyecto_Landing_Experiment.ipynb`: notebook principal con limpieza, EDA, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

1. Haz clic en el siguiente botón:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/egomez-DA/experimento_A-B/blob/f12042d3c7687e3208e733f9cc7d2bbdca9ca517/S9%20Version_Student_Proyecto_Landing_Experiment.ipynb)
2. Ejecuta las celdas en orden.
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público, según corresponda.

---

👤 **Autor:** [egomez-DA](https://github.com/egomez-DA) · [LinkedIn](https://linkedin.com/in/erika-gómezle)
