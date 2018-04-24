## Instrucciones para github

### Actualizar repositorio

Al iniciar trabajo, controlar que el repositorio local esté actualizado con el repositorio de Github.com, esto se hace actualizando el local con el comando

`git pull origin master`

En caso que se hayan realizado cambios en el repositorio local, solicitará que sean adheridos antes de realizar pull. Para adherir estos cambios es necesario:

1. Agregar los cambios para subir:
    
    `git add *`

2. Hacer commit con mensaje sobre los cambios:

    `git commit -m 'Mensaje relativo a los cambios'`

## Subir actualización de repositorio local a Github

Para subir, es necesario el comando seguir los pasos de `add` - `commit` - `push`.

     git add *
     git commit -m 'mensaje relativo a los cambios'
     git push origin master


