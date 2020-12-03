# Ondas electromagneticas 
 

estas ondas no necesitan un medio material para propagarse, pueden propagarse en el vacío y surgen de la interacción entre electricidad y magnetismo como veremos más adelante. Son ejemplos de estas ondas las ondas de radio, de TV, microondas, radiación infrarroja, visible o ultravioleta; Rayos X y gamma.

!["./OEM.png"](./OEM.png)

Una OEM puede propagarse en el vacío (a la velocidad de la luz: c = 300,000 km/s) sin necesidad de que exista un medio físico como el aire o el agua para el transporte de energía. Las OEM son tridimensionales (por su número de direcciones de propagación) y transversales.

La idea principal es que si se hace oscilar cargas eléctricas entre los extremos de una antena, se generan un campo eléctrico (E) y un campo magnético (B), que interactúan entre sí. Las OEM son el resultado de la interacción de estos dos campos.

Las OEM son una forma de transportar señales por un medio como ser el aire o por el vacío, de aquí su gran importancia. Se puede emitir una señal desde un transmisor (donde se genera la onda), enviarla hacia una antena transmisora, propagar la onda generada por el aire hacia una antena receptora, en la antena receptora se recibe la onda y se convierte en una señal eléctrica hacia un receptor (donde se recupera la onda). Esta onda contiene información que una vez recibida por el receptor, se puede procesar esa señal y obtener la información que se envió.

Como sabemos, por el aire viajan muchas ondas, ¿Cómo es que las diferenciamos? ¿Cómo es que, de todas las ondas que viajan por el aire la antena receptora distingue la OEM que contiene la información transmitida? Es aquí donde juega el papel más importante una de las características de las ondas: su frecuencia, es esta la característica que permite distinguir las OEM unas de otras.



# Elementos activos y pasivos de antenas de transmisión:

El elemento activo mas importante es el dipolo,
sobre el la radiación electromagnética incidente induce la fuerza electromotriz, que hará circular 
corrientes variables sobre el circuito de radiotelevisión


!["./antena.webp"](./antena.webp)

el dipolo varia la longitud dependiendo de la frecuencia que se desean captar.

Idealmente, la anchura del dipolo debría coincidir con la mitad de la longitud de onda de estas frecuencias λ/2.


# Caja de conexión.
Caja donde el dipolo está conectado con el cable conductor del circuito de RTV, el cable coaxial. La conexión se realiza a través del "balum", circuito impreso cuya función es la de adaptar la impedancia de la antena, de alrededor de 300Ω, a la impedancia característica de un circuito de televisión, que es 75 Ω.

!["./antena.webp"](./caja_coneccion.webp)

# Emparrillado reflector.
Es un componente pasivo, colocado detrás del dipolo, a 1/4 de longitud de onda aproximadamente, cuya misión principal es la de rechazar señales traseras procedentes de rebotes o de otros repetidores. Además contribuye a aumentar la ganancia de global de la antena.

Tienen una anchura de entre un 3% y un 10% superior a la del dipolo.


# Emparrillado director.
Es un componente pasivo, colocado delante del dipolo, a 1/4 de longitud de onda aproximadamente, cuya misión principal es la de concentrar sobre el dipolo las ondas electromagnéticas incidentes. De esta manera se consigue aumentar la ganancia global de la antena y aumentar su directividad.

Son más cortos que el dipolo y su longitud va disminuyendo según su alejamiento al dipolo o radiador



# Caracteristicas de las antenas:

## Directividad:

Es la capacidad de una antena de absorber las radiaciones incidentes en una determinada dirección del espacio, emitidas desde el repetidor al cual se ha orientado.

" Una alta directividad reduce la captación de señales interferentes y, a su vez, complica el "apuntamiento" de la antena. "

!["Directividad"](./ICTV04_CONT_R151_pic067_mini.jpg)

Esta característica define la capacidad de una antena para recibir la señal procedente de una dirección determinada (perpendicular al dipolo) con un valor de máxima ganancia.

La directividad está determinada por otras dos características de las antenas: **El ancho de haz y la relación delante-atrás.**


## Ancho de haz.

Es el ángulo formado por los dos ejes imaginarios de unión de la antena con los puntos donde la ganancia ha disminuido 3 dB respecto a la ganancia máxima, teniendo como bisectriz el eje de máxima ganancia.

!["Ancho de haz"](./ICTV04_CONT_R152_pic068_mini.jpg)

Este ángulo define la zona de radiación de la antena donde la captación de la señal es la adecuada, entre el 70% y el 100% de la ganancia máxima. El ángulo de recepción puede ser horizontal y vertical, identificándose como ancho de haz horizontal y ancho de haz vertical.


