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

En este paso, hay que preparar la entrevista usando una **guia de entrevista** para *definir el objetivo de la entrevista.* Durante la misma, corresponde definir el **lugar** para hacerla, donde permita a las partes desarrollar una entrevista efectiva, por lo que se busca que sea en el lugar de trabajo, pero no en el puesto de trabajo; el **horario,** en lo posible que sea durante el horario de trabajo; la **duración,** que no va a ser reducido, pero tampoco tiene que consumir mucho tiempo; luego, correspondera saber si va a ser comodo o necesario **anotar, grabar o filmar,** ya sea porque es una entrevista inicial o porque el entrevistado se pueda sentir incomodo, y se dificulte la toma de información; y la **cantidad** de preguntas, para obtener la mayor cantidad de datos por parte de los entrevistados y que no sea agobiante para los mismos. Luego de esto, correspondera hacer un **resumen de la entrevista,** para recapitular lo dicho en el proceso, y tener la opcion de hacer una posterior entrevista para asentar los datos recabados y confirmar o corregir la informacion.

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

Tenemos que planificar como hacer la observacion y que objetivos tenemos de dicha observacion. Se debe anunciar la tarea a realizar para evitar problemas, y nos permite obtener datos empiricos de la problematica y el manejo de la organizacion en dicho modulo. En esta tarea, debemos asumir el rol de observador pasivo, donde no emitimos ninguna opinion, interferencia ni recomendaciones para no alterar la informacion. Es recomendable anotar comentarios y sugerencias por parte del observado, ya que es quien hace la tarea y conoce o encuentra que problemas son los mas importantes. Ademas, se prefiere recopilar documentacion. Al finalizar, debemos realizar un informe detallado de lo observado.

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

Deben ser claros, precisos, factibles, alcanzables dentro de un presupeusto de recursos, dentro de un estudio de factibiilidad limitado, y verificables. Adicionalmente, en los sistemas se agrega el crecimiento modular

### Alternativas de solucion

Para el cliente conviene que le digamos aquellas soluciones a las que puede acceder. Estas se pueden clasificar segun:

- Sin TICs.
- Con TICs

    - Sistema *enlatado:* Son aquellos sistemas diseñados para una solucion y se puede adquirir distintas herramientas segun las necesidades requeridas
    - Sistema *a medida:* Se hace el analisis, el desarrollo y la implementacion para la organizacion que se trata

        - Desarrollo propio: La organizacion desarrolla el sistema
        - Desarrollo de terceros: Se contrata dicho desarrollo

### Anexos

Es frecuente que se entreguen junto con el informe final, donde se detalla la informacion obtenida durante el relevamiento que pueda ser usada por la organizacion en sus decisiones. Puede ser equipamiento, sistemas operativos, capacidades, aplicaciones, etc.

### Requerimiento

Es el documento por el cual la organizacion expresa lo que esta pidiendo, y la importancia que tiene es que permite a los proveedores cotizar el mismo servicio o necesidad. Dicho requerimiento tiene que tener 6 grandes rubros:

- **Normas legales:** Se hace referencia a las normas legales que deben tenerse en cuenta en el desarrollo del sistema, y que afecten directa o indirectamente a la organizacion. Estas incluyen a las normas legales nacionales, provinciales y municipales, resoluciones de los organismos de control, y las normas referidas a la actividad y/o tipo de organizacion.
- **Normas tecnicas:** Hace referencia al conjunto de normas de tipo tecnico que deben aplicarse a la solucion de cada sistema en particular. Se incluyen aquellas normas generadas por procedimientos tecnicos o por la misma costumbre. La misma organizacion puede tener determinada necesidad de informacion que respondera a este punto.
- **Entradas:** Son aquellas necesidades previsibles de ingreso de informacion al sistema. Comprende todos los elementos que pueden generar informacion, tales como el teclado, la pantalla, el scanner, microfono, etc.
- **Salidas:** Incluye todas las necesidades previsibles de salida de informacion del sistema. Estamos hablando de todo lo que permite exportar la informacion del sistema para los usuarios.
- **Controles:** Trata de los procesos de control que se solicitan en las diversas etapas del procesamiento de informacion. Para esto, tanto el profesional de administracion como el profesional de sistemas permitira diseñar procedimientos que cumplan con la tecnica de desarrollo y que permitan ejecutarlos reduciendo al maximo la posibilidad de error. Gran parte de los controles van a estar vinculados a las entradas de informacion. Otra parte se refiere a los procedimientos que verifiquen la consistencia y congruencia de la informacion almacenada.
- **Seguridad:** Es una parte crucial del sistema, por lo que se definen dichas condiciones al principio. Se pueden ennumerar el control de acceso, el respaldo y recupero de la informacion, encriptado de informacion, forma y lugar de procesamiento, y actualmente consideramos la nube como paradigma.

### Presupuesto

Cada potencial proveedor recibio el requerimiento de la organizacion, el cual responde a los objetivos planteados en el informe final del estudio preliminar. Su presupuesto debe responder tal requerimiento para que la organizacion pueda comparar adecuadamente todos los que reciba. Los contenidos a pedir al proveedor son:

- **Descripcion:** Debe responder al requerimiento, que considere los objetivos propuestos, incluya un detalle de los resultados esperados y mencionar las formas de procesamiento propuestas.
- **Recursos afectados:** Se debe detallar el equipamiento existente y necesario, el tiempo, tanto en el cronograma como el control de avance, los recursos economicos y financieros, es decir, importes y certificaciones, y el personal. En este ultimo, se debe considerar el personal de la empresa afectado directa o indirectamente al proyecto, y las personas que han de intervenir en el proyecto pertenecientes al grupo de analisis, y la relacion funcional entre las personas que van a intervenir en dicho proyecto.
- **Propuesta economica y financiera:** Va a incluir el importe total y detalle de las formas de pago.
- **Clausulas generales:** Cotizacion de precios por etapas, segun porcentaje de avance y fecha prevista de pago; forma de ajuste del precio, tanto indices de ajustes, indice base, forma de obtener el indice; intereses por mora, incluyendo la tasa de interes y forma de calculo. Se debera indicar por cuanto tiempo mantendra la oferta.

El presupuesto de cada proveedor debe responder rigurosamente al detalle del requerimiento. Compararlos vuelve a ser tarea de profesionales, para poder evaluar si se ha cumplido con dicha condicion. Diversos procedimientos permitiran realizar la evaluacion de tal forma que pueda establecerse un orden de prioridades que los responsables de la organizacion tomen la decision final.

#### Cronograma segun las etapas de la metodologia
