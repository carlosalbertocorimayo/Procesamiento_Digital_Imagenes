# Técnicas de Procesamiento Digital de Imágenes

Este repositorio recopila las actividades prácticas realizadas para la materia Técnicas de Procesamiento Digital de Imágenes, correspondiente a la Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial del IFTS N° 24.

## Propósito del Repositorio

Este espacio está dedicado al desarrollo de prácticas y proyectos integradores centrados en el procesamiento digital de imágenes. El objetivo principal es aplicar conocimientos teóricos mediante ejercicios prácticos utilizando imágenes reales, desarrollados íntegramente en entornos interactivos como Google Colab.

El repositorio está pensado como base para extender estos conocimientos a nuevos proyectos relacionados con visión por computadora, inteligencia artificial y análisis de imágenes.

## Proyectos incluidos en este repositorio

🧪 **Nivelación en Python**  
Este cuaderno está orientado a reforzar conocimientos esenciales de Python para facilitar la comprensión de futuros cuadernos. Se trabajan estructuras de datos, control de flujo, funciones, manipulación de arrays con NumPy y visualización básica con Matplotlib.

🧪 **Conceptos y Técnicas Fundamentales**  
Este cuaderno presenta una introducción práctica al procesamiento digital de imágenes en Python. Se abordan conceptos básicos como:

- Instalación de bibliotecas (scikit-image, matplotlib, watermark).
- Descarga y carga de imágenes desde la web.
- Visualización y conversión a escala de grises.
- Cuantización de imágenes: reducción de niveles de gris.
- Comparación visual entre versiones originales y procesadas.

El laboratorio está orientado a consolidar los fundamentos para futuros ejercicios relacionados con análisis y visualización de imágenes.

🧪 **Espacios de Color y Visualización**  
Este cuaderno explora los fundamentos del manejo de espacios de color en imágenes digitales, centrándose en las diferencias entre RGB y BGR.  
Se analiza cómo estas representaciones afectan la visualización y el procesamiento con bibliotecas como OpenCV y Matplotlib. 
A través de un ejemplo integrador, se aplican estos conceptos en la práctica y se experimenta con distintos mapas de color, mostrando cómo varía la percepción visual según el esquema elegido.

🧪 **Segmentación Simple por Color**
Este cuaderno presenta una técnica básica de segmentación aplicando un umbral sobre la imagen convertida a escala de grises. A través del análisis de los canales de color y la conversión entre espacios BGR y RGB, se identifican regiones destacadas por su intensidad. Se visualizan los pasos y resultados usando OpenCV y Matplotlib, ideal como primer acercamiento a la segmentación basada en color.

🧪 **Muestreo y Cuantización de Imágenes**  
Este cuaderno introduce los conceptos de muestreo espacial y cuantización de niveles de gris. Se analiza el efecto de reducir la resolución de una imagen y disminuir la profundidad de bits, observando su impacto visual. Ideal para entender la relación entre calidad y eficiencia en la representación digital.

📌 **Proyecto Integrador: Análisis y Segmentación de Imágenes**  
En este proyecto se desarrolló una serie de pasos progresivos con el objetivo de analizar y segmentar imágenes en función del color y sus características morfológicas. Se trabajó con imágenes representativas de casas de Hogwarts para explorar lo siguiente:

- Lectura y visualización de imágenes en formato RGB.
- Separación y análisis individual de los canales de color (Rojo, Verde y Azul).
- Construcción e interpretación de histogramas para cada canal.
- Muestreo espacial: reducción de resolución con diferentes factores.
- Cuantización de imágenes en escala de grises a distintos niveles de profundidad.
- Segmentación por color a partir de umbrales definidos manualmente.
- Creación de máscaras binarias para extraer objetos de interés.
- Detección de bordes de forma manual y con funciones de OpenCV.
- Delimitación de objetos mediante contornos y cajas delimitadoras (bounding boxes).

Estas técnicas fueron aplicadas de forma secuencial, con visualización inmediata de los resultados en cada etapa, facilitando el análisis visual del procesamiento.

## Herramientas Utilizadas

- Google Colab: plataforma en la nube para ejecutar cuadernos interactivos.
- Python 3.x
- Bibliotecas principales: NumPy, Matplotlib, OpenCV, Pillow, scikit-image, watermark

## ¿Cómo usar los cuadernos de Google Colab?

1. Accedé al cuaderno desde el enlace proporcionado o subí el archivo `.ipynb` a tu cuenta de Google Drive.
2. Abrí el cuaderno con Google Colab.
3. Verificá que la imagen requerida esté cargada si corresponde.
4. Ejecutá las celdas en orden para observar paso a paso cada análisis.

## Expansión del Repositorio

Cada nuevo proyecto seguirá esta misma estructura y enfoque, permitiendo así construir un repositorio didáctico y de referencia para temas relacionados con el procesamiento digital de imágenes.

Para más detalles técnicos sobre cada sección, consultar los respectivos cuadernos dentro de cada carpeta.

## Contacto

Si tenés preguntas, sugerencias o simplemente querés conectar, podés escribirme a:

- carlosacorimayo@gmail.com