## Relación delanteatrás (D/A).

Es la relación entre la ganancia de la antena en la dirección máxima de radiación (lóbulo principal) y la ganancia de la antena en cualquier otra dirección entre 90º y 270º de la dirección de máxima captación.

!["ICTV04_CONT_R153_pic069_mini"](./ICTV04_CONT_R153_pic069_mini.jpg)

Los fabricantes suelen suministrar este dato respecto a 180º (por detrás) del lóbulo principal.

Una relación delante-atrás grande permite evitar interferencias de repetidores traseros que emitan señales en los mismos canales que los captados por el lóbulo principal de la antena.

## Ganancia:

Es la relación entre la potencia captada por la antena conectada a un circuito de carga y la potencia captada por una antena llamada de referencia o patrón, denominada dipolo elemental, conectada al mismo circuito.

También se puede definir como la relación entre la tensión máxima captada por la antena y la tensión máxima captada por una antena patrón. Este parámetro se puede calcular mediante la expresión:

!["formula"](./formula.jpg)

La ganancia se expresa en dB.

!["formula"](./ganancia.jpg)

## Ancho de banda

Es el margen de frecuencia dentro del cual la antena mantiene sus características de ganancia, directividad, etc.

También se puede definir como el número de canales que es capaz de captar manteniendo sus niveles de ganancia.

Las casas comerciales sueles especificar el ancho de banda de una antena mediante curvas características.

!["ancho de banda"](./ICTV04_CONT_R157_pic073_mini.jpg)

En la gráfica se refleja la ganancia que tiene la antena para la gama de frecuencias en la que puede trabajar, considerando como ancho de banda efectivo aquel en el que la ganancia de la antena disminuye como máximo en 3 dB, desde el valor de ganancia más alto indicado.

## Relación de onda estacionaria (ROE)

Es una medida que expresa el grado de adaptación entre la antena y la impedancia del propio circuito.

La ROE se mejora al colocar el "balum", circuito adaptativo para conseguir una impedancia de 75 Ω de salida, en la caja de conexiones de la antena. De esta manera se consigue una buena adaptación de impedancias.

Si la adaptación de impedancias fuese perfecta, el valor de ROE sería igual a 1, e indicaría que no existen ondas estacionarias o reflejadas, aunque se tiene como valores normales de ROE los comprendidos entre 1,5 y 2,5.

Cuando la ROE es superior a 1 y hay una desadaptación de impedancias, la energía inducida en la antena no es absorbida en su totalidad por el circuito de RTV, originando un "rebote" de onda inducida. Se produce entonces una oposición mayor al paso de la corriente, provocando un descenso del nivel de la señal.

!["ICTV04_CONT_R158_pic074_mini"](./ICTV04_CONT_R158_pic074_mini.jpg)


## Antenas terrestres de televisión

Son antenas utilizadas para la captación de señales de televisión emitidas por repetidores terrestres.

Las antenas más empleadas para este servicio son las denominadas antenas Yagi. Estas antenas se ajustan a la descripción de la composición realizadas en el apartado anterior.

Básicamente están constituidas por un dipolo, un emparrillado director en la parte delantera que concentra las señales incidentes en el dipolo, un emparrillado reflector trasero para rechazar señales interferentes y la caja de conexiones.

Como ya se ha especificado, las dimensiones del dipolo, y por lo tanto de la antena, dependen de la frecuencia que se desea recibir. A mayor frecuencia, menor es la longitud de onda y también es menor la longitud del dipolo.

![antena](./antena.jpg).

En la actualidad las emisiones digitales de televisión son todas ellas sobre la banda UHF. La elección de las antenas receptoras de estos servicios es una tarea no trivial, se puede decir que la calidad de la instalación depende tanto de su elección como de la ubicación de estas.

Como contrapartida, la señal digital es una transmisión de umbral, es decir, por debajo de un nivel determinado se deja de recibir el servicio. La ganancia y directividad de la antena deben garantizar una correcta recepción en condiciones marginales.

Las antenas de señales televisión, tienen una ancho de banda amplío, toda la banda UHF generalmente, ya que, como se ha dicho, es aquí donde se concentran este tipo de emisiones.

Las ganancias están en torno a 9 -19 dB, en función de la configuración, teniendo una curva progresiva ascendente, desde valores mínimos a máximos, conforme aumentan las frecuencias de la banda recepcionada.

## Antenas logarítmicas

En este tipo de antenas el emparrillado director lo forman una serie de dipolos de anchura variable, cada uno en resonancia con un canal de TV.

![ICTV04_CONT_R163_pic080_mini](./ICTV04_CONT_R163_pic080_mini.jpg)

