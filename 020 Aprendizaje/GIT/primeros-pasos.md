# Comandos frecuentes Git

## Obtener ayuda

Ayuda de git, lista todos los comandos posibles.
```bash
git help
```

Ayuda de un comando especifico de Git.
```bash
git help <comando>
git <comando> --help
man git <comando>
```

## Iniciar nuevo repositorio

(Ubicado en el directorio) Crea un repositorio vacío en el directorio de trabajo (manera local).
```bash
git init
```

Crea un directorio con el nombre del proyecto e inicializa el repositorio en este directorio.
```bash
git init <nombre-proyecto>
```

## Verificar estado del repositorio

Revisa y muestra que archivos han cambiado desde el ultimo envío "commit".
```bash
git status
```

## Añade archivos al repositorio

Añade el archivo al área de deposito "Staging Area".
```bash
git add <archivo>
```

Añade los archivos por sus nombres.
```bash
git add <lista de archivos> ...
```

Añade todos los archivos nuevos o modificados.
```bash
git add --all
git add .
```

Añade todos los archivos con la extensión especificada en el directorio actual.
```bash
git add *.<ext>
```

Añade todos los archivos con la extensión especificada en el directorio especificado.
```bash
git add <directorio>/*.<ext>
```

Añade todos los archivos en el directorio especificado.
```bash
git add <directorio>/
```

Añade todos los archivos con la extensión especificada (entre comillas) del proyecto entero.
```bash
git add "*.<ext>"
```

## Mostrar diferencias entre archivos

Muestra las diferencias del archivo modificado con el depositado "staged".
```bash
git diff
```

Muestra las diferencias encontradas entre las dos versiones de archivos referenciados por el identificador hash hexadecimal asignado por Git en cada commit, \<hash1\> es el commit mas antiguo y \<hash2\> el commit mas reciente.
```bash
git diff <hash1> <hash2>
```

Muestra las diferencias del archivo depositado "staged" (posterior a git add) con el del ultimo envío "commit".
```bash
git diff --staged
git diff --cached
```

## Mostar el registro de actividad

Lista todos los commit realizados hasta el momento.
```bash
git log
```

Lista el número de commits indicados en el parámetro \<num\> y con el parámetro -p muestra las diferencias entre ellos.
```bash
git log -p <num>
```

Lista los commits pero obtiene las diferencias por palabras en lugar de las diferencias línea por línea.
```bash
git log -p --word-diff
```

Lista todos los commits con algunas estadísticas para cada uno de ellos, como por ejemplo, los archivos modificados, el numero de inserciones y eliminaciones en cada archivo.
```bash
git log --stat
```

--pretty cambia el formato de salida del log a otro diferente al default especificando el <tipo_formato> requerido
- oneline - Muestra en la salida, el hash y el texto descriptivo de cada commit
- short - Muestra la salida el hash, autor y el texto descriptivo de cada commit. No muestra la fecha del commit
- full
- fuller
- format:"cadena_de_formatos"
```bash
git log --pretty=<tipo_formato>
```

## Realizar confirmaciones

Envía el (los) archivo(s) modificados desde el área de deposito al repositorio local.
```bash
git commit -m "<mensaje descriptivo>"
```

Añade y envía los archivos modificados en un solo comando. stage & commit. -a = git add.
```bash
git commit -a -m "<mensaje descriptivo>"
```

Cambia el último commit añadiendo a este, un archivo modificado.
```bash
git commit --amend -m "<mensaje descriptivo>"
```
