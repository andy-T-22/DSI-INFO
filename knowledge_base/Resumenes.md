# Resúmenes

> Seccion del repositorio **DSI INFO** — 3 documentos.
> Archivo principal: `DSI_INFO_Completo.md` | Indice: `INDEX.md`

## Contenido de esta seccion

- Resumen DSI 1er Parcial 3K3
- Resumen DSI Alan (1)
- Resumen para Exámenes - Diseño de Sistemas UTN

---



## Resumen DSI 1er Parcial 3K3

**Categoría:** Resúmenes  

**Archivo:** `Resumen DSI 1er Parcial 3K3.pdf`  

**Tamaño:** 1.05 MB  


### 📄 Contenido de Texto

#### Página 1

Resumen DSI 1er Parcial
“Etapa de Análisis”
 Repaso POO
 Diagramas UML
 Realización CU de Análisis
 Máquina de Estados
 Patrones GRASP M
Repaso POO
Objeto: “Representa un elemento, unidad o entidad individual e identificaOble, ya sea real o abstracta, con un papel
bien definido en el dominio del problema”. Todo objeto tiene un estado, una identidad única y exhibe un
comportamiento bien definido (en su clase).
C
Clase: “Es la definición de un conjunto de objetos que comparten una estructura común y un comportamiento
común”. Representa roles, lugares, cosas, conceptos, eventos, transiciones, etc.
.
Elementos esenciales del Modelo OO:
D
Abstracción:
Denota características clave de un objeto, dando fronteras conceptuales respecto a la perspectiva del observador.
D
Encapsulamiento: ¿Qué se oculta?
Proceso de almacenar en un mismo comportamiento, elementos de una abstracción y su implementación.
A
Modularidad: AC + BA = Independencia de componentes
Propiedad de un sistema descompuesto en un conjunto de módulos cohesivos, débilmente acoplados.
L
Jerarquía: De Clases (Generalización) – De Partes (Agregación/Composición)
Clasificación u ordenación de abstracciones. (Relaciones de asociación son NO jerárquicas).
I
Relaciones entFre clases:
Generalización:
(cid:31)Una clase comparte estructura y/o comportamientos definidos en 1 (herencia simple) o + (herencia múltiple)
clases. Polimorfismo: Operación de un hijo con misma firma que operación padre, redefiniendo la operación
heredada de éste (Varias formas de implementación según clases hijas).
Asociación:
Relación estructural, especifica que los objetos de una clase están conectados con los objetos de otra.
Agregación/Composición (Tipo especial de asociación):
Relación “todo/parte”, donde una clase representa el “todo”, constando de elementos más pequeños (“partes”).
En agregación los elementos viven sin su contenedor (Auto-Rueda), en composición no (Cuerpo-Corazón).
Realización
Relación semántica entre clasificadores, en donde un clasificador especifica un contrato que otro clasificador
garantiza que cumplirá.
Dependencia
Relación semántica entre dos elementos, en la cual un cambio a un elemento (el elemento independiente) puede
afectar a la semántica del otro elemento (elemento dependiente).
Página 1 de 12
Mengo, Martín Este archivo fue descargado de https://filadd.com


#### Página 2

Diagramas UML
¿Por qué unificado?
Ciclo de vida de desarrollo: UML proporciona sintaxis visual para modelar software desde los
requisitos a la implementación.
Dominios de aplicación: UML se ha utilizado para modelar de todo, desde sistemas incorporados en
tiempo real a sistemas de soporte a la toma de decisión.
Lenguajes y plataforma de implementación: UML es neutro tanto en lenguaje como en plataforma.
Procesos de desarrollo: UML puede soportar muchos otros procesos de ingeniería Mde software
además de UP y sus variantes.
Sus propios conceptos internos: UML trata de ser coherente y uniforme en su aplicación de un
pequeño grupo de conceptos internos. O
UML:
1) Bloques de Construcción
C
a) Elementos
Elementos estructurales: son las partes estáticas de un mo.delo, y representan conceptos o cosas materiales.
D
1. Clase.
2. Interfaz: colección de operaciones que especifican un servicio de una clase o componente. Define un
conjunto de operaciones, pero nunca la imDplementación de tales.
3. Colaboración: define una interacción y es una sociedad de roles y otros elementos que colaboran para
proporcionar un comportamiento mayor que la suma de los comportamientos de sus elementos.
A
4. Caso de uso: descripción de un conjunto de secuencias de acciones que ejecuta un sistema y que produce
un resultado observable de interés para un actor particular.
5. Clase activa: es una clase cuyos objetos tienen uno o más procesos o hilos de ejecución. Clase con
L
comportamiento concurrente.
6. Componente: es una parte modular del diseño del sistema que oculta su implementación tras un conjunto
I
de interfaces externas.
F
7. Artefacto: es una parte física y reemplazable de un sistema que contiene información física (“bits”, ej.
código fuente).
(cid:31)8. Nodo: elemento físico que existe en tiempo de ejecución y representa un recurso computacional, que por lo
general tiene algo de memoria y capacidad de procesamiento.
Elementos de comportamiento: son las partes dinámicas de los modelos de UML.
1. Interacción: es un comportamiento que comprende un conjunto de mensajes intercambiados entre un
conjunto de objetos, dentro de un contexto particular, para alcanzar un objetivo específico.
2. Máquina de estados: es un comportamiento que especifica las secuencias de estados por las que pasa un
objeto o una interacción durante su vida en respuesta a eventos, junto con sus reacciones a estos eventos.
3. Actividad: es un comportamiento que especifica la secuencia de pasos que ejecuta un proceso
computacional.
Elementos de agrupación: son las partes organizativas de los modelos UML. Ejemplo:
1. Paquete: es un mecanismo de propósito general para organizar el propio diseño. Es el elemento de
agrupación básico para organizar un modelo UML.
Elementos de anotación: son las partes explicativas de los modelos UML. Son comentarios que se pueden
aplicar para describir, clasificar y hacer observaciones sobre cualquier elemento de un modelo.
Página 2 de 12
Mengo, Martín Este archivo fue descargado de https://filadd.com


