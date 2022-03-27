# Cómo crear un repositorio git
Git es una herramienta para administrar las versiones del código fuente de un programa. Para convertir una carpeta en un repositorio git puedes utilizar el comando

`git init`

Recomiendo crear el primer cambio para inicializar el repositorio. Por ejemplo crear las carpetas donde se organizará el código y el archivo `main.c`. 

```bash
mkdir src/ # Crear el directorio src/.
touch src/main.c # Crear un archivo vacío en la ruta especificada.

git add . # Marca el directorio actual para ser añadido al siguiente commit.
git commit -m "Inicio repo" # Crea el commit con los cambios realizados.
```

Por lo general se utilizarán varios comandos de bash como `mkdir, touch, ls, etc...`. Es posible hallar información acerca de los parámetros y el uso general de cada uno de estos programas buscando en Google `man "comando"`. Para los principales es posible añadir la palabra "español", sin embargo para otros es posible que solo se encuentre en inglés.

[Ejemplo: man ls (español)](http://www.linuxcertif.com/man/1/ls/es/)

# Creando el repositorio en github.

Selecciona el signo "+" que se halla a la derecha arriba (una vez iniciada la sesión)

<img src="pic1.png" alt=""/>

[https://github.com/new](https://github.com/new)


# Commits
Los commits son la forma que tenemos de registrar los cambios que realizamos en nuestro repositorio. El commit inicial que realizamos se ve así:

