# Parciales y Exámenes

> Seccion del repositorio **DSI INFO** — 4 documentos.
> Archivo principal: `DSI_INFO_Completo.md` | Indice: `INDEX.md`

## Contenido de esta seccion

- DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1
- DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1
- DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1
- DSI 2026 Simulacro Parcial 2 Estrella de la Muerte

---



## DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1

**Categoría:** Parciales y Exámenes  

**Archivo:** `DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf`  

**Tamaño:** 0.45 MB  


### 📄 Contenido de Texto

#### Página 1

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo primer parcial
Se pide al Estudiante que lea y analice atentamente la situación planteada y en base a
ello:
1. Construya la máquina de estados de la clase Orden de Traslado, utilizando un diagrama de
máquina de estados. Especifique para las transiciones los métodos correspondientes y las
condiciones de control cuando apliquen.
Modele la realización de caso de uso de análisis para el escenario del caso de uso descripto,
aplicando los patrones GRASP de análisis, para ello:
2. Construya la vista de análisis que incluye las clases necesarias para dar soporte al escenario
descripto y a la máquina de estados construida en el punto 1.
3. Modele el escenario descripto en el caso de uso, utilizando un diagrama de secuencia.
Dominio: FIA Fórmula 1
Glosario
Concepto Definición
Una competencia de automovilismo celebrada durante un fin de semana en un circuito
Gran Premio, GP,
específico.
Grand Prix
Es un equipo de pilotos con licencia para disputar la competencia de Fórmula 1. Cada
Escudería
escudería cuenta con 2 pilotos titulares que corren todos los Grandes Premios.
Un monoplaza es el auto que utilizan los pilotos de la Fórmula 1. Llamado así porque solo
Monoplaza
hay lugar para una sola persona.
F1 Acrónimo de Fórmula 1.
FIA Acrónimo de Federación Internacional del Automóvil.
GP Acrónimo de Gran Premio.
Grand Prix Gran Premio.
Tracker GPS Rastreador GPS.
OT Orden de traslado
Descripción del Dominio
La Federación Internacional del Automóvil, también llamada FIA, es una organización sin fines de lucro que
reúne 268 organizaciones automovilísticas de 143 países. La FIA regula a nivel mundial las competiciones de
automovilismo más importantes del mundo entre ellas la Fórmula 1. La Fórmula 1, también conocida como F1, es
conocida como la “competición reina del automovilismo” y es la principal competición de automovilismo internacional
y el campeonato de deportes de motor más prestigioso del mundo. La FIA requiere un software para gestionar la
organización de la competencia de forma exitosa.
Ciclo lectivo 2026 Turnos: Todos Hoja: Página 1 de 9


#### Tabla 1 — Página 1

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo primer parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 1

| 1. Construya la máquina de estados de la clase Orden de Traslado, utilizando un diagrama de
máquina de estados. Especifique para las transiciones los métodos correspondientes y las
condiciones de control cuando apliquen. |
| --- |
| Modele la realización de caso de uso de análisis para el escenario del caso de uso descripto,
aplicando los patrones GRASP de análisis, para ello:
2. Construya la vista de análisis que incluye las clases necesarias para dar soporte al escenario
descripto y a la máquina de estados construida en el punto 1. |
| 3. Modele el escenario descripto en el caso de uso, utilizando un diagrama de secuencia. |


#### Tabla 3 — Página 1

| Modele la realización de caso de uso de análisis para el escenario del caso de uso descripto, |
| --- |
| aplicando los patrones GRASP de análisis, para ello: |


#### Tabla 4 — Página 1

|  | Concepto |  |  | Definición |  |
| --- | --- | --- | --- | --- | --- |
| Gran Premio, GP,
Grand Prix |  |  |  | Una competencia de automovilismo celebrada durante un fin de semana en un circuito |  |
|  |  |  |  | específico. |  |
|  |  |  |  |  |  |
| Escudería |  |  |  | Es un equipo de pilotos con licencia para disputar la competencia de Fórmula 1. Cada |  |
|  |  |  |  | escudería cuenta con 2 pilotos titulares que corren todos los Grandes Premios. |  |
| Monoplaza |  |  |  | Un monoplaza es el auto que utilizan los pilotos de la Fórmula 1. Llamado así porque solo |  |
|  |  |  |  | hay lugar para una sola persona. |  |
|  | F1 |  |  | Acrónimo de Fórmula 1. |  |
|  | FIA |  |  | Acrónimo de Federación Internacional del Automóvil. |  |
|  | GP |  |  | Acrónimo de Gran Premio. |  |
|  | Grand Prix |  |  | Gran Premio. |  |
|  | Tracker GPS |  |  | Rastreador GPS. |  |
|  | OT |  |  | Orden de traslado |  |


#### Tabla 5 — Página 1

| Gran Premio, GP, |
| --- |
| Grand Prix |


#### Página 2

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo primer parcial
La competencia de Fórmula 1 es un evento anual en donde se corren distintas carreras, denominadas Gran
Premio o GP. La FIA anuncia el Calendario de Carreras de la Fórmula 1 para ese año, que incluye las fechas de los
Grandes Premios, determinando donde se correrá y cuando.
Cada Grand Prix se celebra en un circuito particular, cada circuito tiene una sede (que puede ser un autódromo
o un circuito callejero), una longitud de vuelta, una distancia total, una cantidad de vueltas y una traza que indica el
recorrido que realiza. Cada circuito debe negociar con la FIA un contrato para ser parte del calendario de la Fórmula
1, dicho contrato dura una cierta cantidad de años según las negociaciones alcanzadas, dependiendo si el circuito es
popular entre los fanáticos y es un circuito histórico puede ser un contrato año a año o incluso a 10 o 20 años. A la FIA
no le interesa que este software gestione los pormenores del contrato con cada circuito, pero si le interesa saber si un
circuito estará disponible un año dado para armar el calendario. Por ejemplo, el famoso Gran Premio de Italia se
celebra todos los años en el Autódromo Nazionale di Monza en Monza, Italia. Este circuito tiene una longitud de vuelta
de 5,793 kilómetros, una distancia total de 306,720 kilómetros y 53 vueltas. En el 2025, el Gran Premio de Italia se
celebra el fin de semana del 5 al 7 de septiembre y tiene un contrato vigente hasta el año 2035.
Cuando la FIA anuncia un calendario debe anunciar el Gran Premio que se correrá, la fecha del fin de semana
y debe decidir en qué orden se correrán los Grandes Premios. En la Fórmula 1, actualmente, hay 10 escuderías con 2
pilotos cada una, por lo que hay 20 pilotos que buscan coronarse como el Campeón del Mundo. Cada año se compite
por 2 títulos diferentes: Las escuderías compiten por el “Campeonato de Constructores” y los pilotos compiten por el
“Campeonato de Pilotos”.
La FIA quiere que el producto de software no sólo ayude con el armado del calendario y el mantenimiento de
la información de los campeonatos en curso y pasados, sino que también quiere que las distintas escuderías utilicen
este software para la logística relacionada a moverse de un país anfitrión de Gran Premio a otro. Hay 3 tipos de
elementos que las escuderías pueden desear trasladar: elementos de “Hospitality”, que es el área designada para cada
escudería donde los pilotos y el resto del equipo se relajan antes y después de la carrera sin la intromisión de los
fanáticos; “Herramientas y piezas”, que son las herramientas utilizadas para el trabajo en los monoplazas y las partes
extra para los mismo en caso de una avería o rotura; y finalmente los “Monoplazas”, siendo que cada monoplaza entra
en un contenedor. Para trasladar los elementos de un lugar a otro, la FIA utiliza órdenes de traslado.
Estas órdenes de traslado pueden realizarse para trasladar los elementos desde un circuito de un Grand Prix
a otro o pueden utilizarse para:
• Enviar elementos a la fábrica de cada escudería, para ser estudiados por los ingenieros,
• Para enviar partes y herramientas nuevas desde la fábrica a un circuito de un Grand Prix.
La FIA da hasta 10 contenedores para cada escudería; además la FIA instala un rastreador en cada contenedor para
saber a dónde se encuentra en todo momento, y los programa con un código alfanumérico único para distinguirlos
fácilmente.
Para cada Orden de Traslado se debe especificar su lugar de origen y su lugar de destino. Estos lugares de
origen y destino pueden ser algún circuito en particular o la fábrica de la escudería. Quien crea la Orden de Traslado
debe especificar la fecha en la que se necesita que los contenedores lleguen al destino. También debe especificarse
los elementos que deben enviarse en la Orden de Traslado, eligiendo los elementos correspondientes.
Ciclo lectivo 2026 Turnos: Todos Hoja: Página 2 de 9


#### Tabla 1 — Página 2

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo primer parcial |  |
| --- | --- | --- |


#### Página 3

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo primer parcial
Los neumáticos son provistos por la empresa Pirelli, ofreciéndole a todas las escuderías los mismos tipos de
neumáticos. Dado que Pirelli se encarga de la logística y de saber dónde están los neumáticos en todo momento, la
FIA no ve necesario hacer un seguimiento de los neumáticos.
Definición del Producto de Software a construir:
Objetivo del Producto de Software:
Gestionar el calendario de carreras, el campeonato de constructores y el campeonato de pilotos y la logística
de traslado de elementos de escudería de un lugar a otro, generando información relacionada a la logística y a los
campeonatos.
Alcances del producto de software:
● Gestión del calendario de carreras
● Administración de escuderías y pilotos de las escuderías
● Administración de usuarios
● Gestión de Órdenes de Traslado
● Administración de Contenedores
● Generación de reportes de campeonatos y logística de contenedores
No contempla:
● Gestión de Contratos de los circuitos
● Administracion de neumáticos Pirelli
● Administración de paquetes de mejoras
Reglas de Negocio
Nro. Nombre de la Descripción
RN RN
1. C ontenedores Según las reglas de la FIA, cada contenedor puede contener un tipo de elemento a la vez. Por
que provee la ejemplo, no pueden mezclarse elementos del Hospitality con herramientas en un mismo
FIA contenedor que será asignado a una OT.
2. T raslados que Se pueden realizar traslados de elementos desde de un circuito de un Grand Prix a otro; desde
pueden un circuito de un Grand Prix a la fábrica de cada escudería; o desde la fábrica a un circuito de
realizarse con un Grand Prix.
una OT
3. P reparación y Cuando la FIA termina de preparar los contenedores, los marca como Preparados para
entrega de Escudería hasta que sean entregados. Cuando son entregados, los contenedores se marcan
Contenedores como Ociosos hasta que se los asigne a una Orden de Traslado, quedando allí en estado
Asignado a OT.
4. T ratamiento Una Orden de Traslado puede ser creada por el Jefe de Equipo o por alguno de los Jefes de
de una Orden Mecánica de las escuderías.
de Traslado
Ciclo lectivo 2026 Turnos: Todos Hoja: Página 3 de 9


#### Tabla 1 — Página 3

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo primer parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 3

|  | Nro. |  |  | Nombre de la |  | Descripción |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  | RN |  |  | RN |  |  |  |  |
| 1. | 1. |  |  | C ontenedores |  |  | Según las reglas de la FIA, cada contenedor puede contener un tipo de elemento a la vez. Por |  |
|  |  |  |  | que provee la |  |  | ejemplo, no pueden mezclarse elementos del Hospitality con herramientas en un mismo |  |
|  |  |  |  | FIA |  |  | contenedor que será asignado a una OT. |  |
| 2. |  |  |  | T raslados que |  | Se pueden realizar traslados de elementos desde de un circuito de un Grand Prix a otro; desde
un circuito de un Grand Prix a la fábrica de cada escudería; o desde la fábrica a un circuito de
un Grand Prix. | Se pueden realizar traslados de elementos desde de un circuito de un Grand Prix a otro; desde |  |
|  |  |  |  | pueden |  |  | un circuito de un Grand Prix a la fábrica de cada escudería; o desde la fábrica a un circuito de |  |
|  |  |  |  | realizarse con |  |  | un Grand Prix. |  |
|  |  |  |  | una OT |  |  |  |  |
| 3. |  |  | P reparación y
entrega de
Contenedores | P reparación y |  |  | Cuando la FIA termina de preparar los contenedores, los marca como Preparados para |  |
|  |  |  |  | entrega de |  |  | Escudería hasta que sean entregados. Cuando son entregados, los contenedores se marcan |  |
|  |  |  |  | Contenedores |  |  | como Ociosos hasta que se los asigne a una Orden de Traslado, quedando allí en estado |  |
|  |  |  |  |  |  |  | Asignado a OT. |  |
| 4. |  |  |  | T ratamiento |  | Una Orden de Traslado puede ser creada por el Jefe de Equipo o por alguno de los Jefes de
Mecánica de las escuderías. | Una Orden de Traslado puede ser creada por el Jefe de Equipo o por alguno de los Jefes de |  |
|  |  |  |  | de una Orden |  |  | Mecánica de las escuderías. |  |
|  |  |  |  | de Traslado |  |  |  |  |


#### Página 4

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo primer parcial
Nro. Nombre de la Descripción
RN RN
Si a una Orden de Traslado la crea un Jefe de Mecánica, debe ser aprobada por el Jefe de
Equipo. Si la Orden de Traslado la crea un Jefe de Equipo queda aprobada directamente.
El Jefe de Equipo puede aprobar una Orden de Traslado creada por un Jefe de Mecánica o
puede rechazarla, si no está de acuerdo con el destino de la orden. Una vez que la Orden de
Traslado está aprobada, comienza la preparación de la Orden de Traslado, lo que implica el
inicio del armado de los contenedores.
Cuando se finaliza el armado de un contenedor, este se marca como Armado. Cuando el
Encargado de Logística finaliza el armado de todos los contenedores de una Orden de Traslado,
marca esa Orden de Traslado como Lista para envío. Cuando los contenedores se envían a su
lugar de destino, se debe marcar la Orden de Traslado y los contenedores como En Traslado.
5. T ratamiento Cuando el/los contenedor/es llegan a destino se marcan como Para Verificar y la Orden de
de un Traslado debe quedar En Destino. El Encargado de Logística del lugar de destino (Próximo Grand
Contenedor Prix o Fábrica) debe revisar cada contenedor para ver si contiene todo lo que se solicitó
originalmente, y ver que no tenga roturas, abolladuras u otros inconvenientes.
Si los contenedores tienen todo lo que se pidió y están en buenas condiciones, la Orden de
Traslado se actualiza a Exitosa y el contenedor se actualiza a Ocioso. Si algún contenedor de
una orden de traslado está incompleto, se debe marcar la orden de traslado como Incompleta
y se debe crear una nueva Orden de Traslado solicitando lo que falta, marcando al contenedor
como Ocioso también en este caso.
Independientemente de si llega todo lo pedido en la Orden de Traslado o no, si el contenedor
tiene algún tipo de problema o daño, se lo marca como Dañado para que se le realice una
inspección. Si los daños no son sustanciales y no comprometen la integridad del contenedor,
se lo marca como Ocioso, en caso contrario se lo da De baja.
6. N otificaciones Se debe notificar vía mail WhatsApp y/o SMS al Jefe de Equipo cada vez que un Jefe de
para una Mecánica crear una Orden de Traslado.
Orden de Si no se ha aprobado la Orden de Traslado dentro de las 12 horas de su creación, se deben
Traslado enviar las notificaciones nuevamente.
Cuando se aprueba una Orden de Traslado se deberá enviar una notificación al Encargado de
Logística asignado de armar los contenedores para que sean armados dentro de las 12 horas
de la aprobación de la Orden de Traslado.
7. R echazo Si pasan 24 horas desde que se creó una Orden de Traslado y no se ha aprobado, la misma se
automático de rechaza de forma automática.
una Orden de
Traslado
8. C ancelación Una Orden de Traslado puede ser cancelada en tanto no se haya iniciado el traslado de los
de una Orden contenedores. A partir de ese punto ya no puede ser cancelada.
de Traslado
Ciclo lectivo 2026 Turnos: Todos Hoja: Página 4 de 9


#### Tabla 1 — Página 4

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo primer parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 4

