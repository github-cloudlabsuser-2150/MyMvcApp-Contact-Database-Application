# MyMvcApp-Contact-Database-Application

## Descripción

MyMvcApp es una aplicación CRUD desarrollada en ASP.NET Core MVC que permite gestionar datos de contacto de personas. Incluye funcionalidades para crear, leer, actualizar, eliminar y buscar usuarios. Este proyecto demuestra el uso de GitHub Copilot para acelerar el desarrollo y la integración de IA en el flujo de trabajo de desarrollo de software.

---

## Características

- Listado de usuarios
- Visualización de detalles de usuario
- Creación de nuevos usuarios
- Edición de usuarios existentes
- Eliminación de usuarios
- Búsqueda de usuarios por nombre o email

---

## Estructura del Proyecto

- **Controllers/**: Lógica de negocio y endpoints (UserController.cs)
- **Models/**: Definición de entidades (User.cs)
- **Views/**: Vistas Razor para la interfaz de usuario
- **deploy.json**: Plantilla ARM para desplegar la aplicación en Azure
- **deploy.parameters.json**: Parámetros para la plantilla ARM
- **MyMvcApp.Tests/**: Pruebas unitarias con xUnit

---

## Despliegue en Azure con ARM

1. **Configura Azure CLI** y accede a tu suscripción.
2. **Crea un grupo de recursos** (si no existe):

   ```sh
   az group create --name <nombre-grupo> --location <ubicación>
   ```
