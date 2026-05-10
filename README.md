# Detección Adaptativa de Carriles en Condiciones de Iluminación Variables

Este repositorio contiene el desarrollo de un sistema de visión artificial diseñado para la detección de carriles en carreteras, con un enfoque especial en la robustez frente a cambios en las condiciones lumínicas (día, noche, sombras y deslumbramientos).

El proyecto implementa un pipeline de procesamiento de imágenes que utiliza técnicas de visión clásica y algoritmos adaptativos para garantizar la seguridad en sistemas de asistencia al conductor (ADAS).

## 📊 Bases de Datos Utilizadas

Para el desarrollo y validación del sistema se emplearon los siguientes conjuntos de datos:

* **BD TuSimple:** [Enlace a Kaggle](https://www.kaggle.com/datasets/manideep1108/tusimple) - Dataset estándar para detección de carriles en autopistas de día.

* **BD Nocturna:** [Enlace a Google Drive](https://drive.google.com/file/d/1b54L_Ta7zrzN5_M-EcD4u4myCi5wZNoX/view?usp=drive_link) - Dataset específico con condiciones de baja iluminación.

## 📂 Estructura del Repositorio

El proyecto se organiza en las siguientes carpetas:

### 1. 💻 Codigo
Contiene los cuadernos de Jupyter con el desarrollo técnico:

* `NooteBook_Pipeline.ipynb`: Implementación del pipeline inicial de procesamiento.
* `Transformada Probabilística.ipynb`: Explicación y aplicación de la Transformada de Hough Probabilística.
* `Transformada de Hough.ipynb`: Notebook explicativo sobre la Transformada de Hough Estándar.
* `Validación y experimentacion.ipynb`: Análisis comparativo de resultados y experimentacion con algoritmos.

### 2. 📄 Document
Contiene la documentación oficial y material de apoyo:

* `Sistema_adaptativo_de_detección_de_carriles_bajo_condiciones_variables_de_iluminación.pdf`: Documentacion del estudio.
* `Presentacion-PID-G9.ppt`: Presentación utilizada para la sustentación del proyecto.

## 📚 Referencia Bibliográfica

Este trabajo se apoya en investigaciones recientes sobre robustez en visión artificial:

* Mohamed Abdelaal, H. M. A., Connie, T., & Goh, M. K. O. (2025). **Robust Lane Detection under Varying Lighting Conditions Using Adaptive Vision-Based Techniques**. *Journal of Informatics and Web Engineering*, 4(3), 336–355. [https://doi.org/10.33093/jiwe.2025.4.3.20](https://doi.org/10.33093/jiwe.2025.4.3.20)

---
*Este proyecto fue desarrollado como parte de un Trabajo Dirigido enfocado en Procesamiento Digital de Imágenes.*
