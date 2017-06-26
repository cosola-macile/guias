#Resolviendo conflictos

Esta guia es para resolver los conflictos con Git.

NOTA: Estos conflictos ocurren cuando existen choques entre el contenido de tu rama y el contenido de Master, como Git no sabe que contenido tomar, el tuyo o el de master, de ja que seas tú que decidas cual debe tomar.

## 1. Ver el archivo que tiene el conflicto, si tiene el conflicto contendrá la siguiente estructura:

<<<<<<< HEAD


```  Tu contenido...

========

``` El contenido de Master

>>>>>>> Master

## 2. Debes borrar lo que no quieres, si quieres los cambios de Master borras los cambios de tu rama y si quieres los de tu rama, entonces borra los de Master.

## 3. Luego de que arreglas los conflictos, el archivo está listo para ser añadido: usa ```git add.

## 4. ``` git commit

## 5. git push

Y conflicto resuelto. 