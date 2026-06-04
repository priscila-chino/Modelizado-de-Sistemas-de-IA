# 🧠 Modelizado de Sistemas de IA

Este repositorio contiene los trabajos prácticos desarrollados para la materia **Modelizado de Sistemas de IA** correspondientes a la **Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial** (IFTS N° 33). 

El objetivo de este módulo es explorar los diferentes paradigmas de resolución de problemas mediante Inteligencia Artificial, abarcando desde los enfoques lógicos-simbólicos y heurísticos tradicionales hasta el diseño, entrenamiento y evaluación de Arquitecturas de Redes Neuronales Artificiales profundas mediante **Keras** y **TensorFlow**.

---

## 📂 Estructura de Prácticas y Contenidos

### 🏛️ 1. Sistemas Expertos y Problemas de Satisfacción de Restricciones (CSP)
* **Archivo:** `Practica_N°1_Sistemas Expertos.ipynb`
* **Tecnologías:** `experta`, `python-constraint`
* **Descripción:** Implementación de un enfoque de IA clásica enfocado en la gestión inteligente de obras civiles. Desarrolla un **motor de inferencia reactivo** basado en reglas lógicas para la evaluación de riesgos estructurales y climáticos a partir de sensores, junto con un resolvedor de **Sistemas de Satisfacción de Restricciones (CSP)** para la asignación y distribución óptima y segura de maquinaria pesada en el predio.

### 🧬 2. Optimización Heurística mediante Algoritmos Genéticos
* **Archivo:** `Practica_N°2_Algoritmos_Genéticos.ipynb`
* **Tecnologías:** `pygad`, `numpy`, `matplotlib`
* **Descripción:** Resolución de un problema de secuenciación y planificación de tareas concurrentes de carácter *NP-Hard* (Optimización del Cronograma de una Vivienda). Se modeló un espacio de búsqueda evolutivo donde la **función de aptitud (fitness function)** penaliza la sobreasignación de recursos críticos (límite estricto de operarios en cuadrilla) y busca minimizar activamente el tiempo total de finalización de la obra (*Makespan*).

### 📐 3. Clasificación Lineal con Perceptrón Simple
* **Archivo:** `Practica_N°3_ Perceptrón_simple.ipynb`
* **Tecnologías:** `keras`, `tensorflow`, `scikit-learn`
* **Descripción:** Introducción al aprendizaje profundo mediante la implementación del Perceptrón de Rosenblatt para la automatización del **Riesgo Crediticio bancario**. Estudio detallado de la normalización de características de entrada, aplicación de la función de activación exponencial *Sigmoide* y visualización geométrica del hiperplano o frontera de decisión lineal encargada de separar las categorías de riesgo.

### 🧥 4. Redes Neuronales Multicapa (MLP) - Clasificación Multiclase
* **Archivo:** `Practica_N°4_RRNN_multicapa.ipynb`
* **Tecnologías:** `keras`, `tensorflow`, `Fashion MNIST Dataset`
* **Descripción:** Diseño y entrenamiento de un Perceptrón Multicapa (MLP) profundo enfocado en Visión por Computadora para clasificar imágenes de baja resolución de prendas de vestir en 10 categorías discretas. Implementa técnicas de aplanamiento de tensores (`Flatten`), activación **ReLU** en capas ocultas para evitar el desvanecimiento del gradiente, y una capa de salida con **Softmax** combinada con `sparse_categorical_crossentropy` para la inferencia probabilística multiclase.

### 🚢 5. Clasificación Binaria Avanzada y Diagnóstico (Caso Titanic)
* **Archivo:** `Practica N° 5  Clasificación Binaria con Redes Neuronales .ipynb`
* **Tecnologías:** `pandas`, `keras`, `tensorflow`, `scikit-learn`
* **Descripción:** Modelado predictivo de extremo a extremo (*End-to-End*) sobre datos tabulares para resolver la supervivencia de los pasajeros del Titanic. El proyecto incluye fases críticas de ingeniería de características, codificación de variables categóricas, imputación de nulos y un análisis exhaustivo del rendimiento del clasificador mediante métricas de diagnóstico industrial: **Matriz de Confusión, Precisión, Exhaustividad (Recall) y F1-Score**.

---

## 🛠️ Requisitos e Instalación

Para ejecutar estos cuadernos de forma local, asegúrate de contar con Python 3.10+ e instalar las dependencias necesarias:

```bash
pip install tensorflow keras pandas numpy scikit-learn matplotlib pygad python-constraint experta
