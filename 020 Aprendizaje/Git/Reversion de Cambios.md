Links: [[Git - MOC]]

# Comandos para Reversión de Cambios
---

Unstage, revierte el deposito del archivo, esto se debe hacer antes de hacer el commit.
```bash
git reset HEAD <archivos>
```

Deshace un commit hecho con anterioridad y retorna los cambios en los archivos al stage "unstage". El simbolo ^ es importante y significa un estado anterior en el HEAD.
```bash
git reset --soft HEAD^
```

Deshace el último commit y todos los cambios en los archivos.
```bash
git reset --hard HEAD^
```

Deshace los dos últimos commits y todos los cambios en los archivos.
```bash
git reset --hard HEAD^^
```

Descarta todos los cambios desde el último commit.
```bash
git checkout -- <archivo>
```

---

## Referencias
