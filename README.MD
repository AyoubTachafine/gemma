# practica_evaluable
git init: Inicializa un nuevo repositorio Git en el directorio actual.



echo "mi segunda linea de documento" >> documento.txt: Añade “mi segunda linea de documento” al final del archivo “documento.txt”.

git add: Añade los cambios en el directorio de trabajo al área de preparación (staging area) para el próximo commit. Debes especificar qué archivos quieres añadir después de este comando, por ejemplo, git add documento.txt.

git commit -m "mi texto": Crea un nuevo commit con los cambios que has añadido al área de preparación. “mi texto” es el mensaje del commit.

git commit -am "mi texto": Añade todos los archivos modificados al área de preparación y crea un nuevo commit con ellos. “mi texto” es el mensaje del commit.

git push origin main: Sube los cambios al repositorio remoto en la rama “main”.

git reset --hard HEAD^: Deshace el último commit y todos los cambios en el directorio de trabajo.

git revert HEAD: Crea un nuevo commit que deshace los cambios del último commit.

git remote add origin [enlace repositorio]: Añade un nuevo repositorio remoto llamado “origin” con la URL especificada.

cat documento.txt: Muestra el contenido del archivo “documento.txt”.

touch documento2.txt: Crea un nuevo archivo vacío llamado “documento2.txt”.

git merge: Fusiona los cambios de otra rama en la rama actual. Debes especificar qué rama quieres fusionar después de este comando, por ejemplo, git merge feature.

git fetch origin: Descarga los cambios del repositorio remoto “origin” pero no los fusiona en tu rama actual.

git checkout: Cambia a otra rama. Debes especificar a qué rama quieres cambiar después de este comando, por ejemplo, git checkout feature.

git checkout -b: Crea una nueva rama y cambia a ella. Debes especificar el nombre de la nueva rama después de este comando, por ejemplo, git checkout -b feature.

git log: Muestra el historial de commits.

git branch: Muestra las ramas locales.

git branch -d mirama: Elimina la rama local “mirama”.

git push origin --delete mirama: Elimina la rama “mirama” del repositorio remoto “origin”.

git branch -a: Muestra todas las ramas locales y remotas.

git tag V1: Crea una nueva etiqueta llamada “V1” en el commit actual.