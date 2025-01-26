# Atajos útiles en Vim (VSCode)

## Atajos de Vim en VSCode

### Movimientos básicos

- `h`, `j`, `k`, `l` → Moverse a la izquierda, abajo, arriba, derecha.
- `w` → Avanzar al inicio de la siguiente palabra.
- `b` → Retroceder al inicio de la palabra anterior.
- `e` → Ir al final de la palabra actual.
- `gg` → Ir al inicio del archivo.
- `G` → Ir al final del archivo.
- `0` → Ir al inicio de la línea.
- `$` → Ir al final de la línea.
- `Ctrl + u` → Subir media pantalla.
- `Ctrl + d` → Bajar media pantalla.
- `Ctrl + b` → Subir una pantalla completa.
- `Ctrl + f` → Bajar una pantalla completa.

### Edición de texto

- `i` → Entrar en modo de inserción antes del cursor.
- `I` → Insertar al inicio de la línea.
- `a` → Entrar en modo de inserción después del cursor.
- `A` → Insertar al final de la línea.
- `o` → Insertar nueva línea debajo y entrar en modo de inserción.
- `O` → Insertar nueva línea arriba.
- `d` + `w` → Eliminar la palabra desde el cursor.
- `d` + `d` → Eliminar la línea completa.
- `y` + `y` → Copiar la línea completa.
- `p` → Pegar después del cursor.
- `P` → Pegar antes del cursor.
- `u` → Deshacer.
- `Ctrl + r` → Rehacer.
- `v` → Selección visual (caracteres).
- `V` → Selección visual (líneas).
- `Ctrl + v` → Selección visual en bloque.
- `c` + `w` → Cambiar la palabra desde el cursor.
- `c` + `c` → Cambiar la línea completa.
- `r` + `[caracter]` → Reemplazar el caracter bajo el cursor.
- `s` → Eliminar el caracter bajo el cursor e insertar.
- `x` → Eliminar el caracter bajo el cursor.
- `X` → Eliminar el caracter antes del cursor.
- `J` → Unir la línea siguiente a la actual.

### Búsqueda y reemplazo

- `/texto` → Buscar `texto` en el archivo.
- `n` → Ir a la siguiente coincidencia.
- `N` → Ir a la coincidencia anterior.
- `:%s/viejo/nuevo/g` → Reemplazar todas las ocurrencias de "viejo" por "nuevo".
- `:%s/viejo/nuevo/c` → Obliga a Confirmar cada una de las sustituciones.
- `:%s/viejo/nuevo/i` No distingue entre mayúsculas y minúsculas→ .
- `:%s/viejo/nuevo/g` → distingue entre mayúsculas y minúsculas. -`*` → Buscar la palabra bajo el cursor hacia adelante.
- `#` → Buscar la palabra bajo el cursor hacia atrás.

### Macros

- `q` + `[tecla]` → Comenzar a grabar macro.
- `@` + `[tecla]` → Ejecutar la macro grabada.
- `@@` → Repetir la última macro ejecutada.

### Guardado y salida

- `:w` → Guardar archivo.
- `:q` → Cerrar archivo.
- `:wq` → Guardar y cerrar archivo.
- `:q!` → Salir sin guardar.
- `:x` → Guardar y cerrar archivo (igual que `:wq`).
- `ZZ` → Guardar y cerrar archivo.
- `ZQ` → Salir sin guardar.

### Navegar

- `:sp` → Dividir la pantalla Horizontalmente
- `:vsp` → Dividir la pantalla Verticalmente
- `ctrl` + w + h → Ir a la ventana de la izquierda
- `ctrl` + w + j → Ir a la ventana de la abajo
- `ctrl` + w + k → Ir a la ventana de la arriba
- `ctrl` + w + l → Ir a la ventana de la abajo
- `Shift + g` → Ir al final del archivo
- `Shift + h` → Ir al siguiente archivo
- `Shift + l` → Ir al archivo anterior

### Otros comandos útiles

- `.` → Repetir la última acción.
- `~` → Cambiar el caso del caracter bajo el cursor.
- `Ctrl + o` → Volver a la posición anterior.
- `Ctrl + i` → Ir a la siguiente posición.
- `:noh` → Limpiar el resaltado de búsqueda.

## Modo Visual

- `v` → Entrar en modo visual de caracteres.
- `V` → Entrar en modo visual de líneas.
- `Ctrl + v` → Entrar en modo visual de bloque.
- `aw` → Seleccionar una palabra.
- `iw` → Seleccionar palabra interna.
- `ab` → Seleccionar un bloque con ().
- `ib` → Seleccionar bloque interno con ().
- `aB` → Seleccionar un bloque con {}.
- `iB` → Seleccionar bloque interno con {}.
- `at` → Seleccionar un bloque con etiquetas <>.
- `it` → Seleccionar bloque interno con etiquetas <>.
- `o` → Moverse al otro extremo del área marcada.
- `O` → Moverse a la otra esquina del bloque.
- `y` → Copiar texto seleccionado.
- `d` → Eliminar texto marcado.
- `u` → Cambiar texto seleccionado a minúsculas.
- `U` → Cambiar texto seleccionado a mayúsculas.
- `af` → Seleccionar bloques de texto cada vez más grandes.
- `gb` → Añadir un cursor adicional.
- `{movimiento}{operador}` → En modo visual, primero especificas el movimiento para seleccionar texto y luego aplicas el operador.
  > [!TIP]
  > Si Seleccionas varias lineas con `Ctrl + v`
  > y luego presionas `Shift + i` y luego escribes el caracter de comentar una linea
  > seguido de `esc` vas a comentar todas las lineas.

## Marcadores

- `m` + `[letra]` → Crear un marcador en la línea actual.
- `'` + `[letra]` → Moverse al marcador.

## Vim Surround

- `ds{existente}` → Eliminar el entorno {existente}.
- `cs{existente}{deseado}` → Cambiar el entorno {existente} a {deseado}.
- `ys{movimiento}{deseado}` → Añadir el entorno {deseado} al texto definido por {movimiento}.
- `S{deseado}` → Rodear la selección cuando estás en modo visual.

## Atajos de teclado de VSCode

- `Ctrl + p` → Abrir paleta de comandos.
- `>` → Listar todos los comandos.
- `@` → Listar todos los símbolos locales.
- `Ctrl + Shift + .` → Abrir lista de símbolos locales.
- `#` → Listar todos los símbolos globales.
- `Ctrl + Shift + ñ` → Crear nuevo terminal.
- `Ctrl + ñ` → Alternar terminal.
- `Ctrl + PageDown` → Enfocar el siguiente grupo de terminales.
- `Ctrl + PageUp` → Enfocar el grupo de terminales anterior.
- `Alt + Flecha Abajo` → Enfocar el siguiente terminal en el grupo.
- `Alt + Flecha Arriba` → Enfocar el terminal anterior en el grupo.
