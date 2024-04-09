# Visualización de MNIST con t-SNE y Otras Técnicas de Reducción de Dimensionalidad

Este proyecto se centra en explorar y comparar diferentes técnicas de reducción de dimensionalidad aplicadas al conjunto de datos MNIST para visualizar sus imágenes en un espacio de 2 dimensiones. Específicamente, se utilizan t-SNE (t-distributed Stochastic Neighbor Embedding), PCA (Principal Component Analysis), LLE (Locally Linear Embedding) y MDS (Multidimensional Scaling) para este propósito.

## Pasos a seguir:

### 1. Preparación del Conjunto de Datos:
- Seleccionar las primeras 5,000 imágenes del conjunto de datos MNIST para el análisis.

### 2. Aplicación de t-SNE:
- Utilizar el algoritmo t-SNE para reducir la dimensionalidad de las imágenes seleccionadas a 2 dimensiones.
- Graficar el resultado utilizando Matplotlib, empleando diferentes colores para representar cada una de las 10 clases de dígitos.

### 3. Visualización Avanzada:
- Considerar alternativas para enriquecer la visualización, como etiquetar cada punto con el dígito correspondiente o usar miniaturas de las imágenes de los dígitos.
- Para evitar una visualización abarrotada, se puede optar por mostrar una muestra aleatoria de puntos o asegurarse de que los dígitos solo se tracen si están suficientemente separados entre sí.

### 4. Experimentación con Otras Técnicas:
- Aplicar al menos dos técnicas adicionales de reducción de dimensionalidad (PCA, LLE, MDS) al mismo conjunto de imágenes.
- Graficar y comparar los resultados con la visualización obtenida con t-SNE.

### 5. Análisis y Reflexión:
- Evaluar la efectividad de cada técnica de reducción de dimensionalidad en términos de claridad visual y separación entre las clases de dígitos.
- Reflexionar sobre las ventajas y desventajas de cada técnica para este tipo de tarea de visualización.

## Cómo usar este código:

1. Clona este repositorio en tu máquina local.
2. Instala las dependencias necesarias utilizando `pip install -r requirements.txt`.
3. Ejecuta el código proporcionado en un entorno Python compatible.

## Bibliotecas principales utilizadas:

- NumPy
- Matplotlib
- scikit-learn
- TensorFlow (para cargar el conjunto de datos MNIST)

## Notas:

- Asegúrate de tener instaladas las bibliotecas mencionadas anteriormente para ejecutar el código sin problemas.
- Este proyecto proporciona una exploración básica de las técnicas de reducción de dimensionalidad. Si deseas realizar análisis más avanzados, te recomendamos experimentar con diferentes parámetros y métodos de visualización.
