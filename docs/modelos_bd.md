# Modelos de Base de Datos

## Tabla Supplier

La tabla Supplier almacena la información de los proveedores.

### Columnas:
- id: Integer, clave primaria.
- name: String (120), obligatorio.
- contact_email: String (120), opcional.
- phone: String (120), opcional.

### Relación:

- Un proveedor puede tener múltiples productos asociados (relación uno a muchos).

## Tabla Product

La tabla Product almacena la información de los productos del inventario.

### Columnas:
- id: Integer, clave primaria.
- supplier_id: Integer, clave foránea que referencia a Supplier.id.
- name: String (120), obligatorio.
- sku: String (80), único y obligatorio.
- stock: Integer, obligatorio.
- unit_price: Float, obligatorio.

### Relación:
- Cada producto pertenece a un proveedor.
- Relación muchos a uno con Supplier.
