# Diapositivas y Teóricos

> Seccion del repositorio **DSI INFO** — 7 documentos.
> Archivo principal: `DSI_INFO_Completo.md` | Indice: `INDEX.md`

## Contenido de esta seccion

- 01 Modelado Comp con Diag Maquina de Estados
- 02 Modelado Comp con Diag Maquina de Estados parte 2
- 03 Realizaciones de CU - Diagrama de Secuencia
- 04 GRASP con secuencia
- 05 GRASP con com
- 06 Tips para el Modelado de Realizaciones de Caso - Secuencias
- unidad 1 ppt unidas DSI

---



## 01 Modelado Comp con Diag Maquina de Estados

**Categoría:** Diapositivas y Teóricos  

**Archivo:** `01 Modelado Comp con Diag Maquina de Estados.pdf`  

**Tamaño:** 5.45 MB  


### 📄 Contenido de Texto

#### Página 1

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Modelado de Comportamiento con el
Diagrama de Máquina de Estados
4/1/2026 Judith Meles 1


#### Página 2

¿Qué utilizamos del Modelo de
CÁTEDRA DE DISEÑO DE SISTEMAS
Requerimientos como base para el DE INFORMACIÓN
Modelo de Análisis?
1 o más vistas de Casos de uso
Modelo de Casos de Uso Descripciones de Casos de Uso
Descripciones de Actores
Vista de Clases del Dominio del
Modelo de Requerimientos
Problema
Modelo de Dominio
Glosario
Descripción de Interfaces
de usuario
4/1/2026 Judith Meles 2


#### Tabla 1 — Página 2

| Modelo de Análisis?
1 o más vistas de Casos de uso
Modelo de Casos de Uso Descripciones de Casos de Uso
Descripciones de Actores
Vista de Clases del Dominio del
Modelo de Requerimientos
Problema
Modelo de Dominio
Glosario
Descripción de Interfaces
de usuario
4/1/2026 Judith Meles |
| --- |
|  |


#### Página 3

Workflow de Análisis como proceso…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Salida
Entrada
Workflow
de Análisis
4/1/2026 Judith Meles 3


#### Página 4

¿Cómo construimos el Modelo de Análisis?
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Herramienta: Diagrama
Vista Estática
de Clases
Realizaciones de
Casos de Uso de
Herramienta: Diagrama
Análisis
de Comunicación
Vista Dinámica
Herramienta Diagrama
de Secuencia
Herramienta: Diagrama de Clases
Clases de Análisis
Modelo de
Herramienta: Diagrama de Máquina
Análisis
de Estados
Paquetes de Análisis Herramienta: Diagrama de Paquetes
Descripción de la
Arquitectura
4/1/2026 Judith Meles 4


#### Página 5

¿Cómo construimos el Modelo de Análisis?
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Herramienta: Diagrama
Vista Estática
de Clases
Realizaciones de
Casos de Uso de
Herramienta: Diagrama
Análisis
de Comunicación
Vista Dinámica
Herramienta Diagrama
de Secuencia
Herramienta: Diagrama de Clases
Clases de Análisis
Modelo de
Análisis
Diagrama de Máquina de Estados
Paquetes de Análisis Herramienta: Diagrama de Paquetes
Descripción de la
Arquitectura
4/1/2026 Judith Meles 5


#### Página 6

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
¿QUÉ SABE O
QUE TIENE EL ¿QUÉ ES? ¿Qué lo
OBJETO? distingue de los
demás objetos?
Identidad Clase: Auto Objeto: Mi auto
Estado
Comporta
¿QUÉ PUEDE
miento
HACER EL
OBJETO?
Estructura Objeto
La clase AUTO puede tener Instanciado de la clase Auto, lo que significa que
(atributos): asignamos un lugar: Identidad
y le damos valores a los atributos: Estado
Estado = Atributo + Valor
marca: Chevrolet
marca
modelo: Classic
modelo
color: Blanco
En un momento de tiempo
color dominio: MBO056
dominio añoFabricación: 2012
añoFabricación
Comportamiento o Comportamiento o
DNI
Responsabilidades Responsabilidades
Valores
La Clase Auto puede: Lo que el objeto puede hacer lo toma
Invariables
Legajo de la clase, es decir el objeto puede
Alumno encenderMotor hacer lo que está definido en la Clase
Atributos encenderLuces de la que se creó:
avanzar encenderMotor
Estado Civil
retroceder encenderLuces
Valores
estacionar avanzar
Variables obtenerNivelCombustible retroceder
Situación
estacionar
Académica
obtenerNivelCombustible


#### Tabla 1 — Página 6

| Clase: Auto | Objeto: Mi auto |  |
| --- | --- | --- |
|  |  |  |
|  |  |  |
| Estructura | Objeto |  |
| La clase AUTO puede tener
(atributos):
marca
modelo
color
dominio | Instanciado de la clase Auto, lo que significa que
asignamos un lugar: Identidad
y le damos valores a los atributos: Estado
marca: Chevrolet
modelo: Classic
color: Blanco
dominio: MBO056
añoFabricación: 2012 |  |
| añoFabricación
Comportamiento o |  | Comportamiento o |
| Responsabilidades |  | Responsabilidades |
| La Clase Auto puede:
encenderMotor
encenderLuces
avanzar
retroceder
estacionar
obtenerNivelCombustible |  | Lo que el objeto puede hacer lo toma
de la clase, es decir el objeto puede
hacer lo que está definido en la Clase
de la que se creó:
encenderMotor
encenderLuces
avanzar
retroceder
estacionar
obtenerNivelCombustible |


#### Tabla 2 — Página 6

|  | Estado = Atributo + Valor
En un momento de tiempo |
| --- | --- |
| En un momento de tiem
DNI
Valores
Invariables
Legajo
Alumno
Atributos
Estado Civil
Valores
Variables
Situación
Académica | En un momento de tiem |
|  |  |


#### Página 7

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
¿QUÉ SABE O
QUE TIENE EL ¿QUÉ ES? ¿Qué lo
OBJETO? distingue de los
demás objetos?
Identidad
Estado
Comporta
¿QUÉ PUEDE
miento
HACER EL ✓ Los atributos que son variables y que al
OBJETO?
cambiar su valor hacen que el objeto se
comporte de forma diferente.
Estado = Atributo + Valor
En un momento de tiempo
getDni
DNI
No afectados
Valores
por el estado
Invariables
Legajo
setLegajo
Alumno
Métodos
Atributos
inscribirmeACursar
Estado Civil
Si afectados
Valores
por el estado
Variables
Situación inscribirmeARendir
Académica


#### Tabla 1 — Página 7

|  | Estado = Atributo + Valor
En un momento de tiempo |
| --- | --- |
| En un momento de tiem
DNI
Valores
Invariables
Legajo
Alumno
Atributos
Estado Civil
Valores
Variables
Situación
Académica | En un momento de tiem |
|  |  |


#### Tabla 2 — Página 7

| comporte de forma diferent
getDni
No afectados
por el estado
setLegajo
Métodos
inscribirmeACursar
Si afectados
por el estado
inscribirmeARendir |
| --- |
|  |


#### Página 8

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Caso de Estudio:
Pizzería de Venta
en Mostrador


#### Tabla 1 — Página 8

|  |  |  |  |
| --- | --- | --- | --- |
|  |  | Caso de Estudio:
Pizzería de Venta
en Mostrador | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN |
|  |  |  |  |


#### Página 9

Caso de Estudio: Pizzería
Reglas de Negocio para el Sistema de Pizzería de Venta en Mostrador
de Venta en Mostrador CÁTEDRA DE DISEÑO DE SISTEMAS
Precio de las El precio de las pizzas depende de la variedad, el tipo y el tamaño.
DE INFORMACIÓN
pizzas
Un pedido puede modificarse (agregando o quitando ítems
Modificación del pedido, modificando la cantidad en algún ítem), mientras esté
pendiente de preparación.
de un pedido
Un pedido pueden cancelarse inclusive hasta cuando esté finalizado
Cancelación de preparar, es decir justo antes de que sea entregado al cliente. La
cancelación del pedido implica cancelar todos los ítems del pedido.
de un pedido
En el momento de la entrega se registra la hora de entrega y se
Cierre y cierra el pedido.
Facturación Cuando el pedido está preparado se genera una factura para su
del Pedido. cobro y se entrega la o las pizzas al cliente.
Cobro Cuando el cliente paga se actualizada el estado de la factura a
cobrada.
Anulación de Se debe poder anular la factura en caso de que así se requiera.
Factura
Alcances
:
Objetivo:
• Administrar pizzas con sus precios
Administrar los pedidos de venta de
• Administrar variedades, tamaños, y tipos de pizzas
pizza y el cobro de estos, brindar
• Gestionar pedidos de pizzas
información resultante de la gestión.
• Gestionar la facturación de los pedidos y el cobro
• Generar reportes relacionas con la venta de pizzas.


#### Tabla 1 — Página 9

|  |
| --- |
|  |


#### Tabla 2 — Página 9

|  | CÁTEDRA DE DISEÑO DE SISTEMA
El precio de las pizzas depende de la variedad, el tipo y el tamaño.
DE INFORMACIÓN |
| --- | --- |
|  | Un pedido puede modificarse (agregando o quitando ítems
del pedido, modificando la cantidad en algún ítem), mientras esté
pendiente de preparación. |
|  | Un pedido pueden cancelarse inclusive hasta cuando esté finalizado
de preparar, es decir justo antes de que sea entregado al cliente. La
cancelación del pedido implica cancelar todos los ítems del pedido. |
|  | En el momento de la entrega se registra la hora de entrega y se
cierra el pedido.
Cuando el pedido está preparado se genera una factura para su
cobro y se entrega la o las pizzas al cliente. |
|  | Cuando el cliente paga se actualizada el estado de la factura a
cobrada. |
|  | Se debe poder anular la factura en caso de que así se requiera. |
|  |  |
| Alcances
:
Objetivo:
• Administrar pizzas con sus precios
Administrar los pedidos de venta de
• Administrar variedades, tamaños, y tipos de pizzas
pizza y el cobro de estos, brindar
• Gestionar pedidos de pizzas
información resultante de la gestión.
• Gestionar la facturación de los pedidos y el cobro
• Generar reportes relacionas con la venta de pizzas. |  |


#### Página 10

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Vista esencial
uc Primary Use Cases
de casos de
4 Registrar
Tamaño
uso para el 10 Registrar 7 Generar reporte de
Pedido ingresos por período
Sistema de
Administrador
2 Registrar
Pizza
Pizzería con 1 Generar
Factura
Venta en 6 Generar reporte de
ventas por día de la
3 Registrar
semana
EmpleadoPizzería
Mostrador Variedad de
Pizza
5 Generar reporte de
pizzas más
demandadas


#### Página 11

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Modelo de
Dominio para la
Pizzería de
Venta en
Mostrador


#### Tabla 1 — Página 11

| Mode
Dominio
Pizze
Vent
Most | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
lo de
para la
ría de
a en
rador |
| --- | --- |


#### Página 12

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Qué clases de este modelo
necesitarían un análisis de
comportamiento
dependiente del estado?
• Que tengan un atributo
referenciando a la clase Estado
es un indicador significativo, sin
embargo no es el único,
• Hay clases que tienen atributos
propios que al variar hacen que
la clase modifique su
comportamiento, por ejemplo:
fechaDeDevolucion, de un
objeto préstamo en una
Biblioteca.


#### Tabla 1 — Página 12

| Qué clases de este modelo
necesitarían un análisis de
comportamiento
dependiente del estado?
• Que tengan un atributo
referenciando a la clase Estado
es un indicador significativo, sin
embargo no es el único,
• Hay clases que tienen atributos
propios que al variar hacen que
la clase modifique su
comportamiento, por ejemplo:
fechaDeDevolucion, de un
objeto préstamo en una
Biblioteca. | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN |
| --- | --- |


#### Página 13

Caso de Estudio: Pizzería
Reglas de Negocio para el Sistema de Pizzería de Venta en Mostrador
de Venta en Mostrador CÁTEDRA DE DISEÑO DE SISTEMAS
Precio de las El precio de las pizzas depende de la variedad, el tDiEp oIN FyO eRlM tAaCmIÓaNño.
pizzas
Modificación Un pedido puede modificarse (agregando o quitando ítems
de un pedido del pedido, modificando la cantidad en algún ítem), mientras esté
pendiente de preparación.
Cancelación de Un pedido pueden cancelarse inclusive hasta cuando esté finalizado
un pedido de preparar, es decir justo antes de que sea entregado al cliente. La
cancelación del pedido implica cancelar todos los ítems del pedido.
Cierre y En el momento de la entrega se registra la hora de entrega y se cierra
Facturación del el pedido.
Pedido. Cuando el pedido está preparado se genera una factura para su cobro
y se entrega la o las pizzas al cliente.
Cobro Cuando el cliente paga se actualizada el estado de la factura a
cobrada.
Anulación de Se debe poder anular la factura en caso de que así se requiera.
Factura


#### Tabla 1 — Página 13

| CÁTEDRA DE DISEÑO DE SISTEMAS
El precio de las pizzas depende de la variedad, el tDiEp oIN FyO eRlM tAaCmIÓaNño. |
| --- |
| Un pedido puede modificarse (agregando o quitando ítems
del pedido, modificando la cantidad en algún ítem), mientras esté
pendiente de preparación. |
| Un pedido pueden cancelarse inclusive hasta cuando esté finalizado
de preparar, es decir justo antes de que sea entregado al cliente. La
cancelación del pedido implica cancelar todos los ítems del pedido. |
| En el momento de la entrega se registra la hora de entrega y se cierra
el pedido.
Cuando el pedido está preparado se genera una factura para su cobro
y se entrega la o las pizzas al cliente. |
| Cuando el cliente paga se actualizada el estado de la factura a
cobrada. |
| Se debe poder anular la factura en caso de que así se requiera. |


#### Página 14

Reglas de Negocio para el Sistema de Pizzería de Venta en Mostrador
CÁTEDRA DE DISEÑO DE SISTEMAS
Precio de las El precio de las pizzas depende de la variedad, el tDiEp oIN FyO eRlM tAaCmIÓaNño.
pizzas
Caso de Estudio: Pizzería
de Venta en Mostrador Modificación Un pedido puede modificarse (agregando o quitando ítems
de un pedido del pedido, modificando la cantidad en algún ítem), mientras esté
pendiente de preparación.
Cancelación de Un pedido pueden cancelarse inclusive hasta cuando esté finalizado
un pedido de preparar, es decir justo antes de que sea entregado al cliente. La
cancelación del pedido implica cancelar todos los ítems del pedido.
Cierre y En el momento de la entrega se registra la hora de entrega y se
Facturación del cierra el pedido.
Pedido. Cuando el pedido está preparado se genera una factura para su
cobro y se entrega la o las pizzas al cliente.
Cobro Cuando el cliente paga se actualizada el estado de la factura a
cobrada.
Anulación de Se debe poder anular la factura en caso de que así se requiera.
Factura


#### Tabla 1 — Página 14

|  |
| --- |
| Reglas de Negocio para el Sistema de Pizzería de Venta en Mostrador
CÁTEDRA DE DISEÑO DE SISTEMAS
Precio de las El precio de las pizzas depende de la variedad, el tDiEp oIN FyO eRlM tAaCmIÓaNño.
pizzas
Caso de Estudio: Pizzería
de Venta en Mostrador Modificación Un pedido puede modificarse (agregando o quitando ítems
de un pedido del pedido, modificando la cantidad en algún ítem), mientras esté
pendiente de preparación.
Cancelación de Un pedido pueden cancelarse inclusive hasta cuando esté finalizado
un pedido de preparar, es decir justo antes de que sea entregado al cliente. La
cancelación del pedido implica cancelar todos los ítems del pedido.
Cierre y En el momento de la entrega se registra la hora de entrega y se
Facturación del cierra el pedido.
Pedido. Cuando el pedido está preparado se genera una factura para su
cobro y se entrega la o las pizzas al cliente.
Cobro Cuando el cliente paga se actualizada el estado de la factura a
cobrada.
Anulación de Se debe poder anular la factura en caso de que así se requiera.
Factura |
|  |


#### Tabla 2 — Página 14

|  | CÁTEDRA DE DISEÑO DE SISTEMAS
El precio de las pizzas depende de la variedad, el tDiEp oIN FyO eRlM tAaCmIÓaNño. |
| --- | --- |
| Modificación
de un pedido | Un pedido puede modificarse (agregando o quitando ítems
del pedido, modificando la cantidad en algún ítem), mientras esté
pendiente de preparación. |
| Cancelación de
un pedido | Un pedido pueden cancelarse inclusive hasta cuando esté finalizado
de preparar, es decir justo antes de que sea entregado al cliente. La
cancelación del pedido implica cancelar todos los ítems del pedido. |
| Cierre y
Facturación del
Pedido. | En el momento de la entrega se registra la hora de entrega y se
cierra el pedido.
Cuando el pedido está preparado se genera una factura para su
cobro y se entrega la o las pizzas al cliente. |
| Cobro | Cuando el cliente paga se actualizada el estado de la factura a
cobrada. |
| Anulación de
Factura | Se debe poder anular la factura en caso de que así se requiera. |


#### Página 15

Vamos a construir la máquina de estados para la clase Pedido
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Creación del Pedido
Se registran los pedidos que
los clientes realizan en el
mostrador, informando, el
nombre del cliente (para
llamarlo cuando el pedido
esté listo), la fecha y hora de
creación, la cantidad de pizzas
de cada variedad, tipo y
tamaño. Por ejemplo: 2 pizzas
de molde de 8 porciones de
jamón y morrones y 1 pizza a
la piedra de 4 porciones de
palmitos).


#### Página 16

Vamos a construir la máquina de estados para la clase Pedido
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Tratamiento del Pedido
✓ Un pedido puede modificarse
(agregando o quitando ítems del
pedido, modificando la cantidad en
algún ítem), mientras esté pendiente
de preparación.
✓ Cuando el maestro pizzero va a iniciar
la preparación del pedido debe
informarlo actualizando el estado,
también debe informar que el pedido
está preparado para que se lo pueda
entregar al cliente y facturarlo.


#### Página 17

Vamos a construir la máquina de estados para la clase Pedido
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Tratamiento del Pedido
✓ Un pedido puede modificarse
(agregando o quitando ítems del
pedido, modificando la cantidad
en algún ítem), mientras esté
pendiente de preparación.
✓ Cuando el maestro pizzero va a
iniciar la preparación del pedido
debe informarlo actualizando el
estado, también debe informar
que el pedido está preparado
para que se lo pueda entregar al
cliente y facturarlo.


#### Página 18

Vamos a construir la máquina de estados para la clase Pedido
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Facturación del Pedido
✓ Cuando el pedido está preparado
se genera una factura para su
cobro y se entrega la o las pizzas
al cliente.
✓ En el momento de la entrega se
registra la hora de entrega y se
cierra el pedido.


#### Página 19

Vamos a construir la máquina de estados para la clase Pedido
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Cancelación del Pedido
✓ Un pedido puede cancelarse
inclusive hasta cuando esté
finalizado de preparar, es decir
justo antes de que sea entregado al
cliente. La cancelación del pedido
implica cancelar todos los ítems del
pedido.
Hasta este momento hemos identificado todos los estados por los que pueden pasar los objetos de la clase
Pedido, con las transiciones permitidas entre esos estados y hemos indicado cuáles de estos estados son
iniciales o finales (con los Pseudoestados correspondientes)


#### Página 20

Ahora nos ocupamos de las transiciones
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN


#### Página 21

A las transiciones le definimos métodos y casos de uso
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Máquina de Estados para la Clase Pedido


#### Página 22

¿La modificación del pedido afecta el estado del pedido?
¿Y que hay de la clase DetallePedido? CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Modificación del Pedido
✓ Un pedido puede
modificarse (agregando o
quitando ítems del pedido,
modificando la cantidad en
algún ítem), mientras esté
pendiente de preparación.
A las transiciones le definimos métodos y casos de uso
y cuando es necesario condiciones de control


#### Tabla 1 — Página 22

|  |
| --- |
|  |


#### Página 23

¿La modificación del pedido afecta el estado del pedido?
¿Y qué hay de la clase DetallePedido? CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN


#### Página 24

Vista de
Vista de la
Comportamiento
Estructura
(Dinámica)
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Vista de
Comportamiento
(Estática)


#### Página 25

Vista de
Vista de la
Comportamiento
Estructura
(Dinámica)
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Vista de
Comportamiento
(Estática)


#### Página 26

Ahora bien, si tenemos un requerimiento como este:
CÁTEDRA DE DISEÑO DE SISTEMAS
“Necesito conocer cuánto tiempo está el pedido en cada estado”
DE INFORMACIÓN
¿Con esta estructura de clases podemos satisfacerlo? NO
¿La máquina de estados se ve afectada con este requerimiento?
NO
No es ni tuyo, ni mío
es algo que pasa
entre nosotros


#### Página 27

Con esta estructura de clases SI podemos satisfacerlo
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
La máquina de estados NO se ve afectada con este requerimiento


#### Página 28

Repasando lo que vimos…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Diagramas de UML 2.0
Modelo de
PUD como contexto
Requerimientos
Objetos con
Modelado con Diag.
Workflow de Análisis Modelo de Análisis
comportamiento
De Máquina de
dependiente del estado
Estados
4/1/2026 Judith Meles 28


#### Tabla 1 — Página 28

| CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Diagramas de UML 2.0
Modelo de
PUD como contexto
Requerimientos
Objetos con
Modelado con Diag.
Workflow de Análisis Modelo de Análisis
comportamiento
De Máquina de
dependiente del estado
Estados
4/1/2026 Judith Meles |
| --- |
|  |


#### Página 29

Sobre el Diagrama de Máquina de Estados
CÁTEDRA DE DISEÑO DE SISTEMAS
vimos estos elementos para modelar…
DE INFORMACIÓN
c l a s s C l a s
E
s
s
M
t a
o
d
d
o
e l
c l a
E
s
s
s
t a
C
d
l a
o
s
I
s
n
.
i
.
c
.
i a l
c l a
E
s
s
s
t a
C
d
l a
o
s s
F
.
I
.
n
.
a l
Transición condición de control
evento disparador
o caso de uso
.
.
.
.
.
estado origen
estado destino
4/1/2026 Judith Meles 29


#### Página 30

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Finalmente…
Muchas
Gracias!!!


### 🖼️ Imágenes Extraídas (124 imágenes)

#### Imagen 1 — Página 1 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 2 — Página 1 (51.0 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 3 — Página 2 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 4 — Página 2 (14.0 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 5 — Página 2 (13.6 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 6 — Página 2 (13.4 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 7 — Página 2 (13.4 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 8 — Página 2 (13.4 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 9 — Página 2 (13.1 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 10 — Página 2 (13.4 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 11 — Página 2 (13.5 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 12 — Página 2 (16.3 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 13 — Página 3 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 14 — Página 3 (136.5 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 15 — Página 3 (21.5 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 16 — Página 3 (56.2 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 17 — Página 4 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 18 — Página 4 (11.5 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 19 — Página 4 (13.9 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 20 — Página 4 (11.8 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 21 — Página 4 (12.8 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 22 — Página 4 (11.9 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 23 — Página 4 (12.8 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 24 — Página 4 (12.4 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 25 — Página 4 (10.3 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 26 — Página 4 (6.5 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 27 — Página 4 (7.1 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 28 — Página 4 (12.5 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 29 — Página 4 (7.1 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 30 — Página 4 (11.8 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 31 — Página 5 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 32 — Página 5 (11.5 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 33 — Página 5 (13.9 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 34 — Página 5 (11.8 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 35 — Página 5 (12.8 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 36 — Página 5 (11.9 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 37 — Página 5 (12.8 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 38 — Página 5 (12.4 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 39 — Página 5 (10.3 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 40 — Página 5 (12.0 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 41 — Página 5 (6.1 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 42 — Página 5 (12.5 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 43 — Página 5 (12.6 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 44 — Página 5 (11.8 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 45 — Página 6 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 46 — Página 6 (18.3 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 47 — Página 6 (17.6 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 48 — Página 6 (51.1 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 49 — Página 6 (24.9 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 50 — Página 7 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 7**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `7`
> *(Para ver: abrir PDF en página 7)*


#### Imagen 51 — Página 7 (24.5 KB)

> 📄 **Diagrama/Imagen — Página 7**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `7`
> *(Para ver: abrir PDF en página 7)*


#### Imagen 52 — Página 7 (43.3 KB)

> 📄 **Diagrama/Imagen — Página 7**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `7`
> *(Para ver: abrir PDF en página 7)*


#### Imagen 53 — Página 8 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 8**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `8`
> *(Para ver: abrir PDF en página 8)*


#### Imagen 54 — Página 8 (172.5 KB)

> 📄 **Diagrama/Imagen — Página 8**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `8`
> *(Para ver: abrir PDF en página 8)*


#### Imagen 55 — Página 9 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 56 — Página 9 (172.5 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 57 — Página 10 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 10**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `10`
> *(Para ver: abrir PDF en página 10)*


#### Imagen 58 — Página 11 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 11**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `11`
> *(Para ver: abrir PDF en página 11)*


#### Imagen 59 — Página 11 (178.3 KB)

> 📄 **Diagrama/Imagen — Página 11**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `11`
> *(Para ver: abrir PDF en página 11)*


#### Imagen 60 — Página 12 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 12**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `12`
> *(Para ver: abrir PDF en página 12)*


#### Imagen 61 — Página 12 (178.5 KB)

> 📄 **Diagrama/Imagen — Página 12**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `12`
> *(Para ver: abrir PDF en página 12)*


#### Imagen 62 — Página 13 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 13**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `13`
> *(Para ver: abrir PDF en página 13)*


#### Imagen 63 — Página 13 (172.5 KB)

> 📄 **Diagrama/Imagen — Página 13**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `13`
> *(Para ver: abrir PDF en página 13)*


#### Imagen 64 — Página 14 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 65 — Página 14 (172.5 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 66 — Página 15 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 67 — Página 15 (5.8 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 68 — Página 15 (16.7 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 69 — Página 16 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 70 — Página 16 (5.2 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 71 — Página 16 (5.5 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 72 — Página 16 (11.8 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 73 — Página 17 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 74 — Página 17 (4.9 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 75 — Página 17 (5.3 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 76 — Página 17 (17.4 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 77 — Página 18 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 18**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `18`
> *(Para ver: abrir PDF en página 18)*


#### Imagen 78 — Página 18 (23.1 KB)

> 📄 **Diagrama/Imagen — Página 18**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `18`
> *(Para ver: abrir PDF en página 18)*


#### Imagen 79 — Página 19 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 19**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `19`
> *(Para ver: abrir PDF en página 19)*


#### Imagen 80 — Página 19 (39.0 KB)

> 📄 **Diagrama/Imagen — Página 19**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `19`
> *(Para ver: abrir PDF en página 19)*


#### Imagen 81 — Página 20 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 82 — Página 20 (43.7 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 83 — Página 20 (27.6 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 84 — Página 21 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 21**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `21`
> *(Para ver: abrir PDF en página 21)*


#### Imagen 85 — Página 21 (56.7 KB)

> 📄 **Diagrama/Imagen — Página 21**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `21`
> *(Para ver: abrir PDF en página 21)*


#### Imagen 86 — Página 21 (43.4 KB)

> 📄 **Diagrama/Imagen — Página 21**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `21`
> *(Para ver: abrir PDF en página 21)*


#### Imagen 87 — Página 21 (27.6 KB)

> 📄 **Diagrama/Imagen — Página 21**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `21`
> *(Para ver: abrir PDF en página 21)*


#### Imagen 88 — Página 22 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*


#### Imagen 89 — Página 22 (143.8 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*


#### Imagen 90 — Página 22 (259.2 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*


#### Imagen 91 — Página 23 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 92 — Página 23 (78.7 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 93 — Página 23 (48.9 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 94 — Página 23 (143.8 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 95 — Página 24 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 24**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `24`
> *(Para ver: abrir PDF en página 24)*


#### Imagen 96 — Página 24 (59.8 KB)

> 📄 **Diagrama/Imagen — Página 24**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `24`
> *(Para ver: abrir PDF en página 24)*


#### Imagen 97 — Página 24 (48.9 KB)

> 📄 **Diagrama/Imagen — Página 24**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `24`
> *(Para ver: abrir PDF en página 24)*


#### Imagen 98 — Página 24 (80.8 KB)

> 📄 **Diagrama/Imagen — Página 24**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `24`
> *(Para ver: abrir PDF en página 24)*


#### Imagen 99 — Página 24 (47.0 KB)

> 📄 **Diagrama/Imagen — Página 24**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `24`
> *(Para ver: abrir PDF en página 24)*


#### Imagen 100 — Página 25 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 101 — Página 25 (80.8 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 102 — Página 25 (59.8 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 103 — Página 25 (63.4 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 104 — Página 25 (48.9 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 105 — Página 25 (7.6 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 106 — Página 25 (4.9 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 107 — Página 26 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 26**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `26`
> *(Para ver: abrir PDF en página 26)*


#### Imagen 108 — Página 26 (59.8 KB)

> 📄 **Diagrama/Imagen — Página 26**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `26`
> *(Para ver: abrir PDF en página 26)*


#### Imagen 109 — Página 26 (143.8 KB)

> 📄 **Diagrama/Imagen — Página 26**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `26`
> *(Para ver: abrir PDF en página 26)*


#### Imagen 110 — Página 27 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 27**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `27`
> *(Para ver: abrir PDF en página 27)*


#### Imagen 111 — Página 27 (297.2 KB)

> 📄 **Diagrama/Imagen — Página 27**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `27`
> *(Para ver: abrir PDF en página 27)*


#### Imagen 112 — Página 27 (59.8 KB)

> 📄 **Diagrama/Imagen — Página 27**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `27`
> *(Para ver: abrir PDF en página 27)*


#### Imagen 113 — Página 28 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 114 — Página 28 (107.6 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 115 — Página 28 (59.2 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 116 — Página 28 (162.2 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 117 — Página 28 (104.6 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 118 — Página 28 (86.5 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 119 — Página 28 (69.4 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 120 — Página 28 (59.4 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 121 — Página 29 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 29**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `29`
> *(Para ver: abrir PDF en página 29)*


#### Imagen 122 — Página 29 (19.6 KB)

> 📄 **Diagrama/Imagen — Página 29**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `29`
> *(Para ver: abrir PDF en página 29)*


#### Imagen 123 — Página 30 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 30**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `30`
> *(Para ver: abrir PDF en página 30)*


#### Imagen 124 — Página 30 (14.6 KB)

> 📄 **Diagrama/Imagen — Página 30**
> PDF: [`01 Modelado Comp con Diag Maquina de Estados.pdf`](../Diapositivas y Teóricos/01 Modelado Comp con Diag Maquina de Estados.pdf) · Página `30`
> *(Para ver: abrir PDF en página 30)*



---


## 02 Modelado Comp con Diag Maquina de Estados parte 2

**Categoría:** Diapositivas y Teóricos  

**Archivo:** `02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`  

**Tamaño:** 5.49 MB  


### 📄 Contenido de Texto

#### Página 1

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Modelado de Comportamiento con el
Diagrama de Máquina de Estados
3/16/2026 Judith Meles 1


#### Página 2

Workflow de Análisis como proceso…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Salida
Entrada
Workflow
de Análisis
3/16/2026 Judith Meles 2


#### Página 3

¿Cómo construimos el Modelo de Análisis?
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Herramienta: Diagrama
Vista Estática
de Clases
Realizaciones de
Casos de Uso de
Herramienta: Diagrama
Análisis
de Comunicación
Vista Dinámica
Herramienta Diagrama
de Secuencia
Herramienta: Diagrama de Clases
Clases de Análisis
Modelo de
Análisis
Diagrama de Máquina de Estados
Herramienta: Diagrama de
Paquetes de Análisis
Paquetes
Descripción de la
Arquitectura
3/16/2026 Judith Meles 3


#### Página 4

¿Qué es Diagrama de Máquina de Estados?
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Un diagrama de transición de estados muestra una máquina de estados,
la cual especifica la secuencia de estados en los que un objeto puede
estar, los eventos y condiciones que causan que los objetos alcancen
esos estados, y las acciones que ocurren cuando esos estados son
alcanzados.
Son usados para modelar el comportamiento dinámico de un
elemento de modelado, comúnmente clases cuyos objetos varían
el comportamiento en función de su estado.


#### Página 5

Diagrama de Máquina de Estados
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
CLASIFICACIÓN: De comportamiento, dinámico, lógico.
➔
Uso:
➔
Explorar el comportamiento de una clase, actor, subsistema
▪
o componente.
Modelar sistemas de tiempo real.
▪
Contiene comúnmente:
➔
▪ Estados
▪ Transiciones
▪ Eventos


#### Página 6

Sobre el Diagrama de Máquina de Estados
CÁTEDRA DE DISEÑO DE SISTEMAS
vimos estos elementos para modelar…
DE INFORMACIÓN
c l a s s C l a s
E
s
s
M
t a
o
d
d
o
e l
c l a
E
s
s
s
t a
C
d
l a
o
s
I
s
n
.
i
.
c
.
i a l
c l a
E
s
s
s
t a
C
d
l a
o
s s
F
.
I
.
n
.
a l
condición de control
evento disparador
o caso de uso
.
.
.
.
.
estado origen
estado destino
3/16/2026 Judith Meles 6


#### Página 7

Caso de Estudio: Software
para Gestión de
Requerimientos


#### Tabla 1 — Página 7

|  |
| --- |
|  |


#### Tabla 2 — Página 7

|  |  |
| --- | --- |
|  | Caso de Estudio: Software
para Gestión de
Requerimientos |
|  |  |
|  |  |


#### Página 8

