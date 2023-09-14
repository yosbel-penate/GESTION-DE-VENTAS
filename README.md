# GESTION-DE-VENTAS
desarrollo de una aplicación para la gestión de ventas con el  propósito de poder modernizar, facilitar y mejorar a la empresa Meitor para la gestión  en sus procesos de ventas, compras, producción, área de logística y finanzas


Cada miembro del equipo debe completar tareas que demuestren la implementación y el dominio de los objetivos de la asignatura. No se permiten clases implementadas por más de un miembro del equipo, y las clases relacionadas mediante herencia deben ser implementadas por el mismo programador. No se permiten exposiciones compartidas de dichas clases. El profesor evaluará la complejidad del proyecto realizado por el equipo y decidirá si alcanza el nivel suficiente para ser aceptado. El profesor revisará el diagrama UML del proyecto y la contribución de cada estudiante. El proyecto solo será aceptado si todos los diagramas UML de los miembros son aprobados por el profesor, los estudiantes deben tener sus diagramas UML listos antes de codificar y lo más rápido posible.

Los estudiantes deberán entregar de manera individual una documentación en la Wiki del repositorio que explique de manera detallada la implementación de su trabajo, incluyendo un diagrama de clases que muestre su parte del proyecto, así como una explicación de cada método y variable de cada clase, junto con una explicación de cada relación utilizada. En dicha documentacion se debe ver reflejado el cumplimiento de todos los objetivos de la asignatura(estos se encuentran al principio de cada conferencia) por parte del estudiante, así como la esplicación de como utilizar las interfaces gráficas del proceso que implementó. De faltar algun objetivo durante la primera exposición se enviará al estudiante a segunda vuelta. La presentacion del proyecto es de manera individual, por tanto todo estudiante debe tener conocimiento del negocio en general. La parte que implemente un programador debe cumplir un con un flujo completo de al menos una actividad, un CRUD completo. La aplicación debe ser de ventanas gráficas, con menús que utilicen elementos visuales de java. El profesor evaluará a cada miembro del equipo de acuerdo a la frecuencia, calidad y cantidad de pullrequest aceptados, con lo cual verificará que lo que el estudiante expone realmete lo implementó él, no se aceptará ningún códico que no fue previamente aceptado mediante un pullrequest. El proyecto que será aceptado será aquel que está registrado en este repositorio y no se aceptará otra version fuera de este.

Para la realización del diagrama UML se utilizará la extension de Vscode: PlantUML v2.17.5, el lenguaje de desarrollo será java 17.0.5 y el IDE de desarrollo Vscode v 1.81.1 con las extensiones:

Project Manager for Java v0.23.1

Debugger for Java v0.54.0

Language Support for Java(TM) by Red Hat v1.13.0

Se instalará el java:

java 17.0.5 2022-10-18 LTS

Java(TM) SE Runtime Environment (build 17.0.5+9-LTS-191)

Java HotSpot(TM) 64-Bit Server VM (build 17.0.5+9-LTS-191, mixed mode, sharing)

Planteamiento del problema:

Vivimos en un mundo donde día a día estamos sumergidos e inmersos en esta 
era tecnológica y digital es por ello que la empresa Sajor ve por conveniente optar 
por la implementación de una aplicación de escritorio para la gestión de ventas ya que la 
empresa cuenta con varios locales y es tanto dificultoso poder llevar el control de
entrada y salida de la mercadería actualizada ya que lo hacen de forma manual y
al finalizar el día, esto dificulta tener un control exacto en cuanto al stock con la 
que cuenta diariamente la empresa, además el trasladarse o comunicarse de una 
tienda con otra toma más tiempo ya que a diario es diferente las ventas generadas 
,con un control de inventario de escritorio se tendrá un mejor control de la mercadería que 
cuentan a diario será actualizada, reducirá el tiempo en la búsqueda en cuanto a 
la ubicación, preferencia de los clientes y por ultimo ayudara a poder saber que 
mercadería es necesario comprar y producir.
El principal problema que ha identificado en la empresa ha sido la reducción de 
sus ventas ya que con el paso de los años han surgido muchos competidores 
debido a la baja demanda de compradores, falta de organización, márquetin, 
problemas frecuentes como la disminución de producción de fustanes 
computarizados debido a la falta de materiales y falta de ingresos financieros en 
la empresa optan en paralizar la producción para evitar pérdidas en cuanto al
4
pago del personal y mantenimiento de las maquinas bordadoras, otro problema 
que se llegó a identificar es el mal manejo en el control de mercadería ya que se 
lleva en apuntes en cuadernos, falta de marketing, las diversas áreas que no 
cuentan con un adecuado plan de trabajo o estratégico que pueda mantener la 
producción constante, sino que es solo por temporadas. La empresa Sajor ha visto 
conveniente contar con una aplicación de escritorio para la gestión de ventas para poder 
ganar clientes y mejorara el control de la mercadería ya que hay meses 
provechosos como la temporada de Santiago y es ahí en que el negocio tiene 
mucha demanda es necesario tener actualizada el stock de la mercadería tanto 
para poder venderla de manera rápida y también para poder producir la cantidad 
necesaria, exacta para mantener el stock y precio adecuado, fuera de nuestra 
región a nivel nacional también hay clientes en el mercado internacional
compatriotas que salen de nuestro país en busca de nuevas oportunidades a
países como Italia, EEUU; y para eso se propiciara la venta por internet ya que en 
estos tiempos no es ajeno a ello ya que las ventas por internet en estos últimos 
meses se incrementó de manera gigantesca

