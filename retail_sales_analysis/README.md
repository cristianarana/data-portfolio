# 🛍️ Retail Sales Analysis

## 📌 Descripción general

Este proyecto tiene como objetivo analizar datos de ventas minoristas con el fin de identificar patrones de compra, rendimiento de productos y comportamiento de clientes.
El enfoque sigue un flujo completo de **ETL → Análisis exploratorio → Visualización → Insights**, utilizando herramientas de análisis de datos y visualización.

---

## 🎯 Objetivos del proyecto

* Realizar la limpieza y transformación de los datos de ventas.
* Analizar tendencias de consumo, categorías más rentables y desempeño por sucursal.
* Visualizar los resultados mediante gráficos descriptivos y/o dashboard interactivo.
* Obtener insights accionables para la toma de decisiones comerciales.

---

## ⚙️ Tecnologías y librerías utilizadas

* **Python** (Pandas, NumPy, Matplotlib, Seaborn)
* **Jupyter Notebook**
* **Git / GitHub** para control de versiones

---

## 🧠 Etapas del proyecto

### 1️⃣ ETL – Limpieza y preparación de datos

* Eliminación de valores nulos y duplicados
* Conversión de tipos de datos
* Creación de variables derivadas (ej. `Month`, `Revenue_per_Product`)
* Exportación de dataset limpio a `/data/processed`

### 2️⃣ EDA – Análisis exploratorio

* Identificación de los productos más vendidos
* Identificación de tiendas con productos más vendidos
* Análisis temporal de ventas (mensual / semanal)

### 3️⃣ Visualización

* Gráficos de barras, líneas y boxplots para tendencias y comparaciones
* Heatmap de correlación entre variables

### 4️⃣ Conclusiones e insights

* Identificación de patrones de compra por tipo de cliente
* Categorías con mayor rentabilidad y estacionalidad
* Recomendaciones para optimización comercial

---

## 📂 Estructura del proyecto

```
retail-sales-analysis/
├── data/
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   └── 03_summary_reports.ipynb
├── reports/
│   └── insights_summary.md
├── requirements.txt
└── README.md
```

---

## 🚀 Cómo ejecutar el proyecto

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/<tu_usuario>/data-portfolio.git
   cd data-portfolio/retail-sales-analysis
   ```

2. Crear y activar entorno virtual:

   ```bash
   python -m venv venv
   source venv/bin/activate  # En Linux/Mac
   venv\Scripts\activate     # En Windows
   ```

3. Instalar dependencias:

   ```bash
   pip install -r requirements.txt
   ```

4. Abrir los notebooks y ejecutar:

   ```bash
   jupyter notebook
   ```

---

## 📊 Resultados esperados

* Dataset limpio y transformado listo para análisis.
* Visualizaciones descriptivas claras (por categoría, cliente, sucursal, método de pago).
* Dashboard o reporte con conclusiones de negocio.

---

## 📈 Próximos pasos

* Incorporar modelos predictivos simples (por ejemplo, predicción de ventas mensuales).
* Integrar otras fuentes de datos (inventario, clientes, etc.).
* Desarrollar dashboard interactivo final en Power BI o Streamlit.

---

## ✍️ Autor

**Nombre:** Cristian Arana
**Rol:** Analista / Científico de Datos
**LinkedIn:** [linkedin.com/in/cristian-arana](https://linkedin.com/in/cristian-arana)
**GitHub:** [github.com/cristian-arana](https://github.com/cristian-arana)