#### Página 3

1. Nota: es un símbolo para mostrar restricciones y comentarios junto a un elemento o una colección de
elementos.
b) Relaciones (ya descriptas)
c) Diagramas
Diagrama: es la representación gráfica de un conjunto de elementos, visualizado la mayoría de las veces como
un grafo conexo de nodos (elementos) y arcos (relaciones). Los diagramas se dibujan para visualizar un sistema
desde diferentes perspectivas, de forma que un diagrama es una proyección de un sistema. Un diagrama
puede contener cualquier combinación de elementos y relaciones. Sin embargo, en la práctica siempre surgen
un número de combinaciones habituales, las cuales son consistentes con las cinco vistas más útiles que
comprenden la arquitectura de un sistema. UML se divide en dos tipos de diagramMas:
Diagramas Estructurales: Representan elementos y así componen un sistema o función.
1. Diagrama de clases: Muestra un conjunto de clases, interfaces y colaboración, así como sus relaciones.
O
Tienen atributos, relaciones y comportamientos. Abarcan la vista de diseño estática de un sistema.
2. Diagrama de Estructura Compuesta: Muestra la estructura interna de un clasificador, incluyendo sus puntos
C
de interacción a otras partes del sistema. Estructura interna: implementación específica de un componente.
3. Diagrama de objetos: Caso especial de DC. Muestra un conjunto de objetos y sus relaciones. Representan
.
relaciones estáticas de instancias de clases. Útiles para la compresión de DC. Cubren la vista de diseño estática.
D
4. Diagrama de componentes: Representa la encapsulación de una clase, junto con sus interfaces, puertos y
estructura interna, formada por otros componentes anidados y conectores. Cubren la vista de implementación
D
estática del diseño de un sistema. Más abstracción que un DC.
5. Diagrama de despliegue: Muestra la configuración de nodos de procesamiento (HW) en tiempo de ejecución
y los artefactos que residen en elloAs. Abordan la vista de despliegue estática de una arquitectura.
6. Diagrama de paquetes: Reflejan la organización de paquetes y sus elementos (normalmente DC y DCU).
L
Diagramas de Comportamiento: Representan características conductuales de un sistema o proceso de negocio.
1. Diagrama de actividadIes: Muestra la estructura de un proceso u otra computación como el flujo de control y
datos paso a paso. Cubren la vista dinámica del sistema.
F
2. Diagrama de casos de uso: Captura requisitos de un sistema. Organizan y modelan el comportamiento del
sistema. Tien en actores y relaciones. Cubren la vista de casos de uso estática de un sistema.
(cid:31)
3. Diagrama de estados: muestra una máquina de estados, que consta de estados, transiciones, eventos y
actividades. Muestra la vista dinámica de un objeto en respuesta a dichos eventos.
4. Diagrama de interacción: muestra una interacción, que consta de un conjunto de objetos o roles, incluyendo
los mensajes que pueden ser enviados entre ellos. Cubren la vista dinámica de un sistema.
a. Diagrama de secuencia: Resalta la ordenación temporal de los mensajes. Muestra objetos
como líneas de vida hacia abajo en la página con sus interacciones en el tiempo representadas
como flechas desde la línea de vida origen a la línea de vida destino. Buenos para mostrar cuáles
objetos se comunican con otros objetos y qué mensajes disparan esas comunicaciones.
b. Diagrama de comunicación: Resalta la organización estructural de los objetos o roles que
envían y reciben mensajes. Secuencia de mensajes representada por esquema numérico.
c. Diagrama de Tiempo: mostrar los cambios en el estado, o la condición, de una línea de vida de
una instancia a lo largo del tiempo, de manera lineal.
Página 3 de 12
Mengo, Martín Este archivo fue descargado de https://filadd.com


#### Página 4

d. Diagrama de Descripción de Interacciones: diagrama de actividad en el cual los nodos
representan diagramas de interacción. Útil para mostrar cómo distintos escenarios se combinan.
Pueden incluir más diagramas de interacción dentro.
2) Mecanismos Comunes
Especificaciones, adornos, divisiones comunes, mecanismos de extensibilidad (estereotipos, valores
etiquetados, restricciones).
3) Reglas de UML
 Nombres: Cómo llamar a los elementos, relaciones y diagramas.
 Alcance: El contexto que da un significado específico a un nombre. M
 Visibilidad: Cómo se pueden ver y utilizar esos nombres por otros.
 Integridad: Cómo se relacionan apropiada y consistentemente unos elementos con otros.
 Ejecución: Qué significa ejecutar o simular un modelo dinámico.
O
Vistas UML
CU: Describe el comportamiento del sistema a través de los casos de uso. Aspecto estático: Diagrama
C
de casos de uso. Aspecto dinámico: Diagramas de interacción, de estados y de actividades.
Diseño: Comprende las clases, interfaces y colaboraciones que conforman el vocabulario del problema
.
y la solución. Aspecto estático: Diagramas de clases y objetos. Aspecto dinámico: Diagramas de
D
interacción, de estados y de actividades.
Procesos: Comprende los hilos y procesos que forman los mecanismos de sincronización y
D
concurrencia del sistema. Los aspectos estáticos y dinámicos de esta vista se capturan con los mismos
diagramas que la vista de diseño pero poniendo énfasis en las clases activas.
Implementación: Comprende los comAponentes y archivos que se utilizan para ensamblar y hacer
disponible el sistema físico. Aspecto estático: Diagramas de componentes. Aspecto dinámico:
Diagramas de interacción, de estados y de actividades.
L
Despliegue: Contiene los nodos que conforman la topología de hardware sobre la que se ejecuta el
sistema. Aspecto estático: Diagramas de despliegue. Aspecto dinámico: Diagramas de interacción, de
I
estados y de actividades.
F
Realización CU de Análisis
(cid:31)
Página 4 de 12
Mengo, Martín Este archivo fue descargado de https://filadd.com


