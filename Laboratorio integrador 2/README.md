# Proyecto: **Análisis de imagenes por Segmentación de Colores**

## Descripción

Este proyecto utiliza técnicas de procesamiento de imágenes en Python para detectar objetos en color rojo en una imagen basada en la segmentación por colores. El enfoque se basa en la segmentación en el espacio de color **HSV (Hue, Saturation, Value)**, lo que permite identificar objetos de ciertos colores en la imagen.

## Objetivos

- Segmentar objetos por colores en imágenes utilizando el espacio de color HSV.
- Detectar objetos de color rojo (u otros colores, si se ajustan los parámetros).
- Mostrar la máscara de segmentación y la imagen original con los contornos de los objetos detectados.

## Requisitos

- Python 3.x
- Librerías necesarias:
  - `opencv-python`
  - `numpy`
  - `matplotlib`
  - `urllib`

Instalar las dependencias necesarias ejecutando:

```bash
pip install opencv-python numpy matplotlib
