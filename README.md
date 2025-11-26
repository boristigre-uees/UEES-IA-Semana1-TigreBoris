# UEES-IA-Semana1-TigreBoris
# Laboratorio Práctico de IA - Semana 1

## Introducción
Este repositorio contiene el laboratorio práctico de la Semana 1 del curso de Inteligencia Artificial en UEES, enfocado en fundamentos de Python para IA (NumPy, Pandas, visualización, ML básico y Deep Learning intro). El trabajo incluye 4 notebooks en Google Colab, análisis de datasets obligatorios (Titanic, Iris, Boston, Wine, Digits) y automatización de guardado en GitHub.

**Autor**: Boris Tigre  
**Fecha**: 26 de noviembre de 2025  
**Curso**: UEES - IA Semana 1  
**Repositorio**: [github.com/boristigre-uees/UEES-IA-Semana1-TigreBoris](https://github.com/boristigre-uees/UEES-IA-Semana1-TigreBoris)

## Estructura del Repositorio
- **02_Laboratorio/notebooks/**: Los 4 notebooks principales (.ipynb):
  - 01_Fundamentos_NumPy_Pandas.ipynb: Manipulación de arrays y DataFrames con Iris.
  - 02_Visualizacion_Datos.ipynb: Gráficos con Matplotlib, Seaborn y Plotly.
  - 03_Machine_Learning_Basico.ipynb: Clasificación y regresión con Scikit-learn.
  - 04_Deep_Learning_Intro.ipynb: Red neuronal simple con TensorFlow/Keras.
- **02_Laboratorio/images/**: Imágenes generadas (histogramas, pairplots, curvas de entrenamiento, etc.).
- **requirements.txt**: Dependencias usadas (instala con `pip install -r requirements.txt`).
- **README.md**: Este archivo con detalles del proyecto.

## Instrucciones para Reproducir
1. Clona el repo: `git clone https://github.com/boristigre-uees/UEES-IA-Semana1-TigreBoris.git`.
2. Instala dependencias: `pip install -r requirements.txt`.
3. Abre los notebooks en Google Colab o Jupyter: `jupyter notebook`.
4. Ejecuta las celdas en orden (configuración inicial primero).
5. Para datasets: Se cargan automáticamente con Seaborn/Sklearn (no necesitas descargar).

## Datasets Usados
- **Titanic**: Supervivencia (clasificación binaria).
- **Iris**: Clasificación multiclase.
- **Boston Housing**: Regresión (original de StatLib).
- **Wine**: Clasificación de vinos (UCI ML Repository).
- **Digits**: Reconocimiento de dígitos (UCI ML Repository).

## Herramientas y Librerías
- Python 3.10+.
- Dependencias en `requirements.txt`.
- Entorno: Google Colab (GPU para Deep Learning).

## Imágenes Generadas
Las visualizaciones (histogramas, pairplots, curvas de entrenamiento) se guardan en `/02_Laboratorio/images/`. Ejemplos:
- iris_pairplot.png: Matriz de scatterplots de Iris.
- training_curves.png: Curvas de precisión/pérdida en Deep Learning.

## Notas
- GPU en Colab: Cambia a "GPU" en Entorno de ejecución para acelerar ML.
- Errores comunes: Asegúrate de ejecutar la configuración inicial en cada notebook.
- Automatización: La función `save_to_github` al final de cada notebook sube cambios a GitHub.

## Link del Repositorio
[github.com/boristigre-uees/UEES-IA-Semana1-TigreBoris](https://github.com/boristigre-uees/UEES-IA-Semana1-TigreBoris)

¡Gracias por revisar! Si tienes preguntas, contacta a boris.tigre@uees.edu.ec.
