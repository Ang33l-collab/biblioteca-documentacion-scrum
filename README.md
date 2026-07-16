# Sistema Web de Biblioteca con Microservicios

## Descripción general

El proyecto consiste en un sistema web para la administración de una biblioteca. Permite gestionar usuarios, libros y préstamos mediante una arquitectura basada en microservicios.

El sistema cuenta con tres aplicaciones frontend independientes:

- Angular 21.
- React.
- jQuery.

Las tres aplicaciones ofrecen las mismas funciones y consumen los mismos microservicios REST, por lo que comparten la información almacenada en una base de datos MariaDB.

También se desarrolló un portal principal que permite a los administradores iniciar sesión y seleccionar la versión del sistema que desean utilizar.

## Objetivo general

Desarrollar un sistema web de biblioteca utilizando una arquitectura de microservicios y diferentes tecnologías frontend, permitiendo la administración centralizada de usuarios, libros y préstamos.

## Objetivos específicos

- Implementar un microservicio para la administración de usuarios.
- Implementar un microservicio para la administración de libros.
- Implementar un microservicio para la administración de préstamos.
- Desarrollar una versión completa del sistema con Angular 21.
- Desarrollar una versión completa del sistema con React.
- Desarrollar una versión completa del sistema con jQuery.
- Utilizar una sola base de datos para mantener sincronizada la información.
- Crear un portal principal para administradores.
- Utilizar Git y GitHub para el control de versiones.
- Publicar el sistema en un servidor con dominio y HTTPS.

## Arquitectura del sistema

El proyecto utiliza tres microservicios:

| Microservicio | Puerto local | Función principal |
|---|---:|---|
| API Usuarios | 3001 | Administración de usuarios, roles e inicio de sesión |
| API Libros | 3002 | Administración de libros, autores y categorías |
| API Préstamos | 3003 | Registro de préstamos, devoluciones e historial |

Aplicaciones frontend:

| Aplicación | Puerto local | Tecnología |
|---|---:|---|
| Portal principal | 5600 | HTML, CSS y JavaScript |
| Angular | 4200 | Angular 21 y TypeScript |
| React | 5173 | React y Vite |
| jQuery | 5500 | HTML, CSS, JavaScript y jQuery |

Base de datos:

- Sistema gestor: MariaDB.
- Puerto local: 3307.
- Nombre de la base: biblioteca.

## Funciones principales

### Usuarios

- Registrar usuarios.
- Editar información.
- Consultar usuarios.
- Asignar roles.
- Activar o desactivar cuentas.
- Iniciar sesión como administrador.

### Libros

- Registrar libros.
- Editar libros.
- Buscar libros.
- Consultar autores y categorías.
- Controlar ejemplares disponibles.
- Desactivar libros.

### Préstamos

- Registrar préstamos.
- Consultar préstamos activos.
- Registrar devoluciones.
- Actualizar préstamos vencidos.
- Consultar historial por alumno.
- Consultar historial general.

## Metodología

El proyecto se organizó mediante Scrum, utilizando:

- Product Backlog.
- Historias de usuario.
- Priorización de requisitos.
- Organización del trabajo por sprints.
- Revisión funcional al finalizar cada sprint.
- Control de versiones mediante Git.