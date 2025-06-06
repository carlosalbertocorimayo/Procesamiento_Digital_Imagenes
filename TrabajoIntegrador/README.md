# Trabajo Integrador

En el cuaderno compartido se desarrolló una serie de pasos progresivos con el objetivo de analizar y segmentar imágenes en función del color y sus características morfológicas (formas, estructuras y patrones que se pueden identificar dentro de una imagen). Se toma como base todos los recursos aprendidos y utilizados en cuadernos anteriores para un análisis completo. Para ello, se trabajó con imágenes representativas de las casas de Hogwarts (Harry Potter) para explorar técnicas de procesamiento de imágenes usando Python, con enfoque en segmentación por color, cuantización de grises y detección de bordes. Las herramientas principales utilizadas son OpenCV, NumPy, Matplotlib y PIL.

## Contenido del Proyecto

### 1. Carga y Visualización de Imágenes
- Se cargan imágenes en formato RGB usando `cv2.imread`, `plt.imread`, y `Image.open` (PIL).
- Se visualizan con Matplotlib y se realizan conversiones de formato de color (RGB, escala de grises).

### 2. Análisis de Canales de Color (BGR)
- Se separan los canales Azul, Verde y Rojo.
- Se analizan sus valores mínimos, máximos y promedios.
- Se visualizan como imágenes individuales en escala de grises.

### 3. Histogramas de Canales
- Se generan histogramas para cada canal de color.
- Se marca el valor promedio con una línea punteada.

### 4. Muestreo de Imagen
- Se reduce la resolución de la imagen por factores de 2, 4 y 8.
- Se calcula el porcentaje de reducción.
- Se visualizan en una cuadrícula junto a texto informativo.

### 5. Cuantización en Escala de Grises
- Se convierte la imagen a escala de grises con `PIL.convert("L")`.
- Se aplica cuantización a 256, 128, 64 y 32 niveles.
- Se visualizan en una grilla 2x2.

### 6. Segmentación por Color
- Se definen umbrales de color (rojo, verde, azul, amarillo).
- Se crea una imagen binaria basada en esos umbrales.
- Se aplica una máscara para segmentar regiones de ese color.

### 7. Detección y Delimitación de Objetos

#### A. Búsqueda Manual de Bordes
- Se compara cada píxel con sus vecinos para detectar cambios.
- Se marca el borde y se superpone sobre la imagen original en rojo.

#### B. Delimitación Manual con Rectángulo
- Se encuentran coordenadas extremas de los píxeles activados.
- Se dibuja un rectángulo con `matplotlib.plot`.

#### C. Delimitación Automática con OpenCV
- Se usa `cv2.findContours` para detectar objetos.
- Se calcula el "bounding box" del objeto más grande.
- Se dibuja con `cv2.rectangle`.

## Requisitos

- Python 3.x
- numpy
- matplotlib
- opencv-python
- pillow

## Aplicaciones
- Sistemas de visión por computador.
- Análisis automático de imágenes por color.
- Preprocesamiento para clasificadores.
- Extracción de objetos en imágenes RGB.

## Cómo usarlo

1. Abrí el cuaderno en Google Colab.
2. Ejecutá las celdas en orden.
3. Observá los resultados visuales de cada etapa del procesamiento.
