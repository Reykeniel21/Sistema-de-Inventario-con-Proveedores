# Arquitectura del Sistema

La arquitectura del sistema es de tipo cliente-servidor y sigue el patrón MVC de forma simplificada.

## Flujo de la aplicación

Navegador → Flask → SQLAlchemy → SQLite

### Descripción:
- El usuario interactúa desde el navegador web.
- Flask gestiona las rutas, la lógica de negocio y las vistas.
- SQLAlchemy actúa como ORM para interactuar con la base de datos.
- SQLite almacena la información de proveedores y productos.

Esta arquitectura permite un desarrollo modular, sencillo y fácil de mantener.
