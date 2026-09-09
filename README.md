# Sistema de Gestión de Productos

## Descripción
El Sistema de Gestión de Productos permite registrar, consultar, modificar y eliminar productos de una empresa. El sistema permite administrar información como código, nombre, categoría, precio y stock de manera eficiente.

## Características
* Registrar productos nuevos en el sistema.
* Consultar la lista general y detalles de productos.
* Modificar datos existentes de los productos.
* Eliminar productos del registro.
* Buscar productos por categoría o nombre.
* Controlar y actualizar el stock en tiempo real.

## Tecnologías utilizadas
| Tecnología | Uso |
| --- | --- |
| C# | Lenguaje de programación |
| ASP.NET Core | Backend / Framework Web |
| PostgreSQL | Base de datos relacional |
| HTML5 | Estructura de la interfaz |
| CSS3 | Presentación y estilos |
| Git | Control de versiones |

## Requisitos
* .NET SDK 7.0 o superior
* PostgreSQL 14 o superior
* Git instalado en la máquina
* Visual Studio Code

## Instalación
1. Clonar el repositorio localmente.
2. Abrir el proyecto en el editor.
3. Configurar la cadena de conexión.
4. Crear la base de datos.
5. Ejecutar las migraciones.
6. Ejecutar la aplicación.

## Ejecución
Para iniciar la aplicación ejecuta:
```bash
dotnet run
```
## Estructura del proyecto
```text
SistemaProductos/
│
├── Controllers/
├── Models/
├── Views/
├── Data/
├── wwwroot/
├── Program.cs
└── README.md
```
## Base de datos
El sistema utiliza una tabla llamada `productos` con la siguiente estructura:

| Campo | Tipo de dato | Descripción |
| --- | --- | --- |
| id | INT / Primary Key | Identificador único |
| codigo | VARCHAR(50) | Código del producto |
| nombre | VARCHAR(100) | Nombre comercial |
| categoria | VARCHAR(50) | Categoría del producto |
| precio | DECIMAL(10,2) | Precio unitario |
| stock | INT | Cantidad disponible |
## Ejemplo de uso
Consulta de base de datos:
```sql
SELECT * FROM productos;
```
## Estado del proyecto
- [x] Diseño de base de datos
- [x] Modelo de datos
- [x] CRUD de productos
- [x] Consulta de productos
- [ ] Autenticación
- [ ] Reportes

> ⚠️ **Nota:** La autenticación todavía se encuentra en desarrollo.
## Autores
* **Chapilliquen Cruz, Cesia Jemina** - *Estudiante Tecsup*

---

## Conclusiones
1. La utilización del formato Markdown facilita enormemente la creación de documentación técnica clara y estructurada.
2. El uso adecuado de jerarquías, tablas y bloques de código permite transmitir información de forma ordenada y accesible.
3. El uso de repositorios en GitHub facilita la gestión y presentación de los trabajos del curso.
