# Universidad de los Sabios

Este proyecto tiene como objetivo la gestión integral de una universidad, permitiendo administrar profesores, alumnos, horarios, materias, matrículas y asignaturas. La aplicación está construida utilizando tecnologías web modernas, como JavaScript, Bootstrap, CSS y HTML, y almacena los datos en un archivo JSON para simplificar el manejo de la información.

## Características destacadas

- **Interacción Asíncrona con el Backend:** El proyecto utiliza `async` y `fetch` para manejar operaciones de red de manera eficiente. Las solicitudes asíncronas permiten interactuar con un servidor backend para crear, actualizar y eliminar registros de diferentes entidades (profesores, alumnos, asignaturas, etc.) sin recargar la página. Esto asegura una experiencia de usuario más fluida y reactiva.

- **Gestión Dinámica de Datos:** La aplicación permite la creación, búsqueda y eliminación de registros mediante formularios dinámicos. Los formularios se generan y gestionan en el DOM utilizando JavaScript, proporcionando una interfaz de usuario intuitiva. Cada tipo de dato (profesores, alumnos, asignaturas, etc.) tiene una estructura definida y se maneja de acuerdo a sus requisitos específicos.

- **Operaciones CRUD:**
  - **Crear:** Los usuarios pueden agregar nuevos registros a través de formularios específicos para cada entidad. Los datos se validan antes de enviarse al servidor mediante solicitudes `POST` usando `fetch`. Esto garantiza que los registros se ingresen correctamente y que no haya duplicados.
  - **Leer:** Los datos se muestran en tablas actualizadas dinámicamente en la página sin necesidad de recargarla. Cada tipo de dato tiene su propia vista, que se actualiza al interactuar con la aplicación.
  - **Actualizar:** Aunque el código actual no muestra una función explícita para actualizar datos, la estructura del proyecto permite implementar esta funcionalidad fácilmente. Las solicitudes `PUT` o `PATCH` pueden ser utilizadas para modificar registros existentes.
  - **Eliminar:** Los usuarios pueden eliminar registros por ID mediante solicitudes `DELETE`. La interfaz se actualiza automáticamente para reflejar los cambios después de una eliminación.

- **Validación y Manejo de Errores:** El código incluye validaciones para asegurar que todos los campos de los formularios estén completos y correctos antes de realizar una solicitud al servidor. Además, se manejan errores en las solicitudes de red, proporcionando retroalimentación al usuario en caso de fallos.

- **Interfaz de Usuario Intuitiva:** La interfaz utiliza Bootstrap para una presentación atractiva y accesible. Los formularios y botones están diseñados para ser claros y fáciles de usar, mejorando la experiencia general del usuario.

## Enlace al Proyecto

Para más detalles, puedes acceder al proyecto en el siguiente enlace:

[Proyecto Universidad de los Sabios](https://danyellegiraldo.github.io/Proyecto-Javascript.github.io/)
