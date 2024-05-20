_**ANOTACIONES**_

> [!IMPORTANT]
> La librería solamente está disponible para TIA PORTAL de SIEMENS


> [!TIP]
>**MODO PARA IMPORTAR LA LIBRERÍA:**
>- **1**  Dentro de tu proyecto en TIA PORTAL, accede a la sección LIBRERIA
>- **2**  Acceder a "Abrir librería" y abrir la carpeta donde hayas descargado este archivo
>- **3**  Una vez que tengas Timer Libray en tu biblioteca, abrir la pestaña "Plantillas maestras", ahí se encontrarán los archivos de esta librería
>- **4**  Arrastra la sección Timer Library que se encuentra dentro de "Plantillas maestras" hacía "Bloques de programa" y se creará una carpeta que contendrá las funciones y el bloque de datos de la librería


> [!NOTE]
>**MODO DE FUNCIONAMIENTO:**
>- Esta librería tiene unas funciones que se encargan de ejecutar un temporizador asociado a una matriz multidimensional.
>- El objetivo de la función es declarar en programa un solo temporizador para 20 motores.
>- Dentro de la función "HmiButtonFunction" al inicio, se encuentra un bloque de código comentado. Ese código hay que introducirlo en el bloque principal "Main".
>- El código es un sencillo contador que se encarga de recorrer el array, (si tu programa es en KOP, lo que tienes que hacer es implementar una función contador en el bloque main y asociarla a la variable "TimerLibraryVar".ArrayPos")
que es la variable encargada de recorrer el array
>- En el bloque de datos, están todas las variables necesarias para el funcionamiento de esta librería, puedes cambiar o renombrar las variables como creas conveniente.