Reglas de Negocio para la Solicitud de Requerimientos
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
• Las SR las crea el cliente ingresando los siguientes datos: Cliente (si no está registrado como cliente, primero deberá
registrarse); producto de software asociado (si existe), tipo de SR (selección de uno de los indicados anteriormente) y una
descripción de lo que necesita. Al crearse la solicitud se le asigna un número y se registra la fecha y hora de creación.
• La SR creada por el cliente queda pendiente de análisis por parte de un Analista de Requerimientos de la empresa que será
el responsable de evaluar la pertinencia y factibilidad de lo requerido. De análisis de factibilidad realizado, puede resultar que
la SR sea desestimada, o derivada para que sea preparada una propuesta que responda a lo pedido por el Cliente.
• Luego, un Consultor asignado toma la SR y prepara un Propuesta de Servicios y se la envía al cliente para su consideración
• El Cliente recibe la propuesta de servicio asociada a la SR y pueda aceptarla o rechazarla.
• Si el Cliente acepta la propuesta, la SR queda en estado pendiente de inicio. Dado que la empresa necesita un tiempo para
armar el equipo de desarrollo realizará el trabajo.
• Para realizar el trabajo, se inicia un proyecto de desarrollo, que pasará por diferentes etapas (Requerimientos, Análisis &
Diseño, Implementación, Prueba y Despliegue); el proyecto de desarrollo termina con la aceptación del despliegue por parte
del Cliente.
• Con la aceptación del despliegue por parte del cliente se cierra la SR que dio origen al proyecto de desarrollo de software.
• Independientemente de las razones y los aspectos contractuales, un Cliente puede cancelar la SR en cualquier momento
anterior a la aceptación del despliegue del producto de software.
• También debe contemplarse la situación de interrupción del trabajo en cualquiera de las etapas en las que personal de la
empresa esté dedicando tiempo a una SR, para que el tiempo no sea computado como esfuerzo asociado. Cuando se retoma
el trabajo, la SR vuelve al estado en el que estaba al momento de la interrupción; a partir de ahí seguirá con la evolución
correspondiente a ese estado.
3/16/2026 Judith Meles 8


#### Página 9

Vamos cómo se vé la máquina de estados de la clase
SolicitudDeRequerimientos, con lo que sabemos…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN


#### Página 10

Reglas de Negocio para la Solicitud de Requerimientos
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
• Para realizar el trabajo, se inicia un proyecto de desarrollo, que pasará por
diferentes etapas (Requerimientos, Análisis & Diseño, Implementación,
Prueba y Despliegue); el proyecto de desarrollo termina con la aceptación del
despliegue por parte del Cliente.
• Con la aceptación del despliegue por parte del cliente se cierra la SR que dio
origen al proyecto de desarrollo de software.
• Es necesario poder informar a los clientes del estado de la solicitud de
requerimientos en todo momento y del avance del proyecto de desarrollo
asociado a la SR.
• También es necesario poder informar cuánto tiempo permanece una solicitud
en cada estado y quién es el responsable de cada intervención (cambio de
estado).
3/16/2026 Judith Meles 10


#### Página 11

Veamos cómo se ve la máquina de estados de la clase
SolicitudDeRequerimientos, ahora…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN


#### Página 12

Vamos cómo se ve la máquina de estados de la clase
SolicitudDeRequerimientos, ahora…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN


#### Página 13

¿Qué vemos dentro del estado compuesto
EnDesarrolloProyecto?
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Proyecto de Desarrollo
✓ Para realizar el trabajo, se inicia un proyecto de desarrollo, que pasará por diferentes etapas (Requerimientos,
Análisis & Diseño, Implementación, Prueba y Despliegue); el proyecto de desarrollo termina con la
aceptación del despliegue por parte del Cliente.
✓ Es necesario poder informar a los clientes del estado de la solicitud de requerimientos en todo momento y del
avance del proyecto de desarrollo asociado a la SR.
✓ Esto es una simplificación!!! El desarrollo de software no es lineal, ni secuencial, es un
proceso de refinamientos sucesivos.


#### Página 14

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
✓ También es necesario poder informar quién es el
responsable de cada intervención (cambio de
estado).
✓ Es necesario poder informar a los clientes del estado
de la solicitud de requerimientos en todo momento
y del avance del proyecto de desarrollo asociado a
la SR.


#### Página 15

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN


#### Página 16

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN


#### Página 17

¿Qué pasa si la regla de negocio cambia y dice esto?
“Independientemente de las razones y los aspectos contractuales, un Cliente puede
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
cancelar la SR en cualquier momento anterior al inicio del despliegue del producto de
software. “
La transición a
Cancelada, se quita


#### Tabla 1 — Página 17

|  | ¿Qué pasa si la regla de negocio cambia y dice esto? |
| --- | --- |
| “Independientemente de las razones y los aspectos contractuales, un Cliente puede
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
cancelar la SR en cualquier momento anterior al inicio del despliegue del producto de
software. “ |  |


#### Página 18

El pseudoestado Exit Point se puede modelar de cualquiera
de estas dos formas…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN


#### Página 19

Repasemos los elementos de modelado para
CÁTEDRA DE DISEÑO DE SISTEMAS
el Diagrama de Máquina de Estados que
DE INFORMACIÓN
utilizamos en la cátedra:
3/16/2026 Judith Meles 19
c l a
E
s
s
s
t a
C
d
l a
o
s
I
s
n
.
i
.
c
.
i a l
c l a
E
s
s
s
t a
C
d
l a
o
s
F
s .
I
.
n
.
a l
class ...
Historia
c l
c
a s
l a
s C
s
l
s
a s
E
C
E
s M
s t a
l a
s t
o
d
s
a
d
o
s
d
e
M
o
l
C
o
o
d
m
e l
p u e s t o
Esto vimos en la clase anterior
Pseudoestados
En esta clase vimos:


#### Página 20

Algunas cosas para tener cuenta sobre el modelado con
Diagrama de Máquina de Estados CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
UML 2.0 tiene más elementos de modelado que los que vemos
en esta materia.
El estado compuesto se indica con el símbolo infinito en la
esquina inferior del estado. Para ver la máquina de estado
contenida hacemos doble click en el estado compuesto.
Las máquinas de estado dentro de un estado compuesto
pueden no tener estado final.
Estado inicial, estado final, historia y Exit son PSEUDOESTADOS.
3/16/2026 Judith Meles 20


#### Página 21

Para terminar, recordemos…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
El estado es el valor de los atributos en un momento de
tiempo
No todas las clases necesitan una máquina de estados,
cuáles si?
La máquina de estados representa los estados por los que
todos los objetos de la clase modelada pueden pasar.
Los objetos NO van a pasar por todos los estados
identificados.
La máquina de estado de una clase se construye en función
de uno o más atributos de la clase.
Mantener la integración y la consistencia entre las vistas del
software.


#### Página 22

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Finalmente…
Muchas
Gracias!!!


### 🖼️ Imágenes Extraídas (83 imágenes)

#### Imagen 1 — Página 1 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 2 — Página 1 (51.0 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 3 — Página 2 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 4 — Página 2 (136.5 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 5 — Página 2 (21.5 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 6 — Página 2 (56.2 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 7 — Página 3 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 8 — Página 3 (11.3 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 9 — Página 3 (13.7 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 10 — Página 3 (11.6 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 11 — Página 3 (12.9 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 12 — Página 3 (11.7 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 13 — Página 3 (13.0 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 14 — Página 3 (12.6 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 15 — Página 3 (10.1 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 16 — Página 3 (11.8 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 17 — Página 3 (6.0 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 18 — Página 3 (12.2 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 19 — Página 3 (11.9 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 20 — Página 3 (11.7 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 21 — Página 4 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 22 — Página 4 (6.0 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 23 — Página 4 (6.1 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 24 — Página 4 (11.0 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 25 — Página 4 (6.5 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 26 — Página 4 (6.5 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 27 — Página 4 (7.9 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 28 — Página 4 (8.6 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 29 — Página 4 (5.5 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 30 — Página 4 (5.2 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 31 — Página 4 (6.5 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 32 — Página 4 (4.9 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 33 — Página 4 (5.7 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 34 — Página 4 (5.8 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 35 — Página 5 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 36 — Página 5 (5.1 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 37 — Página 5 (161.3 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 38 — Página 6 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 39 — Página 6 (19.6 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 40 — Página 7 (39.5 KB)

> 📄 **Diagrama/Imagen — Página 7**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `7`
> *(Para ver: abrir PDF en página 7)*


#### Imagen 41 — Página 8 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 8**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `8`
> *(Para ver: abrir PDF en página 8)*


#### Imagen 42 — Página 9 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 43 — Página 9 (362.6 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 44 — Página 10 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 10**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `10`
> *(Para ver: abrir PDF en página 10)*


#### Imagen 45 — Página 11 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 11**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `11`
> *(Para ver: abrir PDF en página 11)*


#### Imagen 46 — Página 11 (418.1 KB)

> 📄 **Diagrama/Imagen — Página 11**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `11`
> *(Para ver: abrir PDF en página 11)*


#### Imagen 47 — Página 12 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 12**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `12`
> *(Para ver: abrir PDF en página 12)*


#### Imagen 48 — Página 12 (438.1 KB)

> 📄 **Diagrama/Imagen — Página 12**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `12`
> *(Para ver: abrir PDF en página 12)*


#### Imagen 49 — Página 13 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 13**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `13`
> *(Para ver: abrir PDF en página 13)*


#### Imagen 50 — Página 13 (35.0 KB)

> 📄 **Diagrama/Imagen — Página 13**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `13`
> *(Para ver: abrir PDF en página 13)*


#### Imagen 51 — Página 14 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 52 — Página 14 (235.3 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 53 — Página 14 (35.0 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 54 — Página 14 (524.9 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 55 — Página 15 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 56 — Página 15 (35.0 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 57 — Página 15 (154.5 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 58 — Página 15 (524.9 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 59 — Página 15 (235.3 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 60 — Página 15 (6.7 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 61 — Página 16 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 62 — Página 16 (35.0 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 63 — Página 16 (154.5 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 64 — Página 16 (524.9 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 65 — Página 16 (235.3 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 66 — Página 17 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 67 — Página 17 (524.9 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 68 — Página 17 (79.9 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 69 — Página 18 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 18**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `18`
> *(Para ver: abrir PDF en página 18)*


#### Imagen 70 — Página 18 (79.9 KB)

> 📄 **Diagrama/Imagen — Página 18**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `18`
> *(Para ver: abrir PDF en página 18)*


#### Imagen 71 — Página 18 (70.0 KB)

> 📄 **Diagrama/Imagen — Página 18**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `18`
> *(Para ver: abrir PDF en página 18)*


#### Imagen 72 — Página 19 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 19**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `19`
> *(Para ver: abrir PDF en página 19)*


#### Imagen 73 — Página 19 (11.7 KB)

> 📄 **Diagrama/Imagen — Página 19**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `19`
> *(Para ver: abrir PDF en página 19)*


#### Imagen 74 — Página 20 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 75 — Página 20 (9.2 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 76 — Página 20 (50.1 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 77 — Página 20 (20.0 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 78 — Página 20 (26.8 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 79 — Página 20 (88.3 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 80 — Página 21 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 21**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `21`
> *(Para ver: abrir PDF en página 21)*


#### Imagen 81 — Página 21 (5.4 KB)

> 📄 **Diagrama/Imagen — Página 21**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `21`
> *(Para ver: abrir PDF en página 21)*


#### Imagen 82 — Página 22 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*


#### Imagen 83 — Página 22 (14.6 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`02 Modelado Comp con Diag Maquina de Estados parte 2.pdf`](../Diapositivas y Teóricos/02 Modelado Comp con Diag Maquina de Estados parte 2.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*



---


## 03 Realizaciones de CU - Diagrama de Secuencia

**Categoría:** Diapositivas y Teóricos  

**Archivo:** `03 Realizaciones de CU - Diagrama de Secuencia.pdf`  

**Tamaño:** 5.11 MB  


### 📄 Contenido de Texto

#### Página 1

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realizaciones de CU – Diagrama de
Secuencia y Diagrama de Clases
4/22/2023 Judith Meles – Laura Covaro 1


#### Página 2

Diagramas en UML 2.0
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
De Clases
Modelan
Modelan Clases De Paquetes
Estructura
De Estructura Compuesta
De Componentes
De Despliegue
Modela
De Objetos
Objetos
Diagramas
De Casos de Uso
Modelan De Actividad
Clases
De Máquina de Estados
De Comunicación
Modelan
Comportamiento
De Secuencia
De Interacción
De Timing
(Modelan Objetos)
De Descripción de Interacción
4/22/2023 Judith Meles 2


#### Página 3

Proceso de Desarrollo y sus Artefactos
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Modelado de
Modelo
Negocios l
de Negocios
Cada
workflow
Modelo
Requerimientos
está
de Requerimientos
asociado
con uno o
más Modelo
Análisis
Los diagramas de UML
modelos. Análisis
construyen las vistas en
cada modelo
Diseño Modelo Modelo de
Modelo
Diseño D De e s s p p l l i i e e g g u u e e
Modelo
Implementación
Impl.
Modelo de
Modelo
Prueba
Prueba
Prueba


#### Tabla 1 — Página 3

|  |
| --- |
| Modelo
l
de Negocios |


#### Tabla 2 — Página 3

|  |
| --- |
| Modelo
de Requerimientos |


#### Tabla 3 — Página 3

|  |
| --- |
| Modelo
Análisis |


#### Tabla 4 — Página 3

|  |
| --- |
| Modelo
Diseño |


#### Tabla 5 — Página 3

|  |
| --- |
| Modelo de
Modelo
Despliegue
Despliegue |


#### Tabla 6 — Página 3

|  |
| --- |
| Modelo
Impl. |


#### Tabla 7 — Página 3

|  |
| --- |
| Modelo de
Modelo
Prueba
Prueba |


#### Página 4

Workflow de Análisis como proceso…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Salida
Entrada
Workflow
de Análisis
4/22/2023 Judith Meles 4


#### Página 5

¿Cómo construimos el Modelo de Análisis?
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Herramienta: Diagrama
Vista Estática
de Clases
Realizaciones de
Casos de Uso de
Herramienta: Diagrama
Análisis
de Comunicación
Vista Dinámica
Herramienta Diagrama
de Secuencia
Herramienta: Diagrama de Clases
Clases de Análisis
Modelo de
Herramienta: Diagrama de
Análisis
Máquina de Estados
Herramienta: Diagrama de
Paquetes de Análisis
Paquetes
Descripción de la
Arquitectura
4/22/2023 Judith Meles 5


#### Página 6

¿Cómo construimos el Modelo de Análisis?
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Herramienta: Diagrama
Vista Estática
de Clases
Realizaciones de
Casos de Uso de
Herramienta: Diagrama
Análisis
de Comunicación
Vista Dinámica
Herramienta Diagrama
de Secuencia
Herramienta: Diagrama de Clases
Clases de Análisis
Modelo de
Herramienta: Diagrama de
Análisis
Máquina de Estados
Paquetes de Herramienta: Diagrama de
Análisis Paquetes
Descripción de la
Arquitectura
4/22/2023 Judith Meles 6


#### Página 7

Clases del Análisis
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Clase de Entidad: modela información que podría ser persistente y que
puede sobrevivir a una ejecución de un sistema.
Clase límite o frontera (Boundary) modela el comportamiento e
información que es dependiente de la frontera del sistema con el
ambiente. Modela todo lo que concierne a cualquier vínculo sistema-actor
Clases de
Fabricación
Pura
Clase de control modela funcionalidad que operar sobre varios objetos
diferentes de entidad, haciendo algunos cálculos y retornando el
resultado al objeto de boundary.
Contiene comportamiento de la lógica de negocio definida en un caso de
uso.
Tiene responsabilidades de coordinación de la ejecución de un caso de uso
y funciona como intermediario entre las clases de Boundary y las de
entidad.
4/22/2023 Judith Meles 7


#### Página 8

Realizaciones de CU: Vista Dinámica –
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Diagrama de Secuencia
Laura Covaro


#### Página 9

Realizaciones de CU: Vista Dinámica –
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Diagrama de Secuencia
Laura Covaro


#### Página 10

Realizaciones de CU: Vista Dinámica –
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Diagrama de Secuencia


#### Página 11

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Modelo de
Dominio del
Festival de
Folklore


#### Página 12

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Caso de Estudio: Festival de
Folklore – CU Registrar
Festival
Laura Covaro


#### Tabla 1 — Página 12

|  |
| --- |
|  |


#### Tabla 2 — Página 12

|  | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Caso de Estudio: Festival de
Folklore – CU Registrar
Festival
Laura Covaro |
| --- | --- |


#### Página 13

CÁTEDRA DE DISEÑO DE SISTEMAS
Prototipo de Interfaz
DE INFORMACIÓN
de Usuario
Prototipos para Registrar Festival


#### Página 14

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Laura Covaro


#### Tabla 1 — Página 14

|  |
| --- |
|  |


#### Tabla 2 — Página 14

|  | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Laura Covaro |
| --- | --- |


#### Página 15

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realización de
CU Registrar
Festival:
Vista Dinámica -
Diagrama de
Secuencia
Laura Covaro


#### Tabla 1 — Página 15

|  |  |  |  |
| --- | --- | --- | --- |
|  |  |  |  |
| Realización
CU Regist
Festival:
Vista Dinám
Diagrama
Secuenci |  |  | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
de
rar
ica -
de
a
Laura Covaro |


#### Página 16

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realización de
CU Registrar
Festival:
Vista Dinámica -
Diagrama de
Secuencia
Laura Covaro


#### Tabla 1 — Página 16

|  |
| --- |
|  |


#### Tabla 2 — Página 16

| Realización
CU Regist
Festival:
Vista Dinám
Diagrama
Secuenci | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
de
rar
ica -
de
a
Laura Covaro |
| --- | --- |


#### Página 17

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realización de
CU Registrar
Festival:
Vista Dinámica -
Diagrama de
Secuencia
Laura Covaro


#### Tabla 1 — Página 17

|  |
| --- |
|  |


#### Tabla 2 — Página 17

| Realización
CU Regist
Festival:
Vista Dinám
Diagrama
Secuenci | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
de
rar
ica -
de
a
Laura Covaro |
| --- | --- |


#### Página 18

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realización de
CU Registrar
Festival:
Vista Dinámica -
Diagrama de
Secuencia
Laura Covaro


#### Tabla 1 — Página 18

|  |
| --- |
|  |


#### Tabla 2 — Página 18

| Realización
CU Regist
Festival:
Vista Dinám
Diagrama
Secuenci | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
de
rar
ica -
de
a
Laura Covaro |
| --- | --- |


#### Página 19

Realizaciones de CU: Vista Dinámica –
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Diagrama de Secuencia
Laura Covaro


#### Página 20

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realización de
CU Registrar
Festival:
Vista Dinámica -
Diagrama de
Secuencia
*
Laura Covaro


#### Tabla 1 — Página 20

|  |
| --- |
|  |


#### Tabla 2 — Página 20

|  |  |
| --- | --- |
| Realización
CU Regist
Festival:
Vista Dinám
Diagrama
Secuenci | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
de
rar
ica -
de
a
*
Laura Covaro |
|  |  |


#### Tabla 3 — Página 20

| Laura Covaro |
| --- |
|  |


#### Página 21

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realización de
CU Registrar
Festival:
Vista Dinámica -
Diagrama de
*
Secuencia


#### Tabla 1 — Página 21

|  |
| --- |
|  |


#### Tabla 2 — Página 21

| Realización
CU Regist
Festival:
Vista Dinám
Diagrama
Secuenci | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
de
rar
ica -
de
*
a |
| --- | --- |


#### Página 22

Realización de CU Registrar Festival: Flujo Normal
CÁTEDRA DE DISEÑO DE SISTEMAS
Vista Estática con Diagrama de Clases DE INFORMACIÓN
Vista Dinámica con Diagrama de Secuencia
*
Laura Covaro


#### Tabla 1 — Página 22

|  |
| --- |
|  |


#### Tabla 2 — Página 22

|  |
| --- |
|  |


#### Página 23

Realización de CU Registrar Festival: Flujo Normal
CÁTEDRA DE DISEÑO DE SISTEMAS
Vista Estática con Diagrama de Clases DE INFORMACIÓN
Vista Dinámica con Diagrama de Secuencia (con
fragmentos)
*
Laura Covaro


#### Tabla 1 — Página 23

|  |
| --- |
|  |


#### Tabla 2 — Página 23

|  |
| --- |
|  |


#### Página 24

CÁTEDRA DE DISEÑO DE SISTEMAS
Visibilidad
DE INFORMACIÓN
Para que un objeto le
Trabajaremos con 2
envíe un mensaje a
tipos de visibilidad
otro, debe verlo.
Visibilidad de Visibilidad de
atributos. parámetros
En la estructura se
En la estructura se
modela con asociación,
modela con
agregación,
dependencia
composición


#### Página 25

Vista de la
CÁTEDRA DE DISEÑO DE SISTEMAS
Estructura DE INFORMACIÓN
Vista de
Comportamiento
(Dinámica)
Judith Meles - Laura Covaro


#### Página 26

Vista dinámica con Diagrama de
Comunicación
Vista dinámica con Diagrama de CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Secuencia


#### Página 27

¿Cómo se modela otro escenario?
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realización de Caso de uso de
Análisis
Registrar Festival
Flujo: Existe festival registrado
con los mismos datos


#### Página 28

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realización de Caso de
uso de Análisis
Registrar Festival
Flujo: Existe festival
registrado con los
mismos datos


#### Página 29

Realización de Caso de uso de Análisis
CÁTEDRA DE DISEÑO DE SISTEMAS
Registrar Festival
DE INFORMACIÓN
Flujo: Existe festival registrado con los mismos datos


#### Página 30

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Modelo de
Dominio
Realizaciones
de Casos de
Uso
Escenarios
de Casos de
Uso
Judith Meles - Laura Covaro


#### Página 31

Repasando lo que vimos…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Diagramas de UML 2.0
Workflow de Análisis
PUD como contexto
Elementos del Diagrama de
Realizaciones de CU
Modelo de Análisis
Secuencia
4/22/2023 Judith Meles 32


#### Página 32

Sobre el Diagrama de Secuencia vimos estos
CÁTEDRA DE DISEÑO DE SISTEMAS
elementos para modelar…
DE INFORMACIÓN
Línea de vida
Objetos Foco de
control
Fragmentos
de interacción
Judith Meles - Laura Covaro


#### Página 33

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Finalmente…
Muchas
Gracias!!!


### 🖼️ Imágenes Extraídas (90 imágenes)

#### Imagen 1 — Página 1 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 2 — Página 1 (24.4 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 3 — Página 1 (16.2 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 4 — Página 2 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 5 — Página 3 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 6 — Página 3 (141.5 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 7 — Página 4 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 8 — Página 4 (76.2 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 9 — Página 4 (113.8 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 10 — Página 5 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 11 — Página 6 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 12 — Página 7 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 7**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `7`
> *(Para ver: abrir PDF en página 7)*


#### Imagen 13 — Página 8 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 8**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `8`
> *(Para ver: abrir PDF en página 8)*


#### Imagen 14 — Página 8 (16.2 KB)

> 📄 **Diagrama/Imagen — Página 8**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `8`
> *(Para ver: abrir PDF en página 8)*


#### Imagen 15 — Página 9 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 16 — Página 9 (24.4 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 17 — Página 9 (10.6 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 18 — Página 10 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 10**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `10`
> *(Para ver: abrir PDF en página 10)*


#### Imagen 19 — Página 10 (42.5 KB)

> 📄 **Diagrama/Imagen — Página 10**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `10`
> *(Para ver: abrir PDF en página 10)*


#### Imagen 20 — Página 11 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 11**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `11`
> *(Para ver: abrir PDF en página 11)*


#### Imagen 21 — Página 11 (412.5 KB)

> 📄 **Diagrama/Imagen — Página 11**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `11`
> *(Para ver: abrir PDF en página 11)*


#### Imagen 22 — Página 12 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 12**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `12`
> *(Para ver: abrir PDF en página 12)*


#### Imagen 23 — Página 12 (137.7 KB)

> 📄 **Diagrama/Imagen — Página 12**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `12`
> *(Para ver: abrir PDF en página 12)*


#### Imagen 24 — Página 13 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 13**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `13`
> *(Para ver: abrir PDF en página 13)*


#### Imagen 25 — Página 13 (188.8 KB)

> 📄 **Diagrama/Imagen — Página 13**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `13`
> *(Para ver: abrir PDF en página 13)*


#### Imagen 26 — Página 14 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 27 — Página 14 (188.8 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 28 — Página 14 (137.7 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 29 — Página 15 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 30 — Página 15 (5.4 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 31 — Página 15 (48.8 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 32 — Página 16 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 33 — Página 16 (6.0 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 34 — Página 16 (98.7 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 35 — Página 17 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 36 — Página 17 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 37 — Página 17 (65.5 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 38 — Página 18 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 18**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `18`
> *(Para ver: abrir PDF en página 18)*


#### Imagen 39 — Página 18 (14.2 KB)

> 📄 **Diagrama/Imagen — Página 18**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `18`
> *(Para ver: abrir PDF en página 18)*


#### Imagen 40 — Página 18 (127.5 KB)

> 📄 **Diagrama/Imagen — Página 18**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `18`
> *(Para ver: abrir PDF en página 18)*


#### Imagen 41 — Página 19 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 19**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `19`
> *(Para ver: abrir PDF en página 19)*


#### Imagen 42 — Página 19 (44.3 KB)

> 📄 **Diagrama/Imagen — Página 19**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `19`
> *(Para ver: abrir PDF en página 19)*


#### Imagen 43 — Página 20 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 44 — Página 20 (9.1 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 45 — Página 20 (261.3 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 46 — Página 21 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 21**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `21`
> *(Para ver: abrir PDF en página 21)*


#### Imagen 47 — Página 21 (5.0 KB)

> 📄 **Diagrama/Imagen — Página 21**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `21`
> *(Para ver: abrir PDF en página 21)*


#### Imagen 48 — Página 21 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 21**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `21`
> *(Para ver: abrir PDF en página 21)*


#### Imagen 49 — Página 22 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*


#### Imagen 50 — Página 22 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*


#### Imagen 51 — Página 22 (716.1 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*


#### Imagen 52 — Página 23 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 53 — Página 23 (211.0 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 54 — Página 23 (716.1 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 55 — Página 24 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 24**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `24`
> *(Para ver: abrir PDF en página 24)*


#### Imagen 56 — Página 24 (9.0 KB)

> 📄 **Diagrama/Imagen — Página 24**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `24`
> *(Para ver: abrir PDF en página 24)*


#### Imagen 57 — Página 25 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 58 — Página 25 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 59 — Página 25 (716.1 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 60 — Página 25 (6.2 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 61 — Página 26 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 26**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `26`
> *(Para ver: abrir PDF en página 26)*


#### Imagen 62 — Página 26 (105.9 KB)

> 📄 **Diagrama/Imagen — Página 26**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `26`
> *(Para ver: abrir PDF en página 26)*


#### Imagen 63 — Página 26 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 26**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `26`
> *(Para ver: abrir PDF en página 26)*


#### Imagen 64 — Página 27 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 27**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `27`
> *(Para ver: abrir PDF en página 27)*


#### Imagen 65 — Página 27 (263.2 KB)

> 📄 **Diagrama/Imagen — Página 27**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `27`
> *(Para ver: abrir PDF en página 27)*


#### Imagen 66 — Página 28 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 67 — Página 28 (153.9 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 68 — Página 29 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 29**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `29`
> *(Para ver: abrir PDF en página 29)*


#### Imagen 69 — Página 29 (153.9 KB)

> 📄 **Diagrama/Imagen — Página 29**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `29`
> *(Para ver: abrir PDF en página 29)*


#### Imagen 70 — Página 29 (716.1 KB)

> 📄 **Diagrama/Imagen — Página 29**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `29`
> *(Para ver: abrir PDF en página 29)*


#### Imagen 71 — Página 30 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 30**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `30`
> *(Para ver: abrir PDF en página 30)*


#### Imagen 72 — Página 30 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 30**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `30`
> *(Para ver: abrir PDF en página 30)*


#### Imagen 73 — Página 30 (153.9 KB)

> 📄 **Diagrama/Imagen — Página 30**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `30`
> *(Para ver: abrir PDF en página 30)*


#### Imagen 74 — Página 30 (47.3 KB)

> 📄 **Diagrama/Imagen — Página 30**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `30`
> *(Para ver: abrir PDF en página 30)*


#### Imagen 75 — Página 30 (8.9 KB)

> 📄 **Diagrama/Imagen — Página 30**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `30`
> *(Para ver: abrir PDF en página 30)*


#### Imagen 76 — Página 30 (716.1 KB)

> 📄 **Diagrama/Imagen — Página 30**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `30`
> *(Para ver: abrir PDF en página 30)*


#### Imagen 77 — Página 31 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 31**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `31`
> *(Para ver: abrir PDF en página 31)*


#### Imagen 78 — Página 31 (210.0 KB)

> 📄 **Diagrama/Imagen — Página 31**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `31`
> *(Para ver: abrir PDF en página 31)*


#### Imagen 79 — Página 31 (154.0 KB)

> 📄 **Diagrama/Imagen — Página 31**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `31`
> *(Para ver: abrir PDF en página 31)*


#### Imagen 80 — Página 31 (173.3 KB)

> 📄 **Diagrama/Imagen — Página 31**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `31`
> *(Para ver: abrir PDF en página 31)*


#### Imagen 81 — Página 31 (108.1 KB)

> 📄 **Diagrama/Imagen — Página 31**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `31`
> *(Para ver: abrir PDF en página 31)*


#### Imagen 82 — Página 31 (83.3 KB)

> 📄 **Diagrama/Imagen — Página 31**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `31`
> *(Para ver: abrir PDF en página 31)*


#### Imagen 83 — Página 31 (61.9 KB)

> 📄 **Diagrama/Imagen — Página 31**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `31`
> *(Para ver: abrir PDF en página 31)*


#### Imagen 84 — Página 32 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 32**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `32`
> *(Para ver: abrir PDF en página 32)*


#### Imagen 85 — Página 32 (16.2 KB)

> 📄 **Diagrama/Imagen — Página 32**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `32`
> *(Para ver: abrir PDF en página 32)*


#### Imagen 86 — Página 32 (11.1 KB)

> 📄 **Diagrama/Imagen — Página 32**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `32`
> *(Para ver: abrir PDF en página 32)*


#### Imagen 87 — Página 32 (11.9 KB)

> 📄 **Diagrama/Imagen — Página 32**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `32`
> *(Para ver: abrir PDF en página 32)*


#### Imagen 88 — Página 32 (21.9 KB)

> 📄 **Diagrama/Imagen — Página 32**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `32`
> *(Para ver: abrir PDF en página 32)*


#### Imagen 89 — Página 33 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 90 — Página 33 (14.7 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`03 Realizaciones de CU - Diagrama de Secuencia.pdf`](../Diapositivas y Teóricos/03 Realizaciones de CU - Diagrama de Secuencia.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*



---


## 04 GRASP con secuencia

**Categoría:** Diapositivas y Teóricos  

**Archivo:** `04 GRASP con secuencia.pdf`  

**Tamaño:** 2.75 MB  


### 📄 Contenido de Texto

#### Página 1

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Asignación de
Responsabilidades
a los objetos
PATRONES GRASP
Para Análisis
(Craig Larman)
Judith Meles


#### Página 2

Patrones GRASP: Responsabilidades
relacionadas con: Hacer - Conocer
Hacer algo en
Estar enterado de
uno mismo. los datos privados
encapsulados.
Iniciar una
Estar enterado
acción en
de la existencia
otros objetos. de objetos
conexos.
Controlar y
coordinar Estar enterado
actividades en de cosas que se
pueden derivar
otros objetos.
o calcular.
Judith Meles


#### Tabla 1 — Página 2

| Patrones GRASP: Responsabilidades
relacionadas con: Hacer - Conocer
Hacer algo en
Estar enterado de
uno mismo. los datos privados
encapsulados.
Iniciar una
Estar enterado
acción en
de la existencia
otros objetos. de objetos
conexos.
Controlar y
coordinar Estar enterado
actividades en de cosas que se
pueden derivar
otros objetos.
o calcular.
Judith Meles |  |  |  |  |
| --- | --- | --- | --- | --- |
|  | Hacer algo en
uno mismo.
Iniciar una
acción en
otros objetos.
Controlar y
coordinar
actividades en
otros objetos.
Judith Meles |  |  |  |
|  |  |  | Estar enterado de
los datos privados
encapsulados.
Estar enterado
de la existencia
de objetos
conexos.
Estar enterado
de cosas que se
pueden derivar
o calcular. |  |
|  |  |  |  |  |


#### Página 3

Patrones Grasp para
Análisis
Experto en
Creador
Información
Bajo
Alta Cohesión
Acoplamiento
Controlador
Judith Meles


#### Tabla 1 — Página 3

| Patrones Grasp para
Análisis
Experto en
Creador
Información
Bajo
Alta Cohesión
Acoplamiento
Controlador
Judith Meles |  |
| --- | --- |


#### Tabla 2 — Página 3

|  |  |
| --- | --- |


#### Página 4

Clases del Análisis
Clase de Entidad: modela información que podría ser persistente y que
puede sobrevivir a una ejecución de un sistema.
Clase límite o frontera (Boundary) modela el comportamiento e
información que es dependiente de la frontera del sistema con el
ambiente. Modela todo lo que concierne a cualquier vínculo sistema-actor
Clases de
Fabricación
Pura
Clase de control modela funcionalidad que operar sobre varios objetos
diferentes de entidad, haciendo algunos cálculos y retornando el resultado
al objeto de boundary.
Contiene comportamiento de la lógica de negocio definida en un caso de
uso.
Tiene responsabilidades de coordinación de la ejecución de un caso de uso
y funciona como intermediario entre las clases de interfaz y las de entidad.
Judith Meles


#### Página 5

Sin aplicar el
patrón
Controlador
Judith Meles


#### Tabla 1 — Página 5

| Sin ap
pat
Contr | licar el
rón
olador
Judith Meles |
| --- | --- |


#### Página 6

Aplicando el
Patrón
Controlador
Judith Meles