#### Página 5

M
O
C
.
D
D
A
L
I
F
(cid:31)Clases de An álisis:
Representa una abstracción de una o varias clases y/o subsistemas del diseño del sistema. Se centra en el tratamiento
de los RF y pospone los RNF. Son evidentes en el contexto del dominio del problema, más “conceptual”.
Su comportamiento se define mediante responsabilidades en un alto nivel y menos formal. No se define mediante una
interfaz en términos de operaciones y de sus firmas.
Define atributos en un alto nivel. Los tipos de los atributos son conceptuales y reconocibles en el dominio del problema.
En el diseño los tipos pertenecen al lenguaje de programación. Participa en relaciones, aunque esas relaciones son más
conceptuales que las de diseño e implementación. Siempre encajan en uno de los tres estereotipos básicos:
Clases de interfaz: se utilizan para modelar la interacción entre el sistema y sus actores. Esta interacción implica a
menudo recibir (y presentar) información y peticiones de (y hacia) los usuarios y los sistemas externos. Representan a
menudo abstracciones de ventanas, formularios, paneles, interfaces de comunicaciones, interfaces de impresoras,
sensores, etc. Deberían asociarse con un al menos un actor y viceversa.
Clases de entidad: se utilizan para modelar información que posee una vida larga y que es a menudo persistente.
Modelan la información y el comportamiento asociado a algún fenómeno o concepto, como una persona, un objeto del
mundo real, o un suceso del mundo real. En la mayoría de los casos, las clases de entidad se derivan directamente de
Página 5 de 12
Mengo, Martín Este archivo fue descargado de https://filadd.com


#### Página 6

una clase de entidad del negocio (o de una clase del dominio). Una diferencia fundamental entre clases de entidad y
clases de entidad de negocio es que las primeras consideran objetos manejados por el sistema. En consecuencia, las
clases de entidad reflejan la información de un modo que beneficia a los desarrolladores al diseñar e implementar el
sistema, incluyendo su soporte de persistencia. Modelan información relevante para el dominio y que dura en el
tiempo, siendo candidatas a ser persistentes mediante bases de datos.
Clases de control: representan coordinación, secuencia, transacciones, y control de otros objetos y se usan con
frecuencia para encapsular el control de un caso de uso en concreto. También se utilizan para representar derivaciones
y cálculos complejos, como la lógica de negocio que no puede asociarse con ninguna clase de entidad concreta. Los
aspectos dinámicos del sistema se modelan con clases de control, debido a que ellas manejan y coordinan las acciones y
los flujos de control principales, y delegan trabajo a otros objetos. Son el nexo entre las Mclases de entidad y de interfaz,
ya que éstas no se relacionan directamente.
Paquete de Análisis:
O
Proporcionan un medio para organizar los artefactos del modelo de análisis en piezas manejables. Puede estar
compuesto de clases de análisis, de realizaciones de casos de uso de análisis y de otros paquetes (recursivamente).
Deberían ser cohesivos (contenidos fuertemente relacionados) y deberían ser débilmente acoplados (mínima
C
dependencia de uno de otros).
Tienen las siguientes características:
.
 Pueden representar una separación de interesDes de análisis.
 Deberían crearse basándose en los requerimientos funcionales y en el dominio del problema.
 Probablemente se convertirán en subsistemas en las 2 capas de app. superiores del modelo de diseño, o se
D
distribuirán entre ellos.
Descripción de la Arquitectura:
A
Contiene una vista de la arquitectura del modelo de análisis, que muestra sus artefactos significativos para la
arquitectura.
L
Artefactos que se consideran SPA:
 La descomposición deIl modelo de análisis en paquetes de análisis y sus dependencias.
 Las clases fundamentales del análisis (entidad, control e interfaz).
F
 Realizaciones de caso de uso que describen cierta funcionalidad importante y crítica.
Realización de CU - Diagrama de Secuencia:
(cid:31)
Colaboración que describe cómo se ejecuta un CU, en términos de la interacción entre objetos de análisis.
 Líneas de Vida: Pueden ser de objetos (boundary, control o entity) o instancias de actores (Ej: Encargado).
Sintaxis: nombre [selector]: Tipo
 Mensajes: Muestran cómo interactúan los objetos.
Sintaxis (definido en diseño): nombreMensaje (parámetros: TipoDatoParámetro)
Tipos: - Síncronos ( ) – Asíncronos ( ) – Creación de Objeto ( )
– Señal ( ) – Destrucción de Objeto ( ) – Llamada CU ( ).
 Notas.
 Fragmentos combinados (loop (“for”), opt (“if”), alt (“else”), etc.). Tienen 1 operador, 1 o + operandos y 0
o + condiciones de protección.
Página 6 de 12
Mengo, Martín Este archivo fue descargado de https://filadd.com


#### Página 7

 Foco de Control (Rectángulo largo en línea de vida): Se produce cuando una línea de vida ejecuta un
mensaje, indicando así que la línea de vida posee el foco de control.
Tips Importantes para DS
 A nivel análisis, los mensajes se modelan sin parámetros ni valores de retorno.
 La instancia de actor sólo se puede relacionar con el objeto de la clase boundary
correspondiente (generalmente una pantalla).
 Mensajes desde un objeto de boundary a un actor: sólo podría suceder en caso que el actor
represente un sistema o un dispositivo de hardware.
 Un objeto de entidad no envía mensajes al objeto de control.
M
 Cuando se trabaja sobre un único objeto, éste se modelará de forma separada a la instancia
que representa el conjunto y/o subconjunto de objetos de la misma clase. Ejemplo:
“:Pedido” y “seleccionado:Pedido”.
 Quien itera es el objeto de control o un objeto de entidad que de O be buscar entre una
colección de objetos asociada. Un objeto de una clase NO busca en objetos de la misma clase
(a menos que exista una asociación reflexiva).
 Cuando se generan salidas impresas se modelan objetosC boundary. Se denominan por lo
