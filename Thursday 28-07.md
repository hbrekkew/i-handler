# i-handler
Funciones a Realizar

- [ ]  Integrar API Weather
- [ ]  Flights - Generar PDF desde Flutter
- [ ]  Integrar cámara en la app.
Muchas aplicaciones requieren trabajar con las cámaras del dispositivo para tomar fotos y videos. Flutter proporciona el plugin camera para este propósito. El plugin camera proporciona herramientas para obtener una lista de las cámaras disponibles, mostrar una vista previa que viene de una cámara específica, y tomar fotos o videos.

Esta receta demuestra cómo usar el plugin camera para mostrar una vista previa, tomar una foto y mostrarla.

Añadir las dependencias necesarias
Obtén una lista de las cámaras disponibles
Crear e inicializar el CameraController.
Usa un CameraPreview para mostrar el feed de la cámara.
Toma una foto con el CameraController.
Muestra la imagen con un widget Image.
camera - Proporciona herramientas para trabajar con las cámaras del dispositivo
path_provider - Encuentra las rutas correctas para almacenar imágenes
path - Crea rutas que funcionan en cualquier plataforma
content_copy
dependencies:
  flutter:
    sdk: flutter
  camera:
  path_provider:
  path:
