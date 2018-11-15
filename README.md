# Historias de Usuario

Para la aplicación móvil.

-   Como usuario quiero tomar fotos para guardarlas y categorizarlas (offensive, nudge, o persuasive design).
-   Como usuario quiero recibir una sugerencia de qué tipo de diseño es la imagen para hacer el proceso fácil.
-   Como usuario quiero ver un mapa con pins de las imágenes guardadas para poder localizarlas.
-   Como usuario quiero tocar un pin para ver los detalles de la foto.
-   Como usuario quiero validar una foto para mejorar las sugerencias de nuevas fotos.
-   Como usuario puedo iniciar sesion para guardar mis datos.

# Sprint Planning

## Spike

| Tarea                                                         | Duración |
| ------------------------------------------------------------- | -------- |
| Aprender sobre Azure/heroku                                   | 4h       |
| Aprender sobre React Native (FE)                              | 14h      |
| Aprender sobre Django - SQL (BE)                              | 8h       |
| Aprender sobre SSO de google y medidas de seguridad (FE - BE) | 6h       |
| Aprender sobre geolocation metada de foto                     | 1h       |
| Aprender sobre activar la geolocalización                     | 2h       |
| Aprender sobre solicitar los permisos                         | 2h       |
| Implementar la base de datos en el server                     | 3h       |
| Implementar DJANGO en el server                               | 3h       |

## Story 1

| Tarea                             | Duración |
| --------------------------------- | -------- |
| Crear pantalla                    | 1h       |
| Usar geolocation del cel          | 1h       |
| Tomar fotos                       | 2h       |
| Seleccionar fotos                 | 1h       |
| Preview de las fotos              | 1h       |
| Llenar y enviar fomulario         | 1h       |
| Definir schema para el formulario | 1h       |
| Guardar formulario en DB          | 3h       |


## Story 2

| Tarea                                      | Duración |
| ------------------------------------------ | -------- |
| Implementar SSO en backend                 | ?        |
| Guardar la autenticación en base de datos. | ?        |
| Implementar SSO en frontend                | ?        |

# Technology Stack

## Frontend (Mobile)

* React Native

## Backend

| Componente | Herramienta                                               |
| ---------- | --------------------------------------------------------- |
| Web Server | Django                                                    |
| SQL DB     | DocumentDB if Azure else MongoDB                          |
| NoSQL DB   | SQLServer if Azure else (PostgreSQL if Heroku else MySQL) |
| A.I.       | Tensorflow (Python)                                       |
| Support    | ?                                                         |
