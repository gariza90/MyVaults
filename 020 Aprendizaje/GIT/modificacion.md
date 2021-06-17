# Comandos modificación Git


## Remover archivos -rm-

```bash
git rm <archivo>	# Remueve los archivos del staging area y del directorio de trabajo.
```

```bash
git rm --cached <archivo>	# Remueve el archivo del staging area pero se conserva en el directorio de trabajo. Git no lo rastrea dentro del proyecto nuevamente.
```

```bash
git rm \*~	# El caracter de escape \ es necesario porque Git tiene su propia expansión de archivos además de la expansión del shell. Este comando remueve todos los archivos que finalicen en ~
```

## Mover archivos -mv-

```bash
git mv <desde archivo> <a archivo>	# Renombra un archivo en Git.
```
