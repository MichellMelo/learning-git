# Learning git

## Comandos

#

### Inicializar repositório localmente

```
git init
```

### Trackear o repositório

```
git add .
```

## Semântica dos commits

#

- fix -> quando tu sobe algo pra consertar algum bug
- feat -> quando tu sobe algo novo
- chore -> melhoria
- update -> atualização

## Alterar branch

#

### Se for uma card de implementação de algo novo faça:

```
git checkout -b feature/LEARNINGGIT-2-nome-da-branch
```

### Se for uma card de melhoria:

```
git checkout -b chore/LEARNINGGIT-2-nome-da-branch
```

### Se for uma card de atualização:

```
git checkout -b update/LEARNINGGIT-2-nome-da-branch
```

### Se for uma card pra consertar bug:

```
git checkout -b fix/LEARNINGGIT-2-remove-all-things-from-app-jsx-and-add-im-working-h1
```

## Commitar o Repositório e salvar no repositório local

#

### Subir uma implementação nova (feat)

```
git commit -m "feat(<nomeProjeto> - <xxxx(1234)>): change lorem ipsum."

git commit -m "feat(IJUDA-29): add navbar."
```

### Links úteis

- https://se-education.org/guides/conventions/git.html
- https://cbea.ms/git-commit/
- https://trello.com/
