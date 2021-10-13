# PREVIO

- Controladores de versiones no automaticos.
- Controladores de versiones centralizados SVN.
- Controladores de versiones distribuidos.

# GIT

Es un controlador de versiones

# Reposotorios remotos

Github, Gitlab y Bitbucket

# Repositorio local

- Working directory: Nuestro disco duro o sistema de archivos.
- Staging area: Lo que esta listo para agregarse al historial (Area de indexado de git).
- Repo local : Es lo que se encuentra en el historial del commit.

¿Como conectar repo local y repo remoto?

- Mediante el comando git remote add origin.
- Los repos remotos son el respaldo de nuestro local.
- El historial es gestionado por GIT.

# FLUJO MERGE

1. Cambiarse a la rama de destino.
   git checkout main
2. Ejecutar el comando merge en la rama destino
   git merge develop

# FLUJO PULL REQUEST

1. Hacer un commit (add, commit y push)
2. Crear la pull request en github (rama base y rama destino) y agregar revisores.
3. Los revisores aceptan la PR (Pull request) y se hace el merge.
4. Obtener los cambios mediante git pull origin develop
