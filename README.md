# API Clientes Semana 9 - AIEP

Proyecto de API REST en PHP + MySQL para gestionar clientes y pedidos.

## Instalación
1. Clonar el repositorio: `git clone https://github.com/diegobarahonab-ctrl/api_clientes_Semana9_AIEP.git`
2. Importar `database.sql` en MySQL (phpMyAdmin o consola).
3. Copiar la carpeta `api_clientes` dentro de `htdocs` de XAMPP.
4. Probar los endpoints con Postman usando la colección incluida en `/postman`.

## Endpoints principales
- GET `/api_clientes/clientes.php`
- POST `/api_clientes/clientes.php`
- PUT `/api_clientes/clientes.php?id=1`
- DELETE `/api_clientes/clientes.php?id=1`

## Seguridad
- Conexión con PDO y consultas preparadas para prevenir inyección SQL.
- Validaciones de correo, ID y datos de entrada.

## Evidencias
- Carpeta `/assets` con capturas de Postman y diagramas.
- Colección Postman exportada en `/postman`.

## Autor
Diego Barahona - Taller de Plataformas Web
****************************