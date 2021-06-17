# Comandos Configuración Git

```bash
git config --list	# Lista todas las configuraciones de Git.
git config --global user.name "gariza90"	# Añade usuario a Git.
git config --global user.email "gariza90@gmail.com" # Añade correo electronico a Git.
git config --global color.ui true	# Aplica color a la sintaxis de Git. ***
git config --global core.editor <ruta del ejecutable> -n -w # Cambia el editor de texto por defecto para Git, se requiere añadir la ruta del ejecutable del editor como un alias en el archivo .bash_profile.
git config --global push.default <tipo de push>
git config --global merge.conflictstyle <estilo>
git config --global core.autocrlf <true | false>	# Cambia el estilo de fin de linea entre windows (CRLF = true) y linux (LF = false).
```

```bash
nano ~/.gitconfig	# Archivo de configuraciones de Git.
```
