# Comandos de la consola de windows

### importante:
* La consola de windows no discrimina entre mayusculas y minusculas, es decir, podemos escribir cualquier comando en mayusculas y minusculas sin ningun problema.

    Por ejemplo: cls es igual a ClS

* En los comandos no se debe colar \'<>\', solo se puso para aclarar que eso se debe reemplazar por algo.  
**Ejemplo**:

    Si aparece este codigo ' **MKDIR \<carpeta1>\\\<carpeta2>\\\<carpeta3>** ' en realidad el comando debe quedar \' **MKDIR cursos\\consola\\windws** \' , en donde \'cursos, consola y windows\' se deben reemplazar por los nombres de los diretorios que queremos eliminar.

***

### Relacionado con la consola
Colocar un titulo en la ventana de la consola
```
title
```


De esta forma, aparecerá una lista con todos los comandos y la información sobre lo que hace cada uno de ellos
```
help
```

Consultar la información sobre un comando en particular
```
help <comando>
```

Otra forma de consultar la información de un solo comando
```
<comando> /?
```

Imprimir algun texto o valor en la consola
```
echo <mensaje>
```

Limpiar la consola
```
cls
```

Para la acción o el comando que se ejecuta, esto le pedirá una confirmación
```
pause
```

Para la acción o el comando que se ejecuta pero si que solicite una confirmación
```
pause>nul
```

Cambiar el color y el background de la consola
```
color <numero y/o letra>
```

Crear un comentario
```
REM <comentario>
```

Otra forma de crear un comentario
```
:: <comentario>
```

Cerrar la consola
```
exit
```

### Relacionado con los directorios

Listar todos los ficheros que haya en el directorio donde se encuentra
```
dir
```

Otra forma de listar los ficheros que haya en el directorio donde se encuentra, pero de esta forma muestra las direciones o rutas
```
dir /AD
```

Mostrar a ruta actual en la que se encuentra
```
CD
```

Entrar a una carpeta o directorio
```
CD <carpeta>
```

Salir de un directorio, retroceder
```
CD ../
```

Crear un directorio
```
MD <nombre>
```

Otra forma de crear un directorio
```
MKDIR <nombre>
```

Crear varios directorios con un solo comando
```
MKDIR <carpeta1>\<carpeta2>\<carpeta3>...
```
Eliminar un directorio
```
RD <nombre>
```

Otra forma de eliminar un directorio
```
RMDIR <nombre>
```

Eliminar todo un directorio con sus subcarpetas
```
RD /S /Q <nombre>
```

### Otros

Fecha actual, con este comando se puede cambiar la fecha
```
date
```

Fecha actual sin poder cambiarla, solo ver la fecha
```
echo Fecha: %date%
```

Hora actual, con este comando se puede cambiar la hora
```
time
```

Hora actual sin poder cambiarla, solo ver la hora
```
echo Hora: %time%
```

Imprimir la hora y la fecha actual
```
echo Fecha: %date% Hora: %time%
```

***
Creado por [Jhon Camargo](http://jhoncamargo.000webhostapp.com "Página web de Jhon Camargo") :smiley: :computer:

[Mas comandos](https://www.ionos.es/digitalguide/servidores/know-how/comandos-cmd/#:~:text=Comandos%20CMD%20de%20Windows%3A%20listado%20general,-Existen%20casi%20300 "Todos los comandos")