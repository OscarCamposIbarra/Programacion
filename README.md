	Cálculo de superficies, distancias y azimut de un terreno 

Oscar Campos (1), Edgar Rosales (2), Fernando Carrillo (3)
Universidad de Colima, Campus Coquimatlán, Facultad de Ingeniería Civil, 28400, ocampos@ucol.mx, edgargabriel_rosales@ucol.mx, luisfernando_carrillo@ucol.mx. 
 
Resumen
Programa que pueda obtener la superficie, distancia y azimut con datos reales del usuario.
Palabras clave: Programa que calcula la superficie, distancia y azimut.
1. 	Introducción 
La topografía es la ciencia que estudia la superficie terrestre, con el siguiente programa queremos ayudar a obtener la superficie de un terreno.
Este proyecto está ideado para crear una aplicación capaz solucionar pequeños problemas en este campo de estudio, dando pues la respuesta al nombre de los tipos de enlaces vistos en clase.
Con este programa queremos hacer que el usuario haga los cálculos de su levantamiento topográfico de manera rápida y con cero fallas, ya que, los cálculos que el programa realiza son muy extensos a mano.
El siguiente programa fue realizado con el lenguaje de programación “Python” y utilizamos las fórmulas matemáticas necesarias.
En este nivel de estudios que se lleva alcanzado en la carrera de Ingeniero Topógrafo Geomántico he podido realizar diferentes particas de levantamiento de pequeñas extensiones de tierra utilizando diferentes métodos y cálculos matemáticos que el profesor de la materia de topografía 1 nos ha enseñado. 
Abstract:
Program that can obtain the surface, distance and data with the real data of the user.
Keywords: Program that calculates the surface, distance and azimuth.
.
2. 	Desarrollo 
En la primera parte de nuestro trabajo importé lo necesario para que mi programa pueda compilar correctamente.
 
Math es para que se puedan realizar operaciones y tkinter es para que se puedan hacer ventanas. 
Después creamos la primera ventana, que dicha ventana es la ventana padre, que contendrá los demás cálculos.
 
Esta ventana tiene parámetros que yo le ingresé a mi gusto.
En esa misma ventana le agregamos cuatro botones que serán los que dirijan a los 3 cálculos y el último es un botón de salir.
 
EL comando “ventana.mainloop()” es para que no se cierre al momento de ejecutarlo y que nos dé tiempo para ver el contenido.
El comando “command=abrirventana1” nos ayuda a abrir la primera ventana, que en este caso es la de supericie.
 
En esta parte tiene el acomodo y el diseño de la ventana a mi gusto, tiene 3 cajas de texto, que sirven para que el usuario le pueda ingresar los valores, contiene dos botones, uno para ingresar el resultado y que te arroje los datos y el otro para borrar, y por último y más importante creamos las variables, donde utilizando los comandos float e input, se le pedirá al usuario que ingrese los datos correspondientes a su distancia de su polígono en este caso son a, b, c. Después sacaremos la fórmula del semiperímetro que esta nos ayudará para calcular las mediciones de nuestro terreno, ya ingresados los datos a, b, c dividido entre dos nos da lo que es el semiperímetro.
 
Para el cálculo de la cual sacaremos lo que son nuestra superficie.
 

En la segunda ventana tiene exactamente el mismo acomodo que la primera, pero en esta vetana tiene cuatro cajas de texto, que nos servirán para que ingrese las coordenadas de dos puntos, que son x1, y1 y x2, y2.
 
En este proceso calculamos la superficie, con la primera línea de código colocamos lo que la fórmula para calcular la superficie nos indica, y como línea que continua obtuvimos la raíz cuadrada de la línea de código anterior, posteriormente imprimimos la superficie.
 
A continuación, pedimos dos coordenadas x y dos coordenadas y2, para que a podamos obtener la distancia y el azimut.
 
En estas líneas de hicimos la fórmula para sacar distancia y la imprimimos.
En la tercer y última ventana calculamos el azimut, el orden de todo es como la ventana dos.
 
 
Para finalizar realizamos la fórmula para obtener el azimut, y posteriormente lo imprimimos.
3. 	Manejo de datos
Al momento de ingresarle los datos de a, b y c, se resolverá la fórmula del semiperímetro y resolviendo eso, se podrá realizar la fórmula de la superficie.
 
