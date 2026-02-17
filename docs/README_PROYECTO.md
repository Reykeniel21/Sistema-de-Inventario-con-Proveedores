# Sistema de Inventario con Proveedores

## Descripción del sistema
Este sistema es una aplicación web desarrollada con Flask que permite administrar un inventario de productos asociados a proveedores. El sistema permite crear, editar, eliminar y visualizar proveedores y productos, así como generar un reporte de productos con bajo stock.

La aplicación utiliza una base de datos SQLite para almacenar la información y SQLAlchemy como ORM para la gestión de los datos.

## Cómo se ejecuta el sistema

1. Abrir el proyecto en Visual Studio Code.
2. Abrir el terminal integrado.
3. Asegurarse de estar en la carpeta raíz del proyecto.
4. Activar el entorno virtual:
   - En Windows:

      
      venv\Scripts\activate

5. Ejecutar la aplicación:

6. Abrir el navegador y acceder a:
- http://127.0.0.1:5000/products
- http://127.0.0.1:5000/suppliers

## Funcionalidades principales

- Gestión de proveedores (crear, editar y eliminar).
- Gestión de productos (crear, editar, eliminar y listar).
- Asociación de productos a proveedores.
- Filtro de productos por proveedor.
- Reporte de productos con stock bajo.
- Validaciones básicas en formularios.
