# Modificar línea de tiempo

## Rebase normal establece el punto inicial de una rama
```
git rebase name-feature
```

## Rebase Squash unificar commits
```
git rebase -i HEAD~4
```

## Rebase Reword modificar mensajes de los commits
```
git rebase -i HEAD~4
```

## Rebase Edit modificar el commit
```
git rebase -i HEAD~4
```

## Rebase Edit finaliza
```
git rebase --continue
```

