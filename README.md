# Prueba de Concepto - API REST

Este repositorio contiene una prueba de concepto para una API REST desarrollada con fines educativos y de demostración.

## Descripción

Este proyecto implementa una API RESTful que proporciona operaciones CRUD (Crear, Leer, Actualizar y Eliminar) para gestionar recursos a través de endpoints HTTP. La API sigue los principios de diseño REST y utiliza JSON como formato de intercambio de datos.

## Características

- Arquitectura RESTful completa
- Operaciones CRUD para gestionar recursos
- Autenticación mediante tokens JWT
- Documentación interactiva con Swagger/OpenAPI
- Validación de datos de entrada
- Manejo de errores estandarizado
- Pruebas unitarias y de integración

## Tecnologías Utilizadas

- Node.js y Express.js para el backend
- MongoDB como base de datos NoSQL
- Mongoose para el modelado de objetos
- JWT para la autenticación
- Jest para las pruebas
- Swagger para la documentación

## Endpoints Principales

La API proporciona los siguientes endpoints:

- `GET /api/recursos` - Obtener todos los recursos
- `GET /api/recursos/:id` - Obtener un recurso específico
- `POST /api/recursos` - Crear un nuevo recurso
- `PUT /api/recursos/:id` - Actualizar un recurso existente
- `DELETE /api/recursos/:id` - Eliminar un recurso

## Instalación y Uso

1. Clonar el repositorio:
   ```
   git clone https://github.com/Chepe-Git/Prueba-Api-Rest1.git
   cd Prueba-Api-Rest1
   ```

2. Instalar dependencias:
   ```
   npm install
   ```

3. Configurar variables de entorno:
   ```
   cp .env.example .env
   ```

4. Iniciar el servidor:
   ```
   npm start
   ```

5. Para desarrollo con recarga automática:
   ```
   npm run dev
   ```

## Documentación

La documentación de la API está disponible en `/api-docs` cuando el servidor está en ejecución.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue para discutir los cambios importantes antes de crear un pull request.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.