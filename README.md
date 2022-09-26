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
