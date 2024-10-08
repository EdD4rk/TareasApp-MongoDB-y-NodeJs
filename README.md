# Tareas App!

Tareas App es una aplicación CRUD desarrollada con Node.js, Express, MongoDB y JavaScript. Su objetivo principal es gestionar tareas mediante operaciones básicas de creación, lectura, actualización y eliminación. Este proyecto fue desarrollado con el propósito de aprender y aplicar el uso de bases de datos NoSQL, específicamente MongoDB, en el contexto de un entorno de desarrollo web moderno. 

![](docs/ScreenshotTareasApp.png)

### Con esta Aplicacion pondemos hacer:

```bash
☑ Registrarse, iniciar sesión y cerrar sesión
☑ Crear nuevas tareas
☑ Leer tareas existentes
☑ Actualizar tareas
☒ Eliminar tareas
```
#### Requirimientos:

* Se requiere instalar MongoDB, Node Js, MongoDB debe estar iniciado y funcionando.

### Instalacion e implementacion:

```sh
git clone https://github.com/EdD4rk/TareasApp-MongoDB-y-NodeJs.git
cd TareasApp-MongoDB-y-NodeJs
npm i
npm run dev # run in development mode
npm start # run in production mode
```
* Ahora puedes visitar: <a target="_blank" href="http://localhost:4000">http://localhost:4000</a>

### Esta aplicación necesita las siguientes variables de entorno:

- `MONGODB_URI` esta es la cadena URI de Mongodb.
- `PORT` el puerto http del servidor para la aplicación.
- `NODE_ENV` Entorno de nodo.

### Usuario predeterminado

Cuando se inicie la aplicación, se creará un usuario administrador con las siguientes credenciales:

- correo electrónico: `admin@localhost`
- contraseña: `adminpassword`

Además, la aplicación permite a los usuarios registrarse, iniciar sesión y cerrar sesión para gestionar su lista de tareas de manera personalizada. Este proyecto fue desarrollado con el propósito de aprender y aplicar el uso de bases de datos NoSQL, específicamente MongoDB, en un entorno de desarrollo web moderno.
