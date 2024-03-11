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

## Tips de Uso de la API de Google Maps

- **Atributo Zoom**: Puedes ajustar el nivel de zoom del mapa utilizando el atributo `zoom` en las opciones del mapa. Un valor mayor de zoom acerca la vista del mapa, mientras que un valor menor aleja la vista. Por ejemplo:
  ```javascript
  var mapOptions = {
    center: {lat: 4.5709, lng: -74.2973},
    zoom: 10 // Nivel de zoom
  };

## Configuración

Antes de usar este proyecto, asegúrate de reemplazar `TU_API_KEY` con tu propia clave de API de Google Maps en los archivos `index.html` y `mapa.html`.

## Tecnologías utilizadas

- HTML
- CSS
- JavaScript
- Google Maps JavaScript API
