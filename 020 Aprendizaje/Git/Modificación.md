Links: [[Git - MOC]]

# Comandos de Modificación
---

## Remover archivos -rm-

Remueve los archivos del staging area y del directorio de trabajo.
```bash
git rm <archivo>
```

Remueve el archivo del staging area pero se conserva en el directorio de trabajo. Git no lo rastrea dentro del proyecto nuevamente.
```bash
git rm --cached <archivo>
```

El caracter de escape \ es necesario porque Git tiene su propia expansión de archivos además de la expansión del shell. Este comando remueve todos los archivos que finalicen en ~
```bash
git rm \*~
```

## Mover archivos -mv-

Renombra un archivo en Git.
```bash
git mv <desde archivo> <a archivo>
```

---

## Referencias