Una antena logarítmica periódica es una antena de banda ancha, con varios elementos activos unidireccionales, cuyas distancias mutuas y frecuencia de resonancia se hallan en progresión geométrica, capaz de recepcionar señales de TV en la banda VHF y UHF y señales de radio FM.

El dipolo activo receptor cambia continuamente dependiendo de la frecuencia, con frecuencias bajas son los elementos más largos los resonantes, y el resto de los elementos actúan como directores. En las frecuencias altas, son los elementos más cortos los que recpecionan y los otros elementos (más largos) actúan como directores.

La ganancia de este tipo de antenas varían entre los 8,5 y 10 dB.

## Antenas panel

Las antenas panel se diseñan para aquellos casos en que se recepcione señal desde varios repetidores y en direcciones cercanas.
![ICTV04_CONT_R166_pic083_mini](./ICTV04_CONT_R166_pic083_mini.gif)

En estos casos la directividad de la instalación receptora no es un parámetro importante, Por lo que no habrá rechazo lateral selectivo de señales rebotadas e interferentes.

Este tipo de antenas están formadas por un número par de dipolos (2 o 4) y un panel reflector. Las recepciones de los dipolos se suman consiguiendo ganancias de aproximadamente 14 dB.

Estas antenas poseen un ancho de banda grande, pudiendo recepcionar la banda UHF completa

## Antenas de elevada ganancia

Son antenas de gran longitud donde la configuración de los emparrillados directores se ha modificado, con una estructura en "V" disponiendo de dos o más parrillas, de tal forma que se consigue aumentar la ganancia final.

![ICTV04_CONT_R169_pic085_mini](./ICTV04_CONT_R169_pic085_mini.jpg)

Son antenas especialmente indicadas para la recepción de TV digital terrestre TDT, pues además de la ganancia conseguida tienen una característica de directividad muy alta, lo que estrecha el haz de recepción permitiendo rechazar señales laterales indeseadas.

Su ancho de banda depende del tamaño de dipolo, pero generalmente están configuradas para la recepción con ganancias, progresivamente más elevadas, para frecuencias altas de la banda UHF.

## Antenas terrestres de radio

Son antenas utilizadas para la captación de señales de radio, analógicas FM o digitales DAB (Digital Audio Broadcasting), emitidas por emisores terrestres.

## Radio analógica FM:

Es un servicio diseñado para la recepción móvil, con potencias de transmisión elevadas, por lo que su recepción fija, para canalizarlas en una red de distribución, carece de criticidad.

La elección de antenas para radio FM es simple, bastando la colocación de una antena circular omnidireccional, salvo casos especiales de recepción donde se requieran antenas directivas.

![antenaam](./antenaam.jpg)


Estas antenas tienen un ancho de banda ajustado a las frecuencias utilizadas para las transmisiones de FM, comprendidas entre los 88 y 108 MHz, que corresponden a la banda II de VHF.

![ICTV04_CONT_R175_pic091](./ICTV04_CONT_R175_pic091.jpg)

## Radio digital DAB (Digital Audio Broadcasting)

Al igual que el servicio de radio FM, las emisiones de radio digital DAB han sido diseñadas para la recepción móvil, por lo que su captación desde estaciones estáticas, como edificios, no es una cuestión crítica.

La elección de la antena se ajustará para la captación de la banda III de l VHF, pues es esta banda la reservada para este tipo de transmisiones.

La colocación de la antena será en posición vertical, pues la polarización de la onda electromagnética DAB es también vertical.

![xICTV04_CONT_R176_pic092_mini.jpg](./xICTV04_CONT_R176_pic092_mini.jpg)



![xICTV04_CONT_R177_pic093_mini_mini.png](./xICTV04_CONT_R177_pic093_mini_mini.png)

<br>
<br>

## Cómo funciona una antena Yagi-Uda

En virtud del principio de reciprocidad, se puede demostrar que las propiedades (impedancia, ganancia, etc.) de una antena cualquiera son las mismas tanto en emisión como en recepción. Como es más fácil de comprender el funcionamiento de una antena Yagi-Uda en transmisión que en recepción, comenzaremos por una antena en transmisión.

