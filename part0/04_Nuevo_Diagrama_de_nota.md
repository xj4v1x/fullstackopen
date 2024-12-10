# 0.4: Nuevo diagrama de nota

https://studies.cs.helsinki.fi/exampleapp/notes

    navegador ->> servidor: GET https://studies.cs.helsinki.fi/exampleapp/notes
    servidor ->> navegador: Documento HTML (200 OK)

    navegador ->> servidor: GET https://studies.cs.helsinki.fi/exampleapp/main.css
    servidor ->> navegador: Documento CSS (200 OK)

    navegador ->> servidor: GET https://studies.cs.helsinki.fi/exampleapp/main.js
    servidor ->> navegador: Archivo Javascript (200 OK)

    navegador ->> servidor: GET https://studies.cs.helsinki.fi/exampleapp/data.json
    servidor ->> navegador: Datos JSON (200 OK)

    navegador ->> servidor: GET https://studies.cs.helsinki.fi/favicon.ico
    servidor ->> navegador: 404 Not Found

    navegador ->> servidor: POST https://studies.cs.helsinki.fi/exampleapp/new_note
    servidor ->> navegador: Documento HTML (302 Found)

    navegador ->> servidor: GET https://studies.cs.helsinki.fi/exampleapp/notes
    servidor ->> navegador: Documento HTML (200 OK)

    navegador ->> servidor: GET https://studies.cs.helsinki.fi/exampleapp/main.css
    servidor ->> navegador: Documento CSS (200 OK)

    navegador ->> servidor: GET https://studies.cs.helsinki.fi/exampleapp/main.js
    servidor ->> navegador: Archivo Javascript (200 OK)

    navegador ->> servidor: GET https://studies.cs.helsinki.fi/exampleapp/data.json
    servidor ->> navegador: Datos JSON (200 OK)

    navegador ->> servidor: GET https://studies.cs.helsinki.fi/favicon.ico
    servidor ->> navegador: 404 Not Found


