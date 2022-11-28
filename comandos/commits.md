# Captura :camera:

## Mostrar listado de commits 
```
git log
```

## Ahorrarse pasos al agregar al stage
```
git commit -am "commit initial"
```
##### Nota: `Solo sirve si le estamos dando seguimiento al archivo`

## Guardar cambios 
```
git commit -m "commit initial x2"
```

## Reconstruye el proyecto como estaba en el último commit
```
git commit checkout -- .
```
##### Nota: `Tiene que estar los archivos en stage antes`

## Reconstruye el archivo en el último commit
```
git commit checkout -- name.extension
```

## Editar nombre del commit 
```
git commit --amend -m "rename commit"
```

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

## Recuperar commits por defectos del proyecto
```
git reflog
```



