Descripcióm: Backend de una aplicación To Do list

# Todo App Backend 

Este repositorio contiene el código del backend para la aplicación de lista de tareas (Todo App). Se encarga de gestionar la conexión a la base de datos y proveer una API RESTful para realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar).

## Despliegue en Vivo (Render)

El backend ha sido desplegado exitosamente y está accesible públicamente en la siguiente URL:

**URL Base:** https://todoapp-backend-ju2o.onrender.com

**Ruta principal de la API para probar los datos:**
* `GET` a [https://todoapp-backend-ju2o.onrender.com/api/todos](https://todoapp-backend-ju2o.onrender.com/api/todos)

## Tecnologías Utilizadas

* **Node.js** - Entorno de ejecución
* **MongoDB Atlas** - Base de datos en la nube
* **Mongoose** - Modelado de objetos (ODM)

## Configuración Local

Si deseas correr este proyecto de manera local:

1. Clona el repositorio: `git clone https://github.com/ingac98/todoapp-backend.git`
2. Instala las dependencias: `pnpm install`
3. Configura tus variables de entorno en un archivo `.env` (MONGO_URI y PORT).
4. Inicia el servidor: `node server.js`