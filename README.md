# Proyecto de Inteligencia Artificial para Samsung Innovation Campus

# Modelo de inteligencia artificial para el reconocimiento de enfermedades en plantas de cultivo.


## 📌 Descripción
Red neuronal convolucional para Indentificar el bienestas de plantas de cultivos, el documento incluye el codigo para el entrenamiento para la RNC y 
el codigo para la predicción a tiempo real. Las plantas de cultivo incluidas son:

- Tomate
- Maíz
- Pimentón

## 📚 Librerías utilizadas  
| Librería                | Uso principal                                                                 |
|-------------------------|------------------------------------------------------------------------------|
| `kagglehub`            | Descargar datasets desde Kaggle.                                            |
| `os`                   | Manejo de rutas y operaciones del sistema de archivos.                      |
| `cv2`                  | Procesamiento de imágenes (OpenCV).                                         |
| `numpy`                | Operaciones numéricas y manejo de arrays.                                   |
| `shutil`               | Operaciones avanzadas de archivos (copiar, mover).                          |
| `tensorflow.keras`     | Construcción, entrenamiento y evaluación de modelos de aprendizaje profundo.|
| `ImageDataGenerator`    | Generación de datos aumentados para entrenamiento de modelos.               |
| `matplotlib`           | Visualización de gráficos (implícito en los callbacks de Keras).            |

## 📂 Dataset
- **Fuente:** [Kaggle](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset) 
- **Datos incluidos:**
  - Imagenas a color, escala de grises y segmentadas de las siguientes plantas de cultivo:
    - Manzana (Apple)
    - Arándano (Blueberry)
    - Cereza (Cherry)
    - Maíz (Corn)
    - Uva (Grape)
    - Naranja (Orange)
    - Durazno (Peach)
    - Pimiento (Pepper, bell)
    - Papa (Potato)
    - Frambuesa (Raspberry)
    - Soja (Soybean)
    - Calabaza (Squash)
    - Fresa (Strawberry)
    - Tomate (Tomato)
