---
title: Análisis y Segmentación de Imágenes RGB
layout: default
---

# Análisis y Segmentación de Imágenes RGB

Este proyecto explora técnicas de procesamiento de imágenes usando Python, con enfoque en segmentación por color, cuantización de grises y detección de bordes. Las herramientas principales utilizadas son OpenCV, NumPy, Matplotlib y PIL.

## Sobre este repositorio
En el siguiente repositorio se subirán todas las actividades prácticas realizadas para la materia **Técnicas de Procesamiento Digital de Imágenes**, correspondiente a la carrera de **Ciencias de Datos e Inteligencia Artificial** del **IFTS N° 24**.

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

## Ejecución

1. Instalar las dependencias si es necesario:
   ```bash
   pip install numpy matplotlib opencv-python pillow
   ```

2. Cargar la imagen base (por ejemplo, `houses-hp.jpg`).

3. Ejecutar los bloques de código por sección, según el análisis deseado.

## Aplicaciones
- Sistemas de visión por computador.
- Análisis automático de imágenes por color.
- Preprocesamiento para clasificadores.
- Extracción de objetos en imágenes RGB.