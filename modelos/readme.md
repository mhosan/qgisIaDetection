# Modelo en formato ONNX para detección de objetos (piletas de natación en imagenes satelitales)
Este modelo está armado en base al modelo pre-entrenado YOLO11S.
Para entrenar este modelo se utilizaron los siguientes parámetros:
- Epocas: 20
- Tamaño de lote (batch size): 32
- El resto de los parámetros se mantuvieron en sus valores por defecto provistos por el propio modelo YOLO 11 S
- La cantidad de imagenes anotadas que se utilizaron fue de 9500, considerando aumentación de datos hecha con Roboflow
- Se usaron el 80 % de las imagenes para entrenamiento y el 20 % para validación
