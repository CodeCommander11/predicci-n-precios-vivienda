# 🏠 Predicción de Precios de Vivienda en Madrid con Machine Learning

Este proyecto desarrolla un modelo predictivo para estimar el precio de venta de inmuebles residenciales en Madrid, España, utilizando algoritmos de Machine Learning. El objetivo es identificar oportunidades de inversión inmobiliaria mediante análisis de datos.

### 📊 Rendimiento del Modelo
Tras limpiar más de 15,000 registros y eliminar valores atípicos del mercado (outliers), el modelo final arrojó las siguientes métricas en su evaluación:
* **Precisión del Modelo (R² Score):** 86.50% (Alta capacidad explicativa del precio).
* **Error Absoluto Medio (MAE):** ~125,237 € (Influenciado por propiedades de lujo en zonas premium).

### 🛠️ Tecnologías y Herramientas
* **Lenguaje:** Python 3.12
* **Entorno:** Google Colab & Google Drive Integración
* **Librerías Clave:** Pandas, NumPy, Scikit-Learn (RandomForestRegressor)

### 📂 Estructura del Proyecto
* `01_analisis_y_modelo_predictivo.ipynb`: Cuaderno principal con el Análisis Exploratorio de Datos (EDA), limpieza de nulos/outliers, entrenamiento y predicción final.
