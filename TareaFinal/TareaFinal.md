# TareaFinal
> Resolver dos ejercicios con base a la información que se encuentra en CODAP sobre lo ocurrido en la muestra de 500 combos de Hamburguesa, salsa, papas y refresco.

https://codap.concord.org/releases/latest/static/dg/en/cert/index.html#shared=106296  

    La tabla muestra los datos del consumo de 500 clientes que pidieron un combo en un restaurante de hamburguesas, seleccionados aleatoriamente.

    Las variables son:

    Carne.- Peso de la carne por hamburguesa, en gramos.

    Salsa.- Cantidad de salsa ocupada por el cliente, en gramos.

    Papas.- Tamaño de las papas pedidas por el cliente.

    Refresco.- Tamaño del refresco pedido por el cliente.

> En la página web se puede ver un documento "Actividad final por pares.pdf" para descargar

> La actividad se divide en dos ejercicios. Recuerda revisar la lista de cotejo antes de subir tu archivo a la plataforma. En el primer ejercicio realizarás un reporte sobre lo ocurrido en la muestra de 500 combos de hamburguesa, salsa, papas y refresco; en la segunda parte resolverás preguntas puntuales sobre la misma muestra.

## Contenido de "Actividad final por pares.pdf"

## Documento final

### Ejercicio 1
*  Descripción Variable Carne:
    - mediana=90.03 gramos
    - promedio=media= 90.02 gramos
    - desviación estándar= 2.04 gramos
Observamos que la representación gráfica (histograma continuo) de los datos en el plano presentan una clara distribución normal simétrica (es decir podemos ver la mayoría de datos debajo de una campana de Gauss).
En el diagrama de caja podemos observar que el valor del primer cuartil es Q_1= 88.596 gramos y el del tercer cuartil Q_3=91.3686 gramos. También podemos observar 3 valores o datos atípicos: 83.1616, 83.6483, 97.7986. (Todos los valores en gramos).

* Descripción variable Sala:
    - mediana= 5.60 gramos
    - promedio= 5.608 gramos (casi igual que la mediana)
    - desviación estándar= 0.234 gramos
Observamos que en la representación gráfica (pseudohistograma) se puede observar una clara distribución normal simétrica (es decir, los puntos quedan debajo de una curva de Gauss).
En el diagrama o gráfico  de caja podemos observar que el valor del primer cuartil es Q_1=5.46569  gramos y el del tercer cuartil Q_3=5.76792 gramos. También podemos observar 4 valores atípicos: 4.92999, 5.00779,6.2556, 6.36586. (Todos los valores en gramos de salsa).

* Descripción variables conjuntas (continuas) Carne y Salsa:
Observando el diagrama de dispersión (también llamado, nube de puntos) podemos considerar la idoneidad de efectuar una aproximación por un modelo lineal (es decir, aproximar por una recta de ajuste o regresión). Si calculamos el coeficiente de correlación (o coeficiente de Pearson), que en este caso es de 0.88, concluimos que si que es coherente aproximar el modelo por una recta (modelo lineal). La ecuación  de la recta de ajuste en el eje OY gramos de salsa y  en el eje OX gramos de carne es y=0.1011*x-3.5, todo en unidades de gramos.

* Descripción tamaño papas:
Para hacer la descripción podemos enumerar las frecuencias absolutas y relativas de cada uno de los tres eventos de mayor frecuencia a menor:

- Papas tamaño Medianas: 247 de 500 (49%)
- Papas tamaño Grandes: 166 de 500 (33%)
- Papas tamaño Chicas: 87 de 500 (17%)

(Casi la mitad de los clientes de la muestran piden Papas de tamaño Mediano)

* Descripción tamaño refresco:
Para hacer la descripción podemos enumerar las frecuencias absolutas y relativas de cada uno de los tres eventos de mayor frecuencia a menor:

- Refresco tamaño Mediano: 250 de 500 (50%)
- Refresco tamaño Chico: 83 de 500 (33%)
- Refresco tamaño Grande: 167 de 500 (17%)

(La mitad de los clientes de la muestran piden Refresco de tamaño Mediano)
(Los porcentajes entre Papas y Refrescos curiosamente similares)

* Descripción variables conjuntas (discretas) tamaño papas y tamaño refresco:
Para hacer la descripción enumeramos los valores de mayor freqüencia a menos frequencioa de las diferentes 9 posibles combinaciones de tamaños de patatas (papas) fritas y tamaños de refrescos:

27%  (134 de 500) seleccionaron Papas tamaño Medianas y Refresco tamaño mediano
16%  (80 de 500) seleccionaron Papas tamaño Grandes y Refresco tamaño mediano
16%  (78 de 500) seleccionaron Papas tamaño Medianas  y Refresco Chico tamaño 

11%  (54 de 500) seleccionaron Papas tamaño Grandes  y Refresco Chico tamaño 
7.2% (36 de 500) seleccionaron Papas tamaño Chicas  y Refresco Mediano tamaño 
7%   (35 de 500) seleccionaron Papas tamaño Chicas y Refresco tamaño Chico 

7%   (35 de 500) seleccionaron Papas tamaño Medianas y Refresco tamaño Grande 
6.4% (32 de 500) seleccionaron Papas tamaño Grandes y Refresco tamaño 
3.2% (16 de 500) seleccionaron Papas tamaño Chicas  y Refresco tamaño Grande 

(La combinación más frecuente con menos de un 30% de los clientes de la muestra piden conjuntamente Papas y refresco Grandes).


