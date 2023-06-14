## Revertir cambios del último commit y los deja en staged
```
git reset --soft HEAD^
git reset --soft #-commit
```

## Revertir cambios del último commit y no le da seguimiento en staged
```
git reset --mixed HEAD^
git reset --mixed #-commit
```

## Revertir cambios del último commit y sin dejar los cambios en staged
```
git reset --hard HEAD^
git reset --hard #-commit
```

## Remover cambio en un archivo
```
git reset name.extension
```

## Remover cambio en más archivos
```
git reset name.extension name2.extension
```

## Descarta los cambios del stage
```
git reset .
```