Comercio Internacional de Prendas Típicas y Artesanales:
El sector comercial ya sea ropa, calzado, y accesorios “se caracteriza por 
una producción geográficamente dispersa y por cambios rápidos 
impulsados por el mercado, proporciona oportunidades de empleo a 
millones de trabajadores en todo el mundo, en particular a las mujeres 
jóvenes” (Organización Internacional del Trabajo OIT, 2016),es por eso que 
es uno de los sectores con fuerte potencial a nivel internacional , su 
relevancia a nivel mundial es realmente sorprendente, como pilar del 
comercio y de la economía mundial. La industria textil ha evolucionado con 
el paso de los años y tecnificado de forma acelerada, contribuyendo con 
ello a mejorar su nivel de producción. Las prendas y accesorios típicos 
artesanales ingresan a los países europeos y latinoamericanos con gran 
demanda es por ello que se expanden de manera consustancial, los límites 
del planeta en toda su extensión, vía extracción de materias primas. Se 
profesionalizan las exportaciones, aumentando las cadenas de 
proveedores con el fin de minimizar costos (como misión), es por ello que la 
innovación en procesos productivos es fundamental para conseguir mejores 
ingresos, permitan crecer al país económicamente y posicionaros entre los 
mercados más importantes de todo el mundo “se han convertido en una 
característica dominante del comercio y la inversión mundial que abarca 
economías en desarrollo, emergentes y desarrolladas”.

Comercio Regional de Prendas Típicas y Artesanales:
El sector dedicado a la comercialización de prendas y accesorios típicas 
artesanales está enfrentando nuevas oportunidades de crecimiento, parte 
de esta propagación tiene mucho que ver con las fiestas costumbristas en 
nuestra región ya que es muy acogedora y de gran concurrencia de 
nuestros pobladores, la región del valle del Mantaro goza de diversas 
culturas, vivencias y costumbres tradicionales es por ello que cada distrito
propaga como parte de su cultura. Existe una gran parte de la población que
difunde este tipo de vivencias que vienen de nuestros antecesores ya que 
con coloridos atuendos y vestimentas compiten por quien se vea mejor debido a 
ello y otros factores más hacen que en esta región se comercialice las prendas 
y accesorios típicas artesanales oriunda del valle del Mantaro.
Empresa Sajor:
Sajor es una empresa familiar dedica a la producción de fustanes 
computarizados en todo su variedad y venta de prenda y accesorios
típicas artesanales como mantillas, llicllas, faja, sombrero, manta matiz 
de diferentes calidades, pañolones, telares justes interiores, prendas 
afines a la temporada bailable y tradicional de cada pueblo 
costumbrista.
En 1988 el Sr. Abraham Luis Rojas Laura y la Sra. Eumelia Victoria 
Solano Briceño, iniciaron el negocio de la venta de prendas típicas, 
frazadas, pañolones, telares en esas épocas eran de gran acogida por 
toda nuestra del valle del Mantaro de manera ese tipo de mercadería 
que ofrecían eran muy cotizadas y provechosas ya que eran pocos los
que se dedicaban a este tipo de comercio con el paso de los años la 
empresa incorpora la venta de prendas como fustanes rebetes, fustanes 
con bordados de corazón, fustanes con bordados caracol, plumillados y 
lo que más demanda llego a tener fueron las famosas polleras más 
conocidos como los talqueados (bordados a mano).Mas adelante en el 
año 2010 salen al mercado estas polleras coloridas en bordado 
computarizado y muy conveniente comprarlas ya el precio era mucho 
menor al precio del fustán bordado a mano.

