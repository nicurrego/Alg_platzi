# 📐 Álgebra Aplicada con Python: Transformaciones, SVD, Pseudo-inversa y PCA

Este proyecto forma parte de un proceso de **estudio** sobre álgebra lineal aplicada siguiengo el curso de Platzi. Se desarrolla utilizando Python y herramientas de visualización para comprender y experimentar con conceptos fundamentales como transformaciones lineales, descomposición en valores singulares (SVD), pseudo-inversa y análisis de componentes principales (PCA).

El objetivo es construir una base sólida para su aplicación futura en inteligencia artificial, visión por computadora y compresión de datos.

---

## 🧠 Temas abordados

### 🔹 1. Transformaciones lineales en 2D
- Visualización de transformaciones de matrices 2x2 aplicadas a vectores y al círculo unitario.
- Cálculo y representación gráfica de autovalores y autovectores.
- Interpretación geométrica de matrices como operadores de escala, rotación o deformación.

### 🔹 2. Descomposición de matrices
- Descomposición espectral (Eigen decomposition) para matrices cuadradas.
- Descomposición en Valores Singulares (SVD) aplicada a matrices cuadradas y no cuadradas.
- Visualización paso a paso de la factorización: `A = U · Σ · Vᵗ`.

### 🔹 3. Procesamiento de imágenes
- Conversión de imágenes en matrices (escala de grises).
- Normalización y manipulación de intensidad.
- Aplicación de SVD para compresión, observando el efecto de conservar diferentes cantidades de valores singulares.

### 🔹 4. Pseudo-inversa (Moore–Penrose)
- Resolución de sistemas sobredeterminados mediante mínimos cuadrados con `np.linalg.pinv`.
- Visualización gráfica del sistema y la solución aproximada.

### 🔹 5. Análisis de Componentes Principales (PCA)
- Generación de datos correlacionados y visualización de su estructura.
- Centrado de datos y cálculo de la matriz de covarianza.
- Obtención de autovalores y autovectores.
- Proyección de datos sobre componentes principales.
- Aplicación de PCA al dataset Olivetti Faces para visualización y compresión.

---

## 📦 Herramientas utilizadas

- `NumPy`, `Matplotlib` – Cálculo matricial y visualización.
- `PIL`, `imageio` – Manipulación de imágenes.
- `Scikit-learn` – Acceso a datasets y aplicación de PCA.
- Funciones personalizadas como `graficarVectores()` para visualización de vectores.

---

## 🎯 Objetivos cumplidos

- Representar visualmente operaciones de álgebra lineal.
- Aplicar la teoría a problemas reales (imágenes, compresión, sistemas).
- Fortalecer la intuición geométrica de transformaciones, autovectores y componentes principales.
- Consolidar conocimientos en álgebra lineal como base para aplicaciones futuras en inteligencia artificial.

---

## 📁 Contenido

- `alg_aplicada_platzi.py` – Desarrollo principal del proyecto.
- `cute_zebra.png` – Imagen de prueba para procesamiento con SVD.
- `README.md` – Descripción y documentación general.


---

## 👨‍💻 Autor

**Nicolás Urrego**  
Estudiante de HAL Tokyo | Explorador de inteligencia artificial y aplicaciones matemáticas  
📍 Tokio, Japón  
📧 nicurrego@gmail.com  

---

## 📄 Licencia

Este proyecto se encuentra bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.