#### Tabla 1 — Página 6

| Aplica
Pat
Contr | ndo el
rón
olador
Judith Meles |
| --- | --- |


#### Página 7

Caso de
Estudio: Festival
de Folklore –
CU Registrar
Festival
Judith Meles


#### Tabla 1 — Página 7

|  |
| --- |
|  |


#### Página 8

Estructuramos la realización del caso de uso con un Controlador de caso
Patrón Controlador


#### Tabla 1 — Página 8

|  |
| --- |
|  |
| Estructuramos la realización del caso de uso con un Controlador de caso |
| Patrón Controlador |


#### Tabla 2 — Página 8

| Controlador |  | de | caso |
| --- | --- | --- | --- |


#### Página 9

Necesitamos validar si existe unFestival con esos datos, ya registrado en el sistema…
El Experto nos dice que: Patrón Experto
“Lo hace quién conoce”


#### Tabla 1 — Página 9

|  |
| --- |
| Necesitamos validar si existe unFestival con esos datos, ya registrado en el sistema… |
| El Experto nos dice que: Patrón Experto
“Lo hace quién conoce” |


#### Página 10

¿Qué clase tiene la Información para validar si hay un festival registrado
con esos datos?
Acá aplicamos el
patrón Experto
Acá NO aplicamos
el patrón Experto


#### Página 11

Ahora necesitamos crear
una nueva instancia de
Festival, ¿quién tiene la
responsabilidad de
hacerlo?
Patrón Creador


#### Página 12

Patrón
Creador
Asignar a la clase B la
responsabilidad de crear una
instancia de la clase A en uno
de los siguientes casos:
* B agrega los objetos de A.
* B contiene los objetos de A.
* B tiene los datos de
inicialización que serán
transmitidos a A cuando sea
creado (así B es un experto
respecto de la creación de A).


#### Página 13

Ahora bien, cómo se vería si aplicáramos en los dos casos el patrón Creador con la opción:
* B tiene los datos de inicialización que serán transmitidos a A cuando sea creado (así B es un experto respecto de la
creación de A).
Alto Acoplamiento


#### Página 14

Pasando en limpio…
Esta solución aplica
los patrones:
 Creador
 Bajo
Acoplamiento


#### Tabla 1 — Página 14

|  |  |  |  |
| --- | --- | --- | --- |
|  |  | Pasando en limpio…
Esta solución aplica
los patrones:
 Creador
 Bajo
Acoplamiento |  |


#### Página 15

Baja Cohesión
Mientras tanto…
¿Cómo se ve la clase GestorFestival con esta solución?


#### Página 16

Entonces la solución elegida aplica los patrones:
 Controlador
 Experto
 Creador
 Bajo Acoplamiento
 Alta Cohesión


#### Tabla 1 — Página 16

|  |  |  |
| --- | --- | --- |
| Entonces la solución elegida aplic
 Controlador
 Experto
 Creador
 Bajo Acoplamiento
 Alta Cohesión | a los patrones: |  |
|  |  |  |


#### Página 17

Patrón Controlador
Problema
¿Quién debería encargarse de atender un evento del sistema?
Un evento del sistema es un evento de alto nivel generado por el
actor externo.
Solución
Asignar la responsabilidad del manejo de un mensaje de los eventos
de un sistema, a una clase controladora de esos eventos
Explicación
Un controlador de caso de uso es una buena alternativa cuando hay
muchos eventos del sistema entre varios procesos: asigna su manejo a
clases individuales controlables
Beneficios
Garantiza que los procesos del dominio sean manejados por la capa del
dominio y no por la de interfaz. Reflexionar sobre el estado de un caso de uso:
asegurar que las operaciones ocurran en una cierta secuencia o saber el estado
actual de las operaciones del caso de uso.


#### Tabla 1 — Página 17

| Problema
¿Quién debería encargarse de atender un evento del sistema?
Un evento del sistema es un evento de alto nivel generado por el
actor externo.
Solución
Asignar la responsabilidad del manejo de un mensaje de los eventos
de un sistema, a una clase controladora de esos eventos
Explicación
Un controlador de caso de uso es una buena alternativa cuando hay
muchos eventos del sistema entre varios procesos: asigna su manejo a
clases individuales controlables
Beneficios
Garantiza que los procesos del dominio sean manejados por la capa del
dominio y no por la de interfaz. Reflexionar sobre el estado de un caso de uso:
asegurar que las operaciones ocurran en una cierta secuencia o saber el estado
actual de las operaciones del caso de uso. |
| --- |
|  |


#### Página 18

Patrón Experto
Problema
¿Cuál es el principio fundamental en virtud del cual se asignan
las responsabilidades en el diseño orientado a objetos?
Solución
Asignar una responsabilidad al experto en información: la clase
que cuenta con la información necesaria para cumplir con la
responsabilidad.
Explicación
Los objetos hacen cosas relacionadas con la información que
poseen.
Puede haber expertos parciales
Beneficios
Bajo el acoplamiento
El comportamiento se distribuye entre las clases que cuentan
con la información requerida
Judith Meles


#### Página 19

Patrón Creador
Problema
¿Quién debería ser el responsable de crear una
nueva instancia de alguna clase?
Solución
Asignar a la clase B la responsabilidad de crear una instancia de la clase A cuando:
B agrega/ contiene los objetos de A; B utiliza específicamente los objetos de A; B
tiene los datos de inicialización que serán transmitidos a Acuando sea creado
Explicación
Encontrar un creador que debemos conectar con el objeto
producido, esto soporta el bajo acoplamiento. El agregado “agrega”
la parte, el contenedor “contiene” el contenido, el registro “registra”.
Beneficios
Ayuda al bajo acoplamiento, supone menos dependencias.
Como la clase creada tiende a ser visible al creador (razón por la
cual se la eligió).


#### Tabla 1 — Página 19

| Problema
¿Quién debería ser el responsable de crear una
nueva instancia de alguna clase?
Solución
Asignar a la clase B la responsabilidad de crear una instancia de la clase A cuando:
B agrega/ contiene los objetos de A; B utiliza específicamente los objetos de A; B
tiene los datos de inicialización que serán transmitidos a Acuando sea creado
Explicación
Encontrar un creador que debemos conectar con el objeto
producido, esto soporta el bajo acoplamiento. El agregado “agrega”
la parte, el contenedor “contiene” el contenido, el registro “registra”.
Beneficios
Ayuda al bajo acoplamiento, supone menos dependencias.
Como la clase creada tiende a ser visible al creador (razón por la
cual se la eligió). |  |
| --- | --- |
|  | Problema
¿Quién debería ser el responsable de crear una
nueva instancia de alguna clase?
Solución
Asignar a la clase B la responsabilidad de crear una instancia de la clase A cuando:
B agrega/ contiene los objetos de A; B utiliza específicamente los objetos de A; B
tiene los datos de inicialización que serán transmitidos a Acuando sea creado
Explicación
Encontrar un creador que debemos conectar con el objeto
producido, esto soporta el bajo acoplamiento. El agregado “agrega”
la parte, el contenedor “contiene” el contenido, el registro “registra”.
Beneficios
Ayuda al bajo acoplamiento, supone menos dependencias.
Como la clase creada tiende a ser visible al creador (razón por la
cual se la eligió). |


#### Página 20

Patrón Bajo Acoplamiento
Problema
¿Cómo dar soporte a una dependencia escasa y a
un aumento de reutilización?
Solución
Asignar una responsabilidad para mantener bajo
el acoplamiento.
Explicación
Clases más independientes, que reducen el impacto de los cambios, y
también más reutilizables. Un grado moderado de acoplamiento es normal
para crear un sistema OO, donde los objetos colaboran entre sí.
Beneficios
No se afectan componentes por cambios de otros componentes.
Fáciles de entender por separado. Fáciles de reutilizar.


#### Página 21

Patrón Alta Cohesión
Problema
Las clases con baja cohesión a menudo representan un grado de
abstracción alto o han asumido responsabilidades que deberían
haber delegado en otros objetos.
Solución
Asignar una responsabilidad de modo que la
cohesión siga siendo alta.
Explicación
Una clase de alta cohesión tiene un número relativamente pequeño de
operaciones con funcionalidad relacionada y poco trabajo por hacer.
Colabora con otros objetos para compartir esfuerzo si la tarea es grande.
Beneficios
Mejoranla claridad y la facilidad de comprensión Simplifican la evolución.
A menudo se genera el bajo acoplamiento. Soporta una mayor capacidad de
reutilización, porque una clase muy cohesiva puede destinarse a un propósito muy
específico


#### Página 22

Realización de Análisis del Caso de Uso Registrar Festival
Vista Dinámica con Diagrama de secuencia Vista de Estructura de Clases de
para el escenario del Curso Normal análisis con Diagrama de Clases


#### Página 23

Repasando lo que vimos…
Realizaciones de
Clases de Análisis
Modelo de Análisis CU de Análisis
Patrones GRASP
para Análisis


#### Tabla 1 — Página 23

| Realizaciones de
Clases de Análisis
Modelo de Análisis CU de Análisis
Patrones GRASP
para Análisis |
| --- |
|  |


#### Página 24

Patrones Grasp para
Análisis
Experto en Información
Creador
Bajo Acoplamiento
Alta Cohesión
Controlador


#### Tabla 1 — Página 24

| Patrones Grasp para
Análisis
Experto en Información
Creador
Bajo Acoplamiento
Alta Cohesión
Controlador |  |
| --- | --- |


#### Tabla 2 — Página 24

|  |  |
| --- | --- |


#### Página 25

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Finalmente…
Muchas
Gracias!!!


### 🖼️ Imágenes Extraídas (44 imágenes)

#### Imagen 1 — Página 1 (8.6 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 2 — Página 1 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 3 — Página 2 (26.5 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 4 — Página 2 (12.3 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 5 — Página 3 (8.7 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 6 — Página 5 (34.8 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 7 — Página 6 (45.8 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 8 — Página 7 (139.3 KB)

> 📄 **Diagrama/Imagen — Página 7**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `7`
> *(Para ver: abrir PDF en página 7)*


#### Imagen 9 — Página 8 (16.9 KB)

> 📄 **Diagrama/Imagen — Página 8**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `8`
> *(Para ver: abrir PDF en página 8)*


#### Imagen 10 — Página 9 (8.1 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 11 — Página 9 (65.5 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 12 — Página 10 (116.4 KB)

> 📄 **Diagrama/Imagen — Página 10**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `10`
> *(Para ver: abrir PDF en página 10)*


#### Imagen 13 — Página 10 (89.0 KB)

> 📄 **Diagrama/Imagen — Página 10**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `10`
> *(Para ver: abrir PDF en página 10)*


#### Imagen 14 — Página 11 (7.0 KB)

> 📄 **Diagrama/Imagen — Página 11**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `11`
> *(Para ver: abrir PDF en página 11)*


#### Imagen 15 — Página 11 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 11**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `11`
> *(Para ver: abrir PDF en página 11)*


#### Imagen 16 — Página 12 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 12**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `12`
> *(Para ver: abrir PDF en página 12)*


#### Imagen 17 — Página 12 (7.0 KB)

> 📄 **Diagrama/Imagen — Página 12**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `12`
> *(Para ver: abrir PDF en página 12)*


#### Imagen 18 — Página 13 (10.3 KB)

> 📄 **Diagrama/Imagen — Página 13**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `13`
> *(Para ver: abrir PDF en página 13)*


#### Imagen 19 — Página 13 (29.5 KB)

> 📄 **Diagrama/Imagen — Página 13**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `13`
> *(Para ver: abrir PDF en página 13)*


#### Imagen 20 — Página 13 (8.1 KB)

> 📄 **Diagrama/Imagen — Página 13**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `13`
> *(Para ver: abrir PDF en página 13)*


#### Imagen 21 — Página 14 (9.0 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 22 — Página 14 (24.0 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 23 — Página 14 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 24 — Página 15 (38.0 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 25 — Página 15 (29.5 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 26 — Página 15 (8.1 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 27 — Página 15 (10.3 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 28 — Página 16 (416.3 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 29 — Página 16 (8.6 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 30 — Página 16 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 31 — Página 17 (261.3 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 32 — Página 18 (261.3 KB)

> 📄 **Diagrama/Imagen — Página 18**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `18`
> *(Para ver: abrir PDF en página 18)*


#### Imagen 33 — Página 19 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 19**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `19`
> *(Para ver: abrir PDF en página 19)*


#### Imagen 34 — Página 20 (24.0 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 35 — Página 21 (102.2 KB)

> 📄 **Diagrama/Imagen — Página 21**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `21`
> *(Para ver: abrir PDF en página 21)*


#### Imagen 36 — Página 22 (559.8 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*


#### Imagen 37 — Página 22 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*


#### Imagen 38 — Página 23 (42.0 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 39 — Página 23 (59.8 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 40 — Página 23 (17.7 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 41 — Página 23 (8.9 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 42 — Página 24 (8.7 KB)

> 📄 **Diagrama/Imagen — Página 24**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `24`
> *(Para ver: abrir PDF en página 24)*


#### Imagen 43 — Página 25 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 44 — Página 25 (15.0 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`04 GRASP con secuencia.pdf`](../Diapositivas y Teóricos/04 GRASP con secuencia.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*



---


## 05 GRASP con com

**Categoría:** Diapositivas y Teóricos  

**Archivo:** `05 GRASP con com.pdf`  

**Tamaño:** 1.99 MB  


### 📄 Contenido de Texto

#### Página 1

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Asignación de
Responsabilidades
a los objetos
PATRONES GRASP
Para Análisis
(Craig Larman)
Judith Meles


#### Página 2

Patrones GRASP: Responsabilidades
relacionadas con: Hacer - Conocer
Hacer algo en
Estar enterado de
uno mismo. los datos privados
encapsulados.
Iniciar una
Estar enterado
acción en
de la existencia
otros objetos. de objetos
conexos.
Controlar y
coordinar Estar enterado
actividades en de cosas que se
pueden derivar
otros objetos.
o calcular.
Judith Meles


#### Página 3

Patrones Grasp para
Análisis
Experto en
Creador
Información
Bajo
Alta Cohesión
Acoplamiento
Controlador
Judith Meles


#### Tabla 1 — Página 3

| Patrones Grasp para
Análisis
Experto en
Creador
Información
Bajo
Alta Cohesión
Acoplamiento
Controlador
Judith Meles |  |
| --- | --- |


#### Tabla 2 — Página 3

|  |  |
| --- | --- |


#### Página 4

Clases del Análisis
Clase de Entidad: modela información que podría ser persistente y que
puede sobrevivir a una ejecución de un sistema.
Clase límite o frontera (Boundary) modela el comportamiento e
información que es dependiente de la frontera del sistema con el
ambiente. Modela todo lo que concierne a cualquier vínculo sistema-actor
Clases de
Fabricación
Pura
Clase de control modela funcionalidad que operar sobre varios objetos
diferentes de entidad, haciendo algunos cálculos y retornando el resultado
al objeto de boundary.
Contiene comportamiento de la lógica de negocio definida en un caso de
uso.
Tiene responsabilidades de coordinación de la ejecución de un caso de uso
y funciona como intermediario entre las clases de interfaz y las de entidad.
Judith Meles


#### Página 5

Sin aplicar el
patrón
Controlador
Judith Meles


#### Tabla 1 — Página 5

| Sin ap
pat
Contr | licar el
rón
olador
Judith Meles |
| --- | --- |


#### Página 6

Aplicando el
Patrón
Controlador
Judith Meles


#### Tabla 1 — Página 6

| Aplica
Pat
Contr | ndo el
rón
olador
Judith Meles |
| --- | --- |


#### Página 7

Caso de
Estudio: Festival
de Folklore –
CU Registrar
Festival
Judith Meles


#### Tabla 1 — Página 7

|  |
| --- |
|  |


#### Página 8

Estructuramos la realización del caso de uso con un Controlador de caso
Patrón Controlador


#### Tabla 1 — Página 8

|  |
| --- |
|  |
| Estructuramos la realización del caso de uso con un Controlador de caso |
| Patrón Controlador |


#### Tabla 2 — Página 8

| Controlador |  | de | caso |
| --- | --- | --- | --- |


#### Página 9

Necesitamos validar si existe unFestival con esos datos, ya registrado en el sistema…
El Experto nos dice que:
Patrón Experto
“Lo hace quién conoce”


#### Tabla 1 — Página 9

|  |
| --- |
| Necesitamos validar si existe unFestival con esos datos, ya registrado en el sistema… |
| El Experto nos dice que:
Patrón Experto
“Lo hace quién conoce” |


#### Página 10

¿Qué clase tiene la Información para validar si hay un festival registrado
con esos datos?
Acá aplicamos
Acá NO
el patrón
aplicamos el
Experto
patrón Experto


#### Página 11

Ahora necesitamos crear
una nueva instancia de
Festival, ¿quién tiene la
responsabilidad de
hacerlo?
Patrón Creador


#### Página 12

Patrón
Creador
Asignar a la clase B la
responsabilidad de crear una
instancia de la clase A en uno
de los siguientes casos:
* B agrega los objetos de A.
* B contiene los objetos de A.
* B tiene los datos de
inicialización que serán
transmitidos a A cuando sea
creado (así B es un experto
respecto de la creación de A).


#### Página 13

Ahora bien, cómo se vería si aplicáramos en los dos casos el patrón Creador con la opción:
* B tiene los datos de inicialización que serán transmitidos a A cuando sea creado (así B es un experto respecto de la
creación de A).
Alto Acoplamiento


#### Página 14

Pasando en limpio…
Esta solución aplica los
patrones:
 Creador
 Bajo Acoplamiento


#### Tabla 1 — Página 14

| Pasando en limpio…
Esta solución aplica los
patrones:
 Creador
 Bajo Acoplamiento |  |
| --- | --- |


#### Tabla 2 — Página 14

|  |  |
| --- | --- |


#### Tabla 3 — Página 14

|  |  |
| --- | --- |


#### Página 15

Baja Cohesión
Mientras tanto…
¿Cómo se ve la clase GestorFestival con esta solución?


#### Página 16

Entonces la solución elegida
aplica los patrones:
 Controlador
 Experto
 Creador
 Bajo Acoplamiento
 Alta Cohesión


#### Página 17

Patrón Controlador
Problema
¿Quién debería encargarse de atender un evento del sistema?
Un evento del sistema es un evento de alto nivel generado por el
actor externo.
Solución
Asignar la responsabilidad del manejo de un mensaje de los eventos
de un sistema, a una clase controladora de esos eventos
Explicación
Un controlador de caso de uso es una buena alternativa cuando hay
muchos eventos del sistema entre varios procesos: asigna su manejo a
clases individuales controlables
Beneficios
Garantiza que los procesos del dominio sean manejados por la capa del
dominio y no por la de interfaz. Reflexionar sobre el estado de un caso de uso:
asegurar que las operaciones ocurran en una cierta secuencia o saber el estado
actual de las operaciones del caso de uso.


#### Página 18

Patrón Experto
Problema
¿Cuál es el principio fundamental en virtud del cual se asignan
las responsabilidades en el diseño orientado a objetos?
Solución
Asignar una responsabilidad al experto en información: la clase
que cuenta con la información necesaria para cumplir con la
responsabilidad.
Explicación
Los objetos hacen cosas relacionadas con la información que
poseen.
Puede haber expertos parciales
Beneficios
Bajo el acoplamiento
El comportamiento se distribuye entre las clases que cuentan
con la información requerida
Judith Meles


#### Página 19

Patrón Creador
Problema
¿Quién debería ser el responsable de crear una
nueva instancia de alguna clase?
Solución
Asignar a la clase B la responsabilidad de crear una instancia de la clase A cuando:
B agrega/ contiene los objetos de A; B utiliza específicamente los objetos de A; B
tiene los datos de inicialización que serán transmitidos a Acuando sea creado
Explicación
Encontrar un creador que debemos conectar con el objeto
producido, esto soporta el bajo acoplamiento. El agregado “agrega”
la parte, el contenedor “contiene” el contenido, el registro “registra”.
Beneficios
Ayuda al bajo acoplamiento, supone menos dependencias.
Como la clase creada tiende a ser visible al creador (razón por la
cual se la eligió).


#### Página 20

Patrón Bajo Acoplamiento
Problema
¿Cómo dar soporte a una dependencia escasa y a
un aumento de reutilización?
Solución
Asignar una responsabilidad para mantener bajo
el acoplamiento.
Explicación
Clases más independientes, que reducen el impacto de los cambios, y
también más reutilizables. Un grado moderado de acoplamiento es normal
para crear un sistema OO, donde los objetos colaboran entre sí.
Beneficios
No se afectan componentes por cambios de otros componentes.
Fáciles de entender por separado. Fáciles de reutilizar.


#### Página 21

Patrón Alta Cohesión
Problema
Las clases con baja cohesión a menudo representan un grado de
abstracción alto o han asumido responsabilidades que deberían
haber delegado en otros objetos.
Solución
Asignar una responsabilidad de modo que la
cohesión siga siendo alta.
Explicación
Una clase de alta cohesión tiene un número relativamente pequeño de
operaciones con funcionalidad relacionada y poco trabajo por hacer.
Colabora con otros objetos para compartir esfuerzo si la tarea es grande.
Beneficios
Mejoranla claridad y la facilidad de comprensión Simplifican la evolución.
A menudo se genera el bajo acoplamiento. Soporta una mayor capacidad de
reutilización, porque una clase muy cohesiva puede destinarse a un propósito muy
específico


#### Página 22

Realización de Análisis del Caso de Uso Registrar Festival
Vista Dinámica con Diagrama de comunicación Vista de Estructura de Clases de análisis
para el escenario del Curso Normal con Diagrama de Clases


#### Página 23

Repasando lo que vimos…
Realizaciones de
Clases de Análisis
Modelo de Análisis CU de Análisis
Patrones GRASP
para Análisis


#### Página 24

Patrones Grasp para
Análisis
Experto en Información
Creador
Bajo Acoplamiento
Alta Cohesión
Controlador


#### Tabla 1 — Página 24

| Patrones Grasp para
Análisis
Experto en Información
Creador
Bajo Acoplamiento
Alta Cohesión
Controlador |  |
| --- | --- |


#### Tabla 2 — Página 24

|  |  |
| --- | --- |


#### Página 25

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Finalmente…
Muchas
Gracias!!!


### 🖼️ Imágenes Extraídas (46 imágenes)

#### Imagen 1 — Página 1 (8.6 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 2 — Página 1 (34.3 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 3 — Página 2 (26.5 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 4 — Página 2 (12.3 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 5 — Página 3 (8.7 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 6 — Página 5 (34.8 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 7 — Página 6 (45.8 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 8 — Página 7 (139.3 KB)

> 📄 **Diagrama/Imagen — Página 7**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `7`
> *(Para ver: abrir PDF en página 7)*


#### Imagen 9 — Página 8 (28.0 KB)

> 📄 **Diagrama/Imagen — Página 8**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `8`
> *(Para ver: abrir PDF en página 8)*


#### Imagen 10 — Página 9 (29.1 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 11 — Página 9 (8.1 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 12 — Página 10 (29.1 KB)

> 📄 **Diagrama/Imagen — Página 10**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `10`
> *(Para ver: abrir PDF en página 10)*


#### Imagen 13 — Página 10 (29.3 KB)

> 📄 **Diagrama/Imagen — Página 10**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `10`
> *(Para ver: abrir PDF en página 10)*


#### Imagen 14 — Página 11 (6.9 KB)

> 📄 **Diagrama/Imagen — Página 11**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `11`
> *(Para ver: abrir PDF en página 11)*


#### Imagen 15 — Página 11 (104.8 KB)

> 📄 **Diagrama/Imagen — Página 11**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `11`
> *(Para ver: abrir PDF en página 11)*


#### Imagen 16 — Página 12 (6.9 KB)

> 📄 **Diagrama/Imagen — Página 12**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `12`
> *(Para ver: abrir PDF en página 12)*


#### Imagen 17 — Página 12 (24.0 KB)

> 📄 **Diagrama/Imagen — Página 12**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `12`
> *(Para ver: abrir PDF en página 12)*


#### Imagen 18 — Página 12 (104.8 KB)

> 📄 **Diagrama/Imagen — Página 12**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `12`
> *(Para ver: abrir PDF en página 12)*


#### Imagen 19 — Página 13 (29.5 KB)

> 📄 **Diagrama/Imagen — Página 13**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `13`
> *(Para ver: abrir PDF en página 13)*


#### Imagen 20 — Página 13 (55.9 KB)

> 📄 **Diagrama/Imagen — Página 13**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `13`
> *(Para ver: abrir PDF en página 13)*


#### Imagen 21 — Página 13 (8.1 KB)

> 📄 **Diagrama/Imagen — Página 13**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `13`
> *(Para ver: abrir PDF en página 13)*


#### Imagen 22 — Página 14 (24.0 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 23 — Página 14 (9.0 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 24 — Página 14 (104.8 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 25 — Página 15 (38.0 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 26 — Página 15 (29.5 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 27 — Página 15 (55.9 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 28 — Página 15 (8.1 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 29 — Página 16 (9.0 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 30 — Página 16 (104.8 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 31 — Página 16 (128.7 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 32 — Página 17 (21.9 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 33 — Página 18 (29.1 KB)

> 📄 **Diagrama/Imagen — Página 18**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `18`
> *(Para ver: abrir PDF en página 18)*


#### Imagen 34 — Página 18 (21.9 KB)

> 📄 **Diagrama/Imagen — Página 18**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `18`
> *(Para ver: abrir PDF en página 18)*


#### Imagen 35 — Página 19 (104.8 KB)

> 📄 **Diagrama/Imagen — Página 19**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `19`
> *(Para ver: abrir PDF en página 19)*


#### Imagen 36 — Página 20 (24.0 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 37 — Página 21 (142.5 KB)

> 📄 **Diagrama/Imagen — Página 21**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `21`
> *(Para ver: abrir PDF en página 21)*


#### Imagen 38 — Página 22 (104.8 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*


#### Imagen 39 — Página 22 (559.8 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*


#### Imagen 40 — Página 23 (70.2 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 41 — Página 23 (59.8 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 42 — Página 23 (17.6 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 43 — Página 23 (8.9 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 44 — Página 24 (8.7 KB)

> 📄 **Diagrama/Imagen — Página 24**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `24`
> *(Para ver: abrir PDF en página 24)*


#### Imagen 45 — Página 25 (34.3 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 46 — Página 25 (15.0 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`05 GRASP con com.pdf`](../Diapositivas y Teóricos/05 GRASP con com.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*



---


## 06 Tips para el Modelado de Realizaciones de Caso - Secuencias

**Categoría:** Diapositivas y Teóricos  

**Archivo:** `06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`  

**Tamaño:** 4.3 MB  


### 📄 Contenido de Texto

#### Página 1

Tips para la construcción de
artefactos del Modelo de Análisis
Judith Meles
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 1

|  |  |
| --- | --- |
|  | Tips para la construcción de
artefactos del Modelo de Análisis
Judith Meles
Cátedra de Diseño de Sistemas de Información
Judith Meles |
|  | Judith Meles |
|  |  |


#### Página 2

Creación de Objetos: Creación de un objeto
• Vemos la estructura para analizarla e
identificar el objeto a crear.
• Objeto de la clase
SolicitudDeRequerimiento
✔ Tiene atributos por valor (propios)
✔ Que el actor ingresa (descripción)
✔ Que asigna el sistema (fechaCreacion/número)
✔ Tiene atributos por referencia
✔ Que el actor elige (ProductoSW/TipoSR)
✔ Que asigna el sistema (Estado)
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 2

|  |  |
| --- | --- |


#### Página 3

Creación de Objetos:
Creación de un objeto
En la dinámica simplificada, el Gestor se
encarga primero de:
1. Obtener los atributos que necesita
✔ Atributos por valor:
✔ Que ingresa el actor
✔ Que obtiene el sistema
(Gestor)
✔ Atributos por referencia:
✔ Que el actor selecciona
(ProductoSW/TipoSR)
✔ Predefinidos en el sistema
(Estado); en el caso de la
creación no hay estado
anterior.
2. Crear el objeto
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 3

|  |  |
| --- | --- |


#### Tabla 2 — Página 3

|  | C |
| --- | --- |


#### Página 4

¿Qué vimos …?
Búsqueda de todos los objetos de una clase para pedir que el actor seleccione uno.
Búsqueda de un objeto con un criterio.
Obtención de fecha actual
Obtención del último número para asignar el siguiente al momento de creación del nuevo objeto
Creación de un objeto luego de tener todos los atributos (propios y por referencia) que
necesitamos para crearlo.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 4

|  |  |
| --- | --- |


#### Página 5

Creación que implica crear objetos de más de una
clase
• Vemos la estructura para analizarla e
identificar los objetos a crear.
• 1 objeto de la clase Festival y al menos 1
objetos de la clase DiaFestival.
• Resto de las referencias tienen
multiplicidad 0..*., no se las tiene en
cuenta en la creación.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 5

|  |  |
| --- | --- |


#### Página 6

Creación que implica
crear objetos de más de
una clase
En la dinámica el Gestor se encarga primero
de:
1. Obtener los atributos que necesitan
para el todo y para las partes.
✔ Atributos por valor: los ingresa el
actor
✔ Validar la existencia previa
2. Crear el objeto “Todo”
3. Delegar al objeto “Todo” la
responsabilidad de creación de los
objetos que agrega/contiene/conoce
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 6

|  | Creación que implica
crear objetos de más de
una clase |
| --- | --- |
| Creación que implica
crear objetos de más de
una clase
En la dinámica el Gestor se encarga primero
de:
1. Obtener los atributos que necesitan
para el todo y para las partes.
✔ Atributos por valor: los ingresa el
actor
✔ Validar la existencia previa
2. Crear el objeto “Todo”
3. Delegar al objeto “Todo” la
responsabilidad de creación de los
objetos que agrega/contiene/conoce | Creación que implica
crear objetos de más de
una clase |


#### Tabla 2 — Página 6

|  |  |
| --- | --- |


#### Tabla 3 — Página 6

|  |  |
| --- | --- |


#### Página 7

¿Qué vimos hasta acá…?
Búsqueda de todos los objetos de una clase para pedir que el actor seleccione uno.
Búsqueda de un objeto con un criterio.
Obtención de fecha actual
Obtención del último número para asignar el siguiente al momento de creación del nuevo objeto
Creación de un objeto luego de tener todos los atributos (propios y por referencia) que necesitamos
para crearlo.
Creación de objetos de más de una clase (cuando hay una estructura tipo Todo-Parte)
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 7

|  |  |
| --- | --- |


#### Página 8

• Vemos la estructura para analizarla e identificar el objeto a crear.
Creación de objetos de
• Objeto de la clase SolicitudDeRequerimiento y Objeto de la clase CambioEstadoSR
más de una clase:
✔ Tiene atributos por valor (propios)
Objeto con su cambio de ✔ Que asigna el sistema (FechaHoraInicio)
✔ Tiene atributos por referencia
estado
✔ Que el actor elige (ProductoSW/TipoSR)
✔ Que asigna el sistema (Estado/Responsable)
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 8

|  |
| --- |
| • Vemos la estructura para analizarla e identificar el objeto a crear.
Creación de objetos de
• Objeto de la clase SolicitudDeRequerimiento y Objeto de la clase CambioEstadoS
más de una clase:
✔ Tiene atributos por valor (propios)
Objeto con su cambio de ✔ Que asigna el sistema (FechaHoraInicio)
✔ Tiene atributos por referencia
estado
✔ Que el actor elige (ProductoSW/TipoSR) |
| ✔ Que asigna el sistema (Estado/Responsable) |


#### Tabla 2 — Página 8

|  |  |
| --- | --- |
|  |  |
|  |  |


#### Página 9

Creación de objetos de más
de una clase:
Objeto con su cambio de
estado
En la dinámica simplificada, el Gestor se encarga
primero de:
1. Obtener los atributos que necesita
✔ Atributos por valor: los ingresa el actor
✔ Atributos que selecciona el actor
2. Gestor obtiene los atributos que necesita
Estado/FechaHoraInicio/ Responsable.
3. Gestor crea la SR y le delega a esta la
responsabilidad de crear su cambio de
estado.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 9

|  |  |
| --- | --- |


#### Página 10

¿Qué vimos …?
Búsqueda de todos los objetos de una clase para pedir que el actor seleccione
Obtención de fecha actual
Obtención del usuario de la sesión
Creación de un objeto luego de tener todos los atributos (propios y por referencia) que necesitamos para
crearlo.
Creación de objetos de más de una clase (cuando hay una estructura tipo Todo-Parte)
Creación de objetos de más de una clase cuando el objeto crea su cambio de estado.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 10

|  |  |
| --- | --- |


#### Página 11

Modificación de objetos:
Modificación de atributos propios de un Objeto
• Vemos la estructura para
analizarla e identificar el objeto a
modificar.
• Objeto de la clase Producto
• Vamos a modificar el precio
del producto cuyo código es
“3d4f6789”
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 11

| Modificación de objetos:
Modificación de atributos propios de un Objeto |  |
| --- | --- |
|  |  |
|  | • Vemos la estructura para
analizarla e identificar el objeto a
modificar.
• Objeto de la clase Producto
• Vamos a modificar el precio
del producto cuyo código es
“3d4f6789” |


#### Tabla 2 — Página 11

|  |  |
| --- | --- |


#### Página 12

Modificación de objetos:
Modificación de atributos propios de
un Objeto
•En la dinámica simplificada primero:
• Se ingresa el código para buscar el
producto
• Gestor busca el producto muestra sus
datos.
• Se ingresa el nuevo precio
• Gestor invoca el método de seteo del
atributo precio, actualizando el valor.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 12

|  |  |
| --- | --- |


#### Tabla 2 — Página 12

|  | M |
| --- | --- |


#### Página 13

Modificación de objetos:
Modificación de atributos propios para todos los objetos de la
clase.
• Vemos la estructura para analizarla
e identificar los objetos a modificar.
• Todos los objetos de la clase
Producto tienen un incremento del
10%.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 13