Problemas Frecuentes que se Identificaron en la empresa Sajor:
● Falta de organización interna:
La falta de organización en la empresa es debido a que no cuenta 
con organigrama, áreas específicas, personal no especializado y 
falta de jerarquía dentro de la empresa.
● Mala distribución del trabajo:
Este problema se presenta debido a que la empresa tiene meses 
en que no cuenta con los suficientes ingresos para poder pagar al 
personal y sean solo pocos los que trabajen y eso hace que un 
mismo trabajador esté involucrado en varios procesos y no es lo 
mismo que un personal este designado a un trabajo específico.
● Falta de Innovación Tecnológica:
La empresa no cuenta con ningún apoyo tecnológico todos los 
procesos y actividades son de forma tradicional y manual.
● Mal control de mercadería contabilidad deficiente:
En cuanto al ingreso y salida de mercadería es de manera 
tradicional lo llevan en apuntes en cuadernos como consecuencia 
de ello hace que las ventas sean lentas ya que son numeras 
mercaderías y eso dificulta mantener actualizado el stock de los 
productos

Problemas con la Producción:
La producción de fustanes normalmente es de 4 unidades, a falta de 
compradores la producción tiene que reducirse en más de un 50% de lo 
normal

La producción reducida no favorece al personal, ya que pueda trabajar 
en otras áreas para que llegue a cumplir su jornada laboral y esto 
llevaría a la reducción de personal.
Problemas con los Clientes:
Los clientes en temporadas bajas como por ejemplo las campañas 
escolares las ventas bajan casi en un 65% de lo normal.
Los clientes compran prendas de bajo costo como sombreros, fajas, 
mantas justes interiores.
Gestión de los Procesos:
● Proceso de Ventas:
La venta con los clientes es proceso interactivo nada sencillo, por la 
interrelación constante atención entre vendedora-cliente.
Las clientas son muy detallistas, exquisitas, buscan la mejor calidad 
y precio, las vendedoras cuentan con la asistencia y asesoramiento 
de la dueña del negocio, tienen conocimiento de los modelos y 
colores con que cuentan los puestos y tiendas.
Las vendedoras son personal altamente eficiente ya que como se 
trata de gustos femeninos dan todo de ellas para que puedan 
convencerlas y puedan llevar el producto.
El mismo proceso llega a realizarse en cuanto a la venta de los 
sombreros, fajas, mantillas, mantas, pañolones, telares, justes.
● Proceso de Compras:
La empresa Sajor compra mercadería todo el tiempo a pesar de no 
contar con las expectativas de ventas que la empresa pronostica.
Se hace el pedido de la mercadería una vez que llega la mercadería 
estás llegan hacer registradas en un cuaderno para poder llevar el 
control de la cantidad de mercadería que hay en stock y de esa 
manera según a las salidas poder seguir haciendo más pedidos del 
color, modelo, etc.

Metas del Aplicativo de escritorio
● Diseñar un aplicativo de escritorio que permita tener un registro óptimo de 
las ventas en la empresa “Sajor”; facilitando los procesos 
realizados por los usuarios.
● Controlar los productos, conociendo su stock en tiempo real 
mediante un aplicativo de escritorio de control de inventarios.
● Registrar los ingresos y egresos que se realizan a durante cierto 
periodo de tiempo mediante un aplicativo de escritorio de control de 
ventas.
● Emitir reportes que brinden información a los encargados de la 
empresa “Sajor”, sobre sus ventas, gastos, entre otros mediante 
un aplicativo de escritorio.

