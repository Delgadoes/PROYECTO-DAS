# PROYECTO-DAS


## Gestión de Eventos y Tareas Colaborativas

### Descripción del Proyecto
Este proyecto consiste en una aplicación web diseñada para la gestión de eventos y tareas colaborativas dentro de una empresa organizadora de eventos. La aplicación se basa en una arquitectura de microservicios, lo que garantiza modularidad y facilidad de mantenimiento. Las funciones clave incluyen la creación y administración de eventos, asignación de tareas y notificaciones automáticas, todo con el objetivo de mejorar la organización y seguimiento de tareas, facilitando la colaboración entre los miembros de la empresa.

### Tabla de Contenidos
- [Objetivo General](#objetivo-general)
- [Objetivos Específicos](#objetivos-específicos)
- [Restricciones Arquitectónicas](#restricciones-arquitectónicas)
- [Plataforma Tecnológica](#plataforma-tecnológica)
- [Modelo de Datos](#modelo-de-datos)
- [Cómo Ejecutar el Proyecto](#cómo-ejecutar-el-proyecto)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

### Objetivo General
Desarrollar una aplicación web en ASP.NET Core que permita a los usuarios gestionar eventos y tareas colaborativas dentro de una empresa organizadora de eventos, utilizando una arquitectura de microservicios para asegurar escalabilidad y eficiencia.

### Objetivos Específicos
- Implementar un sistema de gestión de eventos que permita a los usuarios crear, modificar, eliminar y visualizar eventos.
- Desarrollar un módulo de gestión de tareas, permitiendo la asignación y el seguimiento de tareas relacionadas con los eventos.
- Asegurar la comunicación entre los componentes del sistema a través de un API Gateway que gestione las solicitudes a los microservicios.
- Garantizar la seguridad de las transacciones a través de HTTPS y prácticas de autenticación y autorización.
- Proporcionar una documentación clara del sistema utilizando Swagger para facilitar la integración y el uso de la API.

## Restricciones Arquitectónicas
- La arquitectura debe estar basada en microservicios, lo que implica una separación clara entre los servicios de eventos, tareas, usuarios y notificaciones.
- La base de datos será de tipo relacional (SQL), y cada microservicio tendrá acceso exclusivo a su propio almacenamiento para mantener la independencia.
- La seguridad es prioritaria, por lo que las comunicaciones entre servicios deben estar cifradas utilizando HTTPS.
- El API Gateway manejará todas las solicitudes de los usuarios hacia los microservicios.

## Plataforma Tecnológica
El desarrollo de la aplicación se realizó utilizando las siguientes tecnologías:
- **Backend:** ASP.NET Core 6.0
- **Frontend:** Blazor
- **Base de datos:** SQL Server
- **Seguridad:** HTTPS y autenticación JWT
- **API Gateway:** Para gestionar las solicitudes entre los usuarios y los microservicios
- **Documentación:** Swagger

## Modelo de Datos
El modelo físico de datos describe cómo se almacenan los datos en la base de datos. Las principales entidades son:
- **Usuario:** Representa a los usuarios del sistema.
- **Evento:** Contiene los detalles de los eventos.
- **Tarea:** Gestiona las tareas relacionadas con los eventos.
- **Notificación:** Registra las notificaciones enviadas a los usuarios.

## Cómo Ejecutar el Proyecto
1. Clona este repositorio en tu máquina local.
2. Asegúrate de tener instalado ASP.NET Core SDK y SQL Server.
3. Ejecuta el comando `dotnet run` en el directorio del proyecto para iniciar la aplicación.
4. Accede a la aplicación a través de tu navegador.

## Contribuciones
Las contribuciones son bienvenidas. Si deseas contribuir a este proyecto, por favor sigue estos pasos:
1. Haz un fork del repositorio.
2. Crea una nueva rama (git checkout -b feature/nueva-caracteristica).
3. Realiza tus cambios y haz un commit (git commit -m 'Añadir nueva característica').
4. Sube tus cambios (git push origin feature/nueva-caracteristica).
5. Abre una solicitud de extracción.

## Licencia
Este proyecto es un trabajo realizado para fines académicos y no está destinado a la distribución pública. 

