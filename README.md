# Laravel Todo App

## Requirements

### Objetivo  
Desarrollar una aplicación en Laravel en la que se implementen los principios básicos ya vistos del manejo de vistas, rutas, controllers y acceso a datos.  
### Desarrollo  
- Crear en DB la tabla "todos", la cual va a tener las columnas: id (int PK autoincrement), todo (varchar(512) NOT NULL), done (int NOT NULL).    
- Hacer una vista "todos" en donde se muestren todos los ToDos. Estos se pueden mostrar en formato de tabla. Debe estar ligado a un controller para traerse los registros de la DB.    
- Hacer la funcionalidad de agregar un nuevo ToDo, esta puede estar en otra vista o un solo campo de texto y un botón de agregar en la vista principal. Al agregar se debe regresar o mostrar el registro del ToDo agregado en la tabla de la vista "todos". Al agregar, el ToDo se esta en estatus de pendiente.    
- Hacer una vista para editar un ToDo, de la lista poder mostrar un link de [Editar] y este redirija a otra página en la que se pueda editar el ToDo seleccionado, al guardar debe actualizarse el registro en DB y hacer el redirect a la página/vista todos.  
- En la lista principal de los ToDos, implementar la funcionalidad de actualizar el estatus, a realizada. También implementar la funcionalidad de regresar el estatus a pendiente.  
- En la lista principal, implementar la opción de borrar un ToDo.  
### Entregables
Imagenes de la aplicación funcionando, con todas las funcionalidades.  
Source code del proyecto en un ZIP.  
