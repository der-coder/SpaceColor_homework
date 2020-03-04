# SpaceColor_homework
Homework for the Computer VIsion I course

-----


1. Definición de un nuevo espacio de color. Para definir un “nuevo” modelo de
color, deberán seleccionar el canal o canales de los espacios de color vistos en
clase e incluirlos en su nuevo modelo de color. Al menos uno de los canales del
modelo de color que definan deberá poder discriminar claramente (en tonos
blancos, si está representado en escala de grises) el color especificado por la
tupla: <R,G,B>, la cual será enviada vía correo electronico a cada equipo, junto
con una imagen de prueba.

2. Operadores puntuales: Implementa en MATLAB los siguientes operadores
puntuales:
a) estrechamiento del contraste,
b) uso de umbrales, e
c) histogramas.
Tus funciones deberán lucir como sigue:
function_contraste = contraste(imagenE,imagenS,alpha,beta,gamma);
function_umbral = umbral (imagenE,imagenS,umbral);
function_histograma = ecualizar(imagenE,imagenS);
.
Realiza las corridas de los tres operadores en cada una de las imágenes que
elegiste, haz un análisis comparativo de los resultados obtenidos, escribe el
reporte del análisis, así como tus conclusiones.

3. Filtrado: Implementar en MATLAb el filtro de Butterworth. La función debe
lucir como sigue:
function_butterworth =butterworth(imagenE,imagenN,D0);
Se debe desplegar la imagen de entrada y la imagen filtrada normalizada.
Probar con diferentes imágenes y valores de D0.
