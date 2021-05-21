
# __*Comandos para linux en la terminal*__
- [__*Comandos en Linux*__](#__*¿Ques%20es%20un%20comando?*__)
- [__*Comandos Extra basicos*__](#__*ComandosExtrabasicos*__)
- [__*Manipulacion de Directorios y Archivos*__](#__*Manipulacion%20de%20Directorios%20y%20Archivos*__)
- [__*Explorando el contenido de nuestros archivos*__](#__*Explorando%20el%20contenido%20de%20nuestros%20archivos*__)
# __*alias y help*__
- [_Comando **help** y **alias**_](#_Comando%20**help**%20y%20**alias**_)


# [__*¿Ques es un comando?*__](#__*Comandos%20para%20linux%20en%20la%20terminal*__)
>
    un programa ejecutable

> 
    un comando de utilidad de la shell 

>
    una funcion de la shell



# [__*Comandos Extra basicos*__](#__*Comandos%20para%20linux%20en%20la%20terminal*__)

# 1. Navegar entre directorios  ***cd***
> ## `cd `

    nos ayuda a navegar entre directorios
> ## `cd dir `

    nos lleva a el directorio dir
>## `cd ..`

    nos lleva al directorio anterior
# 2. Ver informacion de un directorio con ***ls***

>## `ls `

   nos muestra todos los directorios y archivos de nuestro directorio actuial 



# [__*Manipulacion de Directorios y Archivos*__](#__*Comandos%20para%20linux%20en%20la%20terminal*__)

# 1. Ver archivos con  comando ***tree***
opcion mas factible :



>## `tree -L 2`

    tree muestra las cosas como un arbol  pero agregando (-L 2 )de level(niveles)  de dos nos muestra en dos niveles de arboles nuestros directorios y archivos

# 2. Crear directorios con ***mkdir***
> ## `mkdir nombreDeDirectorio`
## crear varios directorios
> ## `mkdir dir1 dir2 dir3`

    el comando de arriba nos creara 3 directorios
    

# 3. crear archivos con ***touch***
>## `touch nombreDeArchivo`

## crear varios coomo el cmd mkdir

> ## `touch file1 file2 file3`

    en la linea de arriba se crean 3 archivos de texto 
    "PD : tambien podemos ponerles extension "

# 4. Copiar Archivos con ***cp***
> ## `cp file1 fileCopy`

    file1 es el archivo que copiaremos y fileCopy ES EL nombre del archivo copiad 
# 5. Mover archivos o directorios con  ***mv***
> ## `mv file ..`

    este comando mueve el archivo al directorio anterior

> ## `mv dir1 dir2` 

    este mueve el primer parametro dir1 a el segundo parametro dir2

# 6. Renombrar archivos o directorio con mv
> ## `mv file fileNewName`

    el primer parametro es el nombre del archivo o directorio y el segundo es el nuevo nombre

# 7. borrar archivos y directorio con ***rm***

## - Remover Archivos
> ## `rm -i nameFile`

    nameFile es el nombre del directorio o archivo que desamos remover junto con su modificador *-i* de intereactividad pasa 
>##  rm: remove regular empty file 'nameFileOrDir'?

    gracias al modificador de interactividad nos pregunta si lo removemos debemos poner  la letra **y** para decir si o **n** para decir no . Esto nos ayuda muchisimo por si cometemos un error
## -Remover Directorios
> ## `rm -ri dir`

    Es la mejor manera usando la opcion interactiva donde nos pregunta sobre los archivos y directorios que esten dentro de **dir**
    para eliminarlos o no

> ## `rm -rf dir`

    este comando nos eliminara por completo el dir 
    PD: es muy peligroso puedes borrar todo 


# [__*Explorando el contenido de nuestros archivos*__](#__*Comandos%20para%20linux%20en%20la%20terminal*__)

>## `head nameFile`

    nos muestra las primeras lineas del archivo 

>## `head nameFile -n 15`

    con el modificador -n nos muestra las priemras 15 lineas de codigo y el numero puede variar

>## `tail nameFile`

    nos muestra las ultimas lineas de codigo 

>## `tail nameFile -n 15`

    como en el head le decimos cuantas lineas queremos ver


>## `less nameFile`

    nos muestras todo el archivo.

    PD: para salir usa la letra q 

> ## `explorer.exe `.

    este comando abre la interfaz grafica de el directorio donde te encuentras

# [_Comando **help** y **alias**_](#__*Comandos%20para%20linux%20en%20la%20terminal*__)

## help
> ## ` help nameComand`

    o

> ## ` help nameComand`

    este comando te pidie como parametro el nombre de otro comando , con esto podemos saber todas las variaciones o todos los modificadores que le podemos poner.
## alias
 >## `alias nameNewAliasComando = "comando solo o con modificadores"`

> ## `alias l="ls -lh"`

    en este caso a el comando que esta dentro de las comillas(Pd: el comando al que queremos ponerle alias debe estar dentro de las comillas) le asignamos el alias "l"

> entocnes si usamos el comando 

>## `l`
    
    nos mostrara las funciones de 
  
> ## `ls -lh`

## man

>## `man cd`

    ayuda para comando cd

## info

>  ## `info cd`

    informacion para comando cd 

# [_*Usando Wilcards*_](#__*Comandos%20para%20linux%20en%20la%20terminal*__)

    Las WildCards nos sirven para poder filtrar las busquedas con el comando ls. 
       


  

    






    


    










