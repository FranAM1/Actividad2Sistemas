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
2. [Ejercicio 2]()
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
5. [Ejercicio 3]()

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
Estando situado en la carpeta raíz, he utilizado los siguientes comandos.
```
cd APLI
rd ACCES
md ASTRO
```

## Ejercicio 2.2
Este ejercicio lo he realizado de la misma manera que el [ejercicio 1.1](#ejercicio-11).<br>
![image](https://user-images.githubusercontent.com/91600940/159178930-1e47ea93-bf2d-48b9-b8a2-4195d2cf4165.png)








