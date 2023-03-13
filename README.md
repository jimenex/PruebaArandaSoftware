# PruebaArandaSoftware
***
El Api esta desarrollado con C# NetFramework 4.7.2 utilizando Microsoft.EntityFramework
***
# Metodos Desarrollados:
***
1. GET /api/GetListaProductos: Retorna el listado de productos registrados en el sistema.
2. GET /api/GetProducto/{valor}: Retorna el listados de productos wue contengan el valor en los campos Nombre, Descripcion o Categoria.
3. POST /api/CrearProducto: Registra productos en el sistema.
4. PUT /api/EditarProducto/{id}: Modifica el producto según el Id.
5. DELETE /api/EliminarProducto/{id}: Elimina el producto según el Id.
***
# Generalidades:
***
1. Se entrega un Back el cual tienes las funcionalidades basicas CRUD.
2. Se entrega un Front en React el cual tienes las funcionalidades CRUD
3. Con respecto a la Imagen, se pensó de manera que se guardara un Base64 en base de datos,
   en el Front la imagen se carga pero no se puede modificar ni agregar cuando se crea un
   producto nuevo, esta funcionalidad no pudo ser implementada, aunque hay información al respecto
   y es la primera vez que hago algo en React no me funcionó.
# Conclución:
***
No creo haber logrado el objetivo de la prueba, aunque el servicio tiene las funcionalidades 
basicas del CRUD, la prueba exigia un nivel mas de complejidad en la implementación del Servicio.

¡Muchas gracias por la oportunidad!
