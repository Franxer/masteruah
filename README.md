# masteruah

# Solución ejercicios Git, GitHub y Markdown



 ## Repositorio masteruah



| 1. Crear un repositorio en vuestro GitHub llamado **masteruah**. |
| ------------------------------------------------------------ |
| ![image-20220309193231366](C:\Users\Francisco Javier\AppData\Roaming\Typora\typora-user-images\image-20220309193231366.png) |


| 1. Clonar vuestro repositorio en local.                      |
| ------------------------------------------------------------ |
| Usamos el comando git clone de esta manera : ![image-20220309193323142](C:\Users\Francisco Javier\AppData\Roaming\Typora\typora-user-images\image-20220309193323142.png) |


| ## README                                          |
| -------------------------------------------------- |
| git clone https://github.com/Franxer/masteruah.git |


Notas: en este documento tendreís que ir poniendo los **comandos** que habéis tenido que utilizar durante todos los ejercicios y las **explicaciones y capturas de pantalla** que consideréis **necesarias**.

## Commit inicial


| 1. Añadir al README.md los comandos utilizados hasta ahora y hacer un coomit inicial con el mensaje **commit inicial**. |
| ------------------------------------------------------------ |
| git commit -m "commit inicial"                               |

| ## Push inicial 1. Subir los cambios al repositorio remoto.|
| --------------- |
| git push        |



## Añadir fichero 1.txt 

| 1. Añadir fichero **1.txt** al repositorio local. |
| ------------------------------------------------- |
| touch fichero1.txt                                |

## Crear el tag v0.1 


| 1. Crear un tag **v0.1**.                            |
| ---------------------------------------------------- |
| git tag 1.0 9719c5515663ec8fc9f3ada0186fc6fd65e7af5d |


## Subir el tag v0.1


| 1. Subir los cambios al repositorio remoto. |
| ------------------------------------------- |
| git commit -m "v2" |
|git push                 |

## Crear una rama v0.2



| 1. Crear una rama **v0.2**. |
| --------------------------- |
| git checkout -b "v0.2"      |


| 1. Posiciona tu carpeta de trabajo en esta rama. |
| ------------------------------------------------ |
| git checkout v0.2                                |

 ## Añadir fichero 2.txt


| 1. Añadir un fichero **2.txt** en la rama **v0.2**. |
| --------------------------------------------------- |
| git add fichero2.txt                                |


 ## Crear rama remota v0.2


| 1. Subir los cambios al reposiorio remoto. |
| ------------------------------------------ |
| git commit -m "v1"                         |


 ## Merge directo 

| 1. Posicionarse en la rama **master**. |
| -------------------------------------- |
| git checkout main                      |

| 1. Hacer un merge de la rama **v0.2** en la rama **master**. |
| ------------------------------------------------------------ |
| git merge v0.2                                               |


## Merge con conflicto



| 1. En la rama **master** poner **Hola** en el fichero **1.txt** y hacer commit. |
| ------------------------------------------------------------ |
| git commit -m "v3"                                           |


| 1. Posicionarse en la rama **v0.2** y poner **Adios** en el fichero "1.txt" y hacer commit. |
| ------------------------------------------------------------ |
| git checkout v0.2 git commit -m "v2"                         |


| 1. Posicionarse de nuevo en la rama **master** y hacer un merge con la rama **v0.2** |
| ------------------------------------------------------------ |
| git checkout main git merge v0.2                             |


## Listado de ramas


| 1. Listar las ramas con merge y las ramas sin merge. |
| ---------------------------------------------------- |
| git branch                                           |


## Arreglar conflicto


| 1. Arreglar el conflicto anterior y hacer un commit. |
| ---------------------------------------------------- |
| git commit -m "v5"                                   |

## Borrar rama


| 1. Crear un tag **v0.2** |
| ------------------------ |
| git tag 0.2              |


| 1. Borrar la rama **v0.2** |
| -------------------------- |
| git branch -d v0.2         |


## Listado de cambios

| 1. Listar los distintos commits con sus ramas y sus tags. |
| --------------------------------------------------------- |
| git log                                                   |

 ## Cuenta de GitHub


1. Poner una foto en vuestro perfil de GitHub.


1. Poner el doble factor de autentificación en vuestra cuenta de GitHub.

1. Añadir (si no lo habéis hecho ya) la clave pública que se corresponde a tu ordenador.                                                             |

## Uso social de GitHub


1. Preguntar los nombres de usuario de GitHub de tus compañeros de trabajo en grupo, búscalos, y sigueles.

1. Añadir una estrella a los repositorios del resto de tus compañeros.


## Crear una tabla 


1. Crear una tabla de este estilo en el fichero **README.md** con la información de varios de tus compañeros de clase:


|         NOMBRE                                                                                                 GITHUB        |
| ------------------------------------------------------------ |
| \| Ignacio \| [enlace a github 1](https://github.com/IgnacioJavier) \| |
| ------------------------------------------------------------ |
|                                                              |
| \| Alfonso \| [enlace a github 1](https://github.com/AlfonsoAlcaraz) \| |
| ------------------------------------------------------------ |
|                                                              |
| \| Carlos Piña \| [enlace a github 3](https://github.com/carlospdlt) \| |
| ------------------------------------------------------------ |
|                                                              |

## Colaboradores


| 1. Poner a [github.com/i12vecaj](http://github.com/i12vecaj) como colaborador del repositorio **masteruah**  |
| ------------------------------------------------------------ |
|                                                              |

## Crear una organización 

| 1. Crear una organización llamada **masteruah-tunombredeusuariodegithub** |
| ------------------------------------------------------------ |
|                                                              |

## Crear equipos 

| 1. Crear 2 equipos en la organización **masteruah-tunombredeusuariodegithub**, |
| ------------------------------------------------------------ |
| ![image-20220311163822626](C:\Users\Francisco Javier\AppData\Roaming\Typora\typora-user-images\image-20220311163822626.png) |

| uno llamado **administradores** con más permisos y otro **colaboradores** con menos permisos. |
| ------------------------------------------------------------ |
|                                                              |



| 1. Meter a [github.com/i12vecaj](http://github.com/i12vecaj) y a 2 de vuestros |
| ------------------------------------------------------------ |
|                                                              |

| compañeros de clase en el equipo **administradores**. |
| ----------------------------------------------------- |
|                                                       |


| 1. Meter a [github.com/i12vecaj](http://github.com/i12vecaj) y a otros 2 de vuestros |
| ------------------------------------------------------------ |
|                                                              |

| compañeros de clase en el equipo **colaboradores**. |
| --------------------------------------------------- |
|                                                     |

| ## Crear un index.html |
| ---------------------- |
|                        |


| 1. Crear un index.html que se pueda ver como página web en la organización. |
| ------------------------------------------------------------ |
|                                                              |


## Crear Pull-requests

| 1. Hacer 2 forks de 2 repositorios **masteruah-tunombredeusuariodegithub.github.io** |
| ------------------------------------------------------------ |
|                                                              |

| de 2 organizaciones de las que no seais ni administradiores ni colaboradores. |
| ------------------------------------------------------------ |
|                                                              |

| 1. Crearos una rama en cada fork. |
| --------------------------------- |
|                                   |


| 1. En cada rama modificar el fichero **index.html** añadiendo vuestro nombre. |
| ------------------------------------------------------------ |
|                                                              |

| 1. Con cada rama hacer un pull-request. |
| --------------------------------------- |
|                                         |

 ## Gestionar Pull-requests 


\1. Aceptar los pull-request que lleguen a los repositorios de tu organización.