El programa realiza Distancias y Coordenadas, las cuales, en cada una de estas, en las coordenadas maneja “x y y” para esto se manejarán en columnas para su desarrollo del programa ya que este lo ara automáticamente te dará los resultados que tu adquieras, para esto se utilizarán las proyecciones corregidas ya que estamos trabajando con eso.
Primero lo que realizara el programa es pedirte las coordenadas arbitrarias y dos más para así poder trabajar, además cuando las des, el programa compilara en la cual te dará el azimut y distancias.
 
 
Con base de estas coordenadas realizamos las fórmulas de distancia y azimut.
 
Este programa realizado es de gran utilidad para las personas que trabajan en el área de ingenieros u otras carreras ya que es fácil de utilizar, además es eficiente y también es una de las cosas de las cuales los ing.
Topógrafos la ocupan para un mejoramiento. Este programa maneja con Python para su mejoramiento ya establecido, el Python que utilizamos corre en Windows.
4. 	Resultados
En programa se compila correctamente y hace lo que escribimos desde un inicio, y lo muestra de una manera sencilla y entendible, para cuando el usuario lo ejecute logre saber qué hacer.
La primera ventana se muestra al momento de correrlo, y se muestran los 4 botones: el primero es de superficie, el segundo es de distancia, el tercero es de azimut y por ultimo le agregué un botón de salir.
 
Al cliquear el botón de “Salir”, automáticamente se cerrará el programa.
Al cliquear el botón de “superficie”, se abrirá la ventana correspondiente y el usuario podrá ingresar los datos deseados y al cliquear ingresar, te dará el resultado:
 
Al hacer clic en “Distancia”, el usuario podrá ingresar los datos correspondientes y al cliquear ingresar, te dará el resultado:
 
Al hacer clic en “Azimut”, podrás ingresar los datos y al cliquear ingresar, te dará el resultado:
 
A todos las ventanas con título “Ventana bien padre” le agregué un botón de borrar, lo que hace este botón es borrar todo el contenido que esté en las cajas de texto, para que así pueda el usuario ingresar más datos.
 
5. 	Conclusión 
Oscar Ignacio Campos Ibarra: Con el siguiente programa me permite obtener varios valores que son útiles para los levantamientos topográficos que realizaré en un futuro. A pesar de que en el programa solo le puedo meter pocos datos, me sirve para lo que quiero realizar. El objetivo que esperaba de este programa me fue satisfactorio, aunque nos hubiera gustado que fuera un poco mejor.
Edgar Gabriel Rosales Figueroa:
La realización de este proyecto, en el ámbito personal me ayudo a saber desarrollar un programa con el cual podemos hacer nuestro trabajo de campo más sencillo ya que, nos ahorran tiempo y no es necesario tener que usar una calculadora convencional. El proyecto puede ser desarrollado más afondo para así obtener todos los cálculos necesarios que se necesitan en un levantamiento topográfico, para con el fin de solo ingresar un archivo de datos en ventanas que arroje el programa y el este identifique los datos y realice los cálculos necesario para nuestro levantamiento.
Luis Fernando Carrillo Cruz: El proyecto salió de la mejor manera posible, me gusta mucho el resultado y pienso que le otorgamos mucha dedicación al programa.
Mi entendimiento en programación ha mejorado al realizar este proyecto.
6. 	Bibliografía
cctmexico. (27 may 2017). TkInter para Python: ¿Cómo activar una segunda ventana, con un botón y una condición? (Básico). 08/06/2019, de cctmexico Sitio web: https://www.youtube.com/watch?v=hky6aQw65lw&list=LLdtz3RJMxLq-f6MObh8cK1Q&index=4&t=0s
cctmexico. (21 abril 2017). TkInter para Python: Programar los botones, suma de dos números (Básico). 08/06/2019, de cctmexico Sitio web: https://www.youtube.com/watch?v=D4_SQawLwQs&list=LLdtz3RJMxLq-f6MObh8cK1Q&index=2
