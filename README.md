# Enunciado de Proyecto: 
## Gestión de Tareas con API REST en Spring Boot y Documentación con Swagger
### Objetivo:
Desarrollar una API REST para la gestión de tareas utilizando Spring Boot. La aplicación debe permitir a los usuarios crear, leer, actualizar y eliminar tareas. Además, deberás implementar la base de datos usando H2 en memoria, documentar la API con Swagger, y desplegar la aplicación en la plataforma Render.
#### Requisitos:

**1. Modelado de Datos:**

* Implementa una entidad Task con los siguientes campos:
  * `id` (Long): Identificador único de la tarea.
  * `title` (String): Título de la tarea.
  * `description` (String): Descripción de la tarea.
  * `status` (enum): Estado de la tarea (TODO, IN_PROGRESS, DONE).
  * `createdAt` (Date): Fecha y hora de creación de la tarea.
  * `updatedAt` (Date): Fecha y hora de la última actualización de la tarea.
    
**2. Endpoints API:**

* POST /tasks: Crear una nueva tarea.
* GET /tasks: Obtener todas las tareas.
* GET /tasks/{id}: Obtener una tarea por su id.
* PUT /tasks/{id}: Actualizar una tarea existente.
* DELETE /tasks/{id}: Eliminar una tarea por su id.

**3. Persistencia:**

* Utiliza H2 como base de datos en memoria para la persistencia de datos.
  
**4. Documentación con Swagger:**
* Incluir Dependencias: Asegúrate de agregar las dependencias de Swagger en tu archivo pom.xml o build.gradle.
* Configuración: Configura Swagger para escanear tus controladores y generar la documentación automáticamente.
* Acceso a Swagger UI: La documentación generada debe ser accesible en http://localhost:8080/swagger-ui/.
* Personalización Opcional: Puedes personalizar la documentación usando anotaciones como @Api, @ApiOperation, y otros.

**5. Pruebas:**
* Realiza pruebas de los endpoints utilizando Postman o directamente desde la interfaz de Swagger UI. Documenta estas pruebas y adjunta capturas de pantalla que demuestren el funcionamiento correcto de la API.

**6. Despliegue:**
* Configura y despliega la aplicación en Render. Proporciona el enlace público de la API desplegada.
* Asegúrate de que Swagger UI sea accesible desde la API desplegada en Render.
  
**7. Documentación del Proyecto:**

* Crea un archivo README.md en el repositorio donde expliques cómo ejecutar la aplicación localmente, cómo utilizar la API, cómo fue desplegada en Render, y cómo acceder a la documentación de Swagger.
** Incluye capturas de pantalla y descripciones de las pruebas realizadas con Postman o Swagger UI.

**Entrega:**
* Sube el código fuente de la aplicación a un repositorio en GitHub.
* Incluye un enlace a la API desplegada en Render.
* Asegúrate de que el repositorio sea público y que el README.md esté bien documentado.
* Fecha límite de entrega: [Fecha de entrega].
