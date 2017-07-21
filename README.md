# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
# Experiencia22

Actividad 022 - Scaffolding

Para poder realizar este actividad debes haber realizado los cursos previos junto con los videos online correspondientes a la experiencia 11.

Ejercicio 1: Segundo Proyecto.


Crear un proyecto llamado second_app.

Inicializar Git.

Primer commit.

Crear un scaffold de Student con los campos name y age:integer.

Verificar que el archivo migración contenga los cambios necesarios y correr la migración.

Confirmar -en el Schema- que la migración haya corrido correctamente.

Convertir Index de students en la página de inicio.

Segundo commit.

Ingresar 2 estudiantes utilizando rails console y el método create.

Ingresar 1 estudiantes a través de la aplicación.

Comprobar que los registros se crearon correctamente.

Agregar el CDN de una plantilla de Bootswatch.

Agregar las clases de botones de Bootswatch a los links de Show, Edit y Destroy. ss-students

Tercer commit.

Agregar un campo nuevo al modelo Student llamado email de tipo string.

Revisar y correr la migración.

Ingresar un nuevo estudiante mediante rails console (incluir el campo email).

Modificar el form de registro de estudiantes para que permita ingresar el correo.

Agregar el campo email a los strong params en el controlador students.

Cuarto commit.

Crear un nuevo controlador llamado pages con la página landing.

En el método landing consultar todos los registros de Student y almacenarlos en una variable de instancia @students

En la vista de landing iterar la colección @students y listar -en una tabla- todos los estudiantes con su respectivo email.

Agregar un navbar de Bootswatch al layout.

El navbar sólo debe contener 2 links: uno a index y uno a landing.

Quinto commit.

Crear un repositorio en GitHub.

Añadir el remote al repositorio de GitHub y hacer push.

Inicializar proyecto en Heroku y hacer push.
https://hidden-cliffs-93153.herokuapp.com/
