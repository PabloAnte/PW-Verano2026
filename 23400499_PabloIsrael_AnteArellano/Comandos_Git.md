# 🍁 Comandos utilizados en GitHub

Git es una herramienta fundamental para el día a día de muchos desarrolladores de software.
Sirve como controlador de versiones para proyectos, lo que facilita en gran medida el desarrollo.

## 💫 20 comandos:
- 1. git init: Crea un nuevo repositorio Git en el directorio actual. Ejemplo:Empiezas un proyecto nuevo desde cero. Ejecutas git init en la carpeta y conviertes ese directorio en un repositorio Git para empezar a rastrear cambios.

- 2. git clone: Descarga un repositorio remoto existente en tu máquina local. Ejemplo: Te unes a un equipo y necesitas el código del proyecto. Usas git clone https://github.com/usuario/proyecto.git para descargar una copia completa con todo su historial.

- 3. git status: Muestra el estado actual de los archivos (modificados, preparados, no rastreados). Ejemplo: Antes de hacer commit, quieres saber qué archivos cambiaste. git status te muestra cuáles están modificados, cuáles ya están en el área de preparación y cuáles Git no reconoce todavía.

- 4. git add: Prepara archivos para ser incluidos en el próximo commit. Ejemplo: Modificaste tres archivos pero solo quieres incluir uno en el próximo commit. Usas git add archivo.js (o git add . para todos) para prepararlos.

- 5. git commit: Guarda los cambios preparados como una instantánea con un mensaje descriptivo. Ejemplo: Terminaste una función nueva. Guardas ese punto del proyecto con git commit -m "Agrega validación de formulario de login".

- 6. git push: Sube los commits locales al repositorio remoto. Ejemplo: Ya hiciste varios commits locales y quieres que tu equipo los vea. git push origin main sube esos cambios al repositorio remoto.

- 7. git pull: Trae los cambios remotos y los fusiona en tu rama actual. Ejemplo: Un compañero subió cambios mientras trabajabas. Ejecutas git pull para traer esas actualizaciones y fusionarlas con tu rama actual antes de seguir trabajando.

- 8. git branch: Lista ramas o crea una nueva rama. Ejemplo: Quieres empezar una funcionalidad nueva sin tocar el código estable. git branch nueva-funcionalidad crea la rama (y git branch sin argumentos lista las que ya existen).

- 9. git checkout: Cambia entre ramas o restaura archivos. Ejemplo: Necesitas moverte a otra rama para revisar algo, o descartar cambios en un archivo. git checkout desarrollo te cambia de rama; git checkout README.md restaura ese archivo a su última versión confirmada.

- 10. git switch: Una forma más moderna y limpia de cambiar entre ramas. Ejemplo: Quieres cambiar de rama de forma más clara, sin el comportamiento ambiguo de checkout. git switch desarrollo hace exactamente eso, separando el cambio de ramas de la restauración de archivos.

- 11. git merge: Fusiona otra rama en la rama actual. Ejemplo: Terminaste tu rama de funcionalidad y quieres integrarla a main. Desde main, ejecutas git merge nueva-funcionalidad para traer esos cambios.

- 12. git log: Muestra el historial de commits de la rama actual. Ejemplo: Quieres revisar qué se ha hecho en el proyecto últimamente. git log --oneline muestra un historial compacto de commits con sus mensajes.

- 13. git reset: Mueve HEAD y descarta commits o cambios de forma opcional. Ejemplo: Hiciste un commit por error o quieres deshacer cambios en el staging. git reset HEAD~1 deshace el último commit (manteniendo los cambios en tus archivos), o git reset --hard HEAD~1 los descarta por completo.

- 14. git revert: Crea un nuevo commit que deshace de forma segura un commit anterior. Ejemplo: Un commit ya subido al remoto rompió algo, pero no quieres reescribir el historial. git revert a1b2c3d crea un nuevo commit que anula esos cambios de forma segura.

- 15. git checkout --: Descarta cambios locales en un archivo específico. Ejemplo: Editaste un archivo y te arrepentiste antes de hacer commit. git checkout -- archivo.css descarta esos cambios y regresa a la última versión guardada.

- 16. git stash: Guarda temporalmente cambios no confirmados. Ejemplo: Estás a mitad de una tarea pero necesitas cambiar de rama urgentemente para arreglar un bug. git stash guarda tus cambios sin confirmar para que puedas recuperarlos después con git stash pop.

- 17. git stash list: Muestra todas las tareas guardadas. Ejemplo: Has guardado varios stashes en distintos momentos y ya no recuerdas cuáles son. git stash list te muestra todos con su identificador para poder recuperarlos o eliminarlos.

- 18. git remote -v: Muestra los repositorios remotos configurados. Ejemplo: Quieres confirmar a qué URL apunta tu repositorio antes de hacer push. git remote -v muestra las direcciones de fetch y push configuradas (normalmente origin).

- 19. git fetch: Descarga cambios remotos sin fusionarlos. Ejemplo: Quieres ver si hay cambios nuevos en el remoto sin mezclarlos todavía con tu trabajo. git fetch los descarga, y luego puedes revisarlos con git log origin/main antes de decidir si fusionarlos.

- 20. git diff: Muestra las diferencias entre archivos, commits o etapas. Ejemplo: Quieres ver exactamente qué líneas cambiaste antes de hacer commit. git diff muestra las diferencias entre tu área de trabajo y el último commit; git diff --staged muestra lo que ya está preparado.
