# CIB-Open
Dispositivo biomecánico de descanso en plano inclinado con retención pelviana y cinemática diferencial (Open Source Hardware).
CIB-Open: Cama de Inclinacion Biomecanica (Open Source Hardware)

Licencia: CERN-OHL-P (Permisiva) / CC BY-SA 4.0
Estado: Especificacion Abierta / Concepto de Diseno Validado
Filosofia: Dispositivo uniproposito de descanso y recuperacion biomecanica.

JUSTIFICACION FISIOLOGICA Y BIOMECANICA

- El descanso en plano inclinado continuo de 15 a 25 grados aborda limitaciones mecanicas e hidrostaticas del cuerpo en posicion plana de 0 grados:

- Prevencion del Reflujo Gastroesofagico: Genera un gradiente de presion hidrostatica negativo respecto al esfinter esofagico inferior, impidiendo el ascenso del contenido gastrico sin necesidad de doblar el torso.

- Evacuacion de Gases por Flotabilidad: La inclinacion continua provee un vector vertical que facilita la migracion pasiva de gases a traves de las flexuras del colon durante la noche.

- Traccion Cervical Pasiva: La gravedad ejerce un vector longitudinal ligero sobre la columna vertebral, descomprimiendo la zona cervical C1 a C7 sin compresion toracica.

INGENIERIA DETALLADA DE LOS MECANISMOS

A. Cajon Mecanico y Cinematica del Cable Diferencial de 360 Grados
Para permitir la rotacion completa del cuerpo, ya sea dormir de lado o boca arriba, sin que la sujecion se afloje de un lado ni estrangule del otro, se implementa un circuito de transferencia de longitud en tiempo real:

- El Cajon Estructural: La plataforma superior no es una tabla ciega, sino un bastidor hueco de 60 milimetros de altura interna con placas de madera multilaminada de 15 milimetros en la parte superior y 10 milimetros en la inferior. Esto otorga rigidez absoluta para cargas de mas de 150 kilos e independiza el mecanismo de la superficie de descanso.

- Circuito de Poleas y Cable Continuo: Un solo cable de acero flexible de 3 milimetros, recubierto en PVC para una operacion silenciosa, recorre el interior del cajon sobre 4 poleas de nylon montadas en rodamientos sellados de bolilla tipo 608zz.

- Dinamica de Rotacion: Al girar de lado, la cadera que se eleva demanda mayor recorrido de cable; el sobrante del lado opuesto se transfiere instantaneamente a traves del circuito de poleas, manteniendo una tension de retencion constante sin inmovilizar al usuario.

- Mantenimiento y Calibracion: Incluye un tensor roscado pasivo en el circuito interno para absorber la elongacion elastica del cable con el paso de los anos.

B. Sujecion Pelviana Modular y Colchoneta Tecnica

- Separacion de Indumentaria: Se elimina la necesidad de prendas de vestir especiales. El sistema utiliza una faja lumbar independiente de alta tenacidad con cierre de contacto tipo velcro que se coloca sobre cualquier pijama.

- Puntos de Anclaje: Integra dos lenguetas de cinturon de seguridad automotriz en las crestas iliacas laterales. La traccion gravitatoria la absorbe directamente la estructura osea de la pelvis, dejando el abdomen y el torax 100 por ciento libres de presion.

- Colchoneta HR y Pasantes Ovalados: Plancha de poliuretano de Alta Resiliencia de 35 a 45 kilos por metro cubico y de 10 centimetros de espesor con capacidad de soporte para personas de mas de 100 kilos. Cuenta con dos ojales ovalados de 15 por 5 centimetros distanciados a 70 centimetros entre ejes, equipados con bujes flexibles antifriccion para evitar que el cable rompa la espuma.

C. Bloqueo Pasivo por Inclinacion y Destrabe a 0 Grados

- Geometria de Traba en V: La base inferior fija posee perfiles convexos y la base superior cajon caladuras concavas a 120 grados. La propia gravedad y el peso del usuario traban ambas estructuras al inclinarse, eliminando la necesidad de frenos hidraulicos activos.

- Solucion Anti Acunamiento: Para evitar que la madera se clave por friccion de cuna al bajar a posicion horizontal de 0 grados, las caras de contacto estan revestidas con polimero de ultra alto peso molecular tipo UHMW-PE.

- Rodillos de Elevacion Pasiva: En el final del recorrido horizontal de 0 grados, dos rodamientos en la base fija hacen tope contra el cajon superior, levantandolo 5 milimetros en el aire y desacoplando los dientes en V por completo de forma 100 por ciento mecanica.

D. Sistemas de Inclinacion y Control

- Opcion Electromecanica Recomendada: Actuador lineal de 24 voltios de 4000 Newtons acoplado entre la base y el cajon. Incorpora un banco de baterias de gel en serie de 24 voltios y 7 amperios hora que actua como UPS automatica ante cortes de luz, permitiendo hasta 30 ciclos sin red electrica. Incluye un pin de desacople mecanico por cable de traccion manual para emergencias.

- Opcion Mecanica Manual: Pivote central desmultiplicado relacion 1 a 4 desplazado cerca del centro de masa del cuerpo, aprovechando el efecto contrapeso. Se opera mediante una palanca rebatible ubicada en el tercio inferior, en la zona de las piernas, que no obstruye el acceso lateral a la cama, asistida por un piston hidraulico o de gas de descenso progresivo.

E. Integracion Termica y Seguridad Pasiva

- Disipacion de Humedad: La tapa de madera del cajon hueco cuenta con perforaciones matrices de 20 milimetros de diametro cada 10 centimetros por debajo de la colchoneta para evitar la acumulacion de humedad corporal o la formacion de hongos.

- Proteccion Perimetral: Incorpora un fuelle textil elastico entre la base y el cajon para prevenir puntos de atrapamiento en pies o manos durante el movimiento.

- Tope Plantar de Respaldo: Incluye un apoyapies acolchado retractil en el extremo inferior como retencion secundaria en caso de que el usuario olvide ajustar la faja pelviana antes de inclinar la plataforma.

1 - LISTA DE MATERIALES ESTIMADA

- Estructura: Madera multilaminada de 15 milimetros y 10 milimetros, o perfileria de hierro estructural.

- Cinematica: Cable de acero de 3 milimetros recubierto en PVC, mas 4 poleas de nylon con rodamientos 608zz, mas tensor roscado.

- Sujecion: Faja lumbar de poliamida, mas 2 juegos de hebillas y receptaculos de cinturon automotriz.

- Acolchado: Plancha de espuma HR de 35 kilos por metro cubico de 10 centimetros de espesor, mas bujes de goma flexible.

- Actuacion: Actuador lineal de 24 voltios de 4000 Newtons, mas 2 baterias de gel de 12 voltios y 7 amperios hora, mas cargador flotante (o kit de palanca, cable y piston de gas para version manual).

- Desplazamiento: Revestimiento de UHMW-PE en tiras, mas 2 rodillos de elevacion pasiva.

Diseñado para la salud publica, la libre fabricacion y la optimizacion del descanso humano.