general ImpresorXX.
 Cuando existe una agregación a nivel de diagrama de clases, no corresponde que el gestor
.
acceda a la parte de dicha agregación, sino que debe el gestor realizar la petición al todo, y
D
éste tiene la responsabilidad de administrar sus detalles. Se aplica así la correcta asignación
de responsabilidades y la delegación.
D
Modelado de Comportamiento con DME
Máquina de Estados: Especificación de la secuencia de estados por las que pasa un objeto a lo largo de su vida en
A
respuesta a eventos junto con sus respuestas a esos eventos. Toda clase puede tener una sola máquina de
estado de comportamiento.
L
Elementos Básicos
I
Estado: F
Condición o situación en la vida de un objeto durante la cual satisface alguna condición, realiza alguna actividad o
espera algún evento. Representado por: Atributos + Valores Actuales de Esos Atributos. Un objeto permanece en
(cid:31)
un estado durante una cantidad de tiempo finita. Un estado tiene: Nombre, Efectos de Entrada/Salida,
Transiciones Internas, Subestados, Eventos Diferido, Actividades-Do.
ESTADO INICIAL: indica el punto de comienzo por defecto para la máquina de estados o el subestado.
Normalmente, se pasa del pseudoestado inicial al estado “real” de la máquina de estado.
ESTADO FINAL: indica que la ejecución de la máquina de estados o del estado que lo contiene ha finalizado.
Transición:
Relación entre dos estados que indica que un objeto que esté en el primer estado realizará ciertas acciones y
entrará en el segundo estado cuando ocurra un evento especificado y se satisfagan condiciones especificadas.
Una transición tiene: Estado Origen, Evento de Disparo, Condición de Guarda, Efecto, Estado Destino.
Sintaxis: nombreEvento(lista de parámetros opcional)[condición de guarda opcional]/lista de acciones opcional
AutoTransición: Estado origen y estado destino son el mismo. En estos casos, un evento dispara la transición, se
abandona el estado, se ejecuta una acción (si la hay) y se vuelve a entrar en el mismo estado.
Página 7 de 12
Mengo, Martín Este archivo fue descargado de https://filadd.com


#### Página 8

Evento:
Aparición de un estímulo que puede disparar una transición de estado. Puede ser de tipo: Llamada, señal, cambio
o tiempo.
Evento de Llamada: Petición de una operación específica a invocarse en una instancia de la clase de contexto.
Debería tener la misma firma que una operación en la clase de contexto de la máquina de estado. Recibir un
evento de llamada es un activador para que se ejecute la operación.
Estados Compuesto/SubEstado:
Estado Compuesto: Estado con SubEstados. Puede contener subestados concurrentes (ortogonales)
o secuenciales (no ortogonales). M
SubEstado: Estado anidado dentro de otro.
Permiten simplificar transiciones similares desde diferentes estados, agrupándolos en un estado
O
compuesto.
Heredan TODAS las transiciones de los estados en los que están contenidos. Si el estado compuesto
tiene una transición determinada, cada uno de los estados anidaCdos dentro de él también tiene esta
transición.
SubEstados Secuenciales (No Ortogonales): Dado un conjunt.o de estados no ortogonales en un
estado compuesto sencillo, se dice que el objeto estDá en el estado compuesto, y sólo en uno de sus
subestados (o en el estado final) en un momento dado.
Dado un estado compuesto, una transición Ddesde un origen externo puede apuntar al estado
compuesto o a un subestado.
Una transición que salga de un estaAdo compuesto puede tener como origen el propio estado
compuesto o un subestado.
Una máquina de estados no ortogonal anidada puede tener como máximo un subestado inicial y un
L
subestado final.
Estado Historia: I
F
Cuando una transición entra en un estado compuesto, la acción de la máquina de estados anidada
comienza de nuevo en su estado inicial (a menos que la transición se dirija directamente a un
subestado).
(cid:31)
Un estado de historia permite que un estado compuesto que contiene subestados secuenciales
recuerde el último subestado activo antes de la transición que provocó la salida del estado
compuesto. Se representa como un pequeño círculo que contiene el símbolo H.
El pseudoestado de historia superficial puede tener muchas transiciones entrantes, pero solamente
una transición saliente. Si una máquina de estados anidada alcanza un estado final, pierde su historia
almacenada y se comporta como si aún no se hubiera entrado en ella por primera vez.
Nota: Si queremos conocer todos los estados por los que pasa un objeto de una clase, se resuelve a
nivel estructura en el diagrama de clases (Clase CambioEstado)(No afecta al diagrama de máquina de
estados).
Trazabilidad de ME con otros Modelos:
En relación al DC
Los métodos (eventos de llamada) que figuran en la ME, y que provocan los cambios de estado, deben estar
presentes en la definición de la clase. Debe existir un atributo estado o estar modelado mediante otra clase.
Página 8 de 12
Mengo, Martín Este archivo fue descargado de https://filadd.com


#### Página 9

En relación al DCU
Debe existir al menos un CU en relación a cada método que provoca un cambio de estado. Debemos
tener CU que nos permitan administrar todos los estados de la clase.
En relación a realizaciones de CU (DS)
En las realizaciones de CU correspondientes deberán existir mensajes asociados a los métodos que
provocan el cambio de estado.
Patrones GRASP
Son patrones para asignación de responsabilidades a los objetos.
M
La decisión de qué operaciones, dónde colocarlas y cómo deberían interactuar los objetos es muy
importante. Se aplican al elaborar los diagramas de interacción.
Responsabilidad se define en UML como “un contrato u obligación de un
O
clasificador”.
C
.
D
D
A
L
Patrón Experto en Información
Problema: ¿Cuál es el prIincipio fundamental en virtud del cual se asignan las responsabilidades en el
diseño orientadoF a objetos?
Solución: Asignar una responsabilidad al experto en información: la clase que cuenta con la
(cid:31)información n ecesaria para cumplir con la responsabilidad.
Así NO:
Así Sí:
Página 9 de 12
Mengo, Martín Este archivo fue descargado de https://filadd.com


