# Seleccionar Ubicación en Google Maps

Este proyecto consiste en una aplicación web que permite seleccionar una ubicación en un mapa de Google Maps y mostrar las coordenadas de esa ubicación en dos `<input>`. Además, incluye un botón para actualizar las coordenadas y recargar la página con las nuevas coordenadas como parámetros de la URL.

## Funcionamiento

El proyecto está dividido en dos páginas:

1. **index.html**: Contiene el título, dos `<input>` para mostrar las coordenadas, un botón "Actualizar Coordenadas" y un `<iframe>` que carga la página `mapa.html`.
2. **mapa.html**: Contiene el mapa de Google Maps con la funcionalidad para seleccionar una ubicación y actualizar las coordenadas en la página principal.

## Uso

1. Clona este repositorio en tu máquina local.
2. Abre el archivo `index.html` en tu navegador web.
3. El mapa de Google Maps se mostrará junto con un marcador en Colombia.
4. Puedes arrastrar el marcador para seleccionar una ubicación y las coordenadas se actualizarán en tiempo real en la página principal.
5. Si deseas cambiar las coordenadas, simplemente modifica los valores en los `<input>` y haz clic en el botón "Actualizar Coordenadas".

## Configuración

Antes de usar este proyecto, asegúrate de reemplazar `TU_API_KEY` con tu propia clave de API de Google Maps en los archivos `index.html` y `mapa.html`.

## Tecnologías utilizadas

- HTML
- CSS
- JavaScript
- Google Maps JavaScript API

## Contribuciones

Si encuentras algún error o tienes alguna sugerencia de mejora, no dudes en abrir un issue o enviar un pull request.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.
