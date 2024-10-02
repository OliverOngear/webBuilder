# webBuilder
A simple html contruction model bassed JS vanilla, Json and html components.

Build steps:
1. Se realiza la peticion para visualizar el archivo html "main.html".
2. El archivo en blanco se abre y carga el script "builder.js".
3. El script "builder.js" accede a un json "main.json" que contiene la informacion y rutas de archivos para construir la pagina.
4. El archivo json "main.json" regresa la informacion al script "builder.js".
5. El script "builder.js" busca los componentes, genera el codigo html y lo envia a la pagina "main.html".
6. Se crea un nuevo "main.html" que se muestra al usuario.
7. Se ejecutan los scripts que le dan funcionalidad a la pagina.
