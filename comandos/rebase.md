# Rebase interactivo

Permite:
- Reordenar commits.
- Corregir mensajes de los commits.
- Unir commits.
- Separar commits.

Opciones más comunes:
- `pick` (`p`): Mantiene el commit sin cambios.
- `reword` (`r`): Cambia únicamente el mensaje del commit.
- `edit` (`e`): Pausa el rebase para modificar el contenido y/o el mensaje del commit.
- `squash` (`s`): Une el commit con el anterior y permite editar el mensaje final.
- `fixup` (`f`): Une el commit con el anterior y descarta el mensaje del commit actual.
- `drop` (`d`): Elimina el commit.

## Rebase interactivo de los últimos 3 commits

```
git rebase -i HEAD~3
```

## Continuar un rebase pausado
```
git rebase --continue
```

## Cancelar un rebase
```
git rebase --abort
```

## Omitir un commit con problemas
```
git rebase --skip
```