|  | Nro. |  |  | Nombre de la |  | Descripción |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  | RN |  |  | RN |  |  |  |  |
|  |  |  |  |  |  |  | Si a una Orden de Traslado la crea un Jefe de Mecánica, debe ser aprobada por el Jefe de |  |
|  |  |  |  |  |  |  | Equipo. Si la Orden de Traslado la crea un Jefe de Equipo queda aprobada directamente. |  |
|  |  |  |  |  |  |  | El Jefe de Equipo puede aprobar una Orden de Traslado creada por un Jefe de Mecánica o |  |
|  |  |  |  |  |  |  | puede rechazarla, si no está de acuerdo con el destino de la orden. Una vez que la Orden de |  |
|  |  |  |  |  |  |  | Traslado está aprobada, comienza la preparación de la Orden de Traslado, lo que implica el |  |
|  |  |  |  |  |  |  | inicio del armado de los contenedores. |  |
|  |  |  |  |  |  |  | Cuando se finaliza el armado de un contenedor, este se marca como Armado. Cuando el |  |
|  |  |  |  |  |  |  | Encargado de Logística finaliza el armado de todos los contenedores de una Orden de Traslado, |  |
|  |  |  |  |  |  |  | marca esa Orden de Traslado como Lista para envío. Cuando los contenedores se envían a su |  |
|  |  |  |  |  |  |  | lugar de destino, se debe marcar la Orden de Traslado y los contenedores como En Traslado. |  |
| 5. |  |  | T ratamiento
de un
Contenedor |  |  |  | Cuando el/los contenedor/es llegan a destino se marcan como Para Verificar y la Orden de |  |
|  |  |  |  |  |  |  | Traslado debe quedar En Destino. El Encargado de Logística del lugar de destino (Próximo Grand |  |
|  |  |  |  |  |  |  | Prix o Fábrica) debe revisar cada contenedor para ver si contiene todo lo que se solicitó |  |
|  |  |  |  |  |  |  | originalmente, y ver que no tenga roturas, abolladuras u otros inconvenientes. |  |
|  |  |  |  |  |  |  | Si los contenedores tienen todo lo que se pidió y están en buenas condiciones, la Orden de |  |
|  |  |  |  |  |  |  | Traslado se actualiza a Exitosa y el contenedor se actualiza a Ocioso. Si algún contenedor de |  |
|  |  |  |  |  |  |  | una orden de traslado está incompleto, se debe marcar la orden de traslado como Incompleta |  |
|  |  |  |  |  |  |  | y se debe crear una nueva Orden de Traslado solicitando lo que falta, marcando al contenedor |  |
|  |  |  |  |  |  |  | como Ocioso también en este caso. |  |
|  |  |  |  |  |  |  | Independientemente de si llega todo lo pedido en la Orden de Traslado o no, si el contenedor |  |
|  |  |  |  |  |  |  | tiene algún tipo de problema o daño, se lo marca como Dañado para que se le realice una |  |
|  |  |  |  |  |  |  | inspección. Si los daños no son sustanciales y no comprometen la integridad del contenedor, |  |
|  |  |  |  |  |  |  | se lo marca como Ocioso, en caso contrario se lo da De baja. |  |
| 6. |  |  | N otificaciones
para una
Orden de
Traslado |  |  |  | Se debe notificar vía mail WhatsApp y/o SMS al Jefe de Equipo cada vez que un Jefe de |  |
|  |  |  |  |  |  |  | Mecánica crear una Orden de Traslado. |  |
|  |  |  |  |  |  |  | Si no se ha aprobado la Orden de Traslado dentro de las 12 horas de su creación, se deben |  |
|  |  |  |  |  |  |  | enviar las notificaciones nuevamente. |  |
|  |  |  |  |  |  |  | Cuando se aprueba una Orden de Traslado se deberá enviar una notificación al Encargado de |  |
|  |  |  |  |  |  |  | Logística asignado de armar los contenedores para que sean armados dentro de las 12 horas |  |
|  |  |  |  |  |  |  | de la aprobación de la Orden de Traslado. |  |
| 7. |  |  |  | R echazo |  | Si pasan 24 horas desde que se creó una Orden de Traslado y no se ha aprobado, la misma se
rechaza de forma automática. | Si pasan 24 horas desde que se creó una Orden de Traslado y no se ha aprobado, la misma se |  |
|  |  |  |  | automático de |  |  | rechaza de forma automática. |  |
|  |  |  |  | una Orden de |  |  |  |  |
|  |  |  |  | Traslado |  |  |  |  |
| 8. |  |  |  | C ancelación |  | Una Orden de Traslado puede ser cancelada en tanto no se haya iniciado el traslado de los
contenedores. A partir de ese punto ya no puede ser cancelada. |  |  |
|  |  |  |  | de una Orden |  |  |  |  |
|  |  |  |  | de Traslado |  |  |  |  |


#### Tabla 3 — Página 4

| T ratamiento |
| --- |
| de un |
| Contenedor |


#### Tabla 4 — Página 4

| N otificaciones |
| --- |
| para una |
| Orden de |
| Traslado |


#### Tabla 5 — Página 4

| Una Orden de Traslado puede ser cancelada en tanto no se haya iniciado el traslado de los |
| --- |
| contenedores. A partir de ese punto ya no puede ser cancelada. |


#### Página 5

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo primer parcial
Descripción de Caso de Uso
Nombre del Caso de Uso: Generar Orden de Traslado ID: 14
Prioridad: ☒ Esencial ☐ Útil ☐ Deseable
Categoría: ☒ Esencial ☐ Soporte
Complejidad: ☐ Simple ☒ Mediano ☐ Complejo ☐ Muy Complejo ☐ Extremadamente Complejo
Actor Principal: Generador de Orden de Traslado (GOT) Actor Secundario: Servidor de Correo
Servidor de SMS - WhatsApp
Tipo de Use Case: ☒ Concreto ☐ Abstracto
Objetivo: Crear una Orden de Traslado para uno o más contenedores de una escudería
Flujo: Creación de una Orden de Traslado por un Jefe Mecánico y hay suficientes contenedores disponibles con notificación
por email.
1. GOT: Selecciona la opción para generar una Orden de Traslado.
2. Sistema: Valida si el GOT logueado es Jefe de Equipo y no lo es.
3. Sistema: Busca y muestra los circuitos activos de la F1 y la fábrica de la escudería del usuario logueado. (Leer
Observación 1). Solicita que se seleccione un origen y un destino para la OT. (Leer la RN 2 Traslados que
pueden realizarse con una OT).
4. GOT: Selecciona un origen y un destino para el traslado.
5. Sistema: Busca y muestra los elementos pertenecientes a la escudería del usuario logueado. Para cada
elemento muestra su nombre, código y tipo de elemento. Solicita que se seleccionen todos los elementos a
trasladar.
6. GOT: Selecciona cada uno de los elementos a trasladar.
7. Sistema: Calcula cuántos contenedores se necesitan para los elementos seleccionados. Verifica si hay
suficientes contenedores disponibles de la escudería y los hay. (Leer observación 2). Asigna los elementos a un
contenedor. (Leer RN 1 Contenedores que provee la FIA).
8. Sistema: Solicita que se seleccione la fecha en la que se necesitan los elementos en el destino.
9. GOT: Ingresa la fecha en la que se necesitan los elementos en el destino.
10. Sistema: Calcula la última fecha de salida posible y valida si es igual o posterior a la fecha actual y lo es. (Leer
Observaciones 3 y 7)
11. Sistema: Solicita la confirmación de la orden de traslado.
12. GOT: Confirma la orden de traslado.
13. Sistema: Genera la orden de traslado en estado Creada conteniendo los elementos que se van a trasladar y en
qué contenedor se trasladará cada elemento. Actualiza el estado de los contenedores a AsignadoAOrden (Leer
Observación 4), la fecha de llegada esperada, la última fecha de salida posible, el origen y destino, la fecha de
creación de la orden y el responsable de crearla.
14. Sistema: Valida si el Jefe de Equipo tiene formas de notificación activas y solo tiene activa la notificación vía
email. Envía un email al Jefe de Equipo indicando que se ha creado una Orden de Traslado que necesita su
aprobación, con todos los detalles de la OT. (Leer Observación 5). Fin de Caso de uso.
Flujos Alternativos
Ciclo lectivo 2026 Turnos: Todos Hoja: Página 5 de 9


#### Tabla 1 — Página 5

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo primer parcial |
| --- | --- |


#### Tabla 2 — Página 5

| Nombre del Caso de Uso: Generar Orden de Traslado |  |  | ID: 14 |
| --- | --- | --- | --- |
| Prioridad: ☒ Esencial ☐ Útil ☐ Deseable |  |  |  |
| Categoría: ☒ Esencial ☐ Soporte |  |  |  |
| Complejidad: ☐ Simple ☒ Mediano ☐ Complejo ☐ Muy Complejo ☐ Extremadamente Complejo |  |  |  |
| Actor Principal: Generador de Orden de Traslado (GOT) |  | Actor Secundario: Servidor de Correo
Servidor de SMS - WhatsApp |  |
| Tipo de Use Case: ☒ Concreto ☐ Abstracto |  |  |  |
| Objetivo: Crear una Orden de Traslado para uno o más contenedores de una escudería |  |  |  |
|  | Flujo: Creación de una Orden de Traslado por un Jefe Mecánico y hay suficientes contenedores disponibles con notificación
por email. |  |  |
| 1. GOT: Selecciona la opción para generar una Orden de Traslado. |  |  |  |
| 2. Sistema: Valida si el GOT logueado es Jefe de Equipo y no lo es. |  |  |  |
| 3. Sistema: Busca y muestra los circuitos activos de la F1 y la fábrica de la escudería del usuario logueado. (Leer
Observación 1). Solicita que se seleccione un origen y un destino para la OT. (Leer la RN 2 Traslados que
pueden realizarse con una OT). |  |  |  |
| 4. GOT: Selecciona un origen y un destino para el traslado. |  |  |  |
| 5. Sistema: Busca y muestra los elementos pertenecientes a la escudería del usuario logueado. Para cada
elemento muestra su nombre, código y tipo de elemento. Solicita que se seleccionen todos los elementos a
trasladar. |  |  |  |
| 6. GOT: Selecciona cada uno de los elementos a trasladar. |  |  |  |
| 7. Sistema: Calcula cuántos contenedores se necesitan para los elementos seleccionados. Verifica si hay
suficientes contenedores disponibles de la escudería y los hay. (Leer observación 2). Asigna los elementos a un
contenedor. (Leer RN 1 Contenedores que provee la FIA). |  |  |  |
| 8. Sistema: Solicita que se seleccione la fecha en la que se necesitan los elementos en el destino. |  |  |  |
| 9. GOT: Ingresa la fecha en la que se necesitan los elementos en el destino. |  |  |  |
| 10. Sistema: Calcula la última fecha de salida posible y valida si es igual o posterior a la fecha actual y lo es. (Leer
Observaciones 3 y 7) |  |  |  |
| 11. Sistema: Solicita la confirmación de la orden de traslado. |  |  |  |
| 12. GOT: Confirma la orden de traslado. |  |  |  |
| 13. Sistema: Genera la orden de traslado en estado Creada conteniendo los elementos que se van a trasladar y en
qué contenedor se trasladará cada elemento. Actualiza el estado de los contenedores a AsignadoAOrden (Leer
Observación 4), la fecha de llegada esperada, la última fecha de salida posible, el origen y destino, la fecha de
creación de la orden y el responsable de crearla. |  |  |  |
| 14. Sistema: Valida si el Jefe de Equipo tiene formas de notificación activas y solo tiene activa la notificación vía
email. Envía un email al Jefe de Equipo indicando que se ha creado una Orden de Traslado que necesita su
aprobación, con todos los detalles de la OT. (Leer Observación 5). Fin de Caso de uso. |  |  |  |
|  | Flujos Alternativos |  |  |


#### Página 6

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo primer parcial
A1. El Generador de OT es el Jefe de Equipo.
A2. No hay circuitos activos.
A3. No hay elementos a trasladar.
A4. No hay contenedores suficientes disponibles.
A5. No es posible enviar los elementos y que lleguen en la fecha necesaria.
A6. No confirma la Orden de Traslado.
Observaciones
1. Los circuitos activos de la F1 son aquellos que se encuentran en el calendario del año actual y asignados a un
Gran Premio.
2. Para verificar contenedores disponibles se debe ver si la cantidad de contenedores necesarios se encuentran en
estado Ocioso.
3. La última fecha de salida posible se calcula en base a la distancia del destino y del origen considerando un viaje
sin contratiempos. Es la última fecha en la que se puede enviar un contenedor desde ese origen hacia ese
destino y que lleguen para la fecha necesaria.
4. El sistema debe asignar los elementos a trasladar a un contenedor separándolos por tipo y según el espacio
disponible en cada contenedor. Si los elementos de un tipo no entran en un solo contenedor, el sistema debe
asignar algunos elementos a un contenedor y otros elementos a otro contenedor; ambos contenedores del
mismo tipo.
5. El Jefe de Equipo puede recibir notificaciones por WhatsApp, SMS y/o Mail.
6. El rol de Generador de Orden de Traslado puede asumirlo el Jefe de Mecánica o el Jefe de Equipo.
7. Para el cálculo de distancia se utilizarán las coordenadas de ubicación de la locación de origen y de la locación
de destino, ya sean Circuito y/o Fábrica.
Ciclo lectivo 2026 Turnos: Todos Hoja: Página 6 de 9


#### Tabla 1 — Página 6

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo primer parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 6

|  | Observaciones |
| --- | --- |
| 1. Los circuitos activos de la F1 son aquellos que se encuentran en el calendario del año actual y asignados a un
Gran Premio.
2. Para verificar contenedores disponibles se debe ver si la cantidad de contenedores necesarios se encuentran en
estado Ocioso.
3. La última fecha de salida posible se calcula en base a la distancia del destino y del origen considerando un viaje
sin contratiempos. Es la última fecha en la que se puede enviar un contenedor desde ese origen hacia ese
destino y que lleguen para la fecha necesaria.
4. El sistema debe asignar los elementos a trasladar a un contenedor separándolos por tipo y según el espacio
disponible en cada contenedor. Si los elementos de un tipo no entran en un solo contenedor, el sistema debe
asignar algunos elementos a un contenedor y otros elementos a otro contenedor; ambos contenedores del
mismo tipo.
5. El Jefe de Equipo puede recibir notificaciones por WhatsApp, SMS y/o Mail.
6. El rol de Generador de Orden de Traslado puede asumirlo el Jefe de Mecánica o el Jefe de Equipo.
7. Para el cálculo de distancia se utilizarán las coordenadas de ubicación de la locación de origen y de la locación
de destino, ya sean Circuito y/o Fábrica. |  |


### 🖼️ Imágenes Extraídas (12 imágenes)

#### Imagen 1 — Página 1 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 2 — Página 1 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 3 — Página 2 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 4 — Página 2 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 5 — Página 3 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 6 — Página 3 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 7 — Página 4 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 8 — Página 4 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 9 — Página 5 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 10 — Página 5 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 11 — Página 6 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 12 — Página 6 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 1 FIA Formula 1.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*



---


## DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1

**Categoría:** Parciales y Exámenes  

**Archivo:** `DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf`  

**Tamaño:** 0.35 MB  


### 📄 Contenido de Texto

#### Página 1

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo segundo parcial
Se pide al Estudiante que lea y analice atentamente la situación planteada y en base a ello
desarrolle las siguientes vistas arquitectónicas:
Consigna
1. Vista Arquitectónica de la Funcionalidad. Utilizando un diagrama de casos de uso. Justificar la elección de
los casos de uso que incluya en la vista. Para construir esta vista elija los casos de uso que considere de
los definidos en la lista de casos de uso que tiene disponible.
2. Vista Arquitectónica del Diseño (detallada). Utilizando un diagrama de componentes para modelar los
subsistemas, servicios, componentes e interfaces relevantes.
3. Vista Arquitectónica del Despliegue – Nodos y Subsistemas. Utilizando un diagrama de despliegue para
modelar la distribución del software (subsistemas y componentes) en los niveles de hardware.
Dominio: FIA Fórmula 1
Glosario
Término Descripción
AP Actor principal
AS Actor secundario
Gran Premio o Una competencia de automovilismo celebrada durante 3 días durante el fin de semana en un circuito
GP específico.
Escudería Es un equipo de pilotos con licencia para disputar la competencia de Fórmula 1. Cada escudería
cuenta con 2 pilotos titulares que corren todos los Grandes Premios.
Monoplaza Un monoplaza es el auto que utilizan los pilotos de la Fórmula 1. Llamado así porque solo hay lugar
para una sola persona
OT Orden de traslado
RE Responsable de escudería
RN Regla de negocio
La Federación Internacional del Automóvil, también llamada FIA, es una organización sin fines de lucro que reúne 268
organizaciones automovilísticas de 143 países. La FIA regula a nivel mundial las competiciones de automovilismo más
importantes del mundo, entre ellas la Fórmula 1 (también conocida como F1). Esta es la principal competición de
automovilismo internacional y el campeonato de deportes de motor más prestigioso del mundo.
La FIA requiere un software para gestionar la logística relacionada con los movimientos de las escuderías de un país
anfitrión del Gran Premio a otro.
El circuito
La competencia de Fórmula 1 es un evento anual en donde se corren distintas carreras, denominadas Gran Premio.
Cada Gran Premio se celebra en un circuito particular. Cada circuito tiene una sede (que puede ser un autódromo o un
circuito callejero), una longitud de vuelta, una distancia total, una cantidad de vueltas y una traza que indica el recorrido
que realiza. Cada circuito debe negociar con la FIA un contrato para ser parte del calendario de la Fórmula 1, dicho
contrato dura una cierta cantidad de años según las negociaciones
alcanzadas. A la FIA no le interesa que este software gestione los
pormenores del contrato con cada circuito, sólo le interesa saber si un
circuito estará disponible un año dado para armar el calendario. Por
ejemplo, el famoso Gran Premio de Italia se celebra todos los años en el
Autódromo Nazionale di Monza en Monza, Italia. Este circuito tiene una
longitud de vuelta de 5,793 kilómetros, una distancia total de 306,720
kilómetros y 53 vueltas, tiene un contrato vigente hasta el año 2035 y la
Ciclo lectivo 2026 Página 1 de 14


#### Tabla 1 — Página 1

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo segundo parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 1

| Se pide al Estudiante que lea y analice atentamente la situación planteada y en base a ello |  |  |
| --- | --- | --- |
| desarrolle las siguientes vistas arquitectónicas: |  |  |
|  | Consigna |  |
|  | 1. Vista Arquitectónica de la Funcionalidad. Utilizando un diagrama de casos de uso. Justificar la elección de |  |
|  | los casos de uso que incluya en la vista. Para construir esta vista elija los casos de uso que considere de |  |
|  | los definidos en la lista de casos de uso que tiene disponible. |  |
|  | 2. Vista Arquitectónica del Diseño (detallada). Utilizando un diagrama de componentes para modelar los |  |
|  | subsistemas, servicios, componentes e interfaces relevantes. |  |
|  | 3. Vista Arquitectónica del Despliegue – Nodos y Subsistemas. Utilizando un diagrama de despliegue para |  |
|  | modelar la distribución del software (subsistemas y componentes) en los niveles de hardware. |  |


#### Tabla 3 — Página 1

| Término | Descripción |
| --- | --- |
| AP | Actor principal |
| AS | Actor secundario |
| Gran Premio o
GP | Una competencia de automovilismo celebrada durante 3 días durante el fin de semana en un circuito
específico. |
| Escudería | Es un equipo de pilotos con licencia para disputar la competencia de Fórmula 1. Cada escudería
cuenta con 2 pilotos titulares que corren todos los Grandes Premios. |
| Monoplaza | Un monoplaza es el auto que utilizan los pilotos de la Fórmula 1. Llamado así porque solo hay lugar
para una sola persona |
| OT | Orden de traslado |
| RE | Responsable de escudería |
| RN | Regla de negocio |


