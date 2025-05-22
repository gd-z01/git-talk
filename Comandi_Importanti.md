# Git Comandi importanti

## Git Init

```bash
git init
```

Serve per iniziare un progetto Git.

## Git Status

```bash
git status
```

Serve per vedere lo stato del progetto.

## Git Add

```bash
git add .
```

Serve per aggiungere tutti i file al repository.

```bash
git add <file>
```

Serve per aggiungere un singolo file al repository.

## Git Commit

```bash
git commit -m "<messaggio>"
```

Serve per creare un commit con il messaggio specificato.

## Git Log

```bash
git log
```

Serve per vedere i commit del repository.

## Git Checkout

```bash
git checkout <branch>
```

Serve per cambiare la branch attuale.

## Git Branch

```bash
git branch
```

Serve per vedere le branch del repository.

## Git Merge

```bash
git merge <branch>
```

Serve per unire due branch, "branch" con la branch attuale che l'head sta puntando

se errori in auto-merge, allora bisogna risolvere manualmente

## Git Push

```bash
git push origin <branch>
```

Serve per pushare una branch al repository remoto.

## Git Pull

```bash
git pull origin <branch>
```

Serve per pullare una branch dal repository remoto.

## Git Revert

```bash
git revert <commit>
```

Serve per revertare un commit, il commit che scrivi è il commit precedente al commit che vuoi revertare

## Git Reset

```bash
git reset --hard <commit>
```

Serve per revertare un commit, il commit che scrive il commit precedente al commit che vuoi revertare
