# *👇Comandos Básicos de GIT👇*
***
## Índice

1. Creación de repostorio.
2. Clonar un repositorio.
3. Ver el estado del repositorio.
4. Añadir archivos al área de preparación.
5. Hacer commit de los cambios.
6. Ver el historial de commits.
7. Ver remotos.
8. Subir cambios al repositorio remoto.
9. Actualizar el repositorio local con cambios remotos.
10. Crear una nueva rama.
11. Cambiar de rama.
12. Fusionar ramas.
13. Eliminar una rama.
14. Configurar identidad.
***

### 1. CREACIÓN DE UN REPOSITORIO 

`git init`

### 2. CLONAR UN REPOSITORIO

`git clone [nombreRepositorio]`

### 3. VER EL ESTADO DEL REPOSITORIO

`git status`

### 4. AÑADIR ARCHIVOS AL ÁREA DE PREPARACIÓN

`git add nombreArchivo`

### 5. HACER COMMIT DE LOS CAMBIOS

`git commit -m "mensaje"`

### 6. VER EL HISTORIAL DE COMMITS

`git log`
`git log --graph --all`

### 7. VER REMOTOS

`git remote -v`

### 8. SUBIR CAMBIOS AL REPOSITORIO REMOTO

`git push origin [nombreRama]`

### 9. ACTUALIZAR EL REPOSITORIO LOCAL CON CAMBIOS REMOTOS

`git pull origin [nombreRama]`

### 10. CREAR UNA NUEVA RAMA

`git branch [nombreNuevaRama]`

### 11. CAMBIAR DE RAMA

`git checkout [nombreRama]`

### 12. FUSIONAR DOS RAMAS

`git merge [nombreRama]`

### 13. BORRAR UNA RAMA

`git branch -d [nombreRama]`

### 14. CONFIGURAR IDENTIDAD

- ***Nombre de usuario:***

`git config --global user.name "Tu nombre"`

- ***Correo:***

`git config --global user.email "Tu correo`
