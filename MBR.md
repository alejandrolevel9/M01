*¿que contiene un MBR?
un MBR, es el primer sector de un dispositivo de almacenamiento
de datos, como un disco duro.Se emplea para arrancar el sistema operativo 
con bootstrp y para almacenar una tabla de particiones.

Dentro del MBR se encuentra partition o particiones serian los nombres
genetico que recibe cada division como "unidad c: windows" por ejemplo.
Y dentro de las particiones existen dos tipos en concreto, la primaria
activa que seria donde se pone el sistema operativo, es decir, los 
archivos de arranque, y las particiones exendidas o extended se encuentra 
un monton de unidades logicas en su interior, a lo que podriamos llamar particiones logicas.

En las MBR-DOS puedes encontrar particiones, pero el limit para poner 
particiones es de 4, solo una extended puede ser puesta en el disco 
aunque no puede ser activa pero esto solo en windows, en ele linux 
no requiere de una particion primaria active.

El espacio de los disco duros esan de 500 GB y en la MBRDOS 
requiere de un espacio de 512 GB.

Tambien en una extended te puede encontra swap ue seria
una memoria de intercambio con la funcion es almacenar
las imagenes de aquellos procesos que no se quedan en las memorias fisicas.

Pero unos señores les parecieron que la MBRDOS era vieja i anticuada 
pues diseñaron una especie de mejora ala que denomina como 
UEFI que lo acompaña con un estilo de particiones diferente ya que 
no tiene limite del tamaño de ellas conocido como GPT. Pero si no 
tiene el S.O a propiado para el conector SATA, es posible que no sea 
compatibles.'