#### Página 2

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo segundo parcial
traza puede verse en la imagen adjunta. En 2025 el Gran Premio de Italia se celebró el fin de semana del 5 al 7 de
septiembre.
Los monoplaza
Para cada año calendario, las escuderías presentan la versión del monoplaza que utilizarán.
Logística de las escuderías
Las escuderías requieren realizar traslados en contenedores, pudiendo
- movilizar los elementos de un Gran Premio a otro
- enviar elementos a la fábrica de cada escudería, para ser estudiados por los ingenieros
- enviar partes y herramientas nuevas desde la fábrica a los Grandes Premios.
Hay 3 tipos de elementos que las escuderías pueden desear trasladar (Ref. RN 1)
- elementos de Hospitality, que es el área designada para cada escudería donde los pilotos y el resto del equipo se
relajan antes y después de la carrera sin la intromisión de los fanáticos;
- Herramientas y piezas, que son las herramientas utilizadas para el trabajo en los monoplazas y las partes extra para
los mismo en caso de una avería o rotura;
- los Monoplazas, siendo que cada monoplaza entra en un contenedor.
La FIA entrega hasta 10 contenedores a cada escudería. La FIA instala un tracker GPS en cada contenedor para saber a
dónde se encuentra en todo momento, y los programa con un código alfanumérico único para distinguirlos fácilmente.
Este código alfanumérico comienza con las 3 letras que identifican a la escudería y continua con un número. Por ejemplo,
los contenedores de Ferrari tienen códigos “FER-1”, “FER-2”, “FER-3” y así sucesivamente a medida que se registran
contenedores nuevos.
Según las reglas de la FIA, cada contenedor puede contener un tipo de elemento a la vez.
Para trasladar los elementos de un lugar a otro, la FIA utiliza órdenes de traslado.
Creador de las órdenes de traslado
Las OT pueden ser creadas por el Jefe de Equipo o por alguno de los Jefes de Mecánica de las escuderías (Ref. RN 2 y
RN 3).
Qué se incluye en una orden de traslado
Para cada OT se debe especificar
- Su lugar de origen y su lugar de destino. Estos lugares de origen y destino pueden ser algún circuito en particular
o la fábrica de la escudería, según lo mencionado más arriba.
- La fecha en que se necesita que los contenedores arriben a destino
- Los elementos que deben enviarse.
Armado y traslado de los contenedores
Una vez que la orden es aprobada, se comienzan a armar los contenedores para su envío. Mientras los contenedores
están en traslado, se debe conocer su ubicación en todo momento mediante un mapa que muestre dónde está cada
contenedor, mostrando para cada uno una etiqueta con su código único y el tipo de elementos que lleva. Si Ferrari enviase
las herramientas a utilizar para el próximo Gran Premio, el mapa debería mostrar una etiqueta que diga “FER-1,
Herramientas”.
Arribo y control de los contenedores
Una vez que llegan al destino, el Encargado de Logística del lugar de destino (próximo Grand Premio o Fábrica) revisa
cada contenedor para determinar si contiene todo lo indicado en la OT, y que no tenga roturas, abolladuras u otros
inconvenientes.
Se debe controlar el estado en el que los contenedores llegan a destino antes de cerrar la OT.
Ciclo lectivo 2026 Página 2 de 14


#### Tabla 1 — Página 2

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo segundo parcial |  |
| --- | --- | --- |


#### Página 3

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo segundo parcial
Los delegados de la FIA deben poder visualizar dónde se encuentran los contenedores de todas las escuderías, mientras
que el Jefe de Equipo y los ingenieros de una escudería solo pueden ver la ubicación de sus propios contenedores.
Se desea que el sistema genere estadísticas sobre tiempos promedios de las OT en cada estado.
Notificaciones relacionadas a OT
Como puede observarse en la tabla del calendario mostrado arriba, a veces los Grandes Premios son en países lejanos
entre sí en dos fines de semana consecutivos, como por ejemplo el Gran Premio de Las Vegas que se celebra del 20 al 22
de noviembre y el Gran Premio de Qatar que se celebra el fin de semana siguiente, desde el 28 al 30 de noviembre. Dadas
estas condiciones, existe una alta urgencia para la resolución de las órdenes de traslado, debiendo notificarse vía mail al
Jefe de Equipo cada vez que un Jefe de Mecánica registre una Orden de Traslado. Si no se ha aprobado dentro de las 12
horas de su creación, debe volver a notificar por el mismo medio. Si pasan 24 horas desde que se creó la orden y no se
ha aprobado, la misma se rechaza de forma automática.
Cuando se aprueba una orden se debe enviar una notificación por mail al encargado de logística para que los
contenedores sean armados dentro de las 12 horas de la aprobación de la orden. Una orden puede ser cancelada por el
Jefe de Equipo o por el Ingeniero que la creó, en tanto no se encuentre en traslado.
Definición del producto de software a construir
Objetivo
Gestionar la logística de traslado de elementos de escudería de un lugar a otro, generando información
relacionada.
Alcances del producto de software
● Administración de escuderías y monoplazas
● Administración de grandes premios
● Administración de usuarios
● Gestión de Órdenes de Traslado
● Administración de contenedores
● Generación de reportes de logística de contenedores
No contempla
● Administración de pilotos
● Gestión del calendario de carreras
● Gestión de Contratos de los circuitos
● Administracion de neumáticos Pirelli
● Administración de paquetes de mejoras
Ciclo lectivo 2026 Página 3 de 14


#### Tabla 1 — Página 3

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo segundo parcial |  |
| --- | --- | --- |


#### Página 4

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo segundo parcial
Reglas de negocio para el producto de software
Nombre de la RN Descripción de la RN
1. Tipos de elemento Cada contenedor puede contener un tipo de elemento a la vez. Por ejemplo, no pueden
en un contenedor mezclarse elementos del Hospitality con Herramientas y piezas en un mismo contenedor.
2. Jefes por Cada escudería puede tener múltiples Jefes de mecánica que lideran diversos equipos de
escudería ingeniería, pero solo un Jefe de Equipo.
3. Aprobación de una Cuando una OT la crea un Jefe de mecánica, debe ser aprobada por el Jefe de equipo.
OT El Jefe de Equipo puede aprobar una OT creada por un jefe de mecánica o puede rechazarla
si no está de acuerdo con el destino de la orden.
Casos de Uso
Nota: Los casos de uso incluidos son suficientes para construir la vista arquitectónica de la funcionalidad.
Nº Nombre del Caso de Objetivo / Breve Descripción Actores
Uso
1. Reg istrar circuito Registrar un circuito, incluyendo las fechas de vigencia del AP: Administrador FIA
contrato asociado.
2. Mo dificar circuito Actualizar los datos permitidos de un circuito. AP: Administrador FIA
3. Con sultar circuito Visualizar la información de un circuito. AP: Administrador FIA
4. Elim inar circuito Dar de baja un circuito. AP: Administrador FIA
5. Reg istrar escudería Registrar una escudería que competirá en los distintos GP AP: Administrador FIA
programados, incluyendo información de su fábrica.
6. Mo dificar escudería Actualizar los datos permitidos de una escudería. AP: Administrador FIA
7. Con sultar escudería Visualizar la información general de una escudería. AP: Administrador FIA
8. Elim inar escudería Dar de baja una escudería que ya no participe en el AP: Administrador FIA
campeonato.
9. Reg istrar monoplaza Registrar el monoplaza que utilizará una escudería en la AP: Responsable de
temporada, indicando su versión, motor y componentes escudería
principales.
10. Mo dificar monoplaza Actualizar datos permitidos de un monoplaza. AP: Responsable de
escudería
11. Con sultar monoplaza Visualizar información de los monoplazas, incluyendo su AP: Responsable de
escudería y su historial de componentes. escudería
12. Reg istrar baja de Dar de baja un monoplaza perteneciente a una escudería. AP: Responsable de
monoplaza escudería
13. Reg istrar entrega de Registrar la entrega de contenedor/es a una escudería, AP: Administrador FIA
contenedor a asociando el código del tracker GPS instalado en cada uno.
escudería
14. Gen erar Orden de Registrar una orden de traslado para el envío de elementos, AP: Creador de OT
Traslado determinando automáticamente la cantidad de A S: Servidor de Correo
contenedores y la fecha en la que deben salir del origen para
llegar al destino a tiempo.
15. Reg istrar evaluación Visualizar y registrar el resultado del análisis de la OT por AP: Jefe de equipo
de OT parte del Jefe de equipo.
16. Pro cesar OT no Determinar las OT que no fueron analizadas por el Jefe de AP: No aplica
analizadas equipo en los períodos establecidos y proceder a la AS: Servidor de Correo
notificación al Jefe de equipo o al rechazo de la OT.
Notificando la acción correspondiente.
Ciclo lectivo 2026 Página 4 de 14


#### Tabla 1 — Página 4

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo segundo parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 4

| Nombre de la RN | Descripción de la RN |
| --- | --- |
| 1. Tipos de elemento
en un contenedor | Cada contenedor puede contener un tipo de elemento a la vez. Por ejemplo, no pueden
mezclarse elementos del Hospitality con Herramientas y piezas en un mismo contenedor. |
| 2. Jefes por
escudería | Cada escudería puede tener múltiples Jefes de mecánica que lideran diversos equipos de
ingeniería, pero solo un Jefe de Equipo. |
| 3. Aprobación de una
OT | Cuando una OT la crea un Jefe de mecánica, debe ser aprobada por el Jefe de equipo.
El Jefe de Equipo puede aprobar una OT creada por un jefe de mecánica o puede rechazarla
si no está de acuerdo con el destino de la orden. |


#### Tabla 3 — Página 4

| Nº | Nombre del Caso de
Uso | Objetivo / Breve Descripción | Actores |
| --- | --- | --- | --- |
| 1. | Reg istrar circuito | Registrar un circuito, incluyendo las fechas de vigencia del
contrato asociado. | AP: Administrador FIA |
| 2. | Mo dificar circuito | Actualizar los datos permitidos de un circuito. | AP: Administrador FIA |
| 3. | Con sultar circuito | Visualizar la información de un circuito. | AP: Administrador FIA |
| 4. | Elim inar circuito | Dar de baja un circuito. | AP: Administrador FIA |
| 5. | Reg istrar escudería | Registrar una escudería que competirá en los distintos GP
programados, incluyendo información de su fábrica. | AP: Administrador FIA |
| 6. | Mo dificar escudería | Actualizar los datos permitidos de una escudería. | AP: Administrador FIA |
| 7. | Con sultar escudería | Visualizar la información general de una escudería. | AP: Administrador FIA |
| 8. | Elim inar escudería | Dar de baja una escudería que ya no participe en el
campeonato. | AP: Administrador FIA |
| 9. | Reg istrar monoplaza | Registrar el monoplaza que utilizará una escudería en la
temporada, indicando su versión, motor y componentes
principales. | AP: Responsable de
escudería |
| 10. | Mo dificar monoplaza | Actualizar datos permitidos de un monoplaza. | AP: Responsable de
escudería |
| 11. | Con sultar monoplaza | Visualizar información de los monoplazas, incluyendo su
escudería y su historial de componentes. | AP: Responsable de
escudería |
| 12. | Reg istrar baja de
monoplaza | Dar de baja un monoplaza perteneciente a una escudería. | AP: Responsable de
escudería |
| 13. | Reg istrar entrega de
contenedor a
escudería | Registrar la entrega de contenedor/es a una escudería,
asociando el código del tracker GPS instalado en cada uno. | AP: Administrador FIA |
| 14. | Gen erar Orden de
Traslado | Registrar una orden de traslado para el envío de elementos,
determinando automáticamente la cantidad de
contenedores y la fecha en la que deben salir del origen para
llegar al destino a tiempo. | AP: Creador de OT
A S: Servidor de Correo |
| 15. | Reg istrar evaluación
de OT | Visualizar y registrar el resultado del análisis de la OT por
parte del Jefe de equipo. | AP: Jefe de equipo |
| 16. | Pro cesar OT no
analizadas | Determinar las OT que no fueron analizadas por el Jefe de
equipo en los períodos establecidos y proceder a la
notificación al Jefe de equipo o al rechazo de la OT.
Notificando la acción correspondiente. | AP: No aplica
AS: Servidor de Correo |


#### Página 5

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo segundo parcial
Nº Nombre del Caso de Objetivo / Breve Descripción Actores
Uso
17. Con sultar Órdenes de Visualizar las órdenes de traslado activas y su estado. AP: Jefe de equipo
Traslado
18. Reg istrar armado de Registrar el armado de cada contenedor incluido en una OT, AP: Encargado de
contenedores de OT procediendo a marcar esta como Lista para envío una vez Logística
que todos los contenedores fueron armados.
19. Mo nitorear ubicación Consultar la ubicación actual de los contenedores utilizando AP: Consultor de mapa
de contenedores los datos de geolocalización de cada uno. de contenedores
(actores hijo:
Administrador FIA,
Ingeniero de
escudería)
AS: GPS Tracker
20. Reg istrar llegada de Registrar la llegada a destino de los contenedores de una OT, AP: Encargado de
contenedores a indicando el resultado del control del contenido y el estado Logística
destino de cada uno.
21. Reg istrar cancelación Registrar la cancelación de una OT mientras no se haya AP: Creador de OT
de OT iniciado el traslado de los contenedores vinculados.
22. Inic iar sesión Validar credenciales del usuario y habilitar el acceso al AP: Usuario
sistema.
23. Cer rar sesión Finalizar la sesión activa del usuario. AP: Usuario
24. Em itir reporte de Generar reportes con el detalle de órdenes, contenedores y AP: Administrador FIA
traslados fechas, y tiempos promedios por estado.
25. Reg istrar inicio de Registrar el comienzo de la preparación de los contenedores AP: Encargado de
preparación de que integran una OT. Logística
contenedores de una
OT
26. Info rmar el inicio del Se registra día y hora de inicio del traslado de los AP: Encargado de
traslado de contenedores que integran una Orden de Traslado. Logística
contenedores de una
OT
27. Reg istrar revisión de Registrar la revisión de cada contenedor de una OT para AP: Encargado de
contenedores de una verificar que contiene todo lo que se solicitó y que esté en las Logística
OT condiciones adecuadas.
Ciclo lectivo 2026 Página 5 de 14


#### Tabla 1 — Página 5

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo segundo parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 5

| Nº | Nombre del Caso de
Uso | Objetivo / Breve Descripción | Actores |
| --- | --- | --- | --- |
| 17. | Con sultar Órdenes de
Traslado | Visualizar las órdenes de traslado activas y su estado. | AP: Jefe de equipo |
| 18. | Reg istrar armado de
contenedores de OT | Registrar el armado de cada contenedor incluido en una OT,
procediendo a marcar esta como Lista para envío una vez
que todos los contenedores fueron armados. | AP: Encargado de
Logística |
| 19. | Mo nitorear ubicación
de contenedores | Consultar la ubicación actual de los contenedores utilizando
los datos de geolocalización de cada uno. | AP: Consultor de mapa
de contenedores
(actores hijo:
Administrador FIA,
Ingeniero de
escudería)
AS: GPS Tracker |
| 20. | Reg istrar llegada de
contenedores a
destino | Registrar la llegada a destino de los contenedores de una OT,
indicando el resultado del control del contenido y el estado
de cada uno. | AP: Encargado de
Logística |
| 21. | Reg istrar cancelación
de OT | Registrar la cancelación de una OT mientras no se haya
iniciado el traslado de los contenedores vinculados. | AP: Creador de OT |
| 22. | Inic iar sesión | Validar credenciales del usuario y habilitar el acceso al
sistema. | AP: Usuario |
| 23. | Cer rar sesión | Finalizar la sesión activa del usuario. | AP: Usuario |
| 24. | Em itir reporte de
traslados | Generar reportes con el detalle de órdenes, contenedores y
fechas, y tiempos promedios por estado. | AP: Administrador FIA |
| 25. | Reg istrar inicio de
preparación de
contenedores de una
OT | Registrar el comienzo de la preparación de los contenedores
que integran una OT. | AP: Encargado de
Logística |
| 26. | Info rmar el inicio del
traslado de
contenedores de una
OT | Se registra día y hora de inicio del traslado de los
contenedores que integran una Orden de Traslado. | AP: Encargado de
Logística |
| 27. | Reg istrar revisión de
contenedores de una
OT | Registrar la revisión de cada contenedor de una OT para
verificar que contiene todo lo que se solicitó y que esté en las
condiciones adecuadas. | AP: Encargado de
Logística |


#### Página 6

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo segundo parcial
Requerimientos No Funcionales
Los requerimientos no funcionales significativos para la arquitectura son
Nombre Descripción Justificación
1. Sistema web La aplicación debe ser programada con El Lenguaje de Programación a utilizar deberá
tecnología Web. La aplicación web se soportar desarrollo web y ser compatible con
utilizará para gestionar la logística plataforma HTML 5, buscando que sea
relacionada con los movimientos de las responsive con el fin de utilizarse en diversos
escuderías de un país anfitrión del Gran dispositivos.
Premio a otro.
2. Alta A los fines de asegurar alta disponibilidad Se requiere replicación a nivel de la base de
disponibilidad (7x24x365) solicitada para el sistema se datos de todos los servicios, configurando una
del servicio requiere la utilización de bases de datos réplica alojada en su servidor dedicado, para
espejadas (Database Mirroring) para todos garantizar disponibilidad sin depender de otros
los servicios. microservicios.
3. Servicio en la La solución se ofrecerá como servicio SaaS y Se requiere que el sistema se realice en un
nube Tecnología Cloud. lenguaje web y distribuido para ser ejecutado en
la nube y accedido desde cualquier ubicación
con conexión a Internet. El despliegue será
alojando todos los servicios en un mismo
servidor.
4. Seguridad de El sistema debe permitir la administración de Implica desarrollar un módulo para la
usuarios usuarios y sesiones. autenticación y autorización de usuarios y la
gestión de sus sesiones.
5. Notificaciones La aplicación permitirá enviar notificaciones Se deberá desarrollar un componente que
por Correo vía mail al Jefe de Equipo cada vez que un genere y resuelva el envío de notificaciones vía
Jefe de Mecánica registre una Orden de Correo. Se utilizará la API que provee Google
Traslado. para enviar correos.
6. Interfaz con El sistema utiliza el sistema de Se debe desarrollar una interfaz que integre los
GPS geoposicionamiento de los contenedores servicios de localización GPS del contenedor,
para ubicarlos en todo momento. permitiendo obtener en tiempo real las
coordenadas del contenedor.
7. Interfaz con El sistema debe establecer una interfaz con Es necesario resolver la forma de comunicación
Google Maps Google Maps para mostrar en tiempo real la con Google Maps para visualizar un mapa que
ubicación de un contenedor. muestre en tiempo real la ubicación de un
contenedor. Para esto se integrará una librería
que provee Google Maps, que es la que se
comunica con la API de Google Maps que brinda
el servicio.
Ciclo lectivo 2026 Página 6 de 14


