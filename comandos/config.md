## Configurar nombre
```
git config --global user.name "Lorem Ipsum"
```

## Configurar correo
```
git config --global user.email "loremipsum@gmail.com"
```

## Crear un alias
```
git config --global alias.tree "log --graph --decorate --all --oneline"
```

## Configurar solo el metodo fast forward del git pull
```
git config --global pull.ff only
```

## Configurar solo el metodo rebase del git pull
```
git config --global pull.rebase true
```

## Mostrar listado de configuraciones
```
git config --global -e
```

## Rama por default
```
git config --global init.defaultBranch name-feature
```