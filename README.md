# Comparación de Imágenes con SSIM y Cambio de Tamaño

Este proyecto permite comparar imágenes reconstruidas con sus versiones originales en términos de Índice de Similitud Estructural (**SSIM**) y el **cambio de tamaño** (en porcentaje). El proyecto procesa imágenes almacenadas en carpetas específicas y genera una tabla que muestra estos valores para cada imagen, organizada por carpeta.

## Estructura del Proyecto

El proyecto asume la siguiente estructura de carpetas:


- Las carpetas `DATA/5`, `DATA/6` y `DATA/7` contienen imágenes reconstruidas.
- La carpeta `TEST` contiene las imágenes originales con las que se comparan.

## Dependencias

Este proyecto usa las siguientes bibliotecas de Python:

- **Pandas**: para organizar y manipular los datos.
- **OpenCV** (`cv2`): para cargar las imágenes.
- **Scikit-Image** (`skimage.metrics`): para calcular el Índice de Similitud Estructural (SSIM).