# TAREA-9

## 1) Objetivos

### 1.1) Objetivo General

Analizar y comprender el funcionamiento de circuitos con decibles y el grafico de estas mediante el libro de principios de circuitos eléctricos, con el fin de realizar correctamente los ejercicios planteados.

### 1.2) Objetivos Específicos

- Determinar el concepto de circuitos RC pasabajas y  pasaaltas, con el fin de solucionar problemas.

- Identificar la relación entre voltajes e intensidades de circuitos RC

- Conocer las gráficas o la curva de Bode para el filtro de frecuencia y voltajes de entrada y salida.


## 2) Marco Teórico

### RESUMEN

CIRCUITOS RLC Y RESONANCIA

PARTE 1: CIRCUITOS EN SERIE

Como se sabe, la reactancia inductiva (XL) causa que la corriente total se retrase con respecto al voltaje aplicado. La reactancia capacitiva (XC) tiene el efecto opuesto: provoca que la corriente se adelante con respecto al voltaje. Por tanto, XL y XC tienden a contrarrestarse entre sí. Cuando son iguales, se eliminan y la reactancia total es de cero. En cualquier caso, la magnitud de la reactancia total en el circuito en serie es

La impedancia total del circuito RLC se establece en forma rectangular en la ecuación 17-2, y en forma polar en la ecuación

en serie típico la impedancia total se comporta como sigue: al empezar a una frecuencia muy baja, XC es alta, XL es baja, y el circuito es predominantemente capacitivo. Conforme se incrementa la frecuencia, XC disminuye y XL aumenta hasta que se alcanza un valor donde XC XL y las dos reactancias se eliminan, lo cual vuelve al circuito puramente resistivo.

La gráfica de XL es una línea recta y la gráfica de XC es una curva

En un circuito RLC en serie, la resonancia es una condición en la cual las reactancias capacitiva e inductiva son iguales en magnitud; por tanto, se eliminan entre sí y el resultado es una impedancia puramente resistiva

En condición resonante, XL XC y los términos j se eliminan; por tanto, la impedancia es puramente resistiva.


