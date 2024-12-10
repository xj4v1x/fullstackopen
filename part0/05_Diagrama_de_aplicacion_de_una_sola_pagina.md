# 0.5: Diagrama de aplicación de una sola página

https://studies.cs.helsinki.fi/exampleapp/spa

    navegador ->> servidor: GET https://studies.cs.helsinki.fi/exampleapp/spa
    servidor ->> navegador: Documento HTML (200 OK)

    navegador ->> servidor: GET https://studies.cs.helsinki.fi/exampleapp/main.css
    servidor ->> navegador: Documento CSS (200 OK)

    navegador ->> servidor: GET https://studies.cs.helsinki.fi/exampleapp/spa.js
    servidor ->> navegador: Archivo Javascript (200 OK)

    navegador ->> servidor: GET https://studies.cs.helsinki.fi/exampleapp/data.json
    servidor ->> navegador: Datos JSON (200 OK)

    navegador ->> servidor: GET https://studies.cs.helsinki.fi/favicon.ico
    servidor ->> navegador: 404 Not Found
