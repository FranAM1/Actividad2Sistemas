# EJERCICIO DE CLASE 2. Ejercicios básicos de MS-DOS (en github)

Documentación y resolución de cada uno de los ejercicios básicos de MS-DOS.

# Índice
1. [Ejercicio 1](#ejercicio-1)
    + [Ejercicio 1.1](#ejercicio-11)
    + [Ejercicio 1.2](#ejercicio-12)
    + [Ejercicio 1.3](#ejercicio-13)
    + [Ejercicio 1.4](#ejercicio-14)
    + [Ejercicio 1.5](#ejercicio-15)
    + [Ejercicio 1.6](#ejercicio-16)
    + [Ejercicio 1.7](#ejercicio-17)
    + [Ejercicio 1.8](#ejercicio-18)
    + [Ejercicio 1.9](#ejercicio-19)
    + [Ejercicio 1.10](#ejercicio-110)
    + [Ejercicio 1.11](#ejercicio-111)
    + [Ejercicio 1.12](#ejercicio-112)
2. [Ejercicio 2](#ejercicio-2)
    + [Ejercicio 2.1](#ejercicio-21)
    + [Ejercicio 2.2](#ejercicio-22)
    + [Ejercicio 2.3](#ejercicio-23)
    + [Ejercicio 2.4](#ejercicio-24)
    + [Ejercicio 2.5](#ejercicio-25)
    + [Ejercicio 2.6](#ejercicio-26)
    + [Ejercicio 2.7](#ejercicio-27)
    + [Ejercicio 2.8](#ejercicio-28)
    + [Ejercicio 2.9](#ejercicio-29)
    + [Ejercicio 2.10](#ejercicio-210)
3. [Ejercicio 3](#ejercicio-3)
    + [Ejercicio 3.1](#ejercicio-31)
    + [Ejercicio 3.2](#ejercicio-32)
    + [Ejercicio 3.3](#ejercicio-33)
    + [Ejercicio 3.4](#ejercicio-34)
    + [Ejercicio 3.5](#ejercicio-35)
    + [Ejercicio 3.6](#ejercicio-36)
    + [Ejercicio 3.7](#ejercicio-37)
    + [Ejercicio 3.8](#ejercicio-38)
    + [Ejercicio 3.9](#ejercicio-39)
    + [Ejercicio 3.10](#ejercicio-310)
 4. [Ejercicio 4](#ejercicio-4)
    + [Ejercicio 4.1](#ejercicio-41)
    + [Ejercicio 4.2](#ejercicio-42)
    + [Ejercicio 4.3](#ejercicio-43)
    + [Ejercicio 4.4](#ejercicio-44)
    + [Ejercicio 4.5](#ejercicio-45)
    + [Ejercicio 4.6](#ejercicio-46)
    + [Ejercicio 4.7](#ejercicio-47)
    + [Ejercicio 4.8](#ejercicio-48)
    + [Ejercicio 4.9](#ejercicio-49)
    + [Ejercicio 4.10](#ejercicio-410)

# Ejercicio 1

### Ejercicio 1.1 
Para la creación de la estructuras de carpeta he ido utilizando el comando ```md``` con sus respectivos nombres y moviendome por las diferentes rutas con ```cd```.

Para mostrar la estructura de directorios como se ve en la imagen, he utilizado el comando ```tree``` dentro de la carpeta que abarca todas las carpetas del ejercicio.

![image](https://user-images.githubusercontent.com/91600940/159031354-e191a389-4eee-4502-9798-70b9a16ee0a4.png)

### Ejercicio 1.2
Estando en la carpeta raíz del ejercicio, he utilizado los siguientes comandos para moverme a la carpeta **TABLAS**.
~~~~
cd APLI/EXCEL/TABLAS
~~~~

### Ejercicio 1.3
En mi caso, la ruta de la carpeta raíz de mi ejercicio es la siguiente.
```
cd C:\Users\Fran\Documents\Actividad2SI
```

### Ejercicio 1.4
Dentro de la carpeta **PROG** para mostrar el contenido de la misma, he utilizado el comando ```dir``` para mostrar el contenido de la misma.
![image](https://user-images.githubusercontent.com/91600940/159034490-1fdbc787-20b2-4cd6-ac92-3ea14c5faaa3.png)

### Ejercicio 1.5
Para borrar la carpeta **PASCAL** he utilizado ```rmdir``` pero tambien sirve el comando ```rd```. Como se puede observaren la imagen, la carpeta **PASCAL** ya no existe dentro del directorio **PROG**. <br>
![image](https://user-images.githubusercontent.com/91600940/159037257-058edf5e-806c-4988-b075-6f95af873f5f.png)

### Ejercicio 1.6
Dentro de la carpeta **VARIOS**, he creado la carpeta **PRACT** utilizando el siguiente comando.
~~~~
md C:\Users\Fran\Documents\Actividad2SI\APLI\WORD\PRACT
~~~~


### Ejercicio 1.7
Dentro de la carpeta creada en el anterior ejercicio, he utilizado el siguiente comando para mostrar el contenido de la carpeta **EXCEL**.
~~~
dir C:\Users\Fran\Documents\Actividad2SI\APLI\EXCEL
~~~

![image](https://user-images.githubusercontent.com/91600940/159040172-5d7486f7-941b-465e-a020-cc18da5f34ae.png)

### Ejercicio 1.8
En mi caso, como la carpeta raíz es una que he creado solo para este ejercicio solo contiene las carpetas que he ido creando. El comando utilizado ha sido el siguiente.
~~~
dir C:\Users\Fran\Documents\Actividad2SI
~~~
![image](https://user-images.githubusercontent.com/91600940/159041012-d79a19d8-4da5-4478-ab9a-efd53691e8a9.png)

### Ejercicio 1.9
Para crear la subcarpeta llamada **AGENDA** dentro de **VARIOS** he utilizado el siguiente comando.
~~~
md C:\Users\Fran\Documents\Actividad2SI\VARIOS\AGENDA
~~~

### Ejercicio 1.10
Como en este caso queremos borrar la carpeta **EXCEL** y no está vacía, no nos basta con poner simplemente los comandos ```rmdir``` o ```rd```, por lo que tendremos que añadir el parametro ```/S``` para indicar que también eliminaremos todas las subcarpetas que haya dentro de la carpeta.
En mi caso he utilizado el siguiente comando y como se puede observar en la imagen, ya no existe la carpeta EXCEL, ni sus subcarpetas.
~~~
rmdir /S  C:\Users\Fran\Documents\Actividad2SI\APLI\EXCEL
~~~
![image](https://user-images.githubusercontent.com/91600940/159042985-6161c3df-0938-40ad-8ee0-002b7dd9d01d.png)

### Ejercicio 1.11
Para este ejercicio he utilizado el siguiente orden de comandos.
~~~
cd C:\Users\Fran\Documents\Actividad2SI
md NUEVO
~~~
![image](https://user-images.githubusercontent.com/91600940/159043363-4e1c919d-d40b-4c0a-8536-ffd5d49a2326.png)

### Ejercicio 1.12
Para este ejercicio he utilizado el siguiente orden de comandos.
~~~
cd C:\Users\Fran\Documents\Actividad2SI\APLI\WORD\PRACT
dir C:\Users\Fran\Documents\Actividad2SI\APLI\WORD
~~~
![image](https://user-images.githubusercontent.com/91600940/159178305-84f89cae-2a0a-403e-830d-5649d8beb249.png)

# Ejercicio 2

## Ejercicio 2.1
Situandome en la carpeta de **TEXTOS**, he utilizado el comando ```COPY CON EJER.TXT``` para crear el archivo de texto y una vez tuve el texto copiado, utilice el atajo de teclas ```Ctrl + Z``` para salir del editor de texto y crear el archivo.
![image](https://user-images.githubusercontent.com/91600940/159249286-0c266143-7639-4a78-81ab-dd06cc990710.png)

## Ejercicio 2.2
He utilizado el siguiente comando para copiar el txt a la carpeta **AGENDA**
```
copy EJER.TXT C:\Users\Fran\Documents\Actividad2SI\VARIOS\AGENDA
```
## Ejercicio 2.3
He utilizado la siguiente lista de comandos para situarme en la carpeta y borrar el archivo.
```
cd C:\Users\Fran\Documents\Actividad2SI\APLI\WORD\TEXTOS
del EJER.TXT
```

## Ejercicio 2.4
Para añadir la linea de texto he utilizado el siguiente comando.
```
echo "Cada archivo tiene un nombre y una extensión que los distingue del resto de archivos" >> EJER.TXT
```
![image](https://user-images.githubusercontent.com/91600940/159254255-8c7e42af-d936-4698-a0ef-d60470fe00bb.png)

## Ejercicio 2.5
He utilizado el mismo comando que en el [ejercicio 2.2](#ejercicio-21) pero con la ruta ```C:\Users\Fran\Documents\Actividad2SI\PROG\BASIC```.

## Ejercicio 2.6
He utilizado la siguiente linea de comandos.
```
cd C:\Users\Fran\Documents\Actividad2SI\VARIOS\AGENDA
move EJER.TXT FICHERO.TXT
```

## Ejercicio 2.7
He utilizado el siguiente comando
```
move FICHERO.TXT C:\Users\Fran\Documents\Actividad2SI\PROG\BASIC
```

## Ejercicio 2.8
Para este ejercicio, utilizando los siguientes comandos, he copiado el contenido de **EJER.TXT** para luego copiar dentro de **NUEVO.TXT** con la primera linea eliminada, para terminar con la eliminación de **EJER.TXT**
```
type EJER.TXT
copy con NUEVO.TXT
del EJER.TXT
```
![image](https://user-images.githubusercontent.com/91600940/159549442-7deb013e-9351-4369-b51d-3a53d1574cb5.png)

## Ejercicio 2.9
He utilizado el siguiente comando
```
copy NUEVO.TXT C:\Users\Fran\Documents\Actividad2SI\APLI\WORD\NOTAS
```

## Ejercicio 2.10
A traves de la utilizacion del comando ```dir``` en las diferentes rutas podemos ver que en la carpeta en **NOTAS** hay 1 y en **BASIC** hay 2 archivos
![image](https://user-images.githubusercontent.com/91600940/159551027-b74bab6c-1715-464f-a3bf-037b620f8443.png)


# Ejercicio 3

## Ejercicio 3.1
Estando situado en la carpeta raíz, he utilizado los siguientes comandos.
```
cd APLI
rd ACCES
md ASTRO
```

## Ejercicio 3.2
Este ejercicio lo he realizado de la misma manera que el [ejercicio 1.1](#ejercicio-11).<br>
![image](https://user-images.githubusercontent.com/91600940/159178930-1e47ea93-bf2d-48b9-b8a2-4195d2cf4165.png)

## Ejercicio 3.3
He utilizado los siguientes comandos.
```
cd C:\Users\Fran\Documents\Actividad2SI\APLI\ASTRO\CIENCIA
dir C:\Users\Fran\Documents\Actividad2SI\APLI\ASTRO\HISTORIA && tree C:\Users\Fran\Documents\Actividad2SI\APLI\ASTRO\HISTORIA
```
![image](https://user-images.githubusercontent.com/91600940/159552369-11617da1-58d4-4381-81fb-fa2a6bcfbd52.png)

## Ejercicio 3.4
He utilizado el siguiente comando, escribiendo su respectivo texto.
```
copy con C:\Users\Fran\Documents\Actividad2SI\APLI\ASTRO\HISTORIA\DATOS1\TYCHO.TXT
```

## Ejercicio 3.5
He utilizado el siguiente comando, escribiendo su respectivo texto.
```
copy con C:\Users\Fran\Documents\Actividad2SI\APLI\ASTRO\HISTORIA\DATOS2\KEPLER.TXT
```
## Ejercicio 3.6

He utilizado el siguiente comando.
```
copy C:\Users\Fran\Documents\Actividad2SI\APLI\ASTRO\HISTORIA\DATOS1\TYCHO.TXT C:\Users\Fran\Documents\Actividad2SI\APLI\ASTRO\CIENCIA && copy C:\Users\Fran\Documents\Actividad2SI\APLI\ASTRO\HISTORIA\DATOS2\KEPLER.TXT C:\Users\Fran\Documents\Actividad2SI\APLI\ASTRO\CIENCIA
```

## Ejercicio 3.7
He utilizado el siguietne comando.
```
move C:\Users\Fran\Documents\Actividad2SI\APLI\ASTRO\HISTORIA\DATOS1\TYCHO.TXT C:\Users\Fran\Documents\Actividad2SI\APLI\ASTRO\HISTORIA\DATOS2 && move C:\Users\Fran\Documents\Actividad2SI\APLI\ASTRO\HISTORIA\DATOS2\KEPLER.TXT C:\Users\Fran\Documents\Actividad2SI\APLI\ASTRO\HISTORIA\DATOS1
```

## Ejercicio 3.8
Estando en la carpeta **DATOS2**, he utilizado el siguiente comando.
```
copy TYCHO.TXT+C:\Users\Fran\Documents\Actividad2SI\APLI\ASTRO\HISTORIA\DATOS1\KEPLER.TXT C:\Users\Fran\Documents\Actividad2SI\APLI\ASTRO\HISTORIA\TOTAL.TXT
```

## Ejercicio 3.9
Situandome en la carpeta **CIENCIA**, he utilizado el siguiente comando.
```
echo "Kepler aplicó sus teorías a los satélites de Júpiter, descubiertos por Galileo a través de un pequeño telescopio, cuya introducción en la observación astronómica constituye uno de los hitos de la astronomía." >> KEPLER.TXT
```

## Ejercicio 3.10
Estando situado en la carpeta **CIENCIA**, he utilizado el siguiente comando.
```
copy KEPLER.TXT GALILEO.TXT && del KEPLER.TXT
```

# Ejercicio 4

## Ejercicio 4.1
Como en los anteriores ejercicios, no lo he creado en la carpeta raiz del disco, si no en mi carpeta **Actividad2SI** con el siguiente comando.
```
md C:\Users\Fran\Documents\Actividad2SI\TECINFO
```

## Ejercicio 4.2
He seguido los mismo pasos que en el [ejercicio 2.1](#ejercicio-21) pero con su respectivo nombre y texto.

## Ejercicio 4.3
He seguido los mismo pasos que en el [ejercicio 2.1](#ejercicio-21) pero con su respectivo nombre y texto.

## Ejercicio 4.4
Estando en la carpeta **TECINFO**, he utilizado el siguiente comando.
```
move HARD.TXT C:\Users\Fran\Documents\Actividad2SI\APLI && move SOFT.TXT C:\Users\Fran\Documents\Actividad2SI\APLI
```

## Ejercicio 4.5
Estando en la carpeta **APLI**, he utilizado el siguiente comando.
```
copy HARD.TXT+SOFT.TXT C:\Users\Fran\Documents\Actividad2SI\VARIOS\AGENDA\ORDER.TXT
```

## Ejercicio 4.6
He utilizado el siguiente comando.
```
rd C:\Users\Fran\Documents\Actividad2SI\TECINFO
```

## Ejercicio 4.7
Estando en la carpeta **APLI**, he utilizado el siguiente comando.
```
copy HARD.TXT C:\Users\Fran\Documents\Actividad2SI\VARIOS && copy SOFT.TXT C:\Users\Fran\Documents\Actividad2SI\VARIOS
```

## Ejercicio 4.8
Estando en la carpeta **AGENDA**, he utilizado el siguiente comando
```
ren ORDER.TXT ORDER.TYP
```

## Ejercicio 4.9
**NO SE HA CREADO NINGUN ARCHIVO .DOC POR LO QUE NO SE PUEDE HACER ESTE EJERCICIO**

## Ejercicio 4.10
**NO SE HA CREADO NINGUN ARCHIVO .DOC POR LO QUE NO SE PUEDE HACER ESTE EJERCICIO**