|  |  |
| --- | --- |


#### Página 14

Modificación de objetos: •En la dinámica simplificada primero:
• Se ingresa el % de aumento
Modificación de atributos
propios para todos los objetos • Gestor con su método incrementarPrecio() invoca el método
calcularIncremento() de todos los objetos producto de la clase.
de la clase.
• Luego cada objeto producto se setea su nuevo precio calculado
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 14

|  |
| --- |
| Modificación de objetos: •En la dinámica simplificada primero:
• Se ingresa el % de aumento
Modificación de atributos
propios para todos los objetos • Gestor con su método incrementarPrecio() invoca el método
calcularIncremento() de todos los objetos producto de la clase.
de la clase. |
| • Luego cada objeto producto se setea su nuevo precio calculado |


#### Tabla 2 — Página 14

|  |  |
| --- | --- |
|  |  |
|  |  |


#### Página 15

Modificación de objetos:
Modificación de atributos propios para todos los objetos que
cumplen un criterio
• Vemos la estructura para analizarla
e identificar los objetos a modificar.
• Objetos de la clase Producto que
tengan la marca “Sancor”, le vamos
a incrementar el precio en un
porcentaje.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 15

|  |  |
| --- | --- |


#### Página 16

Modificación de objetos:
Modificación de atributos
propios para todos los
objetos que cumplen un
criterio
•En la dinámica simplificada primero:
• Se selecciona la marca
• Gestor busca todos los productos de esa
marca, hacienda una validación con
atributos de referencia.
• Se ingresa el % de incremento.
• Gestor invoca el método
calcularIncremento() de los objetos
producto de esa marca
• Luego cada objeto producto se setea su
nuevo precio calculado
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 16

|  |  |
| --- | --- |


#### Tabla 2 — Página 16

|  |  |
| --- | --- |


#### Página 17

Modificación de objetos:
Modificación de un atributo de referencia para todos los objetos
que cumplen un criterio
• Vemos la estructura para analizarla
e identificar los objetos a modificar.
• Objetos de la clase Producto que
tengan la marca “Sancor”, los
vamos a cambiar de sector.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 17

|  |  |
| --- | --- |


#### Página 18

Modificación de objetos:
Modificación de un atributo
de referencia para todos los
objetos que cumplen un
criterio
•En la dinámica simplificada, primero:
• Gestor busca todos los sectores y los
muestra.
• Se selecciona sector destino para los
productos.
• Gestor busca los objetos producto de esa
marca
• Luego asigna el sector elegido a los objetos
de la marca.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 18

|  |  |
| --- | --- |


#### Página 19

¿Qué vimos…?
Modificación de atributos
Modificación de atributos propios para todos los
propios de un objeto objetos que cumplen un
criterio
Modificación de un atributo
Modificación de atributos
de referencia para todos los
propios para todos los
objetos que cumplen un
objetos de la clase.
criterio
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 19

|  |  |
| --- | --- |


#### Página 20

Manejo de Estados: • Por ejemplo: Queremos cancelar un pedido y por
Actualizar el estado consiguiente cancelar sus detalles de pedido.
de un objeto
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 20

|  |
| --- |
| Manejo de Estados: • Por ejemplo: Queremos cancelar un pedido y por
Actualizar el estado consiguiente cancelar sus detalles de pedido.
de un objeto |
|  |


#### Tabla 2 — Página 20

|  |  |
| --- | --- |
|  |  |
|  |  |


#### Página 21

Manejo de Estados:
Actualizar el estado de un
objeto
• En la dinámica simplificada, el GestorPedido
busca el estado que necesita asignar al
pedido y sus detalles; en este caso el estado
“cancelado”.
• Se usa el método modelado en la transición
de correspondiente de la máquina de
estados, en este caso “cancelar()” con la
referencia al objeto cancelado como
parámetro del método.
• Luego el pedido cancela del mismo modo sus
detalles de pedido.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 21

|  |  |
| --- | --- |


#### Tabla 2 — Página 21

|  |  |
| --- | --- |


#### Página 22

• Por ejemplo: Queremos cambiar el
Manejo de Estados: Actualizar
estado de la solicitud elegida de
estado cuando hay estado
EnAnálisis a Suspendida.
actual y anterior
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 22

|  |
| --- |
| • Por ejemplo: Queremos cambiar el
Manejo de Estados: Actualizar
estado de la solicitud elegida de
estado cuando hay estado
EnAnálisis a Suspendida.
actual y anterior |
|  |


#### Tabla 2 — Página 22

|  |  |
| --- | --- |
|  |  |
|  |  |


#### Página 23

Manejo de Estados: Actualizar
estado cuando hay estado
actual y anterior
•En la dinámica simplificada, primero:
• Gestor busca las SR que pueden
ser suspendidas y las muestra.
• Actor selecciona la SR que desea
suspender.
• Gestor busca el estado a asignar,
en este caso “Suspendida”.
• Se suspende la SR, lo que implica
setear el estado anterior con el
estado actual y el estado actual
con “Suspendida”.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 23

|  |  | o de Estados: Actualizar
cuando hay estado
y anterior |
| --- | --- | --- |
| Manejo de Estados: Actualizar
estado cuando hay estado
actual y anterior
•En la dinámica simplificada, primero:
• Gestor busca las SR que pueden
ser suspendidas y las muestra.
• Actor selecciona la SR que desea
suspender.
• Gestor busca el estado a asignar,
en este caso “Suspendida”.
• Se suspende la SR, lo que implica
setear el estado anterior con el
estado actual y el estado actual
con “Suspendida”.
Cátedra de Diseño de Sistemas de Información
Judith Meles | anejo de Estados: Actualizar
stado cuando hay estado
ctual y anterior
ámica simplificada, primero:
or busca las SR que pueden
uspendidas y las muestra.
r selecciona la SR que desea
ender.
or busca el estado a asignar,
te caso “Suspendida”.
spende la SR, lo que implica
r el estado anterior con el
do actual y el estado actual
Suspendida”.
Cátedra de Diseño de Sistemas de Información
Judith Meles | o de Estados: Actualizar
cuando hay estado
y anterior |


#### Tabla 2 — Página 23

| j
o | o |
| --- | --- |


#### Página 24

• Por ejemplo: Queremos cambiar el estado de la solicitud
Manejo de Estados:
elegida de EnAnálisis a Suspendida.
Actualizar estado cuando
se mantienen los • Queremos saber quién hizo el cambio de estado y
cambios de estado cuándo.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 24

|  |
| --- |
| • Por ejemplo: Queremos cambiar el estado de la solicitud
Manejo de Estados:
elegida de EnAnálisis a Suspendida.
Actualizar estado cuando
se mantienen los • Queremos saber quién hizo el cambio de estado y
cambios de estado cuándo. |
|  |


#### Tabla 2 — Página 24

|  |  |
| --- | --- |
|  |  |
|  |  |


#### Página 25

Manejo de Estados: Actualizar
estado cuando se mantienen los
cambios de estado
•En la dinámica simplificada, primero:
• Gestor busca las SR que pueden ser
suspendidas y las muestra.
• Actor selecciona la SR que desea suspender.
• Gestor busca el estado a asignar, en este
caso “Suspendida”.
• Gestor obtiene fecha y hora actual y obtiene
el responsable desde la sesión de usuario
activa, utilizando el atributo de referencia. En
este caso no se requiere pedirle nada al
objeto Responsable.
• Gestor suspende la solicitud.
• La SR busca el estado actual para cerrarlo y
luego crea el nuevo cambio de estado, en
este caso Suspendida
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 25

|  | Manejo de Estados: Actualizar
estado cuando se mantienen los
cambios de estado |
| --- | --- |
| Manejo de Estados: Actualizar
estado cuando se mantienen los
cambios de estado
•En la dinámica simplificada, primero:
• Gestor busca las SR que pueden ser
suspendidas y las muestra.
• Actor selecciona la SR que desea suspender.
• Gestor busca el estado a asignar, en este
caso “Suspendida”.
• Gestor obtiene fecha y hora actual y obtiene
el responsable desde la sesión de usuario
activa, utilizando el atributo de referencia. En
este caso no se requiere pedirle nada al
objeto Responsable.
• Gestor suspende la solicitud.
• La SR busca el estado actual para cerrarlo y
luego crea el nuevo cambio de estado, en
este caso Suspendida | Manejo de Estados: Actualizar
estado cuando se mantienen los
cambios de estado |


#### Tabla 2 — Página 25

|  |  |
| --- | --- |


#### Página 26

¿Cómo se modela
• Queremos modelar varias clases que tienen
cuando tenemos un comportamiento dependiente del estado utilizando una
atributo ámbito en la sola clase Estado
clase Estado? • Una forma es con un atributo ámbito
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 26

|  |
| --- |
| ¿Cómo se modela
• Queremos modelar varias clases que tienen
cuando tenemos un comportamiento dependiente del estado utilizando una
atributo ámbito en la sola clase Estado
clase Estado? • Una forma es con un atributo ámbito |
|  |


#### Tabla 2 — Página 26

|  |  |
| --- | --- |
|  |  |
|  |  |


#### Página 27

Manejo de Estados: Actualizar el estado de un objeto
Manejo de estados: Actualizar estado cuando hay estado actual y
anterior en la estructura.
Manejo de Estados: Actualizar estado cuando se mantienen los
cambios de estado, (historial de estados).
¿Qué vimos…?
Manejo de Estados: Cómo se modela con el atributo ámbito dentro
de la clase estado.
Obtener usuario logueado
Obtener fecha y hora actual del sistema.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 27

|  |  |  |
| --- | --- | --- |
|  |  |  |


#### Página 28

• El Gestor necesita mostrar la información sobre las reservas y
¿Cómo funciona la
pide colaboración, utilizando el patrón experto a quién tiene la
información.
colaboración entre
• ¿Puedo yo responder a esté mensaje solo? Si no, pido
los objetos?
colaboración… así hasta llegar al objeto que puede, porque
tiene la información.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 28

|  |
| --- |
| • El Gestor necesita mostrar la información sobre las reservas y
¿Cómo funciona la
pide colaboración, utilizando el patrón experto a quién tiene la
información.
colaboración entre
• ¿Puedo yo responder a esté mensaje solo? Si no, pido
los objetos?
colaboración… así hasta llegar al objeto que puede, porque |
| tiene la información. |


#### Tabla 2 — Página 28

|  |  |
| --- | --- |
|  |  |
|  |  |


#### Página 29

¿Todas las realizaciones de
• Queremos modelar un caso de uso o
casos de uso tienen un objeto temporal
Boundary?
• No hay actor, no hay objeto boundary
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 29

|  |  |  |
| --- | --- | --- |
| ¿Todas las realizaciones de
• Queremos modelar un caso de uso o
casos de uso tienen un objeto temporal
Boundary?
• No hay actor, no hay objeto boundary
Cátedra de Diseño de Sistemas de Información
Judith Meles | ¿Todas las realizaciones de
• Queremos modelar un caso de uso o
casos de uso tienen un objeto temporal
Boundary?
• No hay actor, no hay objeto boundary |  |
|  |  |  |


#### Tabla 2 — Página 29

|  | ¿T |
| --- | --- |
|  |  |
|  |  |


#### Página 30

Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Página 31

¿Cómo reflejamos
acciones
opcionales?
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 31

|  |
| --- |
| ¿Cómo reflejamos
acciones
opcionales?
Cátedra de Diseño de Sistemas de Información
Judith Meles |
|  |


#### Tabla 2 — Página 31

|  |  |
| --- | --- |
|  |  |


#### Tabla 3 — Página 31

|  |  |
| --- | --- |


#### Página 32

• 9. Sistema: Envía a la opción registrada por defecto
(mail, sms, WhatsApp) de cada Consultor el aviso del
¿Cómo reflejamos acciones
nivel actual asignado. Fin del caso de uso.
alternativas?
(Observación 3 y 4)
Observación 3: Los Consultores
al registrarse eligen una
opción de notificación por
defecto para recibir
información.
Observación 4: En el aviso se
notifica la cantidad de
puntos obtenidos como
resultado del procesamiento
y el nivel actual.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 32

|  |  |
| --- | --- |
|  |  |
|  |  |


#### Página 33

Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Página 34

¿Cómo se modelan las llamadas a otros casos de uso?
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 34

|  |  |  |
| --- | --- | --- |
| ¿Cómo se modelan las llamadas a otros casos de uso?
Cátedra de Diseño de Sistemas de Información
Judith Meles | ¿Cómo se modelan las llamadas a otros casos de uso? |  |


#### Tabla 2 — Página 34

|  |  |
| --- | --- |
|  |  |


#### Página 35

Cómo funciona la colaboración entre objetos
Cómo se modelan los casos de uso abstractos
Cómo se modelan las llamadas a casos de uso de inclusión y/o
¿Qué vimos…?
extensión con el diagrama de comunicación y de secuencia
Cómo se modelan situaciones alternativas y opcionales con
fragmentos en el diagrama de secuencia.
El constructor es un método estático (método de clase)
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 35

|  |  |  |
| --- | --- | --- |
|  |  |  |


#### Página 36

Las acciones sobre los objetos se resumen a:
Modificar valores de atributos Mostrar valores de Eliminar/Anular/
Crear objetos
permitidos atributos Cancelar
• Localizar el o los objetos a
• Tener todos los • Saber que queremos •Localizar el o los objetos a
modificar.
atributos (por valor o mostrar. eliminar/anular/cancelar.
• Tener en cuenta las reglas de
por referencia), • Pedir filtros de •Validar las reglas de
Negocio. Negocio.
necesarios consulta si hace falta.
• Obtener los nuevos valores •Pedir confirmación
• Decidir quién crea • Iterar para buscar
(puede ser calculándolos o •Decidir quién debe hacerlo.
• Mostrar.
recibiéndolos como •Eliminación física/lógica ≠
parámetros). • Decidir quien tiene la Anular/Cancelar
responsabilidad
• Asignarlos a los atributos
correspondientes
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 36

| Las acciones sobre los objetos se resumen a:
Modificar valores de atributos Mostrar valores de Eliminar/Anular/
Crear objetos
permitidos atributos Cancelar |  |  |
| --- | --- | --- |
|  | Eliminar/Anular/
Cancelar |  |
|  |  |  |


#### Tabla 2 — Página 36

|  |  |
| --- | --- |


#### Página 37

Dudas, consultas….
Finalmente…
Muchas Gracias!!!
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 37

|  | Dudas, consultas…. |
| --- | --- |
|  |  |
|  |  |


#### Tabla 2 — Página 37

|  |  |
| --- | --- |
|  |  |


### 🖼️ Imágenes Extraídas (85 imágenes)

#### Imagen 1 — Página 1 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 2 — Página 1 (33.3 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 3 — Página 1 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 4 — Página 1 (22.0 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 5 — Página 2 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 6 — Página 2 (265.6 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 7 — Página 3 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 8 — Página 3 (79.6 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 9 — Página 4 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 10 — Página 5 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 11 — Página 5 (129.1 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 12 — Página 6 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 13 — Página 6 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 14 — Página 7 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 7**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `7`
> *(Para ver: abrir PDF en página 7)*


#### Imagen 15 — Página 8 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 8**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `8`
> *(Para ver: abrir PDF en página 8)*


#### Imagen 16 — Página 8 (289.8 KB)

> 📄 **Diagrama/Imagen — Página 8**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `8`
> *(Para ver: abrir PDF en página 8)*


#### Imagen 17 — Página 9 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 18 — Página 9 (104.3 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 19 — Página 10 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 10**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `10`
> *(Para ver: abrir PDF en página 10)*


#### Imagen 20 — Página 11 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 11**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `11`
> *(Para ver: abrir PDF en página 11)*


#### Imagen 21 — Página 11 (37.9 KB)

> 📄 **Diagrama/Imagen — Página 11**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `11`
> *(Para ver: abrir PDF en página 11)*


#### Imagen 22 — Página 12 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 12**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `12`
> *(Para ver: abrir PDF en página 12)*


#### Imagen 23 — Página 12 (35.9 KB)

> 📄 **Diagrama/Imagen — Página 12**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `12`
> *(Para ver: abrir PDF en página 12)*


#### Imagen 24 — Página 13 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 13**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `13`
> *(Para ver: abrir PDF en página 13)*


#### Imagen 25 — Página 13 (37.9 KB)

> 📄 **Diagrama/Imagen — Página 13**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `13`
> *(Para ver: abrir PDF en página 13)*


#### Imagen 26 — Página 14 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 27 — Página 14 (24.1 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 28 — Página 15 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 29 — Página 15 (37.9 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 30 — Página 16 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 31 — Página 16 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 32 — Página 17 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 33 — Página 17 (37.9 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 34 — Página 18 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 18**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `18`
> *(Para ver: abrir PDF en página 18)*


#### Imagen 35 — Página 18 (23.7 KB)

> 📄 **Diagrama/Imagen — Página 18**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `18`
> *(Para ver: abrir PDF en página 18)*


#### Imagen 36 — Página 19 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 19**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `19`
> *(Para ver: abrir PDF en página 19)*


#### Imagen 37 — Página 20 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 38 — Página 20 (159.0 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 39 — Página 20 (42.9 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 40 — Página 20 (109.8 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 41 — Página 21 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 21**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `21`
> *(Para ver: abrir PDF en página 21)*


#### Imagen 42 — Página 21 (36.3 KB)

> 📄 **Diagrama/Imagen — Página 21**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `21`
> *(Para ver: abrir PDF en página 21)*


#### Imagen 43 — Página 22 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*


#### Imagen 44 — Página 22 (116.2 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*


#### Imagen 45 — Página 22 (107.5 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*


#### Imagen 46 — Página 23 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 47 — Página 23 (62.8 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 48 — Página 24 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 24**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `24`
> *(Para ver: abrir PDF en página 24)*


#### Imagen 49 — Página 24 (116.2 KB)

> 📄 **Diagrama/Imagen — Página 24**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `24`
> *(Para ver: abrir PDF en página 24)*


#### Imagen 50 — Página 24 (295.1 KB)

> 📄 **Diagrama/Imagen — Página 24**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `24`
> *(Para ver: abrir PDF en página 24)*


#### Imagen 51 — Página 25 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 52 — Página 25 (101.0 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 53 — Página 26 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 26**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `26`
> *(Para ver: abrir PDF en página 26)*


#### Imagen 54 — Página 26 (96.6 KB)

> 📄 **Diagrama/Imagen — Página 26**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `26`
> *(Para ver: abrir PDF en página 26)*


#### Imagen 55 — Página 26 (103.7 KB)

> 📄 **Diagrama/Imagen — Página 26**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `26`
> *(Para ver: abrir PDF en página 26)*


#### Imagen 56 — Página 26 (62.1 KB)

> 📄 **Diagrama/Imagen — Página 26**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `26`
> *(Para ver: abrir PDF en página 26)*


#### Imagen 57 — Página 27 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 27**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `27`
> *(Para ver: abrir PDF en página 27)*


#### Imagen 58 — Página 28 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 59 — Página 28 (47.9 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 60 — Página 28 (83.4 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 61 — Página 29 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 29**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `29`
> *(Para ver: abrir PDF en página 29)*


#### Imagen 62 — Página 29 (102.5 KB)

> 📄 **Diagrama/Imagen — Página 29**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `29`
> *(Para ver: abrir PDF en página 29)*


#### Imagen 63 — Página 29 (79.1 KB)

> 📄 **Diagrama/Imagen — Página 29**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `29`
> *(Para ver: abrir PDF en página 29)*


#### Imagen 64 — Página 30 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 30**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `30`
> *(Para ver: abrir PDF en página 30)*


#### Imagen 65 — Página 30 (93.8 KB)

> 📄 **Diagrama/Imagen — Página 30**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `30`
> *(Para ver: abrir PDF en página 30)*


#### Imagen 66 — Página 30 (75.3 KB)

> 📄 **Diagrama/Imagen — Página 30**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `30`
> *(Para ver: abrir PDF en página 30)*


#### Imagen 67 — Página 31 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 31**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `31`
> *(Para ver: abrir PDF en página 31)*


#### Imagen 68 — Página 31 (47.0 KB)

> 📄 **Diagrama/Imagen — Página 31**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `31`
> *(Para ver: abrir PDF en página 31)*


#### Imagen 69 — Página 31 (32.6 KB)

> 📄 **Diagrama/Imagen — Página 31**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `31`
> *(Para ver: abrir PDF en página 31)*


#### Imagen 70 — Página 32 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 32**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `32`
> *(Para ver: abrir PDF en página 32)*


#### Imagen 71 — Página 32 (56.4 KB)

> 📄 **Diagrama/Imagen — Página 32**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `32`
> *(Para ver: abrir PDF en página 32)*


#### Imagen 72 — Página 32 (36.2 KB)

> 📄 **Diagrama/Imagen — Página 32**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `32`
> *(Para ver: abrir PDF en página 32)*


#### Imagen 73 — Página 33 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 74 — Página 33 (252.6 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 75 — Página 33 (56.4 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 76 — Página 33 (245.1 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 77 — Página 34 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 34**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `34`
> *(Para ver: abrir PDF en página 34)*


#### Imagen 78 — Página 34 (18.5 KB)

> 📄 **Diagrama/Imagen — Página 34**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `34`
> *(Para ver: abrir PDF en página 34)*


#### Imagen 79 — Página 34 (81.8 KB)

> 📄 **Diagrama/Imagen — Página 34**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `34`
> *(Para ver: abrir PDF en página 34)*


#### Imagen 80 — Página 35 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 35**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `35`
> *(Para ver: abrir PDF en página 35)*


#### Imagen 81 — Página 36 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 36**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `36`
> *(Para ver: abrir PDF en página 36)*


#### Imagen 82 — Página 36 (5.1 KB)

> 📄 **Diagrama/Imagen — Página 36**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `36`
> *(Para ver: abrir PDF en página 36)*


#### Imagen 83 — Página 36 (6.0 KB)

> 📄 **Diagrama/Imagen — Página 36**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `36`
> *(Para ver: abrir PDF en página 36)*


#### Imagen 84 — Página 37 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 37**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `37`
> *(Para ver: abrir PDF en página 37)*


#### Imagen 85 — Página 37 (8.9 KB)

> 📄 **Diagrama/Imagen — Página 37**
> PDF: [`06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf`](../Diapositivas y Teóricos/06 Tips para el Modelado de Realizaciones de Caso - Secuencias.pdf) · Página `37`
> *(Para ver: abrir PDF en página 37)*



---


## unidad 1 ppt unidas DSI

**Categoría:** Diapositivas y Teóricos  

**Archivo:** `unidad 1 ppt unidas DSI.pdf`  

**Tamaño:** 25.25 MB  


### 📄 Contenido de Texto

#### Página 1

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Modelado de Comportamiento con el
Diagrama de Máquina de Estados
4/1/2026 Judith Meles 1


#### Página 2

¿Qué utilizamos del Modelo de
CÁTEDRA DE DISEÑO DE SISTEMAS
Requerimientos como base para el DE INFORMACIÓN
Modelo de Análisis?
1 o más vistas de Casos de uso
Modelo de Casos de Uso Descripciones de Casos de Uso
Descripciones de Actores
Vista de Clases del Dominio del
Modelo de Requerimientos
Problema
Modelo de Dominio
Glosario
Descripción de Interfaces
de usuario
4/1/2026 Judith Meles 2


#### Tabla 1 — Página 2

| Modelo de Análisis?
1 o más vistas de Casos de uso
Modelo de Casos de Uso Descripciones de Casos de Uso
Descripciones de Actores
Vista de Clases del Dominio del
Modelo de Requerimientos
Problema
Modelo de Dominio
Glosario
Descripción de Interfaces
de usuario
4/1/2026 Judith Meles |
| --- |
|  |


#### Página 3

Workflow de Análisis como proceso…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Salida
Entrada
Workflow
de Análisis
4/1/2026 Judith Meles 3


#### Página 4

¿Cómo construimos el Modelo de Análisis?
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Herramienta: Diagrama
Vista Estática
de Clases
Realizaciones de
Casos de Uso de
Herramienta: Diagrama
Análisis
de Comunicación
Vista Dinámica
Herramienta Diagrama
de Secuencia
Herramienta: Diagrama de Clases
Clases de Análisis
Modelo de
Herramienta: Diagrama de Máquina
Análisis
de Estados
Paquetes de Análisis Herramienta: Diagrama de Paquetes
Descripción de la
Arquitectura
4/1/2026 Judith Meles 4


#### Página 5

¿Cómo construimos el Modelo de Análisis?
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Herramienta: Diagrama
Vista Estática
de Clases
Realizaciones de
Casos de Uso de
Herramienta: Diagrama
Análisis
de Comunicación
Vista Dinámica
Herramienta Diagrama
de Secuencia
Herramienta: Diagrama de Clases
Clases de Análisis
Modelo de
Análisis
Diagrama de Máquina de Estados
Paquetes de Análisis Herramienta: Diagrama de Paquetes
Descripción de la
Arquitectura
4/1/2026 Judith Meles 5


#### Página 6

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
¿QUÉ SABE O
QUE TIENE EL ¿QUÉ ES? ¿Qué lo
OBJETO? distingue de los
demás objetos?
Identidad Clase: Auto Objeto: Mi auto
Estado
Comporta
¿QUÉ PUEDE
miento
HACER EL
OBJETO?
Estructura Objeto
La clase AUTO puede tener Instanciado de la clase Auto, lo que significa que
(atributos): asignamos un lugar: Identidad
y le damos valores a los atributos: Estado
Estado = Atributo + Valor
marca: Chevrolet
marca
modelo: Classic
modelo
color: Blanco
En un momento de tiempo
color dominio: MBO056
dominio añoFabricación: 2012
añoFabricación
Comportamiento o Comportamiento o
DNI
Responsabilidades Responsabilidades
Valores
La Clase Auto puede: Lo que el objeto puede hacer lo toma
Invariables
Legajo de la clase, es decir el objeto puede
Alumno encenderMotor hacer lo que está definido en la Clase
Atributos encenderLuces de la que se creó:
avanzar encenderMotor
Estado Civil
retroceder encenderLuces
Valores
estacionar avanzar
Variables obtenerNivelCombustible retroceder
Situación
estacionar
Académica
obtenerNivelCombustible


#### Tabla 1 — Página 6

| Clase: Auto | Objeto: Mi auto |  |
| --- | --- | --- |
|  |  |  |
|  |  |  |
| Estructura | Objeto |  |
| La clase AUTO puede tener
(atributos):
marca
modelo
color
dominio | Instanciado de la clase Auto, lo que significa que
asignamos un lugar: Identidad
y le damos valores a los atributos: Estado
marca: Chevrolet
modelo: Classic
color: Blanco
dominio: MBO056
añoFabricación: 2012 |  |
| añoFabricación
Comportamiento o |  | Comportamiento o |
| Responsabilidades |  | Responsabilidades |
| La Clase Auto puede:
encenderMotor
encenderLuces
avanzar
retroceder
estacionar
obtenerNivelCombustible |  | Lo que el objeto puede hacer lo toma
de la clase, es decir el objeto puede
hacer lo que está definido en la Clase
de la que se creó:
encenderMotor
encenderLuces
avanzar
retroceder
estacionar
obtenerNivelCombustible |


#### Tabla 2 — Página 6

|  | Estado = Atributo + Valor
En un momento de tiempo |
| --- | --- |
| En un momento de tiem
DNI
Valores
Invariables
Legajo
Alumno
Atributos
Estado Civil
Valores
Variables
Situación
Académica | En un momento de tiem |
|  |  |


#### Página 7

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
¿QUÉ SABE O
QUE TIENE EL ¿QUÉ ES? ¿Qué lo
OBJETO? distingue de los
demás objetos?
Identidad
Estado
Comporta
¿QUÉ PUEDE
miento
HACER EL ✓ Los atributos que son variables y que al
OBJETO?
cambiar su valor hacen que el objeto se
comporte de forma diferente.
Estado = Atributo + Valor
En un momento de tiempo
getDni
DNI
No afectados
Valores
por el estado
Invariables
Legajo
setLegajo
Alumno
Métodos
Atributos
inscribirmeACursar
Estado Civil
Si afectados
Valores
por el estado
Variables
Situación inscribirmeARendir
Académica


#### Tabla 1 — Página 7

|  | Estado = Atributo + Valor
En un momento de tiempo |
| --- | --- |
| En un momento de tiem
DNI
Valores
Invariables
Legajo
Alumno
Atributos
Estado Civil
Valores
Variables
Situación
Académica | En un momento de tiem |
|  |  |


#### Tabla 2 — Página 7

| comporte de forma diferent
getDni
No afectados
por el estado
setLegajo
Métodos
inscribirmeACursar
Si afectados
por el estado
inscribirmeARendir |
| --- |
|  |


#### Página 8

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Caso de Estudio:
Pizzería de Venta
en Mostrador


#### Tabla 1 — Página 8

|  |  |  |  |
| --- | --- | --- | --- |
|  |  | Caso de Estudio:
Pizzería de Venta
en Mostrador | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN |
|  |  |  |  |


#### Página 9

Caso de Estudio: Pizzería
Reglas de Negocio para el Sistema de Pizzería de Venta en Mostrador
de Venta en Mostrador CÁTEDRA DE DISEÑO DE SISTEMAS
Precio de las El precio de las pizzas depende de la variedad, el tipo y el tamaño.
DE INFORMACIÓN
pizzas
Un pedido puede modificarse (agregando o quitando ítems
Modificación del pedido, modificando la cantidad en algún ítem), mientras esté
pendiente de preparación.
de un pedido
Un pedido pueden cancelarse inclusive hasta cuando esté finalizado
Cancelación de preparar, es decir justo antes de que sea entregado al cliente. La
cancelación del pedido implica cancelar todos los ítems del pedido.
de un pedido
En el momento de la entrega se registra la hora de entrega y se
Cierre y cierra el pedido.
Facturación Cuando el pedido está preparado se genera una factura para su
del Pedido. cobro y se entrega la o las pizzas al cliente.
Cobro Cuando el cliente paga se actualizada el estado de la factura a
cobrada.
Anulación de Se debe poder anular la factura en caso de que así se requiera.
Factura
Alcances
:
Objetivo:
• Administrar pizzas con sus precios
Administrar los pedidos de venta de
• Administrar variedades, tamaños, y tipos de pizzas
pizza y el cobro de estos, brindar
• Gestionar pedidos de pizzas
información resultante de la gestión.
• Gestionar la facturación de los pedidos y el cobro
• Generar reportes relacionas con la venta de pizzas.


#### Tabla 1 — Página 9

|  |
| --- |
|  |


#### Tabla 2 — Página 9

|  | CÁTEDRA DE DISEÑO DE SISTEMA
El precio de las pizzas depende de la variedad, el tipo y el tamaño.
DE INFORMACIÓN |
| --- | --- |
|  | Un pedido puede modificarse (agregando o quitando ítems
del pedido, modificando la cantidad en algún ítem), mientras esté
pendiente de preparación. |
|  | Un pedido pueden cancelarse inclusive hasta cuando esté finalizado
de preparar, es decir justo antes de que sea entregado al cliente. La
cancelación del pedido implica cancelar todos los ítems del pedido. |
|  | En el momento de la entrega se registra la hora de entrega y se
cierra el pedido.
Cuando el pedido está preparado se genera una factura para su
cobro y se entrega la o las pizzas al cliente. |
|  | Cuando el cliente paga se actualizada el estado de la factura a
cobrada. |
|  | Se debe poder anular la factura en caso de que así se requiera. |
|  |  |
| Alcances
:
Objetivo:
• Administrar pizzas con sus precios
Administrar los pedidos de venta de
• Administrar variedades, tamaños, y tipos de pizzas
pizza y el cobro de estos, brindar
• Gestionar pedidos de pizzas
información resultante de la gestión.
• Gestionar la facturación de los pedidos y el cobro
• Generar reportes relacionas con la venta de pizzas. |  |


#### Página 10

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Vista esencial
uc Primary Use Cases
de casos de
4 Registrar
Tamaño
uso para el 10 Registrar 7 Generar reporte de
Pedido ingresos por período
Sistema de
Administrador
2 Registrar
Pizza
Pizzería con 1 Generar
Factura
Venta en 6 Generar reporte de
ventas por día de la
3 Registrar
semana
EmpleadoPizzería
Mostrador Variedad de
Pizza
5 Generar reporte de
pizzas más
demandadas


#### Página 11

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Modelo de
Dominio para la
Pizzería de
Venta en
Mostrador


#### Tabla 1 — Página 11

| Mode
Dominio
Pizze
Vent
Most | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
lo de
para la
ría de
a en
rador |
| --- | --- |


#### Página 12

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Qué clases de este modelo
necesitarían un análisis de
comportamiento
dependiente del estado?
• Que tengan un atributo
referenciando a la clase Estado
es un indicador significativo, sin
embargo no es el único,
• Hay clases que tienen atributos
propios que al variar hacen que
la clase modifique su
comportamiento, por ejemplo:
fechaDeDevolucion, de un
objeto préstamo en una
Biblioteca.


#### Tabla 1 — Página 12

| Qué clases de este modelo
necesitarían un análisis de
comportamiento
dependiente del estado?
• Que tengan un atributo
referenciando a la clase Estado
es un indicador significativo, sin
embargo no es el único,
• Hay clases que tienen atributos
propios que al variar hacen que
la clase modifique su
comportamiento, por ejemplo:
fechaDeDevolucion, de un
objeto préstamo en una
Biblioteca. | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN |
| --- | --- |


#### Página 13

