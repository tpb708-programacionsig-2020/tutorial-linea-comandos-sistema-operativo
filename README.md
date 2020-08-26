# Tutorial sobre la interfaz de línea de comandos del sistema operativo

## Recursos
- Referencia para la línea de comandos: [SS64 Command line reference](https://ss64.com/)
- Algunos comandos básicos para Windows: [Command Prompt: 11 basic commands you should know (cd, dir, mkdir, etc.) | Digital Citizen](https://www.digitalcitizen.life/command-prompt-how-use-basic-commands)

## Windows
El sistema de archivos de Windows tiene una estructura jerárquica organizada en **directorios** (o carpetas). Un directorio puede contener **archivos** y **subdirectorios** (i.e. directorios "hijos"). Cada sistema de archivos tiene un **directorio raíz** (ej. ```C:\```), el cual contiene todos los archivos y subdirectorios.

Cada archivo y directorio se identifica mediante una ruta. Hay dos tipos de rutas:
- **Rutas absolutas**: se especifican a partir del directorio raíz. Por ejemplo: ```C:\Users\mfvargas```
- **Rutas relativas**: se especificar a partir del directorio actual. Por ejemplo: ```Downloads\datos```; en este caso, si el directorio actual es ```C:\Users\mfvargas```, la ruta completa es ```C:\Users\mfvargas\Downloads\datos```

### Comandos comúnmente utilizados
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

# Cambio de directorio
cd <ruta-directorio>

# Cambio al directorio padre
cd ..
```

El comando [md](https://ss64.com/nt/md.html) (*make directory*) se utiliza para crear un directorio.

```shell
# Creación de un directorio
mkdir <nuevo-directorio>
```

