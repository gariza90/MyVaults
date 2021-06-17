## Comandos sincronización remota Git

## Verificar remotos

```bash
git remote add <nombre> <ruta remoto>	# Añade un nombre (usualmente "origin") y una ruta al repositorio remoto.
git remote -v	# lista los orígenes de los repositorios remotos existentes.
git remote rm <nombre>	# Remueve repositorios remotos de git
```

## Publicar repositorio local en remoto

```bash
git push -u <nombre> <branch>	# Sube los cambios del repositorio local (branch = master) al repositorio remoto (nombre = origin) ***
```

## Traer repositorio remoto a local

```bash
git pull
```

## Clonar repositorio remoto

```bash
git clone <ruta repositorio remoto>	 # Realiza una clonación completa de un repositorio remoto como un directorio de trabajo local.
git clone <ruta repositorio remoto> <directorio>	# Realiza una clonación completa de un repositorio remoto como un directorio de trabajo local con el nombre especificado.
```
