# 📊 Data Science Portfolio

> Portafolio académico de proyectos en Ciencia de Datos, Machine Learning y Deep Learning desarrollados durante mi carrera universitaria.

---

## 🗂️ Estructura del Repositorio

El portafolio está organizado siguiendo el mapa completo de Data Science, desde fundamentos matemáticos hasta aplicaciones de IA avanzadas.

```
Data-Science/
├── 05_MACHINE_LEARNING/
│   └── 05_1_SUPERVISED/
│       └── classification/
├── 06_DEEP_LEARNING/
│   ├── 06_1_ANN/
│   ├── 06_2_CNN/
│   │   └── object_detection/
│   ├── 06_3_RNN/
│   ├── 06_4_AUTOENCODERS/
│   ├── 06_5_GANs/
│   └── 06_6_TRANSFORMERS/
└── 07_AI_APPLICATIONS/
    └── 07_1_NLP/
```

---

## 🤖 Machine Learning — `05_MACHINE_LEARNING`

### Clasificación Supervisada

| # | Notebook | Descripción |
|---|----------|-------------|
| 40 | `churn_evaluacion_tuning.ipynb` | Modelado de churn de clientes: evaluación de modelos, mejora e hiperparametrización |

**Técnicas:** Evaluación de modelos, tuning de hiperparámetros, métricas de clasificación

---

## 🧠 Deep Learning — `06_DEEP_LEARNING`

### 06_1 — Redes Neuronales Artificiales (ANN)

| # | Notebook | Descripción |
|---|----------|-------------|
| 1 | `perceptron.ipynb` | Implementación del perceptrón desde cero |
| 2 | `ann_sklearn_keras_tensorflow.ipynb` | Red neuronal con Scikit-learn, Keras y TensorFlow |
| 3 | `ann_regresion_lineal.ipynb` | Red neuronal básica para regresión lineal |
| 4 | `ann_clasificacion_densa.ipynb` | Clasificación binaria con capas densas |
| 5 | `ann_clasificacion_multiclass.ipynb` | Clasificación multiclase con TensorFlow |
| 6 | `taller_ann_regresion.ipynb` | Taller aplicado: regresión con ANN |
| 7 | `taller_ann_prediccion_gasolina.ipynb` | Predicción del precio de la gasolina con ANN |

**Stack:** TensorFlow · Keras · Scikit-learn · NumPy

---

### 06_2 — Redes Neuronales Convolucionales (CNN)

| # | Notebook | Descripción |
|---|----------|-------------|
| 8 | `cnn_procesamiento_imagenes.ipynb` | Procesamiento digital de imágenes con CNN |
| 9 | `cnn_intro_redes_convolucionales.ipynb` | Introducción a las redes convolucionales |
| 10 | `cnn_transfer_learning.ipynb` | Transfer learning con modelos preentrenados |
| 11 | `cnn_numeros_modo1_denso.ipynb` | Clasificación de dígitos — Modo 1: red densa |
| 12 | `cnn_numeros_modo2_rnc.ipynb` | Clasificación de dígitos — Modo 2: red convolucional |
| 13 | `cnn_numeros_modo3_augmentation_dropout.ipynb` | Clasificación de dígitos — Modo 3: augmentation y dropout |
| 14 | `taller_cnn_clasificacion_imagenes.ipynb` | Taller aplicado: clasificación de imágenes |
| 17 | `cnn_matriculas_vehiculos.ipynb` | Reconocimiento de matrículas vehiculares |
| 18 | `cnn_clasificacion_mnist.ipynb` | Clasificación del dataset MNIST |
| 19 | `cnn_clasificacion_perros_gatos.ipynb` | Clasificación binaria: perros vs gatos |

#### Object Detection

| # | Notebook | Descripción |
|---|----------|-------------|
| 15 | `yolov8_deteccion_objetos.ipynb` | Detección de objetos con YOLOv8 |
| 16 | `yolov8_ppe_transfer_learning.ipynb` | Detección de EPP (equipos de protección) con YOLOv8 + Transfer Learning |

**Stack:** TensorFlow · Keras · OpenCV · YOLOv8 · Ultralytics

---

### 06_3 — Redes Neuronales Recurrentes (RNN)

