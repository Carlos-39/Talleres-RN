# 🧠 Talleres de Redes Neuronales – Universidad del Valle

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

Este repositorio contiene los **tres talleres prácticos** de la asignatura **Redes Neuronales** de la **Universidad del Valle**, desarrollados en equipo por **Carlos Corrales** y **José Manuel Palma**.  
Cada taller explora una faceta distinta del aprendizaje profundo, desde implementaciones desde cero hasta modelos listos para producción.

---

## 📚 Contenido

### 🧩 **Taller 1: Red Neuronal desde cero (NumPy)**
- **Objetivo**: Clasificar carros como "normales" o "coleccionables" usando antigüedad y costo.
- **Enfoque**: Implementación manual de un **perceptrón multicapa** con retropropagación en **NumPy**.
- **Habilidades clave**:
  - Cálculo de gradientes paso a paso.
  - Entrenamiento con tasas de aprendizaje y épocas variables.
  - Visualización de fronteras de decisión.
- **Dataset**: Generado sintéticamente para fines educativos.

---

### 🔁 **Taller 2: RNN vanilla para generación de texto**
- **Objetivo**: Generar nombres de personas y fragmentos de Shakespeare.
- **Enfoque**: Implementación **manual de una RNN recurrente** con:
  - Codificación one-hot.
  - Backpropagation through time (BPTT).
  - AdaGrad para optimización.
  - **Gradient clipping** (con/sin) para estabilidad.
- **Experimentación**:
  - Pruebas con distintos `seq_length`, tamaños de datos y épocas.
  - Comparación de calidad en la generación de texto.
- **Datasets**:
  - `female.txt` (nombres reales de la CMU).
  - `shakespeare.txt` (obras completas).

---

### 📈 **Taller 3: Predicción de series temporales con LSTM y GRU**
- **Objetivo**: Predecir el **precio promedio de una acción** (AA.US) 24h adelante.
- **Enfoque**: Uso de **Keras/TensorFlow** para construir y comparar:
  - Modelo **LSTM** (con/sin `recurrent_dropout`).
  - Modelo **GRU** (versión más ligera y eficiente).
- **Flujo completo**:
  - Carga y visualización de datos bursátiles.
  - Normalización y creación de ventanas temporales.
  - División en entrenamiento/validación/prueba respetando la cronología.
  - Evaluación con **MAE** y análisis visual de predicciones.
- **Dataset**: `aa.us.txt` de Kaggle (precios históricos de acciones).

---

## 🛠️ Tecnologías utilizadas

| Taller | Librerías |
|-------|----------|
| **Taller 1** | `numpy`, `matplotlib` |
| **Taller 2** | `numpy`, `matplotlib` (implementación 100% manual) |
| **Taller 3** | `pandas`, `numpy`, `matplotlib`, `tensorflow`, `keras` |

---

## 👥 Autores
- Carlos Daniel Corrales (2122878)
- José Manuel Palma (2125182)
- Estudiantes de Ingeniería de Sistemas en la Universidad del Valle (Cali, Colombia).
Este proyecto forma parte de la asignatura Redes Neuronales.

---

### 💡 Hecho por [Carlos Corrales](https://github.com/Carlos-39)

Estudiante de **Ingeniería de Sistemas** en la **Universidad del Valle (Cali, Colombia)**  
Apasionado por la **Inteligencia Artificial**, **Ciencia de Datos** y el **desarrollo colaborativo**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=flat)](https://linkedin.com/in/TU_LINKEDIN)
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white&style=flat)](https://github.com/Carlos-39)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white&style=flat)](mailto:TU_CORREO)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF6F00?logo=vercel&logoColor=white&style=flat)](https://TU_PORTAFOLIO)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?logo=instagram&logoColor=white&style=flat)](https://instagram.com/TU_IG)
