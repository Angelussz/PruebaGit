#Git Local
Para el uso de git primero debemos iniciar git con:
```
git init
```
Y lo volveremos una rama **MASTER** 

Luego si se tiene archivos dentro de la carpeta estaran de esta forma **UNCOMMITED** que estan fuera de la rama master la cual se puede ver con:
```
git status
```
Para que esten dentro de la rama master debemos utilizar el comando:
```
git add nombredelarchivo
```
O para agregar todos los archivos:
```
git add .
```
Asi poder hacer que git maneje versiones de estos archivos, osea si modificamos algo de este nos lo va a decir github.

Ahora cuando nosotros modificamos un archivo el controlador de versions git no va a poder hacer los cambios en el repositorio a no ser que le demos commit, ademas que te mostrara que un archivo y que lineas de este archivo se modificaron:
//imange
Luego para confirmar todos los cambios que hicimos le hacemos:
```
git commit -m "nombre del archivo"
```
Al realizar esto ya no nos mostrara estos mensajes de que alguien cambio algo del codigo o que modificaste
//imagen

Luego para ver todas las versiones de modificacion del codigo se utiliza:
```
git log
```
//imagen

