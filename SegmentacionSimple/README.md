# Segmentación Simple por Color

Este cuaderno presenta un ejemplo introductorio de segmentación de imágenes digitales utilizando Python y OpenCV, enfocado en el análisis de color y la conversión de imágenes.

## Objetivo

Explorar una técnica sencilla de segmentación de imágenes basada en umbrales aplicados a una versión en escala de grises. El ejemplo busca ilustrar cómo extraer regiones de interés a partir de diferencias de color y características básicas de la imagen.

## Contenido del Cuaderno

- Descarga y visualización de una imagen de flores.
- Conversión del formato de color de BGR (OpenCV) a RGB (Matplotlib).
- Separación de canales de color: Rojo, Verde y Azul.
- Conversión de la imagen a escala de grises mediante promedio ponderado.
- Segmentación por umbral para destacar regiones con colores más intensos.
- Visualización de resultados con `cv2_imshow` y `matplotlib.pyplot`.

## Herramientas Utilizadas

- Python 3.x
- Google Colab
- Bibliotecas: NumPy, OpenCV, Matplotlib

## Cómo usarlo

1. Abrí el cuaderno en Google Colab.
2. Ejecutá las celdas en orden.
3. Observá los resultados visuales de cada etapa del procesamiento.
