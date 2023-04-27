# Podcast Technical Test


### ESPAÑOL
Realizar un podcast SPA basado en la información facilitada en el documento de requisitos técnicos.

## Objetivos
Tres puntos de vista principales
1. Página de inicio
    - Mostrar la lista de 100 podcasts ... **HECHO**
    - Una vez obtenida, la lista debe almacenarse en el lado del cliente y sólo debe llamarse de nuevo una vez transcurrido un día ... **HECHO**
    - Filtro en directo/inmediato para los podcasts basado en el nombre del podcast y del autor ... **HECHO**
    - Cada podcast está vinculado a su vista detallada ... **HECHO**
2. Vista detallada del podcast
    - Barra lateral con imagen del Podcast, título, autor y descripción ... **HECHO**
    - En el lado derecho, Recuento de Episodios y la lista de Episodios con su título, fecha de publicación y duración ... **HECHO**
    - Almacenar la información de cada podcast en el lado del cliente cuando se llama por primera vez. **HECHO**
    - Debe ser llamado de nuevo sólo después de un día ha pasado ... **HECHO**
    - La barra lateral con la información de los podcasts debería estar vinculada a la vista detallada de los podcasts. ... **HECHO**
3. Vista detallada del episodio
    - La misma barra lateral de la información del podcast de la página de detalles del podcast ... **HECHO**
    - La imagen, el título y el autor deben estar vinculados para ir a la vista detallada del podcast. ... **HECHO**
    - La sección Episodio debería tener título, descripción y un reproductor de audio HTML5 básico para escuchar el podcast. ... **HECHO**

Cabecera
- El título 'Podcaster' debería estar enlazado para ir a la página de inicio. ... **HECHO**
- Cada vez que hay una navegación desde el lado del cliente, algún signo visual debe estar allí para actuar como un cargador mientras se carga la información. ... **HECHO**

General
- CORS ... He probado el método de axios baseurl pero no parece funcionar. Tendré que comprobar cómo puedo integrarlo. ...**HECHO**


## Paquetes externos necesarios para instalar
1. npm install styled-components
2. npm install axios
3. npm install react-router-dom

En el directorio del proyecto, puedes ejecutar:

## Detalles adicionales de UI/UX
- Ver más botón en la página de inicio para mostrar podcasts en grupos de 10.
- El número de podcasts junto a la barra de búsqueda se actualiza a partir de la consulta del filtro.
- El cargador es un disco de vinilo.
- En la página de inicio, los podcasts tienen un color de sombra al pasar el ratón por encima.
- Efecto hover en la lista de episodios.


### ENGLISH
To make a podcast SPA based on the information provided in the technical requirements document.

## Objectives
Three main views
1. Homepage
    - Show the list of 100 podcasts ... **DONE**
    - Once obtained, the list should be stored on the client side and only called again after one day has passed ... **DONE**
    - Live/Immediate Filter for the podcasts based on the Podcast and Author Name ... **DONE**
    - Each Podcast is linked to its detail view ... **DONE**
2. Podcast Detail View
    - Side Bar with Podcast Image, title, author and description ... **DONE**
    - On the right side, Episode Count and the list of Episodes with their title, published date and duration ... **DONE**
    - Store the information of each podcast on the client side when it is called for the first time. **DONE**
    - It should be called again only after a day has passed ... **DONE**
    - Side Bar with Podcast Information should be linked to the podcast detail view. ... **DONE**
3. Episode Detail View
    - The same side bar of the podcast information from the podcast detail page ... **DONE**
    - The image, title and author should be linked to go to the podcast detail view. ... **DONE**
    - The Episode section should have title, description and a basic HTML5 audio player to listen to the podcast. ... **DONE**

Header
- The Title 'Podcaster' should be linked to go to the home page. ... **DONE**
- Every time there is a navigation from the client side, some visual sign should be there to act as a loader while the information is being loaded. ... **DONE**

General
- CORS ... I tried the method of axios baseurl but it didn't seem to work. I will have to check to see how I can integrate it...**DONE**


## External packages needed to install
1. npm install react-router-dom
2. npm install styled-components
3. npm install axios
4. npm install acios-mock-adapter
5. npm install jest



In the project directory, you can run:

## Additional UI/UX details
- See more button on the homepage to show podcasts in groups of 10.
- The number of podcasts next to the search bar are getting updated from the filter query.
- The loader is a vinyl disc.
- On the homepage, the podcast have a hover shadow colour.
- Hover effect on episode list.



