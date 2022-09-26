## Fundamentos de **GIT**:

- Es el estándar actual.
- Código distribuido colaborativo y versionado.
- Recuperación de archivos.
- Mayor control.
- Shorcuts y plugins implementados.
- Mejora la productividad.

### Intro:

Git es un software de control de versiones, descentralizado y distribuido, lo que hace que pueda ser utilizado por varios usuarios a la vez.

Git es el software que nos permite versionar nuestro código.

Permite trabajar de manera simultánea entre los compañeros de trabajo, cada uno con su copia y así van actualizando el directorio de orígen.

#### GIT-HUB:

Plataforma social que nos permite almacenar y compartir nuestro código con otras personas.

---

## Configuración inicial de **GIT**:

- git --version
- git config --global user.name "Jonathan MirCha"
- git config --global user.email jonmircha@gmail.com
- git config --global user.ui true
- git config --global init.defaultBranch main
- git config --list

### Visual Studio como editor nativo:

- git config --global core.editor "code --wait"
- git config --global -e

### Estandarizar los saltos de línea en Windows y Mac:

- Windows: git config --global core.autocrlf true
- Mac: git config --global core.autocrlf input

### Configuración en la terminal y navegador:

- Terminal: git config -h
- Navegador: git help config

---

## Iniciar un repositorio con **GIT**:

- mkdir carpeta
- cd carpeta
- touch README.md
- touch .gitignore
- git init
- code .

## Flujo básico de trabajo:

![Flujo de trabajo **GIT**](img/git-flow.png)

```md
# agregar los cambios de un archivo al staged

git add archivo/directorio

# agregar todos los cambios de todos los archivos al staged

git add .

# los cambios son comprometidos en el repositorio

# debes escribir el mensaje del cambio

# cuando se abra el archivo de configuración

# al terminar guarda y cierra el archivo

# para que los cambios tengan efecto

git commit

# es un shortcut del comando anterior

# escribes y confirmas el mensaje del cambio en un sólo paso

git commit -m "mensaje descriptivo del cambio"

# se agrega el origen remoto de tu repositorio de GitHub

git remote add origin https://github.com/usuario/repositorio.git

# la primera vez que vinculamos el repositorio remoto con el local

git push -u origin master

# para las subsecuentes actualizaciones, sino cambias de rama

git push

# para descargar los cambios del repositorio remoto al local

git pull
```
