Links: [[Git - MOC]]

# Comandos de Configuración
---

Lista todas las configuraciones de Git.
```bash
git config --list
```

Añade usuario a Git.
```bash
git config --global user.name "gariza90"
```

 Añade correo electronico a Git.
```bash
git config --global user.email "gariza90@gmail.com"
```

Aplica color a la sintaxis de Git.
```bash
git config --global color.ui true
```

 Cambia el editor de texto por defecto para Git, se requiere añadir la ruta del ejecutable del editor como un alias en el archivo .bash_profile.
```bash
git config --global core.editor <ruta del ejecutable> -n -w
```
```bash
git config --global push.default <tipo de push>
```
```bash
git config --global merge.conflictstyle <estilo>
```

Cambia el estilo de fin de linea entre windows (CRLF = true) y linux (LF = false).
```bash
git config --global core.autocrlf <true | false>
```

```bash
nano ~/.gitconfig	# Archivo de configuraciones de Git.
```

---

## Referencias