## ¿CÓMO REGRESAR A UN COMMIT ANTERIOR CON GIT?
> ## Estos comando eliminaran todos los commit despues del commit a cual quieres regresar.
>
>


    Se nos da que por error hacemos un commit indebido o necesitamos regresar al proyecto a una versión anterior por sea cual sea el motivo.

    Lo que debemos hacer es lo siguiente:
>

    ubicar el ID del commit al cual queremos regresar
> `git reset --hard <commit-id>`

    indicar que este commit será el nuevo
> `git reset --soft HEAD@{1} `

    subir los cambios
> `git commit -m "Se revirtieron los cambios" `