#### Tabla 1 — Página 6

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo segundo parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 6

| Nombre | Descripción | Justificación |
| --- | --- | --- |
| 1. Sistema web | La aplicación debe ser programada con
tecnología Web. La aplicación web se
utilizará para gestionar la logística
relacionada con los movimientos de las
escuderías de un país anfitrión del Gran
Premio a otro. | El Lenguaje de Programación a utilizar deberá
soportar desarrollo web y ser compatible con
plataforma HTML 5, buscando que sea
responsive con el fin de utilizarse en diversos
dispositivos. |
| 2. Alta
disponibilidad
del servicio | A los fines de asegurar alta disponibilidad
(7x24x365) solicitada para el sistema se
requiere la utilización de bases de datos
espejadas (Database Mirroring) para todos
los servicios. | Se requiere replicación a nivel de la base de
datos de todos los servicios, configurando una
réplica alojada en su servidor dedicado, para
garantizar disponibilidad sin depender de otros
microservicios. |
| 3. Servicio en la
nube | La solución se ofrecerá como servicio SaaS y
Tecnología Cloud. | Se requiere que el sistema se realice en un
lenguaje web y distribuido para ser ejecutado en
la nube y accedido desde cualquier ubicación
con conexión a Internet. El despliegue será
alojando todos los servicios en un mismo
servidor. |
| 4. Seguridad de
usuarios | El sistema debe permitir la administración de
usuarios y sesiones. | Implica desarrollar un módulo para la
autenticación y autorización de usuarios y la
gestión de sus sesiones. |
| 5. Notificaciones
por Correo | La aplicación permitirá enviar notificaciones
vía mail al Jefe de Equipo cada vez que un
Jefe de Mecánica registre una Orden de
Traslado. | Se deberá desarrollar un componente que
genere y resuelva el envío de notificaciones vía
Correo. Se utilizará la API que provee Google
para enviar correos. |
| 6. Interfaz con
GPS | El sistema utiliza el sistema de
geoposicionamiento de los contenedores
para ubicarlos en todo momento. | Se debe desarrollar una interfaz que integre los
servicios de localización GPS del contenedor,
permitiendo obtener en tiempo real las
coordenadas del contenedor. |
| 7. Interfaz con
Google Maps | El sistema debe establecer una interfaz con
Google Maps para mostrar en tiempo real la
ubicación de un contenedor. | Es necesario resolver la forma de comunicación
con Google Maps para visualizar un mapa que
muestre en tiempo real la ubicación de un
contenedor. Para esto se integrará una librería
que provee Google Maps, que es la que se
comunica con la API de Google Maps que brinda
el servicio. |


### 🖼️ Imágenes Extraídas (13 imágenes)

#### Imagen 1 — Página 1 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 2 — Página 1 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 3 — Página 1 (9.0 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 4 — Página 2 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 5 — Página 2 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 6 — Página 3 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 7 — Página 3 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 8 — Página 4 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 9 — Página 4 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 10 — Página 5 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 11 — Página 5 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 12 — Página 6 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 13 — Página 6 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 2 FIA Formula 1.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*



---


## DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1

**Categoría:** Parciales y Exámenes  

**Archivo:** `DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`  

**Tamaño:** 1.53 MB  


### 📄 Contenido de Texto

#### Página 1

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial
Se pide al Estudiante que lea y analice atentamente la situación planteada y en base a ello:
Rediseñe la realización de caso de uso de análisis presentada aplicando los patrones de diseño adecuados a
cada situación, para resolver las siguientes problemáticas de diseño:
1. Utilizando el patrón Observer, diseñar una manera flexible de informar al Jefe de Equipo
cuando se registra una nueva Orden de Traslado. Modelar la dinámica relacionada al
escenario del caso de uso descripto.
2. Diseñar una forma de implementar un mecanismo que permita modificar el comportamiento
variable de la clase Orden de Traslado, de acuerdo con la situación en la que se encuentra.
Modelar la dinámica relacionada al escenario del caso de uso descripto.
Para los puntos 1 y 2, se espera que el estudiante plantee:
Consigna
A. La vista de diseño de la estructura utilizando un diagrama de clases que incluya la signatura
completa de los métodos utilizados y la especificación completa de los atributos, que
muestre el rediseño resultante de la aplicación del patrón que resuelve el problema de
diseño.
B. La vista dinámica utilizando un diagrama de secuencia, que modele el comportamiento
resultante al rediseño aplicando el patrón.
C. La especificación del comportamiento de los métodos utilizados en la dinámica con una
descripción textual o pseudocódigo
Ciclo lectivo 2026 Turnos: Todos Hoja: Página 1 de 15


#### Tabla 1 — Página 1

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 1

| 1. Utilizando el patrón Observer, diseñar una manera flexible de informar al Jefe de Equipo
cuando se registra una nueva Orden de Traslado. Modelar la dinámica relacionada al
escenario del caso de uso descripto. |
| --- |
| 2. Diseñar una forma de implementar un mecanismo que permita modificar el comportamiento
variable de la clase Orden de Traslado, de acuerdo con la situación en la que se encuentra.
Modelar la dinámica relacionada al escenario del caso de uso descripto. |


#### Tabla 3 — Página 1

| Consigna |
| --- |
| A. La vista de diseño de la estructura utilizando un diagrama de clases que incluya la signatura
completa de los métodos utilizados y la especificación completa de los atributos, que
muestre el rediseño resultante de la aplicación del patrón que resuelve el problema de
diseño. |
| B. La vista dinámica utilizando un diagrama de secuencia, que modele el comportamiento
resultante al rediseño aplicando el patrón. |
| C. La especificación del comportamiento de los métodos utilizados en la dinámica con una
descripción textual o pseudocódigo |


#### Página 2

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial
Dominio: FIA Formula 1
Glosario
Concepto Definición
Gran Premio, GP, Una competencia de automovilismo celebrada durante un fin de semana en un circuito
Grand Prix específico.
Escudería Es un equipo de pilotos con licencia para disputar la competencia de Fórmula 1. Cada
escudería cuenta con 2 pilotos titulares que corren todos los Grandes Premios.
Monoplaza Un monoplaza es el auto que utilizan los pilotos de la Fórmula 1. Llamado así porque solo
hay lugar para una sola persona.
F1 Acrónimo de Fórmula 1.
FIA Acrónimo de Federación Internacional del Automóvil.
GP Acrónimo de Gran Premio.
Grand Prix Gran Premio.
Tracker GPS Rastreador GPS.
OT Orden de traslado
Descripción del Dominio
La Federación Internacional del Automóvil, también llamada FIA, es una organización sin fines de lucro que reúne
268 organizaciones automovilísticas de 143 países. La FIA regula a nivel mundial las competiciones de automovilismo más
importantes del mundo entre ellas la Fórmula 1. La Fórmula 1, también conocida como F1, es conocida como la
“competición reina del automovilismo” y es la principal competición de automovilismo internacional y el campeonato de
deportes de motor más prestigioso del mundo. La FIA requiere un software para gestionar la organización de la
competencia de forma exitosa.
La competencia de Fórmula 1 es un evento anual en donde se corren distintas carreras, denominadas Gran Premio
o GP. La FIA anuncia el Calendario de Carreras de la Fórmula 1 para ese año, que incluye las fechas de los Grandes Premios,
determinando donde se correrá y cuando.
Cada Grand Prix se celebra en un circuito particular, cada circuito tiene una sede (que puede ser un autódromo o
un circuito callejero), una longitud de vuelta, una distancia total, una cantidad de vueltas y una traza que indica el
recorrido que realiza. Cada circuito debe negociar con la FIA un contrato para ser parte del calendario de la Fórmula 1,
dicho contrato dura una cierta cantidad de años según las negociaciones alcanzadas, dependiendo si el circuito es popular
entre los fanáticos y es un circuito histórico puede ser un contrato año a año o incluso a 10 o 20 años. A la FIA le interesa
saber si un circuito estará disponible un año dado para armar el calendario. Por ejemplo, el famoso Gran Premio de Italia
se celebra todos los años en el Autódromo Nazionale di Monza en Monza, Italia. Este circuito tiene una longitud de vuelta
de 5,793 kilómetros, una distancia total de 306,720 kilómetros y 53 vueltas y la traza puede verse en la imagen adjunta.
En el 2025, el Gran Premio de Italia se celebra el fin de semana del 5 al 7 de septiembre y tiene un contrato vigente hasta
el año 2035. Cuando la FIA anuncia un calendario debe anunciar el Gran Premio que se correrá, la fecha del fin de semana
y debe decidir en qué orden se correrán los Grandes Premios.
La FIA quiere que el producto de software que ayude con el armado del calendario y el mantenimiento de la
información de los campeonatos en curso y pasados, y quiere que las distintas escuderías utilicen este software para la
logística relacionada a moverse de un país anfitrión de Gran Premio a otro. Hay 3 tipos de elementos que las escuderías
pueden desear trasladar: elementos de “Hospitality”, que es el área designada para cada escudería donde los pilotos y el
resto del equipo se relajan antes y después de la carrera sin la intromisión de los fanáticos; “Herramientas y piezas”, que
Ciclo lectivo 2026 Turnos: Todos Hoja: Página 2 de 15


#### Tabla 1 — Página 2

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 2

|  | Concepto |  |  | Definición |  |
| --- | --- | --- | --- | --- | --- |
| Gran Premio, GP,
Grand Prix | Gran Premio, GP, |  |  | Una competencia de automovilismo celebrada durante un fin de semana en un circuito |  |
|  | Grand Prix |  |  | específico. |  |
|  |  |  |  |  |  |
| Escudería |  |  |  | Es un equipo de pilotos con licencia para disputar la competencia de Fórmula 1. Cada |  |
|  |  |  |  | escudería cuenta con 2 pilotos titulares que corren todos los Grandes Premios. |  |
| Monoplaza |  |  |  | Un monoplaza es el auto que utilizan los pilotos de la Fórmula 1. Llamado así porque solo |  |
|  |  |  |  | hay lugar para una sola persona. |  |
|  | F1 |  |  | Acrónimo de Fórmula 1. |  |
|  | FIA |  |  | Acrónimo de Federación Internacional del Automóvil. |  |
|  | GP |  |  | Acrónimo de Gran Premio. |  |
|  | Grand Prix |  |  | Gran Premio. |  |
|  | Tracker GPS |  |  | Rastreador GPS. |  |
|  | OT |  |  | Orden de traslado |  |


#### Página 3

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial
son las herramientas utilizadas para el trabajo en los monoplazas y las partes extra para los mismo en caso de una avería
o rotura; y finalmente los “Monoplazas”, siendo que cada monoplaza entra en un contenedor. Para trasladar los
elementos de un lugar a otro, la FIA utiliza órdenes de traslado.
Estas órdenes de traslado pueden realizarse para trasladar los elementos desde un circuito de un Grand Prix a
otro o pueden utilizarse para enviar elementos a la fábrica de cada escudería, para ser estudiados por los ingenieros, o
desde la fábrica para enviar partes y herramientas nuevas a un circuito de un Grand Prix. La FIA da hasta 10 contenedores
para cada escudería y además de esto, la FIA instala un rastreador en cada contenedor para saber a dónde se encuentra
en todo momento, y los programa con un código alfanumérico único para distinguirlos fácilmente.
Para cada Orden de Traslado se debe especificar su lugar de origen y su lugar de destino. Estos lugares de origen
y destino pueden ser algún circuito en particular o la fábrica de la escudería. Quien crea la Orden de Traslado debe
especificar la fecha en la que se necesita que los contenedores lleguen al destino. También debe especificarse los
elementos que deben enviarse en la Orden de Traslado, eligiendo los elementos correspondientes.
Definición del Producto de Software a construir:
Objetivo del Producto de Software:
Gestionar el calendario de carreras, el campeonato de constructores y el campeonato de pilotos y la
logística de traslado de elementos de escudería de un lugar a otro, generando información relacionada a la
logística y a los campeonatos.
Alcances del producto de software:
● Gestión del calendario de carreras
● Administración de escuderías y pilotos de las escuderías
● Administración de usuarios
● Gestión de Órdenes de Traslado
● Administración de Contenedores
● Generación de reportes de campeonatos y logística de contenedores
No contempla:
● Gestión de Contratos de los circuitos
● Administracion de neumáticos Pirelli
● Administración de paquetes de mejoras
Reglas de Negocio
Nro. Nombre de la Descripción
RN RN
1. C ontenedores Según las reglas de la FIA, cada contenedor puede contener un tipo de elemento a la vez. Por
que provee la ejemplo, no pueden mezclarse elementos del Hospitality con herramientas en un mismo
FIA contenedor que será asignado a una OT.
2. T raslados que Se pueden realizar traslados de elementos desde de un circuito de un Grand Prix a otro; desde
pueden un circuito de un Grand Prix a la fábrica de cada escudería; o desde la fábrica a un circuito de
un Grand Prix.
Ciclo lectivo 2026 Turnos: Todos Hoja: Página 3 de 15


#### Tabla 1 — Página 3

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 3

|  | Nro. |  |  | Nombre de la |  | Descripción |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  | RN |  |  | RN |  |  |  |  |
| 1. | 1. |  |  | C ontenedores |  |  | Según las reglas de la FIA, cada contenedor puede contener un tipo de elemento a la vez. Por |  |
|  |  |  |  | que provee la |  |  | ejemplo, no pueden mezclarse elementos del Hospitality con herramientas en un mismo |  |
|  |  |  |  | FIA |  |  | contenedor que será asignado a una OT. |  |
| 2. |  |  | T raslados que
pueden | T raslados que |  |  | Se pueden realizar traslados de elementos desde de un circuito de un Grand Prix a otro; desde |  |
|  |  |  |  | pueden |  |  | un circuito de un Grand Prix a la fábrica de cada escudería; o desde la fábrica a un circuito de |  |
|  |  |  |  |  |  |  | un Grand Prix. |  |


#### Página 4

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial
Nro. Nombre de la Descripción
RN RN
realizarse con
una OT
3. P reparación y Cuando la FIA termina de preparar los contenedores, los marca como Preparados para
entrega de Escudería hasta que sean entregados. Cuando son entregados, los contenedores se marcan
Contenedores como Ociosos hasta que se los asigne a una Orden de Traslado, quedando allí en estado
Asignado a OT.
4. T ratamiento Una Orden de Traslado puede ser creada por el Jefe de Equipo o por alguno de los Jefes de
de una Orden Mecánica de las escuderías.
de Traslado Si a una Orden de Traslado la crea un Jefe de Mecánica, debe ser aprobada por el Jefe de Equipo.
Si la Orden de Traslado la crea un Jefe de Equipo queda aprobada directamente.
El Jefe de Equipo puede aprobar una Orden de Traslado creada por un Jefe de Mecánica o puede
rechazarla, si no está de acuerdo con el destino de la orden. Una vez que la Orden de Traslado
está aprobada, comienza la preparación de la Orden de Traslado, lo que implica el inicio del
armado de los contenedores.
Cuando se finaliza el armado de un contenedor, este se marca como Armado. Cuando el
Encargado de Logística finaliza el armado de todos los contenedores de una Orden de Traslado,
marca esa Orden de Traslado como Lista para envío. Cuando los contenedores se envían a su
lugar de destino, se debe marcar la Orden de Traslado y los contenedores como En Traslado.
5. T ratamiento Cuando el/los contenedor/es llegan a destino se marcan como Para Verificar y la Orden de
de un Traslado debe quedar En Destino. El Encargado de Logística del lugar de destino (Próximo Grand
Contenedor Prix o Fábrica) debe revisar cada contenedor para ver si contiene todo lo que se solicitó
originalmente, y ver que no tenga roturas, abolladuras u otros inconvenientes.
Si los contenedores tienen todo lo que se pidió y están en buenas condiciones, la Orden de
Traslado se actualiza a Exitosa y el contenedor se actualiza a Ocioso. Si algún contenedor de
una orden de traslado está incompleto, se debe marcar la orden de traslado como Incompleta
y se debe crear una nueva Orden de Traslado solicitando lo que falta, marcando al contenedor
como Ocioso también en este caso.
Independientemente de si llega todo lo pedido en la Orden de Traslado o no, si el contenedor
tiene algún tipo de problema o daño, se lo marca como Dañado para que se le realice una
inspección. Si los daños no son sustanciales y no comprometen la integridad del contenedor, se
lo marca como Ocioso, en caso contrario se lo da De baja.
6. N otificaciones Se debe notificar vía mail WhatsApp y/o SMS al Jefe de Equipo cada vez que un Jefe de Mecánica
para una crear una Orden de Traslado.
Orden de Si no se ha aprobado la Orden de Traslado dentro de las 12 horas de su creación, se deben
Traslado enviar las notificaciones nuevamente.
Cuando se aprueba una Orden de Traslado se deberá enviar una notificación al Encargado de
Logística asignado de armar los contenedores para que sean armados dentro de las 12 horas
de la aprobación de la Orden de Traslado.
7. R echazo Si pasan 24 horas desde que se creó una Orden de Traslado y no se ha aprobado, la misma se
automático de rechaza de forma automática.
una Orden de
Traslado
8. C ancelación Una Orden de Traslado puede ser cancelada en tanto no se haya iniciado el traslado de los
de una Orden contenedores. A partir de ese punto ya no puede ser cancelada.
de Traslado
Ciclo lectivo 2026 Turnos: Todos Hoja: Página 4 de 15


#### Tabla 1 — Página 4

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 4