Requisitos para el Aplicativo de escritorio
A continuación, se establece los requisitos de la empresa “Sajor” 
necesita en realidad; basándose en las metas establecidas. De esta 
forma, se tiene una idea clara de lo deseado por el cliente y lo pensado 
por el desarrollador. Los requerimientos son listados a continuación:
3.2.2.1. Requerimientos Funcionales
● El aplicativo permitirá registrar un nuevo modelo de 
prendas.
● El aplicativo permitirá modificar algunos datos de los 
modelos de prendas.
● El aplicativo permitirá desactivar algunos registros de los 
modelos de prendas.
● El aplicativo permitirá buscar algún registro de los modelos 
de prendas.
● El aplicativo mostrará una interfaz para gestionar los 
modelos de prendas.
● El aplicativo listará a todos los modelos de prendas 
registrados en la base de datos.
30
● El aplicativo permitirá registrar un nuevo artículo de venta.
● El aplicativo permitirá modificar algunos datos de los 
artículos de venta.
● El aplicativo permitirá desactivar algunos registros de los 
artículos de venta.
● El aplicativo permitirá buscar algún registro de los artículos 
de venta.
● El aplicativo mostrará una interfaz para gestionar los 
artículos en venta.
● El aplicativo listará a todos los artículos en venta 
registrados en la base de datos.
● El aplicativo permitirá registrar un nuevo proveedor.
● El aplicativo permitirá modificar algunos datos del 
proveedor.
● El aplicativo permitirá eliminar los datos de un proveedor.
● El aplicativo permitirá buscar algún registro de los 
proveedores.
● El aplicativo mostrará una interfaz para gestionar a los 
proveedores.
● El aplicativo listará todos los proveedores registrados en la 
base de datos.
● El aplicativo mostrará una lista de los permisos preconfigurados.
● El aplicativo mostrará una interfaz para gestionar los 
permisos.
● El aplicativo permitirá asignar los permisos mediante 
selección de opciones.
● El aplicativo permitirá registrar un nuevo usuario.
● El aplicativo permitirá modificar algunos datos de los 
usuarios.
31
● El aplicativo permitirá desactivar algunos registros de los 
usuarios.
● El aplicativo permitirá buscar algún registro de los 
usuarios.
● El aplicativo mostrará una interfaz para gestionar los 
usuarios.
● El aplicativo listará a todos los usuarios registrados en la 
base de datos.
● El aplicativo permitirá registrar permisos para un usuario.
● El aplicativo permitirá modificar algunos permisos de los 
usuarios.
● El aplicativo permitirá desactivar algunos registros de los 
permisos de usuarios.
● El aplicativo mostrará una interfaz para gestionar los 
permisos de cada usuario.
● El aplicativo listará todos los permisos de los usuarios 
registrados en la base de datos.
● El aplicativo mostrará una interfaz para acceso login, 
mediante un usuario y contraseña registrada.
● El aplicativo validará el acceso según los permisos 
asignados al usuario.
● El aplicativo permitirá registrar una compra de un 
proveedor de la empresa.
● El aplicativo permitirá anular una compra de un proveedor 
de la empresa.
● El aplicativo mostrará una interfaz para gestionar las 
compras de proveedores de la empresa.
● El aplicativo listará todas las compras realizadas por la 
empresa.
● El aplicativo permitirá ingresar artículos detallados para la 
compra.
32
● El aplicativo mostrará una lista con los artículos adquiridos 
por la empresa en un pedido en particular.
● El aplicativo permitirá registrar un nuevo cliente.
● El aplicativo permitirá modificar algunos datos del cliente.
● El aplicativo permitirá eliminar los datos de un cliente.
● El aplicativo permitirá buscar algún registro de los clientes.
● El aplicativo mostrará una interfaz para gestionar a los 
clientes.
● El aplicativo listará todos los clientes registrados en la base 
de datos.
● El aplicativo permitirá registrar una venta a un cliente por 
la empresa.
● El aplicativo permitirá anular una venta a un cliente por la 
empresa.
● El aplicativo mostrará una interfaz para gestionar las 
ventas a clientes por la empresa.
● El aplicativo listará todas las ventas realizadas por la 
empresa.
● El aplicativo permitirá ingresar artículos detallados para la 
venta.
● El aplicativo mostrará una lista con los artículos vendidas 
por la empresa en una venta en particular.
● El aplicativo mostrará una lista de compras realizadas 
dentro de un rango de fechas.
● El aplicativo mostrará una lista de ventas realizadas dentro 
de un rango de fechas.
● El aplicativo mostrará una interfaz principal que contenga 
un reporte general de compra y venta.
● El aplicativo mostrará gráficos que muestren las compras 
y ventas de los últimos 10 días.
33
● El aplicativo mostrará gráficos que muestren las compras 
y ventas de los últimos 6 meses.

Requisitos 

