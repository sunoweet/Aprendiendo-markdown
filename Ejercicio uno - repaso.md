# Primer ejercicio

Crear un archivo de texto que contenga los siguientes elementos:

- Tres niveles de encabezado
- Texto en negritas, cursiva y combinado
- Una cita de texto, dos citas anidadas y una cita de código
- Una imagen embebida



# Inicio del primer ejercicio

En esta primera práctica lo importante es recordar que los textos elaborados en markdown poseen una sintaxis específica, por ejemplo, combinar elementos en el mismo párrafo **es posible** y no es *algo complicado*, podría combinarse texto en negritas y cursiva solamente encerrando el texto entre tres asteriscos ***como se muestra en esta frase***.

## Iniciamos con una cita

Preparar una cita de texto es algo peculiar, simplemente se debe agregar el símbolo 'mayor que' (>) antes de la frase a citar, así mismo, para anidar citas solamente debe agregarse un espacio, procedamos a agregar un par de citas a este archivo:

> Citar nunca había sido tan fácil.
>
> > Ojala así fuese todo el tiempo.
> >
> > > Esto parece un thread en reddit.

Una cita de código es algo técnicamente diferente, pese a ello, el procedimiento es sencillo, vamos a recurrir a encerrar el código que vamos a escribir entre dos acentos fuertes (`) como se muestra a continuación:

Así nació la primera línea de código de nuestro archivo:`print ('hola mundo')`

Otra manera de hacerlo es insertar un cajón para código (así lo llamo yo) para hacer explicito que estamos diferenciando el código en una frase de una línea de código, para ello agregamos tres veces consecutivas el símbolo (~~~), para obtener el siguiente resultado:

~~~python
print("Hola mundo.")
~~~

## Finalizamos con una imagen

Hay que cumplir con el requisito de añadir una imagen a nuestro archivo para finalizar la práctica, además, aún nos falta añadir un tercer nivel de encabezado, entonces pongamos manos en ello.

### Un tercer encabezado 

Agregar una imagen es una cosa sencilla, basta con escribir entre corchetes el título de nuestra imagen, después, añadimos entre paréntesis el url de nuestra imagen, si queremos hacer visible la imagen (en lugar de tener solo un enlace texto) solamente añadimos este símbolo de exclamación (!) al inicio de la línea de código, como se muestra a continuación:

[Hamtaro final](https://res.cloudinary.com/teepublic/image/private/s--j3PMmCBB--/t_Resized%20Artwork/c_fit,g_north_west,h_1054,w_1054/co_ffffff,e_outline:53/co_ffffff,e_outline:inner_fill:53/co_bbbbbb,e_outline:3:1000/c_mpad,g_center,h_1260,w_1260/b_rgb:eeeeee/c_limit,f_auto,h_630,q_90,w_630/v1536122671/production/designs/3111366_0.jpg)

Ahora, a mostrar la imagen

![Hamtaro final](https://res.cloudinary.com/teepublic/image/private/s--j3PMmCBB--/t_Resized%20Artwork/c_fit,g_north_west,h_1054,w_1054/co_ffffff,e_outline:53/co_ffffff,e_outline:inner_fill:53/co_bbbbbb,e_outline:3:1000/c_mpad,g_center,h_1260,w_1260/b_rgb:eeeeee/c_limit,f_auto,h_630,q_90,w_630/v1536122671/production/designs/3111366_0.jpg)

