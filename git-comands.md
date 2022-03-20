# Comandos git
### Importante

En los comandos no se debe colar \'<>\', solo se puso para aclarar que eso se debe reemplazar por algo.  
**Ejemplo**:

Si aparece este codigo ' **git branch \<nombre de la rama\>** ' en realidad el comando debe quedar \' **git branch prueba** \' , en donde \'prueba\' se debe reemplazar por el nombre del branch que deseamos crear.

## Fundamentales
Comenzar el proyecto, agregar git a el proyecto.

```git
git init
```

Añadir todos los archivos al staging area (area de preparación) para luego ser guardados en un commit

Si desea añadir un solo arhivo, tendrá que cambiar el \".\" por el nombre del archivo

```
git add .
```

Revisar el estado de los archivos del proyecto, los que están actualmente en el proyecto y los del staging area

```
git status -s
```

Realizar un commit, guardar una copia del código que está en el staging area
```
git commit -m "Texto que describa el commit"
```

Ver todos los commits que se han creado
```
git log --oneline
```

Volver a un commit que se creó anteriormente. Primero debemos ver todos los commits que tengamos y copiar el codigo al que queremos regresar
```
git reset -hard <codigo del commit>
```

Configurar el repositorio para subirlo a github
```
git remote add origin <enlace de la carpeta de github>
```

Subir el repositorio a github
```
git push origin master
```

## Ramas

Crear una rama
```
git branch <nombre de la rama>
```

Ver todas las ramas que hayan
```
git branch
```

Moverse de una rama a otra
```
git checkout <nombre de la rama>
```

Eliminar una rama
```
git branch -d <nombre de la rama>
```

Unir una rama con la rama original, se debe entar en la rama principal que por lo general es la rama llamada \'main\'
```
git merge <nombre de la rama>
```

***
Creado por [Jhon Camargo](http://jhoncamargo.000webhostapp.com "Página web de Jhon Camargo") :smiley: :computer:

[Mas comandos](https://gist.github.com/dasdo/9ff71c5c0efa037441b6 "Todos los comandos")