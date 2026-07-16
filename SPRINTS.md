# Planeación de sprints

El desarrollo se organizó en cinco sprints. Cada sprint incluyó planeación, desarrollo, pruebas y revisión del incremento obtenido.

## Sprint 1. Base de datos y microservicios

### Objetivo

Construir la base técnica del sistema mediante MariaDB y tres microservicios REST.

### Elementos trabajados

- PB-01: Base de datos.
- PB-02: API Usuarios.
- PB-03: API Libros.
- PB-04: API Préstamos.

### Incremento obtenido

- Base de datos biblioteca.
- Tablas relacionadas mediante llaves foráneas.
- Endpoints CRUD para usuarios.
- Endpoints CRUD para libros.
- Registro, devolución e historial de préstamos.
- Conexión de las tres APIs a MariaDB.

### Pruebas realizadas

- Consultas GET desde el navegador.
- Pruebas POST, PUT y DELETE.
- Verificación directa de registros en MariaDB.
- Comprobación de puertos 3001, 3002 y 3003.

---

## Sprint 2. Aplicación completa con Angular 21

### Objetivo

Implementar todos los módulos del sistema utilizando Angular 21.

### Elementos trabajados

- PB-05: Usuarios en Angular.
- PB-06: Libros en Angular.
- PB-07: Préstamos en Angular.

### Incremento obtenido

- Panel de estadísticas.
- Administración de usuarios.
- Administración de libros.
- Gestión de préstamos.
- Historial por alumno.
- Historial general.
- Actualización de préstamos vencidos.
- Consumo de las tres APIs.

### Pruebas realizadas

- Registro y edición de usuarios.
- Registro, búsqueda y edición de libros.
- Registro y devolución de préstamos.
- Compilación de Angular sin errores.
- Revisión de consola del navegador.

---

## Sprint 3. Aplicaciones React y jQuery

### Objetivo

Reproducir la funcionalidad completa de Angular utilizando React y jQuery.

### Elementos trabajados

- PB-08: Sistema React.
- PB-09: Sistema jQuery.
- PB-10: Información compartida.

### Incremento obtenido

- Aplicación React completa.
- Aplicación jQuery completa.
- Consumo de los tres microservicios.
- Formularios, tablas, búsquedas y estadísticas.
- Sincronización mediante una base de datos compartida.

### Pruebas realizadas

- Registro de información desde React.
- Consulta de los cambios desde Angular.
- Registro de información desde jQuery.
- Consulta de los cambios desde Angular y React.
- Compilación de producción de React.

---

## Sprint 4. Portal principal e integración

### Objetivo

Crear un portal para controlar el acceso administrativo y seleccionar el frontend.

### Elementos trabajados

- PB-11: Portal principal.
- PB-12: Inicio de sesión.
- PB-13: Registro de administradores.
- PB-14: Estado de APIs.
- PB-15: Navegación a frontends.

### Incremento obtenido

- Inicio de sesión para administradores.
- Validación de roles.
- Registro de cuentas administrativas.
- Sesión almacenada en el navegador.
- Estado de microservicios.
- Acceso a Angular, React y jQuery.

### Pruebas realizadas

- Inicio de sesión con administrador.
- Rechazo de acceso para alumnos.
- Registro de un nuevo administrador.
- Cierre y restauración de sesión.
- Apertura de los tres frontends.

---

## Sprint 5. Repositorios, despliegue y documentación

### Objetivo

Preparar el proyecto para su entrega y publicación en internet.

### Elementos considerados

- PB-16: Repositorios independientes.
- PB-17: Publicación en GitHub.
- PB-18: Variables de producción.
- PB-19: Servidor.
- PB-20: Publicación de aplicaciones.
- PB-21: Dominio o subdominios.
- PB-22: HTTPS.
- PB-23: Pruebas finales.
- PB-24: Evidencias.

### Resultado esperado

- Proyectos publicados en GitHub.
- Historial de commits disponible.
- Servidor configurado.
- Aplicaciones accesibles mediante internet.
- Dominio o subdominios configurados.
- Certificados HTTPS activos.
- Documento final con capturas y evidencias.