#### Página 10

M
Patrón Creador:
Problema: ¿Quién debería ser el responsable de crear una nueva instancOia de alguna clase?
Solución: Asignar a la clase B la responsabilidad de crear una instancia de la clase A en uno de los
siguientes casos:
C
 B agrega los objetos de A.
 B contiene los objetos de A. .
 B registra las instancias de los objetos de A. D
 B utiliza específicamente los objetos de A.
 B tiene los datos de inicialización que serán transmitidos a A cuando sea creado (así B es un
D
experto respecto de la creación de A).
Así NO:
A
L
I
F
(cid:31)
Así Sí:
Página 10 de 12
Mengo, Martín Este archivo fue descargado de https://filadd.com


#### Página 11

M
O
Patrón Controlador:
C
Problema: ¿Quién debería encargarse de atender un evento del sistema/de un CU?
Solución: Un manejador artificial de todos los eventos del sistema de un CU, generalmente
denominado “Manejador <Nombre de CU> (controlador de C . U).
D
Patrón Bajo Acoplamiento:
Problema: ¿Cómo dar soporte a una dependencia escasa y a un aumento de reutilización?
D
Alto acoplamiento implica: Cambios de las clases afines ocasionan cambios locales, difíciles de entender de
manera aislada y de reutilizar porque se requiere la presencia de las clases de las que depende.
A
Solución: Asignar una responsabilidad para mantener bajo el acoplamiento.
Así NO: (Para método mostrarDatosCategoría())(Genera dependencias entre gestor y categoría y sueldo).
L
I
F
(cid:31)
Así Sí:
Página 11 de 12
Mengo, Martín Este archivo fue descargado de https://filadd.com


#### Página 12

M
O
C
Patrón Alta Cohesión: .
D
Problema: ¿Cómo mantener la complejidad dentro de límites manejables?
Baja cohesión implica: Son difíciles de entender, reutilizar, conservar y son delicadas (las afectan
constantemente los cambios). D
Solución: Asignar una responsabilidad de modo que la cohesión siga siendo alta.
A
Beneficios:
 Se incrementa la claridad y facilita la comprensión del diseño.
L
 Se simplifican el mantenimiento y las mejoras.
 Se soporta a menudo bajo acoplamiento.
I
 El grano fino de funcionalidad altamente relacionada incrementa la reutilización porque una clase
cohesivaF se puede utilizar para un propósito muy específico.
(cid:31)
Página 12 de 12
Mengo, Martín Este archivo fue descargado de https://filadd.com


### 🖼️ Imágenes Extraídas (10 imágenes)

#### Imagen 1 — Página 4 (50.7 KB)

> 📄 **Diagrama/Imagen — Página 4**
> PDF: [`Resumen DSI 1er Parcial 3K3.pdf`](../Resúmenes/Resumen DSI 1er Parcial 3K3.pdf) · Página `4`
> *(Para ver: abrir PDF en página 4)*


#### Imagen 2 — Página 5 (36.6 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`Resumen DSI 1er Parcial 3K3.pdf`](../Resúmenes/Resumen DSI 1er Parcial 3K3.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 3 — Página 5 (43.7 KB)

> 📄 **Diagrama/Imagen — Página 5**
> PDF: [`Resumen DSI 1er Parcial 3K3.pdf`](../Resúmenes/Resumen DSI 1er Parcial 3K3.pdf) · Página `5`
> *(Para ver: abrir PDF en página 5)*


#### Imagen 4 — Página 9 (52.2 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`Resumen DSI 1er Parcial 3K3.pdf`](../Resúmenes/Resumen DSI 1er Parcial 3K3.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 5 — Página 9 (24.2 KB)

> 📄 **Diagrama/Imagen — Página 9**
> PDF: [`Resumen DSI 1er Parcial 3K3.pdf`](../Resúmenes/Resumen DSI 1er Parcial 3K3.pdf) · Página `9`
> *(Para ver: abrir PDF en página 9)*


#### Imagen 6 — Página 10 (34.3 KB)

> 📄 **Diagrama/Imagen — Página 10**
> PDF: [`Resumen DSI 1er Parcial 3K3.pdf`](../Resúmenes/Resumen DSI 1er Parcial 3K3.pdf) · Página `10`
> *(Para ver: abrir PDF en página 10)*


#### Imagen 7 — Página 10 (49.7 KB)

> 📄 **Diagrama/Imagen — Página 10**
> PDF: [`Resumen DSI 1er Parcial 3K3.pdf`](../Resúmenes/Resumen DSI 1er Parcial 3K3.pdf) · Página `10`
> *(Para ver: abrir PDF en página 10)*


#### Imagen 8 — Página 11 (93.0 KB)

> 📄 **Diagrama/Imagen — Página 11**
> PDF: [`Resumen DSI 1er Parcial 3K3.pdf`](../Resúmenes/Resumen DSI 1er Parcial 3K3.pdf) · Página `11`
> *(Para ver: abrir PDF en página 11)*


#### Imagen 9 — Página 11 (63.3 KB)

> 📄 **Diagrama/Imagen — Página 11**
> PDF: [`Resumen DSI 1er Parcial 3K3.pdf`](../Resúmenes/Resumen DSI 1er Parcial 3K3.pdf) · Página `11`
> *(Para ver: abrir PDF en página 11)*


#### Imagen 10 — Página 12 (84.4 KB)

> 📄 **Diagrama/Imagen — Página 12**
> PDF: [`Resumen DSI 1er Parcial 3K3.pdf`](../Resúmenes/Resumen DSI 1er Parcial 3K3.pdf) · Página `12`
> *(Para ver: abrir PDF en página 12)*



---


## Resumen DSI Alan (1)

**Categoría:** Resúmenes  

**Archivo:** `Resumen DSI Alan (1).pdf`  

**Tamaño:** 0.1 MB  


### 📄 Contenido de Texto

