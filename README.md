# AL Salud & Belleza

Catálogo de Andrea Larrecochea conectado a Google Apps Script.

La raíz contiene index.html, favicon.ico, favicon.png y .nojekyll. index.html muestra el catálogo público dentro de un iframe; los productos se administran en Google Sheets mediante Apps Script.

## Implementación

https://script.google.com/macros/s/AKfycbwmDYqBTswopw7Hyx8lA0Vx8Hv6f_7RMufbqpV0LdnJGDStF6PnJoRO7vgXhJeF0EPj/exec

## Publicación

En Settings → Pages seleccionar Deploy from a branch, la rama main y / (root). Guardar y abrir la dirección que indique GitHub.

## Actualizaciones

Actualizar Code.gs e Index en Apps Script y desplegar una nueva versión conservando la misma URL /exec. Manteniendo esa URL, este repositorio sigue conectado sin cambiar index.html.

Index, con I mayúscula, es el HTML interno de Apps Script. index.html, con i minúscula, es el documento de publicación de este repositorio.
