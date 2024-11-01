# Let's create a markdown file with the Vimium shortcodes

# Vimium Shortcodes

## Navegación Básica

- `j` : Desplazarse hacia abajo.
- `k` : Desplazarse hacia arriba.
- `h` : Desplazarse hacia la izquierda.
- `l` : Desplazarse hacia la derecha.
- `gg` : Ir al inicio de la página.
- `G` : Ir al final de la página.
- `e` : Desplazarse hacia adelante.
- `b` : Desplazarce hacia atras

## Navegación entre Enlaces

- `f` : Resaltar enlaces y seguir uno (en la misma pestaña).
- `F` : Resaltar enlaces y abrir en una nueva pestaña.

## Navegación entre Pestañas

- `J` : Ir a la pestaña anterior.
- `K` : Ir a la pestaña siguiente.
- `t` : Abrir una nueva pestaña.
- `x` : Cerrar la pestaña actual.
- `T` : Abrir una pestaña cerrada recientemente.

## Búsqueda

- `/` : Buscar en la página.
- `n` : Ir a la siguiente coincidencia de búsqueda.
- `N` : Ir a la coincidencia anterior.

## Desplazamiento Rápido

- `d` : Desplazarse hacia abajo en bloques grandes.
- `u` : Desplazarse hacia arriba en bloques grandes.
- `Ctrl + f` : Desplazarse rápidamente hacia abajo.
- `Ctrl + b` : Desplazarse rápidamente hacia arriba.

## Navegación por Historial

- `H` : Ir a la página anterior.
- `L` : Ir a la página siguiente.

## Marcadores en la Página

- `m` : Marcar posición en la página.
- `'` : Volver a la posición marcada.

## Apertura de Páginas

- `o` : Abrir una URL, marcador o historial.
- `O` : Abrir una URL, marcador o historial en una nueva pestaña.

## Herramientas Misceláneas

- `r` : Recargar la página.
- `gs` : Ver el origen de la página.
- `yy` : Copiar la URL actual.
- `p` : Abrir la URL copiada en la pestaña actual.
  """

# Writing the markdown content to a file

with open("/mnt/data/vimium_shortcodes.md", "w") as file:
file.write(vimium_shortcodes)

"/mnt/data/vimium_shortcodes.md"
