🤖 Bot de Discord - Gestión de Imágenes con IA

Este proyecto es un bot para Discord diseñado para gestionar imágenes mediante comandos simples. Utiliza un modelo de IA basado en Keras para analizar y organizar las imágenes que los usuarios suben. Además, incluye funciones para activar/desactivar el bot y consultar imágenes guardadas.
🚀 Funcionalidades:

  Subir y Analizar Imágenes:
        Usa /subirimagen para subir una imagen al bot. Si la imagen se sube correctamente, será procesada por un modelo de IA para su clasificación y guardada en una carpeta local.
        El bot confirmará la subida de la imagen y su clasificación con un mensaje claro.

  Activar el Bot:
        Usa /Activar para activar el bot. Mientras no esté activado, el bot ignorará cualquier comando relacionado con la subida de imágenes.
        El bot te notificará que está activado y listo para usarse.

  Desactivar el Bot:
        Usa /Desactivar para desactivar el bot. Después de esto, no se responderán comandos como /subirimagen hasta que lo actives nuevamente.
        El bot te confirmará que ha sido desactivado.

  Ver Imágenes Guardadas:
        Usa /check para obtener una lista de las imágenes guardadas y su clasificación.
        Este comando te permite revisar las imágenes previamente subidas y clasificadas, aunque el bot no esté activado.

  Simplicidad y Feedback Claro:
        Si intentas subir una imagen sin activar el bot, el bot te notificará que no está activado y te recordará usar /Activar.
        En caso de no subir una imagen con el comando /subirimagen, el bot te lo recordará también.

📚 Requisitos

Para ejecutar este bot, necesitas:

    Python 3.9 o superior
    Librerías de Python:
        discord.py
        tensorflow
        keras
        requests
        os