Como ya se ha mencionado, una antena Yagi-Uda está formada por un elemento alimentado (conectado al emisor o al receptor) formado por un simple dipolo o un dipolo doblado llamado también "radiador" de manera inapropiada, ya que en la antena Yagi-Uda todos los elementos irradian de manera comparable. Además de ese elemento, la antena tiene uno o varios elementos aislados llamados, injustamente, elementos parásitos. La corriente que circula en el elemento alimentado irradia un campo electromagnético, el cual induce corrientes en los "elementos parásitos" de la antena. Las corrientes inducidas en esos elementos irradian también campos electromagnéticos que a su vez inducen corrientes en los demás. Finalmente la corriente que circula en cada uno de los elementos es el resultado de la interacción entre todos los elementos. El elemento alimentado. La fase de la corriente que circula en el elemento parásito dependerá de la distancia entre los dos elementos y de la longitud y diámetro de este último. La amplitud también dependerá de lo mismo pero mucho menos y será, de todas maneras, de la misma magnitud que la corriente del elemento alimentado.

Coloquemos el elemento parásito delante del elemento alimentado a una distancia de {\displaystyle \scriptstyle {\lambda \over 10}}\scriptstyle{\lambda\over 10} (donde {\displaystyle \scriptstyle {\lambda }}\scriptstyle {\lambda} es la longitud de onda) y ajustemos su longitud para que la corriente tenga un retardo de fase de {\displaystyle \scriptstyle {180-{360 \over 10}\,=\,144^{\circ }}}\scriptstyle {180-{360 \over 10}\,=\,144^\circ}. En ese caso, el cálculo muestra que la corriente en el elemento parásito es 1,19 veces la corriente en el elemento alimentado. El campo radiado hacia atrás será la suma del campo producido por el elemento alimentado más el campo producido por el elemento parásito. Pero este último ha sido emitido con un retardo de 144° y como debe recorrer una distancia adicional de {\displaystyle \scriptstyle {\lambda \over 10}}\scriptstyle{ {\lambda\over 10}} sufrirá un retardo adicional de 36°, lo que hace que, hacia atrás, los campos emitidos por los dos elementos estarán a 180° en oposición de fase y se anulan. En cambio, hacia adelante, el campo emitido por el elemento parásito, ganará 36° (en lugar de perderlos) y su retardo de fase no será más que {\displaystyle \scriptstyle {144-36=108^{\circ }}}\scriptstyle{144-36=108^\circ}. La suma de los dos campos será máxima.

En el caso particular de este ejemplo, la amplitud E del campo eléctrico de la onda electromagnética radiada hacia adelante en una dirección {\displaystyle \scriptstyle {\theta }}\scriptstyle {\theta } es {\displaystyle \scriptstyle {E_{1}{\sqrt {2{,}42+2{,}38\cos \left({2\pi \over 10}\cos \theta -{8\pi \over 10}\right)}}}}\scriptstyle{ E_1\sqrt{2{,}42 + 2{,}38\cos\left({2\pi\over 10}\cos\theta-{8\pi\over 10}\right)}} donde {\displaystyle \scriptstyle {E_{1}}}\scriptstyle {E_1} es el campo producido por el elemento alimentado si estuviese solo. La ganancia es de 8,96 dBi.

Este tipo de elemento parásito, situado delante el elemento alimentado y que refuerza el campo hacia adelante, se llama director. Los elementos situados detrás y que refuerzan el campo hacia adelante se llaman reflectores. Pero no hay que confundirlos con las superficies o rejas reflectoras utilizadas en otros tipos de antenas.

Generalmente se ponen uno o dos reflectores y uno o varios directores. Se calculan las posiciones y las dimensiones de manera que las fases de las corrientes resultantes sean tales que la adición de los campos sea mínima hacia atrás y máxima hacia adelante.

Eléctricamente, el costo de esta directividad es una disminución de la parte resistiva de la impedancia de la antena. Con una misma corriente de alimentación, el campo radiado es más débil. Se compensa este inconveniente remplazando el dipolo alimentado por un dipolo doblado.

Para la antena en recepción, la fase y la amplitud de las corrientes inducidas en los elementos por el campo incidente y los demás elementos hace que la corriente inducida en el elemento alimentado (ahora conectado al receptor) sea máxima para los campos que vienen de delante y mínima para los campos que vienen de detrás.

<br>
<br>

# Amplificador 

## Tipos 
    1. Monocanal.
    2. Banda ancha.


## Caracteristicas técnicas.

Ganancia del amplificador en dB: ni muy alta ni muy baja.

Factor de ruido o figura de ruido.

Banda de frecuencia pasante.

Impedancia de entrada y salida 

Tensión máxima de entrada

Tensión máxima de salida

<br>
<br>

# Preamplificador de antena


[instalacion de antena TDT](https://elcajondelelectronico.com/instalacion-antena-tdt/)

<br>
<br>

# Amplificadores de mastil

buscar


<br>
<br>

# Amplificadores monocanal

buscar tipos


<br>
<br>

# Central Amplificadora

Los niveles de señal tienen que ser de un maximo de 6db


































