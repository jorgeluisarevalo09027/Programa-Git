# Comandos básicos de Git

## Git local

| Comando | Descripción |
|---|---|
| `git init` | Crea un repositorio nuevo en la carpeta actual |
| `git status` | Muestra el estado de los archivos |
| `git add .` | Pasa los cambios al área de preparación |
| `git commit -m "mensaje"` | Guarda los cambios en el historial |
| `git log --oneline` | Muestra el historial en una línea por commit |
| `git branch` | Lista las ramas |
| `git switch -c nombre` | Crea una rama y cambia a ella |
| `git merge nombre` | Integra una rama en la actual |

## Git remoto

| Comando | Descripción |
|---|---|
| `git remote add nombre url` | Vincula el repositorio local con un remoto |
| `git remote -v` | Muestra los remotos configurados |
| `git push -u nombre rama` | Envía la rama al remoto y la deja vinculada |
| `git pull` | Descarga e integra los cambios del remoto |
| `git clone url` | Descarga una copia completa de un repositorio remoto |