### Ejercicio 2
* Para cada una de las siguientes preguntas, escribe el resultado, agrega
evidencia de cómo llegaste a él y la interpretación del mismo. (La
evidencia será una captura de pantalla.)

1. ¿Cuánto vale el coeficiente de correlación entre las variables Carne y
Salsa? Aproxima a dos decimales.

>Resultado: 
El coeficiente de correlación o coeficiente de Pearson entre las variables Carne y
Salsa, aproximado a dos decimales con punto decimal es, 0.88.

>Breve evidencia:
Podemos llegar fácilmente a este resultado utilizando la plataforma CODAP y efectuando la raíz cuadrada de r^2. Sino podemos exportar los datos y utilizar una hoja de excel "=COEF.DE.CORRL(DatosCarne;DatosSalsa)".

>Interpretación resultado:
La interpretación de este resultado es relativamente fácil. Como el resultado es un valor numérico "bastante próximo a 1" sabemos que el diagrama de dispersión podrá ser bien aproximado por una recta.

2. ¿Qué cantidad de salsa, en gramos, se esperaría que un cliente le ponga
a su hamburguesa si ésta tiene 89 gramos de carne? Redondea a dos
decimales.

>Resultado: 
Podemos esperar que el cliente ponga, aproximadamente redondeando a dos decimales después del punto, 5.50 gramos de salsa.

>Breve evidencia:
Podemos usar la ecuación de la recta calculada
0.1011 * 89 − 3.5= 5.4979, redondeado a dos decimales, 5.50 gramos. También podemos usar otras herramientas de la plataforma CODAP.

>Interpretación resultado:
Observando el resto de valores parece un valor bastante verosímil. Es decir parece aproximar-se bastante a lo observado en la muestra de datos que tenemos.

3. ¿Qué combinación de papas y refresco es la más frecuente?

>Resultado:
La combinación de papas y refresco más frecuente es refresco mediano y papas medianas.

>Breve evidencia:
De las 9 combinaciones posibles la que más frecuencia tiene es la de "refresco mediano y papas medianas" con 134 muestras de las 500, un 27% del total! Se puede utilizar una tabla de doble entrada. A veces también se suele llamar a estas tablas tablas de contingencia. 

>Interpretación resultado:
De nuevo el resultado, parece bastante coherente con lo que podríamos esperar a priori.

4. ¿Qué combinación de papas y refresco es la menos frecuente?

>Resultado:
La combinación de papas y refresco es la menos frecuente es patatas chicas y refresco grande.

>Breve evidencia:
Utilizando la tabla de contingencia (o de doble entrada) obtenemos que la combinación menos frecuente es refresco grande y patatas chicas con un 3.2% (solo 16 de 500).

>Interpretación resultado:
El resultado resulta curios, aunque tampoco podemos saber con seguridad el porqué, sin un mayor análisis.

5. Calcula la probabilidad que hay de que un cliente seleccionado al azar
haya pedido...

a) Papas medianas:
>Resultado: 
La probabilidad de que un cliente seleccionada al azar haya seleccionado papas medianas es de  0.49.
>Breve evidencia: Los cálculos  son 247/500=0.494, aunque CODAP ya los da directamente
>Interpretación resultado:
Podríamos decir que: prácticamente la mitad de la gente de la muestra pide patatas medianas. 

b) Papas medianas o refresco chico:
>Resultado: 0.66 (aunque es mejor aproximación 336/500=0.672 )
>Breve evidencia: Las personas que seleccionaron papas medianas son 247 y las que seleccionaron refresco chico 167. Las que seleccionaron papas medias y refresco chico a la vez fueron 78. Por tanto 247+167-78=336, dividio por el número total de casos (500), 336/500=0.672. Si sencillamente sumamos los valores en percentatge 0.49+0.33-0.16=0.66
>Interpretación resultado:
Más de un 60 % de las muestras cumplen Papas medianas o refresco chico.

c) Papas grandes y refresco chico:
>Resultado:  Aproximadamente 0.11.
>Breve evidencia: No hace efectuar ningú calculo extra, se puede sacar el dato directamente de la tabla de doble entrada o de contingència.

>Interpretación resultado: Un 11 % de la muestra selecciona la combinación Papas grandes y refresco chico. Si seleccionaramos al azar entre los 500 datos que tenemos registrados hay una probabilidad del 0.11 de seleccionar un usuario que haya seleccionado Papas grandes y refresco chico.

d) Refresco chico si pidió ya papas grandes:
>Resultado: Aproximadamente 0.33.

>Breve evidencia: Usamos la fórmula para probabilidad condicionada con ayuda de la tabla. P=(0.11)/(0.11+0.064+0.16)~0.33.

>Interpretación resultado: El 33% de los datos que disponemos de clientes que seleccionaron papas grandes también seleccionaron refresco chico. (Se supone refresco grande y dentro de este subconjunto del espacio muestral se mira, además, que gente selecciono refresco chico. Es un concepto un poco lioso pero si se mira con calma se entiende su gran utilidad.)  


6. ¿Los eventos papas grandes y refresco grande son independientes? Sí,
No y Por qué.
>Resultado: No
>Breve evidencia: 
P(PapasGrandes)=0.332
P(RefrescoGrande)=0.166
P(PapasGrandes)*P(RefrescoGrande)=0.055112
P((PapasGrandes) y (RefrescoGrande))=0.64000
Por tanto no son eventos independientes.
>Interpretación resultado: Utlizamos el test de independència que se puede ver el los calculós. Como 0.055112 es suficientemente diferente de 0.64000, podemos concluir que los eventos no son del todo eventos independientes. 
