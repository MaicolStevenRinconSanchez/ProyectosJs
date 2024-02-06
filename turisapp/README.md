# Taller Alias git

El comando `git log --graph` se utiliza para mostrar una representación gráfica del historial de commits en un repositorio Git. Cuando se utiliza esta opción, Git representa gráficamente las relaciones entre los commits, mostrando ramificaciones y fusiones de manera visual.

![Mostrar repositorio](C:\Users\user\Desktop\Mostrar repositorio.png)



git log --pretty=format:'%Cred%h%Creset' --abbrev-commit

El comando `git log --pretty=format:'%Cred%h%Creset' --abbrev-commit` se utiliza para mostrar una lista de commits en la terminal, donde el hash corto de cada commit está resaltado en color rojo. Aquí hay una descripción de cada parte del comando

![capture2](C:\Users\user\Desktop\capture2.png)

El comando `git log --pretty=format:'%Cred%h%Creset %C(yellow)%d%Creset' --abbrev-commit` sirve para mostrar una lista de commits en la terminal, donde cada commit se presenta con su hash corto resaltado en rojo y las referencias (ramas o tags) en las que está involucrado resaltadas en amarillo. Aquí hay una descripción de cada parte del comando:

![image-20240206042957525](C:\Users\user\AppData\Roaming\Typora\typora-user-images\image-20240206042957525.png)

El comando `git log --pretty=format:'%Cred%h%Creset %C(yellow)%d%Creset %s' --abbrev-commit` sirve para mostrar una lista de commits en la terminal, proporcionando información específica en un formato personalizado. Aquí está una descripción de cada parte del comando:

![capture5](C:\Users\user\Desktop\capture5.png)

El comando `git log --pretty=format:'%Cred%h%Creset %C(yellow)%d%Creset %s %Cgreen(%cr)%Creset' --abbrev-commit` sirve para mostrar una lista de commits en la terminal, proporcionando información específica en un formato personalizado. Aquí está una descripción de cada parte del comando:

![capture6](C:\Users\user\Desktop\capture6.png)

El comando `git log --pretty=format:'%Cred%h%Creset %C(yellow)%d%Creset %s %Cgreen(%cr)%Creset' --abbrev-commit` se utiliza para mostrar una lista detallada de commits en la terminal, con varios elementos formateados de manera personalizada. Aquí hay una descripción de cada parte del comando:

![Captura7](C:\Users\user\Desktop\Captura7.png)

El comando `git log --pretty=format:'%Cred%h%Creset %C(yellow)%d%Creset %s %Cgreen(%cr)%Creset' --abbrev-commit` sirve para visualizar el historial de commits de un repositorio Git en la terminal, con un formato personalizado que incluye:

![Captura8](C:\Users\user\Desktop\Captura8.png)