| # | Notebook | Descripción |
|---|----------|-------------|
| 20 | `rnn_intro_simple_lstm_gru.ipynb` | Introducción a RNN: Simple, LSTM y GRU |
| 21 | `rnn_lstm_precio_energia_colombia.ipynb` | Pronóstico del precio de energía en Colombia con LSTM + MLP |
| 22 | `rnn_char_generacion_texto.ipynb` | Generación de texto con Char-RNN en TensorFlow |
| 23 | `rnn_simple_numpy.ipynb` | RNN simple implementada desde cero en NumPy |
| 24 | `rnn_clasificacion_emociones.ipynb` | Clasificación de emociones con RNN |

**Stack:** TensorFlow · Keras · NumPy

---

### 06_4 — Autoencoders

| # | Notebook | Descripción |
|---|----------|-------------|
| 30 | `autoencoder_convolucional_denoising.ipynb` | Autoencoder convolucional para reducción de ruido en imágenes |
| 31 | `autoencoder_intro_tres_ejemplos.ipynb` | Introducción a autoencoders: tres ejemplos prácticos |
| 32 | `autoencoder_ecg_anomalias_cardiacas.ipynb` | Detección de anomalías cardiacas en señales ECG |
| 33 | `autoencoder_limpieza_imagenes.ipynb` | Limpieza y restauración de imágenes con autoencoders |

**Stack:** TensorFlow · Keras · NumPy · Matplotlib

---

### 06_5 — Redes Generativas Adversariales (GANs)

| # | Notebook | Descripción |
|---|----------|-------------|
| 34 | `gan_intro_keras.ipynb` | Introducción a GANs con Keras |
| 35 | `gan_entrenamiento_fifa.ipynb` | GAN entrenada con datos de jugadores de FIFA |

**Stack:** TensorFlow · Keras

---

### 06_6 — Transformers

| # | Notebook | Descripción |
|---|----------|-------------|
| 37 | `transformer_aplicacion.ipynb` | Aplicación práctica de Transformers |
| 38 | `vision_transformer_fine_tuning.ipynb` | Fine-tuning de Vision Transformer (ViT) |
| 39 | `vision_transformer_transfer_learning.ipynb` | Transfer learning con Vision Transformer |

**Stack:** HuggingFace · TensorFlow · Keras

---

## 🗣️ AI Applications — `07_AI_APPLICATIONS`

### 07_1 — Procesamiento de Lenguaje Natural (NLP)

| # | Notebook | Descripción |
|---|----------|-------------|
| 25 | `nlp_intro_procesamiento_lenguaje.ipynb` | Introducción al procesamiento de lenguaje natural |
| 26 | `nlp_texto_tensorflow.ipynb` | Procesamiento de texto con TensorFlow |
| 27 | `nlp_lstm_generacion_texto.ipynb` | Generación de texto con LSTM |
| 28 | `nlp_lstm_generacion_texto_v2.ipynb` | Generación de texto con LSTM — versión avanzada |
| 29 | `nlp_webscraping_llm.ipynb` | Web scraping asistido con LLM |

**Stack:** TensorFlow · Keras · NLTK · HuggingFace

---

## 🛠️ Stack Tecnológico

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## 📌 Temas Cubiertos

- **Redes Neuronales Artificiales** — Perceptrón, MLP, clasificación y regresión
- **Visión por Computadora** — CNN, Transfer Learning, Detección de Objetos con YOLO
- **Series de Tiempo** — Pronóstico con LSTM y RNN
- **Generación de Contenido** — GANs para imágenes y texto
- **Compresión y Anomalías** — Autoencoders para ECG, denoising e imágenes
- **NLP** — Clasificación de texto, generación con LSTM, LLMs
- **Vision Transformers** — Fine-tuning y Transfer Learning con ViT
- **Machine Learning Clásico** — Modelado de churn, evaluación y tuning

---

## 👤 Autor

**Isaac Guzmán**
Estudiante de Ingeniería — Universidad UNAB, Colombia

[![GitHub](https://img.shields.io/badge/GitHub-jisaacguzmanm-181717?style=flat&logo=github)](https://github.com/jisaacguzmanm)

---

> 📁 Portafolio en construcción continua — se agregan nuevos proyectos a medida que avanzan los semestres.