#### Página 1

Proceso Unificado de Desarrollo (PUD)
El PUD es guía que marca los lineamientos generales para transformar los requerimientos
del cliente en un sistema de información funcional, sin importar la implementación, la
tecnología o aspectos particulares.
El PUD se basa en los casos de uso (que son fragmentos de funcionalidad del sistema que
brindan un resultado de valor para el actor) y en la arquitectura que es como se deberán
llevar a cabo esos casos de uso. Es iterativo e incremental mediante las fases (inicio,
elaboración, construcción y transición) donde en cada una de estas se aplican todos los
workflow (requerimientos, análisis, diseño, implementación y prueba) en diferente
proporción dependiendo de la fase.
● Los workflow: Son actividades secuenciales y lógicas realizadas por los
trabajadores que dan como resultado de valor un artefacto.
● Las vistas: Son una proyección o perspectiva de la arquitectura del sistema, su
función es brindar una forma de observar al sistema desde un ángulo en particular.
● Asociación con modelos: Cada workflow está asociado a con uno o mas modelos.
Los modelos a su vez cuentan con herramientas que son diagramas que ofrece UML
para representar la realidad (para construir los artefactos del workflow).
Clasificación de Diagramas UML
Tenemos 2 tipos de diagramas:
1. Modelan estructura
● Modelan objetos: * Diagrama de objetos.
● Modelan clases: * Diagrama de clases.
○ Diagrama de componentes.
○ Diagrama de paquetes.
○ Diagrama de artefactos.
○ Diagrama de secuencia.
○ Diagrama de estructura compuesta.
2. Modelan comportamiento
● Modelan clases: * Diagrama de máquina de estados.
○ Diagrama de CU.
○ Diagrama de actividad.
● Modelan interacciones: * Diagrama de secuencia.
○ Diagrama de comunicaciones.
○ Diagrama de timing.
○ Diagrama de descripción de interacción.


#### Página 2

Workflow de Requerimientos
Se centra en el dominio del problema, usa lenguaje natural, ofrece una vista externa del
sistema. Tiene como entrada las necesidades del cliente y tiene como salida (artefactos):
● a) MODELO DE CASOS DE USO: Para eso implementa como herramienta al
diagrama de casos de uso (que muestra la interacción entre los actores y las
funcionalidades). Como la vista gráfica no es suficiente también implementa
descripciones de casos de uso y descripciones de actores. Es la salida más
importante.
● b) Modelo de dominio: Este modelo implementa como herramienta al diagrama de
clases pero enfocándose estrictamente en el negocio (las clases de entidad).
● c) Descripción de interfaces de usuario.
● d) Descripción de la arquitectura.
Workflow de Análisis
Establece un puente entre “el mundo del usuario, dominio del problema” y “el mundo del
desarrollador, dominio de la solución”. Utiliza lenguaje técnico, ofrece una vista interna del
sistema, nos permite realizar una especificación más precisa de los requerimientos.
Tiene como entrada los modelos del workflow de requerimientos y tiene como salida:
a) Las clases de análisis
Son clases de fabricación pura, son las abstracciones lógicas del sistema, pertenecen al
dominio de la solución:
● Clases de entidad: Representan la información y el comportamiento de conceptos o
fenómenos del negocio. Suelen derivarse de las clases de entidad del negocio.
Tienen una vida larga y son persistentes.
● Clases de control: Representan la coordinación, secuencia, transacciones y control
de otros objetos. Encapsulan la lógica de un caso de uso en concreto. Además
representan cálculos complejos y derivaciones que no pueden asignarse a una clase
de entidad en específico. Funcionan de nexo entre las clases de Entidad y las clases
boundary, ya que estas no pueden comunicarse directamente. No son persistente,
su vida acaba cuando finaliza la ejecución del flujo.
● Clases boundary: Representan la interacción entre los actores y el sistema. Sirven
de medio para que el actor pueda ingresar información y ver los resultados y el
sistema pueda recibir la información y presentar los resultados.
Otras salidas del workflow:
● b) Las realizaciones de caso de uso: Implementa como herramienta el diagrama
de casos de uso o el diagrama de comunicaciones. Muestran el paso a paso de
como las instancias de las clases de análisis colaboran e intercambian mensajes
para llevar a cabo el flujo de un caso de uso. Es la salida más importante.


#### Página 3

● c) Paquete de análisis: Agrupaciones de clases de análisis que están fuertemente
relacionadas.
● d) Descripción de la arquitectura.
Dominios del Desarrollo
Dominio del Problema
Es el entorno o espacio del negocio del cliente donde existen las necesidades, desafíos y
procesos propios de la organización. En este dominio no se aborda nada de la lógica interna
ni técnica del sistema de información, sino que se enfoca estrictamente en el negocio.
● Objetivo: Permite obtener "qué" se necesita resolver.
● Relación con el PUD: Está directamente vinculado con el Workflow de
Requerimientos.
Dominio de la Solución
Es el espacio técnico y de software donde las necesidades, desafíos y procesos del negocio
identificados en el dominio del problema se transforman en estructuras lógicas, algoritmos y
componentes de software para construir el sistema de información.
● Objetivo: Su enfoque principal es el "cómo" se va a implementar y construir técnica
y físicamente el software.
● Relación con el PUD: Está directamente vinculado con los Workflows de Diseño,
Implementación y Prueba.
Visibilidad entre Objetos
La visibilidad es la capacidad de un objeto de ver a otro para que pueda enviarle un
mensaje, en la estructura del sistema, esto determina el nivel de acoplamiento entre las
clases. Existen dos tipos de visibilidad:
● Visibilidad de atributos (permanente): Esta se da cuando un objeto tiene una
referencia directa y duradera hacia otro objeto a través de un atributo de su clase,
estas son a largo plazo (mientras el objeto exista, tendrá acceso al otro objeto
vinculado). Estas se modelan a través de las relaciones de asociación, agregación o
composición.
● Visibilidad de parámetros (momentánea): Se produce cuando un objeto recibe la
referencia de otro objeto únicamente durante la ejecución de un método,
generalmente como un argumento o parámetro. En este caso se modelan gracias a
las dependencias, proporcionan un menor acoplamiento ya que la conexión es
“transitoria” (dura lo que dura la ejecución de ese método).
Patrones y Responsabilidades


