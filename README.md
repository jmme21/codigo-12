# Primer dia con Git y Github 

Lista de comandos de git

* Para poder ver la version de Git ejecutamos en nuestra terminal:

```bash
git --version
git -v
```

* Para configurar el correo y nombre (solo la primera vez en mi maquina)

```bash
git config --global user.email "jmme21@gmail.com"
git config --global user.name "jmme21"
```

* Para ver la configuracion de git
```bash
git config --list
```

* Para inicializar nuestro repositorio en git :
```bash
git init

```
* Para ver el estado de nuestro cambio en git :
```bash
git status
```
* Para preparar nuestros archivos para la zona de stage(prepararlos para commit) git :
```bash
git add .
git add nombredelarchivo.extension
```

* Crear el registro de los cambios realizados:
```bash
git commit -m "Creando mi primer commit"

```
* Para ver una linea de tiempo de los commits que hemos realizado:
```bash
git log

```

* Para poder ver el detalle de un commit especifico:
```bash
git show iddelcommit

```