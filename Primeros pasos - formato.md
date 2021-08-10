# Aprendiendo a utilizar Markdown: Formato

- Primeros pasos

## Encabezados 

Aprendiendo a crear encabezados, estos se crean poniendo una almohadilla al comienzo de la palabra o frase.

# Una almohadilla

## Dos almohadillas

### Tres almohadillas

#### Cuatro almohadillas

##### Cinco almohadillas

###### Seis almohadillas



## Citas 

Aprendiendo a crear citas en los textos, estas citas se añaden al utilizar los símbolos ''mayor que'' (>) 

> Esto es una cita

Para añadir una cita por debajo de la anterior, debes añadir el mismo símbolo 

> Esto es una cita
>
> > Esto también es una cita
> >
> > > Esta última es una cita

## Listas (con orden y sin orden)

Las listas desordenadas en Markdown son muy sencillas, solo se tiene que comenzarlas con un guion, esto para que se detecten automáticamente: 

- Esto es una lista
- Este es otro elemento de una lista

Algunas aplicaciones aceptarán también asteriscos (*) y símbolos de más (+) para este fin

+ Este fue un símbolo de más
+ Este fue un asterisco
  - Basta con añadir un espacio entre inicios de lista para crear niveles
    - y también subniveles

Si lo que queremos crear es listas numeradas, lo único que debe hacerse es incluir el número seguido de un punto y un espacio antes de comenzar a escribir:

1. Primer elemento de la lista
2. Segundo elemento de la lista
3. Tercer elemento de la lista

## Separadores de textos

Para añadir separaciones de texto, solamente debes escribir tres guiones bajos seguidos para crear la separación de sección

___

Para entenderlo: Markdown intercambiará los símbolos anteriores por la etiqueta <hr> 

# Aprendiendo a usar Markdown: Formato de texto

El lenguaje markdown es muy sencillo, pero requiere que pongas atención en la forma en que escribes la sintaxis y el orden que llevas en tu texto, así como su formato.

## Negritas, cursivas y texto tachado

Con markdown pueden crearse los estilos de letra cursiva y negrita mediante dos formas: con el uso de asteriscos y el uso de guiones bajos.

Si rodeas una palabra o frase con uno de estos símbolos, le darás formato de cursiva a la palabra o frase, ejemplo: *esto es un texto en cursiva, con un asterisco* 

**Esto es un texto en negritas, con dos asteriscos** 

La combinación de ambos elementos genera que ***puedas aplicar a un texto el formato de negritas y cursiva*** 

Tachar texto dentro de un archivo puede ser un recurso utilizado para fines prácticos, por ejemplo, corregir una frase haciendo explícita una diferencia, tachar cambios pendientes, o simplemente con fines estéticos, hacer esto requiere solamente que antes del texto o palabra a tachar se escriba el siguiente símbolo dos veces (~), recordando cerrar la instrucción con el mismo símbolo al final, dos veces, como se muestra a continuación: ~~este es un texto tachado~~

Importante recomendación: el uso de asteriscos se recomienda sobre el uso de guiones bajos, pues dichos guiones pueden entrar en conflicto con la interpretación del formato, resultando en a) nada y b) un bonito guion en pantalla.

 ## Creación de enlaces

Para añadir un enlace al texto, o bien, vincularlo a una palabra, basta con preceder al mismo encerrándolo entre corchetes, justo al lado de la palabra entre corchetes debes colocar el enlace, encerrado entre paréntesis como se muestra a continuación:

[Todopoderoso Google](https://www.google.com/)

¿Qué ocurrió aquí? El producto de combinar [Todopoderoso Google ] + (https://www.google.com/) (sin espacio entre ambos)

Para agregar un título al enlace, basta con añadir entre paréntesis algún texto, claro, esto dentro del área de la URL encerrada entre paréntesis, como se muestra a continuación:

[Todopoderoso Google](https://www.google.com/ 'Este es un enlace')

Si mantienes el curso por encima de la palabra con hipervínculo, podrás ver el texto que dice 'Este es un enlace'

Ahora bien, en caso de que quisieras hacer enlace la propia url, solamente añade los símbolos menor qué y mayor qué entre el texto del enlace, así:

<https://www.google.com/>

<https://www.google.com/> (Como si fuese una etiqueta)



## Añadir imágenes

Puedes añadir imágenes de una forma bastante similar a lo que has hecho con los enlaces, aunque esta vez hay que agregar unos pasos para ello.

Debes escribir entre corchetes el texto que vas a asociar a la imagen, luego, entre paréntesis, procederás a insertar el enlace directo de la imagen, como se observa en el siguiente ejemplo:

[Foto de Hamtaro](https://ih1.redbubble.net/image.171880009.2437/flat,750x,075,f-pad,750x1000,f8f8f8.u3.jpg) 

Para hacer la magia, basta con añadir un signo de exclamación (!) al principio del código, antes de los corchetes:

![Foto de Hamtaro](https://ih1.redbubble.net/image.171880009.2437/flat,750x,075,f-pad,750x1000,f8f8f8.u3.jpg) 

## Añadir código de forma sencilla

Puede darse el caso de que lo que estás escribiendo requiera un poco más de detalle técnico y visual, vamos a asumir que lo que quieres es insertar código, sea para mostrar un ejemplo u diferenciar el mismo, los pasos son los siguientes.

Puedes incluir citas de código de cualquier lenguaje de programación, estas líneas no serán interpretadas, para ello, debes añadir cuatro espacios seguidos en blanco antes del código, en este caso vamos a asumir que solamente se trata de una frase:

`Código`

Una forma más segura de añadir código más extenso es añadir tres veces este símbolo cuyo nombre no recuerdo (~), debes añadirlo tres veces antes y tres veces después de la línea de código:

~~~python
print("Hola mundo.")
~~~

Dependiendo del editor de texto es que solamente puede requerirse añadir tres veces el símbolo ~ al inicio, más no al final. En este caso, Typora lo hace si añades tres veces al inicio.

Puede resaltarse también el código en medio de una frase, para ello, debemos encerrar la palabra o texto entre dos acentos graves (`)

Ejemplo: El estudiante desvelado comenzó a aprender Python con una línea de hola mundo, tan sencilla como un `print("Hola mundo.")`

## Anular el uso de markdown

Como se ha visto, markdown es muy peculiar al momento de utilizar e interpretar símbolos para otorgar formato al texto, lo cual representa un problema si lo que deseamos es utilizar dichos símbolos en nuestros textos.

La manera sencilla y directa de anular la intepretación de markdown es añadir un slash inverso (\\) antes de todo el texto que comenzarás a escribir y que contendrá símbolos o caracteres específicos.

Texto con markdown

Quiero mostrar un texto *entre asteriscos* 

Texto sin markdown

Quiero mostrar un texto \*entre asteriscos*