![resuemnn_9_1](https://user-images.githubusercontent.com/99141342/155485549-d38cac56-c827-425e-8fdd-c245c8b9a9a9.png)


![resuemnn_9_2](https://user-images.githubusercontent.com/99141342/155485566-b756c152-0062-45dc-a93e-d6f91e9cc8f0.png)



PARTE 2: CIRCUITOS EN PARALELO

Los conceptos de conductancia (G), susceptancia capacitiva (BC), susceptancia inductiva (BL), y admitancia (Y) fueron analizados en los capítulos 15 y 16. Las fórmulas fasoriales se vuelven a establecer aquí.


![resuemnn_9_3](https://user-images.githubusercontent.com/99141342/155485584-a37c7383-6593-4d4b-90c4-ee51bc252199.png)



Relaciones de corriente En un circuito RLC dispuesto en paralelo, las corrientes que circulan por las ramas capacitiva e inductiva siempre están desfasadas en 180° entre sí (omitiendo cualquier resistencia de bobina). Como IC e IL se suman algebraicamente, la corriente total es en realidad la diferencia de sus magnitudes. Por tanto, la corriente total que entra a las ramas de L y C en paralelo siempre es menor que la corriente de rama individual más grande.

Condición para resonancia ideal en paralelo De manera ideal, la resonancia en paralelo ocurre cuando XC XL. La frecuencia a la cual ocurre la resonancia se llama frecuencia resonante, exactamente como en el caso en serie. Cuando XC XL, las corrientes de rama, IC e IL, son iguales en magnitud, y, desde luego, siempre están desfasadas entre sí en 180°. Por tanto, las dos corrientes se cancelan y la corriente total es de cero.


![resuemnn_9_4](https://user-images.githubusercontent.com/99141342/155485609-15386451-c3cf-4c1c-88c3-e4e627cc0b34.png)



PARTE 3: CIRCUITOS EN SERIE-PARALELO
Conversión de en serie-paralelo a paralelo La configuración particular en serie-paralelo mostrada en la figura 17-36 es importante porque representa un circuito que tiene ramas L y C en paralelo, con la resistencia de devanado de la bobina tomada en cuenta como resistencia en serie en la rama L.


![resuemnn_9_5](https://user-images.githubusercontent.com/99141342/155485622-bbaebc1a-3cd3-4b96-ae7d-a18ee95355b7.png)


Es conveniente ver al circuito en serie-paralelo de la figura 17-36 en una forma equivalente en paralelo.


![resuemnn_9_6](https://user-images.githubusercontent.com/99141342/155485653-7cdd3731-4155-41ee-ade8-233f1fe22959.png)



Las fórmulas siguientes proporcionan la inductancia equivalente, Leq, y la resistencia en paralelo equivalente, Rp(eq).


![resuemnn_9_7](https://user-images.githubusercontent.com/99141342/155485751-96ce1083-a220-469d-b4f1-f31d81b04322.png)



donde Q es el factor de calidad de la bobina, XL/RW. Las derivaciones de estas fórmulas son bastante complicadas, y por tanto no se muestran aquí. Advierta en las ecuaciones que, con Q 10, el valor de Leq es aproximadamente el mismo que el valor original de L. Por ejemplo, si L 10 mH y Q 10, entonces:


![resuemnn_9_8](https://user-images.githubusercontent.com/99141342/155485770-1d93218d-c2c9-43fa-9971-aa9db8b008bb.png)



La equivalencia de los circuitos significa que, a una frecuencia dada, cuando se aplica el mismo valor de voltaje a ambos circuitos, la misma corriente total fluye en ambos circuitos y los ángulos de fase son los mismos. De manera básica, un circuito equivalente sólo propicia que el análisis de circuitos sea más conveniente.


FILTROS PASIVOS

Filtros pasabajas

Un diagrama de bloques y una curva de respuesta general para un filtro pasabajas. El intervalo de frecuencias pasadas por un filtro dentro de límites especificados se llama banda de paso del filtro. El punto considerado como extremo superior del intervalo de la banda de paso está en la frecuencia crítica, fc, como se ilustra en la figura 18-1(b). La frecuencia crítica (fc) es la frecuencia a la cual el voltaje de salida del filtro es un 70.7% del voltaje máximo. La frecuencia crítica del filtro se conoce también como frecuencia de corte, frecuencia de ruptura, o frecuencia de = 3 dB porque el voltaje de salida se encuentra a 3 dB por debajo de su valor máximo en esta frecuencia. El término dB (decibel) es una unidad utilizada comúnmente en mediciones con filtros.


![resuemnn_9_9](https://user-images.githubusercontent.com/99141342/155485802-ecc0db35-d1cd-49f5-a56b-4be994ac67c7.png)



Decibeles La base de la unidad decibel se deriva de la respuesta logarítmica que el oído humano presenta a la intensidad del sonido. El decibel es una medida logarítmica de la relación de una potencia a otra y de un voltaje a otro, la cual puede ser utilizada para expresar la relación de entrada a salida de un filtro.

Filtros pasaaltas

A un diagrama de bloques y una curva de respuesta general para un filtro pasaaltas. La frecuencia considerada como el extremo inferior de la banda de paso se llama frecuencia crítica. Al igual que en el filtro pasabajas, es la frecuencia a la cual la salida es el 70.7% de la frecuencia máxima, como indica la figura.


![resuemnn_9_10](https://user-images.githubusercontent.com/99141342/155485829-56bead01-f67e-4717-92f7-82006f9781a0.png)



Filtro RC pasaaltas: se muestra un filtro RC pasaaltas. Advierta que el voltaje de salida se toma a través del resistor.


![resuemnn_9_11](https://user-images.githubusercontent.com/99141342/155485850-73d77e98-056a-4e86-aa07-d421d61af38b.png)



Filtro RL pasaaltas: un filtro RL básico pasaaltas. Observe que la salida se toma a través del inductor. Cuando la frecuencia de salida alcanza su valor crítico, XL R, y el voltaje de salida es de 0.707Vent. Conforme la frecuencia se incrementa por encima de fc, XL aumenta y, por consiguiente


![resuemnn_9_12](https://user-images.githubusercontent.com/99141342/155485867-1593ea9b-f9ac-40a9-b510-d6802399834f.png)



Fitros pasabanda


El ancho de banda de un filtro pasabanda es el intervalo de frecuencias dentro del cual la corriente, y por tanto el voltaje de salida, es igual o mayor que el 70.7% de su valor en la frecuencia de resonancia. Como se sabe, el ancho de banda a menudo se abrevia AB y se calcula como:


AB = fc2 – fc1


 donde fc1 es la frecuencia de corte baja y fc2 es la frecuencia de corte alta. La figura 18-19 muestra una curva típica de respuesta pasabanda.


![resuemnn_9_13](https://user-images.githubusercontent.com/99141342/155485897-501d8e07-18f3-4a65-8951-e68a776806d6.png)



Filtros rechazabanda


Se muestra una curva general de respuesta de un filtro rechazabanda


![resuemnn_9_14](https://user-images.githubusercontent.com/99141342/155485912-fe7f90a6-f0e3-44cf-9aac-acee32e842d3.png)



Filtro pasabajas/pasaaltas: Se puede formar un filtro rechazabanda con un filtro pasabajas y un filtro pasaaltas


![resuemnn_9_15](https://user-images.githubusercontent.com/99141342/155485926-baefddc8-68d2-4483-8969-48a4ace8631e.png)



Filtro rechazabanda resonante en serie

circuito resonante dispuesto en serie en una configuración rechazabanda. Básicamente, esta configuración funciona como sigue: en la frecuencia resonante, la impedancia es mínima y, por consiguiente, el voltaje de salida es mínimo. La mayor parte del voltaje de entrada disminuye a través de R. En frecuencias sobre y bajo la frecuencia de resonancia la impedancia se incrementa, lo cual provoca más voltaje en la salida.


![resuemnn_9_16](https://user-images.githubusercontent.com/99141342/155485951-a955cd09-aa47-4a97-8d53-f7a69497ef42.png)

### MAPA CONCEPTUAL

![MAPA](https://user-images.githubusercontent.com/99141342/155528647-127e726e-21b5-40a1-bd41-7ad039eef18b.jpg)


## 3) Explicación y Resolución de Ejercicios

###  CIRCUITOS RCL Y RESONANCIA

1.	Cierto circuito RLC en serie tiene los siguientes valores: R 10 Ω, C=0.047 mF, y L=5 mH. Determine la impedancia en forma polar. ¿Cuál es la reactancia neta? La frecuencia de la fuente es de 5 kHz.


![tarea_9_1](https://user-images.githubusercontent.com/99141342/155474515-af881091-4b1d-4be0-8d2c-fcacae2fea89.png)


3. Si en la figura 17-59 la frecuencia del voltaje de fuente se duplica a partir del valor que producen las reactancias indicadas, ¿cómo cambia la magnitud de la impedancia?

![tarea_9_2](https://user-images.githubusercontent.com/99141342/155474529-47d8349f-bcb5-4f10-8055-e32c3d7d9a76.png)

![Tarea_9_3](https://user-images.githubusercontent.com/99141342/155474544-b3724cc4-29c2-4b19-85cf-d8a2010a6287.png)


La impedancia se incrementa a 150 Ω


5. Para el circuito de la figura 17-59, determine Itot, VR, VL y VC en forma polar

![Tarea_9_4](https://user-images.githubusercontent.com/99141342/155474575-7a573c58-aa7b-405b-a588-cba633365560.png)



7. Analice el circuito de la figura 17-60 para determinar lo siguiente (f 25 kHz):

A) Itot

B) Preal

C) Pr

D) Pa

![Tarea_9_5](https://user-images.githubusercontent.com/99141342/155474601-a98976da-64de-44d4-ac01-51e54ea7e69c.png)


![Tarea_9_6](https://user-images.githubusercontent.com/99141342/155474620-32013f38-63a5-4623-932c-32b5225e294f.png)



9. Para el circuito de la figura 17-61, ¿cuál es el voltaje a través de R en condición de resonancia?

![Tarea_9_7](https://user-images.githubusercontent.com/99141342/155474631-a43c16c0-ded8-4e60-a2fb-9d02948a42eb.png)

![Tarea_9_8](https://user-images.githubusercontent.com/99141342/155474648-7e65e907-c91c-4981-9348-e259ab9428d1.png)



11. Cierto circuito resonante dispuesto en serie tiene una corriente mínima de 50 mA y un VL de 100 V. El voltaje aplicado es de 10 V. ¿Cuál es el valor de Z? ¿Cuáles los valores de XL y XC?

![Tarea_9_9](https://user-images.githubusercontent.com/99141342/155474687-3fe49b74-1382-430b-b812-189e751546a6.png)



13. Para la figura 17-62, ¿cuál es el valor de la corriente en los puntos de potencia media?

![Tarea_9_10](https://user-images.githubusercontent.com/99141342/155474695-12e47f6a-94ae-4877-95fe-0d88b8da958b.png)


corriente = 500 Ma


15. Diseñe un circuito en el cual las siguientes frecuencias resonantes en serie se puedan seleccionar con un conmutador: (a) 500 kHz (b) 1000 kHz (c) 1500 kHz (d) 2000 kHz

![Tarea_9_11](https://user-images.githubusercontent.com/99141342/155474714-30ea4bbb-365c-40fa-add4-f81215b274fd.png)



17. ¿Es capacitivo o inductivo el circuito de la figura 17-63? Explique su respuesta.

![Tarea_9_12](https://user-images.githubusercontent.com/99141342/155474734-f4f6c270-c636-4d0e-84b5-1b0f74927afa.png)


El ángulo de fase de -4.43° indica un circuito levemente capacitivo.


19. Para el circuito de la figura 17-63, determine todas las corrientes y los voltajes en forma polar.

![Tarea_9_13](https://user-images.githubusercontent.com/99141342/155474749-2924502c-8c60-4bc4-9438-5d52969f64d9.png)



21. Cambie la frecuencia a 100 kHz en la figura 17-63 y repita el problema 19.

![Tarea_9_14](https://user-images.githubusercontent.com/99141342/155474763-84b1035f-dafd-479d-8301-2747be0d71c0.png)



23. Determine Z en condición de resonancia y fr para el circuito tanque de la figura 17-64.

![Tarea_9_15](https://user-images.githubusercontent.com/99141342/155474790-2b1aad92-a9fe-41d2-9903-471105cbf4e2.png)

![Tarea_9_16](https://user-images.githubusercontent.com/99141342/155474799-b8cca613-b435-4165-b5c1-aa647358a401.png)



25. Determine Preal, Pr y Pa en el circuito de la figura 17-64 en condición de resonancia.


Pr = 0 VAR

Pa = 7,45µVA

Preal = 538mW



27. Para cada circuito de la figura 17-65, determine el ángulo de fase entre el voltaje de fuente y la corriente total. 

![1](https://user-images.githubusercontent.com/99141342/155475107-28f5fa5e-132c-4a40-aa2d-8fb2f7c2d25e.jpeg)

![27a](https://user-images.githubusercontent.com/99141342/155475130-a1ed7ac4-6c0a-48b5-9343-e371cbe74f14.jpeg)

![27b](https://user-images.githubusercontent.com/99141342/155475146-be0b96f9-27fb-4024-bead-5471030fae9d.jpeg)


29. Convierta el circuito de la figura 17-66 a una forma equivalente dispuesta en serie. 

![FIGURA 2](https://user-images.githubusercontent.com/99141342/155475287-d9c2a7fd-70b1-4f7b-ae65-a137e110aeef.PNG)

![29](https://user-images.githubusercontent.com/99141342/155475300-efae4800-c8c2-4896-9610-41a66fb70b35.jpeg)


31. En la figura 17-67, ¿cuál es el ángulo de fase entre I2 y el voltaje de fuente?

![FIGURA 3](https://user-images.githubusercontent.com/99141342/155475314-c3177a8e-09ee-40aa-be6c-e6730f27c400.PNG)

![31](https://user-images.githubusercontent.com/99141342/155475328-136c2736-05d5-432c-9480-a49e5e796c0b.jpeg)


33. Determine la corriente a través de cada componente mostrado en la figura 17-68. Encuentre el voltaje
entre las terminales de cada componente.

![FIGURA 4](https://user-images.githubusercontent.com/99141342/155475367-2bd341fb-2a0d-49e7-a280-12950fc3dc56.PNG)

![33](https://user-images.githubusercontent.com/99141342/155475381-e864c34d-df22-4600-97e0-0bada44cbfd1.jpeg)


35. Si el valor de C es de 0.22 mF, ¿cuál es la corriente a través de un resistor de 100 Æ conectado de a a b
en la figura 17-69?

![FIGURA 5](https://user-images.githubusercontent.com/99141342/155475481-3c685d9b-af6d-4636-b239-f476997e9f60.PNG)

![35](https://user-images.githubusercontent.com/99141342/155475498-da949e36-3453-45a3-b8aa-6696aee6754a.jpeg)



37. Determine las frecuencias resonantes y el voltaje de salida en cada frecuencia mostrada en la figura 17-70.

![FIGURA 6](https://user-images.githubusercontent.com/99141342/155475516-652397b8-178c-4cb7-854a-e01b972fbd3c.PNG)

![37](https://user-images.githubusercontent.com/99141342/155475582-f3192fd7-a630-45a6-a05c-6c6f20e77b06.jpeg)


39. En condición de resonancia, XL =2 ohm y RW = 25 ohm en un circuito RLC en paralelo. La frecuencia resonante
es de 5 kHz. Determine el ancho de banda.

![39](https://user-images.githubusercontent.com/99141342/155475601-9a8a0c20-b908-49e6-a3b5-fc4ba27c65c7.jpeg)


41. En cierto circuito RLC, la potencia en condición de resonancia es de 2.75 W. ¿Cuál es la potencia a la
frecuencia crítica baja?

![41](https://user-images.githubusercontent.com/99141342/155475614-a4688311-3588-4714-bbc3-fa131095a976.jpeg)


43. Cierto circuito resonante en paralelo tiene un factor Q de 50 y un AB de 400 Hz. Si Q se duplica, ¿cuál
es el ancho de banda a la misma fr?


![43](https://user-images.githubusercontent.com/99141342/155475657-b2e319dc-f872-422a-8ee8-25cf0c2d7461.jpeg)


FILTROS 

1. En cierto filtro pasabajas, XC =500 ohm y R = 2.2 kohm. ¿Cuál es el voltaje de salida (Vsal) cuando la entrada
es de 10 V rms?

### FILTROS PASIVOS

1. En cierto filtro pasabajas, XC =500 ohm y R = 2.2 kohm. ¿Cuál es el voltaje de salida (Vsal) cuando la entrada
es de 10 V rms?

![1](https://user-images.githubusercontent.com/99141342/155464125-13946b43-dd99-4179-a780-347667b130e3.jpeg)


3. Determine el voltaje de salida (Vsal) de cada filtro mostrado en la figura 18-38 a la frecuencia especificada cuando Vent  10 V.

![axelejer_3](https://user-images.githubusercontent.com/99141342/155522846-e009577d-3b1c-4f57-8f7a-504264ffa446.png)


a)
Vsal=(R/sqrt(R^2+R^2))Vent

Vsal=(100/sqrt(100^2+100^2))* 10

Vsal=7,07 V


b)
Vsal=(R/sqrt(R^2+R^2))Vent

Vsal=(47/sqrt(47^2+47^2))* 10

Vsal=7,07 V


c)
Vsal=(1/2pi*1/2pi*(5/0.33)*330)*10
Vsal=0.4591 V


d)
Vsal=(1/2pi*1/2pi*(0.08/0.01)*10)*10

Vsal=8 V


5. Para el filtro de la figura 18-39, calcule el valor de C requerido para cada una de las siguientes frecuencias críticas: 


(a) 60 Hz 

Fc=1/2pi*R*C

C=1/2pi*R*Fc

C=1/2pi*220*60HZ

C=12 uF


(b) 500 Hz 

Fc=1/2pi*R*C

C=1/2pi*R*Fc

C=1/2pi*220*500HZ

C=1,446 uF


(c) 1 kHz 

Fc=1/2pi*R*C

C=1/2pi*R*Fc

C=1/2pi*220*1kHZ

C= 0,723uF


(d) 5 kHz

Fc=1/2pi*R*C

C=1/2pi*R*Fc

C=1/2pi*220*5kHZ

C=0.114 uF


7. Trace una curva de Bode para cada una de las partes del problema 5.

![axelejer_7](https://user-images.githubusercontent.com/99141342/155522893-119f4623-b362-429b-ab5e-fc259b963f41.png)

![axelejer_7_1](https://user-images.githubusercontent.com/99141342/155522909-12fd12bd-cea8-4e3b-92bc-bad47d07c856.png)

![axelejer_7_2](https://user-images.githubusercontent.com/99141342/155522918-2176f729-0bce-481d-965b-f30dbc3e1b61.png)

![axelejer_7_3](https://user-images.githubusercontent.com/99141342/155522932-26976ad7-a3af-42c1-a547-88916cb7d2e9.png)




9. El voltaje de entrada a un filtro RC pasabajas es de 8 V rms. Determine el voltaje de salida a los siguientes niveles de dB:

a)	-1dB

Vsal/Vent=-1dB

Vsal= 8V


b)	-3dB

Vsal/Vent=-3dB

Vsal= 24V


c)	-6dB

Vsal/Vent=-6dB

Vsal= 48V


d)	-20dB

Vsal/Vent=-20dB

Vsal= 160v


11. En un filtro pasaaltas, XC  500 Ω y R 2.2 kΩ. ¿Cuál es el voltaje de salida (Vsal) cuando Vent 10 V rms?

Vsal=(R/(sqrt(R^2+Xc^2)))*Vent

Vsal=(2.2k/ sqrt(2.2^2+500^2)))*10)

Vsal=9,75V


13. Determine el voltaje de salida de cada filtro mostrado en la figura 18-41 a la frecuencia especificada cuando Vent  10 V.

![axelejer_13](https://user-images.githubusercontent.com/99141342/155522985-632ae158-54f8-48fa-9b9d-d7f0ae0c424d.png)


a)
Vsal=(R/(sqrt(R^2+Xc^2)))*Vent

Vsal=(100/ sqrt(100^2+10^2)))*10)

Vsal=9,95V


b)
Vsal=(R/(sqrt(R^2+Xc^2)))*Vent

Vsal=(47/ sqrt(47^2+4.7^2)))*10)

Vsal=9.95V


c)
Vsal=(R/(sqrt(R^2+Xc^2)))*Vent

Vsal=(330/ sqrt(330^2+330^2)))*10)

Vsal=7,07V


d)
Vsal=(R/(sqrt(R^2+Xc^2)))*Vent

Vsal=(10/ sqrt(10^2+10^2)))*10)

Vsal=7,07V


15. Trace la curva de Bode para cada filtro mostrado en la figura 18-41

![axelejer_15_1](https://user-images.githubusercontent.com/99141342/155523019-f4b58ec4-6179-4326-8797-4ff8e191b869.png)

![axelejer_15_2](https://user-images.githubusercontent.com/99141342/155523031-213a1595-c4c2-4535-97d5-00537ad94d83.png)

![axelejer_15_3](https://user-images.githubusercontent.com/99141342/155523037-ed7bf6d7-9895-432a-8cac-ccf91ff694af.png)

![axelejer_15_4](https://user-images.githubusercontent.com/99141342/155523050-828f1737-04e8-414f-aa79-f79c6812d986.png)


17. Determine la frecuencia central para cada filtro de la figura 18-43.

![axelejer_17](https://user-images.githubusercontent.com/99141342/155523081-7a0d2167-5a62-4e88-a5d1-0697376fad32.png)


a)	f0 = 1/2pisqrt(L*C)

f0 = 1/2pisqrt(12*0,01)=45,94 kHz


b)
f0 = 1/2pisqrt(L*C)

f0 = 1/2pisqrt(2*0,022)=75,87 kHz


19. ¿Cuáles son las frecuencias críticas alta y baja para cada filtro de la figura 18-43? Suponga que la respuesta es simétrica con respecto a f0

La alta en a es 45 kHz y la baja es -45kHz por simetría y de igual manera en b, la alta es 75kHz y la baja es -75kHz


21. Si la resistencia de devanado de las bobinas que aparecen en la figura 18-44 es de 4 Æ, ¿cuál es el voltaje de salida en condición de resonancia cuando Vent  120 V?

![axelejer_21](https://user-images.githubusercontent.com/99141342/155523149-ea2e7c9d-b1bb-484d-af3a-c6d18fa14d26.png)


a)
F0=sqrt(1-R^2*C/L)/2piSqrt(LC)

F0= sqrt(1-680^2*10/1)/2piSqrt(1*10)

F0=108 Hz

Q=2piF0*L/Rw=2pi*108*1/4=169,64


b)
F0=sqrt(1-R^2*C/L)/2piSqrt(LC)

F0= sqrt(1-1000^2*25/2,5)/2piSqrt(2.5*25)

F0=63,66 Hz

Q=2piF0*L/Rw=2pi*63,66*2.5/4=249,99


23. Diseñe un filtro pasabanda utilizando un circuito resonante paralelo que satisfaga las siguientes especificaciones: AB  500 Hz; Q  40; e IC(máx)  20 mA, VC(máx)  2.5 V.


25. Para cada filtro de la figura 18-47, determine la frecuencia central de la banda de rechazo.

![axelejer_25](https://user-images.githubusercontent.com/99141342/155523210-e6772e9c-de04-4164-be4d-aca97a3e604a.png)


F0=sqrt(1-R^2*C/L)/2piSqrt(LC)

F0= sqrt(1-1000^2*6.8/0,5)/2piSqrt(0.5*6,8)

F0=318Hz

F0=sqrt(1-R^2*C/L)/2piSqrt(LC)

F0= sqrt(1-2200^2*47/10)/2piSqrt(10*47)

F0=10,21Hz


27. Determine los valores de L1 y L2 en la figura 18-48 para dejar pasar una señal con frecuencia de 1200kHz y rechazar una señal con frecuencia de 456 kHz

![axelejer_27](https://user-images.githubusercontent.com/99141342/155523231-c30f5aee-1c81-4ee2-862f-58c105f5ced6.png)


## 4) Video

https://youtu.be/QMak6wczMI8

## 5) Conclusiones

- Un filtro pasa bajas es para evitar el vaso de una frecuencia indeseada, por lo cual se descarta frecuencias que no se necesitan, por lo cual este compuesto de una resistencia y un capacitador.

- El voltaje y la corriente se relacionan mediante la impedancia total del circuito, ya que este define el desfase del uno con respecto del otro.

-  La curva de Bode sirvió para representar la respuesta de un circuito en una frecuencia determinada.



## 6) Bibliografía

Circuito RLC en paralelo. Fórmulas y diagrama vectorial. Ejercicios. (2021, 26 noviembre). Clases de Matemáticas Online. https://ekuatio.com/circuito-rlc-en-paralelo-en-corriente-alterna-formulas-y-ejercicios-resueltos/#Circuito_en_paralelo_RLC

Floyd, T. (2007). Circuitos RCL y resonancia. En LM Cruz Castillo (Ed.), Principios de Circuitos Eléctricos (VIII ed., pp. 406-465). Pearson Educación.

Floyd, T. (2007). Filtros pasivos. En LM Cruz Castillo (Ed.), Principios de Circuitos Eléctricos (VIII ed., pp. 406-465). Pearson Educación.