Caso de Estudio: Pizzería
Reglas de Negocio para el Sistema de Pizzería de Venta en Mostrador
de Venta en Mostrador CÁTEDRA DE DISEÑO DE SISTEMAS
Precio de las El precio de las pizzas depende de la variedad, el tDiEp oIN FyO eRlM tAaCmIÓaNño.
pizzas
Modificación Un pedido puede modificarse (agregando o quitando ítems
de un pedido del pedido, modificando la cantidad en algún ítem), mientras esté
pendiente de preparación.
Cancelación de Un pedido pueden cancelarse inclusive hasta cuando esté finalizado
un pedido de preparar, es decir justo antes de que sea entregado al cliente. La
cancelación del pedido implica cancelar todos los ítems del pedido.
Cierre y En el momento de la entrega se registra la hora de entrega y se cierra
Facturación del el pedido.
Pedido. Cuando el pedido está preparado se genera una factura para su cobro
y se entrega la o las pizzas al cliente.
Cobro Cuando el cliente paga se actualizada el estado de la factura a
cobrada.
Anulación de Se debe poder anular la factura en caso de que así se requiera.
Factura


#### Tabla 1 — Página 13

| CÁTEDRA DE DISEÑO DE SISTEMAS
El precio de las pizzas depende de la variedad, el tDiEp oIN FyO eRlM tAaCmIÓaNño. |
| --- |
| Un pedido puede modificarse (agregando o quitando ítems
del pedido, modificando la cantidad en algún ítem), mientras esté
pendiente de preparación. |
| Un pedido pueden cancelarse inclusive hasta cuando esté finalizado
de preparar, es decir justo antes de que sea entregado al cliente. La
cancelación del pedido implica cancelar todos los ítems del pedido. |
| En el momento de la entrega se registra la hora de entrega y se cierra
el pedido.
Cuando el pedido está preparado se genera una factura para su cobro
y se entrega la o las pizzas al cliente. |
| Cuando el cliente paga se actualizada el estado de la factura a
cobrada. |
| Se debe poder anular la factura en caso de que así se requiera. |


#### Página 14

Reglas de Negocio para el Sistema de Pizzería de Venta en Mostrador
CÁTEDRA DE DISEÑO DE SISTEMAS
Precio de las El precio de las pizzas depende de la variedad, el tDiEp oIN FyO eRlM tAaCmIÓaNño.
pizzas
Caso de Estudio: Pizzería
de Venta en Mostrador Modificación Un pedido puede modificarse (agregando o quitando ítems
de un pedido del pedido, modificando la cantidad en algún ítem), mientras esté
pendiente de preparación.
Cancelación de Un pedido pueden cancelarse inclusive hasta cuando esté finalizado
un pedido de preparar, es decir justo antes de que sea entregado al cliente. La
cancelación del pedido implica cancelar todos los ítems del pedido.
Cierre y En el momento de la entrega se registra la hora de entrega y se
Facturación del cierra el pedido.
Pedido. Cuando el pedido está preparado se genera una factura para su
cobro y se entrega la o las pizzas al cliente.
Cobro Cuando el cliente paga se actualizada el estado de la factura a
cobrada.
Anulación de Se debe poder anular la factura en caso de que así se requiera.
Factura


#### Tabla 1 — Página 14

|  |
| --- |
| Reglas de Negocio para el Sistema de Pizzería de Venta en Mostrador
CÁTEDRA DE DISEÑO DE SISTEMAS
Precio de las El precio de las pizzas depende de la variedad, el tDiEp oIN FyO eRlM tAaCmIÓaNño.
pizzas
Caso de Estudio: Pizzería
de Venta en Mostrador Modificación Un pedido puede modificarse (agregando o quitando ítems
de un pedido del pedido, modificando la cantidad en algún ítem), mientras esté
pendiente de preparación.
Cancelación de Un pedido pueden cancelarse inclusive hasta cuando esté finalizado
un pedido de preparar, es decir justo antes de que sea entregado al cliente. La
cancelación del pedido implica cancelar todos los ítems del pedido.
Cierre y En el momento de la entrega se registra la hora de entrega y se
Facturación del cierra el pedido.
Pedido. Cuando el pedido está preparado se genera una factura para su
cobro y se entrega la o las pizzas al cliente.
Cobro Cuando el cliente paga se actualizada el estado de la factura a
cobrada.
Anulación de Se debe poder anular la factura en caso de que así se requiera.
Factura |
|  |


#### Tabla 2 — Página 14

|  | CÁTEDRA DE DISEÑO DE SISTEMAS
El precio de las pizzas depende de la variedad, el tDiEp oIN FyO eRlM tAaCmIÓaNño. |
| --- | --- |
| Modificación
de un pedido | Un pedido puede modificarse (agregando o quitando ítems
del pedido, modificando la cantidad en algún ítem), mientras esté
pendiente de preparación. |
| Cancelación de
un pedido | Un pedido pueden cancelarse inclusive hasta cuando esté finalizado
de preparar, es decir justo antes de que sea entregado al cliente. La
cancelación del pedido implica cancelar todos los ítems del pedido. |
| Cierre y
Facturación del
Pedido. | En el momento de la entrega se registra la hora de entrega y se
cierra el pedido.
Cuando el pedido está preparado se genera una factura para su
cobro y se entrega la o las pizzas al cliente. |
| Cobro | Cuando el cliente paga se actualizada el estado de la factura a
cobrada. |
| Anulación de
Factura | Se debe poder anular la factura en caso de que así se requiera. |


#### Página 15

Vamos a construir la máquina de estados para la clase Pedido
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Creación del Pedido
Se registran los pedidos que
los clientes realizan en el
mostrador, informando, el
nombre del cliente (para
llamarlo cuando el pedido
esté listo), la fecha y hora de
creación, la cantidad de pizzas
de cada variedad, tipo y
tamaño. Por ejemplo: 2 pizzas
de molde de 8 porciones de
jamón y morrones y 1 pizza a
la piedra de 4 porciones de
palmitos).


#### Página 16

Vamos a construir la máquina de estados para la clase Pedido
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Tratamiento del Pedido
✓ Un pedido puede modificarse
(agregando o quitando ítems del
pedido, modificando la cantidad en
algún ítem), mientras esté pendiente
de preparación.
✓ Cuando el maestro pizzero va a iniciar
la preparación del pedido debe
informarlo actualizando el estado,
también debe informar que el pedido
está preparado para que se lo pueda
entregar al cliente y facturarlo.


#### Página 17

Vamos a construir la máquina de estados para la clase Pedido
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Tratamiento del Pedido
✓ Un pedido puede modificarse
(agregando o quitando ítems del
pedido, modificando la cantidad
en algún ítem), mientras esté
pendiente de preparación.
✓ Cuando el maestro pizzero va a
iniciar la preparación del pedido
debe informarlo actualizando el
estado, también debe informar
que el pedido está preparado
para que se lo pueda entregar al
cliente y facturarlo.


#### Página 18

Vamos a construir la máquina de estados para la clase Pedido
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Facturación del Pedido
✓ Cuando el pedido está preparado
se genera una factura para su
cobro y se entrega la o las pizzas
al cliente.
✓ En el momento de la entrega se
registra la hora de entrega y se
cierra el pedido.


#### Página 19

Vamos a construir la máquina de estados para la clase Pedido
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Cancelación del Pedido
✓ Un pedido puede cancelarse
inclusive hasta cuando esté
finalizado de preparar, es decir
justo antes de que sea entregado al
cliente. La cancelación del pedido
implica cancelar todos los ítems del
pedido.
Hasta este momento hemos identificado todos los estados por los que pueden pasar los objetos de la clase
Pedido, con las transiciones permitidas entre esos estados y hemos indicado cuáles de estos estados son
iniciales o finales (con los Pseudoestados correspondientes)


#### Página 20

Ahora nos ocupamos de las transiciones
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN


#### Página 21

A las transiciones le definimos métodos y casos de uso
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Máquina de Estados para la Clase Pedido


#### Página 22

¿La modificación del pedido afecta el estado del pedido?
¿Y que hay de la clase DetallePedido? CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Modificación del Pedido
✓ Un pedido puede
modificarse (agregando o
quitando ítems del pedido,
modificando la cantidad en
algún ítem), mientras esté
pendiente de preparación.
A las transiciones le definimos métodos y casos de uso
y cuando es necesario condiciones de control


#### Tabla 1 — Página 22

|  |
| --- |
|  |


#### Página 23

¿La modificación del pedido afecta el estado del pedido?
¿Y qué hay de la clase DetallePedido? CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN


#### Página 24

Vista de
Vista de la
Comportamiento
Estructura
(Dinámica)
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Vista de
Comportamiento
(Estática)


#### Página 25

Vista de
Vista de la
Comportamiento
Estructura
(Dinámica)
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Vista de
Comportamiento
(Estática)


#### Página 26

Ahora bien, si tenemos un requerimiento como este:
CÁTEDRA DE DISEÑO DE SISTEMAS
“Necesito conocer cuánto tiempo está el pedido en cada estado”
DE INFORMACIÓN
¿Con esta estructura de clases podemos satisfacerlo? NO
¿La máquina de estados se ve afectada con este requerimiento?
NO
No es ni tuyo, ni mío
es algo que pasa
entre nosotros


#### Página 27

Con esta estructura de clases SI podemos satisfacerlo
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
La máquina de estados NO se ve afectada con este requerimiento


#### Página 28

Repasando lo que vimos…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Diagramas de UML 2.0
Modelo de
PUD como contexto
Requerimientos
Objetos con
Modelado con Diag.
Workflow de Análisis Modelo de Análisis
comportamiento
De Máquina de
dependiente del estado
Estados
4/1/2026 Judith Meles 28


#### Tabla 1 — Página 28

| CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Diagramas de UML 2.0
Modelo de
PUD como contexto
Requerimientos
Objetos con
Modelado con Diag.
Workflow de Análisis Modelo de Análisis
comportamiento
De Máquina de
dependiente del estado
Estados
4/1/2026 Judith Meles |
| --- |
|  |


#### Página 29

Sobre el Diagrama de Máquina de Estados
CÁTEDRA DE DISEÑO DE SISTEMAS
vimos estos elementos para modelar…
DE INFORMACIÓN
c l a s s C l a s
E
s
s
M
t a
o
d
d
o
e l
c l a
E
s
s
s
t a
C
d
l a
o
s
I
s
n
.
i
.
c
.
i a l
c l a
E
s
s
s
t a
C
d
l a
o
s s
F
.
I
.
n
.
a l
Transición condición de control
evento disparador
o caso de uso
.
.
.
.
.
estado origen
estado destino
4/1/2026 Judith Meles 29


#### Página 30

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Finalmente…
Muchas
Gracias!!!


#### Página 31

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Modelado de Comportamiento con el
Diagrama de Máquina de Estados
3/16/2026 Judith Meles 1


#### Página 32

Workflow de Análisis como proceso…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Salida
Entrada
Workflow
de Análisis
3/16/2026 Judith Meles 2


#### Página 33

¿Cómo construimos el Modelo de Análisis?
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Herramienta: Diagrama
Vista Estática
de Clases
Realizaciones de
Casos de Uso de
Herramienta: Diagrama
Análisis
de Comunicación
Vista Dinámica
Herramienta Diagrama
de Secuencia
Herramienta: Diagrama de Clases
Clases de Análisis
Modelo de
Análisis
Diagrama de Máquina de Estados
Herramienta: Diagrama de
Paquetes de Análisis
Paquetes
Descripción de la
Arquitectura
3/16/2026 Judith Meles 3


#### Página 34

¿Qué es Diagrama de Máquina de Estados?
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Un diagrama de transición de estados muestra una máquina de estados,
la cual especifica la secuencia de estados en los que un objeto puede
estar, los eventos y condiciones que causan que los objetos alcancen
esos estados, y las acciones que ocurren cuando esos estados son
alcanzados.
Son usados para modelar el comportamiento dinámico de un
elemento de modelado, comúnmente clases cuyos objetos varían
el comportamiento en función de su estado.


#### Página 35

Diagrama de Máquina de Estados
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
CLASIFICACIÓN: De comportamiento, dinámico, lógico.
➔
Uso:
➔
Explorar el comportamiento de una clase, actor, subsistema
▪
o componente.
Modelar sistemas de tiempo real.
▪
Contiene comúnmente:
➔
▪ Estados
▪ Transiciones
▪ Eventos


#### Página 36

Sobre el Diagrama de Máquina de Estados
CÁTEDRA DE DISEÑO DE SISTEMAS
vimos estos elementos para modelar…
DE INFORMACIÓN
c l a s s C l a s
E
s
s
M
t a
o
d
d
o
e l
c l a
E
s
s
s
t a
C
d
l a
o
s
I
s
n
.
i
.
c
.
i a l
c l a
E
s
s
s
t a
C
d
l a
o
s s
F
.
I
.
n
.
a l
condición de control
evento disparador
o caso de uso
.
.
.
.
.
estado origen
estado destino
3/16/2026 Judith Meles 6


#### Página 37

Caso de Estudio: Software
para Gestión de
Requerimientos


#### Tabla 1 — Página 37

|  |
| --- |
|  |


#### Tabla 2 — Página 37

|  |  |
| --- | --- |
|  | Caso de Estudio: Software
para Gestión de
Requerimientos |
|  |  |
|  |  |


#### Página 38

Reglas de Negocio para la Solicitud de Requerimientos
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
• Las SR las crea el cliente ingresando los siguientes datos: Cliente (si no está registrado como cliente, primero deberá
registrarse); producto de software asociado (si existe), tipo de SR (selección de uno de los indicados anteriormente) y una
descripción de lo que necesita. Al crearse la solicitud se le asigna un número y se registra la fecha y hora de creación.
• La SR creada por el cliente queda pendiente de análisis por parte de un Analista de Requerimientos de la empresa que será
el responsable de evaluar la pertinencia y factibilidad de lo requerido. De análisis de factibilidad realizado, puede resultar que
la SR sea desestimada, o derivada para que sea preparada una propuesta que responda a lo pedido por el Cliente.
• Luego, un Consultor asignado toma la SR y prepara un Propuesta de Servicios y se la envía al cliente para su consideración
• El Cliente recibe la propuesta de servicio asociada a la SR y pueda aceptarla o rechazarla.
• Si el Cliente acepta la propuesta, la SR queda en estado pendiente de inicio. Dado que la empresa necesita un tiempo para
armar el equipo de desarrollo realizará el trabajo.
• Para realizar el trabajo, se inicia un proyecto de desarrollo, que pasará por diferentes etapas (Requerimientos, Análisis &
Diseño, Implementación, Prueba y Despliegue); el proyecto de desarrollo termina con la aceptación del despliegue por parte
del Cliente.
• Con la aceptación del despliegue por parte del cliente se cierra la SR que dio origen al proyecto de desarrollo de software.
• Independientemente de las razones y los aspectos contractuales, un Cliente puede cancelar la SR en cualquier momento
anterior a la aceptación del despliegue del producto de software.
• También debe contemplarse la situación de interrupción del trabajo en cualquiera de las etapas en las que personal de la
empresa esté dedicando tiempo a una SR, para que el tiempo no sea computado como esfuerzo asociado. Cuando se retoma
el trabajo, la SR vuelve al estado en el que estaba al momento de la interrupción; a partir de ahí seguirá con la evolución
correspondiente a ese estado.
3/16/2026 Judith Meles 8


#### Página 39

Vamos cómo se vé la máquina de estados de la clase
SolicitudDeRequerimientos, con lo que sabemos…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN


#### Página 40

Reglas de Negocio para la Solicitud de Requerimientos
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
• Para realizar el trabajo, se inicia un proyecto de desarrollo, que pasará por
diferentes etapas (Requerimientos, Análisis & Diseño, Implementación,
Prueba y Despliegue); el proyecto de desarrollo termina con la aceptación del
despliegue por parte del Cliente.
• Con la aceptación del despliegue por parte del cliente se cierra la SR que dio
origen al proyecto de desarrollo de software.
• Es necesario poder informar a los clientes del estado de la solicitud de
requerimientos en todo momento y del avance del proyecto de desarrollo
asociado a la SR.
• También es necesario poder informar cuánto tiempo permanece una solicitud
en cada estado y quién es el responsable de cada intervención (cambio de
estado).
3/16/2026 Judith Meles 10


#### Página 41

Veamos cómo se ve la máquina de estados de la clase
SolicitudDeRequerimientos, ahora…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN


#### Página 42

Vamos cómo se ve la máquina de estados de la clase
SolicitudDeRequerimientos, ahora…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN


#### Página 43

¿Qué vemos dentro del estado compuesto
EnDesarrolloProyecto?
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Proyecto de Desarrollo
✓ Para realizar el trabajo, se inicia un proyecto de desarrollo, que pasará por diferentes etapas (Requerimientos,
Análisis & Diseño, Implementación, Prueba y Despliegue); el proyecto de desarrollo termina con la
aceptación del despliegue por parte del Cliente.
✓ Es necesario poder informar a los clientes del estado de la solicitud de requerimientos en todo momento y del
avance del proyecto de desarrollo asociado a la SR.
✓ Esto es una simplificación!!! El desarrollo de software no es lineal, ni secuencial, es un
proceso de refinamientos sucesivos.


#### Página 44

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
✓ También es necesario poder informar quién es el
responsable de cada intervención (cambio de
estado).
✓ Es necesario poder informar a los clientes del estado
de la solicitud de requerimientos en todo momento
y del avance del proyecto de desarrollo asociado a
la SR.


#### Página 45

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN


#### Página 46

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN


#### Página 47

¿Qué pasa si la regla de negocio cambia y dice esto?
“Independientemente de las razones y los aspectos contractuales, un Cliente puede
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
cancelar la SR en cualquier momento anterior al inicio del despliegue del producto de
software. “
La transición a
Cancelada, se quita


#### Tabla 1 — Página 47

|  | ¿Qué pasa si la regla de negocio cambia y dice esto? |
| --- | --- |
| “Independientemente de las razones y los aspectos contractuales, un Cliente puede
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
cancelar la SR en cualquier momento anterior al inicio del despliegue del producto de
software. “ |  |


#### Página 48

El pseudoestado Exit Point se puede modelar de cualquiera
de estas dos formas…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN


#### Página 49

Repasemos los elementos de modelado para
CÁTEDRA DE DISEÑO DE SISTEMAS
el Diagrama de Máquina de Estados que
DE INFORMACIÓN
utilizamos en la cátedra:
3/16/2026 Judith Meles 19
c l a
E
s
s
s
t a
C
d
l a
o
s
I
s
n
.
i
.
c
.
i a l
c l a
E
s
s
s
t a
C
d
l a
o
s
F
s .
I
.
n
.
a l
class ...
Historia
c l
c
a s
l a
s C
s
l
s
a s
E
C
E
s M
s t a
l a
s t
o
d
s
a
d
o
s
d
e
M
o
l
C
o
o
d
m
e l
p u e s t o
Esto vimos en la clase anterior
Pseudoestados
En esta clase vimos:


#### Página 50

Algunas cosas para tener cuenta sobre el modelado con
Diagrama de Máquina de Estados CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
UML 2.0 tiene más elementos de modelado que los que vemos
en esta materia.
El estado compuesto se indica con el símbolo infinito en la
esquina inferior del estado. Para ver la máquina de estado
contenida hacemos doble click en el estado compuesto.
Las máquinas de estado dentro de un estado compuesto
pueden no tener estado final.
Estado inicial, estado final, historia y Exit son PSEUDOESTADOS.
3/16/2026 Judith Meles 20


#### Página 51

Para terminar, recordemos…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
El estado es el valor de los atributos en un momento de
tiempo
No todas las clases necesitan una máquina de estados,
cuáles si?
La máquina de estados representa los estados por los que
todos los objetos de la clase modelada pueden pasar.
Los objetos NO van a pasar por todos los estados
identificados.
La máquina de estado de una clase se construye en función
de uno o más atributos de la clase.
Mantener la integración y la consistencia entre las vistas del
software.


#### Página 52

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Finalmente…
Muchas
Gracias!!!


#### Página 53

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realizaciones de CU – Diagrama de
Secuencia y Diagrama de Clases
4/22/2023 Judith Meles – Laura Covaro 1


#### Página 54

Diagramas en UML 2.0
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
De Clases
Modelan
Modelan Clases De Paquetes
Estructura
De Estructura Compuesta
De Componentes
De Despliegue
Modela
De Objetos
Objetos
Diagramas
De Casos de Uso
Modelan De Actividad
Clases
De Máquina de Estados
De Comunicación
Modelan
Comportamiento
De Secuencia
De Interacción
De Timing
(Modelan Objetos)
De Descripción de Interacción
4/22/2023 Judith Meles 2


#### Página 55

Proceso de Desarrollo y sus Artefactos
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Modelado de
Modelo
Negocios l
de Negocios
Cada
workflow
Modelo
Requerimientos
está
de Requerimientos
asociado
con uno o
más Modelo
Análisis
Los diagramas de UML
modelos. Análisis
construyen las vistas en
cada modelo
Diseño Modelo Modelo de
Modelo
Diseño D De e s s p p l l i i e e g g u u e e
Modelo
Implementación
Impl.
Modelo de
Modelo
Prueba
Prueba
Prueba


#### Tabla 1 — Página 55

|  |
| --- |
| Modelo
l
de Negocios |


#### Tabla 2 — Página 55

|  |
| --- |
| Modelo
de Requerimientos |


#### Tabla 3 — Página 55

|  |
| --- |
| Modelo
Análisis |


#### Tabla 4 — Página 55

|  |
| --- |
| Modelo
Diseño |


#### Tabla 5 — Página 55

|  |
| --- |
| Modelo de
Modelo
Despliegue
Despliegue |


#### Tabla 6 — Página 55

|  |
| --- |
| Modelo
Impl. |


#### Tabla 7 — Página 55

|  |
| --- |
| Modelo de
Modelo
Prueba
Prueba |


#### Página 56

Workflow de Análisis como proceso…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Salida
Entrada
Workflow
de Análisis
4/22/2023 Judith Meles 4


#### Página 57

¿Cómo construimos el Modelo de Análisis?
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Herramienta: Diagrama
Vista Estática
de Clases
Realizaciones de
Casos de Uso de
Herramienta: Diagrama
Análisis
de Comunicación
Vista Dinámica
Herramienta Diagrama
de Secuencia
Herramienta: Diagrama de Clases
Clases de Análisis
Modelo de
Herramienta: Diagrama de
Análisis
Máquina de Estados
Herramienta: Diagrama de
Paquetes de Análisis
Paquetes
Descripción de la
Arquitectura
4/22/2023 Judith Meles 5


#### Página 58

¿Cómo construimos el Modelo de Análisis?
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Herramienta: Diagrama
Vista Estática
de Clases
Realizaciones de
Casos de Uso de
Herramienta: Diagrama
Análisis
de Comunicación
Vista Dinámica
Herramienta Diagrama
de Secuencia
Herramienta: Diagrama de Clases
Clases de Análisis
Modelo de
Herramienta: Diagrama de
Análisis
Máquina de Estados
Paquetes de Herramienta: Diagrama de
Análisis Paquetes
Descripción de la
Arquitectura
4/22/2023 Judith Meles 6


#### Página 59

Clases del Análisis
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Clase de Entidad: modela información que podría ser persistente y que
puede sobrevivir a una ejecución de un sistema.
Clase límite o frontera (Boundary) modela el comportamiento e
información que es dependiente de la frontera del sistema con el
ambiente. Modela todo lo que concierne a cualquier vínculo sistema-actor
Clases de
Fabricación
Pura
Clase de control modela funcionalidad que operar sobre varios objetos
diferentes de entidad, haciendo algunos cálculos y retornando el
resultado al objeto de boundary.
Contiene comportamiento de la lógica de negocio definida en un caso de
uso.
Tiene responsabilidades de coordinación de la ejecución de un caso de uso
y funciona como intermediario entre las clases de Boundary y las de
entidad.
4/22/2023 Judith Meles 7


#### Página 60

Realizaciones de CU: Vista Dinámica –
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Diagrama de Secuencia
Laura Covaro


#### Página 61

Realizaciones de CU: Vista Dinámica –
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Diagrama de Secuencia
Laura Covaro


#### Página 62

Realizaciones de CU: Vista Dinámica –
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Diagrama de Secuencia


#### Página 63

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Modelo de
Dominio del
Festival de
Folklore


#### Página 64

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Caso de Estudio: Festival de
Folklore – CU Registrar
Festival
Laura Covaro


#### Tabla 1 — Página 64

|  |
| --- |
|  |


#### Tabla 2 — Página 64

|  | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Caso de Estudio: Festival de
Folklore – CU Registrar
Festival
Laura Covaro |
| --- | --- |


#### Página 65

CÁTEDRA DE DISEÑO DE SISTEMAS
Prototipo de Interfaz
DE INFORMACIÓN
de Usuario
Prototipos para Registrar Festival


#### Página 66

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Laura Covaro


#### Tabla 1 — Página 66

|  |
| --- |
|  |


#### Tabla 2 — Página 66

|  | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Laura Covaro |
| --- | --- |


#### Página 67

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realización de
CU Registrar
Festival:
Vista Dinámica -
Diagrama de
Secuencia
Laura Covaro


#### Tabla 1 — Página 67

|  |  |  |  |
| --- | --- | --- | --- |
|  |  |  |  |
| Realización
CU Regist
Festival:
Vista Dinám
Diagrama
Secuenci |  |  | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
de
rar
ica -
de
a
Laura Covaro |


#### Página 68

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realización de
CU Registrar
Festival:
Vista Dinámica -
Diagrama de
Secuencia
Laura Covaro


#### Tabla 1 — Página 68

|  |
| --- |
|  |


#### Tabla 2 — Página 68

| Realización
CU Regist
Festival:
Vista Dinám
Diagrama
Secuenci | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
de
rar
ica -
de
a
Laura Covaro |
| --- | --- |


#### Página 69

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realización de
CU Registrar
Festival:
Vista Dinámica -
Diagrama de
Secuencia
Laura Covaro


#### Tabla 1 — Página 69

|  |
| --- |
|  |


#### Tabla 2 — Página 69

| Realización
CU Regist
Festival:
Vista Dinám
Diagrama
Secuenci | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
de
rar
ica -
de
a
Laura Covaro |
| --- | --- |


#### Página 70

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realización de
CU Registrar
Festival:
Vista Dinámica -
Diagrama de
Secuencia
Laura Covaro


#### Tabla 1 — Página 70

|  |
| --- |
|  |


#### Tabla 2 — Página 70

| Realización
CU Regist
Festival:
Vista Dinám
Diagrama
Secuenci | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
de
rar
ica -
de
a
Laura Covaro |
| --- | --- |


#### Página 71

Realizaciones de CU: Vista Dinámica –
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Diagrama de Secuencia
Laura Covaro


#### Página 72

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realización de
CU Registrar
Festival:
Vista Dinámica -
Diagrama de
Secuencia
*
Laura Covaro


#### Tabla 1 — Página 72

|  |
| --- |
|  |


#### Tabla 2 — Página 72

|  |  |
| --- | --- |
| Realización
CU Regist
Festival:
Vista Dinám
Diagrama
Secuenci | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
de
rar
ica -
de
a
*
Laura Covaro |
|  |  |


#### Tabla 3 — Página 72

| Laura Covaro |
| --- |
|  |


#### Página 73

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realización de
CU Registrar
Festival:
Vista Dinámica -
Diagrama de
*
Secuencia


#### Tabla 1 — Página 73

|  |
| --- |
|  |


#### Tabla 2 — Página 73

| Realización
CU Regist
Festival:
Vista Dinám
Diagrama
Secuenci | CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
de
rar
ica -
de
*
a |
| --- | --- |


#### Página 74

Realización de CU Registrar Festival: Flujo Normal
CÁTEDRA DE DISEÑO DE SISTEMAS
Vista Estática con Diagrama de Clases DE INFORMACIÓN
Vista Dinámica con Diagrama de Secuencia
*
Laura Covaro


#### Tabla 1 — Página 74

|  |
| --- |
|  |


#### Tabla 2 — Página 74

|  |
| --- |
|  |


#### Página 75

Realización de CU Registrar Festival: Flujo Normal
CÁTEDRA DE DISEÑO DE SISTEMAS
Vista Estática con Diagrama de Clases DE INFORMACIÓN
Vista Dinámica con Diagrama de Secuencia (con
fragmentos)
*
Laura Covaro


#### Tabla 1 — Página 75

|  |
| --- |
|  |


#### Tabla 2 — Página 75

|  |
| --- |
|  |


#### Página 76

CÁTEDRA DE DISEÑO DE SISTEMAS
Visibilidad
DE INFORMACIÓN
Para que un objeto le
Trabajaremos con 2
envíe un mensaje a
tipos de visibilidad
otro, debe verlo.
Visibilidad de Visibilidad de
atributos. parámetros
En la estructura se
En la estructura se
modela con asociación,
modela con
agregación,
dependencia
composición


#### Página 77

Vista de la
CÁTEDRA DE DISEÑO DE SISTEMAS
Estructura DE INFORMACIÓN
Vista de
Comportamiento
(Dinámica)
Judith Meles - Laura Covaro


#### Página 78

Vista dinámica con Diagrama de
Comunicación
Vista dinámica con Diagrama de CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Secuencia


#### Página 79

¿Cómo se modela otro escenario?
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realización de Caso de uso de
Análisis
Registrar Festival
Flujo: Existe festival registrado
con los mismos datos


#### Página 80

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Realización de Caso de
uso de Análisis
Registrar Festival
Flujo: Existe festival
registrado con los
mismos datos


#### Página 81

Realización de Caso de uso de Análisis
CÁTEDRA DE DISEÑO DE SISTEMAS
Registrar Festival
DE INFORMACIÓN
Flujo: Existe festival registrado con los mismos datos


#### Página 82

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Modelo de
Dominio
Realizaciones
de Casos de
Uso
Escenarios
de Casos de
Uso
Judith Meles - Laura Covaro


#### Página 83

Repasando lo que vimos…
CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Diagramas de UML 2.0
Workflow de Análisis
PUD como contexto
Elementos del Diagrama de
Realizaciones de CU
Modelo de Análisis
Secuencia
4/22/2023 Judith Meles 32


#### Página 84

Sobre el Diagrama de Secuencia vimos estos
CÁTEDRA DE DISEÑO DE SISTEMAS
elementos para modelar…
DE INFORMACIÓN
Línea de vida
Objetos Foco de
control
Fragmentos
de interacción
Judith Meles - Laura Covaro


#### Página 85

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Finalmente…
Muchas
Gracias!!!


#### Página 86

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Asignación de
Responsabilidades
a los objetos
PATRONES GRASP
Para Análisis
(Craig Larman)
Judith Meles


#### Página 87

Patrones GRASP: Responsabilidades
relacionadas con: Hacer - Conocer
Hacer algo en
Estar enterado de
uno mismo. los datos privados
encapsulados.
Iniciar una
Estar enterado
acción en
de la existencia
otros objetos. de objetos
conexos.
Controlar y
coordinar Estar enterado
actividades en de cosas que se
pueden derivar
otros objetos.
o calcular.
Judith Meles


#### Tabla 1 — Página 87

| Patrones GRASP: Responsabilidades
relacionadas con: Hacer - Conocer
Hacer algo en
Estar enterado de
uno mismo. los datos privados
encapsulados.
Iniciar una
Estar enterado
acción en
de la existencia
otros objetos. de objetos
conexos.
Controlar y
coordinar Estar enterado
actividades en de cosas que se
pueden derivar
otros objetos.
o calcular.
Judith Meles |  |  |  |  |
| --- | --- | --- | --- | --- |
|  | Hacer algo en
uno mismo.
Iniciar una
acción en
otros objetos.
Controlar y
coordinar
actividades en
otros objetos.
Judith Meles |  |  |  |
|  |  |  | Estar enterado de
los datos privados
encapsulados.
Estar enterado
de la existencia
de objetos
conexos.
Estar enterado
de cosas que se
pueden derivar
o calcular. |  |
|  |  |  |  |  |


#### Página 88

Patrones Grasp para
Análisis
Experto en
Creador
Información
Bajo
Alta Cohesión
Acoplamiento
Controlador
Judith Meles


#### Tabla 1 — Página 88

| Patrones Grasp para
Análisis
Experto en
Creador
Información
Bajo
Alta Cohesión
Acoplamiento
Controlador
Judith Meles |  |
| --- | --- |


#### Tabla 2 — Página 88

|  |  |
| --- | --- |


#### Página 89

Clases del Análisis
Clase de Entidad: modela información que podría ser persistente y que
puede sobrevivir a una ejecución de un sistema.
Clase límite o frontera (Boundary) modela el comportamiento e
información que es dependiente de la frontera del sistema con el
ambiente. Modela todo lo que concierne a cualquier vínculo sistema-actor
Clases de
Fabricación
Pura
Clase de control modela funcionalidad que operar sobre varios objetos
diferentes de entidad, haciendo algunos cálculos y retornando el resultado
al objeto de boundary.
Contiene comportamiento de la lógica de negocio definida en un caso de
uso.
Tiene responsabilidades de coordinación de la ejecución de un caso de uso
y funciona como intermediario entre las clases de interfaz y las de entidad.
Judith Meles


#### Página 90

Sin aplicar el
patrón
Controlador
Judith Meles


#### Tabla 1 — Página 90

| Sin ap
pat
Contr | licar el
rón
olador
Judith Meles |
| --- | --- |


#### Página 91

Aplicando el
Patrón
Controlador
Judith Meles


#### Tabla 1 — Página 91

| Aplica
Pat
Contr | ndo el
rón
olador
Judith Meles |
| --- | --- |


#### Página 92

Caso de
Estudio: Festival
de Folklore –
CU Registrar
Festival
Judith Meles


#### Tabla 1 — Página 92

|  |
| --- |
|  |


#### Página 93

Estructuramos la realización del caso de uso con un Controlador de caso
Patrón Controlador


#### Tabla 1 — Página 93

|  |
| --- |
|  |
| Estructuramos la realización del caso de uso con un Controlador de caso |
| Patrón Controlador |


#### Tabla 2 — Página 93

| Controlador |  | de | caso |
| --- | --- | --- | --- |


#### Página 94

Necesitamos validar si existe unFestival con esos datos, ya registrado en el sistema…
El Experto nos dice que: Patrón Experto
“Lo hace quién conoce”


#### Tabla 1 — Página 94

|  |
| --- |
| Necesitamos validar si existe unFestival con esos datos, ya registrado en el sistema… |
| El Experto nos dice que: Patrón Experto
“Lo hace quién conoce” |


