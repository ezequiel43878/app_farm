
Aplicacion web: FarmApp
=========
Sistema de consultas creado por alumnos del IFST 18, el objetivo fue actualizar el programa que venia utilizando una drogueria.
Alumnos:
- Bossa Camargo Sabrina
- Ramos Mauricio

Demo
=========
Vinculo de la demo :[http://ezequiel43878.pythonanywhere.com/](http://ezequiel43878.pythonanywhere.com/)

Funcionamiento
=========

El sistema cuenta con una serie de consultas:
- Productos consumidos por determinado cliente.
- Clientes que consumieron determinado producto
- N produtos mas vendidos.
- N clientes que gastaron mas dinero.

Para ingresar a dichas consultas el usuario tendra que crearse un cuenta y loguearse o bien utilizar la cuenta de prueba que posee la aplicacion.

Cuenta de prueba:
- Usuario: admin
- Contraseña: admin

Flujo de programa
=========
app.farm.py : Archivo principal de la aplicacion, contiene los enrutamientos del programa.

form.py: Archivo que contiene todos los formularios utilizados en la aplicacion

lectura_bd.py : Archivo que lee la base de datos y busca los siguientes errores:
- Que la base de datos sea inexistente.
- Que algun registro tenga una cantidad invalidad de campos.
- Que algun dato del campo "CODIGO" no este vacio.
- Que algun dato del campo "CANTIDAD" no contenga un numero entero.
- Que algun dato del campo "PRECIO" no contenga un valor decimal.

requierement.txt:  Archivo q contiene las librerias necesarias para correr la aplicacion.

templates: Carpeta que contiene los archivos htmls utilizados.

csv: Carpeta que contiene la base de datos y el csv donde se guardaran los datos de los usuarios que se registraran.

Instalación
=========
La aplicacion fue desarrollada con el microframework Flask.

Demo
=========
Vinculo de la demo : 
