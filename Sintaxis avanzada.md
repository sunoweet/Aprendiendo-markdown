# Elementos intermedios de markdown: sintaxis complementaria.

La sintaxis de markdown es muy sencilla, la combinación de los elementos de la misma da lugar a muchas posibilidades, como tal, markdown es especialmente utilizado para documentar código y proyectos en la red, por lo cual su aprendizaje resulta complementario a los conocimientos técnicos que uno posee.

Debe recordarse que, para la elaboración de otro tipo de textos, documentos o archivos de investigación, podría ser preferible el aprendizaje de LaTeX.

## Recordatorio respecto al uso de markdown

Como se ha mencionado, markdown puede ser utilizado para redactar textos y documentar código, la sintaxis básica nos mostró algunos elementos importantes respecto al formato de MD:

1. Los títulos y subtítulos, al igual que en código HTML, pueden crearse con etiquetas en específico por nivel, en el caso de markdown utilizamos el símbolo de (#), aumentando el número de símbolos de número para señalar el nivel del encabezado.

2. Anular la interpretación del lenguaje markdown puede hacerse tan solo con añadir un slash inverso (\\) antes de la línea de código o de texto que se piensa escribir

3. Agregar comentarios en markdown es similar a hacerlo en HTML, se encierra entre los símbolos 'menor qué' (<) y 'mayor que' (>) el texto a comentar, como se muestra a continuación: 

   

   <!--- Comentario --->

Dicho lo anterior, comencemos con un poco de orden, recuerda lo siguiente:

> Lo más importante en Markdown es llevar un orden claro y conciso, aunque este tutorial no se vea como el mejor ejemplo de ello.

___

## Especificar el lenguaje de programación de una línea de código

Recordemos que, la forma en que puede citarse una línea de código viene dada por la inserción del siguiente símbolo (~) tres veces antes de la línea a citar, como se muestra a continuación:

~~~
# Este código realiza la suma de dós números
num1 = 2
num2 = 3
# Realizar la suma correspondiente
suma = num1 + num2
# Presentar resultado
print('La suma de {0} y {1} es {2}'.format(num1, num2, sum))
~~~

Ahora bien, para especificar el lenguaje de programación al cual corresponde la línea de código, debe añadirse después del símbolo (~)* el nombre del lenguaje de programación, por ejemplo:

~~~Python
# Este código realiza la suma de dós números
num1 = 2
num2 = 3
# Realizar la suma correspondiente
suma = num1 + num2
# Presentar resultado
print('La suma de {0} y {1} es {2}'.format(num1, num2, suma))
~~~

Nota* En el archivo .md sin procesar debería ser visible esta acción, al utilizar Typora no es posible ver directamente esta parte de la sintaxis pues se realiza en automático

## Crear una tabla en markdown

Generar tablas en markdown no es difícil, pese a ello, suele ser un error común crear dichas tablas sin dimensionar adecuadamente el tamaño y número de filas x columnas a utilizar; lo primero que debe comprenderse es la siguiente idea:

* Una tabla se compone de un espacio de m filas por n columnas
* Generalmente, la primer fila está destinada a los títulos o encabezados de las columnas en la tabla
* El espaciado deberá realizarse con tabulador, con la finalidad de delimitar adecuadamente el espacio de separación entre nuestros campos

Ahora bien, el símbolo (|) es indispensable para la creación de tablas, este se agrega para delimitar la separación entre filas y entre columnas, creando así una tabla, un ejemplo práctico visual sería el siguiente

\ |	Categoría	|	Primer criterio	|	Segundo criterio	|

\ |	Nombre	   |	Valor de celda    |	Valor de celda	   |

Quedando explícita la estructura y la forma, procedamos a crear una tabla de tres columnas y cuatro filas:



| Monedas | Manzanas | Peras |
| ------- | -------- | ----- |
| 35      | 5        | 7     |
| 49      | 7        | 7     |
| 24      | 4        | 6     |

Dependiendo del editor de markdown y las extensiones propias del mismo, la creación de tablas puede contener más o menos opciones de edición para la misma. En el caso de este ejemplo, al haber sido creado mediante Typora, nos permite seleccionar la alineación del texto y redimensionar la tabla.

## Crear una checklist

En Github puedes emplear un checklist para señalar tareas que has realizado, elementos corregidos de un archivo .md, o bien, una lista cuyo detalle visual sea un poco más 'elaborado', vamos a crear una lista como si fuese un checklist, la sintaxis detrás de esto es la siguiente:

Coloca primero un asterisco, añade un espacio y después dos corchetes, afuera del espacio de los corchetes podrás añadir el texto correspondiente a la tarea.

* [x] Primer ejercicio resuelto
* [ ] Segundo ejercicio resuelto

Para marcar la tarea como 'realizada' solamente añade una 'x' dentro de los corchetes, o bien, para dejarla como 'no realizada' sencillamente deja el espacio sin llenar.

\* Nota, el checklist no es un estándar en markdown, por lo cual su visualización depende de tu editor de texto, así mismo, algunos pedazos de código podrían no interpretarse en algún blog, visualizador, entre otras herramientas.

En los próximos ejercicios sobre markdown daremos un repaso final a los elementos avanzados de la sintaxis (Multimarkdown), como podrás observar, el aprendizaje de este lenguaje de marcado ligero resulta muy sencillo, práctico, eficiente si lo que deseas es comenzar a editar tus propios archivos documentados en Github.

