# Geo-Enhanced-price-prediction
# 🏠 Predicción de Precios de Vivienda Geo-Mejorada en California

Este repositorio contiene el proyecto desarrollado durante el bootcamp Xpirience, enfocado en la predicción de precios de vivienda en California utilizando técnicas de aprendizaje automático y análisis geoespacial. El objetivo principal es demostrar cómo la incorporación de datos geográficos puede mejorar significativamente la precisión de los modelos predictivos.

## 🌟 Características Principales

  * **Análisis Exploratorio de Datos (EDA) Geoespacial:** Visualizaciones interactivas de la distribución de viviendas y precios en el estado de California.
  * **Ingeniería de Características Geo-Mejoradas:** Creación de nuevas características a partir de datos geográficos (e.g., densidad de población, proximidad a puntos de interés, características del distrito).
  * **Modelado Predictivo con XGBoost:** Implementación de un modelo de regresión robusto para predecir los precios de las viviendas.
  * **Visualización de Resultados en un Mapa Interactivo:** Presentación de las predicciones del modelo y la distribución de errores en un mapa utilizando Folium.
  * **Integración de Datos Climáticos:** Incorporación de información de temperaturas promedio para analizar su impacto en los precios de vivienda.

## 🚀 Tecnologías Utilizadas

  * **Python:** Lenguaje de programación principal.
  * **Pandas & NumPy:** Manipulación y análisis de datos.
  * **Matplotlib & Seaborn:** Visualización de datos estática.
  * **Folium & Geopandas:** Visualización y análisis de datos geoespaciales interactivos.
  * **XGBoost:** Algoritmo de Machine Learning para la predicción de precios.
  * **Scikit-learn:** Herramientas para la preparación de datos y evaluación del modelo.
  * **Requests:** Para obtener datos de APIs externas (e.g., datos climáticos).
  * **Joblib:** Para la serialización y deserialización del modelo.

## 📊 Estructura del Repositorio

  * `Prediccion_precios_vivienda_CA.ipynb`: El Jupyter Notebook principal que contiene todo el código del proyecto, desde la configuración del ambiente hasta las visualizaciones finales y el guardado del modelo.
  * `data/`: (Opcional, se puede crear si los datos se guardan localmente) Carpeta para almacenar los conjuntos de datos utilizados.
  * `models/`: (Opcional) Carpeta para almacenar el modelo entrenado serializado (e.g., `modelo_xgboost.joblib`).
  * `README.md`: Este archivo.

## ⚙️ Cómo Ejecutar el Proyecto

1.  **Clona el Repositorio:**
    ```bash
    git clone https://github.com/tu-usuario/nombre-del-repositorio.git
    cd nombre-del-repositorio
    ```
2.  **Crea un Entorno Virtual (Recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # En Linux/macOS
    # venv\Scripts\activate   # En Windows
    ```
3.  **Instala las Dependencias:**
    ```bash
    pip install pandas numpy matplotlib seaborn folium requests branca-colormap xgboost joblib geopandas scikit-learn shapely
    ```
4.  **Abre el Jupyter Notebook:**
    ```bash
    jupyter notebook Prediccion_precios_vivienda_CA.ipynb
    ```
5.  **Ejecuta las Celdas:** Sigue las instrucciones dentro del notebook para ejecutar cada celda secuencialmente y ver el análisis, el entrenamiento del modelo y las visualizaciones.

## 🗺️ Visualizaciones Clave

El notebook incluye varias visualizaciones interactivas y estáticas para entender mejor los datos y los resultados del modelo:

  * **Mapa de Calor de Precios de Vivienda:** Un mapa Folium que muestra la densidad de precios de vivienda en California.
  * **Mapa de Precios por Valor Medio de Manzana:** Marcadores en el mapa que muestran el valor medio de vivienda por `median_house_value`.
  * **Mapa de Precios Predichos vs. Reales:** Visualización de las predicciones del modelo frente a los valores reales, con el error de predicción codificado por color.

## 🎓 Agradecimientos

Este proyecto fue desarrollado como parte del bootcamp Xpirience, proporcionando una valiosa experiencia práctica en Machine Learning y análisis geoespacial.

-----
