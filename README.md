# INFORME-LABORATORIO-6

# 1) OBJETIVOS

OBJETIVO GENERAL:

- Comprobar el Teorema de Máxima Transferencia de Potencia mediante el uso de un simulador y análisis matemático.

OBJETIVOS ESPECÍFICOS:

- Explicar de qué se trata el Teorema de Máxima Transferencia de Potencia, para comprender el comportamiento del circuito que contiene una resistencia de carga de valor variable.

- Realizar una simulación en Tinkercad del Teorema de Máxima Transferencia de Potencia, para analizar el circuito mediante los valores mostrados en la simulación.

- Identificar los valores de corriente y voltaje en donde se da la Máxima Transferencia de potencia, para comprobar que el Teorema se cumpla.


# 2) Marco teorico

- El teorema de máxima transferencia de potencia establece que, dada una fuente, con una resistencia de fuente fijada de antemano, la resistencia de carga que maximiza la transferencia de potencia es aquella con un valor óhmico igual a la resistencia de fuente.
  
Se transfiere potencia máxima a una carga conectada a un circuito cuando la impedancia total es el complejo conjugado de la impedancia de salida del circuito. 
Donde las resistencias son iguales en magnitud y las reactancias también iguales en magnitud pero de signo opuesto. La impedancia de salida es efectivamente la impedancia equivalente de Thevenin vista desde las terminales de salida. 
- Cuando ZL es el complejo conjugado de Zsal, se transfiere potencia máxima desde el circuito hasta la carga con un factor de potencia de 1. En la figura  se muestra un circuito
equivalente con su carga e impedancia de salida.

![](https://github.com/spcueva1/INFORME-LABORATORIO-6/blob/adb81509e4e1ba409698da2181447ca593fa8f7b/Mac%20inf%20lab6/1.png)

Se transfiere potencia máxima a una carga cuando la impedancia de carga es el complejo conjugado de la impedancia del circuito de control.

La teoría se utiliza para calcular el valor de la resistencia de carga, que provoca que la potencia máxima se transfiera de la fuente a la carga. El teorema es válido para circuitos de CA y CC (punto a tener en cuenta: para los circuitos de CA, las resistencias se reemplazan por impedancia).

Pasos para resolver problemas relacionados con el teorema de transferencia de potencia máxima

Se siguen los pasos mencionados a continuación para resolver problemas de teoría de transferencia de potencia. Hay otras formas, pero seguir estos pasos conducirá a una ruta más eficiente.

Paso 1: Descubra la resistencia de carga del circuito. Ahora retírelo del circuito.
Paso 2: Calcule la resistencia equivalente de Thevenin del circuito desde el punto de vista de la rama de resistencia de carga en circuito abierto.
Paso 3: Ahora, como dice la teoría, la nueva resistencia de carga será la resistencia equivalente de Thevenin. Esta es la resistencia responsable de la máxima transferencia de potencia.
Paso 4: Entonces se deriva la potencia máxima. Viene como sigue.

PMAX V =TH2 / 4RTH

Mapa conceptual

![](https://github.com/spcueva1/INFORME-LABORATORIO-6/blob/adb81509e4e1ba409698da2181447ca593fa8f7b/Mac%20inf%20lab6/Mapa.jpg)




# 3) Explicacion de procedimiento


Resolver el siguente circuito: 

![](https://github.com/spcueva1/INFORME-LABORATORIO-6/blob/478fa16df2fa615b82dcfb09891983868746a8a0/lab%206.png)

Mida el voltaje y la corriente para cada valor de RL. Tambien Calcule las potencia consumida por RL, para cada valor dado.

Calculos:

Para la potencia:

P=I^2*RL

1) RL=220 Ω

I=15/(1200+220)=10,56mA

P=〖(10,56)〗^2*220=24,53mW

2) RL=470 Ω

I=15/(1200+470)=8,98mA

P=〖(8,98)〗^2*470=37,91mW

3) RL=680 Ω

I=15/(1200+680)=7,97mA

P=(7,97)^2*680=43,2mW

4) RL=820 Ω

I=15/(1200+820)=7,42mA

P=〖(7,42)〗^2*820=45,21mW

5) RL=1000 Ω

I=15/(1200+1000)=6,81mA

P=〖(6,81)〗^2*1000=46,48mW

6) RL=1500 Ω

I=15/(1200+1500)=5,55mA

P=〖(5,55)〗^2*1500=46,29mW

7) RL=1800 Ω

I=15/(1200+1800)=5mA

P=〖(5)〗^2*1800=45mW

8) RL=2200 Ω


I=15/(1200+2200)=4,41mA

P=〖(4,41)〗^2*2200=42,82mW

9) RL=3900 Ω

I=15/(1200+3900)=2,94mA

P=〖(2,94)〗^2*3900=33,7mW

10) RL=4700 Ω

I=15/(1200+4700)=2,54mA

P=〖(2,54)〗^2*4700=30,3mW