|  | Nro. |  |  | Nombre de la |  | Descripción |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  | RN |  |  | RN |  |  |  |  |
|  |  |  |  | realizarse con |  |  |  |  |
|  |  |  |  | una OT |  |  |  |  |
| 3. |  |  | P reparación y
entrega de
Contenedores | P reparación y |  |  | Cuando la FIA termina de preparar los contenedores, los marca como Preparados para |  |
|  |  |  |  | entrega de |  |  | Escudería hasta que sean entregados. Cuando son entregados, los contenedores se marcan |  |
|  |  |  |  | Contenedores |  |  | como Ociosos hasta que se los asigne a una Orden de Traslado, quedando allí en estado |  |
|  |  |  |  |  |  |  | Asignado a OT. |  |
| 4. |  |  | T ratamiento
de una Orden
de Traslado |  |  |  | Una Orden de Traslado puede ser creada por el Jefe de Equipo o por alguno de los Jefes de |  |
|  |  |  |  |  |  |  | Mecánica de las escuderías. |  |
|  |  |  |  |  |  |  | Si a una Orden de Traslado la crea un Jefe de Mecánica, debe ser aprobada por el Jefe de Equipo. |  |
|  |  |  |  |  |  |  | Si la Orden de Traslado la crea un Jefe de Equipo queda aprobada directamente. |  |
|  |  |  |  |  |  |  | El Jefe de Equipo puede aprobar una Orden de Traslado creada por un Jefe de Mecánica o puede |  |
|  |  |  |  |  |  |  | rechazarla, si no está de acuerdo con el destino de la orden. Una vez que la Orden de Traslado |  |
|  |  |  |  |  |  |  | está aprobada, comienza la preparación de la Orden de Traslado, lo que implica el inicio del |  |
|  |  |  |  |  |  |  | armado de los contenedores. |  |
|  |  |  |  |  |  |  | Cuando se finaliza el armado de un contenedor, este se marca como Armado. Cuando el |  |
|  |  |  |  |  |  |  | Encargado de Logística finaliza el armado de todos los contenedores de una Orden de Traslado, |  |
|  |  |  |  |  |  |  | marca esa Orden de Traslado como Lista para envío. Cuando los contenedores se envían a su |  |
|  |  |  |  |  |  |  | lugar de destino, se debe marcar la Orden de Traslado y los contenedores como En Traslado. |  |
| 5. |  |  | T ratamiento
de un
Contenedor |  |  |  | Cuando el/los contenedor/es llegan a destino se marcan como Para Verificar y la Orden de |  |
|  |  |  |  |  |  |  | Traslado debe quedar En Destino. El Encargado de Logística del lugar de destino (Próximo Grand |  |
|  |  |  |  |  |  |  | Prix o Fábrica) debe revisar cada contenedor para ver si contiene todo lo que se solicitó |  |
|  |  |  |  |  |  |  | originalmente, y ver que no tenga roturas, abolladuras u otros inconvenientes. |  |
|  |  |  |  |  |  |  | Si los contenedores tienen todo lo que se pidió y están en buenas condiciones, la Orden de |  |
|  |  |  |  |  |  |  | Traslado se actualiza a Exitosa y el contenedor se actualiza a Ocioso. Si algún contenedor de |  |
|  |  |  |  |  |  |  | una orden de traslado está incompleto, se debe marcar la orden de traslado como Incompleta |  |
|  |  |  |  |  |  |  | y se debe crear una nueva Orden de Traslado solicitando lo que falta, marcando al contenedor |  |
|  |  |  |  |  |  |  | como Ocioso también en este caso. |  |
|  |  |  |  |  |  |  | Independientemente de si llega todo lo pedido en la Orden de Traslado o no, si el contenedor |  |
|  |  |  |  |  |  |  | tiene algún tipo de problema o daño, se lo marca como Dañado para que se le realice una |  |
|  |  |  |  |  |  |  | inspección. Si los daños no son sustanciales y no comprometen la integridad del contenedor, se |  |
|  |  |  |  |  |  |  | lo marca como Ocioso, en caso contrario se lo da De baja. |  |
| 6. |  |  | N otificaciones
para una
Orden de
Traslado |  |  |  | Se debe notificar vía mail WhatsApp y/o SMS al Jefe de Equipo cada vez que un Jefe de Mecánica |  |
|  |  |  |  |  |  |  | crear una Orden de Traslado. |  |
|  |  |  |  |  |  |  | Si no se ha aprobado la Orden de Traslado dentro de las 12 horas de su creación, se deben |  |
|  |  |  |  |  |  |  | enviar las notificaciones nuevamente. |  |
|  |  |  |  |  |  |  | Cuando se aprueba una Orden de Traslado se deberá enviar una notificación al Encargado de |  |
|  |  |  |  |  |  |  | Logística asignado de armar los contenedores para que sean armados dentro de las 12 horas |  |
|  |  |  |  |  |  |  | de la aprobación de la Orden de Traslado. |  |
| 7. |  |  |  | R echazo |  | Si pasan 24 horas desde que se creó una Orden de Traslado y no se ha aprobado, la misma se
rechaza de forma automática. | Si pasan 24 horas desde que se creó una Orden de Traslado y no se ha aprobado, la misma se |  |
|  |  |  |  | automático de |  |  | rechaza de forma automática. |  |
|  |  |  |  | una Orden de |  |  |  |  |
|  |  |  |  | Traslado |  |  |  |  |
| 8. |  |  |  | C ancelación |  | Una Orden de Traslado puede ser cancelada en tanto no se haya iniciado el traslado de los
contenedores. A partir de ese punto ya no puede ser cancelada. |  |  |
|  |  |  |  | de una Orden |  |  |  |  |
|  |  |  |  | de Traslado |  |  |  |  |


#### Tabla 3 — Página 4

| T ratamiento |
| --- |
| de una Orden |
| de Traslado |


#### Tabla 4 — Página 4

| T ratamiento |
| --- |
| de un |
| Contenedor |


#### Tabla 5 — Página 4

| N otificaciones |
| --- |
| para una |
| Orden de |
| Traslado |


#### Tabla 6 — Página 4

| Una Orden de Traslado puede ser cancelada en tanto no se haya iniciado el traslado de los |
| --- |
| contenedores. A partir de ese punto ya no puede ser cancelada. |


#### Página 5

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial
Descripción de Caso de Uso
Nombre del Caso de Uso: Generar Orden de Traslado ID: 14
Prioridad: ☒ Esencial ☐ Útil ☐ Deseable
Categoría: ☒ Esencial ☐ Soporte
Complejidad: ☐ Simple ☒ Mediano ☐ Complejo ☐ Muy Complejo ☐ Extremadamente Complejo
Actor Principal: Generador de Orden de Traslado (GOT) Actor Secundario: Servidor de Correo
Servidor de SMS - WhatsApp
Tipo de Use Case: ☒ Concreto ☐ Abstracto
Objetivo: Crear una Orden de Traslado para uno o más contenedores de una escudería
Flujo: Creación de una Orden de Traslado por un Jefe Mecánico y hay suficientes contenedores disponibles con notificación
por email.
1. GOT: Selecciona la opción para generar una Orden de Traslado.
2. Sistema: Valida si el GOT logueado es Jefe de Equipo y no lo es.
3. Sistema: Busca y muestra los circuitos activos de la F1 y la fábrica de la escudería del usuario logueado. (Leer
Observación 1). Solicita que se seleccione un origen y un destino para la OT. (Leer la RN 2 Traslados que
pueden realizarse con una OT).
4. GOT: Selecciona un origen y un destino para el traslado.
5. Sistema: Busca y muestra los elementos pertenecientes a la escudería del usuario logueado. Para cada
elemento muestra su nombre, código y tipo de elemento. Solicita que se seleccionen todos los elementos a
trasladar.
6. GOT: Selecciona cada uno de los elementos a trasladar.
7. Sistema: Calcula cuántos contenedores se necesitan para los elementos seleccionados. Verifica si hay
suficientes contenedores disponibles de la escudería y los hay. (Leer observación 2). Asigna los elementos a un
contenedor. (Leer RN 1 Contenedores que provee la FIA).
8. Sistema: Solicita que se seleccione la fecha en la que se necesitan los elementos en el destino.
9. GOT: Ingresa la fecha en la que se necesitan los elementos en el destino.
10. Sistema: Calcula la última fecha de salida posible y valida si es igual o posterior a la fecha actual y lo es. (Leer
Observaciones 3 y 7)
11. Sistema: Solicita la confirmación de la orden de traslado.
12. GOT: Confirma la orden de traslado.
13. Sistema: Genera la orden de traslado en estado Creada conteniendo los elementos que se van a trasladar y en
qué contenedor se trasladará cada elemento. Actualiza el estado de los contenedores a AsignadoAOrden (Leer
Observación 4), la fecha de llegada esperada, la última fecha de salida posible, el origen y destino, la fecha de
creación de la orden y el responsable de crearla.
14. Sistema: Valida si el Jefe de Equipo tiene activas y tiene activas las de mail y SMS. Envía la notificación por email
y SMS al Jefe de Equipo indicando que se ha creado una Orden de Traslado que necesita su aprobación, con
todos los detalles de la OT. (Leer Observación 5). Fin de Caso de uso.
Flujos Alternativos
A1. El Generador de OT es el Jefe de Equipo.
A2. No hay circuitos activos.
A3. No hay elementos a trasladar.
A4. No hay contenedores suficientes disponibles.
A5. No es posible enviar los elementos y que lleguen en la fecha necesaria.
A6. No confirma la Orden de Traslado.
Ciclo lectivo 2026 Turnos: Todos Hoja: Página 5 de 15


#### Tabla 1 — Página 5

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial |
| --- | --- |


#### Tabla 2 — Página 5

| Nombre del Caso de Uso: Generar Orden de Traslado |  |  | ID: 14 |
| --- | --- | --- | --- |
| Prioridad: ☒ Esencial ☐ Útil ☐ Deseable |  |  |  |
| Categoría: ☒ Esencial ☐ Soporte |  |  |  |
| Complejidad: ☐ Simple ☒ Mediano ☐ Complejo ☐ Muy Complejo ☐ Extremadamente Complejo |  |  |  |
| Actor Principal: Generador de Orden de Traslado (GOT) |  | Actor Secundario: Servidor de Correo
Servidor de SMS - WhatsApp |  |
| Tipo de Use Case: ☒ Concreto ☐ Abstracto |  |  |  |
| Objetivo: Crear una Orden de Traslado para uno o más contenedores de una escudería |  |  |  |
|  | Flujo: Creación de una Orden de Traslado por un Jefe Mecánico y hay suficientes contenedores disponibles con notificación
por email. |  |  |
| 1. GOT: Selecciona la opción para generar una Orden de Traslado. |  |  |  |
| 2. Sistema: Valida si el GOT logueado es Jefe de Equipo y no lo es. |  |  |  |
| 3. Sistema: Busca y muestra los circuitos activos de la F1 y la fábrica de la escudería del usuario logueado. (Leer
Observación 1). Solicita que se seleccione un origen y un destino para la OT. (Leer la RN 2 Traslados que
pueden realizarse con una OT). |  |  |  |
| 4. GOT: Selecciona un origen y un destino para el traslado. |  |  |  |
| 5. Sistema: Busca y muestra los elementos pertenecientes a la escudería del usuario logueado. Para cada
elemento muestra su nombre, código y tipo de elemento. Solicita que se seleccionen todos los elementos a
trasladar. |  |  |  |
| 6. GOT: Selecciona cada uno de los elementos a trasladar. |  |  |  |
| 7. Sistema: Calcula cuántos contenedores se necesitan para los elementos seleccionados. Verifica si hay
suficientes contenedores disponibles de la escudería y los hay. (Leer observación 2). Asigna los elementos a un
contenedor. (Leer RN 1 Contenedores que provee la FIA). |  |  |  |
| 8. Sistema: Solicita que se seleccione la fecha en la que se necesitan los elementos en el destino. |  |  |  |
| 9. GOT: Ingresa la fecha en la que se necesitan los elementos en el destino. |  |  |  |
| 10. Sistema: Calcula la última fecha de salida posible y valida si es igual o posterior a la fecha actual y lo es. (Leer
Observaciones 3 y 7) |  |  |  |
| 11. Sistema: Solicita la confirmación de la orden de traslado. |  |  |  |
| 12. GOT: Confirma la orden de traslado. |  |  |  |
| 13. Sistema: Genera la orden de traslado en estado Creada conteniendo los elementos que se van a trasladar y en
qué contenedor se trasladará cada elemento. Actualiza el estado de los contenedores a AsignadoAOrden (Leer
Observación 4), la fecha de llegada esperada, la última fecha de salida posible, el origen y destino, la fecha de
creación de la orden y el responsable de crearla. |  |  |  |
| 14. Sistema: Valida si el Jefe de Equipo tiene activas y tiene activas las de mail y SMS. Envía la notificación por email
y SMS al Jefe de Equipo indicando que se ha creado una Orden de Traslado que necesita su aprobación, con
todos los detalles de la OT. (Leer Observación 5). Fin de Caso de uso. |  |  |  |
|  | Flujos Alternativos |  |  |
| A1. El Generador de OT es el Jefe de Equipo.
A2. No hay circuitos activos.
A3. No hay elementos a trasladar.
A4. No hay contenedores suficientes disponibles.
A5. No es posible enviar los elementos y que lleguen en la fecha necesaria.
A6. No confirma la Orden de Traslado. |  |  |  |


#### Página 6

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial
Observaciones
1. Los circuitos activos de la F1 son aquellos que se encuentran en el calendario del año actual y asignados a un
Gran Premio.
2. Para verificar contenedores disponibles se debe ver si la cantidad de contenedores necesarios se encuentran en
estado Ocioso.
3. La última fecha de salida posible se calcula en base a la distancia del destino y del origen considerando un viaje
sin contratiempos. Es la última fecha en la que se puede enviar un contenedor desde ese origen hacia ese
destino y que lleguen para la fecha necesaria.
4. El sistema debe asignar los elementos a trasladar a un contenedor separándolos por tipo y según el espacio
disponible en cada contenedor. Si los elementos de un tipo no entran en un solo contenedor, el sistema debe
asignar algunos elementos a un contenedor y otros elementos a otro contenedor; ambos contenedores del
mismo tipo.
5. El Jefe de Equipo puede recibir notificaciones por WhatsApp, SMS y/o Mail.
6. El rol de Generador de Orden de Traslado puede asumirlo el Jefe de Mecánica o el Jefe de Equipo.
7. Para el cálculo de distancia se utilizarán las coordenadas de ubicación de la locación de origen y de la locación
de destino, ya sean Circuito y/o Fábrica.
Máquina de Estado de la clase Orden de Traslado
Ciclo lectivo 2026 Turnos: Todos Hoja: Página 6 de 15


#### Tabla 1 — Página 6

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 6

|  | Observaciones |
| --- | --- |
| 1. Los circuitos activos de la F1 son aquellos que se encuentran en el calendario del año actual y asignados a un
Gran Premio.
2. Para verificar contenedores disponibles se debe ver si la cantidad de contenedores necesarios se encuentran en
estado Ocioso.
3. La última fecha de salida posible se calcula en base a la distancia del destino y del origen considerando un viaje
sin contratiempos. Es la última fecha en la que se puede enviar un contenedor desde ese origen hacia ese
destino y que lleguen para la fecha necesaria.
4. El sistema debe asignar los elementos a trasladar a un contenedor separándolos por tipo y según el espacio
disponible en cada contenedor. Si los elementos de un tipo no entran en un solo contenedor, el sistema debe
asignar algunos elementos a un contenedor y otros elementos a otro contenedor; ambos contenedores del
mismo tipo.
5. El Jefe de Equipo puede recibir notificaciones por WhatsApp, SMS y/o Mail.
6. El rol de Generador de Orden de Traslado puede asumirlo el Jefe de Mecánica o el Jefe de Equipo.
7. Para el cálculo de distancia se utilizarán las coordenadas de ubicación de la locación de origen y de la locación
de destino, ya sean Circuito y/o Fábrica. |  |


#### Página 7

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial
Realización de Caso de Uso de Análisis: CU 14 Generar Orden de Traslado - Vista de Estructura
Ciclo lectivo 2026 Turnos: Todos Hoja: Página 7 de 15


#### Tabla 1 — Página 7

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial |  |
| --- | --- | --- |


#### Página 8

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial
Vista Dinámica de la Realización de análisis del CU 14 Generar OT - Flujo: Creación de una Orden de Traslado por un Jefe
Mecánico y hay suficientes contenedores disponibles con notificación por email y por SMS.
Ciclo lectivo 2026 Turnos: Todos Hoja: Página 8 de 15


#### Tabla 1 — Página 8

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial |  |
| --- | --- | --- |


#### Página 9

Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial
Ciclo lectivo 2026 Turnos: Todos Hoja: Página 9 de 15


#### Tabla 1 — Página 9

|  | Diseño de Sistemas de Información
Caso de Estudio: FIA F1
Ejercicio práctico tipo tercer parcial |  |
| --- | --- | --- |


### 🖼️ Imágenes Extraídas (23 imágenes)

#### Imagen 1 — Página 1 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 2 — Página 1 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 3 — Página 2 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 4 — Página 2 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 5 — Página 3 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 6 — Página 3 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 7 — Página 4 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 8 — Página 4 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 9 — Página 5 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 10 — Página 5 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 11 — Página 6 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 12 — Página 6 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 13 — Página 6 (229.1 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 14 — Página 7 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 7**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `7`
> *(Para ver: abrir PDF en página 7)*


#### Imagen 15 — Página 7 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 7**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `7`
> *(Para ver: abrir PDF en página 7)*


#### Imagen 16 — Página 7 (445.9 KB)

> 📄 **Diagrama/Imagen — Página 7**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `7`
> *(Para ver: abrir PDF en página 7)*


#### Imagen 17 — Página 8 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 8**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `8`
> *(Para ver: abrir PDF en página 8)*


#### Imagen 18 — Página 8 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 8**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `8`
> *(Para ver: abrir PDF en página 8)*


#### Imagen 19 — Página 8 (178.7 KB)

> 📄 **Diagrama/Imagen — Página 8**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `8`
> *(Para ver: abrir PDF en página 8)*


