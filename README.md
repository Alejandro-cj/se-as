# yolov8_senas

# Crea un entorno virtual:
# Crea el entorno
python -m venv venv

# Genera requirements.txt con tus dependencias:
pip freeze > requirements.txt

# Activa el entorno:
# En Windows
venv\Scripts\activate

# Instala YOLOv8 y otras librerías necesarias:
Con el entorno virtual activado, ejecuta:
pip install ultralytics opencv-python matplotlib

Esto instalará:

ultralytics: para usar YOLOv8 directamente
opencv-python: para usar la cámara y leer imágenes
matplotlib: para mostrar resultados si quieres