#### Página 95

¿Qué clase tiene la Información para validar si hay un festival registrado
con esos datos?
Acá aplicamos el
patrón Experto
Acá NO aplicamos
el patrón Experto


#### Página 96

Ahora necesitamos crear
una nueva instancia de
Festival, ¿quién tiene la
responsabilidad de
hacerlo?
Patrón Creador


#### Página 97

Patrón
Creador
Asignar a la clase B la
responsabilidad de crear una
instancia de la clase A en uno
de los siguientes casos:
* B agrega los objetos de A.
* B contiene los objetos de A.
* B tiene los datos de
inicialización que serán
transmitidos a A cuando sea
creado (así B es un experto
respecto de la creación de A).


#### Página 98

Ahora bien, cómo se vería si aplicáramos en los dos casos el patrón Creador con la opción:
* B tiene los datos de inicialización que serán transmitidos a A cuando sea creado (así B es un experto respecto de la
creación de A).
Alto Acoplamiento


#### Página 99

Pasando en limpio…
Esta solución aplica
los patrones:
 Creador
 Bajo
Acoplamiento


#### Tabla 1 — Página 99

|  |  |  |  |
| --- | --- | --- | --- |
|  |  | Pasando en limpio…
Esta solución aplica
los patrones:
 Creador
 Bajo
Acoplamiento |  |


#### Página 100

Baja Cohesión
Mientras tanto…
¿Cómo se ve la clase GestorFestival con esta solución?


#### Página 101

Entonces la solución elegida aplica los patrones:
 Controlador
 Experto
 Creador
 Bajo Acoplamiento
 Alta Cohesión


#### Tabla 1 — Página 101

|  |  |  |
| --- | --- | --- |
| Entonces la solución elegida aplic
 Controlador
 Experto
 Creador
 Bajo Acoplamiento
 Alta Cohesión | a los patrones: |  |
|  |  |  |


#### Página 102

Patrón Controlador
Problema
¿Quién debería encargarse de atender un evento del sistema?
Un evento del sistema es un evento de alto nivel generado por el
actor externo.
Solución
Asignar la responsabilidad del manejo de un mensaje de los eventos
de un sistema, a una clase controladora de esos eventos
Explicación
Un controlador de caso de uso es una buena alternativa cuando hay
muchos eventos del sistema entre varios procesos: asigna su manejo a
clases individuales controlables
Beneficios
Garantiza que los procesos del dominio sean manejados por la capa del
dominio y no por la de interfaz. Reflexionar sobre el estado de un caso de uso:
asegurar que las operaciones ocurran en una cierta secuencia o saber el estado
actual de las operaciones del caso de uso.


#### Tabla 1 — Página 102

| Problema
¿Quién debería encargarse de atender un evento del sistema?
Un evento del sistema es un evento de alto nivel generado por el
actor externo.
Solución
Asignar la responsabilidad del manejo de un mensaje de los eventos
de un sistema, a una clase controladora de esos eventos
Explicación
Un controlador de caso de uso es una buena alternativa cuando hay
muchos eventos del sistema entre varios procesos: asigna su manejo a
clases individuales controlables
Beneficios
Garantiza que los procesos del dominio sean manejados por la capa del
dominio y no por la de interfaz. Reflexionar sobre el estado de un caso de uso:
asegurar que las operaciones ocurran en una cierta secuencia o saber el estado
actual de las operaciones del caso de uso. |
| --- |
|  |


#### Página 103

Patrón Experto
Problema
¿Cuál es el principio fundamental en virtud del cual se asignan
las responsabilidades en el diseño orientado a objetos?
Solución
Asignar una responsabilidad al experto en información: la clase
que cuenta con la información necesaria para cumplir con la
responsabilidad.
Explicación
Los objetos hacen cosas relacionadas con la información que
poseen.
Puede haber expertos parciales
Beneficios
Bajo el acoplamiento
El comportamiento se distribuye entre las clases que cuentan
con la información requerida
Judith Meles


#### Página 104

Patrón Creador
Problema
¿Quién debería ser el responsable de crear una
nueva instancia de alguna clase?
Solución
Asignar a la clase B la responsabilidad de crear una instancia de la clase A cuando:
B agrega/ contiene los objetos de A; B utiliza específicamente los objetos de A; B
tiene los datos de inicialización que serán transmitidos a Acuando sea creado
Explicación
Encontrar un creador que debemos conectar con el objeto
producido, esto soporta el bajo acoplamiento. El agregado “agrega”
la parte, el contenedor “contiene” el contenido, el registro “registra”.
Beneficios
Ayuda al bajo acoplamiento, supone menos dependencias.
Como la clase creada tiende a ser visible al creador (razón por la
cual se la eligió).


#### Tabla 1 — Página 104

| Problema
¿Quién debería ser el responsable de crear una
nueva instancia de alguna clase?
Solución
Asignar a la clase B la responsabilidad de crear una instancia de la clase A cuando:
B agrega/ contiene los objetos de A; B utiliza específicamente los objetos de A; B
tiene los datos de inicialización que serán transmitidos a Acuando sea creado
Explicación
Encontrar un creador que debemos conectar con el objeto
producido, esto soporta el bajo acoplamiento. El agregado “agrega”
la parte, el contenedor “contiene” el contenido, el registro “registra”.
Beneficios
Ayuda al bajo acoplamiento, supone menos dependencias.
Como la clase creada tiende a ser visible al creador (razón por la
cual se la eligió). |  |
| --- | --- |
|  | Problema
¿Quién debería ser el responsable de crear una
nueva instancia de alguna clase?
Solución
Asignar a la clase B la responsabilidad de crear una instancia de la clase A cuando:
B agrega/ contiene los objetos de A; B utiliza específicamente los objetos de A; B
tiene los datos de inicialización que serán transmitidos a Acuando sea creado
Explicación
Encontrar un creador que debemos conectar con el objeto
producido, esto soporta el bajo acoplamiento. El agregado “agrega”
la parte, el contenedor “contiene” el contenido, el registro “registra”.
Beneficios
Ayuda al bajo acoplamiento, supone menos dependencias.
Como la clase creada tiende a ser visible al creador (razón por la
cual se la eligió). |


#### Página 105

Patrón Bajo Acoplamiento
Problema
¿Cómo dar soporte a una dependencia escasa y a
un aumento de reutilización?
Solución
Asignar una responsabilidad para mantener bajo
el acoplamiento.
Explicación
Clases más independientes, que reducen el impacto de los cambios, y
también más reutilizables. Un grado moderado de acoplamiento es normal
para crear un sistema OO, donde los objetos colaboran entre sí.
Beneficios
No se afectan componentes por cambios de otros componentes.
Fáciles de entender por separado. Fáciles de reutilizar.


#### Página 106

Patrón Alta Cohesión
Problema
Las clases con baja cohesión a menudo representan un grado de
abstracción alto o han asumido responsabilidades que deberían
haber delegado en otros objetos.
Solución
Asignar una responsabilidad de modo que la
cohesión siga siendo alta.
Explicación
Una clase de alta cohesión tiene un número relativamente pequeño de
operaciones con funcionalidad relacionada y poco trabajo por hacer.
Colabora con otros objetos para compartir esfuerzo si la tarea es grande.
Beneficios
Mejoranla claridad y la facilidad de comprensión Simplifican la evolución.
A menudo se genera el bajo acoplamiento. Soporta una mayor capacidad de
reutilización, porque una clase muy cohesiva puede destinarse a un propósito muy
específico


#### Página 107

Realización de Análisis del Caso de Uso Registrar Festival
Vista Dinámica con Diagrama de secuencia Vista de Estructura de Clases de
para el escenario del Curso Normal análisis con Diagrama de Clases


#### Página 108

Repasando lo que vimos…
Realizaciones de
Clases de Análisis
Modelo de Análisis CU de Análisis
Patrones GRASP
para Análisis


#### Tabla 1 — Página 108

| Realizaciones de
Clases de Análisis
Modelo de Análisis CU de Análisis
Patrones GRASP
para Análisis |
| --- |
|  |


#### Página 109

Patrones Grasp para
Análisis
Experto en Información
Creador
Bajo Acoplamiento
Alta Cohesión
Controlador


#### Tabla 1 — Página 109

| Patrones Grasp para
Análisis
Experto en Información
Creador
Bajo Acoplamiento
Alta Cohesión
Controlador |  |
| --- | --- |


#### Tabla 2 — Página 109

|  |  |
| --- | --- |


#### Página 110

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Finalmente…
Muchas
Gracias!!!


#### Página 111

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Asignación de
Responsabilidades
a los objetos
PATRONES GRASP
Para Análisis
(Craig Larman)
Judith Meles


#### Página 112

Patrones GRASP: Responsabilidades
relacionadas con: Hacer - Conocer
Hacer algo en
Estar enterado de
uno mismo. los datos privados
encapsulados.
Iniciar una
Estar enterado
acción en
de la existencia
otros objetos. de objetos
conexos.
Controlar y
coordinar Estar enterado
actividades en de cosas que se
pueden derivar
otros objetos.
o calcular.
Judith Meles


#### Página 113

Patrones Grasp para
Análisis
Experto en
Creador
Información
Bajo
Alta Cohesión
Acoplamiento
Controlador
Judith Meles


#### Tabla 1 — Página 113

| Patrones Grasp para
Análisis
Experto en
Creador
Información
Bajo
Alta Cohesión
Acoplamiento
Controlador
Judith Meles |  |
| --- | --- |


#### Tabla 2 — Página 113

|  |  |
| --- | --- |


#### Página 114

Clases del Análisis
Clase de Entidad: modela información que podría ser persistente y que
puede sobrevivir a una ejecución de un sistema.
Clase límite o frontera (Boundary) modela el comportamiento e
información que es dependiente de la frontera del sistema con el
ambiente. Modela todo lo que concierne a cualquier vínculo sistema-actor
Clases de
Fabricación
Pura
Clase de control modela funcionalidad que operar sobre varios objetos
diferentes de entidad, haciendo algunos cálculos y retornando el resultado
al objeto de boundary.
Contiene comportamiento de la lógica de negocio definida en un caso de
uso.
Tiene responsabilidades de coordinación de la ejecución de un caso de uso
y funciona como intermediario entre las clases de interfaz y las de entidad.
Judith Meles


#### Página 115

Sin aplicar el
patrón
Controlador
Judith Meles


#### Tabla 1 — Página 115

| Sin ap
pat
Contr | licar el
rón
olador
Judith Meles |
| --- | --- |


#### Página 116

Aplicando el
Patrón
Controlador
Judith Meles


#### Tabla 1 — Página 116

| Aplica
Pat
Contr | ndo el
rón
olador
Judith Meles |
| --- | --- |


#### Página 117

Caso de
Estudio: Festival
de Folklore –
CU Registrar
Festival
Judith Meles


#### Tabla 1 — Página 117

|  |
| --- |
|  |


#### Página 118

Estructuramos la realización del caso de uso con un Controlador de caso
Patrón Controlador


#### Tabla 1 — Página 118

|  |
| --- |
|  |
| Estructuramos la realización del caso de uso con un Controlador de caso |
| Patrón Controlador |


#### Tabla 2 — Página 118

| Controlador |  | de | caso |
| --- | --- | --- | --- |


#### Página 119

Necesitamos validar si existe unFestival con esos datos, ya registrado en el sistema…
El Experto nos dice que:
Patrón Experto
“Lo hace quién conoce”


#### Tabla 1 — Página 119

|  |
| --- |
| Necesitamos validar si existe unFestival con esos datos, ya registrado en el sistema… |
| El Experto nos dice que:
Patrón Experto
“Lo hace quién conoce” |


#### Página 120

¿Qué clase tiene la Información para validar si hay un festival registrado
con esos datos?
Acá aplicamos
Acá NO
el patrón
aplicamos el
Experto
patrón Experto


#### Página 121

Ahora necesitamos crear
una nueva instancia de
Festival, ¿quién tiene la
responsabilidad de
hacerlo?
Patrón Creador


#### Página 122

Patrón
Creador
Asignar a la clase B la
responsabilidad de crear una
instancia de la clase A en uno
de los siguientes casos:
* B agrega los objetos de A.
* B contiene los objetos de A.
* B tiene los datos de
inicialización que serán
transmitidos a A cuando sea
creado (así B es un experto
respecto de la creación de A).


#### Página 123

Ahora bien, cómo se vería si aplicáramos en los dos casos el patrón Creador con la opción:
* B tiene los datos de inicialización que serán transmitidos a A cuando sea creado (así B es un experto respecto de la
creación de A).
Alto Acoplamiento


#### Página 124

Pasando en limpio…
Esta solución aplica los
patrones:
 Creador
 Bajo Acoplamiento


#### Tabla 1 — Página 124

| Pasando en limpio…
Esta solución aplica los
patrones:
 Creador
 Bajo Acoplamiento |  |
| --- | --- |


#### Tabla 2 — Página 124

|  |  |
| --- | --- |


#### Tabla 3 — Página 124

|  |  |
| --- | --- |


#### Página 125

Baja Cohesión
Mientras tanto…
¿Cómo se ve la clase GestorFestival con esta solución?


#### Página 126

Entonces la solución elegida
aplica los patrones:
 Controlador
 Experto
 Creador
 Bajo Acoplamiento
 Alta Cohesión


#### Página 127

Patrón Controlador
Problema
¿Quién debería encargarse de atender un evento del sistema?
Un evento del sistema es un evento de alto nivel generado por el
actor externo.
Solución
Asignar la responsabilidad del manejo de un mensaje de los eventos
de un sistema, a una clase controladora de esos eventos
Explicación
Un controlador de caso de uso es una buena alternativa cuando hay
muchos eventos del sistema entre varios procesos: asigna su manejo a
clases individuales controlables
Beneficios
Garantiza que los procesos del dominio sean manejados por la capa del
dominio y no por la de interfaz. Reflexionar sobre el estado de un caso de uso:
asegurar que las operaciones ocurran en una cierta secuencia o saber el estado
actual de las operaciones del caso de uso.


#### Página 128

Patrón Experto
Problema
¿Cuál es el principio fundamental en virtud del cual se asignan
las responsabilidades en el diseño orientado a objetos?
Solución
Asignar una responsabilidad al experto en información: la clase
que cuenta con la información necesaria para cumplir con la
responsabilidad.
Explicación
Los objetos hacen cosas relacionadas con la información que
poseen.
Puede haber expertos parciales
Beneficios
Bajo el acoplamiento
El comportamiento se distribuye entre las clases que cuentan
con la información requerida
Judith Meles


#### Página 129

Patrón Creador
Problema
¿Quién debería ser el responsable de crear una
nueva instancia de alguna clase?
Solución
Asignar a la clase B la responsabilidad de crear una instancia de la clase A cuando:
B agrega/ contiene los objetos de A; B utiliza específicamente los objetos de A; B
tiene los datos de inicialización que serán transmitidos a Acuando sea creado
Explicación
Encontrar un creador que debemos conectar con el objeto
producido, esto soporta el bajo acoplamiento. El agregado “agrega”
la parte, el contenedor “contiene” el contenido, el registro “registra”.
Beneficios
Ayuda al bajo acoplamiento, supone menos dependencias.
Como la clase creada tiende a ser visible al creador (razón por la
cual se la eligió).


#### Página 130

Patrón Bajo Acoplamiento
Problema
¿Cómo dar soporte a una dependencia escasa y a
un aumento de reutilización?
Solución
Asignar una responsabilidad para mantener bajo
el acoplamiento.
Explicación
Clases más independientes, que reducen el impacto de los cambios, y
también más reutilizables. Un grado moderado de acoplamiento es normal
para crear un sistema OO, donde los objetos colaboran entre sí.
Beneficios
No se afectan componentes por cambios de otros componentes.
Fáciles de entender por separado. Fáciles de reutilizar.


#### Página 131

Patrón Alta Cohesión
Problema
Las clases con baja cohesión a menudo representan un grado de
abstracción alto o han asumido responsabilidades que deberían
haber delegado en otros objetos.
Solución
Asignar una responsabilidad de modo que la
cohesión siga siendo alta.
Explicación
Una clase de alta cohesión tiene un número relativamente pequeño de
operaciones con funcionalidad relacionada y poco trabajo por hacer.
Colabora con otros objetos para compartir esfuerzo si la tarea es grande.
Beneficios
Mejoranla claridad y la facilidad de comprensión Simplifican la evolución.
A menudo se genera el bajo acoplamiento. Soporta una mayor capacidad de
reutilización, porque una clase muy cohesiva puede destinarse a un propósito muy
específico


#### Página 132

Realización de Análisis del Caso de Uso Registrar Festival
Vista Dinámica con Diagrama de comunicación Vista de Estructura de Clases de análisis
para el escenario del Curso Normal con Diagrama de Clases


#### Página 133

Repasando lo que vimos…
Realizaciones de
Clases de Análisis
Modelo de Análisis CU de Análisis
Patrones GRASP
para Análisis


#### Página 134

Patrones Grasp para
Análisis
Experto en Información
Creador
Bajo Acoplamiento
Alta Cohesión
Controlador


#### Tabla 1 — Página 134

| Patrones Grasp para
Análisis
Experto en Información
Creador
Bajo Acoplamiento
Alta Cohesión
Controlador |  |
| --- | --- |


#### Tabla 2 — Página 134

|  |  |
| --- | --- |


#### Página 135

CÁTEDRA DE DISEÑO DE SISTEMAS
DE INFORMACIÓN
Finalmente…
Muchas
Gracias!!!


#### Página 136

Tips para la construcción de
artefactos del Modelo de Análisis
Judith Meles
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 136

|  |  |
| --- | --- |
|  | Tips para la construcción de
artefactos del Modelo de Análisis
Judith Meles
Cátedra de Diseño de Sistemas de Información
Judith Meles |
|  | Judith Meles |
|  |  |


#### Página 137

Creación de Objetos: Creación de un objeto
• Vemos la estructura para analizarla e
identificar el objeto a crear.
• Objeto de la clase
SolicitudDeRequerimiento
✔ Tiene atributos por valor (propios)
✔ Que el actor ingresa (descripción)
✔ Que asigna el sistema (fechaCreacion/número)
✔ Tiene atributos por referencia
✔ Que el actor elige (ProductoSW/TipoSR)
✔ Que asigna el sistema (Estado)
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 137

|  |  |
| --- | --- |


#### Página 138

Creación de Objetos:
Creación de un objeto
En la dinámica simplificada, el Gestor se
encarga primero de:
1. Obtener los atributos que necesita
✔ Atributos por valor:
✔ Que ingresa el actor
✔ Que obtiene el sistema
(Gestor)
✔ Atributos por referencia:
✔ Que el actor selecciona
(ProductoSW/TipoSR)
✔ Predefinidos en el sistema
(Estado); en el caso de la
creación no hay estado
anterior.
2. Crear el objeto
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 138

|  |  |
| --- | --- |


#### Tabla 2 — Página 138

|  | C |
| --- | --- |


#### Página 139

¿Qué vimos …?
Búsqueda de todos los objetos de una clase para pedir que el actor seleccione uno.
Búsqueda de un objeto con un criterio.
Obtención de fecha actual
Obtención del último número para asignar el siguiente al momento de creación del nuevo objeto
Creación de un objeto luego de tener todos los atributos (propios y por referencia) que
necesitamos para crearlo.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 139

|  |  |
| --- | --- |


#### Página 140

Creación que implica crear objetos de más de una
clase
• Vemos la estructura para analizarla e
identificar los objetos a crear.
• 1 objeto de la clase Festival y al menos 1
objetos de la clase DiaFestival.
• Resto de las referencias tienen
multiplicidad 0..*., no se las tiene en
cuenta en la creación.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 140

|  |  |
| --- | --- |


#### Página 141

Creación que implica
crear objetos de más de
una clase
En la dinámica el Gestor se encarga primero
de:
1. Obtener los atributos que necesitan
para el todo y para las partes.
✔ Atributos por valor: los ingresa el
actor
✔ Validar la existencia previa
2. Crear el objeto “Todo”
3. Delegar al objeto “Todo” la
responsabilidad de creación de los
objetos que agrega/contiene/conoce
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 141

|  | Creación que implica
crear objetos de más de
una clase |
| --- | --- |
| Creación que implica
crear objetos de más de
una clase
En la dinámica el Gestor se encarga primero
de:
1. Obtener los atributos que necesitan
para el todo y para las partes.
✔ Atributos por valor: los ingresa el
actor
✔ Validar la existencia previa
2. Crear el objeto “Todo”
3. Delegar al objeto “Todo” la
responsabilidad de creación de los
objetos que agrega/contiene/conoce | Creación que implica
crear objetos de más de
una clase |


#### Tabla 2 — Página 141

|  |  |
| --- | --- |


#### Tabla 3 — Página 141

|  |  |
| --- | --- |


#### Página 142

¿Qué vimos hasta acá…?
Búsqueda de todos los objetos de una clase para pedir que el actor seleccione uno.
Búsqueda de un objeto con un criterio.
Obtención de fecha actual
Obtención del último número para asignar el siguiente al momento de creación del nuevo objeto
Creación de un objeto luego de tener todos los atributos (propios y por referencia) que necesitamos
para crearlo.
Creación de objetos de más de una clase (cuando hay una estructura tipo Todo-Parte)
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 142

|  |  |
| --- | --- |


#### Página 143

• Vemos la estructura para analizarla e identificar el objeto a crear.
Creación de objetos de
• Objeto de la clase SolicitudDeRequerimiento y Objeto de la clase CambioEstadoSR
más de una clase:
✔ Tiene atributos por valor (propios)
Objeto con su cambio de ✔ Que asigna el sistema (FechaHoraInicio)
✔ Tiene atributos por referencia
estado
✔ Que el actor elige (ProductoSW/TipoSR)
✔ Que asigna el sistema (Estado/Responsable)
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 143

|  |
| --- |
| • Vemos la estructura para analizarla e identificar el objeto a crear.
Creación de objetos de
• Objeto de la clase SolicitudDeRequerimiento y Objeto de la clase CambioEstadoS
más de una clase:
✔ Tiene atributos por valor (propios)
Objeto con su cambio de ✔ Que asigna el sistema (FechaHoraInicio)
✔ Tiene atributos por referencia
estado
✔ Que el actor elige (ProductoSW/TipoSR) |
| ✔ Que asigna el sistema (Estado/Responsable) |


#### Tabla 2 — Página 143

|  |  |
| --- | --- |
|  |  |
|  |  |


#### Página 144

Creación de objetos de más
de una clase:
Objeto con su cambio de
estado
En la dinámica simplificada, el Gestor se encarga
primero de:
1. Obtener los atributos que necesita
✔ Atributos por valor: los ingresa el actor
✔ Atributos que selecciona el actor
2. Gestor obtiene los atributos que necesita
Estado/FechaHoraInicio/ Responsable.
3. Gestor crea la SR y le delega a esta la
responsabilidad de crear su cambio de
estado.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 144

|  |  |
| --- | --- |


#### Página 145

¿Qué vimos …?
Búsqueda de todos los objetos de una clase para pedir que el actor seleccione
Obtención de fecha actual
Obtención del usuario de la sesión
Creación de un objeto luego de tener todos los atributos (propios y por referencia) que necesitamos para
crearlo.
Creación de objetos de más de una clase (cuando hay una estructura tipo Todo-Parte)
Creación de objetos de más de una clase cuando el objeto crea su cambio de estado.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 145

|  |  |
| --- | --- |


#### Página 146

Modificación de objetos:
Modificación de atributos propios de un Objeto
• Vemos la estructura para
analizarla e identificar el objeto a
modificar.
• Objeto de la clase Producto
• Vamos a modificar el precio
del producto cuyo código es
“3d4f6789”
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 146

| Modificación de objetos:
Modificación de atributos propios de un Objeto |  |
| --- | --- |
|  |  |
|  | • Vemos la estructura para
analizarla e identificar el objeto a
modificar.
• Objeto de la clase Producto
• Vamos a modificar el precio
del producto cuyo código es
“3d4f6789” |


#### Tabla 2 — Página 146

|  |  |
| --- | --- |


#### Página 147

Modificación de objetos:
Modificación de atributos propios de
un Objeto
•En la dinámica simplificada primero:
• Se ingresa el código para buscar el
producto
• Gestor busca el producto muestra sus
datos.
• Se ingresa el nuevo precio
• Gestor invoca el método de seteo del
atributo precio, actualizando el valor.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 147

|  |  |
| --- | --- |


#### Tabla 2 — Página 147

|  | M |
| --- | --- |


#### Página 148

Modificación de objetos:
Modificación de atributos propios para todos los objetos de la
clase.
• Vemos la estructura para analizarla
e identificar los objetos a modificar.
• Todos los objetos de la clase
Producto tienen un incremento del
10%.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 148

|  |  |
| --- | --- |


#### Página 149

Modificación de objetos: •En la dinámica simplificada primero:
• Se ingresa el % de aumento
Modificación de atributos
propios para todos los objetos • Gestor con su método incrementarPrecio() invoca el método
calcularIncremento() de todos los objetos producto de la clase.
de la clase.
• Luego cada objeto producto se setea su nuevo precio calculado
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 149

|  |
| --- |
| Modificación de objetos: •En la dinámica simplificada primero:
• Se ingresa el % de aumento
Modificación de atributos
propios para todos los objetos • Gestor con su método incrementarPrecio() invoca el método
calcularIncremento() de todos los objetos producto de la clase.
de la clase. |
| • Luego cada objeto producto se setea su nuevo precio calculado |


#### Tabla 2 — Página 149

|  |  |
| --- | --- |
|  |  |
|  |  |


#### Página 150

Modificación de objetos:
Modificación de atributos propios para todos los objetos que
cumplen un criterio
• Vemos la estructura para analizarla
e identificar los objetos a modificar.
• Objetos de la clase Producto que
tengan la marca “Sancor”, le vamos
a incrementar el precio en un
porcentaje.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 150

|  |  |
| --- | --- |


#### Página 151

Modificación de objetos:
Modificación de atributos
propios para todos los
objetos que cumplen un
criterio
•En la dinámica simplificada primero:
• Se selecciona la marca
• Gestor busca todos los productos de esa
marca, hacienda una validación con
atributos de referencia.
• Se ingresa el % de incremento.
• Gestor invoca el método
calcularIncremento() de los objetos
producto de esa marca
• Luego cada objeto producto se setea su
nuevo precio calculado
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 151

|  |  |
| --- | --- |


#### Tabla 2 — Página 151

|  |  |
| --- | --- |


#### Página 152

Modificación de objetos:
Modificación de un atributo de referencia para todos los objetos
que cumplen un criterio
• Vemos la estructura para analizarla
e identificar los objetos a modificar.
• Objetos de la clase Producto que
tengan la marca “Sancor”, los
vamos a cambiar de sector.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 152

|  |  |
| --- | --- |


#### Página 153

Modificación de objetos:
Modificación de un atributo
de referencia para todos los
objetos que cumplen un
criterio
•En la dinámica simplificada, primero:
• Gestor busca todos los sectores y los
muestra.
• Se selecciona sector destino para los
productos.
• Gestor busca los objetos producto de esa
marca
• Luego asigna el sector elegido a los objetos
de la marca.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 153

|  |  |
| --- | --- |


#### Página 154

¿Qué vimos…?
Modificación de atributos
Modificación de atributos propios para todos los
propios de un objeto objetos que cumplen un
criterio
Modificación de un atributo
Modificación de atributos
de referencia para todos los
propios para todos los
objetos que cumplen un
objetos de la clase.
criterio
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 154

|  |  |
| --- | --- |


#### Página 155

Manejo de Estados: • Por ejemplo: Queremos cancelar un pedido y por
Actualizar el estado consiguiente cancelar sus detalles de pedido.
de un objeto
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 155

|  |
| --- |
| Manejo de Estados: • Por ejemplo: Queremos cancelar un pedido y por
Actualizar el estado consiguiente cancelar sus detalles de pedido.
de un objeto |
|  |


#### Tabla 2 — Página 155

|  |  |
| --- | --- |
|  |  |
|  |  |


#### Página 156

Manejo de Estados:
Actualizar el estado de un
objeto
• En la dinámica simplificada, el GestorPedido
busca el estado que necesita asignar al
pedido y sus detalles; en este caso el estado
“cancelado”.
• Se usa el método modelado en la transición
de correspondiente de la máquina de
estados, en este caso “cancelar()” con la
referencia al objeto cancelado como
parámetro del método.
• Luego el pedido cancela del mismo modo sus
detalles de pedido.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 156

|  |  |
| --- | --- |


#### Tabla 2 — Página 156

|  |  |
| --- | --- |


#### Página 157

• Por ejemplo: Queremos cambiar el
Manejo de Estados: Actualizar
estado de la solicitud elegida de
estado cuando hay estado
EnAnálisis a Suspendida.
actual y anterior
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 157

|  |
| --- |
| • Por ejemplo: Queremos cambiar el
Manejo de Estados: Actualizar
estado de la solicitud elegida de
estado cuando hay estado
EnAnálisis a Suspendida.
actual y anterior |
|  |


#### Tabla 2 — Página 157

|  |  |
| --- | --- |
|  |  |
|  |  |


#### Página 158

Manejo de Estados: Actualizar
estado cuando hay estado
actual y anterior
•En la dinámica simplificada, primero:
• Gestor busca las SR que pueden
ser suspendidas y las muestra.
• Actor selecciona la SR que desea
suspender.
• Gestor busca el estado a asignar,
en este caso “Suspendida”.
• Se suspende la SR, lo que implica
setear el estado anterior con el
estado actual y el estado actual
con “Suspendida”.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 158

|  |  | o de Estados: Actualizar
cuando hay estado
y anterior |
| --- | --- | --- |
| Manejo de Estados: Actualizar
estado cuando hay estado
actual y anterior
•En la dinámica simplificada, primero:
• Gestor busca las SR que pueden
ser suspendidas y las muestra.
• Actor selecciona la SR que desea
suspender.
• Gestor busca el estado a asignar,
en este caso “Suspendida”.
• Se suspende la SR, lo que implica
setear el estado anterior con el
estado actual y el estado actual
con “Suspendida”.
Cátedra de Diseño de Sistemas de Información
Judith Meles | anejo de Estados: Actualizar
stado cuando hay estado
ctual y anterior
ámica simplificada, primero:
or busca las SR que pueden
uspendidas y las muestra.
r selecciona la SR que desea
ender.
or busca el estado a asignar,
te caso “Suspendida”.
spende la SR, lo que implica
r el estado anterior con el
do actual y el estado actual
Suspendida”.
Cátedra de Diseño de Sistemas de Información
Judith Meles | o de Estados: Actualizar
cuando hay estado
y anterior |


#### Tabla 2 — Página 158

| j
o | o |
| --- | --- |


#### Página 159

• Por ejemplo: Queremos cambiar el estado de la solicitud
Manejo de Estados:
elegida de EnAnálisis a Suspendida.
Actualizar estado cuando
se mantienen los • Queremos saber quién hizo el cambio de estado y
cambios de estado cuándo.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 159

|  |
| --- |
| • Por ejemplo: Queremos cambiar el estado de la solicitud
Manejo de Estados:
elegida de EnAnálisis a Suspendida.
Actualizar estado cuando
se mantienen los • Queremos saber quién hizo el cambio de estado y
cambios de estado cuándo. |
|  |


#### Tabla 2 — Página 159

|  |  |
| --- | --- |
|  |  |
|  |  |


#### Página 160

Manejo de Estados: Actualizar
estado cuando se mantienen los
cambios de estado
•En la dinámica simplificada, primero:
• Gestor busca las SR que pueden ser
suspendidas y las muestra.
• Actor selecciona la SR que desea suspender.
• Gestor busca el estado a asignar, en este
caso “Suspendida”.
• Gestor obtiene fecha y hora actual y obtiene
el responsable desde la sesión de usuario
activa, utilizando el atributo de referencia. En
este caso no se requiere pedirle nada al
objeto Responsable.
• Gestor suspende la solicitud.
• La SR busca el estado actual para cerrarlo y
luego crea el nuevo cambio de estado, en
este caso Suspendida
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 160

|  | Manejo de Estados: Actualizar
estado cuando se mantienen los
cambios de estado |
| --- | --- |
| Manejo de Estados: Actualizar
estado cuando se mantienen los
cambios de estado
•En la dinámica simplificada, primero:
• Gestor busca las SR que pueden ser
suspendidas y las muestra.
• Actor selecciona la SR que desea suspender.
• Gestor busca el estado a asignar, en este
caso “Suspendida”.
• Gestor obtiene fecha y hora actual y obtiene
el responsable desde la sesión de usuario
activa, utilizando el atributo de referencia. En
este caso no se requiere pedirle nada al
objeto Responsable.
• Gestor suspende la solicitud.
• La SR busca el estado actual para cerrarlo y
luego crea el nuevo cambio de estado, en
este caso Suspendida | Manejo de Estados: Actualizar
estado cuando se mantienen los
cambios de estado |


#### Tabla 2 — Página 160

|  |  |
| --- | --- |


#### Página 161

¿Cómo se modela
• Queremos modelar varias clases que tienen
cuando tenemos un comportamiento dependiente del estado utilizando una
atributo ámbito en la sola clase Estado
clase Estado? • Una forma es con un atributo ámbito
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 161

|  |
| --- |
| ¿Cómo se modela
• Queremos modelar varias clases que tienen
cuando tenemos un comportamiento dependiente del estado utilizando una
atributo ámbito en la sola clase Estado
clase Estado? • Una forma es con un atributo ámbito |
|  |


#### Tabla 2 — Página 161

|  |  |
| --- | --- |
|  |  |
|  |  |


#### Página 162

Manejo de Estados: Actualizar el estado de un objeto
Manejo de estados: Actualizar estado cuando hay estado actual y
anterior en la estructura.
Manejo de Estados: Actualizar estado cuando se mantienen los
cambios de estado, (historial de estados).
¿Qué vimos…?
Manejo de Estados: Cómo se modela con el atributo ámbito dentro
de la clase estado.
Obtener usuario logueado
Obtener fecha y hora actual del sistema.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 162

