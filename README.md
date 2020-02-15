# Markdown
Instrucciones para comprender los lenguajes de programación enfocado a Mackdown
***
## Titulos
para generar titulos se utiliza "#" acompañado del texto

#### Codigo
~~~
# titulo
## titulo
### titulo
#### titulo
##### titulo
###### titulo
~~~
los niveles de titulos dependen de la cantidad de "#" que posee
#### Vista:

# titulo
## titulo
### titulo
#### titulo
##### titulo
###### titulo

***
# Estilos del texto

Para agregar efectos al texto de realizan las siguientes adiciones
#### Codigo
~~~
*cursiva*
**negrita**
~tachado~
***negritacursiva***
~~~
#### Vista
*cursiva*
**negrita**
~tachado~
***negritacursiva***

***
# Tablas
Para generar una tabla se inicia el encabezado con cada uno de los titulos sepadados por "|"
#### Codigo
~~~
alumno|nota|identificacion
---|---|---
juan|4.2|120471    
luis|3.5|154595
jorge|5.0|755554
~~~
#### Vista

alumno|nota|identificacion
---|---|---
juan|4.2|120471    
luis|3.5|154595
jorge|5.0|755554

***
# Listas
### listas ordenadas
para generar las listas ordenadas se enumeran los indices

#### Codigo
~~~
1. manzana
2. pera
3. naranja
~~~
#### Vista
1. manzana
2. pera
3. naranja
### listas desordenadas
para generar las listas ordenadas se inican los indices con * , +,-

#### Codigo
~~~
* pera
+ naranja
- sandia
~~~
#### Vista
* pera
+ naranja
- sandia
### Listas de tareas
para una lista de tareas con checks al inicio del texto se utilizan * [ ]
#### Codigo
~~~
* [x] Instruccion
* [ ] Marco teorico
* [ ] Justificacion
~~~
#### Vista
* [x] Instruccion
* [ ] Marco teorico
* [ ] Justificacion
***
# Citas
Para agregar citas se utiliza ">"
#### Codigo
~~~
>"Un buen navegante solo navega por amor al mar" -Anonimo
~~~
#### Vista
>"Un buen navegante solo navega por amor al mar" -Anonimo

***
# Enlaces
Para realizar un enlace se ingresa la palabra clave dentro de corchetes y el link dentro de parentesis
Entre corchetes agregamos el nombre el nombre del enlace **[buscar]** y a continuación entre paréntesis la url **(http://www.google.com)** madianet el siguiente codigo
#### Codigo
~~~
[Buscar](http:/google.com)
~~~
#### Vista
[Buscar](http:/google.com)

***
#Imágenes
La manera de enlazar imágenes es básicamente la misma de crear enlaces, con una única diferencia, se añade el carácter de exclamación ! al principio de la pareja de corchetes que definen el nombre del enlace. La imagen se puede cargar en una carpeta de forma que entre corchetes se agreguen la ruta, por ejemplo: imagenes/tres.jpg
~~~
![Uno](imagenes/2000000001.jpg "ejemplo")
~~~
![uno](Imagen/2000000001.jpg "Ejemplo")
