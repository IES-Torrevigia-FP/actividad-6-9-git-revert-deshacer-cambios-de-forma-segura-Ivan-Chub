1\)

git reset mueve la rama hacia atrás y puede reescribir historia, eliminando commits de la rama actual. Es peligroso si ya has hecho push.

git revert no borra commits, sino que crea un nuevo commit que invierte los cambios de uno anterior. El historial queda intacto: A‑B‑C‑D‑(revert de B).



2\)

git revent: deshacer solo el cambio “modo=debug”, sin tocar el resto de commits.

git reset: el commit ya está en una rama compartida.



3\)

Se llama “forward‑moving undo” porque, a diferencia de un "deshacer" tradicional que borra el último paso, git revert añade un nuevo paso que neutraliza el anterior.

