# Comandos reversión cambios Git

```bash
git reset HEAD <archivos>	# Unstage, revierte el deposito del archivo, esto se debe hacer antes de hacer el commit.
git reset --soft HEAD^	# Deshace un commit hecho con anterioridad y retorna los cambios en los archivos al stage "unstage". El simbolo ^ es importante y significa un estado anterior en el HEAD.
git reset --hard HEAD^	# Deshace el último commit y todos los cambios en los archivos.
git reset --hard HEAD^^	# Deshace los dos últimos commits y todos los cambios en los archivos.
```

```bash
git checkout -- <archivo>	# Descarta todos los cambios desde el último commit.
```
