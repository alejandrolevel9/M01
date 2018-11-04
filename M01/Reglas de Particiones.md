# Las reglas de windows (en partíciones)

*Estilo Bios-MBR Dos

Dentro del disco duro hay Particones son sectores dividiros en el disco 
duro para organizar la instalación del sistema operativo.

En windows hay cuarto reglas que se tienes que complir para tenerlo
 
	-1: Solo puede haver 4 particiones.
	-2:Cada particion puede tener un máximo de 2TB
	-3: En las particones Puede haver una particion extended sirve para 
		contener múltiples unidades lógicas en su interior.
	-4: Solo una particion puede ser active.
	-5: La extended no puede ser active porqué se necesito una primaria.
	
En linux es diferente porqué no requiere de una primaria active.

## GPT
Puedes tener N particiones primarias A diferencia del MBR, supera el límite de 2TB por partición, y hasta el momento, no hace falta pensar en el límite, porque aún queda tiempo para ello.


## Por lo tanto, ¿Cual es mejor? 
La respuesta es obvia: siemrpe que podamos hemos de trabajar en el sistema de archivos GPT, porque nos forece más libertades y ventajas que el antiguo MBR
