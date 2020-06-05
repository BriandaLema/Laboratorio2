# LABORATORIO # 01

TEMA: LEYES DE KIRCHHOFF
## 1. OBJETIVOS

**1,1.- GENERALES** 

* Explicar y demostrar experimentalmente la Ley de Kirchhoff de Voltajes y la Ley de Kirchhoff de Corrientes. 

* Observar como se efectua un circuito mixto en condiciones simuladas y teoricas.

**1,2.-ESPECÍFICOS**

* Hallar las corrientes y voltajes de cada elemento del sistema.

* Distinguir las mallas, los nodos y las ramas del sistema

## 2. MARCO TEÓRICO 

**LEYES DE KIRCHHOFF**

Las leyes de Kirchhoff fueron planteadas por Gustav Kirchhoff en 1845, en la actualidad son muy utilizadas en la física eléctrica para obtener los valores de la corriente y voltaje en cada uno de los puntos de un circuito eléctrico.
Estas leyes escriben el comportamiento de la corriente en un nodo , y el voltaje alrededor de una trayectoria cerrada, estos dos planteamientos , junto con las ecuaciones de componentes individuales como resistores, capacitores, entre otros, obtenemos un conjunto de herramientas básicas para el análisis de circuitos.

**LEY DE CORRIENTE DE KIRCHHOFF** 

La ley de corriente de Kirchhoff (LCK) establece que la suma algebraica de todas las corrientes que ingresan hacia un nodo es igual a la suma algebraica de las corrientes que salen del nodo. Es decir: 

∑i(ingresan)=∑i(salen)

**LEY DE VOLTAJE DE KIRCHHOFF**

La ley de voltaje de Kirchhoff (LVK) establece que la suma algebraica de las caídas de voltaje en una trayectoria cerrada es igual a cero. Es decir: 

∑Vi(t)=0

Tomemos en cuenta que la caída de voltaje sucede cuando el voltaje pasa a través de un componente y a su salida obtiene un valor menor que el inicial.


## 3. DIAGRAMAS

Para este laboratorio se utilizó un circuito mixto en donde encontramos que las resistencias R2 y  la suma de las resistencias R4 y  R3  hacen un circuito en paralelo y las resistencias restantes forman un circuito en serie, esta unión de dos circuitos es lo que nos hace llamarlo  MIXTO

