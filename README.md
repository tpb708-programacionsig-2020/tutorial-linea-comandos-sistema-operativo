# Tutorial sobre la interfaz de línea de comandos del sistema operativo

## Recursos
- Referencia para la línea de comandos: [SS64 Command line reference](https://ss64.com/)
- Algunos comandos básicos para Windows: [Command Prompt: 11 basic commands you should know (cd, dir, mkdir, etc.) | Digital Citizen](https://www.digitalcitizen.life/command-prompt-how-use-basic-commands)

## Windows
El sistema de archivos de Windows tiene una estructura jerárquica organizada en directorios (o carpetas). Un directorio puede contener archivos y subdirectorios (i.e. directorios "hijos"). Cada sistema de archivos tiene un directorio raíz, el cual contiene todos los archivos y subdirectorios.

El comando [dir](https://ss64.com/nt/dir.html) (*directory*) despliega la lista de archivos y subdirectorios de un directorio.

```shell
# Listado sencillo
dir

# Listado paginado
dir /p
```

El comando [cd](https://ss64.com/nt/cd.html) (*change directory*) se utiliza para cambiar de directorio.

```shell
# Cambio al directorio raíz
cd \

# Cambio a un subdirectorio
cd <nombre-subdirectorio>

# Cambio al directorio padre
cd ..
```

El comando [md](https://ss64.com/nt/md.html) (*make directory*) se utiliza para crear un subdirectorio.

```shell
# Creación de un subdirectorio
mkdir <nuevo-subdirectorio>
```