|  |  |  |
| --- | --- | --- |
|  |  |  |


#### Página 163

• El Gestor necesita mostrar la información sobre las reservas y
¿Cómo funciona la
pide colaboración, utilizando el patrón experto a quién tiene la
información.
colaboración entre
• ¿Puedo yo responder a esté mensaje solo? Si no, pido
los objetos?
colaboración… así hasta llegar al objeto que puede, porque
tiene la información.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 163

|  |
| --- |
| • El Gestor necesita mostrar la información sobre las reservas y
¿Cómo funciona la
pide colaboración, utilizando el patrón experto a quién tiene la
información.
colaboración entre
• ¿Puedo yo responder a esté mensaje solo? Si no, pido
los objetos?
colaboración… así hasta llegar al objeto que puede, porque |
| tiene la información. |


#### Tabla 2 — Página 163

|  |  |
| --- | --- |
|  |  |
|  |  |


#### Página 164

¿Todas las realizaciones de
• Queremos modelar un caso de uso o
casos de uso tienen un objeto temporal
Boundary?
• No hay actor, no hay objeto boundary
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 164

|  |  |  |
| --- | --- | --- |
| ¿Todas las realizaciones de
• Queremos modelar un caso de uso o
casos de uso tienen un objeto temporal
Boundary?
• No hay actor, no hay objeto boundary
Cátedra de Diseño de Sistemas de Información
Judith Meles | ¿Todas las realizaciones de
• Queremos modelar un caso de uso o
casos de uso tienen un objeto temporal
Boundary?
• No hay actor, no hay objeto boundary |  |
|  |  |  |


#### Tabla 2 — Página 164

|  | ¿T |
| --- | --- |
|  |  |
|  |  |


#### Página 165

Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Página 166

¿Cómo reflejamos
acciones
opcionales?
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 166

|  |
| --- |
| ¿Cómo reflejamos
acciones
opcionales?
Cátedra de Diseño de Sistemas de Información
Judith Meles |
|  |


#### Tabla 2 — Página 166

|  |  |
| --- | --- |
|  |  |


#### Tabla 3 — Página 166

|  |  |
| --- | --- |


#### Página 167

• 9. Sistema: Envía a la opción registrada por defecto
(mail, sms, WhatsApp) de cada Consultor el aviso del
¿Cómo reflejamos acciones
nivel actual asignado. Fin del caso de uso.
alternativas?
(Observación 3 y 4)
Observación 3: Los Consultores
al registrarse eligen una
opción de notificación por
defecto para recibir
información.
Observación 4: En el aviso se
notifica la cantidad de
puntos obtenidos como
resultado del procesamiento
y el nivel actual.
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 167

|  |  |
| --- | --- |
|  |  |
|  |  |


#### Página 168

Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Página 169

¿Cómo se modelan las llamadas a otros casos de uso?
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 169

|  |  |  |
| --- | --- | --- |
| ¿Cómo se modelan las llamadas a otros casos de uso?
Cátedra de Diseño de Sistemas de Información
Judith Meles | ¿Cómo se modelan las llamadas a otros casos de uso? |  |


#### Tabla 2 — Página 169

|  |  |
| --- | --- |
|  |  |


#### Página 170

Cómo funciona la colaboración entre objetos
Cómo se modelan los casos de uso abstractos
Cómo se modelan las llamadas a casos de uso de inclusión y/o
¿Qué vimos…?
extensión con el diagrama de comunicación y de secuencia
Cómo se modelan situaciones alternativas y opcionales con
fragmentos en el diagrama de secuencia.
El constructor es un método estático (método de clase)
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 170

|  |  |  |
| --- | --- | --- |
|  |  |  |


#### Página 171

Las acciones sobre los objetos se resumen a:
Modificar valores de atributos Mostrar valores de Eliminar/Anular/
Crear objetos
permitidos atributos Cancelar
• Localizar el o los objetos a
• Tener todos los • Saber que queremos •Localizar el o los objetos a
modificar.
atributos (por valor o mostrar. eliminar/anular/cancelar.
• Tener en cuenta las reglas de
por referencia), • Pedir filtros de •Validar las reglas de
Negocio. Negocio.
necesarios consulta si hace falta.
• Obtener los nuevos valores •Pedir confirmación
• Decidir quién crea • Iterar para buscar
(puede ser calculándolos o •Decidir quién debe hacerlo.
• Mostrar.
recibiéndolos como •Eliminación física/lógica ≠
parámetros). • Decidir quien tiene la Anular/Cancelar
responsabilidad
• Asignarlos a los atributos
correspondientes
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 171

| Las acciones sobre los objetos se resumen a:
Modificar valores de atributos Mostrar valores de Eliminar/Anular/
Crear objetos
permitidos atributos Cancelar |  |  |
| --- | --- | --- |
|  | Eliminar/Anular/
Cancelar |  |
|  |  |  |


#### Tabla 2 — Página 171

|  |  |
| --- | --- |


#### Página 172

Dudas, consultas….
Finalmente…
Muchas Gracias!!!
Cátedra de Diseño de Sistemas de Información
Judith Meles


#### Tabla 1 — Página 172

|  | Dudas, consultas…. |
| --- | --- |
|  |  |
|  |  |


#### Tabla 2 — Página 172

|  |  |
| --- | --- |
|  |  |


### 🖼️ Imágenes Extraídas (472 imágenes)

#### Imagen 1 — Página 1 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 2 — Página 1 (51.0 KB)

> 📄 **Diagrama/Imagen — Página 1**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `1`
> *(Para ver: abrir PDF en página 1)*


#### Imagen 3 — Página 2 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 4 — Página 2 (14.0 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 5 — Página 2 (13.6 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 6 — Página 2 (13.4 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 7 — Página 2 (13.4 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 8 — Página 2 (13.4 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 9 — Página 2 (13.1 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 10 — Página 2 (13.4 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 11 — Página 2 (13.5 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 12 — Página 2 (16.3 KB)

> 📄 **Diagrama/Imagen — Página 2**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `2`
> *(Para ver: abrir PDF en página 2)*


#### Imagen 13 — Página 3 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 14 — Página 3 (136.5 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 15 — Página 3 (21.5 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 16 — Página 3 (56.2 KB)

> 📄 **Diagrama/Imagen — Página 3**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `3`
> *(Para ver: abrir PDF en página 3)*


#### Imagen 17 — Página 4 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 18 — Página 4 (11.5 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 19 — Página 4 (13.9 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 20 — Página 4 (11.8 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 21 — Página 4 (12.8 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 22 — Página 4 (11.9 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 23 — Página 4 (12.8 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 24 — Página 4 (12.4 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 25 — Página 4 (10.3 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 26 — Página 4 (6.5 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 27 — Página 4 (7.1 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 28 — Página 4 (12.5 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 29 — Página 4 (7.1 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 30 — Página 4 (11.8 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 31 — Página 5 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 32 — Página 5 (11.5 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 33 — Página 5 (13.9 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 34 — Página 5 (11.8 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 35 — Página 5 (12.8 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 36 — Página 5 (11.9 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 37 — Página 5 (12.8 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 38 — Página 5 (12.4 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 39 — Página 5 (10.3 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 40 — Página 5 (12.0 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 41 — Página 5 (6.1 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 42 — Página 5 (12.5 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 43 — Página 5 (12.6 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 44 — Página 5 (11.8 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 45 — Página 6 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 46 — Página 6 (18.3 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 47 — Página 6 (17.6 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 48 — Página 6 (51.1 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 49 — Página 6 (24.9 KB)

> 📄 **Diagrama/Imagen — Página 6**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `6`
> *(Para ver: abrir PDF en página 6)*


#### Imagen 50 — Página 7 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 7**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `7`
> *(Para ver: abrir PDF en página 7)*


#### Imagen 51 — Página 7 (24.5 KB)

> 📄 **Diagrama/Imagen — Página 7**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `7`
> *(Para ver: abrir PDF en página 7)*


#### Imagen 52 — Página 7 (43.3 KB)

> 📄 **Diagrama/Imagen — Página 7**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `7`
> *(Para ver: abrir PDF en página 7)*


#### Imagen 53 — Página 8 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 8**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `8`
> *(Para ver: abrir PDF en página 8)*


#### Imagen 54 — Página 8 (172.5 KB)

> 📄 **Diagrama/Imagen — Página 8**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `8`
> *(Para ver: abrir PDF en página 8)*


#### Imagen 55 — Página 9 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 56 — Página 9 (172.5 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 57 — Página 10 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 10**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `10`
> *(Para ver: abrir PDF en página 10)*


#### Imagen 58 — Página 11 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 11**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `11`
> *(Para ver: abrir PDF en página 11)*


#### Imagen 59 — Página 11 (178.3 KB)

> 📄 **Diagrama/Imagen — Página 11**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `11`
> *(Para ver: abrir PDF en página 11)*


#### Imagen 60 — Página 12 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 12**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `12`
> *(Para ver: abrir PDF en página 12)*


#### Imagen 61 — Página 12 (178.5 KB)

> 📄 **Diagrama/Imagen — Página 12**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `12`
> *(Para ver: abrir PDF en página 12)*


#### Imagen 62 — Página 13 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 13**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `13`
> *(Para ver: abrir PDF en página 13)*


#### Imagen 63 — Página 13 (172.5 KB)

> 📄 **Diagrama/Imagen — Página 13**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `13`
> *(Para ver: abrir PDF en página 13)*


#### Imagen 64 — Página 14 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 65 — Página 14 (172.5 KB)

> 📄 **Diagrama/Imagen — Página 14**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `14`
> *(Para ver: abrir PDF en página 14)*


#### Imagen 66 — Página 15 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 67 — Página 15 (5.8 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 68 — Página 15 (16.7 KB)

> 📄 **Diagrama/Imagen — Página 15**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `15`
> *(Para ver: abrir PDF en página 15)*


#### Imagen 69 — Página 16 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 70 — Página 16 (5.2 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 71 — Página 16 (5.5 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 72 — Página 16 (11.8 KB)

> 📄 **Diagrama/Imagen — Página 16**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `16`
> *(Para ver: abrir PDF en página 16)*


#### Imagen 73 — Página 17 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 74 — Página 17 (4.9 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 75 — Página 17 (5.3 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 76 — Página 17 (17.4 KB)

> 📄 **Diagrama/Imagen — Página 17**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `17`
> *(Para ver: abrir PDF en página 17)*


#### Imagen 77 — Página 18 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 18**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `18`
> *(Para ver: abrir PDF en página 18)*


#### Imagen 78 — Página 18 (23.1 KB)

> 📄 **Diagrama/Imagen — Página 18**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `18`
> *(Para ver: abrir PDF en página 18)*


#### Imagen 79 — Página 19 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 19**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `19`
> *(Para ver: abrir PDF en página 19)*


#### Imagen 80 — Página 19 (39.0 KB)

> 📄 **Diagrama/Imagen — Página 19**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `19`
> *(Para ver: abrir PDF en página 19)*


#### Imagen 81 — Página 20 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 82 — Página 20 (43.7 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 83 — Página 20 (27.6 KB)

> 📄 **Diagrama/Imagen — Página 20**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `20`
> *(Para ver: abrir PDF en página 20)*


#### Imagen 84 — Página 21 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 21**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `21`
> *(Para ver: abrir PDF en página 21)*


#### Imagen 85 — Página 21 (56.7 KB)

> 📄 **Diagrama/Imagen — Página 21**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `21`
> *(Para ver: abrir PDF en página 21)*


#### Imagen 86 — Página 21 (43.4 KB)

> 📄 **Diagrama/Imagen — Página 21**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `21`
> *(Para ver: abrir PDF en página 21)*


#### Imagen 87 — Página 21 (27.6 KB)

> 📄 **Diagrama/Imagen — Página 21**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `21`
> *(Para ver: abrir PDF en página 21)*


#### Imagen 88 — Página 22 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*


#### Imagen 89 — Página 22 (143.8 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*


#### Imagen 90 — Página 22 (259.2 KB)

> 📄 **Diagrama/Imagen — Página 22**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `22`
> *(Para ver: abrir PDF en página 22)*


#### Imagen 91 — Página 23 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 92 — Página 23 (78.7 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 93 — Página 23 (48.9 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 94 — Página 23 (143.8 KB)

> 📄 **Diagrama/Imagen — Página 23**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `23`
> *(Para ver: abrir PDF en página 23)*


#### Imagen 95 — Página 24 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 24**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `24`
> *(Para ver: abrir PDF en página 24)*


#### Imagen 96 — Página 24 (59.8 KB)

> 📄 **Diagrama/Imagen — Página 24**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `24`
> *(Para ver: abrir PDF en página 24)*


#### Imagen 97 — Página 24 (48.9 KB)

> 📄 **Diagrama/Imagen — Página 24**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `24`
> *(Para ver: abrir PDF en página 24)*


#### Imagen 98 — Página 24 (80.8 KB)

> 📄 **Diagrama/Imagen — Página 24**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `24`
> *(Para ver: abrir PDF en página 24)*


#### Imagen 99 — Página 24 (47.0 KB)

> 📄 **Diagrama/Imagen — Página 24**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `24`
> *(Para ver: abrir PDF en página 24)*


#### Imagen 100 — Página 25 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 101 — Página 25 (80.8 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 102 — Página 25 (59.8 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 103 — Página 25 (63.4 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 104 — Página 25 (48.9 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 105 — Página 25 (7.6 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 106 — Página 25 (4.9 KB)

> 📄 **Diagrama/Imagen — Página 25**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `25`
> *(Para ver: abrir PDF en página 25)*


#### Imagen 107 — Página 26 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 26**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `26`
> *(Para ver: abrir PDF en página 26)*


#### Imagen 108 — Página 26 (59.8 KB)

> 📄 **Diagrama/Imagen — Página 26**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `26`
> *(Para ver: abrir PDF en página 26)*


#### Imagen 109 — Página 26 (143.8 KB)

> 📄 **Diagrama/Imagen — Página 26**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `26`
> *(Para ver: abrir PDF en página 26)*


#### Imagen 110 — Página 27 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 27**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `27`
> *(Para ver: abrir PDF en página 27)*


#### Imagen 111 — Página 27 (297.2 KB)

> 📄 **Diagrama/Imagen — Página 27**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `27`
> *(Para ver: abrir PDF en página 27)*


#### Imagen 112 — Página 27 (59.8 KB)

> 📄 **Diagrama/Imagen — Página 27**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `27`
> *(Para ver: abrir PDF en página 27)*


#### Imagen 113 — Página 28 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 114 — Página 28 (107.6 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 115 — Página 28 (59.2 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 116 — Página 28 (162.2 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 117 — Página 28 (104.6 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 118 — Página 28 (86.5 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 119 — Página 28 (69.4 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 120 — Página 28 (59.4 KB)

> 📄 **Diagrama/Imagen — Página 28**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `28`
> *(Para ver: abrir PDF en página 28)*


#### Imagen 121 — Página 29 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 29**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `29`
> *(Para ver: abrir PDF en página 29)*


#### Imagen 122 — Página 29 (19.6 KB)

> 📄 **Diagrama/Imagen — Página 29**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `29`
> *(Para ver: abrir PDF en página 29)*


#### Imagen 123 — Página 30 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 30**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `30`
> *(Para ver: abrir PDF en página 30)*


#### Imagen 124 — Página 30 (14.6 KB)

> 📄 **Diagrama/Imagen — Página 30**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `30`
> *(Para ver: abrir PDF en página 30)*


#### Imagen 125 — Página 31 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 31**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `31`
> *(Para ver: abrir PDF en página 31)*


#### Imagen 126 — Página 31 (51.0 KB)

> 📄 **Diagrama/Imagen — Página 31**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `31`
> *(Para ver: abrir PDF en página 31)*


#### Imagen 127 — Página 32 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 32**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `32`
> *(Para ver: abrir PDF en página 32)*


#### Imagen 128 — Página 32 (136.5 KB)

> 📄 **Diagrama/Imagen — Página 32**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `32`
> *(Para ver: abrir PDF en página 32)*


#### Imagen 129 — Página 32 (21.5 KB)

> 📄 **Diagrama/Imagen — Página 32**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `32`
> *(Para ver: abrir PDF en página 32)*


#### Imagen 130 — Página 32 (56.2 KB)

> 📄 **Diagrama/Imagen — Página 32**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `32`
> *(Para ver: abrir PDF en página 32)*


#### Imagen 131 — Página 33 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 132 — Página 33 (11.3 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 133 — Página 33 (13.7 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 134 — Página 33 (11.6 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 135 — Página 33 (12.9 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 136 — Página 33 (11.7 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 137 — Página 33 (13.0 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 138 — Página 33 (12.6 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 139 — Página 33 (10.1 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 140 — Página 33 (11.8 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 141 — Página 33 (6.0 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 142 — Página 33 (12.2 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 143 — Página 33 (11.9 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 144 — Página 33 (11.7 KB)

> 📄 **Diagrama/Imagen — Página 33**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `33`
> *(Para ver: abrir PDF en página 33)*


#### Imagen 145 — Página 34 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 34**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `34`
> *(Para ver: abrir PDF en página 34)*


#### Imagen 146 — Página 34 (6.0 KB)

> 📄 **Diagrama/Imagen — Página 34**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `34`
> *(Para ver: abrir PDF en página 34)*


#### Imagen 147 — Página 34 (6.1 KB)

> 📄 **Diagrama/Imagen — Página 34**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `34`
> *(Para ver: abrir PDF en página 34)*


#### Imagen 148 — Página 34 (11.0 KB)

> 📄 **Diagrama/Imagen — Página 34**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `34`
> *(Para ver: abrir PDF en página 34)*


#### Imagen 149 — Página 34 (6.5 KB)

> 📄 **Diagrama/Imagen — Página 34**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `34`
> *(Para ver: abrir PDF en página 34)*


#### Imagen 150 — Página 34 (6.5 KB)

> 📄 **Diagrama/Imagen — Página 34**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `34`
> *(Para ver: abrir PDF en página 34)*


#### Imagen 151 — Página 34 (7.9 KB)

> 📄 **Diagrama/Imagen — Página 34**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `34`
> *(Para ver: abrir PDF en página 34)*


#### Imagen 152 — Página 34 (8.6 KB)

> 📄 **Diagrama/Imagen — Página 34**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `34`
> *(Para ver: abrir PDF en página 34)*


#### Imagen 153 — Página 34 (5.5 KB)

> 📄 **Diagrama/Imagen — Página 34**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `34`
> *(Para ver: abrir PDF en página 34)*


#### Imagen 154 — Página 34 (5.2 KB)

> 📄 **Diagrama/Imagen — Página 34**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `34`
> *(Para ver: abrir PDF en página 34)*


#### Imagen 155 — Página 34 (6.5 KB)

> 📄 **Diagrama/Imagen — Página 34**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `34`
> *(Para ver: abrir PDF en página 34)*


#### Imagen 156 — Página 34 (4.9 KB)

> 📄 **Diagrama/Imagen — Página 34**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `34`
> *(Para ver: abrir PDF en página 34)*


#### Imagen 157 — Página 34 (5.7 KB)

> 📄 **Diagrama/Imagen — Página 34**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `34`
> *(Para ver: abrir PDF en página 34)*


#### Imagen 158 — Página 34 (5.8 KB)

> 📄 **Diagrama/Imagen — Página 34**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `34`
> *(Para ver: abrir PDF en página 34)*


#### Imagen 159 — Página 35 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 35**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `35`
> *(Para ver: abrir PDF en página 35)*


#### Imagen 160 — Página 35 (5.1 KB)

> 📄 **Diagrama/Imagen — Página 35**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `35`
> *(Para ver: abrir PDF en página 35)*


#### Imagen 161 — Página 35 (161.3 KB)

> 📄 **Diagrama/Imagen — Página 35**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `35`
> *(Para ver: abrir PDF en página 35)*


#### Imagen 162 — Página 36 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 36**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `36`
> *(Para ver: abrir PDF en página 36)*


#### Imagen 163 — Página 36 (19.6 KB)

> 📄 **Diagrama/Imagen — Página 36**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `36`
> *(Para ver: abrir PDF en página 36)*


#### Imagen 164 — Página 37 (39.5 KB)

> 📄 **Diagrama/Imagen — Página 37**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `37`
> *(Para ver: abrir PDF en página 37)*


#### Imagen 165 — Página 38 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 38**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `38`
> *(Para ver: abrir PDF en página 38)*


#### Imagen 166 — Página 39 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 39**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `39`
> *(Para ver: abrir PDF en página 39)*


#### Imagen 167 — Página 39 (362.6 KB)

> 📄 **Diagrama/Imagen — Página 39**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `39`
> *(Para ver: abrir PDF en página 39)*


#### Imagen 168 — Página 40 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 40**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `40`
> *(Para ver: abrir PDF en página 40)*


#### Imagen 169 — Página 41 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 41**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `41`
> *(Para ver: abrir PDF en página 41)*


#### Imagen 170 — Página 41 (418.1 KB)

> 📄 **Diagrama/Imagen — Página 41**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `41`
> *(Para ver: abrir PDF en página 41)*


#### Imagen 171 — Página 42 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 42**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `42`
> *(Para ver: abrir PDF en página 42)*


#### Imagen 172 — Página 42 (438.1 KB)

> 📄 **Diagrama/Imagen — Página 42**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `42`
> *(Para ver: abrir PDF en página 42)*


#### Imagen 173 — Página 43 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 43**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `43`
> *(Para ver: abrir PDF en página 43)*


#### Imagen 174 — Página 43 (35.0 KB)

> 📄 **Diagrama/Imagen — Página 43**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `43`
> *(Para ver: abrir PDF en página 43)*


#### Imagen 175 — Página 44 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 44**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `44`
> *(Para ver: abrir PDF en página 44)*


#### Imagen 176 — Página 44 (235.3 KB)

> 📄 **Diagrama/Imagen — Página 44**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `44`
> *(Para ver: abrir PDF en página 44)*


#### Imagen 177 — Página 44 (35.0 KB)

> 📄 **Diagrama/Imagen — Página 44**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `44`
> *(Para ver: abrir PDF en página 44)*


#### Imagen 178 — Página 44 (524.9 KB)

> 📄 **Diagrama/Imagen — Página 44**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `44`
> *(Para ver: abrir PDF en página 44)*


#### Imagen 179 — Página 45 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 45**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `45`
> *(Para ver: abrir PDF en página 45)*


#### Imagen 180 — Página 45 (35.0 KB)

> 📄 **Diagrama/Imagen — Página 45**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `45`
> *(Para ver: abrir PDF en página 45)*


#### Imagen 181 — Página 45 (154.5 KB)

> 📄 **Diagrama/Imagen — Página 45**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `45`
> *(Para ver: abrir PDF en página 45)*


#### Imagen 182 — Página 45 (524.9 KB)

> 📄 **Diagrama/Imagen — Página 45**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `45`
> *(Para ver: abrir PDF en página 45)*


#### Imagen 183 — Página 45 (235.3 KB)

> 📄 **Diagrama/Imagen — Página 45**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `45`
> *(Para ver: abrir PDF en página 45)*


#### Imagen 184 — Página 45 (6.7 KB)

> 📄 **Diagrama/Imagen — Página 45**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `45`
> *(Para ver: abrir PDF en página 45)*


#### Imagen 185 — Página 46 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 46**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `46`
> *(Para ver: abrir PDF en página 46)*


#### Imagen 186 — Página 46 (35.0 KB)

> 📄 **Diagrama/Imagen — Página 46**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `46`
> *(Para ver: abrir PDF en página 46)*


#### Imagen 187 — Página 46 (154.5 KB)

> 📄 **Diagrama/Imagen — Página 46**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `46`
> *(Para ver: abrir PDF en página 46)*


#### Imagen 188 — Página 46 (524.9 KB)

> 📄 **Diagrama/Imagen — Página 46**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `46`
> *(Para ver: abrir PDF en página 46)*


#### Imagen 189 — Página 46 (235.3 KB)

> 📄 **Diagrama/Imagen — Página 46**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `46`
> *(Para ver: abrir PDF en página 46)*


#### Imagen 190 — Página 47 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 47**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `47`
> *(Para ver: abrir PDF en página 47)*


#### Imagen 191 — Página 47 (524.9 KB)

> 📄 **Diagrama/Imagen — Página 47**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `47`
> *(Para ver: abrir PDF en página 47)*


#### Imagen 192 — Página 47 (79.9 KB)

> 📄 **Diagrama/Imagen — Página 47**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `47`
> *(Para ver: abrir PDF en página 47)*


#### Imagen 193 — Página 48 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 48**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `48`
> *(Para ver: abrir PDF en página 48)*


#### Imagen 194 — Página 48 (79.9 KB)

> 📄 **Diagrama/Imagen — Página 48**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `48`
> *(Para ver: abrir PDF en página 48)*


#### Imagen 195 — Página 48 (70.0 KB)

> 📄 **Diagrama/Imagen — Página 48**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `48`
> *(Para ver: abrir PDF en página 48)*


#### Imagen 196 — Página 49 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 49**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `49`
> *(Para ver: abrir PDF en página 49)*


#### Imagen 197 — Página 49 (11.7 KB)

> 📄 **Diagrama/Imagen — Página 49**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `49`
> *(Para ver: abrir PDF en página 49)*


#### Imagen 198 — Página 50 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 50**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `50`
> *(Para ver: abrir PDF en página 50)*


#### Imagen 199 — Página 50 (9.2 KB)

> 📄 **Diagrama/Imagen — Página 50**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `50`
> *(Para ver: abrir PDF en página 50)*


#### Imagen 200 — Página 50 (50.1 KB)

> 📄 **Diagrama/Imagen — Página 50**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `50`
> *(Para ver: abrir PDF en página 50)*


#### Imagen 201 — Página 50 (20.0 KB)

> 📄 **Diagrama/Imagen — Página 50**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `50`
> *(Para ver: abrir PDF en página 50)*


#### Imagen 202 — Página 50 (26.8 KB)

> 📄 **Diagrama/Imagen — Página 50**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `50`
> *(Para ver: abrir PDF en página 50)*


#### Imagen 203 — Página 50 (88.3 KB)

> 📄 **Diagrama/Imagen — Página 50**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `50`
> *(Para ver: abrir PDF en página 50)*


#### Imagen 204 — Página 51 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 51**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `51`
> *(Para ver: abrir PDF en página 51)*


#### Imagen 205 — Página 51 (5.4 KB)

> 📄 **Diagrama/Imagen — Página 51**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `51`
> *(Para ver: abrir PDF en página 51)*


#### Imagen 206 — Página 52 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 52**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `52`
> *(Para ver: abrir PDF en página 52)*


#### Imagen 207 — Página 52 (14.6 KB)

> 📄 **Diagrama/Imagen — Página 52**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `52`
> *(Para ver: abrir PDF en página 52)*


#### Imagen 208 — Página 53 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 53**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `53`
> *(Para ver: abrir PDF en página 53)*


#### Imagen 209 — Página 53 (24.4 KB)

> 📄 **Diagrama/Imagen — Página 53**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `53`
> *(Para ver: abrir PDF en página 53)*


#### Imagen 210 — Página 53 (16.2 KB)

> 📄 **Diagrama/Imagen — Página 53**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `53`
> *(Para ver: abrir PDF en página 53)*


#### Imagen 211 — Página 54 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 54**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `54`
> *(Para ver: abrir PDF en página 54)*


#### Imagen 212 — Página 55 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 55**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `55`
> *(Para ver: abrir PDF en página 55)*


#### Imagen 213 — Página 55 (141.5 KB)

> 📄 **Diagrama/Imagen — Página 55**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `55`
> *(Para ver: abrir PDF en página 55)*


#### Imagen 214 — Página 56 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 56**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `56`
> *(Para ver: abrir PDF en página 56)*


#### Imagen 215 — Página 56 (76.2 KB)

> 📄 **Diagrama/Imagen — Página 56**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `56`
> *(Para ver: abrir PDF en página 56)*


#### Imagen 216 — Página 56 (113.8 KB)

> 📄 **Diagrama/Imagen — Página 56**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `56`
> *(Para ver: abrir PDF en página 56)*


#### Imagen 217 — Página 57 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 57**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `57`
> *(Para ver: abrir PDF en página 57)*


#### Imagen 218 — Página 58 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 58**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `58`
> *(Para ver: abrir PDF en página 58)*


#### Imagen 219 — Página 59 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 59**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `59`
> *(Para ver: abrir PDF en página 59)*


#### Imagen 220 — Página 60 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 60**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `60`
> *(Para ver: abrir PDF en página 60)*


#### Imagen 221 — Página 60 (16.2 KB)

> 📄 **Diagrama/Imagen — Página 60**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `60`
> *(Para ver: abrir PDF en página 60)*


#### Imagen 222 — Página 61 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 61**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `61`
> *(Para ver: abrir PDF en página 61)*


#### Imagen 223 — Página 61 (24.4 KB)

> 📄 **Diagrama/Imagen — Página 61**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `61`
> *(Para ver: abrir PDF en página 61)*


#### Imagen 224 — Página 61 (10.6 KB)

> 📄 **Diagrama/Imagen — Página 61**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `61`
> *(Para ver: abrir PDF en página 61)*


#### Imagen 225 — Página 62 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 62**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `62`
> *(Para ver: abrir PDF en página 62)*


#### Imagen 226 — Página 62 (42.5 KB)

> 📄 **Diagrama/Imagen — Página 62**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `62`
> *(Para ver: abrir PDF en página 62)*


#### Imagen 227 — Página 63 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 63**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `63`
> *(Para ver: abrir PDF en página 63)*


#### Imagen 228 — Página 63 (412.5 KB)

> 📄 **Diagrama/Imagen — Página 63**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `63`
> *(Para ver: abrir PDF en página 63)*


#### Imagen 229 — Página 64 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 64**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `64`
> *(Para ver: abrir PDF en página 64)*


#### Imagen 230 — Página 64 (137.7 KB)

> 📄 **Diagrama/Imagen — Página 64**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `64`
> *(Para ver: abrir PDF en página 64)*


#### Imagen 231 — Página 65 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 65**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `65`
> *(Para ver: abrir PDF en página 65)*


#### Imagen 232 — Página 65 (188.8 KB)

> 📄 **Diagrama/Imagen — Página 65**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `65`
> *(Para ver: abrir PDF en página 65)*


#### Imagen 233 — Página 66 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 66**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `66`
> *(Para ver: abrir PDF en página 66)*


#### Imagen 234 — Página 66 (188.8 KB)

> 📄 **Diagrama/Imagen — Página 66**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `66`
> *(Para ver: abrir PDF en página 66)*


#### Imagen 235 — Página 66 (137.7 KB)

> 📄 **Diagrama/Imagen — Página 66**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `66`
> *(Para ver: abrir PDF en página 66)*


#### Imagen 236 — Página 67 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 67**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `67`
> *(Para ver: abrir PDF en página 67)*


#### Imagen 237 — Página 67 (5.4 KB)

> 📄 **Diagrama/Imagen — Página 67**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `67`
> *(Para ver: abrir PDF en página 67)*


#### Imagen 238 — Página 67 (48.8 KB)

> 📄 **Diagrama/Imagen — Página 67**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `67`
> *(Para ver: abrir PDF en página 67)*


#### Imagen 239 — Página 68 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 68**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `68`
> *(Para ver: abrir PDF en página 68)*


#### Imagen 240 — Página 68 (6.0 KB)

> 📄 **Diagrama/Imagen — Página 68**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `68`
> *(Para ver: abrir PDF en página 68)*


#### Imagen 241 — Página 68 (98.7 KB)

> 📄 **Diagrama/Imagen — Página 68**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `68`
> *(Para ver: abrir PDF en página 68)*


#### Imagen 242 — Página 69 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 69**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `69`
> *(Para ver: abrir PDF en página 69)*


#### Imagen 243 — Página 69 (10.0 KB)

> 📄 **Diagrama/Imagen — Página 69**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `69`
> *(Para ver: abrir PDF en página 69)*


#### Imagen 244 — Página 69 (65.5 KB)

> 📄 **Diagrama/Imagen — Página 69**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `69`
> *(Para ver: abrir PDF en página 69)*


#### Imagen 245 — Página 70 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 70**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `70`
> *(Para ver: abrir PDF en página 70)*


#### Imagen 246 — Página 70 (14.2 KB)

> 📄 **Diagrama/Imagen — Página 70**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `70`
> *(Para ver: abrir PDF en página 70)*


#### Imagen 247 — Página 70 (127.5 KB)

> 📄 **Diagrama/Imagen — Página 70**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `70`
> *(Para ver: abrir PDF en página 70)*


#### Imagen 248 — Página 71 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 71**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `71`
> *(Para ver: abrir PDF en página 71)*


#### Imagen 249 — Página 71 (44.3 KB)

> 📄 **Diagrama/Imagen — Página 71**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `71`
> *(Para ver: abrir PDF en página 71)*


#### Imagen 250 — Página 72 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 72**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `72`
> *(Para ver: abrir PDF en página 72)*


#### Imagen 251 — Página 72 (9.1 KB)

> 📄 **Diagrama/Imagen — Página 72**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `72`
> *(Para ver: abrir PDF en página 72)*


#### Imagen 252 — Página 72 (261.3 KB)

> 📄 **Diagrama/Imagen — Página 72**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `72`
> *(Para ver: abrir PDF en página 72)*


#### Imagen 253 — Página 73 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 73**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `73`
> *(Para ver: abrir PDF en página 73)*


#### Imagen 254 — Página 73 (5.0 KB)

> 📄 **Diagrama/Imagen — Página 73**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `73`
> *(Para ver: abrir PDF en página 73)*


#### Imagen 255 — Página 73 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 73**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `73`
> *(Para ver: abrir PDF en página 73)*


#### Imagen 256 — Página 74 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 74**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `74`
> *(Para ver: abrir PDF en página 74)*


#### Imagen 257 — Página 74 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 74**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `74`
> *(Para ver: abrir PDF en página 74)*


