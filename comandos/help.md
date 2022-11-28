# Ayuda

## Versión
```
git --version
```

## Ayuda
```
git --help
```

## Ayuda 2
```
git --help commit
```

## Configurar nombre
```
git config --global user.name "Lorem Ipsum"
```

## Configurar correo
```
git config --global user.email "loremipsum@gmail.com"
```

## Mostrar listado de configuraciones
```
git config --global -e
```

## Salir
```
esc + :w(write) q(quit) !(salir)
:wq!
```

## Crear un alías
```
git config --global alias.s "status --short"
```

## Inicializar el repositorio
```
git init
```

## Clonar repositorio
```
git clone URL
```

## Clonar repositorio en una carpeta
```
git clone URL folder-name
```

## Ver el origin del repositorio
```
git remote -v
```

## Configurar solo el metodo fast forward del git pull
```
git config --global pull.ff only
```

## Configurar solo el metodo rebase del git pull
```
git config --global pull.rebase true
```

## Actualizar repositorio y fusiona la rama con los cambios
```
git pull
```

## Actualizar repositorio y los añade al stage
```
git fetch
```

## Renombrar archivo
```
git mv example.md demo.md
```

## Borrar archivo
```
git rm example.md
```


