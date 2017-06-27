#Resolviendo conflictos

Esta guia es para resolver conflictos con Git.

NOTA: Conflictos ocurren cuando existen choques entre el contenido de tu rama y el contenido de Master. Como Git no sabe que contenido escoger, el tuyo o el de Master, deja que seas tú, o alguien con autoridad, quien decida cual contenido aceptar.

## 1. 
Ver el archivo que tiene el conflicto.
Si tiene el conflicto contendrá una estructura como lo muestra el siguiente ejemplo:

```
<<<<<<< HEAD


Tu contenido...

<h1>MACILE</h1>
<p>Matemáticas, Ciencias, Ingeniería y lenguaje</p>

========

El contenido de Master...

<h1>MACILE</h1>
<p>Mathematics, Science, Engineering and Language</p>

>>>>>>> Master
```

## 2.
 Debes borrar cambios que no quieres mantener. Si quieres los cambios de Master, borras los cambios de tu rama; si quieres los de tu rama, entonces borra los de Master.

## 3. 
 Luego de resolver los conflictos, el archivo está listo para ser añadido. 
```
Usa "git add".
```

## 4.
 ```
 "git commit"
 ```

## 5. 
```
"git push"
```

Y conflicto resuelto. 