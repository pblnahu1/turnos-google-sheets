# Aplicación de Turnos con Google Sheets

(En file está el archivo de Google Sheet para descargar y probar)

Se trata de un proyecto de Turnos con Usuarios que se almacena en un Google Sheet y se elimina del listado del sitio web cuando se marca como finalizado.

Es un proyecto sencillo pero abarca mucha lógica y de paso aprendemos cómo usar Google Workspace, usar API's, OAuth, y más.

## Pasos resumidos

### Guía de inicio rápido de Google:
https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbjQ1dUdoc1RibHc0clZVNUttOGdTb05kemJQUXxBQ3Jtc0trTTNVcTFnQXZTYVVVS3hhYU1LN2Q3TEludlFJY2FmYjBwczJvTjJ0dnY0dDJVeHN4bXloZkh1RzFhZWNhd1RIa3lvX0tLMk16TWNwUlJfOUN4THg4UzFWbERRbllZSGhVWmxYbzlLYTl1SkliY3FsQQ&q=https%3A%2F%2Fdevelopers.google.com%2Fsheets%2Fapi%2Fquickstart%2Fjs%3Fhl%3Des-419%23prereqs&v=GUgf4UmYnHQ

1. Crear un proyecto en Google
2. Crear plantilla de consentimiento OAuth
3. Agregar usuario de prueba
4. Habilitar API sheets https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbGY4UkJfODFCN3BqUDRMLWFfeFlYTWhBdm1EZ3xBQ3Jtc0tuQ3E1dnJieEtxVW4yb01MOVBVbkh1OXQ5eVFfSmtaaTI1YjlhVXJaLVh4X2N6dHYxZGlJMFpydVZra044OF9yUU94Z29lUVNJQXNhaWpCQ0piNnZRVXRYUEdGOEFZbUhFajFpM1JPZExzSDM5aERpdw&q=https%3A%2F%2Fconsole.cloud.google.com%2Fflows%2Fenableapi%3Fapiid%3Dsheets.googleapis.com%26hl%3Des-419&v=GUgf4UmYnHQ
5. Crear Clave API, con restricción a Sheets
6. Crear ID cliente OAuth2, con URI http://127.0.0.1:5500 (o el servidor que le proporciona el lenguaje de programación con en el que esté ejecutando el proyecto)
7. Copiar y pegar el código que nos proporciona Google
8. Reemplazar el CLIENT_ID y el SECRET
9. Llevar todo el script a otro archivo
10. Reemplazar los eventos 'onload' de 'gapi' y 'gis' por 'eventListeners' en JavaScript
11. Adaptar el proyecto a como prefieras

# Aclaración
* La clave de API no se debería de poner en ningún lugar que el usuario lo pueda leer, por lo cual no se recomienda dejarlo como un string, sino que hay que agregarlo como variable de entorno dentro de un servidor. (Que no se pueda ni leer mirando el código fuente del front).