#### Imagen 20 — Página 9 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 21 — Página 9 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 22 — Página 9 (46.2 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 23 — Página 9 (239.5 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf`](../Parciales y Exámenes/DSI 2026 Ejercicio tipo Parcial 3 FIA Formula 1.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*



---


## DSI 2026 Simulacro Parcial 2 Estrella de la Muerte

**Categoría:** Parciales y Exámenes  

**Archivo:** `DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`  

**Tamaño:** 0.53 MB  


### 📄 Contenido de Texto

#### Página 1

Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial
Se pide al Estudiante que lea y analice atentamente la situación planteada y en base a
ello:
1. Considerando la situación planteada, se pide al estudiante que lea y analice la información
que se le presenta y luego desarrolle las siguientes vistas arquitectónicas:
a. Vista Arquitectónica de la Funcionalidad. Utilizando un diagrama de casos de uso.
Justificar la elección de los casos de uso que incluya en la vista. Para construir esta
vista elija los casos de uso que considere en función de los definidos en la lista de
casos de uso que tiene disponible.
b. Vista Arquitectónica del Diseño. Utilizando un diagrama de componentes para
modelar los subsistemas, componentes e interfaces relevantes.
c. Vista Arquitectónica del Despliegue – Nodos y Subsistemas. Utilizando un
diagrama de despliegue para modelar la distribución del software (subsistemas y
componentes) en los niveles de hardware.
Dominio: La Estrella de la Muerte
Glosario:
● Droides: Robots que poseen inteligencia artificial. El imperio utiliza estos robots para todas las operaciones que
pueden ser peligrosas para otros soldados. También para dar soporte en operaciones militares complicadas.
● DS-MK: Nombre clave que utiliza el imperio de manera oficial para referirse al proyecto de construcción de la
estación espacial de gran tamaño conocida por los soldados del imperio como “Estrella de la Muerte”
● Unidad Militar: Es un elemento organizacional dentro de las fuerzas armadas bajo el mando de un líder o jefe. La
unidad militar básica es un escuadrón que está compuesto por entre 7 y 15 soldados.
● Tipo de Unidad Militar: El tipo de una Unidad Militar se refiere al lugar que la Unidad Militar ocupa en la jerarquía.
Estos tipos pueden ser: escuadrón, pelotón, compañía, batallón, brigada, división o cuerpo armado.
Son tiempos de guerra civil en la galaxia. Un grupo armado clandestino llamado “Alianza Rebelde” ha
atacado diversas bases de operaciones del Imperio Galáctico. El Emperador Palpatine ha ordenado a su
comandante en jefe de las fuerzas armadas, Darth Vader, que se encargue de los rebeldes para traer paz y
estabilidad a la galaxia. Darth Vader ha comisionado una estación espacial de gran tamaño para transportar
tropas más rápida y cómodamente a lo largo de la galaxia, esta estación espacial también estará armada para
permitir tomar acciones defensivas y ofensivas contra la Alianza Rebelde. Esta estación espacial es conocida
con el nombre clave DS-MK, pero los soldados del imperio la llaman “Death Star” o “Estrella de la Muerte”.
La Estrella de la Muerte puede transportar entre 1 y 1.5 millones de personas (Entre las cuales se encuentran
soldados de diversos rangos, médicos, cocineros, etc.). Se necesita un software especializado que controle
Ciclo lectivo 2026 Hoja: 1 de 14


#### Tabla 1 — Página 1

|  | Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 1

| 1. Considerando la situación planteada, se pide al estudiante que lea y analice la información |  |
| --- | --- |
| que se le presenta y luego desarrolle las siguientes vistas arquitectónicas: |  |
|  | a. Vista Arquitectónica de la Funcionalidad. Utilizando un diagrama de casos de uso. |
|  | Justificar la elección de los casos de uso que incluya en la vista. Para construir esta |
|  | vista elija los casos de uso que considere en función de los definidos en la lista de |
|  | casos de uso que tiene disponible. |
|  | b. Vista Arquitectónica del Diseño. Utilizando un diagrama de componentes para |
|  | modelar los subsistemas, componentes e interfaces relevantes. |
|  | c. Vista Arquitectónica del Despliegue – Nodos y Subsistemas. Utilizando un |
|  | diagrama de despliegue para modelar la distribución del software (subsistemas y |
|  | componentes) en los niveles de hardware. |


#### Tabla 3 — Página 1

| ● Droides: Robots que poseen inteligencia artificial. El imperio utiliza estos robots para todas las operaciones que |
| --- |
| pueden ser peligrosas para otros soldados. También para dar soporte en operaciones militares complicadas. |
| ● DS-MK: Nombre clave que utiliza el imperio de manera oficial para referirse al proyecto de construcción de la |
| estación espacial de gran tamaño conocida por los soldados del imperio como “Estrella de la Muerte” |
| ● Unidad Militar: Es un elemento organizacional dentro de las fuerzas armadas bajo el mando de un líder o jefe. La |
| unidad militar básica es un escuadrón que está compuesto por entre 7 y 15 soldados. |
| ● Tipo de Unidad Militar: El tipo de una Unidad Militar se refiere al lugar que la Unidad Militar ocupa en la jerarquía. |
| Estos tipos pueden ser: escuadrón, pelotón, compañía, batallón, brigada, división o cuerpo armado. |
|  |


#### Página 2

Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial
todos los aspectos de la estación, desde los accesos a las distintas áreas hasta las raciones y suministros que
se encuentran en la misma.
La armada imperial tiene su propia organización militar avanzada ya que deben patrullar y proteger
toda la galaxia. Dentro de la Estrella de la Muerte se maneja una jerarquía similar a la que suele manejar el
resto de la armada imperial. La unidad más pequeña es un Escuadrón compuesto por entre 7 y 15 soldados
(llamados Stormtroopers) y liderado por un teniente. Estas unidades militares son de una especialidad dada
(Infantería, Artillería, Unidades Especiales, Paracaidistas, Pilotos, etc.) y todos los miembros del escuadrón
tienen el mismo entrenamiento y habilidades de combate. Además de esto, cada Escuadrón cuenta con al
menos un soldado con entrenamiento como médico de campo, (cumple su función de médico sólo durante
una misión) y un soldado con entrenamiento de cocina de campo, (cumple su función de cocinero sólo
durante una misión). A su vez un grupo de 4 o 5 escuadrones componen un Pelotón que es liderado por un
comandante. Todos los escuadrones de un pelotón son de la misma habilidad. Un grupo de 2 a 4 pelotones
componen una Compañía que es liderada por un capitán. Los pelotones dentro de una compañía pueden
tener distintas especialidades para lograr misiones más completas. De esta forma, si se debe realizar un
ataque a gran escala se puede utilizar diversas habilidades de combate. Además, se puede planificar misiones
pequeñas que requieran de distintos escuadrones para complementar habilidades. Un grupo de 2 a 5
compañías forman un Batallón que es liderado por un comodoro. Un grupo de 2 a 6 batallones forman una
brigada que es liderada por un Vicealmirante. Un grupo de 4 a 5 brigadas forman una división que es liderada
por un Almirante. Finalmente, un grupo de 2 a 7 divisiones forman un cuerpo armado, que es liderado por
un Gran Almirante. Debería haber al menos 2 cuerpos armados completos en la Estrella de la Muerte en todo
momento. Toda esta estructura se encuentra al mando de Darth Vader, que ocupa el cargo de Comandante
en Jefe de las Fuerzas Imperiales. Darth Vader responde solo ante la autoridad del Comandante Supremo,
Darth Sidious.
Cada una de estas unidades militares posee un número identificatorio que se combina con una letra
que indica su jerarquía. Entonces un Cuerpo Armado puede tener el numero identificatorio “CP-1”. La
cantidad de dígitos de este número no tiene restricción ya que puede haber miles de unidades militares a lo
Ciclo lectivo 2026 Hoja: 2 de 14


#### Tabla 1 — Página 2

|  | Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial |  |
| --- | --- | --- |


#### Página 3

Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial
largo de la Galaxia. Además de esto, cada unidad militar tiene un emblema identificatorio único elegido por
su líder (Un Gran Almirante en el caso de un Cuerpo Armado) que permite a otras unidades una rápida
identificación en caso de encontrarse. Este emblema debe ir acompañado siempre del símbolo imperial
oficial para su tipo de unidad. Estos símbolos se ilustran en la imagen, son iguales para todas las unidades
del mismo tipo.
Sumada a la jerarquía militar que se deberá encontrar en todo momento asignada a la estación
espacial, la estrella de la muerte debe contar con personal medico, personal de limpieza, personal de
ingeniería y personal de cocina para abastecer a la estación. Ninguna de estas personas tiene entrenamiento
militar ni es parte del cuerpo activo del ejercito, sin embargo se dice que están trabajando para el ejercito.
Ninguna de estas personas tiene un rango y solo pueden acceder a ciertos espacios de la estación sin estar
acompañados de un oficial de alto rango. El software solicitado debe poder manejar este esquema de
permisos y abrir o cerrar puertas de la estación espacial. El acceso a las distintas áreas de la estación espacial
está controlado mediante escaneos de retina. Todo habitante de la Estrella de la Muerte debe registrar sus
datos biométricos al ser asignados a la estación espacial para acceder a las distintas áreas de la misma.
Para cualquier individuo que se encuentre habitando la estación espacial, es importante conocer su
nombre completo, su planeta de origen, su raza, su fecha de nacimiento y su fecha de ingreso al ejército. En
caso de los solados debe conocerse también su código de identificación único dentro del ejército (Un código
alfanumérico generado automáticamente al enlistarse) y su rango. Darth Vader ha especificado que es muy
importante mantener un registro de los cambios de rango de cada soldado ya que algunas de las misiones
planeadas sólo pueden ser asignadas a soldados y/o líderes con mayor experiencia.
Las tropas duermen en habitaciones conjuntas por Escuadrón. Cada habitación tendrá una pantalla
sobre la puerta que indicará toda la información del escuadrón que duerme en la habitación. Esto es el
emblema de ese escuadrón, su número de identificación y los números de identificación de todas las
unidades militares superiores a las que pertenece dicho escuadrón (pelotón, compañía, brigada, etc.). Cada
teniente duerme junto a su escuadrón, pero el resto de los oficiales de alto rango duerme en habitaciones
separadas por rango junto a otros oficiales de alto rango de su propia unidad militar. La estrella de la muerte
cuenta con diversas Secciones Habitacionales identificadas por colores. A lo largo de los pasillos de las
secciones habitacionales hay luces LED que cambian de color según el color de la sección. Cada sección está
asignada a un cuerpo armado y no puede haber soldados asignados a otro cuerpo armado durmiendo en la
sección. Darth Vader puede cambiar como están delimitados los módulos habitacionales, creando algún
módulo nuevo, eliminando un módulo o reasignado las divisiones. Las luces LED que marcan las distintas
secciones deben cambiar de color según el color asignado por Darth Vader. Todas las habitaciones son iguales
ya que se desea tener gran flexibilidad a la hora de transportar las tropas.
Por esta razón el Imperio permite que se creen nuevas unidades militares de cualquier tipo
correspondientes a una unidad de orden superior ya existente. También está permitido mover una unidad
Ciclo lectivo 2026 Hoja: 3 de 14


#### Tabla 1 — Página 3

|  | Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial |  |
| --- | --- | --- |


#### Página 4

Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial
militar para que pertenezca a cualquier otra. Por ejemplo, el pelotón P-501 era parte de la Compañía C-1103,
pero luego de la Guerra de los Clones fue movido a la Compañía C-609 encargada del patrullaje de los
sistemas exteriores. Esta flexibilidad es la que permite que el Imperio responda de forma rápida y eficiente
a las diversas necesidades de los ciudadanos del imperio.
Para mover unidades militares de una base militar a otra se utiliza una Orden de Reubicación. Esta
Orden de Reubicación puede ser iniciada por un oficial con rango de comandante o superior. Un oficial no
puede generar Órdenes de Reubicación para una unidad militar que sea superior a él en la jerarquía, es decir
que un comandante no puede generar una Orden de Reubicación para un Batallón. El oficial debe indicar
que unidad militar desea reubicar, que oficial se hará cargo ahora de la unidad militar (Indicando su nombre,
rango y el número identificatorio de la unidad militar que encabeza), el lugar o base al cual se reubicará a la
unidad militar, el motivo por el que se reubica a esa unidad y una fecha óptima para que las tropas ocupen
su nuevo puesto. Para que una Orden de Reubicación sea ejecutada, debe ser aprobada por al menos un
oficial de rango superior al que generó la orden. Este oficial puede aceptar o rechazar la Orden de
Reubicación. Las únicas excepciones son las órdenes generadas por Darth Vader o un Gran Almirante, esas
órdenes están aprobadas desde su creación. Una vez que la Orden ha sido aprobada, la misma debe ser
comunicada a las tropas afectadas para que puedan prepararse para el movimiento, esta comunicación debe
incluir el motivo de la Reubicación, la base a donde han sido asignados y la fecha de salida de la base actual
y debe hacerse utilizando las cuentas de E-Mail oficiales del imperio y/o por mensaje de texto a los
dispositivos celulares intergalácticos provistos por el Imperio. Si la Orden no es comunicada a las tropas,
entonces no es posible ejecutar la salida de la base origen. Si la comunicación no se realiza antes de la fecha
de vencimiento de la Orden, entonces la misma se considera como vencida y no puede ejecutarse. En ese
caso debe comunicarse al oficial que la creó mediante un correo electrónico. Una vez comunicada la orden
y llegada la fecha de salida, las tropas salen de su base actual camino a la nueva base. En este punto se
considera que la Orden está en proceso. Cuando las tropas llegan a la nueva base militar y han sido
acomodadas en sus habitaciones se considera que la Orden fue ejecutada. Darth Vader desea obtener
estadísticas respecto al cumplimiento de las órdenes, es por eso por lo que es de extrema importancia
diferencias las ordenes que se Ejecutaron satisfactoriamente (Es decir, las que cumplieron con todas las
fechas óptimas) y las que se Ejecutaron insatisfactoriamente (Es decir, las ordenes en las que las tropas
llegaron luego de la fecha optima de llegada). Para simplificar la mejora del proceso de ejecución de órdenes,
Darth Vader ha pedido que se registren todas las fechas de actividad de una Orden. Finalmente, una Orden
de Reubicación puede ser cancelada por el oficial que la creó si todavía no ha sido aprobada.
Darth Vader quiere que el software de la Estrella de la Muerte pueda manejar el hospedaje de todo
aquel que habite la estación espacial, la gestión de expediciones y/o misiones militares que salgan de la
misma y la gestión de los suministros necesarios para mantener a todos los habitantes de la Estrella de la
Muerte. Este software debe estar embebido en el hardware de la estrella de la muerte, por lo que se necesita
un sistema de escritorio. Sin embargo, es importante que los líderes de las unidades militares puedan acceder
Ciclo lectivo 2026 Hoja: 4 de 14


#### Tabla 1 — Página 4

|  | Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial |  |
| --- | --- | --- |


#### Página 5

Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial
desde las terminales de las naves espaciales de forma web. Este software maneja todos los sistemas de la
Estrella de la Muerte y la vida de sus habitantes depende del mismo, es por eso que debe estar disponible
24x7x365. El software de la Estrella de la Muerte debe llevar los colores oficiales del Imperio, que son negro,
gris y blanco, así como también el logo del Imperio en todas las pantallas.
Definición del Producto de Software a construir:
Objetivo del Producto de Software:
Gestionar el hospedaje del personal militar de la Estrella de la Muerte a través de órdenes de
reubicación, las misiones militares y los suministros necesarios para su ejecución, generando información
relacionada a las reubicaciones y el consumo de suministros militares en misiones.
Alcances del producto de software:
● Administración de unidades militares y personal auxiliar (Médicos, cocineros, etc.)
● Administración de droides
● Gestión de soldados con sus rangos militares a lo largo de su carrera militar.
● Gestión de órdenes de reubicación
● Gestión de Misiones y Suministros
Reglas de Negocio para el Producto de Software Gestión de personal militar de La Estrella de La
Muerte
Nombre de la RN Descripción de la RN
Creación de la Orden de Un oficial con rango de comandante o superior puede crear una Orden de Reubicación para
Reubicación una unidad militar inferior a su rango en la jerarquía. Debe indicar las unidades militares a
reubicar, el oficial que estará a cargo de las unidades a mover, la nueva base de la unidad
militar, el motivo de la Reubicación y la fecha óptima de ejecución de la orden.
Aprobación de una Para que una orden sea ejecutada, debe ser aprobada por al menos un oficial de rango
orden de Reubicación superior al que generó la orden. La orden puede ser aceptada o rechazada. Si la orden se
rechaza se debe comunicar la situación al oficial que la creó.
Excepción en la Las órdenes de reubicación creadas por Darth Vader o un Gran Almirante no necesitan ser
creación de órdenes de aprobadas. Están aprobadas desde su creación.
reubicación
Comunicación de una Una vez que la Orden ha sido aprobada, la misma debe ser comunicada a las tropas afectadas
orden de reubicación para que puedan prepararse para el movimiento, esta comunicación debe incluir el motivo
de la Reubicación, la base a donde han sido asignados y la fecha de salida de la base actual.
Vencimiento de Si la aprobación y comunicación no se realiza antes de la fecha de vencimiento de la orden
órdenes de reubicación de reubicación, entonces la misma se considera como vencida y no puede ejecutarse. En ese
caso debe comunicarse al oficial que la creó mediante un correo electrónico.
Salida de la base actual Una vez comunicada la orden de reubicación y llegada la fecha de salida, las tropas salen de
su base militar actual camino a la nueva base militar. En este punto se considera que la orden
reubicación está En Proceso.
Finalización de una Cuando las tropas llegan a la nueva base militar y han sido acomodadas en sus habitaciones
Orden de Reubicación se considera que la orden de reubicación fue ejecutada. Una orden de reubicación puede ser
Ciclo lectivo 2026 Hoja: 5 de 14


#### Tabla 1 — Página 5

|  | Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 5

