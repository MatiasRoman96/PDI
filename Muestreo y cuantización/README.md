# 🧮 Muestreo Espacial y Cuantización de Imágenes

**Fecha:** 21/04/2025  
**Autor:** [Tu nombre acá]  

---

### 🧪 Tecnologías utilizadas
- Python 3.x  
- OpenCV (cv2)  
- NumPy  
- Matplotlib  
- Google Colab (como entorno sugerido)  

---

### 📌 Se trata de:
**Exploración práctica de los conceptos de muestreo espacial y cuantización**

Este notebook realiza pruebas controladas sobre una imagen digital para visualizar los efectos de la reducción espacial y de la reducción en el número de niveles de intensidad de color:

- Reducción de resolución (muestreo) con factores 2, 4 y 8.  
- Cálculo del nuevo tamaño de imagen y del porcentaje de reducción de datos.  
- Aplicación de **cuantización** con distintos niveles: 256, 128, 64, 32, 16, 8 y 4.  
- Análisis visual para determinar a partir de qué punto se observa una pérdida notable de calidad.

---

### ▶️ Instrucciones de uso
1. Subí una imagen (el ejemplo usa `/content/palta.jpg`).  
2. Instalá las dependencias:
   ```bash
   pip install opencv-python matplotlib