RF01 Interfaz general del 
aplicativo de escritorio.
Diseñar la plantilla general de las interfaces 
que tendrá el aplicativo de escritorio. 1
RF02 Interfaz para gestionar 
los modelos de prendas.
Diseñar una interfaz que permita registrar,
modificar, eliminar, buscar y listar los 
modelos de prendas (categorías).
1
RF03 Interfaz para gestionar 
los artículos en venta.
Diseñar una interfaz que permita registrar,
modificar, eliminar, buscar y listar los 
artículos en venta.
1
RF04 Interfaz para gestionar 
los proveedores.
Diseñar una interfaz que permita registrar,
modificar, eliminar, buscar y listar los 
proveedores.
2
RF05 Interfaz para gestionar
los permisos.
Diseñar una interfaz que permita buscar y
listar los permisos.
2
RF06 Interfaz para gestionar 
los usuarios.
Diseñar una interfaz que permita registrar,
modificar, eliminar, buscar y listar los 
usuarios.
2
RF07 Interfaz para gestionar 
los permisos de
usuarios.
Diseñar una interfaz que permita registrar, 
modificar, eliminar y listar los permisos de
los usuarios.
2
RF08 Interfaz para acceso
login.
Diseñar una interfaz que permita ingresa
mediante acceso login.
1
RF09 Interfaz para gestionar
las compras de 
artículos.
Diseñar una interfaz que permita ingresa o
anular, y listar las compras realizadas por la 
empresa.
2
RF10 Interfaz para gestionar 
los artículos comprados.
Diseñar una interfaz que permita registrar
artículos comprados por la empresa y el 
control de stock agregado.
2
RF11 Interfaz para gestionar 
los clientes.
Diseñar una interfaz que permita registrar,
modificar, eliminar, buscar y listar los 
clientes.
2
RF12 Interfaz para gestionar Diseñar una interfaz que permita ingresa o 2
35
las ventas de artículos. anular, y listar las ventas realizadas por la
empresa.
RF13 Interfaz para gestionar 
los artículos vendidos.
Diseñar una interfaz que permita registrar 
artículos vendidos por la empresa y el
control de stock disminuido.
2
RF14 Interfaz para gestionar 
los reportes de compras
y ventas.
Diseñar una interfaz que permita mostrar las 
ventas y compras realizadas entre dos
fechas.
3
RF15 Interfaz principal que 
resume las compras y 
ventas realizadas 
durante el día, últimos
10 días y meses.
Diseñar una interfaz que muestre los gastos 
y ventas realizadas durante el día, los 
últimos 10 días y los últimos 6 meses. 3
Fuente. Elaboración propia.
La anterior tabla muestra los requerimientosfuncionales, indicando una 
breve descripción de su respectivo requerimiento y mostrando una 
prioridad (alta, media, baja) que ayuda a la posterior definición de 
sprints.
3.3.2. Historias de Usuario
A continuación, se detalla cada requerimiento, en distintas historias de 
usuario, según nos indica la metodología ágil SCRUM, estas historias 
de usuario se encuentran reflejados en distintas tablas.
La siguiente tabla muestra la historia de usuario para cubrir el 
requerimiento de diseñar una interfaz general que permitirá navegar por 
el aplicativo de escritorio.
Tabla 6: Historia de Usuario 01– Diseñar interfaz general de navegación.
ID HU01
Nombre: Diseñar interfaz general de navegación.
Prioridad: 1 Riesgo: 3
Descripción:
Diseñar un interfaz que sirve para una plantilla general que contiene una 
cabecera, un pie de página y un apartado.
Validación:
- Quiero ver una interfaz principal de navegación.
- La interfaz muestra un side que muestra el acceso a otras interfaces.
- La interfaz muestra al usuario que ha accedido al aplicativo de escritorio.
Fuente. Elaboración propia.
36
En la anterior tabla 6 se muestra la historia de usuario sobre el diseño 
de la interfaz general para navegar, mencionando las validaciones 
superficiales que tendrá el diseño de la interfaz; para el cumplimiento
exitoso del requerimiento.
La siguiente tabla muestra la historia de usuario para cubrir el requisito 
de una interfaz que permita gestionar los modelos de prendas que 
vende la empresa “Sajor”.
Tabla 7: Historia de usuario 02 – Registrar y gestionar los modelos de
prendas.
ID HU02
Nombre: Registrar y gestionar los modelos de prendas.
Prioridad: 1 Riesgo: 3
Descripción:
Diseñar una interfaz que permita registrar, modificar, eliminar, buscar y listar 
los modelos de prendas.
Validación:
- Quiero ingresar un nuevo modelo de prenda.
- Los modelos deben tener un nombre único y una breve 
descripción.
- Los registros pueden modificarse posteriormente.
- Los registros no deben ser eliminados solo desactivados.
Fuente. Elaboración propia.
En la anterior tabla 7 se muestra la historia de usuario para registrar y 
gestionar los modelos de prendas que se venden en la empresa “Sajor”, 
se muestra también algunos criterios de validación para confirmar que 
la historia de usuario cubre el requerimiento establecido.
En la siguiente tabla se muestra la historia de usuario para cubrir el 
requisito de una interfaz que permita gestionar los artículos que son 
vendidos por la empresa “Sajor”.
37
Tabla 8: Historia de usuario 03 – Registrar y gestionar los artículos.
ID HU03
Nombre: Registrar y gestionar los artículos.
Prioridad: 1 Riesgo: 2
Descripción:
Diseñar una interfaz que permita registrar, modificar, eliminar, buscar y 
listar los artículos.
Validación:
- Quiero ingresar un nuevo artículo.
- Los artículos deben tener un nombre y una breve descripción con 
detalles.
- Los registros pueden modificarse posteriormente.
- Los registros no deben ser eliminados solo desactivados.
Fuente. Elaboración propia.
En la anterior tabla 8 se muestra la historia de usuario para registrar y 
gestionar los artículos que se venden en la empresa “Sajor”, se muestra 
también algunos criterios de validación para confirmar que la historia de 
usuario cubre el requerimiento establecido.
La siguiente tabla muestra la historia de usuario para cubrir el requisito 
de una interfaz que permita gestionar los proveedores que tienen 
relación con la empresa “Sajor”.
Tabla 9: Historia de usuario 04 – Registrar y gestionar los proveedores.
ID HU04
Nombre: Registrar y gestionar los proveedores.
Prioridad: 2 Riesgo: 2
Descripción: Diseñar una interfaz que permita registrar, modificar, 
eliminar, buscar y listar a los proveedores.
Validación:
- Quiero ingresar un nuevo proveedor.
- Los proveedores deben tener un nombre y datos de contacto.
- Los registros pueden modificarse posteriormente.
- Los registros pueden ser eliminados posteriormente.
Fuente. Elaboración propia.
38
En la anterior tabla 9 se muestra la historia de usuario para registrar y 
gestionar los proveedores de la empresa “Sajor”, se muestra también 
algunos criterios de validación para confirmar que la historia de usuario 
cubre el requerimiento establecido.
La siguiente tabla muestra la historia de usuario para cubrir el requisito 
de una interfaz que permita gestionar los permisos que tienen relación 
con la empresa “Sajor”.
Tabla 10: Historia de usuario 05 – Registrar y gestionar los permisos.
ID HU05
Nombre: Gestionar los permisos.
Prioridad: 2 Riesgo: 2
Descripción: Diseñar una interfaz que permita buscar y listar los 
permisos.
Validación:
- Quiero asignar permisos a un usuario.
- Los permisos deben tener un nombre único.
Fuente. Elaboración propia.
En la anterior tabla 10 se muestra la historia de usuario para gestionar 
los permisos de la empresa “Sajor”, se muestra también algunos 
criterios de validación para confirmar que la historia de usuario cubre el 
requerimiento establecido.
La siguiente tabla muestra la historia de usuario para cubrir el requisito 
de una interfaz que permita gestionar los usuarios que pertenecen a la 
empresa “Sajor”.
Tabla 11: Historia de usuario 06 – Registrar y gestionar los usuarios. 
ID HU06
Nombre: Registrar y gestionar los usuarios.
Prioridad: 2 Riesgo: 2
Descripción: Diseñar una interfaz que permita registrar, modificar, 
eliminar, buscar y listar a los usuarios.
Validación:
- Quiero ingresar un nuevo usuario.
- Los usuarios deben tener un nombre y datos de contacto.
- Los registros pueden modificarse posteriormente.
- Los registros pueden ser eliminados posteriormente.
Fuente. Elaboración propia.
39
En la anterior tabla 11 se muestra la historia de usuario para registrar y 
gestionar los usuarios de la empresa “Sajor”, se muestra también 
algunos criterios de validación para confirmar que la historia de usuario 
cubre el requerimiento establecido.
La siguiente tabla muestra la historia de usuario para cubrir el requisito 
de una interfaz que permita gestionar los permisos de usuarios de la 
empresa “Sajor”.
Tabla 12: Historia de usuario 07 – Registrar y gestionar los permisos de
usuarios.
ID HU07
Nombre: Registrar y gestionar los permisos de
usuarios.
Prioridad: 2 Riesgo: 2
Descripción:
Diseñar una interfaz que permita registrar, modificar, eliminar y listar 
los permisos de los usuarios.
Validación:
- Quiero ingresar un nuevo permiso para el usuario.
- Los permisos de los usuarios deben tener un nombre y datos de 
contacto.
- Los registros pueden modificarse posteriormente.
- Los registros pueden ser eliminados posteriormente.
Fuente. Elaboración propia.
En la anterior tabla 12 se muestra la historia de usuario para registrar y 
gestionar los permisos de los usuarios de la empresa “Sajor”, se 
muestra también algunos criterios de validación para confirmar que la 
historia de usuario cubre el requerimiento establecido.
La siguiente tabla muestra la historia de usuario para cubrir el requisito 
de una interfaz que permita gestionar los permisos de usuarios de la 
empresa “Sajor”.
40
Tabla 13: Historia de usuario 08 – Acceso mediante login.
ID HU08
Nombre: Gestionar el acceso login.
Prioridad: 1 Riesgo: 2
Descripción:
Diseñar una interfaz que gestiona el acceso mediante login al 
aplicativo de escritorio.
Validación:
- Quiero ingresar mediante el ingreso de usuario y contraseña.
- El acceso al aplicativo será según el permiso del usuario.
Fuente. Elaboración propia.
En la anterior tabla 13 se muestra la historia de usuario para gestionar 
el acceso login para el aplicativo de escritorio de la empresa “Sajor”, se muestra 
también algunos criterios de validación para confirmar que la historia de 
usuario cubre el requerimiento establecido.
La siguiente tabla muestra la historia de usuario para cubrir el requisito 
de una interfaz que permita gestionar las compras de artículos de la 
empresa “Sajor”.
Tabla 14: Historia de usuario 09 – Registrar y gestionar las compras de 
artículos.
ID HU09
Nombre: Registrar y gestionar las compras de artículos.
Prioridad: 2 Riesgo: 1
Descripción: Diseñar una interfaz que permita registrar, anular y listar las 
compras realizadas por la empresa.
Validación:
- Quiero ingresar una nueva compra de artículos.
- Las compras de artículos deben tener datos del proveedor y el 
usuario que registra dicha compra.
- Los registros pueden ser anulados posteriormente.
Fuente. Elaboración propia.
41
En la anterior tabla 14 se muestra la historia de usuario para registrar y 
gestionar las compras de artículos de la empresa “Sajor”, se muestra 
también algunos criterios de validación para confirmar que la historia de 
usuario cubre el requerimiento establecido.
La siguiente tabla muestra la historia de usuario para cubrir el requisito 
de una interfaz que permita gestionar los artículos comprados por la 
empresa “Sajor”.
Tabla 15: Historia de usuario 10 – Gestionar stock de artículos.
ID HU10
Nombre: Gestionar stock de artículos.
Prioridad: 2 Riesgo: 1
Descripción: Diseñar una interfaz que permita registrar los artículos 
comprados, con su respectivo control de stock.
Validación:
- Quiero agregar artículos a la compra.
- Los artículos deben ser agregar a una lista.
- El stock debe variar según la compra registrada.
- El total a pagar se debe actualizar con todo un botón.
- Los artículos comprados se deben mostrar mediante una interfaz.
Fuente. Elaboración propia.
En la anterior tabla 15 se muestra la historia de usuario para gestionar
stock de artículos comprados por la empresa “Sajor”, se muestra 
también algunos criterios de validación para confirmar que la historia de 
usuario cubre el requerimiento establecido.
La siguiente tabla muestra la historia de usuario para cubrir el requisito 
de una interfaz que permita gestionar los clientes que tienen relación 
con la empresa “Sajor”.
42
Tabla 16: Historia de usuario 11 – Registrar y gestionar los clientes.
ID HU11
Nombre: Registrar y gestionar los clientes.
Prioridad: 2 Riesgo: 2
Descripción:
Diseñar una interfaz que permita registrar, modificar, eliminar, 
buscar y listar a los clientes.
Validación:
- Quiero ingresar un nuevo cliente.
- Los clientes deben tener un nombre y datos de contacto.
- Los registros pueden modificarse posteriormente.
- Los registros pueden ser eliminados posteriormente.
Fuente. Elaboración propia.
En la anterior tabla 16 se muestra la historia de usuario para registrar y 
gestionar los clientes de la empresa “Sajor”, se muestra también 
algunos criterios de validación para confirmar que la historia de usuario 
cubre el requerimiento establecido.
La siguiente tabla muestra la historia de usuario para cubrir el requisito 
de una interfaz que permita gestionar las ventas de artículos de la 
empresa “Sajor”.
Tabla 17: Historia de usuario 12 – Registrar y gestionar las ventas de 
artículos.
ID HU12
Nombre: Registrar y gestionar las compras de artículos.
Prioridad: 2 Riesgo: 1
Descripción:
Diseñar una interfaz que permita registrar, anular y listar las ventas 
realizadas por la empresa.
Validación:
- Quiero ingresar una nueva venta de artículos.
- Las ventas de artículos deben tener datos del cliente y el usuario que 
registra dicha venta.
- Los registros pueden ser anulados posteriormente.
Fuente. Elaboración propia.
43
En la anterior tabla 17 se muestra la historia de usuario para registrar y 
gestionar las ventas de artículos de la empresa “Sajor”, se muestra 
también algunos criterios de validación para confirmar que la historia de 
usuario cubre el requerimiento establecido.
La siguiente tabla muestra la historia de usuario para cubrir el requisito 
de una interfaz que permita gestionar los artículos vendidos por la 
empresa “Sajor”.
Tabla 18: Historia de usuario 13 – Gestionar stock de artículos vendidos.
ID HU13
Nombre: Gestionar stock de artículos vendidos.
Prioridad: 2 Riesgo: 1
Descripción:
Diseñar una interfaz que permita registrar los artículos vendidos, con su 
respectivo control de stock.
Validación:
- Quiero agregar artículos a la venta.
- Los artículos deben ser agregar a una lista.
- El stock debe variar según la venta registrada.
- El total a pagar se debe actualizar con todo un botón.
- Los artículos vendidos se deben mostrar mediante una interfaz.
Fuente. Elaboración propia.
En la anterior tabla18 se muestra la historia de usuario para gestionar
stock de artículos vendidos por la empresa “Sajor”, se muestra también 
algunos criterios de validación para confirmar que la historia de usuario 
cubre el requerimiento establecido.
En la siguiente tabla se muestra la historia de usuario para cubrir el 
requisito de una interfaz que permita visualizar las ventas y compras 
realizadas por la empresa “Sajor”.
44
Tabla 19: Historia de usuario 14 – Listar las ventas y compras realizadas.
ID HU14
Nombre: Listar compras y ventas realizadas.
Prioridad: 3 Riesgo: 3
Descripción:
Diseñar una interfaz que permita observar listas de las compras y 
las ventas realizadas.
Validación:
- Quiero conocer las compras realizadas dentro de un rango de 
fechas.
- Quiero conocer las compras realizadas dentro de un rango de 
fechas.
- Elegir fecha de inicio y final para emitir la lista.
Fuente. Elaboración propia.
En la anterior tabla 19 se muestra la historia de usuario para listar las 
ventas y compras realizadas por la empresa “Sajor”, se muestra también 
algunos criterios de validación para confirmar que la historia de usuario 
cubre el requerimiento establecido.
En la siguiente tabla se muestra la historia de usuario para cubrir el 
requisito de una interfaz principal para el aplicativo de escritorio.

Tabla 20: Historia de usuario 15 – Interfaz principal.
ID HU15
Nombre: Interfaz principal.
Prioridad: 3 Riesgo: 3
Descripción: Diseñar una interfaz que muestre los gastos e ingresos del día, 
y de un par de periodos de fechas.
Validación:
- Quiero conocer cuánto de gasto en el día he realizado.
- Quiero conocer cuántos ingresos en el día he tenido.
- Ver mediante un gráfico el flujo de dinero durante los últimos 10 días.
- Ver mediante un gráfico el flujo de dinero durante los últimos 6 meses.

En la anterior tabla 20 se muestra la historia de usuario para diseñar la 
interfaz principal para el aplicativo de escritorio, esta interfaz contendrágráficos 
y valores sobre los ingresos y gastos durante distintos periodos de 
fecha.


