#Resolviendo conflictos

Esta guia es para resolver conflictos con Git.

NOTA: Conflictos ocurren cuando existen choques entre el contenido de tu rama y el contenido de Master. Como Git no sabe que contenido escoger, el tuyo o el de Master, deja que seas tú, o alguien con autoridad, quien decida cual contenido aceptar.

## 1. Ver el archivo que tiene el conflicto, si tiene el conflicto contendrá la siguiente estructura:

<<<<<<< HEAD


```  Tu contenido...

========

``` El contenido de Master

>>>>>>> Master

## 2. Debes borrar cambios que no quieres mantener. Si quieres los cambios de Master, borras los cambios de tu rama; si quieres los de tu rama, entonces borra los de Master.

## 3. Luego de que arreglas los conflictos, el archivo está listo para ser añadido: usa ```git add.

## 4. ``` git commit

## 5. git push

Y conflicto resuelto. 