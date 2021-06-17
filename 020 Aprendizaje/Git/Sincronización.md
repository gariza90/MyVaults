Links: [[Git - MOC]]

# Comandos para Sincronización Remota
---

## Verificar remotos

Añade un nombre (usualmente "origin") y una ruta al repositorio remoto.
```bash
git remote add <nombre> <ruta remoto>
```

Lista los orígenes de los repositorios remotos existentes.
```bash
git remote -v
```

Remueve repositorios remotos de git.
```bash
git remote rm <nombre>
```

## Publicar repositorio local en remoto

Sube los cambios del repositorio local (branch = master) al repositorio remoto (nombre = origin)
```bash
git push -u <nombre> <branch>
```

## Traer repositorio remoto a local

```bash
git pull
```

## Clonar repositorio remoto

Realiza una clonación completa de un repositorio remoto como un directorio de trabajo local.
```bash
git clone <ruta repositorio remoto>
```

Realiza una clonación completa de un repositorio remoto como un directorio de trabajo local con el nombre especificado.
```bash
git clone <ruta repositorio remoto> <directorio>
```

---

## Referencias
