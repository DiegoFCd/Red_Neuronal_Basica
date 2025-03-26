# Red Neuronal Básica para Conversión de Kilómetros a Millas

[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)](https://www.tensorflow.org/)
[![Python](https://img.shields.io/badge/Python-3.7%2B-blue?logo=python)](https://www.python.org/)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tu_usuario/tu_repositorio/blob/main/RedNeuronalBasicaConCapasOcultas.ipynb)

## 🚀 Descripción del Proyecto
Implementé una red neuronal básica utilizando TensorFlow y Keras para convertir kilómetros a millas. El modelo demuestra cómo las redes neuronales pueden aprender relaciones matemáticas simples y cómo la adición de capas ocultas mejora su rendimiento.



## 🔍 Características Clave
- **Arquitectura de Red Neuronal**: Implementación con capas densas y función de activación lineal.
- **Proceso de Entrenamiento**: Uso del optimizador Adam y métrica de error cuadrático medio.
- **Visualización**: Gráficos de pérdida durante el entrenamiento para evaluar el aprendizaje.
- **Exportación del Modelo**: Conversión a formato TensorFlow.js para implementación web.

## 🛠 Tecnologías Utilizadas
- **TensorFlow/Keras**: Para construcción y entrenamiento del modelo.
- **NumPy**: Manipulación de datos numéricos.
- **Matplotlib**: Visualización de resultados.
- **TensorFlow.js**: Para convertir y exportar el modelo.

## 📊 Resultados Destacados
- **Precisión**: El modelo logra conversiones precisas con un error mínimo.
- **Comparación**: Se demostró cómo las capas ocultas mejoran el rendimiento frente a un modelo sin ellas.
- **Implementación**: El modelo fue exportado exitosamente para su uso en entornos web.

## 🏗 Estructura del Código
```bash
.
├── RedNeuronalBasicaConCapasOcultas.ipynb  # Notebook con el desarrollo completo
├── km_a_millas.h5                          # Modelo entrenado en formato HDF5
└── output_folder/                          # Modelo convertido para TensorFlow.js
    ├── group1-shard1of1.bin
    └── model.json
