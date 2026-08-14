# Machine Learning Algorithms

Repositorio de actividades, prácticas y ejercicios de la materia **Algoritmos de Aprendizaje Automático**.

El objetivo del repositorio es documentar de forma progresiva los conceptos vistos durante el curso y su implementación práctica en Python, principalmente utilizando `pandas`, `NumPy` y `scikit-learn`.

---
#### Práctica Tema 1

[`Practica 1.ipynb`](./Tema1.ipynb)
[`GoogleCollab-1`](./https://colab.research.google.com/drive/1o1sr76Z26OvY6fHh6VX3A5ibOzRaZUat?usp=sharing)

Implementación práctica utilizando el dataset del Titanic:

1. Autopsia del dataset.
2. Limpieza e imputación.
3. Transformación y representación de variables.
4. Pipeline integrado para prevención de fugas de información.

---
#### Práctica Tema 2

[`Practica 2.ipynb`](./Tema2.ipynb)  
[`GoogleCollab-2`](https://colab.research.google.com/drive/1UNP8uvDUXwRvDFoqcpjPKSJ6i3G4Dm1M?usp=sharing)

Experimento de validación utilizando el dataset de diagnóstico de cáncer de mama de Scikit-Learn:

1. División de datos en entrenamiento y prueba.
2. Configuración de validación cruzada K-Fold.
3. Evaluación con regresión logística.
4. Comparación de exactitud entre folds.
5. Análisis de media y desviación estándar para determinar la estabilidad del modelo.
6. Uso de escalado de datos para mejorar la convergencia del modelo.

---

# Práctica Tema 3

[`Practica 3.ipynb`]
(./Practica%20Tema%203.ipynb) [Open in Google Colab](https://colab.research.google.com/github/1816x/Algoritmos-Aprendizaje-Automatico/blob/main/Practica%20Tema%203.ipynb) 

Experimento de muestreo y representatividad utilizando el dataset de diagnóstico de cáncer de mama de Scikit-Learn: 
1. Análisis de la distribución original de las clases.
2. Generación de diferentes particiones mediante muestreo aleatorio simple.
3. Comparación de distintos valores de `test_size` y `random_state`.
4. Identificación del escenario con mayor distorsión respecto a la distribución original.
5. Visualización gráfica de las diferencias entre los experimentos.
6. Aplicación de muestreo estratificado utilizando `stratify=y`.
7. Comparación entre la distribución original, el muestreo aleatorio y el muestreo estratificado.
8. Análisis del impacto del tamaño de muestra sobre la representatividad de los datos.


Este repositorio se irá actualizando conforme avance el curso.
