# 📸 Introduccion operaciones Básicas con Imágenes (BSDS)

**Fecha:** 21/04/2025  
**Autor:** Matias Roman  

---

### 🧪 Tecnologías utilizadas
- Python 3.x  
- OpenCV  
- NumPy  
- Matplotlib  
- Scikit-image (solo instalación)  
- Google Colab  

---

### 📌 ¿Qué hicimos en este notebook?

Trabajamos sobre una imagen del dataset **BSDS300** realizando operaciones básicas para entender su estructura y manipulación.

Se aplicaron los siguientes pasos:

1. 📥 **Descarga y carga de imagen** desde una URL externa.
2. 🔎 **Análisis de características** (tamaño, máximo, mínimo).
3. ✂️ **Recorte** de una región específica.
4. 🎚️ **Conversión a escala de grises** y separación de canales de color.
5. 🔍 **Detección de bordes** con **Canny** en:
   - Imagen original.
   - Imagen en RGB.
   - Imagen en escala de grises.
   - Imagen suavizada con **Gaussian Blur**.
6. 🔁 **Redimensionamiento y apilamiento** vertical/horizontal de imágenes.

---

### ▶️ Instrucciones de uso

1. Ejecutá el notebook en un entorno compatible (Google Colab).
2. Instalá las librerías necesarias:
   ```bash
   pip install scikit-image watermark
