# Milestone 0 (interno): Estructura Inicial del Proyecto

## Descripción
Establecer la base del proyecto y organizar los módulos necesarios para la aplicación.

## Producto Mínimamente Viable (PMV)
Se ha creado la estructura básica de la aplicación, incluyendo la organización de módulos y clases necesarias para el desarrollo.

## Requisitos Técnicos
- **Estructura de Carpetas del Proyecto**:
  - `src/`: Contendrá el código fuente de la aplicación.
  - `src/models/`: Definiciones de los modelos de datos, como `Usuario`, `Rutina`, `Ejercicio`.
  - `src/controllers/`: Lógica de negocio para manejar las interacciones con los modelos (por ejemplo, `UsuarioController`, `RutinaController`).
  - `src/routes/`: Definición de las rutas de la API (por ejemplo, `authRoutes.js`, `userRoutes.js`).
  - `src/views/`: Vistas de la aplicación (si aplica, en caso de usar un framework frontend).
  - `tests/`: Para las pruebas unitarias, con subcarpetas por módulo.
- **Configuración de Entorno**:
  - Inicializar un archivo `package.json` si se usa Node.js.
  - Configuración de las dependencias necesarias (como Express, Mongoose, etc.).
  - Configuración de la base de datos (MongoDB, MySQL, etc.) y conexión inicial.
