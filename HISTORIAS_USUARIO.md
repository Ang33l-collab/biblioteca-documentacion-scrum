# Historias de usuario

## HU-01. Registrar usuarios

**Como** administrador de la biblioteca,  
**quiero** registrar nuevos usuarios,  
**para** permitirles utilizar los servicios de la biblioteca.

### Criterios de aceptación

- El sistema debe solicitar nombre, apellido, correo, contraseña y rol.
- El correo electrónico no debe repetirse.
- El usuario debe guardarse con estado Activo.
- El usuario debe aparecer en la lista después del registro.

---

## HU-02. Editar usuarios

**Como** administrador,  
**quiero** modificar la información de los usuarios,  
**para** mantener sus datos actualizados.

### Criterios de aceptación

- Debe ser posible modificar nombre, apellidos, teléfono, correo y rol.
- La contraseña puede conservarse si el campo se deja vacío.
- Los cambios deben reflejarse en la base de datos.
- Los cambios deben aparecer en Angular, React y jQuery.

---

## HU-03. Desactivar usuarios

**Como** administrador,  
**quiero** desactivar usuarios,  
**para** impedir que las cuentas que ya no se utilizan aparezcan en nuevos préstamos.

### Criterios de aceptación

- El registro no debe eliminarse físicamente.
- El estado debe cambiar a Inactivo.
- Los usuarios inactivos no deben aparecer en el selector de alumnos.

---

## HU-04. Registrar libros

**Como** bibliotecario,  
**quiero** registrar libros,  
**para** mantener actualizado el catálogo de la biblioteca.

### Criterios de aceptación

- El título, categoría y autor son obligatorios.
- Debe registrarse el número total de ejemplares.
- Los ejemplares disponibles no pueden superar a los totales.
- El libro debe aparecer en el catálogo después de guardarse.

---

## HU-05. Buscar libros

**Como** usuario del sistema,  
**quiero** buscar libros,  
**para** localizar rápidamente un título dentro del catálogo.

### Criterios de aceptación

- Se debe poder buscar por título.
- Se debe poder buscar por ISBN.
- Se debe poder buscar por editorial.
- Se debe poder buscar por categoría o autor.
- Debe existir una opción para mostrar nuevamente todos los libros.

---

## HU-06. Editar libros

**Como** bibliotecario,  
**quiero** modificar la información de un libro,  
**para** corregir datos o actualizar el número de ejemplares.

### Criterios de aceptación

- Deben poder modificarse los datos bibliográficos.
- Los ejemplares disponibles deben mantenerse dentro del rango permitido.
- El estado debe cambiar automáticamente a Agotado cuando no existan ejemplares.
- Los cambios deben reflejarse en los tres frontends.

---

## HU-07. Registrar préstamos

**Como** bibliotecario,  
**quiero** registrar el préstamo de un libro,  
**para** controlar qué alumno tiene cada ejemplar.

### Criterios de aceptación

- Solo deben aparecer alumnos activos.
- Solo deben aparecer libros disponibles.
- La cantidad no puede superar los ejemplares disponibles.
- Al registrar el préstamo debe disminuir la disponibilidad del libro.
- El préstamo debe aparecer en la lista de préstamos activos.

---

## HU-08. Registrar devoluciones

**Como** bibliotecario,  
**quiero** registrar la devolución de un préstamo,  
**para** devolver los ejemplares al catálogo disponible.

### Criterios de aceptación

- El estado debe cambiar a Devuelto.
- Debe registrarse la fecha real de devolución.
- El préstamo debe desaparecer de la lista de activos.
- Los ejemplares disponibles deben incrementarse.

---

## HU-09. Consultar historial

**Como** administrador o bibliotecario,  
**quiero** consultar el historial de préstamos,  
**para** conocer los movimientos realizados por los alumnos.

### Criterios de aceptación

- Debe mostrarse un historial general.
- Debe existir un historial filtrado por alumno.
- Deben mostrarse las fechas de préstamo y devolución.
- Debe mostrarse el estado de cada préstamo.

---

## HU-10. Actualizar préstamos vencidos

**Como** bibliotecario,  
**quiero** identificar automáticamente los préstamos vencidos,  
**para** dar seguimiento a los libros que no se devolvieron a tiempo.

### Criterios de aceptación

- Los préstamos activos cuya fecha límite haya pasado deben cambiar a Vencido.
- Los préstamos devueltos no deben modificarse.
- La actualización debe reflejarse en las tres aplicaciones.

---

## HU-11. Iniciar sesión en el portal

**Como** administrador,  
**quiero** iniciar sesión en el portal principal,  
**para** seleccionar la versión del sistema que voy a utilizar.

### Criterios de aceptación

- El sistema debe validar correo y contraseña.
- Solo los usuarios con rol Administrador deben acceder.
- Las cuentas inactivas no deben entrar.
- La sesión debe mantenerse mientras no se cierre manualmente.

---

## HU-12. Registrar administradores

**Como** responsable de la biblioteca,  
**quiero** registrar nuevas cuentas administrativas,  
**para** permitir que otros responsables accedan al portal.

### Criterios de aceptación

- El registro debe solicitar datos personales, correo y contraseña.
- Las contraseñas deben coincidir.
- La contraseña debe contener al menos seis caracteres.
- La cuenta debe guardarse con el rol Administrador.

---

## HU-13. Seleccionar frontend

**Como** administrador,  
**quiero** seleccionar Angular, React o jQuery,  
**para** utilizar cualquiera de las tres implementaciones del sistema.

### Criterios de aceptación

- El portal debe mostrar las tres aplicaciones disponibles.
- Cada botón debe abrir la aplicación correspondiente.
- Las aplicaciones deben compartir la misma información.
- El portal debe mostrar el estado de las APIs.