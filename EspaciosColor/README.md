# 🖼️ Espacios de Color en Imágenes Digitales

Este cuaderno introduce los fundamentos del manejo de **espacios de color** en imágenes digitales, y las diferencias clave entre los formatos utilizados por diferentes bibliotecas de Python como OpenCV y Matplotlib.

## 🎯 Objetivo

Explorar la representación y conversión de imágenes entre los espacios de color **RGB** y **BGR**, comprendiendo su impacto en el análisis y visualización.

## 📚 Contenidos del Cuaderno

1. **Introducción a los espacios de color:**
   - RGB (Red, Green, Blue)
   - BGR (Blue, Green, Red)

2. **OpenCV (`cv2`):**
   - Análisis de canales en formato BGR
   - Visualización y manipulación de imágenes

3. **Matplotlib:**
   - Visualización en RGB
   - Personalización de gráficos para análisis detallado

4. **Conversión entre espacios de color:**
   - Uso de funciones de OpenCV para conversión entre RGB y BGR
   - Prevención de errores comunes en la visualización

5. **Resumen de buenas prácticas:**
   - Verificar siempre el espacio de color antes de operar
   - Utilizar funciones de conversión adecuadas
   - Documentar los pasos y formatos utilizados

## 🧪 Ejemplo Integrador

Al final del cuaderno se presenta un ejemplo práctico que aplica todos los conceptos previamente discutidos. En esta sección se:

- Carga una nueva imagen para su análisis.
- Se extraen y visualizan los canales individuales en formato RGB.
- Se realiza la conversión adecuada entre espacios de color para asegurar la visualización correcta.
- Se experimenta con diferentes **mapas de color** (colormaps) aplicados a la imagen en escala de grises, mostrando cómo varían las representaciones visuales según el mapa elegido.

Este ejemplo permite reforzar el entendimiento sobre los espacios de color y explorar nuevas formas de visualización creativa.

## 🛠 Herramientas Utilizadas

- **Python 3.x**
- **OpenCV (`cv2`)**
- **Matplotlib**
- **NumPy**
