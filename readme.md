# Clase-Fake-Api

## Instalación
Para poder ejecutar la API, primero se debe ejecutar "install.bat". Este script generará un entorno virtual de Python llamado "pythonapi-env" y luego instalará las dependencias del proyecto almacenadas en el archivo de requisitos "requirements.txt".


## Ejecución
Una vez generado el entorno virtual e instaladas las dependencias, puedes ejecutar "boot.bat". Este script iniciará la API. Después de ejecutarlo, se podrá comenzar a acceder a la API. Esta estará disponible en el puerto 5000.

### Metodos 

- **POST localhost:5000/products** - Agregar un producto.
- **GET localhost:5000/product/{id}** - Obtener un producto en base a su {id}.
- **GET localhost:5000/products** - Obtener todos los productos.
- **GET localhost:5000/products?precioMinimo={precio}** - Obtener todos los productos con un precio mayor a {precio}.
- **GET localhost:5000/products?precioMaximo={precio}** - Obtener todos los productos con un precio menor a {precio}.
- **GET localhost:5000/products?precioMinimo={precioMínimo}&precioMaximo={precioMáximo}** - Obtener todos los productos con un precio mayor a {precioMínimo} y menor a {precioMáximo}.
- **DELETE localhost:5000/product/{1}** - Eliminar un producto en base a su {id}.
- **PUT localhost:5000/product/{1}** - Actualizar un producto en base a su {id}.