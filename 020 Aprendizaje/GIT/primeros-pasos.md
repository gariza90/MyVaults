# Comandos frecuentes Git

## Obtener ayuda

```bash
git help	# Ayuda de git, lista todos los comandos posibles.
git help <comando>
git <comando> --help
man git <comando>	# Ayuda de un comando especifico de Git.
```

## Iniciar nuevo repositorio

```bash
git init	# (Ubicado en el directorio) Crea un repositorio vacío en el directorio de trabajo (manera local).
git init <nombre-proyecto>	# Crea un directorio con el nombre del proyecto e inicializa el repositorio en este directorio.
```

## Verificar estado del repositorio

```bash
git status	# Revisa y muestra que archivos han cambiado desde el ultimo envío "commit".
```

## Añade archivos al repositorio

```bash
git add <archivo>	# Añade el archivo al área de deposito "Staging Area".
git add <lista de archivos> ...	# Añade los archivos por sus nombres.
git add --all	# Añade todos los archivos nuevos o modificados.
git add .
git add *.<ext>	# Añade todos los archivos con la extensión especificada en el directorio actual.
git add <directorio>/*.<ext>	# Añade todos los archivos con la extensión especificada en el directorio especificado.
git add <directorio>/	# Añade todos los archivos en el directorio especificado.
git add "*.<ext>"	# Añade todos los archivos con la extensión especificada (entre comillas) del proyecto entero.
```

## Mostrar diferencias entre archivos

```bash
git diff	# Muestra las diferencias del archivo modificado con el depositado "staged".
git diff <hash1> <hash2>	# Muestra las diferencias encontradas entre las dos versiones de archivos referenciados por el identificador hash hexadecimal asignado por Git en cada commit, <hash1> es el commit mas antiguo y <hash2> el commit mas reciente.
git diff --staged	# Muestra las diferencias del archivo depositado "staged" (posterior a git add) con el del ultimo envío "commit".
git diff --cached
```

## Mostar el registro de actividad

```bash
git log	# Lista todos los commit realizados hasta el momento.
git log -p <num>	# Lista el número de commits indicados en el parámetro <num> y con el parámetro -p muestra las diferencias entre ellos.
git log -p --word-diff	# Lista los commits pero obtiene las diferencias por palabras en lugar de las diferencias línea por línea.
git log --stat	# Lista todos los commits con algunas estadísticas para cada uno de ellos, como por ejemplo, los archivos modificados, el numero de inserciones y eliminaciones en cada archivo.
git log --pretty=<tipo_formato>
	# --pretty cambia el formato de salida del log a otro diferente al default especificando el <tipo_formato> requerido
  	# oneline - Muestra en la salida, el hash y el texto descriptivo de cada commit
  	# short - Muestra la salida el hash, autor y el texto descriptivo de cada commit. No muestra la fecha del commit
  	# full
  	# fuller
  	# format:"cadena_de_formatos"
```

## Realizar confirmaciones

```bash
git commit -m "<mensaje descriptivo>"	# Envía el (los) archivo(s) modificados desde el área de deposito al repositorio local.
git commit -a -m "<mensaje descriptivo>"	# Añade y envía los archivos modificados en un solo comando. stage & commit. -a = git add.
git commit --amend -m "<mensaje descriptivo>"	# Cambia el último commit añadiendo a este, un archivo modificado.
```