![](https://github.com/BriandaLema/Laboratorio1/blob/master/img/Terrific%20Albar.png)

## 4. LISTA DE COMPONENTES

1 Fuente de Voltaje 

2 Multímetros digitales 

1 Resistencia de 1 kΩ

2 resistores de 2,2 kΩ

1 Resistencia de 1,8 kΩ

1 resistencia de 3,9 kΩ

1 Protoboard


## 5. EXPLICACIÓN CÓDIGO DE FUENTE

Para este laboratorio utilizamos el simulador de Tinkercad , el cual es un sofware de diseño de circuitos, en este dispositivo encontramos una gama alta de componentes electrónicos que se utilizan para la creación de circuitos y simular su funcionamiento.
Tinkercad funciona directamente en un navegador web moderno por lo cual una conexión a internet es fundamental para la utilización de esta fuente. 

El mismo programa nos guía y asesora acerca de lo que realizamos, por lo cual la utilizacion de esta fuente es muy práctica si tienes un conocimiento básico sobre circuitos eléctricos.Una herramienta característica de Tinkercad es quemientras la simulación está en marcha podemos ir modificando las variables de cada elemento y ver los cambios en el momento. También podemos obtener una lista con los materiales empleado  que nos sirvio para realizar las fichas técnicas.



## 6.- DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

Para complementar la correcta cuantificacion de valores calculados y valores medidos se utilizo una aplicación más denominada Multisim, que es un programa que se debe instalar en un sistema inteligente para poder hacer una grafica y simulación de un circuito.

## 7.- CONCLUSIONES

**ANÁLISIS DE RESULTADOS Y CÁLCULO DEL ERROR**

- RESULTADOS OBTENIDOS DE VOLTAJE Y CORRIENTE EN CADA ELEMENTO DEL CIRCUITO 

| VARIABLE | VALOR CALCULADO | VALOR MEDIDO |
| ------------- | ------------- | ------------ |
| VR1 (V)  | 2.0544 V  |  2.05 V  |
| IR1 (mA)  | 2.0544 mA  |  2.05 mA  |
| VR2 (V)  |  4.2475 V  |  4.25 V  |
| IR2 (mA)  |  1.089 mA  |  1.09 mA  |
| VR3 (V)  |  2.1235 V  |  2.12 V  |
| IR3 (mA)  |  0.9653 mA  |  0.956 mA  |
| VR4 (V)  |  2.1235 V  |  2.12 V  |
| IR4 (mA)  |  0.9653 mA  |  0.965 mA  |
| VR5 (V)  | 3.6979 V  |  3.70 V  |
| IR5 (mA)  |  2.0544 mA  |  2.05 mA  |

- CÁLCULO DEL ERROR DEL VOLTAJE 

∑(Voltaje calculado)= (2.0544 + 4.2475 + 2.1235 + 2.1235 + 3.6979) V

∑(Voltaje calculado)= 14.2468 V

∑(Voltaje medido)= (2.05 + 4.25 + 2.12 + 2.12 + 3.70) V

∑(Voltaje medido)= 14.24 V

%error=((Valor teórico-Valor medido)/Valor teórico)* 100

%error=((14.2468 V - 14.24 V)/ 14.2468 V)* 100

%error= 0.048 % 

- CÁLCULO DEL ERROR DE LA CORRIENTE

∑(Corriente calculado)= (2.0544 + 1.089 + 0.9653 + 0.9653 + 2.0544) mA

∑(Corriente calculado)= 7.1284 mA

∑(Corriente medido)= (2.05 + 1.09 + 0.956 + 0.965 + 2.05) mA

∑(Corriente medido)= 7.111 mA


Las leyes de voltaje y corriente de Kirchhoff son herramientas esenciales para la resolución de circuitos electrónicos, que ayuda a determinar valores de voltaje y corriente en el mismo, y así poder analizar gran variedad de circuitos eléctricos.

Hay una pequeña diferencia entre los valores medidos y calculados, se podría dar por dos razones : al momento de medir con el multímetro los valores de  los voltajes y  las corrientes, intervienen las tolerancias de las resistencias, y esto podría afectar a los valores obtenidos; mientras que en los valores calculados intervienen los decimales al momento de ir desarrollando los cálculos correspondientes,  lo cual también afectaría los valores que vamos obteniendo. 

8.- RECOMENDACIONES

Consideramos importante el recomendar un mejor sistema de explicación acerca del trabajo a realizar.

Una recomendación fundamental que proponemos es el ampliar la busqueda de simuladores para poder realizar los laboratios virtuales, pues al no encontrarnos fisicamente con algunos componentes se nos hace mas complejo un correcto aprendizaje 

9.- BIBLIOGRAFÍA

Charles, A., & Matthew, S. (2006). Fundamentos de circuitos eléctricos. México, D.F.: McGraw-Hill/Interamericana Editores, S.A. de C.V.

GÓMEZ, A. J. (2009). Fundamentos de Circuitos. Bogotá: Ediciones Uniandes.

10.- ANEXOS

![](https://github.com/BriandaLema/Laboratorio1/blob/master/img/Calculo%20de%20intensidad%20y%20voltaje1.jpg)

![](https://github.com/BriandaLema/Laboratorio1/blob/master/img/Calculo%20de%20intensidad%20y%20voltaje2.jpg)

![](https://github.com/BriandaLema/Laboratorio1/blob/master/img/Calculo%20de%20intensidad%20y%20voltaje3.jpg)

![](https://github.com/BriandaLema/Laboratorio1/blob/master/img/C%C3%A1lculo%20LVK.jpg)

![](https://github.com/BriandaLema/Laboratorio1/blob/master/img/C%C3%A1lculo%20LCK.jpg)

![](https://github.com/BriandaLema/Laboratorio1/blob/master/img/C%C3%A1lculo%20LCK2.jpg)


10,1.- HOJAS TECNICAS

https://github.com/BriandaLema/Laboratorio1/tree/master/Hojas%20t%C3%A9cnicas



