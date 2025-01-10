Claro, aquí tienes el README actualizado con las funcionalidades más recientes del bot:
🤖 Bot de Discord - Gestión de Imágenes con IA

Este proyecto es un bot para Discord diseñado para gestionar imágenes mediante comandos simples. Utiliza un modelo de IA basado en Keras para analizar y organizar las imágenes que los usuarios suben. El bot también permite activar/desactivar su funcionamiento, y consultar las imágenes guardadas.
🚀 Funcionalidades

    Subir y Analizar Imágenes
        Usa /subirimagen para subir una imagen al bot. Si la imagen se sube correctamente, será procesada por un modelo de IA para su clasificación y guardada en una carpeta local.
        El bot te notificará cuando la imagen haya sido subida y guardada correctamente, mostrando también la clasificación realizada por el modelo.

    Activar el Bot
        Usa /Activar para activar el bot. Mientras no esté activado, el bot ignorará cualquier comando relacionado con la subida de imágenes.
        El bot te confirmará que está activado y listo para usarse.

    Desactivar el Bot
        Usa /Desactivar para desactivar el bot. Después de esto, no se responderán comandos como /subirimagen hasta que lo actives nuevamente.
        El bot te confirmará que ha sido desactivado.

    Ver Imágenes Guardadas
        Usa /check para obtener una lista de las imágenes guardadas y su clasificación.
        Este comando muestra los nombres de las imágenes guardadas en el bot y te permite revisar las imágenes previamente subidas y clasificadas.

    Simplicidad y Feedback Claro
        Si intentas subir una imagen sin activar el bot, el bot te notificará que no está activado y te recordará usar /Activar.
        Si no subes una imagen con el comando /subirimagen, el bot te lo recordará también.

📚 Requisitos

Para ejecutar este bot, necesitas:

    Python 3.9 o superior
    Librerías de Python:
        discord.py
        tensorflow
        keras
        requests
        os