#### Página 4

Un patrón es una solución genérica y reutilizable para un problema común dentro de cierto
contexto determinado, es una plantilla o guía de cómo resolver un problema que puede
darse en muchas situaciones.
En sí dentro del “WORKFLOW” de análisis los implementamos para plantear a qué clase
(Boundary, Controller o Entity) le corresponden ciertas responsabilidades y además me
propician que el modelo resultante tenga alta cohesión y bajo acoplamiento.
● Responsabilidades del HACER: Se refieren a las acciones que un
objeto debe ser capaz de ejecutar (son sus métodos), en sí puede ser
algo que haga el mismo, iniciar una acción en otros objetos, controlar y
coordinar actividades en otros objetos y/o crear otros objetos.
● Responsabilidades del CONOCER: Se refiere a la información que un
objeto debe de mantener y ser capaz de proporcionar (atributos y/o
relaciones con otros objetos).
Patrones GRASP
Son un conjunto de directrices fundamentales para asignar responsabilidades a clases y
objetos, estos patrones se aplican intensamente durante el Workflow de Análisis para actuar
las clases necesarias y distribuir las responsabilidades para cumplir con los requerimientos
funcionales. Se tienen en cuenta 5:
● Patrón Experto: Establece que se debe de asignar una responsabilidad a la clase
que cuenta con la información necesaria para llevarla a cabo.
● Patrón Creador: Determina qué clase debe crear una nueva instancia de otra. Una
clase A debe crear una instancia de otra clase B si: Tiene o agrega a B, tiene los
datos de inicialización de B.
● Patrón Controlador: Asigna la responsabilidad de manejar los eventos del sistema
a una clase que representa el escenario de caso de uso. Es una Fabricación Pura
que coordina la lógica, en sí asegura que los procesos del dominio sean manejados
por la capa del dominio y no por la de interfaz.
● Patrón Bajo Acoplamiento: Se busca asignar responsabilidades para mantener un
bajo acoplamiento, mientras más independientes sean las clases se reduce el
impacto de los cambios y son más reutilizables.
● Patrón Alta Cohesión: Se busca asignar una responsabilidad a la clase de manera
que tenga un número relativamente pequeño de operaciones con funcionalidad
relacionada y poco trabajo por hacer. Por esto colabora con otros objetos para
compartir esfuerzo si la tarea es grande.


> ℹ️ No se encontraron imágenes significativas en este PDF.



---


## Resumen para Exámenes - Diseño de Sistemas UTN

**Categoría:** Resúmenes  

**Archivo:** `Resumen para Exámenes - Diseño de Sistemas UTN.pdf`  

**Tamaño:** 0.16 MB  


### 📄 Contenido de Texto

#### Página 1

Resumen: Modelo de Análisis en Diseño
de Sistemas (UTN)
El flujo de trabajo (Workflow) de Análisis toma como entrada el Modelo de Requerimientos
(Casos de Uso, Modelo de Dominio, Glosario) y produce como salida el Modelo de Análisis.
Este modelo es el "cómo" lógico y se divide en dos grandes vistas:
● Vista Estática: Representada por el Diagrama de Clases de Análisis. Nos muestra la
estructura.
● Vista Dinámica: Representada por los Diagramas de Secuencia, Comunicación y
Máquina de Estados. Nos muestra cómo los objetos colaboran a lo largo del tiempo.
1. Las Clases del Análisis (El modelo ECB)
Para separar responsabilidades, en la cátedra utilizamos tres tipos de clases (estereotipos):
Estereotipo Descripción Ejemplo
Entidad (Entity) Modela la información que Festival, Pedido, Factura
es persistente (sobrevive a
la ejecución del sistema).
Límite (Boundary) Modela la interfaz entre el PantallaAdministrarFestival
sistema y el ambiente (el
actor). Maneja entradas y
salidas.
Control (Control) Clase de Fabricación Pura. GestorFestival
Coordina y delega la
ejecución de un caso de
uso.


#### Tabla 1 — Página 1

|  |  |  |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  | Estereotipo |  |  | Descripción |  |  | Ejemplo |  |
|  |  |  |  |  |  |  |  |  |
| Entidad (Entity) |  |  | Modela la información que
es persistente (sobrevive a
la ejecución del sistema). |  |  | Festival, Pedido, Factura |  |  |
|  |  |  |  |  |  |  |  |  |
| Límite (Boundary) |  |  |  | Modela la interfaz entre el |  | PantallaAdministrarFestival |  |  |
|  |  |  |  | sistema y el ambiente (el |  |  |  |  |
|  |  |  |  | actor). Maneja entradas y |  |  |  |  |
|  |  |  |  | salidas. |  |  |  |  |
|  |  |  |  |  |  |  |  |  |
| Control (Control) |  |  | Clase de Fabricación Pura.
Coordina y delega la
ejecución de un caso de
uso. |  |  | GestorFestival |  |  |


#### Página 2

