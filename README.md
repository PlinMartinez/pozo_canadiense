# pozo_canadiense
ADAPTACION DE POZO CANADIENSE A MAQUINA AEROTERMIA
ADAPTACION DE POZO CANADIENSE A BOMBA DE CALOR AIRE AGUA


OBJETIVOS
Implementar el aporte de calor a la bomba de calor cuando las temperaturas bajan mucho en invierno
Sobre todo al anochecer (de 18 horas a 22 horas) cuando la temperatura del aire baja mucho y la tierra aún acumula calor

DESARROLLO
Ya que la bomba de calor no tiene modbus tomo el par de cables de la válvula 2 vías (señal calefacción)
Le añado un relé genérico de 220V para alimentar el extractor del pozo
1.400m3 aire caudal , consumo 200W
Para que funcione solamente al atardecer le añado un termostato regulado a 10º 


CONCUSIONES
La instalación consume lo mismo, se aumenta 200W el consumo y la maquina detecta mejoría en la temperatura y consume lo mismo
Sin embargo, entiendo que ese calor geotermico se termina transmitiendo a la casa 
El camino es 
Aire - tierra – aire : salto térmico de 6,5º
De ahí va al evaporador que esta a -20º y absorbe más calor en menos tiempo


TODO
Medir caudales para poder obtener el COP real tanto del pozo como de la solución integrada 