![](https://github.com/spcueva1/INFORME-LABORATORIO-6/blob/fdd06c6bf0870094cfc8a5c253b2db4ee4b2f938/calcl%20lab%206/1.png)

![](https://github.com/spcueva1/INFORME-LABORATORIO-6/blob/fdd06c6bf0870094cfc8a5c253b2db4ee4b2f938/calcl%20lab%206/2.png)

![](https://github.com/spcueva1/INFORME-LABORATORIO-6/blob/fdd06c6bf0870094cfc8a5c253b2db4ee4b2f938/calcl%20lab%206/3.png)


Simulacion en Tinkercard:

Imagen 1 simulador RL=220 Ω

![](https://github.com/spcueva1/INFORME-LABORATORIO-6/blob/fdd06c6bf0870094cfc8a5c253b2db4ee4b2f938/Mac%20inf%20lab6/220.jpeg)

Imagen 2 simulador RL=470 Ω

![](https://github.com/spcueva1/INFORME-LABORATORIO-6/blob/fdd06c6bf0870094cfc8a5c253b2db4ee4b2f938/Mac%20inf%20lab6/470.jpeg)

Imagen 3 simulador RL=680 Ω

![](https://github.com/spcueva1/INFORME-LABORATORIO-6/blob/fdd06c6bf0870094cfc8a5c253b2db4ee4b2f938/Mac%20inf%20lab6/680.jpeg)

Imagen 4 simulador RL=820 Ω

![](https://github.com/spcueva1/INFORME-LABORATORIO-6/blob/fdd06c6bf0870094cfc8a5c253b2db4ee4b2f938/Mac%20inf%20lab6/820.jpeg)

Imagen 5 simulador RL=1000 Ω

![](https://github.com/spcueva1/INFORME-LABORATORIO-6/blob/fdd06c6bf0870094cfc8a5c253b2db4ee4b2f938/Mac%20inf%20lab6/1000.jpeg)

Imagen 6 simulador RL=1500 Ω

![](https://github.com/spcueva1/INFORME-LABORATORIO-6/blob/fdd06c6bf0870094cfc8a5c253b2db4ee4b2f938/Mac%20inf%20lab6/1500.jpeg)

Imagen 7 simulador RL=1800 Ω

![](https://github.com/spcueva1/INFORME-LABORATORIO-6/blob/fdd06c6bf0870094cfc8a5c253b2db4ee4b2f938/Mac%20inf%20lab6/1800.jpeg)

Imagen 8 simulador RL=2200 Ω

![](https://github.com/spcueva1/INFORME-LABORATORIO-6/blob/fdd06c6bf0870094cfc8a5c253b2db4ee4b2f938/Mac%20inf%20lab6/2200.jpeg)

Imagen 9 simulador RL=3900 Ω

![](https://github.com/spcueva1/INFORME-LABORATORIO-6/blob/fdd06c6bf0870094cfc8a5c253b2db4ee4b2f938/Mac%20inf%20lab6/3900.jpeg)

Imagen 10 simulador RL=4700 Ω

![](https://github.com/spcueva1/INFORME-LABORATORIO-6/blob/fdd06c6bf0870094cfc8a5c253b2db4ee4b2f938/Mac%20inf%20lab6/4700.jpeg)


# 4) Respuesta a interrogantes y cálculo de error.

Completando la tabla se obtiene de la siguiente manera: 

![](https://github.com/spcueva1/INFORME-LABORATORIO-6/blob/fdd06c6bf0870094cfc8a5c253b2db4ee4b2f938/Mac%20inf%20lab6/Tabla.jpeg)



¿Se cumple el Teorema de la Máxima Transferencia de Potencia? Argumente surespuesta.


- Si se cumple puesto que una fuente de voltaje entrega la máxima transferencia de potencia a una resistencia de carga RL, cuando el valor de esta resistencia es igual a la resistencia interna de la fuente y como se observa la resitencia RL de 1kohm es la que mas se acerca a la resitencia RS 1.2kohm, y es con esta resistencia donde se obtiene la máxima transferencia de potencia. Incluyen que al momento de realizar una grafica podemos ver el pico donde tiene un maximo como lo dice la teoria.


¿Cuál fue la potencia máxima en RL?

0.04648 Watts


¿Para qué valor de RL se obtiene la MTP?

1000 Ω


# 5) Video




# 6) Conclusiones.

- Se logro comprobar el Teorema de Máxima Transferencia de Potencia mediante el uso de un simulador y análisis matemático como se indica anteriormen. 

- La teoría se utiliza para calcular el valor de la resistencia de carga, que provoca que la potencia máxima se transfiera de la fuente a la carga. El teorema es válido para circuitos de CA y CC, la mayoría de veces se utiliza para sistemas de seguridad o reglas dentro de la seguridad industrial.

- Se realizó la simulación en Tinkercad, con esto se utilizaron los valores mostrados en pantalla para realizar el análisis analítico del circuito utilizando las fórmulas que permiten obtener la potencia de un circuito.

- Los valores de corriente y voltaje que se identificaron permitieron comprobar el Teorema, ya que son valores en donde se obtuvo el valor máximo de potencia, comparando con los demás resultados obtenidos.

# 7) Bibliografia

- M. (2021b, abril 2). Teorema de superposición. MiElectrónicaFácil.com. Recuperado 27 de diciembre de 2021, de https://mielectronicafacil.com/analisis-de-circuitos/teorema-de-superposición/#pasos-del-teorema-de-superposición.

- Salazar, A. (2012). 3. Análisis de superposición 3.1. 35–62. http://wwwprof.uniandes.edu.co/~ant-sala/cursos/FDC/Contenidos/03_superposición.pdf