2. Asignación de Responsabilidades: Patrones
GRASP
GRASP (General Responsibility Assignment Software Patterns) nos da reglas de oro para
decidir qué objeto hace qué.
● Experto en Información: "Lo hace quien lo conoce". Asigna la responsabilidad a la clase
que tiene los datos necesarios para cumplirla.
● Creador: Asigna a la clase B la responsabilidad de crear una instancia de A si: B
contiene a A, B agrega a A, o B tiene los datos de inicialización de A.
● Controlador: Maneja los eventos del sistema. Evita que la capa de presentación tenga
lógica de negocio.
● Bajo Acoplamiento & Alta Cohesión: Principios evaluativos. Clases que hacen una
sola cosa bien y dependen de la menor cantidad de clases posibles.
3. Análisis Profundo de Diagramas UML
A. Diagrama de Secuencia (Vista Dinámica)
Muestra la interacción de un conjunto de objetos a lo largo del tiempo para realizar un Caso de
Uso.
● Actor: Inicia la interacción enviando un mensaje síncrono a la Boundary.
● Línea de vida: La línea punteada vertical que representa la existencia del objeto.
● Foco de control (Cilindro): Indica cuándo el objeto está ejecutando una acción.
● Mensaje Síncrono (Flecha llena): El emisor espera la respuesta antes de seguir.
● Fragmentos (Alt, Loop, Opt): Controlan el flujo. Loop (iterar), Alt (If-Else), Opt (If
simple).
● Creación (new()): Apunta directamente a la "caja" del objeto nuevo.
B. Diagrama de Máquina de Estados (Vista Dinámica)
Especifica la secuencia de estados por los que pasa un objeto durante su vida en respuesta a
eventos. SOLO se usa en clases de Entidad cuyo comportamiento varía radicalmente según su
estado.
● Estado: Atributo + Valor en un momento del tiempo.
● Transición: El paso de un estado a otro.
● Evento Disparador: El método o caso de uso que provoca el cambio de estado.
● Condición de Control (Guarda): Condición booleana [Condición].


#### Página 3

4. Explicaciones Ampliadas: Conceptos Difíciles
Visibilidad (Por Atributo vs. Por Parámetro)
Tipo de Visibilidad Significado Representación UML
Por Atributo El objeto origen guarda una Asociación o Agregación
referencia permanente al
destino.
Por Parámetro El origen solo conoce al Dependencia (flecha
destino durante la ejecución punteada)
de un método.
Modificación Masiva de Objetos (El "Loop" en Secuencia)
Paso a paso lógico del Gestor al modificar muchos objetos:
1. Solicita el dato a la pantalla.
2. Inicia un fragmento Loop para recorrer la colección de objetos.
3. Envía un método de consulta (ej. esTuMarca()) (Patrón Experto).
4. Si responde True (fragmento Opt o Alt), el Gestor llama al método de actualización de la
entidad.
5. Reglas de Oro y Relaciones Clave
● Regla de Capas Estricta: Actor ➔ Boundary ➔ Control ➔ Entity. Ninguna se puede saltar
ni ir en desorden.
● Regla del Experto: El Gestor no calcula por su cuenta, delega el cálculo a la Entidad
que tiene los datos.
● Regla de Creación en Cascada: El "Todo" crea a sus "Partes" (Creador).


#### Tabla 1 — Página 3

|  |  |  |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  | Tipo de Visibilidad |  |  | Significado |  |  | Representación UML |  |
|  |  |  |  |  |  |  |  |  |
| Por Atributo |  |  | El objeto origen guarda una
referencia permanente al
destino. |  |  | Asociación o Agregación |  |  |
|  |  |  |  |  |  |  |  |  |
| Por Parámetro |  |  |  | El origen solo conoce al |  | Dependencia (flecha
punteada) |  |  |
|  |  |  |  | destino durante la ejecución |  |  |  |  |
|  |  |  |  | de un método. |  |  |  |  |
|  |  |  |  |  |  |  |  |  |


#### Tabla 2 — Página 3

| Dependencia (flecha |
| --- |
| punteada) |


#### Página 4

6. Errores Típicos que Cuestan Puntos
● Resolver reglas de negocio en la capa de presentación: Poner a la pantalla
(Boundary) a sumar precios o validar lógicas.
● El "Gestor Dios": Hacer que el Controlador (Gestor) haga todos los cálculos dejando a
las Entidades como meras estructuras de datos.
● Flecha de creación mal dibujada: Hacer que un mensaje de creación (new()) impacte
en la línea de vida en vez de en la caja principal del objeto.
● Máquinas de estado innecesarias: Hacerle estados a clases que son simples
diccionarios o descriptores de datos sin comportamiento dinámico.
7. Posibles Preguntas de Parcial / Final
¿Por qué el Controlador delega la creación de un detalle a la
cabecera?
Para mantener el bajo acoplamiento. Según el patrón Creador de GRASP, la cabecera contiene
a los detalles, por lo que es la "Experta" en crearlos. Si el Gestor lo hiciera, se acoplaría a las
partes internas de la cabecera.
¿Qué indica que una clase requiere una Máquina de Estados?
Cuando los objetos tienen un comportamiento que depende de su estado. Es decir, cuando la
respuesta a un mismo evento varía según los valores actuales de sus atributos.
8. Mini Resumen Final (Cheat Sheet)
* Workflow: Requerimientos ➔ Análisis ➔ Diseño ➔ Implementación.
* Clases ECB: Límite (Pantalla) ➔ Control (Gestor) ➔ Entidad (Dominio).
* GRASP:
- Experto: Delega al que tiene los atributos.
- Creador: El "Todo" crea a la "Parte".
- Controlador: Gestor que protege al dominio de la pantalla.
* Secuencia: Lee temporalmente. Flecha llena = sincrónico. Línea de vida = objeto vivo.
* Consistencia: ¡Método mandado en Secuencia = Método anotado en el Diagrama de
Clases!


#### Tabla 1 — Página 4

| * Workflow: Requerimientos ➔ Análisis ➔ Diseño ➔ Implementación. |
| --- |
| * Clases ECB: Límite (Pantalla) ➔ Control (Gestor) ➔ Entidad (Dominio). |
| * GRASP: |
| - Experto: Delega al que tiene los atributos. |
| - Creador: El "Todo" crea a la "Parte". |
| - Controlador: Gestor que protege al dominio de la pantalla. |
| * Secuencia: Lee temporalmente. Flecha llena = sincrónico. Línea de vida = objeto vivo. |
| * Consistencia: ¡Método mandado en Secuencia = Método anotado en el Diagrama de |
| Clases! |


> ℹ️ No se encontraron imágenes significativas en este PDF.



---
