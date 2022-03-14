# Resumen Analisis de Sistemas Administrativos

## Sistemas

Un **sistema** es un *conjunto de partes interrelacionadas* que cuentan con **mecanismos** que lo definen, apuntan a un **objetivo** en comun, y tienen una **estructura** que define las relaciones entre los componentes tanto *interna* como *externa.* Todo este sistema interactua en un *entorno o ambiente* que lo condiciona. Este sistema permite obtener un resultado superior a la mera suma de sus partes.

## Modelos de desarrollo de sistemas

![Modelo](https://raw.githubusercontent.com/Axtris/Uni/main/Res%C3%BAmenes/images/Resumen%20ASA/Modelo.png)

## Premisas basicas de la metodologia

- **Trabajo en equipo:** permite tener diferentes perspectivas para contemplar todas las posibilidades del sistema y su alcance.
- **Implementacion** del sistema
- **Modularidad:** Son todos los componentes que integran a los sistemas. Es la division de tareas dentro de un sistema, es decir, el conjunto de modulos que componen el sistema mismo.
- **Factorizacion progresiva:** Se basa en la especificacion de cada componente de un modulo, a fin de poder definir la funcion y los datos que buscamos cumplan.

## Criterios para seleccionar por donde empezar

- **Modulo critico:** es el modulo sobre el cual *se relaciona la organización y da existencia de la misma.* **No se refiere** al modulo que contiene el problema, si no que es aquel donde se tiene la parte principal de la organizacion.  
- **Problema:** es la situación que genera la necesidad de una solucion
- **Oportunidad:** frente a una necesidad se busca un desarrollo/modulo/sistema especifico que la satisfaga.
- **Volumen:** Capacidad de manejo de datos del modulo
- **Complejidad:** Se refiere a la dificultad de desarrollo y proceso de un modulo en particular.
- **Costo beneficio:** qué tan rentable o eficiente es el modulo que estoy desarrollando para la organización.
- **Relaciones funcionales:** En un punto de vista tecnico, busca **analizar las dependencias del modulo,** para poder *encontrar las relaciones entre los mismos y ver con cual empezar.* De esta manera, conozco la estructura de los modulos, sus dependencias y relaciones, y me permite saber qué modulo sería prioridad, dado que de éste surgen los datos para los modulos subsiguientes.
- **Preferencia de la direccion:** Es la decision de quien dirige la organizacion, en base al analisis realizado por este organo, que puede o no coincidir con el criterio del administrador.

# Estudio Preliminar

## Actores que intervienen en el proceso

- **Usuario:** Puede asumir diferentes roles. Estos son:

    - **Dueño del sistema:** Titular, gerente general, presidente.
    - **Responsable ejecutivo:** Nivel gerencial
    - **Operador:**
    - **Auditor:** Interno o externo
    - **Beneficiario:** Tereros o destinatarios de las salidas.

Cree tener una necesidad o problema y la transmite al *analista.*
- **Analista:** Profesional de sistemas, diseñador, profesional de administración con conocimiento de sistemas. Toma nota de las necesidades del usuario.
- **Programador:** Técnicos en el desarrollo de sistemas, programadores. Desarrolla una solucion en base a los datos del analista, destinada al usuario.

Dentro del proceso, cada parte puede tener una **interpretación** de las necesidades del usuario, que dificulta la realizacion de una solución satisfactoria. Para eliminar dicha interpretación, se utilizan ciertas **herrramientas de precisión** que determina los lineamientos de manera precisa.

### Herramientas a utilizar

- **Entrevistas**
- **Cuestionario**
- **Pedido de informes**
- **Observacion directa**
- **Consultas interdisciplinarias**
- **Documentacion**
- **Sistematizar la información**

#### Entrevistas

En este paso, hay que preparar la entrevista usando una **guia de entrevista** para *definir el objetivo de la entrevista.* Durante la misma, corresponde definir:

- El **lugar** para hacerla, donde permita a las partes desarrollar una entrevista efectiva, por lo que se busca que sea en el lugar de trabajo, pero no en el puesto de trabajo;
- El **horario,** en lo posible que sea durante el horario de trabajo;
- La **duración,** que no va a ser reducido, pero tampoco tiene que consumir mucho tiempo;
- Luego, correspondera saber si va a ser comodo o necesario **anotar, grabar o filmar,** ya sea porque es una entrevista inicial o porque el entrevistado se pueda sentir incomodo, y se dificulte la toma de información;
- Y la **cantidad** de preguntas, para obtener la mayor cantidad de datos por parte de los entrevistados y que no sea agobiante para los mismos.
- Luego de esto, correspondera hacer un **resumen de la entrevista,** para recapitular lo dicho en el proceso, y tener la opcion de hacer una posterior entrevista para asentar los datos recabados y confirmar o corregir la informacion.

Hay distintos tipos de entrevistas:

- **Segun la cantidad de personas:** individual para poder integrar a la persona al desarrollo de la solucion, o grupal para intercambiar puntos de vista y datos.
- **Segun la informacion a obtener:** Inicial para tomar conocimiento del problema, de recoleccion de datos, y de seguimiento.
- **Segun la funcion del entrevistado:** nivel directivo, ejecutivo u operativo.

Se considera que es una herramienta muy costosa por el tiempo que insume de todos los participantes. Por otro lado, nos permite involucrar a la persona en la solucion de la necesidad o problema.

#### Cuestionarios

Primero, hay que **elaborar el cuestionario** y **definir el objetivo a lograr,** para poder armar el cuestionario en funcion de lo que buscamos conocer. Luego, se debe **coordinar el lugar o sitio web** para tener disponible el cuestionario para su desarrollo, coordinar un **horario de comienzo** y **asignar un tiempo para responder.** Por ultimo, se hace el **tabulado,** para poder conocer la cantidad de respuestas que se realizaron, y en base a eso obtener datos cuantitativos de las necesidades de la organizacion. Estas encuestas **no reemplazan a las entrevistas,** dado que su profundidad es menor y bastante mas acortada a cierto rango de preguntas realizadas, pero son de utilidad cuando es necesario obtener respuestas de una cantidad numerosa de participantes.

#### Pedido de informes

Nos permite **tomar contacto con otros profesionales asesores** para poder consultar acerca de ciertas dudas e informacion. Primero, se **redacta la carta de presentacion y se elabora el pedido de la informacion necesaria,** para luego, cuando recibamos la respuesta, poder **analizar la informacion recibida.** Luego, en caso de existir dudas nuevas o aclaratorias, podemos **pedir una entrevista** para mayor profundidad.

Es una solicitud escrita dirigida a un profesional o especialista, donde se piden precisiones y detalles para tomar decisiones relacionadas con el diseño del sistema. La respuesta resulta muy laboriosa para el profesional, pero permite reducir las interpretaciones. Es una herramienta muy costosa por el tiempo que se insume elaborar, responder y analizar dicha respuesta.

#### Observacion directa

Tenemos que **planificar como hacer la observacion** y que **objetivos** tenemos de dicha observacion. Se debe **anunciar la tarea a realizar** para evitar problemas, y nos permite obtener datos empiricos de la problematica y el manejo de la organizacion en dicho modulo. En esta tarea, debemos asumir el rol de **observador pasivo**, donde no emitimos ninguna opinion, interferencia ni recomendaciones para no alterar la informacion. Es recomendable **anotar comentarios y sugerencias** por parte del observado, ya que es quien hace la tarea y conoce o encuentra que problemas son los mas importantes. Ademas, se prefiere **recopilar documentacion**. Al finalizar, debemos realizar un **informe detallado** de lo observado.

Se desarrolla en el puesto de trabajo de las personas que realizan dichas tareas, observando y tomando nota de la forma en que se realizan los procedimientos, uso de documentacion y archivo de las mismas, las condiciones de trabajo y de los archivos, etc.

#### Consultas interdisciplinarias

Se realizan reuniones con diferentes profesionales de distintas materias para intercambiar informacion segun cada competencia, incluyendo tambien quienes realizan las tareas en el lugar. Primero, se debe invitar a los participantes y definir objetivos y alcances. Durante la reunion, conviene coordinarla y tomar nota. Y por ultimo, en base a lo dicho realizar un informe de la reunion.

#### Documentacion

Es una herramienta que involucra a todas las anteriores. Durante cada una de las herramientas, se solicita documentacion, incluyendo estatutos, reglamentos, organigramas, balances, etc.

#### Sistematizar la informacion

Es una forma de tener informacion disponible. Si el volumen de informacion es muy grande, tenerla organizada en carpetas y archivos permite tener todo disponible. De manera mas comoda, se puede alojar toda la informacion sistematizada en la nube para poder tener acceso desde diversos dispositivos y en cualquier lugar, y los usuarios pueden alojar dicha informacion en cada seccion, pudiendo hacer mas sencilla la documentacion.

## Documentos

- Antes de comenzar el Estudio Preliminar: contrato con profesional o consultor.
- Final del Estudio Preliminar: Informe final del Estudio
- Posterior: Requerimiento, presupuestos de proveedores, evaluacion de presupuestos.

### Contenido minimo del Informe Final del Estudio Preliminar

- Diagnostico: en que situacion se encuentra
- Objetivos: a donde tiene que llegar
- Alternativas de solucion

### Diagnostico

En este punto del informe, el analista detalla la situacion en la que se encuentra la organizacion respecto del o los sistemas objeto del estudio segun el alcance dado a su tarea. Es una descripcion objetiva que estara fundamentada en las herramientas utilizadas durante el relevamiento, para evitar en mayor medida la interpretacion. Permite que cada sector tenga una vision profesional del todo.

### Objetivos

Deben ser:

- **Claros**
- **Precisos**
- **Factibles** o realizables
- Alcanzables dentro de un **presupuesto de recursos**.
- Dentro de un **estudio de factibiilidad limitado,** es decir, que tienen que ser realizables en un periodo de tiempo y con los recursos estipulados.
- **Verificables.**

Adicionalmente, en los sistemas se agrega el **crecimiento modular,** que consiste en que, al agregar un nuevo modulo, los cambios que realice en los otros modulos debe ser inexistente o insignificante.

### Alternativas de solucion

Para el cliente conviene que le digamos aquellas **soluciones a las que puede acceder.** Estas se pueden clasificar segun:

- Sin TICs.
- Con TICs

    - Sistema *enlatado:* Son aquellos sistemas diseñados para una solucion y se puede adquirir distintas herramientas segun las necesidades requeridas
    - Sistema *a medida:* Se hace el analisis, el desarrollo y la implementacion para la organizacion que se trata

        - Desarrollo propio: La organizacion desarrolla el sistema
        - Desarrollo de terceros: Se contrata dicho desarrollo

### Anexos

Es frecuente que se entreguen junto con el informe final, donde **se detalla la informacion obtenida durante el relevamiento** que pueda ser usada por la organizacion en sus decisiones. Puede ser equipamiento, sistemas operativos, capacidades, aplicaciones, etc.

### Requerimiento

Es el documento por el cual la organizacion expresa lo que esta pidiendo, y la importancia que tiene es que permite a los proveedores cotizar el mismo servicio o necesidad. Dicho requerimiento tiene que tener 6 grandes rubros:

- **Normas legales:** Se hace referencia a las normas legales que deben tenerse en cuenta en el desarrollo del sistema, y que afecten directa o indirectamente a la organizacion. Estas incluyen a las normas legales nacionales, provinciales y municipales, resoluciones de los organismos de control, y las normas referidas a la actividad y/o tipo de organizacion.
- **Normas tecnicas:** Hace referencia al conjunto de normas de tipo tecnico que deben aplicarse a la solucion de cada sistema en particular. Se incluyen aquellas normas generadas por procedimientos tecnicos o por la misma costumbre. La misma organizacion puede tener determinada necesidad de informacion que respondera a este punto.
- **Entradas:** Son aquellas necesidades previsibles de ingreso de informacion al sistema. Comprende todos los elementos que pueden generar informacion, tales como el teclado, la pantalla, el scanner, microfono, etc. Se refiere a todos los metodos de entrada que tenga el sistema para poder importar informacion.
- **Salidas:** Incluye todas las necesidades previsibles de salida de informacion del sistema. Estamos hablando de todo lo que permite exportar la informacion del sistema para los usuarios.
- **Controles:** Trata de los procesos de control que se solicitan en las diversas etapas del procesamiento de informacion. Para esto, tanto el profesional de administracion como el profesional de sistemas permitira diseñar procedimientos que cumplan con la tecnica de desarrollo y que permitan ejecutarlos reduciendo al maximo la posibilidad de error. Gran parte de los controles van a estar vinculados a las entradas de informacion. Otra parte se refiere a los procedimientos que verifiquen la consistencia y congruencia de la informacion almacenada.
- **Seguridad:** Es una parte crucial del sistema, por lo que se definen dichas condiciones al principio. Se pueden ennumerar el control de acceso, el respaldo y recupero de la informacion, encriptado de informacion, forma y lugar de procesamiento, y actualmente consideramos la nube como paradigma.

### Presupuesto

Cada potencial proveedor recibio el requerimiento de la organizacion, el cual responde a los objetivos planteados en el informe final del estudio preliminar. Su presupuesto debe responder tal requerimiento para que la organizacion pueda comparar adecuadamente todos los que reciba. Los contenidos a pedir al proveedor son:

- **Descripcion:** Debe responder al requerimiento, que considere los objetivos propuestos, incluya un detalle de los resultados esperados y mencionar las formas de procesamiento propuestas.
- **Recursos afectados:** Se debe detallar el equipamiento existente y necesario, el tiempo, tanto en el cronograma como el control de avance, los recursos economicos y financieros, es decir, importes y certificaciones, y el personal. En este ultimo, se debe considerar el personal de la empresa afectado directa o indirectamente al proyecto, las personas que han de intervenir en el proyecto pertenecientes al grupo de analisis, y la relacion funcional entre dichas personas que van a intervenir en el proyecto.
- **Propuesta economica y financiera:** Va a incluir el importe total y detalle de las formas de pago.
- **Clausulas generales:**

    - Cotizacion de precios por etapas, segun porcentaje de avance y fecha prevista de pago;
    - Forma de ajuste del precio, tanto indices de ajustes, indice base, forma de obtener el indice;
    - Intereses por mora, incluyendo la tasa de interes y forma de calculo.
    - Se debera indicar por cuanto tiempo mantendra la oferta.

El presupuesto de cada proveedor debe responder rigurosamente al detalle del requerimiento. Compararlos vuelve a ser tarea de profesionales, para poder evaluar si se ha cumplido con dicha condicion. Diversos procedimientos permitiran realizar la evaluacion de tal forma que pueda establecerse un orden de prioridades que los responsables de la organizacion tomen la decision final.

### Cronograma segun las etapas de la metodologia

Nos permite conocer el tiempo que nos llevaria cada etapa de la metodologia. Se prevee cuanto puede costar cada parte, aunque luego puede variar con la realidad a medida que se vaya cumpliendo dichas etapas. Pueden existir diferentes etapas superpuestas, dado que a medida que se va recibiendo informacion y progresos en una etapa, se puede trabajar en algun aspecto de la etapa posterior.

Para el analista, conviene presupuestar y conocer la duracion de cada etapa vista segun el modelo. Pero, a efectos de poder transmitir la evolucion a quien contrata los servicios, correspondera realizar un *cronograma diferente,* donde se muestre en que parte del proceso se encuentra el sistema, y que es lo que, a grandes rasgos, se estuvo trabajando. A modo de ejemplo, se pueden detallar como etapas los *datos fijos, las operaciones, los reportes, y los controles.*

# Analisis

Nos permite relevar toda la informacion necesaria que permita evaluar el sistema actual y conocer sus requerimientos. Se pormenoriza hasta el ultimo detalle profundizando la tarea del estudio preliminar:

- Recolectar informacion del sistema actual.
- Realizar un diagnostico de la situacion actual.
- Proponer mejoras.
- Revisar el presupuesto necesario para llevarlo a cabo.

## Objetivos

- Evaluar el sistema existente
- Obtener informacion detallada acerca del sistema objeto del estudio
- Identificar los elementos e interrelaciones del sistema.

## Tareas

- Identificar el flujo fisico y de informacion
- Relevar en detalle de estructuras, funciones, tareas, flujos, procedimientos, metodos, formularios, volumenes, costos, etc.
- Obtener opiniones de clientes
- Identificar y evaluar los requerimientos
- Verificar restricciones internas y externas que reglan el sistema
- Verificar la informacion recogida por la realidad
- Analizar y evaluar la informacion recogida.

## Herramientas

Son las mismas herramientas que se usan en el estudio preliminar, pero profundizando su empleo, aplicando el criterio de factorizacion progresiva, llegando hasta el ultimo detalle de cada componente.

## Documentacion

- Carpetas de relevamiento
- Organigramas
- Informe sobre evaluacion del sistema actual
- Diagramas funcionales
- Diagramas generales de sistemas.

## Participantes

 Principalmente el analista de sistemas con la activa participacion de los usuarios.

## Sobre esta etapa

La extension y profunidad del relevamiento debe ser limitada para no *ahogarse* con informacion inutil y correr el riesgo de ser excesivamente influido por las caracteristicas presentes del sistema.

# Diseño general

En esta etapa debemos lograr tener una vision general del sistema o modulo objeto de estudio y de su relacion con el resto de los modulos. Al diseñar el nuevo sistema, nuevamente se aplicara el criterio de factorizacion.

## Objetivos

- Desarrollar propuestas alternativas que satisfagan los requerimientos de la organizacion
- Definir salidas del sistema propuesto y el esquema general del proceso
- Identificar los requerimientos y restricciones del sistema
- Segmentar el sistema en sub-sistemas

## Tareas

- Determinar las salidas de informacion
- Definir los archivos, entradas y proceso de los datos
- Especificar los medios de procesamiento
- Determinar necesidades de personal
- Realizar los estudios de factibilidad
- Diseñar el nuevo flujo de informacion
- Crecimiento modular
- Elaborar el programa de trabajo detallado
- Planificar la implementacion del proyecto
- Proponer el diseño funcional
- Fijar los criterios de control y de seguridad

## Herramientas a utilizar

Se tratara de plasmar en algunas herramientas graficas el concepto del sistema y su interrelacion con los demas modulos.

- **Interdependencia modular o sectorial:** Toda cosa es un sistema o componente de un sistema. Lo que nos permite esta herramienta es entender como se relacionan los diferentes modulos entre si, que partes los componen y como actuan en otros modulos cuando se modifican ciertos datos.
- **Mapa de procesos:** Es un mapa conceptual en el cual vamos haciendo un recorrido por los diversos procesos que componen un proyecto y los presentamos de la misma forma en que los vera relacionados el usuario en su menu de opciones. Se comienza a partir de un menu principal; luego se divide en un menu donde se cargan datos fijos, tales como datos de clientes, un menu auxiliar para poder cargar datos de comprobantes, tipos de responsables, y secciones de la empresa; un menu de operaciones, para cargar operaciones transitorias y definitivas; ademas de diferentes procesos necesarios segun los requerimientos de la organizacion.
- **Diagrama de sistema \(entrada/salida):** A los efectos de graficar las entradas y salidas de un programa, es conveniente el uso de diagramas especiales que tienen por objetivo poner de relieve las tablas utilizadas en el mismo y su modo de apertura. Nos conviene usar una que nos permita visualizar rapidamente un proceso y sus datos. Las figuras describen su funcion:

    - Rectangulo: se pone la descripcion del proceso, con una division donde en la parte inferior se escribe el nombre del proceso, el cual debe ser el mismo que usamos en el mapa de procesos.
    - Rectangulo redondeado: expresa la terminal que permite la entrada y salida de datos
    - Figura de salida: dibujado como un cuadrado rasgado, nos indica la salida del proceso usando un formato de reporte.
    - Datos almacenados: muestran los datos que entran al proceso y los que salen, los cuales surgen de las tablas o archivos del sistema, y su almacenamiento en disco o recursos similares.
    - Flecha de entrada o salida: indican el flujo de los datos desde y hacia el proceso.

## Caracteristicas del diseño general

### Documentacion

- Propuesta general del nuevo sistema con justificacion costo/beneficio
- Flujograma general y diseño de salidas, archivos, entradas y esquemas del proceso

### Participantes

Principalmente el Jefe de Proyecto y Gerencia, con activa participacion de usuarios directos y analista de sistemas.

## Los datos en los Sistemas

### Jerarquia de datos

![Jerarquia de datos](https://raw.githubusercontent.com/Axtris/Uni/main/Res%C3%BAmenes/images/Resumen%20ASA/Jerarquia_Datos.png)

- Bit: es la minima porcion de informacion que puede manejar un equipamiento, correspondiente a un digito binario \(cero o uno), que puede determinarse como un valor booleano. Es el espacio necesario para almacenar un valor binario en una memoria de ordenador.
- Byte: es un conjunto de bits. Con un byte se pueden representar caracteres, tales como letras, numeros, signos, etc. Es la unidad de informacion de base utilizada en computacion y en telecomunicaciones, que equivale a un conjunto ordenado de bits. Se pueden representar hasta 256 valores diferentes.
- Campo - Variable: es un conjunto de bytes que permiten almacenar informacion. Se usa dicho concepto en los registros de una tabla, y el de variable para la memoria de la computadora. Desde el punto de vista logico, un campo permite almacenar un atributo de un sujeto.
- Registro: es un conjunto de campos que almacena la informacion de una fila de la tabla. Desde el punto de vista logico, permitira almacenar el conjunto de datos de un sujeto. Es el conjunto de atributos de un sujeto determinado en un modulo o sistema.
- Archivo - Tabla: es un conjunto de registros. Es considerado como el conjunto de sujetos de un modulo o sistema. Toda la informacion que se procesa dentro del modulo o sistema se encuentra agrupada en tablas o archivos.
- Base de datos: es un conjunto de tablas o archivos relacionados entre si. Se considera que es un sistema de datos relacionados con una redundancia minima de informacion almacenada. Permite almacenar los datos y luego acceder a los mismos de forma rapida y estructurada. Puede agrupar toda la informacion de un modulo o incluir a todos los modulos de la organizacion. Mantiene relaciones funcionales entre los datos de tal manera de asegurar la integridad referencial de los mismos.
- Almacen de datos: es una coleccion de datos orientada a un determinado ambito, integrado, no volatil y variable en el tiempo, que ayuda a la toma de decisiones en la entidad en la que se utiliza. Se usa para realizar informes y analisis de datos. Se trata de un expediente completo de una organizacion, mas alla de la informacion transaccional y operacional, almacenado en una base de datos diseñada para favorecer el analisis y la divulgacion eficiente de datos.

### Tipos de archivos o tablas segun la informacion almacenada

- Maestros: Contienen informacion mas o menos permanente referida a los datos que constituyen la base de un sistema de informacion, tales como datos fijos de empleados y clientes, o tablas de sueldos basicos.
- Auxiliares: Se encuentran presentes en todos los procesos administrativos, que se usan especialmente para facilitar el empleo de determinados datos que se pueden codificar en forma simple. Se usa para codificar la situacion de los contribuyentes, los tipos de documentos, etc.
- Operaciones: Son archivos o tablas que contienen el conjunto de informacion detallada de un sistema. Pueden usarse para actualizar los datos contenidos en archivos maestros de un sistema.  
- Temporales: Se generan por razones tecnicas u operativas, y pueden ser borradas luego de haber cumplido su proposito. Pueden denominarse tambien como tablas transitorias o borradores.
- De control: Se usan para el control de procesos o para conservar datos necesarios a todos los procesos que pueden ejecutarse en un sistema. Tales como los datos de la ultima emision del libro diario, el ultimo numero de cliente, datos para resumenes de cuenta. Por lo general suelen ser archivos muy pequeños.

# Diseño detallado

En la etapa de desarrollo se debe traducir el diseño conceptual en terminos que puedan ser operativos y expresados a traves de un programa de computadora. Se buscara llegar al mayor detalle posible para su posterior programacion.

## objetivos
Especificar y diseñar con el maximo grado de detalle cada uno de los subsistemas identificados en la fase anterior.

## Tareas

Se basa principalmente en especificar y diseñar todas las tareas anteriormente vistas, especialmente las de documentacion y capacitacion

## Herramientas a utilizar

Se tratara de usar todas las herramientas disponibles, algunas sumamente tecnicas, que permitan eliminar las interpretaciones y documentar para la etapa de programacion.

- **Descripcion de tablas, archivos y bases de datos:** Para cada una de las tablas o archivos del modulo, haremos la descripcion indicando:

    - Nombre del archivo o tabla
    - Clave principal de acceso
    - Otras claves o modos de acceso
    - Descripcion general del conjunto de su contenido
    - Nombre del o los registros
    - Descripcion narrada de un registro y su contenido

- **Diagrama de Entidad/Relacion:** Presenta las relaciones existentes en una base de datos entre las tablas y como se establecen a traves de campos de dichas tablas.
- **Diccionario:** El diccionario de datos es un listado organizado de todos los datos pertinentes al sistema, con definiciones precisas y rigurosas para que tanto el usuario como el analista tengan un entendimiento comun de todas las entradas, salidas, componentes de almacenes y calculos intermedios. Sin un diccionario formal que defina el significado de los terminos, no se puede esperar precision. Este lo crea el analista durante el desarrollo del modelo del sistema, pero el usuario debe ser capaz de leerlo y entenderlo para poder verificar el modelo. Junto al diccionario de datos aparece el diccionario de procesos, que contiene las caracteristicas logicas de los sitios donde se almacenan los datos del sistema. Tambien identifica los procesos donde se emplean los datos y los sitios donde se necesita el acceso inmediato a la informacion; se desarrolla durante el analisis de flujo de datos y auxilia a los analistas que participan en la determinacion de los requerimientos del sistema, su contenido tambien se emplea durante el diseño.
- **Definicion de registros:** Para cada uno de los archivos o tablas dentro del modulo, se debe realizar una descripcion detallada de cada uno de los campos que contendra:

    - Nombre del registro
    - Para cada campo:

        - Orden de cada campo
        - Nombre del campo
        - Tipo de campo
        - Posiciones que ocupa o longitud
        - Cantidad de decimales si es numerico
        - Descripcion de su contenido y restricciones

    - Tipos de campos mas usados:

        - Numericos
        - Caracter o alfanumerico
        - Alfabetico
        - Fecha
        - Logico o booleano
        - Memo o texto

- **Herramientas para la logica de los procesos:** Existen herramientas que se pueden usar para definir claramente cada situacion.

    - **Tablas de decision:** Permitira definir con toda precision las acciones a realizar asi como las condiciones que deben contemplarse. Se divide en una tabla de cuatro cuadrantes, en donde los cuadrantes izquierdos describen las definiciones de las condiciones y las acciones, y en los cuadrantes derechos estaran los valores de dichas condiciones y acciones. Admiten una cantidad limitada de condiciones y una cantidad grande de acciones. La solucion la definimos en el cuadrante inferior derecho.

        - Primero, intentamos separar las condiciones de las acciones. Para esto, tenemos que hacer definiciones que se veran reflejadas en el diccionario para poder dar una solucion precisa, eliminando interpretaciones.
        - Luego, plasmamos las condiciones, y determinamos el valor de las condiciones segun la cantidad de opciones de cada condicion y sus alternativas.
        - Por ultimo, asignamos un valor a cada accion segun la combinacion de cada condicion.
        - En caso de existir combinaciones que, al cambiar la ultima condicion, el valor de las acciones es igual, se considera una indiferencia o redundancia
        - Ademas, se pueden presentar incongruencias en donde los valores de dos condiciones no tengan sentido en la vida real, pero se toman en cuenta en caso de que exista una varicion en la definicion. A fines practicos las incongruencias no expresan un problema, dado que son situaciones que no se van a dar en principio.

          | Herramienta | Tablas de decision |
          | -- | -- |
          | Verificacion de la logica | Muy buena |
          | Representa toda la estructura logica | Moderada: solo las acciones por condiciones |
          | Facilidad de uso | Pobre |
          | Verificacion por el usuario | Pobre |
          | Conversion a programa | Muy buena |
          | Cambios y modificaciones | Pobre |

    - **Arboles de decision:** Es una herramienta que permite definir la logica mediante un grafico o un esquema de tablas. Utilizaremos el grafico porque se asimila a un mapa conceptual y resultara mas facil de entender cuando se le proponga a un usuario.

    | Herramienta | Arboles de decision |
    | -- | -- |
    | Verificacion de la logica | Muy buena |
    | Representa toda la estructura logica | Muy buena: solo las acciones por condiciones |
    | Facilidad de uso | Muy buena |
    | Verificacion por el usuario | Buena |
    | Conversion a programa | Pobre |
    | Cambios y modificaciones | Moderada |

    - **Diagramas de flujo:** Permite definir la logica mediante un conjunto de graficos, usados tecnicamente por todo el ambito del desarrollo de sistemas. Se usan en los casos en los que el equipo debe acordar e interpretar algun aspecto del problema que tiene cierto grado de complejidad.

        - Tiene una entrada al inicio, que indica que viene de un programa anterior.
        - El rombo se usa para marcar la *condicion.*
        - El rectangulo indica las *acciones* a realizar.
        - Los valores de las condiciones se detallan en las uniones.
        - Contrario al arbol de decision, el diagrama de flujo tiene que tener una salida, indicada con un cuadrado con forma de flecha

    | Herramienta | Diagrama de flujo |
    | -- | -- |
    | Verificacion de la logica | Muy buena |
    | Representa toda la estructura logica | Muy buena |
    | Facilidad de uso | Pobre |
    | Verificacion por el usuario | Buena |
    | Conversion a programa | Muy buena |
    | Cambios y modificaciones | Moderada |

    - **Lenguaje estructurado:** Permite definir la logica mediante un lenguaje natural. Intenta narrar, en un lenguaje que mantiene algunas reglas de los lenguajes de computacion, y se aproxima al lenguaje comun del usuario para que pueda entenderlo.

    Una de las estructuras tipicas es la que se forma de la siguente manera:

    > si *condicion* entonces *accion*
    >
    >     sino *accion2*
    >
    > finsi

    | Herramienta | Lenguaje estructurado |
    | Verificacion de la logica | Buena |
    | Representa toda la estructura logica | Muy buena |
    | Facilidad de uso | Buena |
    | Verificacion por el usuario | Pobre |
    | Conversion a programa | Muy buena |
    | Cambios y modificaciones | Buena |

## Documentacion

Diseños de entradas, archivos, salidas; tablas de decision; diagramas de flujo de procesamiento; diagramas de logica en bloque.

## Participantes

Queda a cargo del analista de sistemas con alguna participacion del usuario y colaboracion de programadores.

# Construccion

Se trata de la programacion o codificacion en un lenguaje determinado. Se desarrollan los procedimientos y/o programas de computacion que satisfagan las especificaciones definidas en la fase anterior.

## Objetivos

Desarrollar y realizar la puesta a punto de los programas de computacion de acuerdo a lo especificado en la fase anterior, y elaborar las normas, instrucciones y formularios correspondientes a los procedimientos administrativos

## Tareas

- Desarrollo de logica de los programas
- Codificar
- Elaborar datos de prueba
- Preparar datos, archivos y resultados esperados
- Realizar prueba de sistema
- Documentar, definir metodos de archivo
- Elaborar normas de procedimiento
- Diseñar y probar los formularios y registros.

## Herramientas a utilizar

- Tecnicas de programacion
- Diagramacion logica
- Tecnicas de documentacion
- Tecnicas de diseño de formularios
- Tecnicas de diseño, organizacion y estructuracion de archivos
- Tecnicas de diseño de registros manuales
- Normas de emision de informes

## Documentacion

- Programas en lenguaje
- Diagrama de logica en detalle
- Programa ejecutables
- Documentacion de la prueba
- Carpeta de formularios, registros e informes
- Manual de normas y procedimientos
- Manual de metodos

Los participantes son los programadores, con alguna participacion reducida por parte de los usuarios. Es la etapa que demanda mayor numero de recursos humanos y tiempo de proyecto.

# Seguridad en los sistemas de informacion

Veremos la seguridad como un **conjunto de medidas** o **mecanismos** que tienen por objetivo **proteger los recursos o activos informaticos,** y conducen a la elaboracion de un **plan de seguridad.** Antes que nada, *es inconcebible en terminos de coste economico proteger, monitorizar, auditar y actualizar en tiempo real un sistema informatico.* No existe el 100% de seguridad en ningun orden.

Dentro de las PyMEs, debemos desarrollar nuestro plan considerando que las amenazas han cumplido su accion y nos propondremos como objetivos:

- Asegurar la continuidad de trabajo en todos los sistemas
- Limitar las consecuencias de una amenaza que se concreta
- Recuperar la capacidad de procesamiento en el menor tiempo y al menor costo.

Por lo tanto, queremos estar en condiciones de *enfrentar las amenazas, reducir las debilidades, acrecentar las fortalezas, distinguir las oportunidades, y limitar las consecuencias.*

## Seguridad FODA - Modulo 1

Al ver la seguridad como un **conjunto de medidas,** tenemos que establecer dichos mecanismos en tres grandes grupos:

- Preventivas
- Detectivas
- Correctivas

Hay tres aspectos a **proteger** en los sistemas administrativos:

- Confidencialidad: previene la divulgacion de informacion a personas o sistemas no autorizados. Requiere que la informacion sea accesible unicamente por las entidades autorizadas.
- Integridad: busca mantener a los datos libres de modificaciones no autorizadas. Incluye a todos los recursos informaticos.
- Disponibilidad: es la caracteristica, cualidad o condicion de la informacion de encontrarse a disposicion de quienes deben acceder a ella.

Cuando hablamos de **recursos informaticos,** nos referimos a todo lo que hace que el sistema funcione:

- Hardware: sistema fisico
- Software: sistema logico o programas
- Instalaciones: edificios y sus instalaciones, provision de energia, redes informaticas.
- Informacion: es el activo mas importante de los sistemas de informacion. Son las bases de datos.
- Personas: es el activo mas importante de la organizacion. Debe extremarse la seguridad para protegerlas.

Para estudiar la seguridad en una organizacion, vamos a utilizar el analisis FODA que surga de dicho ente.

- Primero, corresponde conocer las **amenazas** del ente, tanto no intencionales como intencionales. La diferencia entre una y otra es el ejercicio de la voluntad por parte de las personas, hecho que igual involucra un responsable, pero no un culpable.

    - Dentro de las no intencionales, tenemos las amenazas de la naturaleza; las fallas del sistema; y los errores y omisiones provocados por las personas
    - Las amenazas intencionales comprenden el perjuicio con motivacion economica; daño intencional sin motivacion economica; y la invasion a la privacidad.  

Se pueden clasificar en internas o externas segun las comete; si son ataques pasivos o activos segun como se perciban; si se interrumpe un servicio, un recurso, se modifique un recurso o se introduzcan elementos extraños o malwares.

- Luego, tenemos que saber que **debilidades** tiene la organizacion.

    - Primero, tenemos el desconocimiento de los problemas de seguridad por parte de la organizacion
    - Luego, tenemos la inadecuada designacion de responsables a cargo de la seguridad en informatica
    - Podemos contemplar tambien la falta de un plan de seguridad
    - Ademas, puede faltar una auditoria especifica para sistemas de informacion, o dicha auditoria es inadecuada
    - Existe la falta de un plan frente a contingencias
    - Una mala seleccion o capacitacion del personal
    - Errores en el analisis y diseño
    - Programacion y mantenimiento realizados sin normas precisas de trabajo
    - Falta de control sobre los procesos y operacion de los sistemas
    - Mala documentacion

- En cuanto a los aspectos positivos, podemos empezar por las **fortalezas** de la organizacion. Se puede decir que son la contraparte de las debilidades descriptas anteriormente.
- Por ultimo, tenemos que conocer las **oportunidades.** No se deben dejar pasar cursos de capacitacion, las nuevas tecnicas de procesamiento, novedades en equipamiento, instalaciones y nuevos elementos tecnicos, actualizaciones de sistemas operativos, lenguajes o software que mejoren la seguridad. Corresponde aprovechar todas las oportunidades que se nos presentan.

El estudio FODA es una **foto** de la situacion de la organizacion en un momento especifico. Luego, correspondera actuar en funcion del analisis previamente hecho.

Las consecuencias de que se concreten las amenazas nos impiden procesar normalmente. Esto genera que no se pueda procesar en el sistema, existan perdidas o modificaciones de archivos o registros, generen fallas o destruccion de equipos e instalaciones, y se altere la informacion o los resultados de los procesos. Otra consecuencia tiene que ver con la imagen de la organizacion, que ocurre cuando existen accesos indebidos, se usan los recursos informaticos indebidamente, se divulgue la informacion que maneja la organizacion, exista desconfianza interna y externa en la informacion obtenida. Esto genera una perdida de confianza en la organizacion, perjudicando su imagen.

Para decidir sobre nuestra seguridad, debemos detectar las amenaza, determinar las debilidades y evaluar las fortalezas. En funcion a esto, tenemos que estimar la probabilidad de que una amenaza se concrete frente a nuestras debilidades y fortalezas. Luego de determinar la probabilidad, tenemos que distinguir las oportunidades que brinda el medio. Al saber esto, debemos ponderar las consecuencias y costos de cada amenaza, y determinar los costos de las medidas de seguridad. En base a esto, decidiremos sobre las medidas de seguridad apropiadas para nuestra organizacion.

## Plan de seguridad - Modulo 2

El plan de seguridad esta formado por un conjunto de medidas preventivas, detectivas y correctivas que tienen por objetivo proteger la integridad, confidencialidad y disponibilidad de los recursos o activos informaticos, tales como hardware, software, instalaciones, informacion y personas.

Los requisitos indispensables del plan son:

- Formulado por escrito
- Politica clara de Seguridad
- Transmitida a todos los niveles
- Asignacion de recursos

Se le debe asignar responsables al plan en todos los niveles, tanto en el area de sistemas, auditores, usuarios, seguridad general, y un consultor externo, segun si lo necesita dicha organizacion.

Los contenidos minimos del plan son:

- Objetivos generales
- Politicas de la empresa
- Educacion y capacitacion
- Procedimientos y controles
- Auditoria
- Plan de contingencias

Podemos hacer un esquema de amenazas con los siguientes requisitos:

| Tipo de amenaza | Se detalla la amenaza que puede afectar al sistema |
| -- | -- |
| Descripcion de la amenaza | Que tipo de amenaza se trata |
| Principales caracteristicas | Se detallan las caracteristicas de la amenaza |
| Consecuencias si se concreta | Se especifica que ocurre si dicha amenaza se realiza |
| Medidas preventivas | Medidas a realizar para evitar en la medida de lo posible la concrecion de la amenaza |
| Medidas detectivas | Son acciones realizadas para detectar cuando una amenaza esta ocurriendo |
| Medidas correctivas | Se especifica los hechos a realizar cuando la amenaza se concreto, para reducir el impacto de dicha accion |

## Plan de contingencias - Modulo 3

El plan de contingencias busca asegurar la continuidad de trabajo en todos los sistemas, limitando las consecuencias de una amenaza que se concreta, y recuperar la capacidad de procesamiento en el menor tiempo y al menor costo. Queremos recuperar los recursos informaticos protegiendo a las personas.

Se establecen los roles de cada uno y que tiene que hacer cada cosa. Tiene que contemplar los llamados a los servicios de emergencia, a los responsables de seguridad y al personal capacitado. Luego, se debe programar la recuperacion de los sistemas operativos, los utilitarios, los aplicativos y los datos de la organizacion que tengan relacion con todo el sistema en general. Ademas, tenemos que programar la puesta en marcha del equipamiento, incluyendo las instalaciones, equipos, redes y perifericos.

Para aplicarlo con exito, tenemos que tener pruebas del plan de contingencias, ensayandolo periodicamente y su concrecion para tener ensayado dicho plan. Se debe dictaminar al responsable de su elaboracion, que esté formulado por escrito, difundirse adecuadamente, verificarse su comprension, y revisar su validez, tanto de contenidos como de propositos.

Si vemos las principales dificultades que se pueden presentar para implementarlo, podemos tener en cuenta:

- Falta de directivas y politicas que gestionen la seguridad
- Falta de un Sistema de Gestion de la Seguridad de la Informacion
- El area de seguridad no tiene relacion con el resto de los departamentos:

    - Parece que no agrega valor al negocio
    - En la planificacion estrategica del negocio no se tiene en cuenta la estrategia que hay que llevar a cabo para la seguridad.

## Recomendaciones especiales - Modulo 4

- Principales medidas a considerar:

    - Copias de seguridad:

        - Segun su modalidad de copia:

            - Total: se realiza una copia de todos los archivos, permitiendo tener una restauracion completa de cada vez que se hace.
            - Diferencial: el sistema detecta que se cambio desde la ultima copia completa, y para su restauracion usa tanto la copia completa como la ultima copia diferencial realizada.  
            - Incremental: a partir de la ultima copia completa, se hace una copia de lo que cambio en funcion del periodo anterior. Al hacer una restauracion, se va a necesitar la copia completa mas todas las copias incrementales realizadas a la fecha.

        - Segun su forma de hacerlo:

            - Manual
            - Automatica

        - Multiples soportes de destino:

            - Fisicos
            - Virtuales

    - Proteccion ante accesos indebidos:

        - Seguridad en internet: Los cambios que obligan a adoptar medidas para la proteccion de la informacion, la proliferacion del hacking, la creciente extension de las redes de las empresas, su integracion con internet y su uso masivo, hace necesario una vigilancia permanente del estado de la seguridad de los sistemas. Para reducir el riesgo, podemos aplicar ciertas medidas, tales como:

            - Evitar accesos locales por parte de personas no deseadas
            - Evitar la contaminacion del equipo por parte de elementos que puedan dañar o ralentizar el funcionamiento del mismo, y que se aprovechan fundamentalmente de los sistemas de almacenamiento portatiles y/o de los sistemas de comunicacion
            - Evitar agujeros de seguridad mediante el mantenimiento actualizado del equipo informatico, su sistema operativo y los programas que utilicemos.

        Exsiten riesgos de la navegacion, tales como el robo de identidad, virus, gusanos, troyanos, spyware, hacking, estafas online, spam, contenidos web inapropiados. Para protegernos de estos riesgos, hay que mantener actualizado el sistema operativo y el soft instalado, cambiar periodicamente las contraseñas de acceso al sistema, e instalar y mantener actualizado un programa antivirus. Como proteccion general, convendra tener configurado un firewall o cortafuegos, y un filtrado de informacion.

        - Virus y otro software malicioso: La finalidad de un virus o malware responde a amenazas intencionales o no. En principio, no existe motivacion economica. Las recomendaciones realizadas son:

            - Usar un antivirus
            - Tener un firewall
            - Mantener dichos programas actualizados
            - No usar el usuario root salvo que sea necesario
            - Usar software de fuente legal
            - Desconectar puertos usb y grabadoras de cd
            - Restriccion del uso en internet
            - Restricciones en el uso del correo electronico
            - Existencia de un plan de contingencias

        - Claves de seguridad: Es el uso de contraseñas y factores de autenticacion para acceder a los diferentes servicios que necesitemos. Es la primera linea de defensa contra los ataques ciberneticos. Ademas de usar la contraseña como un factor de acceso, se pueden usar diferentes factores de autenticacion que permitan al usuario confirmar si el acceso realizado esta autorizado o no, y puede detectar si hubo intenciones de un acceso desconocido al sistema, mediantes confirmaciones por correo electronico, mensajes de texto, preguntas de verificacion de identidad, o un token de seguridad especifico. Se recomienda que las contraseñas sean distintas y dificiles de averiguar, se reestablezcan en forma peridoca, se usen diferentes caracteres, y sean de una longitud importante para que el costo de fuerza bruta sea mucho mayor para el atacante.

# Prueba y conversion

Se instalaran equipos, se acondicionaran locales, se tomaran cursos de capacitacion, se adiestrara personal, se convertiran archivos. Un punto importante sera controlar que el sistema funcione de acuerdo a las especificaciones. Una forma de conseguirlo es ejecutar en forma _paralela_ durante cierto tiempo los sistemas nuevo y viejo a efectos de notar diferencias. Se realizan las pruebas finales y las conversiones de archivos al nuevo sistema que permitan pasar a la fase siguiente.

## Objetivos

- Realizar las pruebas finales del sistema
- Realizar la conversion de los archivos para el nuevo sistema.

## Tareas

- Planificar, preparar y realizar la prueba operativa del sistema \(prueba piloto)
- Planificar la puesta en marcha y emitir las instrucciones de implantacion
- Planificar y concretar la conversion de los archivos al nuevo sistema
- Fijar los puntos de control para evaluar la puesta en marcha
- Fijar los criterios de aprobacion para el usuario

## Herramientas a usar

- **Tecnicas de simulacion:** Se podria definir como un medio que experimenta con un modelo detallado de un sistema real para determinar como respondera el sistema a los cambios en su estructura o entorno, y realizar mejoras en caso de ser necesarias. Pretende imitar el comportamiento del sistema real, evolucionando como este, ademas de estudiar la evolucion del sistema en el tiempo. Se insertan varios *inputs* a un sistema y proporcionan un modelo para evaluar o volver a diseñar y medir o cuantificar factores tan importantes como la satisfaccion del cliente, el uso de recursos, el proceso de reingenieria y el tiempo invertido en todo ello.   
- **Prueba de escritorio:** Esta prueba se realiza preparando los datos en el *escritorio,* para ello se utilizaran diversas herramientas que nos permitan crear un lote de informacion y obtener los resultados esperados que luego se cotejaran con los resultados obtenidos del sistema. La prueba tiene una asignacion de personal, en donde tiene que dirigirla un profesional que tenga conocimientos de administracion en general, del modulo en desarrollo, y de TICs en general; ademas de un desarrollador y un operador. En el inicio de la prueba, se deben usar exactamente el mismo lote de datos, y documentar paso a paso. Durante la prueba, se designa a un responsable general de la prueba, se cargan en el sistema los datos preparados, documentar los resultados, y enviar al desarrollador las solicitudes de cambios. Se finaliza la prueba cuando se encuentren depurados todos los cambios solicitados, y se emitira un informe final. Dicho informe es interno del equipo de desarrollo, donde se informara y documentara los resultados obtenidos en base a los requerimientos planteados. No se puede opinar sobre los objetivos propuestos, dado que no se hizo ninguna prueba en la organizacion.

    **Ventajas:**

    - Permite probar el funcionamiento del sistema en una situacion simulada.
    - Sirve para comenzar a verificar el cumplimiento de los requeridos realizados por la empresa
    - Usa un pequeño volumen de datos simulados pero contempla todas las situaciones imaginables
    - Ayuda a depurar errores del sistema sin exponerlo en el ambito productivo real de la empresa.

  **Desventajas:**

    - Es una prueba de elevado costo, dado que se implica el uso de personal especializado
    - El uso de datos simulados y en escaso volumen puede implicar que no se evalue el sistema con la exigencia de la empresa

 Se trata de una prueba realizada en el ambito del desarrollo, que resulta muy util para verificar el cumplimiento del sistema en todas las situaciones imaginables dentro de los parametros del requerimiento.
- **Prueba en paralelo:** 

## Documentacion

- Plan de prueba operativa
- Resultado de la prueba operativa
- Plan de conversion
- Instrucciones de instalacion

## Participantes

Participan todos los involucrados tanto del area de sistemas como del area del usuario
