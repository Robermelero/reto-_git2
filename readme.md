1. Crea un repositorio de GitHub en el que almacenar tu proyecto.
2. Clonar el repositorio en vuestro equipo con git clone git + enlace a repositorio creado.
3. Dentro de la carpeta del repositorio ( en visual )crear un proyecto node.
4. Trabajar con tu proyecto y hacer lo que necesites.
5. subir proyecto revisado al modo "stage" usando git add . y comprobar estado con git status. 
6. Para confirmar los cambios, subir el proyecto a modo comentado con git commid -n"comentario".
7. Volver comprobar estado con git status.
8. Subir de repositorio local a repositorio remoto el proyecto con git push.
9. Al incluir el comando *.png en el fichero .gitignore, se han quedado en gris.
He subido todos los archivos del proyecto con add . commit y push, se han quedado todos guardado en el reppositorio remoto sin generar ningun problema, a su vez la carpeta con fotos y resto de archivos .png no aparecen.
10. Al crear las ramas y hacer los cambios en la rama 1, al intentar guardarlo en el repositorio remoto nos da un error/aviso de que hay que crear las ramas en el repositorio remoto primero para poder guardar los cambios creados en dicha rama. En la propia consola sale el comando a ejecutar para crearla. Despues de esto se puede subir con push y fusionar con merge al proyecto principal ya que no hay conflictos.
11. Al subir desde la rama dos la modificacion de la suma, ha surgido un conflicto que he tenido que solucionar desde github y a su vez he tenido que confirmar los dos merge, de las dos ramas, ambas desde la pagina web.
