# Da Rule
Para poder subir una archivo debes comprobar los siguientes puntos :

  - Te aseguras de estas en la carpeta del repositorio.
  - Debes tener lo archivos que quieres subir dentro de la carpeta.

Teniendo listo esto, procedemos a abrir tu cmd (tecla windows + R) y ingresar las siguientes líneas de código.
```sh
$ git pull
```
Este comando sirve para actualizar el repositorio antes de subir nuestros archivos.
```sh
$ git status
```
Muestra el estado del repositorio, debes ver archivos en rojo los cuales son lo archivos que no se han subido.
```sh
$ git add .
```
Agregamos todos los archivos que se listaron anteriormente.
```sh
$ git status
```
Debemos ver la misma lista anteriormente solo que ahora de color verde.
```sh
$ git commit -m "mensaje"
```
Capturamos una instantánea de los archivos que se encuentran agregados.
```sh
$ git push
```
Cargamos el contendió del repositorio local al repositorio remoto.
