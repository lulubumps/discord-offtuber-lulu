# Discord Offtuber — Lulu

Estilos CSS personalizados para adaptar el overlay de voz de Discord StreamKit a un diseño de **Offtuber** para OBS.

## ¿Qué hace?

- Mantiene el fondo transparente para superponer el overlay sobre una escena de OBS.
- Personaliza la apariencia del avatar de voz.
- Cambia la imagen y el brillo del avatar según si la persona está hablando.
- Oculta elementos de texto para conseguir una composición más limpia.
- Añade una pequeña animación vertical al estado de voz activa.

## Requisitos

- Una cuenta de Discord.
- [Discord StreamKit](https://streamkit.discord.com/overlay).
- [OBS Studio](https://obsproject.com/) u otro software que admita fuentes de navegador.
- El archivo **style.css** de este repositorio.

## Configuración

1. Abre Discord StreamKit y selecciona el overlay de voz para tu servidor.
2. Configura el overlay con los usuarios y canales que quieras mostrar.
3. Añade la URL del overlay como una **fuente de navegador** en OBS.
4. Define el tamaño de la fuente en **1920 × 1080** si quieres usar la composición para un lienzo Full HD.
5. Copia el contenido de style.css en el campo CSS personalizado del overlay.
6. Ajusta la posición y escala de la fuente desde OBS según tu escena.

> **Nota:** el CSS utiliza selectores internos de Discord StreamKit y una imagen específica alojada en Discord CDN. Si Discord cambia sus clases o la URL del recurso deja de estar disponible, puede ser necesario actualizar los estilos y reemplazar la imagen.

## Archivos

- **README.md**: documentación del proyecto.
- **style.css**: estilos y animaciones del overlay.

## Personalización

Puedes modificar **--bounce-height** para ajustar el salto del avatar cuando alguien habla. También puedes cambiar las URLs de las imágenes dentro de las reglas CSS por tus propios recursos, respetando sus derechos de uso.

## Licencia y uso

Este repositorio contiene una personalización CSS para uso con Discord StreamKit. Discord y OBS son marcas y proyectos de sus respectivos titulares. No incluye ni reemplaza el software oficial de Discord.
