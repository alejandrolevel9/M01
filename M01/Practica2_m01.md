**¿que contiene un MBR?**


Un MBR, son los sectores de un dispositivo de almacenamiento
de datos, como un disco duro. El tamaño mínimo de cada sector 
és de 512 B.

En el MBR hay un espacio dónde se ejecuta 
el arranque del sistema operativo, llamado bootstrap que ocupa 446 B.
Después de el Gestor de arranque hay una tabla de particiones, 
que ocupa 64 B dónde se guardan los datos de las particiones que hay en 
el DD. Y por último la firma, un número de identificación del MBR que 
solo ocupa 2 B.


Dentro del MBR se encuentra _partition_ o particiones serian los nombres
genetico que recibe cada division como "unidad c: windows" por ejemplo.
Y dentro de las particiones existen dos tipos en concreto, la primaria
activa que seria donde se pone el sistema operativo, es decir, los 
archivos de arranque, y las particiones exendidas o extended se encuentra 
un monton de unidades logicas en su interior, a lo que podriamos llamar
particiones logicas.


En las MBR DOS se puedes encontrar particiones, pero el limite para 
poner particiones es de 4 solo una extended puede ser puesta en el disco 
aunque no puede ser activa pero esto solo en windows, en el linux 
no requiere de una particion primaria active.


Los informáticos del momento decidieron renovar la BIOS MBR DOS ya que,
era vieja i anticuada. Pues diseñaron una especie de mejora a la que se 
denomina como UEFI acompañado de GPT, que es un estilo de particiones 
diferente; ya que no tiene límite de tamaño ni numero de estas. 



