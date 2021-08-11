# Segundo ejercicio

Crear un archivo de texto que posea los siguientes elementos:

* Un texto cualquiera, seguido de una cita a una línea de código (puede ser cualquier lenguaje)
* Una tabla cuyas dimensiones sean (4 * 4) cuyo contenido  (salvo los rótulos de la tabla) sea completamente numérico, con números en negritas.
* Una imagen cualquiera y que sea visible en el archivo sin necesidad de dar click en enlace alguno
* Tres citas anidadas de texto (es decir, una dentro de otra)
* Un salto o quiebre de línea.

# Inicio del segundo ejercicio

## Cita de código 

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod  tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim  veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea  commodo consequat. Duis aute irure dolor in reprehenderit in voluptate  velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint  occaecat cupidatat non proident, sunt in culpa qui officia deserunt  mollit anim id est laborum.

De tal forma que, el siguiente código muestra lo escrito en el párrafo anterior:

~~~R
# Genera número aleatorios para utilizarlos en esta práctica
set.seed(1234)

# Número total de observaciones
N <- 67

# Simula una variable x bajo una distribución uniforme 
x <- runif(N, 1, 40)

# Simula el comportamiento de una variable y
y <- 40 + .5 * x + rnorm(N, 0, 2)
~~~

## Creación de tabla

Vamos a asumir que el código anterior nos dio un par de números aleatorios, de los cuales podemos tomar algunos para crear una bella tabla que no signifique nada, pero sirva de ejemplo para aprender a crear tablas: 



| Frutas  | Verduras | Dulces  | Monedas |
| ------- | -------- | ------- | ------- |
| **24**  | **32**   | **45**  | **56**  |
| **45**  | **76**   | **64**  | **46**  |
| **102** | **245**  | **120** | **131** |



## Insertando una imagen

La siguiente imagen es solamente referencial, muy bella, por cierto.

![Gran Hamtaro](https://w7.pngwing.com/pngs/530/422/png-transparent-hamtaro-ham-ham-games-hamster-anime-television-show-tv-tokyo-anime-white-face-cat-like-mammal.png)



## Citas de texto

Recordando que las citas de texto se realizan al agregar al inicio de la línea de texto el símbolo 'mayor que' (>), como se observa a continuación:

> Esta es una cita de texto
>
> > Esta es una segunda cita de texto
> >
> > > Esta es una tercera cita de texto, bien anidada.

# Salto de hoja

El salto de hoja se realiza solamente al añadir tres guiones bajos (_) al principio de una línea de texto, como se muestra a continuación:

___

