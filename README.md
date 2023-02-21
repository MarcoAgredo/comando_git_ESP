# comando_git_ESP
En este repositorio hago una lista para recordar los comandos de GIT que más utilizo. Guardo la lista en español que es mi lengua nativa.

# Para iniciar un repositorio local:
git init

# Se utiliza para agregar un nuevo repositorio remoto a un repositorio local existente de Git
git remote add origin <url del repo creado en GitHub>
  
# Hacer push de tus cambios al repositorio remoto
git push origin <nombre_de_la_rama>
  
__________________________________________________________________
__________________________________________________________________
  
#LA RUTA DEL COMMIT:

# 1. Se utiliza para agregar todos los archivos modificados o nuevos en tu directorio de trabajo al índice de Git.
git add .

# 2. Se utiliza para confirmar los cambios preparados en el índice de Git en un nuevo commit con un mensaje de confirmación especificado.
git commit -m "Descripción del commit"
  
# 3. Se utiliza para enviar los cambios confirmados en un repositorio local a un repositorio remoto.
git push

__________________________________________________________________
__________________________________________________________________

#
git fetch
  
# Se utiliza para descargar los cambios más recientes del repositorio remoto y fusionarlos automáticamente en la rama local actual. En esencia, git pull es una combinación de dos comandos de Git: git fetch y git merge.
git pull
  
# Si deseas hacer pull de una rama específica, puedes utilizar el comando git pull <remote> <branch>, donde <remote> es el nombre del repositorio remoto y <branch> es el nombre de la rama remota que deseas descargar y fusionar en tu rama local actual.