|  | Nombre de la RN |  |  | Descripción de la RN |  |
| --- | --- | --- | --- | --- | --- |
| Creación de la Orden de
Reubicación | Creación de la Orden de |  |  | Un oficial con rango de comandante o superior puede crear una Orden de Reubicación para |  |
|  | Reubicación |  |  | una unidad militar inferior a su rango en la jerarquía. Debe indicar las unidades militares a |  |
|  |  |  |  | reubicar, el oficial que estará a cargo de las unidades a mover, la nueva base de la unidad |  |
|  |  |  |  | militar, el motivo de la Reubicación y la fecha óptima de ejecución de la orden. |  |
| Aprobación de una
orden de Reubicación |  |  | Para que una orden sea ejecutada, debe ser aprobada por al menos un oficial de rango
superior al que generó la orden. La orden puede ser aceptada o rechazada. Si la orden se
rechaza se debe comunicar la situación al oficial que la creó. |  |  |
|  | Excepción en la |  | Las órdenes de reubicación creadas por Darth Vader o un Gran Almirante no necesitan ser
aprobadas. Están aprobadas desde su creación. |  |  |
|  | creación de órdenes de |  |  |  |  |
|  | reubicación |  |  |  |  |
| Comunicación de una
orden de reubicación |  |  | Una vez que la Orden ha sido aprobada, la misma debe ser comunicada a las tropas afectadas
para que puedan prepararse para el movimiento, esta comunicación debe incluir el motivo
de la Reubicación, la base a donde han sido asignados y la fecha de salida de la base actual. |  |  |
| Vencimiento de
órdenes de reubicación |  |  |  | Si la aprobación y comunicación no se realiza antes de la fecha de vencimiento de la orden |  |
|  |  |  |  | de reubicación, entonces la misma se considera como vencida y no puede ejecutarse. En ese |  |
|  |  |  |  | caso debe comunicarse al oficial que la creó mediante un correo electrónico. |  |
| Salida de la base actual |  |  | Una vez comunicada la orden de reubicación y llegada la fecha de salida, las tropas salen de
su base militar actual camino a la nueva base militar. En este punto se considera que la orden
reubicación está En Proceso. |  |  |
|  | Finalización de una |  |  | Cuando las tropas llegan a la nueva base militar y han sido acomodadas en sus habitaciones |  |
|  | Orden de Reubicación |  |  | se considera que la orden de reubicación fue ejecutada. Una orden de reubicación puede ser |  |


#### Tabla 3 — Página 5

| Las órdenes de reubicación creadas por Darth Vader o un Gran Almirante no necesitan ser |
| --- |
| aprobadas. Están aprobadas desde su creación. |


#### Tabla 4 — Página 5

| Vencimiento de |
| --- |
| órdenes de reubicación |


#### Página 6

Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial
Nombre de la RN Descripción de la RN
ejecutada satisfactoriamente si se cumplió con la fecha óptima de ejecución o ejecutada
insatisfactoriamente si no se cumplió con la fecha óptima de ejecución.
Cancelación de una El oficial que creó la Orden de Reubicación puede cancelarla hasta antes de que haya sido
Orden de Reubicación. aprobada.
Rangos Militares de los Darth Vader ha especificado que es muy importante mantener un registro de los cambios de
soldados rango de cada soldado ya que algunas de las misiones planeadas sólo pueden ser asignadas
a soldados y/o líderes con mayor experiencia.
Casos de Uso
Nota: Si bien el listado de casos de uso no es exhaustivo, los casos de uso incluidos para una mejor comprensión de la funcionalidad del
producto son suficientes para construir la vista arquitectónica de la funcionalidad.
Nro. Nombre del Caso de Objetivo Actores
Uso
1 Registrar usuario Registrar los datos de una persona que desea utilizar el AP: Usuario
sistema.
2 Modificar usuario Modificar los datos permitidos de un usuario registrado en AP: Usuario
el sistema.
3 Consultar usuario Consultar los datos de un usuario. AP: Usuario
4 Eliminar usuario Dar de baja un usuario para que no pueda utilizar el sistema. AP: Administrador
de usuarios
5 Registrar perfil Registrar un perfil de usuario con los permisos requeridos AP: Administrador
para su rol. de usuarios
6 Modificar perfil Modificar datos permisos a un perfil de usuario. AP: Administrador
de usuarios
7 Consultar perfil Visualizar los datos y permisos de un perfil de usuario. AP: Administrador
de usuarios
8 Eliminar perfil Dar de baja un perfil de usuario. AP: Administrador
de usuarios
9 Registrar permiso Registrar datos de un permiso para que pueda asociarse a AP: Administrador
un perfil. de usuarios
10 Modificar permiso Modificar datos de un permiso AP: Administrador
de usuarios
11 Consultar permiso Visualizar datos de un permiso. AP: Administrador
de usuarios
12 Eliminar permiso Dar de baja un permiso. AP: Administrador
de usuarios
13 Asignar perfiles a Registrar la asignación de uno o más perfiles a un usuario. AP: Administrador
usuario de usuarios
14 Iniciar sesión Iniciar una sesión en el sistema mediante una cuenta con AP: Usuario
nombre de usuario y contraseña, accediendo a los permisos AS: Servicio Auth
del perfil asignado. Otra alternativa para iniciar una sesión Google
puede ser utilizando la cuenta de Google.
Ciclo lectivo 2026 Hoja: 6 de 14


#### Tabla 1 — Página 6

|  | Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 6

|  | Nombre de la RN |  |  | Descripción de la RN |  |
| --- | --- | --- | --- | --- | --- |
|  |  |  |  | ejecutada satisfactoriamente si se cumplió con la fecha óptima de ejecución o ejecutada |  |
|  |  |  |  | insatisfactoriamente si no se cumplió con la fecha óptima de ejecución. |  |
| Cancelación de una
Orden de Reubicación. |  |  | El oficial que creó la Orden de Reubicación puede cancelarla hasta antes de que haya sido
aprobada. |  |  |
| Rangos Militares de los
soldados |  |  |  | Darth Vader ha especificado que es muy importante mantener un registro de los cambios de |  |
|  |  |  |  | rango de cada soldado ya que algunas de las misiones planeadas sólo pueden ser asignadas |  |
|  |  |  |  | a soldados y/o líderes con mayor experiencia. |  |


#### Tabla 3 — Página 6

| Rangos Militares de los |
| --- |
| soldados |


#### Tabla 4 — Página 6

| Nro. |  |  |  | Nombre del Caso de |  | Objetivo |  |  | Actores |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  |  |  |  | Uso |  |  |  |  |  |  |  |
| 1 |  |  | Registrar usuario | Registrar usuario |  |  | Registrar los datos de una persona que desea utilizar el |  | AP: Usuario |  |  |
|  |  |  |  |  |  |  | sistema. |  |  |  |  |
| 2 |  |  | Modificar usuario |  |  |  | Modificar los datos permitidos de un usuario registrado en |  | AP: Usuario |  |  |
|  |  |  |  |  |  |  | el sistema. |  |  |  |  |
|  | 3 |  |  | Consultar usuario |  |  | Consultar los datos de un usuario. |  |  | AP: Usuario |  |
| 4 | 4 |  | Eliminar usuario | Eliminar usuario |  | Dar de baja un usuario para que no pueda utilizar el sistema. | Dar de baja un usuario para que no pueda utilizar el sistema. |  |  | AP: Administrador |  |
|  |  |  |  |  |  |  |  |  |  | de usuarios |  |
| 5 |  |  | Registrar perfil |  |  |  | Registrar un perfil de usuario con los permisos requeridos |  |  | AP: Administrador |  |
|  |  |  |  |  |  |  | para su rol. |  |  | de usuarios |  |
| 6 |  |  | Modificar perfil |  |  | Modificar datos permisos a un perfil de usuario. | Modificar datos permisos a un perfil de usuario. |  |  | AP: Administrador |  |
|  |  |  |  |  |  |  |  |  |  | de usuarios |  |
| 7 |  |  | Consultar perfil |  |  | Visualizar los datos y permisos de un perfil de usuario. |  |  |  | AP: Administrador |  |
|  |  |  |  |  |  |  |  |  |  | de usuarios |  |
| 8 |  |  | Eliminar perfil |  |  | Dar de baja un perfil de usuario. |  |  |  | AP: Administrador |  |
|  |  |  |  |  |  |  |  |  |  | de usuarios |  |
| 9 |  |  | Registrar permiso |  |  |  | Registrar datos de un permiso para que pueda asociarse a |  |  | AP: Administrador |  |
|  |  |  |  |  |  |  | un perfil. |  |  | de usuarios |  |
| 10 |  |  | Modificar permiso |  |  | Modificar datos de un permiso | Modificar datos de un permiso |  |  | AP: Administrador |  |
|  |  |  |  |  |  |  |  |  |  | de usuarios |  |
| 11 |  |  | Consultar permiso |  |  | Visualizar datos de un permiso. |  |  |  | AP: Administrador |  |
|  |  |  |  |  |  |  |  |  |  | de usuarios |  |
| 12 |  |  | Eliminar permiso |  |  | Dar de baja un permiso. |  |  |  | AP: Administrador |  |
|  |  |  |  |  |  |  |  |  |  | de usuarios |  |
| 13 |  |  |  | Asignar perfiles a |  | Registrar la asignación de uno o más perfiles a un usuario. |  |  |  | AP: Administrador |  |
|  |  |  |  | usuario |  |  |  |  |  | de usuarios |  |
| 14 |  |  | Iniciar sesión | Iniciar sesión |  |  | Iniciar una sesión en el sistema mediante una cuenta con |  | AP: Usuario
AS: Servicio Auth
Google | AP: Usuario |  |
|  |  |  |  |  |  |  | nombre de usuario y contraseña, accediendo a los permisos |  |  | AS: Servicio Auth |  |
|  |  |  |  |  |  |  | del perfil asignado. Otra alternativa para iniciar una sesión |  |  | Google |  |
|  |  |  |  |  |  |  | puede ser utilizando la cuenta de Google. |  |  |  |  |


#### Página 7

Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial
Nro. Nombre del Caso de Objetivo Actores
Uso
16 Cerrar sesión Cerrar una sesión en el sistema cuando el usuario así lo AP: Usuario
requiera
17 Registrar tipo de unidad Registrar datos de un tipo de unidad militar para que pueda AP: Encargado de
militar asociarse a una unidad militar. Administración
18 Modificar tipo de Modificar datos de un tipo de unidad militar. AP: Encargado de
unidad militar Administración
19 Consultar tipo de Visualizar datos de un tipo de unidad militar. AP: Encargado de
unidad militar Administración
20 Eliminar tipo de unidad Dar de baja un tipo de unidad militar. AP: Encargado de
militar Administración
21 Registrar base militar Registrar datos de una base militar para que pueda AP: Encargado de
asociarse a una unidad militar o a una orden de reubicación. Administración
22 Modificar base militar Modificar datos de una base militar. AP: Encargado de
Administración
23 Consultar base militar Visualizar datos de una base militar. AP: Encargado de
Administración
25 Eliminar base militar Dar de baja una base militar. AP: Encargado de
Administración
26 Registrar rango militar Registrar datos de un rango militar para que pueda asociarse AP: Encargado de
a un soldado. Administración
27 Modificar rango militar Modificar datos de un rango militar. AP: Encargado de
Administración
28 Consultar rango militar Visualizar datos de un rango militar. AP: Encargado de
Administración
29 Eliminar rango militar Dar de baja un rango militar. AP: Encargado de
Administración
30 Registrar orden de Crear una orden de reubicación de una unidad militar desde AP: Oficial
reubicación una base de origen a una base destino.
31 Registrar aprobación de Registrar el estado de aprobación de una orden de AP: Oficial
una orden militar reubicación de una unidad militar por parte de un oficial
apropiado.
32 Validar vencimiento de Marcar automáticamente como vencida todas las órdenes AP: -
órdenes de reubicación de reubicación cuya fecha de vencimiento haya pasado.
33 Cancelar orden de Cancelar una orden de reubicación cuando esta no fue AP: Oficial
reubicación aprobada.
34 Comunicar orden de Notificar mediante Email o SMS la aprobacion de una orden AP: Oficial
reubicación a la unidad de reubicación incluyendo el motivo de la reubicación, la AS: Servidor de
militar base a donde han sido asignados y la fecha de salida de la Correo
base actual. AS: Servidor de
SMS
35 Marcar el inicio de la Marcar el inicio de la movilización de las unidades militares AP: Oficial
ejecución de una orden desde la base militar de origen hacia la base militar de
de reubicación destino.
Ciclo lectivo 2026 Hoja: 7 de 14


#### Tabla 1 — Página 7

|  | Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 7

| Nro. |  | Nombre del Caso de |  | Objetivo |  |  | Actores |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | Uso |  |  |  |  |  |  |  |
| 16 | Cerrar sesión | Cerrar sesión |  |  | Cerrar una sesión en el sistema cuando el usuario así lo |  | AP: Usuario |  |  |
|  |  |  |  |  | requiera |  |  |  |  |
| 17 |  | Registrar tipo de unidad |  |  | Registrar datos de un tipo de unidad militar para que pueda |  |  | AP: Encargado de |  |
|  |  | militar |  |  | asociarse a una unidad militar. |  |  | Administración |  |
| 18 |  | Modificar tipo de |  | Modificar datos de un tipo de unidad militar. | Modificar datos de un tipo de unidad militar. |  |  | AP: Encargado de |  |
|  |  | unidad militar |  |  |  |  |  | Administración |  |
| 19 |  | Consultar tipo de |  | Visualizar datos de un tipo de unidad militar. |  |  |  | AP: Encargado de |  |
|  |  | unidad militar |  |  |  |  |  | Administración |  |
| 20 |  | Eliminar tipo de unidad |  | Dar de baja un tipo de unidad militar. |  |  |  | AP: Encargado de |  |
|  |  | militar |  |  |  |  |  | Administración |  |
| 21 | Registrar base militar | Registrar base militar |  |  | Registrar datos de una base militar para que pueda |  |  | AP: Encargado de |  |
|  |  |  |  |  | asociarse a una unidad militar o a una orden de reubicación. |  |  | Administración |  |
| 22 | Modificar base militar |  |  | Modificar datos de una base militar. | Modificar datos de una base militar. |  |  | AP: Encargado de |  |
|  |  |  |  |  |  |  |  | Administración |  |
| 23 | Consultar base militar |  |  | Visualizar datos de una base militar. |  |  |  | AP: Encargado de |  |
|  |  |  |  |  |  |  |  | Administración |  |
| 25 | Eliminar base militar |  |  | Dar de baja una base militar. |  |  |  | AP: Encargado de |  |
|  |  |  |  |  |  |  |  | Administración |  |
| 26 | Registrar rango militar |  |  |  | Registrar datos de un rango militar para que pueda asociarse |  |  | AP: Encargado de |  |
|  |  |  |  |  | a un soldado. |  |  | Administración |  |
| 27 | Modificar rango militar |  |  | Modificar datos de un rango militar. | Modificar datos de un rango militar. |  |  | AP: Encargado de |  |
|  |  |  |  |  |  |  |  | Administración |  |
| 28 | Consultar rango militar |  |  | Visualizar datos de un rango militar. |  |  |  | AP: Encargado de |  |
|  |  |  |  |  |  |  |  | Administración |  |
| 29 | Eliminar rango militar |  |  | Dar de baja un rango militar. |  |  |  | AP: Encargado de |  |
|  |  |  |  |  |  |  |  | Administración |  |
| 30 |  | Registrar orden de |  |  | Crear una orden de reubicación de una unidad militar desde |  | AP: Oficial | AP: Oficial |  |
|  |  | reubicación |  |  | una base de origen a una base destino. |  |  |  |  |
| 31 | Registrar aprobación de
una orden militar | Registrar aprobación de |  |  | Registrar el estado de aprobación de una orden de |  | AP: Oficial |  |  |
|  |  | una orden militar |  |  | reubicación de una unidad militar por parte de un oficial |  |  |  |  |
|  |  |  |  |  | apropiado. |  |  |  |  |
| 32 |  | Validar vencimiento de |  |  | Marcar automáticamente como vencida todas las órdenes |  | AP: - |  |  |
|  |  | órdenes de reubicación |  |  | de reubicación cuya fecha de vencimiento haya pasado. |  |  |  |  |
| 33 |  | Cancelar orden de |  |  | Cancelar una orden de reubicación cuando esta no fue |  | AP: Oficial |  |  |
|  |  | reubicación |  |  | aprobada. |  |  |  |  |
| 34 | Comunicar orden de
reubicación a la unidad
militar | Comunicar orden de |  |  | Notificar mediante Email o SMS la aprobacion de una orden |  |  | AP: Oficial |  |
|  |  | reubicación a la unidad |  |  | de reubicación incluyendo el motivo de la reubicación, la |  |  | AS: Servidor de |  |
|  |  | militar |  |  | base a donde han sido asignados y la fecha de salida de la |  |  | Correo |  |
|  |  |  |  |  | base actual. |  |  | AS: Servidor de |  |
|  |  |  |  |  |  |  |  | SMS |  |
| 35 |  | Marcar el inicio de la |  |  | Marcar el inicio de la movilización de las unidades militares |  | AP: Oficial | AP: Oficial |  |
|  |  | ejecución de una orden |  |  | desde la base militar de origen hacia la base militar de |  |  |  |  |
|  |  | de reubicación |  |  | destino. |  |  |  |  |


