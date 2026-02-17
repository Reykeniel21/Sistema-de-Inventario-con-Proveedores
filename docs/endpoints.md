# Endpoints del Sistema

## Lista de Endpoints

| Ruta | Método | Descripción |
|------|---------|------------|
| / | GET | Redirige a la lista de productos |
| /suppliers | GET | Lista todos los proveedores |
| /suppliers/new | GET, POST | Crear un nuevo proveedor |
| /suppliers/<id>/edit | GET, POST | Editar un proveedor |
| /suppliers/<id>/delete | POST | Eliminar un proveedor |
| /products | GET | Lista productos y permite filtrar por proveedor |
| /products/new | GET, POST | Crear un nuevo producto |
| /products/<id>/edit | GET, POST | Editar un producto |
| /products/<id>/delete | POST | Eliminar un producto |
| /reports/low-stock | GET | Muestra productos con stock bajo |

## Ejemplos

- /suppliers – GET – Lista proveedores.
- /suppliers/new – GET/POST – Crear proveedor.
- /products – GET – Lista productos y permite filtrar por proveedor.
- /reports/low-stock – GET – Muestra productos con stock bajo.
