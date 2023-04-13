# Neovim configuration
El presente repositorio contiene la configuración básica que utilizo para el uso de [Neovim](https://neovim.io/), en el archivo de configuración se encuentran los siguientes parámetros:
- title: muestra el nombre del archivo abierto en la ventana de la terminal.
- relativenumber: muestra los el número de líneas relativas hacia arriba o hacia abajo.
- nowrap: no divide la línea si esta es muy larga.
- cursosline: resalta la línea actual.
- colorcolumn\=120: muestra la columna límite a 120 caracteres.

Los siguientes parámetros ayudan a que la indentación sea de 2 espacios.
- tabstop\=2
- shiftwidth\=2
- softtabstop\=2
- shiftround
- shiftround: inserta espacios en lugar de tabuladores.

- hidden: permite cambiar de buffers sin tener que guardarlos.
- ignorecase: ignora las mayúsculas al hacer una búsqueda.
- smartcase: no ignora las mayúsculas si la palabra a buscar contiene mayúsculas.
- spelllang=en,es: ayuda a corregir las palabras usando diccionarios en Inglés y Español.
- termguicolors: activa true colors en la terminal.
- background=dark: Fondo del tema oscuro, también puede ser cambiado por _light_.
