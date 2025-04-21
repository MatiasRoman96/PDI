# 🎯 Ejercicio 3: Segmentación por Color

**Fecha:** 21/04/2025  
**Autor:** Matias Roman  

---

### 🧪 Tecnologías utilizadas
- Python 3.x  
- OpenCV (cv2)  
- NumPy  
- Matplotlib  
- Google Colab

---

### 📌 ¿Qué hicimos en este notebook?

**Segmentamos objetos de un color específico (rojo) en una imagen y analizamos su distribución de intensidad en escala de grises.**

Se implementan las siguientes tareas:

- Segmentación por color con umbrales definidos manualmente (rojo en este caso).
- Visualización de la máscara generada.
- Cálculo y visualización del histograma de la imagen en escala de grises.
- Identificación y visualización de los rectángulos que encierran los objetos rojos.
- Dibujo de los bordes de los objetos segmentados con color rojo sobre la imagen original.

---

### ▶️ Instrucciones de uso

1. Subí una imagen con colores bien definidos (el ejemplo usa `/content/joy.webp`).  
2. Instalá las dependencias necesarias:
   ```bash
   pip install opencv-python matplotlib