#### Página 8

Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial
Nro. Nombre del Caso de Objetivo Actores
Uso
36 Marcar finalización de Marcar la finalización de ejecución de una orden de AP: Oficial
una orden de reubicación.
reubicación
37 Validar identidad de Validar permisos de acceso de un usuario a una sección de la AP: Usuario
acceso estación espacial mediante sus datos biométricos para AS: Hardware de
poder abrir la puerta. detección de datos
biométricos
38 Generar Informe de Generar un informe de cumplimiento de órdenes de AP: Oficial
cumplimiento de reubicación según el método de cálculo seleccionado y la
órdenes de reubicación forma de visualización elegida.
39 Generar estadística de Generar una estadística que permita visualizar el tiempo AP: Oficial
órdenes de reubicación promedio transcurrido por estado para las órdenes de
por estado reubicación.
40 Planificar Misión Registrar una misión indicando la unidad militar que la AP: Oficial
llevará a cabo, el objetivo, asociando los suministros
necesarios e indicando la fecha de inicio y fecha estimada de
cumplimiento.
41 Registrar resultado de Indicar si una misión terminó de manera exitosa o fracasó en AP: Oficial
misión el cumplimiento de su objetivo, incluyendo una descripción
del resultado.
42 Cancelar Misión Indicar que una misión no se llevará a cabo debido a que su AP: Oficial
objetivo ya no es relevante.
43 Registrar suministro Registrar datos de un suministro para que pueda ser usado AP: Encargado de
en una misión indicando su stock. Administración
44 Modificar suministro Modificar datos de una base militar. AP: Encargado de
Administración
45 Consultar suministro Visualizar datos de una base militar. AP: Encargado de
Administración
46 Eliminar suministro Dar de baja una base militar. AP: Encargado de
Administración
Requerimientos No Funcionales
SPA: Significativo para la arquitectura
Nº Nombre Descripción SPA Justificación
1 Tecnología Este software debe estar embebido en SI Restricción técnica de implementación, que
Desktop el hardware de la estrella de la muerte, afecta a la arquitectura. Se debe utilizar un
por lo que se necesita un sistema de lenguaje de desarrollo que permita que el
escritorio compatible con las software se utilice en las terminales de la
terminales de la estación espacial. Estrella de la Muerte.
Ciclo lectivo 2026 Hoja: 8 de 14


#### Tabla 1 — Página 8

|  | Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 8

| Nro. |  | Nombre del Caso de |  | Objetivo |  |  | Actores |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  |  | Uso |  |  |  |  |  |  |
| 36 |  | Marcar finalización de |  | Marcar la finalización de ejecución de una orden de
reubicación. |  |  | AP: Oficial |  |
|  |  | una orden de |  |  |  |  |  |  |
|  |  | reubicación |  |  |  |  |  |  |
| 37 | Validar identidad de
acceso | Validar identidad de |  | Validar permisos de acceso de un usuario a una sección de la
estación espacial mediante sus datos biométricos para
poder abrir la puerta. |  |  |  | AP: Usuario
AS: Hardware de
detección de datos
biométricos |
|  |  | acceso |  |  |  |  |  |  |
| 38 |  | Generar Informe de |  |  | Generar un informe de cumplimiento de órdenes de |  | AP: Oficial |  |
|  |  | cumplimiento de |  |  | reubicación según el método de cálculo seleccionado y la |  |  |  |
|  |  | órdenes de reubicación |  |  | forma de visualización elegida. |  |  |  |
| 39 |  | Generar estadística de |  |  | Generar una estadística que permita visualizar el tiempo |  | AP: Oficial |  |
|  |  | órdenes de reubicación |  |  | promedio transcurrido por estado para las órdenes de |  |  |  |
|  |  | por estado |  |  | reubicación. |  |  |  |
| 40 | Planificar Misión | Planificar Misión |  |  | Registrar una misión indicando la unidad militar que la |  | AP: Oficial |  |
|  |  |  |  |  | llevará a cabo, el objetivo, asociando los suministros |  |  |  |
|  |  |  |  |  | necesarios e indicando la fecha de inicio y fecha estimada de |  |  |  |
|  |  |  |  |  | cumplimiento. |  |  |  |
| 41 | Registrar resultado de
misión |  |  |  | Indicar si una misión terminó de manera exitosa o fracasó en |  | AP: Oficial |  |
|  |  |  |  |  | el cumplimiento de su objetivo, incluyendo una descripción |  |  |  |
|  |  |  |  |  | del resultado. |  |  |  |
| 42 | Cancelar Misión |  |  |  | Indicar que una misión no se llevará a cabo debido a que su |  | AP: Oficial |  |
|  |  |  |  |  | objetivo ya no es relevante. |  |  |  |
| 43 | Registrar suministro |  |  |  | Registrar datos de un suministro para que pueda ser usado |  |  | AP: Encargado de
Administración |
|  |  |  |  |  | en una misión indicando su stock. |  |  |  |
| 44 | Modificar suministro |  |  | Modificar datos de una base militar. | Modificar datos de una base militar. |  |  | AP: Encargado de
Administración |
| 45 | Consultar suministro |  |  | Visualizar datos de una base militar. |  |  |  | AP: Encargado de
Administración |
| 46 | Eliminar suministro |  |  | Dar de baja una base militar. |  |  |  | AP: Encargado de
Administración |


#### Tabla 3 — Página 8

| Marcar la finalización de ejecución de una orden de |
| --- |
| reubicación. |


#### Tabla 4 — Página 8

| Validar permisos de acceso de un usuario a una sección de la |
| --- |
| estación espacial mediante sus datos biométricos para |
| poder abrir la puerta. |


#### Tabla 5 — Página 8

| Registrar resultado de |
| --- |
| misión |


#### Tabla 6 — Página 8

| Nº | Nombre |  |  | Descripción |  |  | SPA |  |  | Justificación |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Tecnología
Desktop |  | Este software debe estar embebido en |  |  | SI |  |  | Restricción técnica de implementación, que |  |  |
|  |  |  | el hardware de la estrella de la muerte, |  |  |  |  |  | afecta a la arquitectura. Se debe utilizar un |  |  |
|  |  |  | por lo que se necesita un sistema de |  |  |  |  |  | lenguaje de desarrollo que permita que el |  |  |
|  |  |  | escritorio compatible con las |  |  |  |  |  | software se utilice en las terminales de la |  |  |
|  |  |  | terminales de la estación espacial. |  |  |  |  |  | Estrella de la Muerte. |  |  |


#### Tabla 7 — Página 8

| Tecnología |
| --- |
| Desktop |


#### Página 9

Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial
Nº Nombre Descripción SPA Justificación
2 Tecnología Se requiere utilizar tecnología web SI Restricción técnica de implementación, que
Web para la implementación de la gestión afecta a la arquitectura. Se debe utilizar un
de unidades militares y sus misiones. lenguaje de desarrollo web para la gestión de
las unidades militares y sus misiones.
3 Conexión con El software solicitado por Darth Vader Si Debe desarrollarse un componente que
el hardware debe poder abrir y cerrar las puertas interactúe con el controlador (driver) de las
de puertas automáticas de la Estrella de la puertas automáticas de la Estrella de la
automáticas Muerte. Se necesita una conexión con Muerte, y pueda manejarlas.
su hardware.
4 Conexión con El acceso a las distintas áreas de la SI Debe desarrollarse un componente que se
el lector de estación espacial está controlado conecte con el lector de retina para traducir
retina mediante escaneos de retina. Todo los datos biométricos a información que
habitante de la Estrella de la Muerte pueda ser interpretada por nuestro software.
debe registrar sus datos biométricos al Se puede aplicar un patrón Broker.
ser asignados a la estación espacial
para acceder a las distintas áreas de
esta.
5 Luces LED de Las luces LED que marcan las distintas No Las luces LED adquiridas por el imperio son
los módulos secciones de los cuerpos militares del tipo Plug & Play y funcionan sin necesidad
habitacionale deben cambiar de color según el color de ningún tipo de desarrollo extra.
s asignado por Darth Vader.
6 Confiabilidad Este software maneja todos los SI Para resolver este requerimiento debe
sistemas de la Estrella de la Muerte y la utilizarse servidores espejados de aplicaciones
vida de sus habitantes depende del y de base de datos. Esta redundancia es para
mismo, es por lo que debe estar asegurar que ante la caída eventual de uno de
disponible 24x7x365. los servidores, el otro pueda brindar el servicio
necesario.
7 Notificación a Se debe permitir notificar a los SI Debe desarrollarse un componente que
soldados por soldados por mail la información genere y resuelva el envío de mensajes por
email referente a las Ordenes de Reubicación email, utilizando un servidor de correo de tipo
que los afecta. Exchange.
8 Notificación a Se debe permitir notificar a los SI Debe desarrollarse un componente que
soldados vía soldados por SMS la información genere y resuelva el envío de mensajes vía
SMS referente a las Órdenes de Reubicación SMS.
que los afecta.
9 Colores del El software de la Estrella de la Muerte NO No significativo para la arquitectura.
software debe llevar los colores oficiales del
Imperio, que son negro, gris y blanco.
Ciclo lectivo 2026 Hoja: 9 de 14


#### Tabla 1 — Página 9

|  | Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 9

| Nº | Nombre |  |  |  |  | Descripción |  |  | SPA |  |  | Justificación |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 2 | Tecnología
Web |  |  | Se requiere utilizar tecnología web
para la implementación de la gestión
de unidades militares y sus misiones. |  |  |  | SI |  |  | Restricción técnica de implementación, que |  |  |
|  |  |  |  |  |  |  |  |  |  |  | afecta a la arquitectura. Se debe utilizar un |  |  |
|  |  |  |  |  |  |  |  |  |  |  | lenguaje de desarrollo web para la gestión de |  |  |
|  |  |  |  |  |  |  |  |  |  |  | las unidades militares y sus misiones. |  |  |
| 3 | Conexión con
el hardware
de puertas
automáticas |  |  |  | El software solicitado por Darth Vader |  |  | Si |  | Debe desarrollarse un componente que
interactúe con el controlador (driver) de las
puertas automáticas de la Estrella de la
Muerte, y pueda manejarlas. | Debe desarrollarse un componente que |  |  |
|  |  |  |  |  | debe poder abrir y cerrar las puertas |  |  |  |  |  | interactúe con el controlador (driver) de las |  |  |
|  |  |  |  |  | automáticas de la Estrella de la |  |  |  |  |  | puertas automáticas de la Estrella de la |  |  |
|  |  |  |  |  | Muerte. Se necesita una conexión con |  |  |  |  |  | Muerte, y pueda manejarlas. |  |  |
|  |  |  |  |  | su hardware. |  |  |  |  |  |  |  |  |
| 4 | Conexión con
el lector de
retina |  |  |  | El acceso a las distintas áreas de la |  |  | SI |  | Debe desarrollarse un componente que se
conecte con el lector de retina para traducir
los datos biométricos a información que
pueda ser interpretada por nuestro software.
Se puede aplicar un patrón Broker. |  |  |  |
|  |  |  |  |  | estación espacial está controlado |  |  |  |  |  |  |  |  |
|  |  |  |  |  | mediante escaneos de retina. Todo |  |  |  |  |  |  |  |  |
|  |  |  |  |  | habitante de la Estrella de la Muerte |  |  |  |  |  |  |  |  |
|  |  |  |  |  | debe registrar sus datos biométricos al |  |  |  |  |  |  |  |  |
|  |  |  |  |  | ser asignados a la estación espacial |  |  |  |  |  |  |  |  |
|  |  |  |  |  | para acceder a las distintas áreas de |  |  |  |  |  |  |  |  |
|  |  |  |  |  | esta. |  |  |  |  |  |  |  |  |
| 5 |  | Luces LED de |  |  | Las luces LED que marcan las distintas |  |  | No |  | Las luces LED adquiridas por el imperio son
del tipo Plug & Play y funcionan sin necesidad
de ningún tipo de desarrollo extra. |  |  |  |
|  |  | los módulos |  |  | secciones de los cuerpos militares |  |  |  |  |  |  |  |  |
|  |  | habitacionale |  |  | deben cambiar de color según el color |  |  |  |  |  |  |  |  |
|  |  | s |  |  | asignado por Darth Vader. |  |  |  |  |  |  |  |  |
| 6 | Confiabilidad | Confiabilidad |  | Este software maneja todos los
sistemas de la Estrella de la Muerte y la
vida de sus habitantes depende del
mismo, es por lo que debe estar
disponible 24x7x365. | Este software maneja todos los |  |  | SI |  |  | Para resolver este requerimiento debe |  |  |
|  |  |  |  |  | sistemas de la Estrella de la Muerte y la |  |  |  |  |  | utilizarse servidores espejados de aplicaciones |  |  |
|  |  |  |  |  | vida de sus habitantes depende del |  |  |  |  |  | y de base de datos. Esta redundancia es para |  |  |
|  |  |  |  |  | mismo, es por lo que debe estar |  |  |  |  |  | asegurar que ante la caída eventual de uno de |  |  |
|  |  |  |  |  | disponible 24x7x365. |  |  |  |  |  | los servidores, el otro pueda brindar el servicio |  |  |
|  |  |  |  |  |  |  |  |  |  |  | necesario. |  |  |
| 7 | Notificación a
soldados por
email |  |  | Se debe permitir notificar a los
soldados por mail la información
referente a las Ordenes de Reubicación
que los afecta. |  |  |  | SI |  |  | Debe desarrollarse un componente que |  |  |
|  |  |  |  |  |  |  |  |  |  |  | genere y resuelva el envío de mensajes por |  |  |
|  |  |  |  |  |  |  |  |  |  |  | email, utilizando un servidor de correo de tipo |  |  |
|  |  |  |  |  |  |  |  |  |  |  | Exchange. |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 8 | Notificación a
soldados vía
SMS |  |  |  | Se debe permitir notificar a los |  |  | SI |  | Debe desarrollarse un componente que
genere y resuelva el envío de mensajes vía
SMS. | Debe desarrollarse un componente que |  |  |
|  |  |  |  |  | soldados por SMS la información |  |  |  |  |  | genere y resuelva el envío de mensajes vía |  |  |
|  |  |  |  |  | referente a las Órdenes de Reubicación |  |  |  |  |  | SMS. |  |  |
|  |  |  |  |  | que los afecta. |  |  |  |  |  |  |  |  |
| 9 | Colores del
software |  |  |  | El software de la Estrella de la Muerte |  |  | NO |  | No significativo para la arquitectura. |  |  |  |
|  |  |  |  |  | debe llevar los colores oficiales del |  |  |  |  |  |  |  |  |
|  |  |  |  |  | Imperio, que son negro, gris y blanco. |  |  |  |  |  |  |  |  |


#### Tabla 3 — Página 9

| Tecnología |
| --- |
| Web |


#### Tabla 4 — Página 9

| Se requiere utilizar tecnología web |
| --- |
| para la implementación de la gestión |
| de unidades militares y sus misiones. |


#### Tabla 5 — Página 9

| Conexión con |
| --- |
| el hardware |
| de puertas |
| automáticas |


#### Tabla 6 — Página 9

| Conexión con |
| --- |
| el lector de |
| retina |


#### Tabla 7 — Página 9

| Debe desarrollarse un componente que se |
| --- |
| conecte con el lector de retina para traducir |
| los datos biométricos a información que |
| pueda ser interpretada por nuestro software. |
| Se puede aplicar un patrón Broker. |


#### Tabla 8 — Página 9

| Las luces LED adquiridas por el imperio son |
| --- |
| del tipo Plug & Play y funcionan sin necesidad |
| de ningún tipo de desarrollo extra. |


#### Tabla 9 — Página 9

| Notificación a |
| --- |
| soldados por |
| email |


#### Tabla 10 — Página 9

| Se debe permitir notificar a los |
| --- |
| soldados por mail la información |
| referente a las Ordenes de Reubicación |
| que los afecta. |


#### Tabla 11 — Página 9

| Notificación a |
| --- |
| soldados vía |
| SMS |


#### Tabla 12 — Página 9

| Colores del |
| --- |
| software |


#### Página 10

Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial
Nº Nombre Descripción SPA Justificación
10 Logo del El software de la Estrella de la Muerte NO No significativo para la arquitectura.
Imperio debe llevar el logo del Imperio en
todas las pantallas.
11 Login con el sistema debe permitir como SI Se deberá desarrollar un componente de
Google alternativa el login mediante Google interfaz que resuelva la comunicación con el
servicio de login de Google Auth.
Ciclo lectivo 2026 Hoja: 10 de 14


#### Tabla 1 — Página 10

|  | Diseño de Sistemas de Información
Caso de Estudio: La Estrella de la Muerte
Ejercicio práctico tipo segundo parcial |  |
| --- | --- | --- |


#### Tabla 2 — Página 10

| Nº | Nombre |  |  | Descripción |  |  | SPA |  |  | Justificación |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 10 | Logo del
Imperio |  | El software de la Estrella de la Muerte |  |  | NO |  | No significativo para la arquitectura. |  |  |  |
|  |  |  | debe llevar el logo del Imperio en |  |  |  |  |  |  |  |  |
|  |  |  | todas las pantallas. |  |  |  |  |  |  |  |  |
| 11 | Login con
Google | el sistema debe permitir como
alternativa el login mediante Google | el sistema debe permitir como |  |  | SI |  |  | Se deberá desarrollar un componente de |  |  |
|  |  |  | alternativa el login mediante Google |  |  |  |  |  | interfaz que resuelva la comunicación con el |  |  |
|  |  |  |  |  |  |  |  |  | servicio de login de Google Auth. |  |  |


#### Tabla 3 — Página 10

| Logo del |
| --- |
| Imperio |


#### Tabla 4 — Página 10

| Login con |
| --- |
| Google |


### 🖼️ Imágenes Extraídas (21 imágenes)

#### Imagen 1 — Página 1 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 2 — Página 1 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 3 — Página 2 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 4 — Página 2 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 5 — Página 2 (63.3 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 6 — Página 3 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 7 — Página 3 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 8 — Página 4 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 9 — Página 4 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 10 — Página 5 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 11 — Página 5 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 12 — Página 6 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 13 — Página 6 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 14 — Página 7 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 7**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `7`
> *(Para ver: abrir PDF en página 7)*


#### Imagen 15 — Página 7 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 7**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `7`
> *(Para ver: abrir PDF en página 7)*


#### Imagen 16 — Página 8 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 8**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `8`
> *(Para ver: abrir PDF en página 8)*


#### Imagen 17 — Página 8 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 8**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `8`
> *(Para ver: abrir PDF en página 8)*


#### Imagen 18 — Página 9 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 19 — Página 9 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 20 — Página 10 (20.2 KB)

> 📄 **Diagrama/Imagen — Página 10**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `10`
> *(Para ver: abrir PDF en página 10)*


#### Imagen 21 — Página 10 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 10**
> PDF: [`DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf`](../Parciales y Exámenes/DSI 2026 Simulacro Parcial 2 Estrella de la Muerte.pdf) · Página `10`
> *(Para ver: abrir PDF en página 10)*



---

