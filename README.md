# client-test

Este repositorio contiene una aplicación frontend básica desarrollada con **HTML, CSS y JavaScript** que forma parte de un mini ecosistema de prueba. Su función principal es servir como una interfaz web muy simple que permite al usuario enviar peticiones a otros microservicios y visualizar sus respuestas.

Está diseñada para interactuar con:

- `api-core-test`: Microservicio que expone la ruta `/core` para gestionar mensajes almacenados en una base de datos **MongoDB**.
- `api-gm-test`: Microservicio que expone la ruta `/gm` para gestionar registros almacenados en una base de datos **PostgreSQL**.
