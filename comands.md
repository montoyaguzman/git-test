# inicializar un repositorio

git init

# agregar uno o mas archivos al staging area

git add .

# hacer un commit

git commit -m "mensaje"

# ver el estado actual de nuestro repositorio

git status

# ver el historial de commits

git log

# ver si nuestro repo local hace referencia a un repo remoto

git remote -v

# subir cambios

git push URL/ALIAS RAMA

# bajar una rama nueva

git fetch && git checkout RAMA

# subir cambios a una rama

git pull URL/ALIAS RAMA

# ver las ramas que tenemos

git branch

# crear una nueva rama y cambiarse a esa nueva rama

git checkout -B nuevaRama

# cambiarse a una rama

git checkout branch

# cambiar a un commit

git checkout hash

# para hacer merge en la rama actual (destino) desde la rama origen

git merge ramaOrigen

# no es un comando sino un concepto para integrar cambios desde el remoto

pull request

# mandar cambios sttaging a un temporal para usarlos despues

git stash

# recuperar cambios desde el temporal

git stash pop

# BUENAS PRACTICAS

1. Siempre guardar.
2. Hacer commits antes de cambiar de rama.
3. Procurar tener limpio el staging area y working directory.
4. Cambiarse a la rama de la que haran pull, antes del pull.
5. Uso de ramas master, develop, fix/, refactor, feat/
6. Usar commit nombrados.
7. Agregar revisores a las pull request.

master -> produccion
develop -> integracion de cambios que se estan probando o validando

MGJ
montoya
isaac

fix/nueva-reaccion
feature/login
refactor/styles

q1/montoya

git commit -m "FEAT : ASSAS"
FEAT
DOCS
STYLES
REFACTOR
