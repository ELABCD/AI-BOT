🤖 Bot de Discord - Gestión de Imágenes con IA

¡Bienvenido al repositorio del Bot de Discord de Gestión de Imágenes! Este bot está diseñado para recibir imágenes de los usuarios, analizarlas mediante un modelo de inteligencia artificial (IA) basado en Keras y guardarlas para su posterior consulta. Además, el bot cuenta con comandos fáciles de usar para activar/desactivar su funcionamiento y consultar las imágenes guardadas.
🚀 Funcionalidades
1. Subir y Analizar Imágenes

Usa /subirimagen para subir una imagen al bot. Esta imagen será procesada por un modelo de IA entrenado para su clasificación. Una vez subida, el bot te informará que la imagen ha sido guardada y procesada correctamente.
2. Activar el Bot

Usa /Activar para activar el bot. Solo cuando esté activado, el bot responderá a los comandos de imágenes.
3. Desactivar el Bot

Usa /Desactivar para desactivar el bot, de modo que no procesará más imágenes hasta que lo actives nuevamente.
4. Ver Imágenes Guardadas

Usa /check para obtener una lista de las imágenes guardadas y su clasificación. Esto permite a los usuarios revisar qué imágenes han subido y cómo fueron clasificadas.
5. Feedback Claro y Sencillo

    Si intentas subir una imagen sin activar el bot, el bot te notificará que necesitas activarlo primero.
    Si no subes ninguna imagen, el bot te recordará que necesitas hacerlo.

📚 Requisitos

Para ejecutar este bot, necesitas tener instalado lo siguiente:

    Python 3.9 o superior
    Librerías de Python:
        discord.py
        tensorflow
        keras
        requests
        os

Instala las dependencias con:

pip install -r requirements.txt

⚙️ Configuración

    Clona el repositorio a tu máquina local.
    Asegúrate de tener los archivos keras_model.h5 (el modelo de IA) y labels.txt (las etiquetas del modelo) en el directorio raíz del proyecto.
    Configura tu token de Discord en el archivo bot.py.
    Ejecuta el bot con:

python bot.py

🎮 Comandos Disponibles

    /Activar: Activa el bot para empezar a recibir comandos de imágenes.
    /Desactivar: Desactiva el bot y evita que procese imágenes.
    /subirimagen: Sube una imagen al bot, la guarda y la clasifica.
    /check: Muestra las imágenes guardadas y sus clasificaciones.

📁 Estructura de Archivos

    bot.py: El archivo principal que contiene la lógica del bot.
    keras_model.h5: El modelo de IA entrenado.
    labels.txt: El archivo con las etiquetas del modelo.
    imagenes/: Carpeta donde se guardan las imágenes subidas.

🖼️ Capturas de Pantalla

![image](https://github.com/user-attachments/assets/986493fb-d5ec-426e-b944-3c586a013390)



📄 Licencia

Este proyecto está bajo la licencia MIT. Puedes usar, modificar y distribuir el código bajo los términos de la licencia MIT.
