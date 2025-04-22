# Proyecto: **Análisis de Frutas por Segmentación de Colores**

## Descripción

Este proyecto utiliza técnicas de procesamiento de imágenes en Python para detectar frutas en una imagen basada en la segmentación por colores. El enfoque se basa en la segmentación en el espacio de color **HSV (Hue, Saturation, Value)**, lo que permite identificar objetos de ciertos colores en la imagen, como frutas amarillas.

## Objetivos

- Segmentar objetos por colores en imágenes utilizando el espacio de color HSV.
- Detectar frutas de color amarillo (u otros colores, si se ajustan los parámetros).
- Mostrar la máscara de segmentación y la imagen original con los contornos de los objetos detectados.
- Medir las áreas de los objetos detectados y extraer estadísticas relacionadas.

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
