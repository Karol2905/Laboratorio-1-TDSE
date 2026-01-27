
---

# 🌟 Stellar Luminosity Regression from First Principles

## Descripción del proyecto

Este laboratorio explora la relación entre las propiedades físicas de las estrellas y su luminosidad utilizando técnicas de aprendizaje automático implementadas desde primeros principios. A partir de datos simplificados de masa estelar y temperatura efectiva, se construyen modelos de regresión que permiten aproximar cómo varía la luminosidad en estrellas de la secuencia principal.

El proyecto se centra en comprender el funcionamiento interno de los modelos de regresión, evitando el uso de librerías de machine learning de alto nivel. En su lugar, se implementan explícitamente la función de predicción, la función de pérdida, el cálculo de gradientes y el algoritmo de descenso por gradiente, con el fin de reforzar la intuición matemática y computacional detrás del entrenamiento de modelos.

Además de la ejecución local, los notebooks se ejecutan en AWS SageMaker para demostrar la portabilidad del código y su correcta operación en un entorno de computación en la nube. Este enfoque conecta el aprendizaje automático con conceptos de arquitectura empresarial y transformación digital, donde los modelos inteligentes son tratados como componentes fundamentales dentro de sistemas modernos.

---

## Prerequisitos

Antes de ejecutar los notebooks, se requiere:

* Python 3.9 o superior
* Jupyter Notebook o JupyterLab

---
### Librerías requeridas

* NumPy
* Matplotlib


---

## Instalación

A continuación se describe cómo configurar el entorno de desarrollo.

### Paso 1: Clonar el repositorio

git clone <https://github.com/Karol2905/Laboratorio-1-TDSE>
cd <Laboratorio-1-TDSE>

### Paso 2: Crear un entorno virtual 

python -m venv venv
source venv/bin/activate   (Linux / macOS)
venv\Scripts\activate      (Windows)

### Paso 3: Iniciar Jupyter Notebook

jupyter notebook

---

## Uso del proyecto

La estructura del repositorio es:

/
├── README.md

├── 01_part1_linreg_1feature.ipynb

└── 02_part2_polyreg.ipynb

### Notebooks

**01_part1_linreg_1feature.ipynb**
Implementa regresión lineal con una sola característica (masa estelar). Incluye visualización del dataset, superficie de costo, gradientes, descenso por gradiente y análisis de convergencia.

**02_part2_polyreg.ipynb**
Implementa regresión polinómica con múltiples características e interacción masa–temperatura. Incluye ingeniería de características, selección de modelos, análisis del término de interacción y demostración de inferencia.

Al ejecutar los notebooks se obtienen visualizaciones de los datos, gráficas de convergencia, comparaciones entre modelos y predicciones para nuevas estrellas.

---

## Evidencia de ejecución AWS SageMaker 

### Ejecución en SageMaker

 Lo primero que debemos realizar es abrir el espacio de codigo previamente creado.


 ![Texto alternativo](images/Captura%20de%20pantalla%20de%202026-01-27%2000-43-55.png)

Luego los notebooks fueron cargados manualmente en **AWS SageMaker Studio** utilizando la interfaz web, solo arrastrando los notebooks.

![Texto alternativo](images/Captura%20de%20pantalla%20de%202026-01-27%2000-51-17.png)


Despues de cargarlos, seleccionamos un kernel compatible y ejecutamos los cuadernos.
---

### Evidencia
---

## Notebook 1

![Texto alternativo](images/Captura%20de%20pantalla%20de%202026-01-27%2000-51-25.png)
![Texto alternativo](images/Captura%20de%20pantalla%20de%202026-01-27%2000-51-33.png)
![Texto alternativo](images/Captura%20de%20pantalla%20de%202026-01-27%2000-51-51.png)

---
## Notebook 2
![Texto alternativo](images/Captura%20de%20pantalla%20de%202026-01-27%2000-53-35.png)
![Texto alternativo](images/Captura%20de%20pantalla%20de%202026-01-27%2000-53-30.png)
![Texto alternativo](images/Captura%20de%20pantalla%20de%202026-01-27%2000-53-45.png)
![Texto alternativo](images/Captura%20de%20pantalla%20de%202026-01-27%2000-53-52.png)
![Texto alternativo](images/Captura%20de%20pantalla%20de%202026-01-27%2000-54-17.png)

---
### Comparación entre ejecución local y en la nube

No pude observar diferencias, no hubo ningun problema ejecutandolo en la nube, fue muy sencillo e igual que ejecutarlo localmente.

---

## Tecnologías usadas

* Python – Lenguaje principal
* NumPy – Cálculo numérico y vectorización
* Matplotlib – Visualización de datos
* Jupyter Notebook – Entorno interactivo
* AWS SageMaker – Ejecución en la nube

---

## Autores

Karol Estupiñan 

---