#### Imagen 258 — Página 74 (716.1 KB)

> 📄 **Diagrama/Imagen — Página 74**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `74`
> *(Para ver: abrir PDF en página 74)*


#### Imagen 259 — Página 75 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 75**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `75`
> *(Para ver: abrir PDF en página 75)*


#### Imagen 260 — Página 75 (211.0 KB)

> 📄 **Diagrama/Imagen — Página 75**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `75`
> *(Para ver: abrir PDF en página 75)*


#### Imagen 261 — Página 75 (716.1 KB)

> 📄 **Diagrama/Imagen — Página 75**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `75`
> *(Para ver: abrir PDF en página 75)*


#### Imagen 262 — Página 76 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 76**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `76`
> *(Para ver: abrir PDF en página 76)*


#### Imagen 263 — Página 76 (9.0 KB)

> 📄 **Diagrama/Imagen — Página 76**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `76`
> *(Para ver: abrir PDF en página 76)*


#### Imagen 264 — Página 77 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 77**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `77`
> *(Para ver: abrir PDF en página 77)*


#### Imagen 265 — Página 77 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 77**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `77`
> *(Para ver: abrir PDF en página 77)*


#### Imagen 266 — Página 77 (716.1 KB)

> 📄 **Diagrama/Imagen — Página 77**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `77`
> *(Para ver: abrir PDF en página 77)*


#### Imagen 267 — Página 77 (6.2 KB)

> 📄 **Diagrama/Imagen — Página 77**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `77`
> *(Para ver: abrir PDF en página 77)*


#### Imagen 268 — Página 78 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 78**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `78`
> *(Para ver: abrir PDF en página 78)*


#### Imagen 269 — Página 78 (105.9 KB)

> 📄 **Diagrama/Imagen — Página 78**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `78`
> *(Para ver: abrir PDF en página 78)*


#### Imagen 270 — Página 78 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 78**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `78`
> *(Para ver: abrir PDF en página 78)*


#### Imagen 271 — Página 79 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 79**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `79`
> *(Para ver: abrir PDF en página 79)*


#### Imagen 272 — Página 79 (263.2 KB)

> 📄 **Diagrama/Imagen — Página 79**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `79`
> *(Para ver: abrir PDF en página 79)*


#### Imagen 273 — Página 80 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 80**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `80`
> *(Para ver: abrir PDF en página 80)*


#### Imagen 274 — Página 80 (153.9 KB)

> 📄 **Diagrama/Imagen — Página 80**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `80`
> *(Para ver: abrir PDF en página 80)*


#### Imagen 275 — Página 81 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 81**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `81`
> *(Para ver: abrir PDF en página 81)*


#### Imagen 276 — Página 81 (153.9 KB)

> 📄 **Diagrama/Imagen — Página 81**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `81`
> *(Para ver: abrir PDF en página 81)*


#### Imagen 277 — Página 81 (716.1 KB)

> 📄 **Diagrama/Imagen — Página 81**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `81`
> *(Para ver: abrir PDF en página 81)*


#### Imagen 278 — Página 82 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 82**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `82`
> *(Para ver: abrir PDF en página 82)*


#### Imagen 279 — Página 82 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 82**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `82`
> *(Para ver: abrir PDF en página 82)*


#### Imagen 280 — Página 82 (153.9 KB)

> 📄 **Diagrama/Imagen — Página 82**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `82`
> *(Para ver: abrir PDF en página 82)*


#### Imagen 281 — Página 82 (47.3 KB)

> 📄 **Diagrama/Imagen — Página 82**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `82`
> *(Para ver: abrir PDF en página 82)*


#### Imagen 282 — Página 82 (8.9 KB)

> 📄 **Diagrama/Imagen — Página 82**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `82`
> *(Para ver: abrir PDF en página 82)*


#### Imagen 283 — Página 82 (716.1 KB)

> 📄 **Diagrama/Imagen — Página 82**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `82`
> *(Para ver: abrir PDF en página 82)*


#### Imagen 284 — Página 83 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 83**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `83`
> *(Para ver: abrir PDF en página 83)*


#### Imagen 285 — Página 83 (210.0 KB)

> 📄 **Diagrama/Imagen — Página 83**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `83`
> *(Para ver: abrir PDF en página 83)*


#### Imagen 286 — Página 83 (154.0 KB)

> 📄 **Diagrama/Imagen — Página 83**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `83`
> *(Para ver: abrir PDF en página 83)*


#### Imagen 287 — Página 83 (173.3 KB)

> 📄 **Diagrama/Imagen — Página 83**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `83`
> *(Para ver: abrir PDF en página 83)*


#### Imagen 288 — Página 83 (108.1 KB)

> 📄 **Diagrama/Imagen — Página 83**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `83`
> *(Para ver: abrir PDF en página 83)*


#### Imagen 289 — Página 83 (83.3 KB)

> 📄 **Diagrama/Imagen — Página 83**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `83`
> *(Para ver: abrir PDF en página 83)*


#### Imagen 290 — Página 83 (61.9 KB)

> 📄 **Diagrama/Imagen — Página 83**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `83`
> *(Para ver: abrir PDF en página 83)*


#### Imagen 291 — Página 84 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 84**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `84`
> *(Para ver: abrir PDF en página 84)*


#### Imagen 292 — Página 84 (16.2 KB)

> 📄 **Diagrama/Imagen — Página 84**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `84`
> *(Para ver: abrir PDF en página 84)*


#### Imagen 293 — Página 84 (11.1 KB)

> 📄 **Diagrama/Imagen — Página 84**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `84`
> *(Para ver: abrir PDF en página 84)*


#### Imagen 294 — Página 84 (11.9 KB)

> 📄 **Diagrama/Imagen — Página 84**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `84`
> *(Para ver: abrir PDF en página 84)*


#### Imagen 295 — Página 84 (21.9 KB)

> 📄 **Diagrama/Imagen — Página 84**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `84`
> *(Para ver: abrir PDF en página 84)*


#### Imagen 296 — Página 85 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 85**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `85`
> *(Para ver: abrir PDF en página 85)*


#### Imagen 297 — Página 85 (14.7 KB)

> 📄 **Diagrama/Imagen — Página 85**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `85`
> *(Para ver: abrir PDF en página 85)*


#### Imagen 298 — Página 86 (8.6 KB)

> 📄 **Diagrama/Imagen — Página 86**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `86`
> *(Para ver: abrir PDF en página 86)*


#### Imagen 299 — Página 86 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 86**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `86`
> *(Para ver: abrir PDF en página 86)*


#### Imagen 300 — Página 87 (26.5 KB)

> 📄 **Diagrama/Imagen — Página 87**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `87`
> *(Para ver: abrir PDF en página 87)*


#### Imagen 301 — Página 87 (12.3 KB)

> 📄 **Diagrama/Imagen — Página 87**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `87`
> *(Para ver: abrir PDF en página 87)*


#### Imagen 302 — Página 88 (8.7 KB)

> 📄 **Diagrama/Imagen — Página 88**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `88`
> *(Para ver: abrir PDF en página 88)*


#### Imagen 303 — Página 90 (34.8 KB)

> 📄 **Diagrama/Imagen — Página 90**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `90`
> *(Para ver: abrir PDF en página 90)*


#### Imagen 304 — Página 91 (45.8 KB)

> 📄 **Diagrama/Imagen — Página 91**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `91`
> *(Para ver: abrir PDF en página 91)*


#### Imagen 305 — Página 92 (139.3 KB)

> 📄 **Diagrama/Imagen — Página 92**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `92`
> *(Para ver: abrir PDF en página 92)*


#### Imagen 306 — Página 93 (16.9 KB)

> 📄 **Diagrama/Imagen — Página 93**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `93`
> *(Para ver: abrir PDF en página 93)*


#### Imagen 307 — Página 94 (8.1 KB)

> 📄 **Diagrama/Imagen — Página 94**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `94`
> *(Para ver: abrir PDF en página 94)*


#### Imagen 308 — Página 94 (65.5 KB)

> 📄 **Diagrama/Imagen — Página 94**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `94`
> *(Para ver: abrir PDF en página 94)*


#### Imagen 309 — Página 95 (116.4 KB)

> 📄 **Diagrama/Imagen — Página 95**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `95`
> *(Para ver: abrir PDF en página 95)*


#### Imagen 310 — Página 95 (89.0 KB)

> 📄 **Diagrama/Imagen — Página 95**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `95`
> *(Para ver: abrir PDF en página 95)*


#### Imagen 311 — Página 96 (7.0 KB)

> 📄 **Diagrama/Imagen — Página 96**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `96`
> *(Para ver: abrir PDF en página 96)*


#### Imagen 312 — Página 96 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 96**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `96`
> *(Para ver: abrir PDF en página 96)*


#### Imagen 313 — Página 97 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 97**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `97`
> *(Para ver: abrir PDF en página 97)*


#### Imagen 314 — Página 97 (7.0 KB)

> 📄 **Diagrama/Imagen — Página 97**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `97`
> *(Para ver: abrir PDF en página 97)*


#### Imagen 315 — Página 98 (10.3 KB)

> 📄 **Diagrama/Imagen — Página 98**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `98`
> *(Para ver: abrir PDF en página 98)*


#### Imagen 316 — Página 98 (29.5 KB)

> 📄 **Diagrama/Imagen — Página 98**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `98`
> *(Para ver: abrir PDF en página 98)*


#### Imagen 317 — Página 98 (8.1 KB)

> 📄 **Diagrama/Imagen — Página 98**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `98`
> *(Para ver: abrir PDF en página 98)*


#### Imagen 318 — Página 99 (9.0 KB)

> 📄 **Diagrama/Imagen — Página 99**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `99`
> *(Para ver: abrir PDF en página 99)*


#### Imagen 319 — Página 99 (24.0 KB)

> 📄 **Diagrama/Imagen — Página 99**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `99`
> *(Para ver: abrir PDF en página 99)*


#### Imagen 320 — Página 99 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 99**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `99`
> *(Para ver: abrir PDF en página 99)*


#### Imagen 321 — Página 100 (38.0 KB)

> 📄 **Diagrama/Imagen — Página 100**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `100`
> *(Para ver: abrir PDF en página 100)*


#### Imagen 322 — Página 100 (29.5 KB)

> 📄 **Diagrama/Imagen — Página 100**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `100`
> *(Para ver: abrir PDF en página 100)*


#### Imagen 323 — Página 100 (8.1 KB)

> 📄 **Diagrama/Imagen — Página 100**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `100`
> *(Para ver: abrir PDF en página 100)*


#### Imagen 324 — Página 100 (10.3 KB)

> 📄 **Diagrama/Imagen — Página 100**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `100`
> *(Para ver: abrir PDF en página 100)*


#### Imagen 325 — Página 101 (416.3 KB)

> 📄 **Diagrama/Imagen — Página 101**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `101`
> *(Para ver: abrir PDF en página 101)*


#### Imagen 326 — Página 101 (8.6 KB)

> 📄 **Diagrama/Imagen — Página 101**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `101`
> *(Para ver: abrir PDF en página 101)*


#### Imagen 327 — Página 101 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 101**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `101`
> *(Para ver: abrir PDF en página 101)*


#### Imagen 328 — Página 102 (261.3 KB)

> 📄 **Diagrama/Imagen — Página 102**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `102`
> *(Para ver: abrir PDF en página 102)*


#### Imagen 329 — Página 103 (261.3 KB)

> 📄 **Diagrama/Imagen — Página 103**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `103`
> *(Para ver: abrir PDF en página 103)*


#### Imagen 330 — Página 104 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 104**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `104`
> *(Para ver: abrir PDF en página 104)*


#### Imagen 331 — Página 105 (24.0 KB)

> 📄 **Diagrama/Imagen — Página 105**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `105`
> *(Para ver: abrir PDF en página 105)*


#### Imagen 332 — Página 106 (102.2 KB)

> 📄 **Diagrama/Imagen — Página 106**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `106`
> *(Para ver: abrir PDF en página 106)*


#### Imagen 333 — Página 107 (559.8 KB)

> 📄 **Diagrama/Imagen — Página 107**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `107`
> *(Para ver: abrir PDF en página 107)*


#### Imagen 334 — Página 107 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 107**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `107`
> *(Para ver: abrir PDF en página 107)*


#### Imagen 335 — Página 108 (42.0 KB)

> 📄 **Diagrama/Imagen — Página 108**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `108`
> *(Para ver: abrir PDF en página 108)*


#### Imagen 336 — Página 108 (59.8 KB)

> 📄 **Diagrama/Imagen — Página 108**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `108`
> *(Para ver: abrir PDF en página 108)*


#### Imagen 337 — Página 108 (17.7 KB)

> 📄 **Diagrama/Imagen — Página 108**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `108`
> *(Para ver: abrir PDF en página 108)*


#### Imagen 338 — Página 108 (8.9 KB)

> 📄 **Diagrama/Imagen — Página 108**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `108`
> *(Para ver: abrir PDF en página 108)*


#### Imagen 339 — Página 109 (8.7 KB)

> 📄 **Diagrama/Imagen — Página 109**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `109`
> *(Para ver: abrir PDF en página 109)*


#### Imagen 340 — Página 110 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 110**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `110`
> *(Para ver: abrir PDF en página 110)*


#### Imagen 341 — Página 110 (15.0 KB)

> 📄 **Diagrama/Imagen — Página 110**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `110`
> *(Para ver: abrir PDF en página 110)*


#### Imagen 342 — Página 111 (8.6 KB)

> 📄 **Diagrama/Imagen — Página 111**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `111`
> *(Para ver: abrir PDF en página 111)*


#### Imagen 343 — Página 111 (34.3 KB)

> 📄 **Diagrama/Imagen — Página 111**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `111`
> *(Para ver: abrir PDF en página 111)*


#### Imagen 344 — Página 112 (26.5 KB)

> 📄 **Diagrama/Imagen — Página 112**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `112`
> *(Para ver: abrir PDF en página 112)*


#### Imagen 345 — Página 112 (12.3 KB)

> 📄 **Diagrama/Imagen — Página 112**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `112`
> *(Para ver: abrir PDF en página 112)*


#### Imagen 346 — Página 113 (8.7 KB)

> 📄 **Diagrama/Imagen — Página 113**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `113`
> *(Para ver: abrir PDF en página 113)*


#### Imagen 347 — Página 115 (34.8 KB)

> 📄 **Diagrama/Imagen — Página 115**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `115`
> *(Para ver: abrir PDF en página 115)*


#### Imagen 348 — Página 116 (45.8 KB)

> 📄 **Diagrama/Imagen — Página 116**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `116`
> *(Para ver: abrir PDF en página 116)*


#### Imagen 349 — Página 117 (139.3 KB)

> 📄 **Diagrama/Imagen — Página 117**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `117`
> *(Para ver: abrir PDF en página 117)*


#### Imagen 350 — Página 118 (28.0 KB)

> 📄 **Diagrama/Imagen — Página 118**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `118`
> *(Para ver: abrir PDF en página 118)*


#### Imagen 351 — Página 119 (29.1 KB)

> 📄 **Diagrama/Imagen — Página 119**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `119`
> *(Para ver: abrir PDF en página 119)*


#### Imagen 352 — Página 119 (8.1 KB)

> 📄 **Diagrama/Imagen — Página 119**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `119`
> *(Para ver: abrir PDF en página 119)*


#### Imagen 353 — Página 120 (29.1 KB)

> 📄 **Diagrama/Imagen — Página 120**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `120`
> *(Para ver: abrir PDF en página 120)*


#### Imagen 354 — Página 120 (29.3 KB)

> 📄 **Diagrama/Imagen — Página 120**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `120`
> *(Para ver: abrir PDF en página 120)*


#### Imagen 355 — Página 121 (6.9 KB)

> 📄 **Diagrama/Imagen — Página 121**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `121`
> *(Para ver: abrir PDF en página 121)*


#### Imagen 356 — Página 121 (104.8 KB)

> 📄 **Diagrama/Imagen — Página 121**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `121`
> *(Para ver: abrir PDF en página 121)*


#### Imagen 357 — Página 122 (6.9 KB)

> 📄 **Diagrama/Imagen — Página 122**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `122`
> *(Para ver: abrir PDF en página 122)*


#### Imagen 358 — Página 122 (24.0 KB)

> 📄 **Diagrama/Imagen — Página 122**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `122`
> *(Para ver: abrir PDF en página 122)*


#### Imagen 359 — Página 122 (104.8 KB)

> 📄 **Diagrama/Imagen — Página 122**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `122`
> *(Para ver: abrir PDF en página 122)*


#### Imagen 360 — Página 123 (29.5 KB)

> 📄 **Diagrama/Imagen — Página 123**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `123`
> *(Para ver: abrir PDF en página 123)*


#### Imagen 361 — Página 123 (55.9 KB)

> 📄 **Diagrama/Imagen — Página 123**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `123`
> *(Para ver: abrir PDF en página 123)*


#### Imagen 362 — Página 123 (8.1 KB)

> 📄 **Diagrama/Imagen — Página 123**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `123`
> *(Para ver: abrir PDF en página 123)*


#### Imagen 363 — Página 124 (24.0 KB)

> 📄 **Diagrama/Imagen — Página 124**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `124`
> *(Para ver: abrir PDF en página 124)*


#### Imagen 364 — Página 124 (9.0 KB)

> 📄 **Diagrama/Imagen — Página 124**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `124`
> *(Para ver: abrir PDF en página 124)*


#### Imagen 365 — Página 124 (104.8 KB)

> 📄 **Diagrama/Imagen — Página 124**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `124`
> *(Para ver: abrir PDF en página 124)*


#### Imagen 366 — Página 125 (38.0 KB)

> 📄 **Diagrama/Imagen — Página 125**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `125`
> *(Para ver: abrir PDF en página 125)*


#### Imagen 367 — Página 125 (29.5 KB)

> 📄 **Diagrama/Imagen — Página 125**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `125`
> *(Para ver: abrir PDF en página 125)*


#### Imagen 368 — Página 125 (55.9 KB)

> 📄 **Diagrama/Imagen — Página 125**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `125`
> *(Para ver: abrir PDF en página 125)*


#### Imagen 369 — Página 125 (8.1 KB)

> 📄 **Diagrama/Imagen — Página 125**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `125`
> *(Para ver: abrir PDF en página 125)*


#### Imagen 370 — Página 126 (9.0 KB)

> 📄 **Diagrama/Imagen — Página 126**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `126`
> *(Para ver: abrir PDF en página 126)*


#### Imagen 371 — Página 126 (104.8 KB)

> 📄 **Diagrama/Imagen — Página 126**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `126`
> *(Para ver: abrir PDF en página 126)*


#### Imagen 372 — Página 126 (128.7 KB)

> 📄 **Diagrama/Imagen — Página 126**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `126`
> *(Para ver: abrir PDF en página 126)*


#### Imagen 373 — Página 127 (21.9 KB)

> 📄 **Diagrama/Imagen — Página 127**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `127`
> *(Para ver: abrir PDF en página 127)*


#### Imagen 374 — Página 128 (29.1 KB)

> 📄 **Diagrama/Imagen — Página 128**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `128`
> *(Para ver: abrir PDF en página 128)*


#### Imagen 375 — Página 128 (21.9 KB)

> 📄 **Diagrama/Imagen — Página 128**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `128`
> *(Para ver: abrir PDF en página 128)*


#### Imagen 376 — Página 129 (104.8 KB)

> 📄 **Diagrama/Imagen — Página 129**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `129`
> *(Para ver: abrir PDF en página 129)*


#### Imagen 377 — Página 130 (24.0 KB)

> 📄 **Diagrama/Imagen — Página 130**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `130`
> *(Para ver: abrir PDF en página 130)*


#### Imagen 378 — Página 131 (142.5 KB)

> 📄 **Diagrama/Imagen — Página 131**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `131`
> *(Para ver: abrir PDF en página 131)*


#### Imagen 379 — Página 132 (104.8 KB)

> 📄 **Diagrama/Imagen — Página 132**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `132`
> *(Para ver: abrir PDF en página 132)*


#### Imagen 380 — Página 132 (559.8 KB)

> 📄 **Diagrama/Imagen — Página 132**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `132`
> *(Para ver: abrir PDF en página 132)*


#### Imagen 381 — Página 133 (70.2 KB)

> 📄 **Diagrama/Imagen — Página 133**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `133`
> *(Para ver: abrir PDF en página 133)*


#### Imagen 382 — Página 133 (59.8 KB)

> 📄 **Diagrama/Imagen — Página 133**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `133`
> *(Para ver: abrir PDF en página 133)*


#### Imagen 383 — Página 133 (17.6 KB)

> 📄 **Diagrama/Imagen — Página 133**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `133`
> *(Para ver: abrir PDF en página 133)*


#### Imagen 384 — Página 133 (8.9 KB)

> 📄 **Diagrama/Imagen — Página 133**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `133`
> *(Para ver: abrir PDF en página 133)*


#### Imagen 385 — Página 134 (8.7 KB)

> 📄 **Diagrama/Imagen — Página 134**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `134`
> *(Para ver: abrir PDF en página 134)*


#### Imagen 386 — Página 135 (34.3 KB)

> 📄 **Diagrama/Imagen — Página 135**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `135`
> *(Para ver: abrir PDF en página 135)*


#### Imagen 387 — Página 135 (15.0 KB)

> 📄 **Diagrama/Imagen — Página 135**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `135`
> *(Para ver: abrir PDF en página 135)*


#### Imagen 388 — Página 136 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 136**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `136`
> *(Para ver: abrir PDF en página 136)*


#### Imagen 389 — Página 136 (33.3 KB)

> 📄 **Diagrama/Imagen — Página 136**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `136`
> *(Para ver: abrir PDF en página 136)*


#### Imagen 390 — Página 136 (34.7 KB)

> 📄 **Diagrama/Imagen — Página 136**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `136`
> *(Para ver: abrir PDF en página 136)*


#### Imagen 391 — Página 136 (22.0 KB)

> 📄 **Diagrama/Imagen — Página 136**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `136`
> *(Para ver: abrir PDF en página 136)*


#### Imagen 392 — Página 137 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 137**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `137`
> *(Para ver: abrir PDF en página 137)*


#### Imagen 393 — Página 137 (265.6 KB)

> 📄 **Diagrama/Imagen — Página 137**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `137`
> *(Para ver: abrir PDF en página 137)*


#### Imagen 394 — Página 138 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 138**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `138`
> *(Para ver: abrir PDF en página 138)*


#### Imagen 395 — Página 138 (79.6 KB)

> 📄 **Diagrama/Imagen — Página 138**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `138`
> *(Para ver: abrir PDF en página 138)*


#### Imagen 396 — Página 139 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 139**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `139`
> *(Para ver: abrir PDF en página 139)*


#### Imagen 397 — Página 140 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 140**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `140`
> *(Para ver: abrir PDF en página 140)*


#### Imagen 398 — Página 140 (129.1 KB)

> 📄 **Diagrama/Imagen — Página 140**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `140`
> *(Para ver: abrir PDF en página 140)*


#### Imagen 399 — Página 141 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 141**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `141`
> *(Para ver: abrir PDF en página 141)*


#### Imagen 400 — Página 141 (124.6 KB)

> 📄 **Diagrama/Imagen — Página 141**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `141`
> *(Para ver: abrir PDF en página 141)*


#### Imagen 401 — Página 142 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 142**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `142`
> *(Para ver: abrir PDF en página 142)*


#### Imagen 402 — Página 143 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 143**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `143`
> *(Para ver: abrir PDF en página 143)*


#### Imagen 403 — Página 143 (289.8 KB)

> 📄 **Diagrama/Imagen — Página 143**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `143`
> *(Para ver: abrir PDF en página 143)*


#### Imagen 404 — Página 144 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 144**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `144`
> *(Para ver: abrir PDF en página 144)*


#### Imagen 405 — Página 144 (104.3 KB)

> 📄 **Diagrama/Imagen — Página 144**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `144`
> *(Para ver: abrir PDF en página 144)*


#### Imagen 406 — Página 145 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 145**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `145`
> *(Para ver: abrir PDF en página 145)*


#### Imagen 407 — Página 146 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 146**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `146`
> *(Para ver: abrir PDF en página 146)*


#### Imagen 408 — Página 146 (37.9 KB)

> 📄 **Diagrama/Imagen — Página 146**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `146`
> *(Para ver: abrir PDF en página 146)*


#### Imagen 409 — Página 147 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 147**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `147`
> *(Para ver: abrir PDF en página 147)*


#### Imagen 410 — Página 147 (35.9 KB)

> 📄 **Diagrama/Imagen — Página 147**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `147`
> *(Para ver: abrir PDF en página 147)*


#### Imagen 411 — Página 148 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 148**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `148`
> *(Para ver: abrir PDF en página 148)*


#### Imagen 412 — Página 148 (37.9 KB)

> 📄 **Diagrama/Imagen — Página 148**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `148`
> *(Para ver: abrir PDF en página 148)*


#### Imagen 413 — Página 149 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 149**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `149`
> *(Para ver: abrir PDF en página 149)*


#### Imagen 414 — Página 149 (24.1 KB)

> 📄 **Diagrama/Imagen — Página 149**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `149`
> *(Para ver: abrir PDF en página 149)*


#### Imagen 415 — Página 150 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 150**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `150`
> *(Para ver: abrir PDF en página 150)*


#### Imagen 416 — Página 150 (37.9 KB)

> 📄 **Diagrama/Imagen — Página 150**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `150`
> *(Para ver: abrir PDF en página 150)*


#### Imagen 417 — Página 151 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 151**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `151`
> *(Para ver: abrir PDF en página 151)*


#### Imagen 418 — Página 151 (34.4 KB)

> 📄 **Diagrama/Imagen — Página 151**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `151`
> *(Para ver: abrir PDF en página 151)*


#### Imagen 419 — Página 152 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 152**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `152`
> *(Para ver: abrir PDF en página 152)*


#### Imagen 420 — Página 152 (37.9 KB)

> 📄 **Diagrama/Imagen — Página 152**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `152`
> *(Para ver: abrir PDF en página 152)*


#### Imagen 421 — Página 153 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 153**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `153`
> *(Para ver: abrir PDF en página 153)*


#### Imagen 422 — Página 153 (23.7 KB)

> 📄 **Diagrama/Imagen — Página 153**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `153`
> *(Para ver: abrir PDF en página 153)*


#### Imagen 423 — Página 154 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 154**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `154`
> *(Para ver: abrir PDF en página 154)*


#### Imagen 424 — Página 155 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 155**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `155`
> *(Para ver: abrir PDF en página 155)*


#### Imagen 425 — Página 155 (159.0 KB)

> 📄 **Diagrama/Imagen — Página 155**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `155`
> *(Para ver: abrir PDF en página 155)*


#### Imagen 426 — Página 155 (42.9 KB)

> 📄 **Diagrama/Imagen — Página 155**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `155`
> *(Para ver: abrir PDF en página 155)*


#### Imagen 427 — Página 155 (109.8 KB)

> 📄 **Diagrama/Imagen — Página 155**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `155`
> *(Para ver: abrir PDF en página 155)*


#### Imagen 428 — Página 156 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 156**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `156`
> *(Para ver: abrir PDF en página 156)*


#### Imagen 429 — Página 156 (36.3 KB)

> 📄 **Diagrama/Imagen — Página 156**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `156`
> *(Para ver: abrir PDF en página 156)*


#### Imagen 430 — Página 157 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 157**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `157`
> *(Para ver: abrir PDF en página 157)*


#### Imagen 431 — Página 157 (116.2 KB)

> 📄 **Diagrama/Imagen — Página 157**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `157`
> *(Para ver: abrir PDF en página 157)*


#### Imagen 432 — Página 157 (107.5 KB)

> 📄 **Diagrama/Imagen — Página 157**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `157`
> *(Para ver: abrir PDF en página 157)*


#### Imagen 433 — Página 158 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 158**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `158`
> *(Para ver: abrir PDF en página 158)*


#### Imagen 434 — Página 158 (62.8 KB)

> 📄 **Diagrama/Imagen — Página 158**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `158`
> *(Para ver: abrir PDF en página 158)*


#### Imagen 435 — Página 159 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 159**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `159`
> *(Para ver: abrir PDF en página 159)*


#### Imagen 436 — Página 159 (116.2 KB)

> 📄 **Diagrama/Imagen — Página 159**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `159`
> *(Para ver: abrir PDF en página 159)*


#### Imagen 437 — Página 159 (295.1 KB)

> 📄 **Diagrama/Imagen — Página 159**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `159`
> *(Para ver: abrir PDF en página 159)*


#### Imagen 438 — Página 160 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 160**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `160`
> *(Para ver: abrir PDF en página 160)*


#### Imagen 439 — Página 160 (101.0 KB)

> 📄 **Diagrama/Imagen — Página 160**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `160`
> *(Para ver: abrir PDF en página 160)*


#### Imagen 440 — Página 161 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 161**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `161`
> *(Para ver: abrir PDF en página 161)*


#### Imagen 441 — Página 161 (96.6 KB)

> 📄 **Diagrama/Imagen — Página 161**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `161`
> *(Para ver: abrir PDF en página 161)*


#### Imagen 442 — Página 161 (103.7 KB)

> 📄 **Diagrama/Imagen — Página 161**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `161`
> *(Para ver: abrir PDF en página 161)*


#### Imagen 443 — Página 161 (62.1 KB)

> 📄 **Diagrama/Imagen — Página 161**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `161`
> *(Para ver: abrir PDF en página 161)*


#### Imagen 444 — Página 162 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 162**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `162`
> *(Para ver: abrir PDF en página 162)*


#### Imagen 445 — Página 163 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 163**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `163`
> *(Para ver: abrir PDF en página 163)*


#### Imagen 446 — Página 163 (47.9 KB)

> 📄 **Diagrama/Imagen — Página 163**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `163`
> *(Para ver: abrir PDF en página 163)*


#### Imagen 447 — Página 163 (83.4 KB)

> 📄 **Diagrama/Imagen — Página 163**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `163`
> *(Para ver: abrir PDF en página 163)*


#### Imagen 448 — Página 164 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 164**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `164`
> *(Para ver: abrir PDF en página 164)*


#### Imagen 449 — Página 164 (102.5 KB)

> 📄 **Diagrama/Imagen — Página 164**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `164`
> *(Para ver: abrir PDF en página 164)*


#### Imagen 450 — Página 164 (79.1 KB)

> 📄 **Diagrama/Imagen — Página 164**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `164`
> *(Para ver: abrir PDF en página 164)*


#### Imagen 451 — Página 165 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 165**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `165`
> *(Para ver: abrir PDF en página 165)*


#### Imagen 452 — Página 165 (93.8 KB)

> 📄 **Diagrama/Imagen — Página 165**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `165`
> *(Para ver: abrir PDF en página 165)*


#### Imagen 453 — Página 165 (75.3 KB)

> 📄 **Diagrama/Imagen — Página 165**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `165`
> *(Para ver: abrir PDF en página 165)*


#### Imagen 454 — Página 166 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 166**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `166`
> *(Para ver: abrir PDF en página 166)*


#### Imagen 455 — Página 166 (47.0 KB)

> 📄 **Diagrama/Imagen — Página 166**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `166`
> *(Para ver: abrir PDF en página 166)*


#### Imagen 456 — Página 166 (32.6 KB)

> 📄 **Diagrama/Imagen — Página 166**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `166`
> *(Para ver: abrir PDF en página 166)*


#### Imagen 457 — Página 167 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 167**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `167`
> *(Para ver: abrir PDF en página 167)*


#### Imagen 458 — Página 167 (56.4 KB)

> 📄 **Diagrama/Imagen — Página 167**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `167`
> *(Para ver: abrir PDF en página 167)*


#### Imagen 459 — Página 167 (36.2 KB)

> 📄 **Diagrama/Imagen — Página 167**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `167`
> *(Para ver: abrir PDF en página 167)*


#### Imagen 460 — Página 168 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 168**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `168`
> *(Para ver: abrir PDF en página 168)*


#### Imagen 461 — Página 168 (252.6 KB)

> 📄 **Diagrama/Imagen — Página 168**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `168`
> *(Para ver: abrir PDF en página 168)*


#### Imagen 462 — Página 168 (56.4 KB)

> 📄 **Diagrama/Imagen — Página 168**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `168`
> *(Para ver: abrir PDF en página 168)*


#### Imagen 463 — Página 168 (245.1 KB)

> 📄 **Diagrama/Imagen — Página 168**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `168`
> *(Para ver: abrir PDF en página 168)*


#### Imagen 464 — Página 169 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 169**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `169`
> *(Para ver: abrir PDF en página 169)*


#### Imagen 465 — Página 169 (18.5 KB)

> 📄 **Diagrama/Imagen — Página 169**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `169`
> *(Para ver: abrir PDF en página 169)*


#### Imagen 466 — Página 169 (81.8 KB)

> 📄 **Diagrama/Imagen — Página 169**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `169`
> *(Para ver: abrir PDF en página 169)*


#### Imagen 467 — Página 170 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 170**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `170`
> *(Para ver: abrir PDF en página 170)*


#### Imagen 468 — Página 171 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 171**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `171`
> *(Para ver: abrir PDF en página 171)*


#### Imagen 469 — Página 171 (5.1 KB)

> 📄 **Diagrama/Imagen — Página 171**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `171`
> *(Para ver: abrir PDF en página 171)*


#### Imagen 470 — Página 171 (6.0 KB)

> 📄 **Diagrama/Imagen — Página 171**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `171`
> *(Para ver: abrir PDF en página 171)*


#### Imagen 471 — Página 172 (7.5 KB)

> 📄 **Diagrama/Imagen — Página 172**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `172`
> *(Para ver: abrir PDF en página 172)*


#### Imagen 472 — Página 172 (8.9 KB)

> 📄 **Diagrama/Imagen — Página 172**
> PDF: [`unidad 1 ppt unidas DSI.pdf`](../Diapositivas y Teóricos/unidad 1 ppt unidas DSI.pdf) · Página `172`
> *(Para ver: abrir PDF en página 172)*



---

