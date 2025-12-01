# Curso de Análisis de Datos con Python

¡Bienvenido! Este repositorio contiene una serie de notebooks de Jupyter diseñados para un curso práctico de análisis de datos utilizando Python. El objetivo es guiar a los usuarios desde los conceptos estadísticos fundamentales hasta la creación de modelos de machine learning como la regresión lineal.

## 📜 Descripción

A través de ejemplos prácticos y explicaciones detalladas, este curso te enseñará a:
- Calcular e interpretar las principales medidas estadísticas.
- Realizar pruebas de hipótesis para entender la distribución de tus datos.
- Analizar la correlación entre variables.
- Preprocesar datos para modelos de machine learning.
- Entrenar, evaluar y visualizar modelos de regresión lineal simple y múltiple.

## 📚 Contenido del Curso

El curso está estructurado en los siguientes notebooks, que avanzan en complejidad:

1.  **`estadisticas_descriptivas.ipynb`**
    - **Nivel:** Intermedio
    - **Conceptos:**
        - Medidas de tendencia central: Media, Mediana, Moda.
        - Medidas de dispersión: Varianza y Desviación Estándar.
        - Tests de Normalidad: Shapiro-Wilk y D'Agostino-Pearson.
        - Correlación no paramétrica: Spearman y Kendall.
        - Normalización de datos (Min-Max Scaling).

2.  **`analisis_estadistico_dataframe.ipynb`**
    - **Nivel:** Intermedio
    - **Conceptos:**
        - Aplicación de todos los conceptos del notebook anterior directamente sobre un **DataFrame de Pandas**.
        - Creación de un conjunto de datos simulado.
        - Análisis y visualización de estadísticas por columna.
        - Cálculo de matrices de correlación (Pearson, Spearman, Kendall) y su visualización con heatmaps.

3.  **`regresion_lineal_completa.ipynb`**
    - **Nivel:** Intermedio-Avanzado
    - **Conceptos:**
        - **Regresión Lineal Simple y Múltiple**.
        - Análisis exploratorio de datos (EDA) con gráficas de distribución y correlación.
        - División de datos en conjuntos de **entrenamiento y prueba** (`train_test_split`).
        - Entrenamiento de modelos con `scikit-learn`.
        - Visualización de las líneas de regresión y de los resultados del modelo.
        - **Métricas de evaluación** para regresión: R-cuadrado (R²), MAE, MSE y RMSE.
        - Realización de predicciones sobre nuevos datos.

## 🛠️ Tecnologías Utilizadas

- **Python 3**
- **Jupyter Notebook**
- **Pandas:** Para la manipulación y análisis de datos.
- **NumPy:** Para operaciones numéricas.
- **SciPy:** Para cálculos estadísticos avanzados y tests.
- **Matplotlib & Seaborn:** Para la visualización de datos.
- **Scikit-learn:** Para el preprocesamiento de datos y la creación de modelos de machine learning.

## 🚀 Instalación y Uso

Para ejecutar estos notebooks en tu máquina local, sigue estos pasos:

1.  **Clona el repositorio:**
    ```bash
    git clone https://github.com/jaquimbayoc7/CursoAnalisisDatosPython.git
    ```

2.  **Navega al directorio del proyecto:**
    ```bash
    cd CursoAnalisisDatosPython
    ```

3.  **Crea un entorno virtual (recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # En Windows: venv\Scripts\activate
    ```

4.  **Instala las dependencias:**
    ```bash
    pip install -r requirements.txt
    ```
    *(Nota: Deberás crear un archivo `requirements.txt` con las librerías listadas en la sección de tecnologías).*

5.  **Inicia Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
    Se abrirá una pestaña en tu navegador donde podrás seleccionar y ejecutar los notebooks del curso.

## 🤝 Cómo Contribuir

Las contribuciones son bienvenidas. Si tienes ideas para mejorar los notebooks, corregir errores o añadir nuevos ejemplos, por favor, abre un *issue* para discutirlo o envía un *pull request*.

## 👨‍💻 Autor

- **[jaquimbayoc7](https://github.com/jaquimbayoc7)**
