Desarrollo del proyecto
-----------------------

Cómo se trabajará
=================
La dinámica de desarrollo del sistema será iterativa, es decir que se irán haciendo versiones
en las que se implementa un avance en la aplicación y se van mostrando al cliente para que
evalúe si el avance que se hizo es funcional o si es que se le ocurrió una nueva necesidad,
y de ser así se aplican las correcciones. Para esto se hace necesaria la implementación de
alguna de las metodologías de desarrollo, de tal manera que se tenga un estandar para el
desarrollo de cada iteración.

En cuanto a la implementación de metodologías, existen muchas de estas, que se adaptan a ciertos
tipos de sistemas específico. Pero todas abarcan la comunicación con el cliente, que ya se ha
realizado en dos ocasiones, la fase del análisis, la cual se encuentra implementada en este
documento junto con el diseño del sistema (en donde si incluyen la mayoría de gráficas), las cuales
son las fases mas importantes del desarrollo, luego vienen las fases de implementación y despliegue.
Estas últimas fases son las que normalmente definen qué metodología utilizar.
Para llevar a cabo el desarrollo de este sistema se ha determinado que se utilizará el modelo
de "desarrollo por Prototipos".

Modelo por prototipos
^^^^^^^^^^^^^^^^^^^^^
Es un modelo iterativo, en el cual cada iteración representa un nuevo prototipo de alguna propiedad
o solución a una necesidad del sistema, en el cual se le da mucha participación al cliente para poder
validar lo que se está desarrollando.
Un prototipo es una versión de prueba de alguna o algunas soluciones en el sistema, el cual puede o no
aplicarse a los avances definitivos del proyecto, según sea validado por el cliente.

Motivos para la utilización del modelo por prototipos:
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
 * En cada iteración se podrá observar el grado de conformidad del usuario por medio de una prueba sin haber implementada aún dicho protipo.
 * Se disminuyen los riesgos, por medio de la validación del cliente.
 * En caso de haber implementato un prototipo no funcional, es posible hacer una nueva iteración para replantearlo y optimizarlo.
 * Cada prototipo será aplicado al proyecto hasta que ya ha sido validado del todo.


Actividades a realizar
======================
Estas son todas las actividades implicadas en la realización del proyecto, las cuales se mencionan a continuación:

Análisis y diseño:
^^^^^^^^^^^^^^^^^^
En el análisis se toman los datos de las entrevistas para determinar todas las características que el sistema
requiere y las actividades que todos los usuarios podrán realizar en él.
Luego, en el diseño se realizan los modelos y diagramas necesarios para representar el sistema y su funcionamiento,
todos los tipos de usuarios que tendrá y de que forma van a interactuar con que el sistema para que el cliente
pueda determinar si es exactamente lo que quiere, antes de empezar a desarrollar.

El desarrollo y depuración:
^^^^^^^^^^^^^^^^^^^^^^^^^^^
Estas actividades son las que normalmente toman más tiempo, ya que comprenden toda la parte de la codificación del
sistema en el lenguaje de programación más adecuado para este tipo de sistema (php) y la corrección en caso de
que el cliente determine que algo debe ser distinto o necesite alguna otra característica.

Instalación del sistema:
^^^^^^^^^^^^^^^^^^^^^^^^
Entas actividades son las que están relacionadas con el despliegue del software que se va entregar. En este punto
la aplicación ya estará terminada, pero deben realizarse todos los trabajos relacionados con el hardware necesario
para la aplicación, las cuales van desde la instalación del software en un ordenador que cumpla con los recursos
minimos que necesitará el sistema, la configuración de los servidores para administrar los datos de la institución
y la instalación de la red necesaria, que abarca la configuración de todos los dispositivos de red que se utilizarán.

Capacitaciones:
^^^^^^^^^^^^^^^
Al momento de haber instalado y entredado el sistema se debe instruir y capacitar a todo el personal de La Casa de la
Cultura que utilizará la aplicación, esto abarca demostraciones de las tareas que se pueden hacer en el sistema y la
explicación de la función de todos los menús y botones en las diferentes interfaces de la aplicación, como también
aclaración de dudas e inquietudes que los usuarios tengan para utilizar adecuadamente el programa.
El objetivo principal de esta actividad esque todos los usuarios de La Casa de la Cultura aprendan a utilizar de la
mejor forma la aplicación.

Entregables
===========
A continuación se mencionarán los productos y subproductos (no servicios) que se entregarán como parte del sistema:

La aplicación web:
^^^^^^^^^^^^^^^^^^
Es el paquete con todos los archivos necesarios para el funcionamiento de la página web, en donde se incluiría
el código fuente en forma de un archivo html, archivos de configuración del sistema junto con todos los recursos
que éste necesite para desplegar la información de forma adecuada (por ejemplo imagenes, diseños con css,
archivos de configuración, etc).

Manual de usuario:
^^^^^^^^^^^^^^^^^^
Este es un archivo, puede ser en formato PDF en el cual se describen todas las opciones que tendrá la aplicación,
es similar a lo que se enseñaría en la capacitación del persona. Es decir que quedará como un material de apoyo
cuando en algún momento algun usuario de La Casa de la Cultura tenga duda sobre como realizar alguna tarea.
Por lo anteriormente mencionado, en este documento deben ir contemplados sino todos, casi todos los casos que
puedan darse en el uso de la apliación.

Manual Técnico:
^^^^^^^^^^^^^^^
Al igual que el aterior, este es un archivo de texto, con la diferencia de que en este se especificarán las
características técnicas que utiliza el sistema, como por ejemplo, las características del servidor desde donde
se ejecutará la página, características del diseño de la red (topología, mecanismos implementados, tipos de
terminales utilizados y para qué, etc), descripción del la configuración de la base de datos, entre otros.
Este manual va enfocado para personal de La Casa de la Cultura con conocimientos técnicos, es decir, personas
que tengan el mayor conocimiento posible sobre temas de computación.

Tabla de tiempos y costos
=========================

+-----------------------+----------------+-------------+
| Productos y servicios | Tiempo de      |             |
| a entregar            | realización    | Costo(Q)    |
+=======================+================+=============+
| Aplicación principal  |                |             |
| con todos los módulos.| 10 semanas     | 10,000.00   |
+-----------------------+----------------+-------------+
| Soporte por 5 meses.  | N/A            | 0.00        |
+-----------------------+----------------+-------------+
| Diseño, cofiguración  |                |             |
| e instalación de red. | 4 días         | 1,000.00    |
+-----------------------+----------------+-------------+
| Capacitaciones.       | 2 días         | 0.00        |
+-----------------------+----------------+-------------+

NOTA: Los costos de los manuales (de usuario y técnico) y las capacitaciones están incluídas en el costo de
la aplicación, al igual que el tiempo de soporte al sistema.

Condiciones
===========

Tiempos y costos:
^^^^^^^^^^^^^^^^^
Tanto los costos como también los tiempos de producción están sujetos a cambios, según las necesidades o
preferencias que el cliente decida agregar durante el transcurso de la etapa del desarrollo. Así,
si el cliente presenta siempre conformidad con lo mostrado en las entregas parciales, se mantiene el
tiempo estipulado en la tabla anterior.

Modos de pago:
^^^^^^^^^^^^^^
El cliente debe hacer efectivo un pago por el 20% del total del costo del proyecto al momento de hacer el trato
y aceptar el inicio del desarrollo, luego deberá hacer efectivo otro 30% del total al momento de la primera entrega
del proyecto. Efectuando el último pago por el otro 50% del total al hacer la entrega final del sistema.

Contrato Legal:
^^^^^^^^^^^^^^^
Este debe estar respaldado por un abogado, en el cual se estipularán los costos y modos de pago, las fechas de
entrega y el tiempo de soporte al sistema, la fecha de inicio y fecha de finalización de éste.

Pago de servicio de hosting:
^^^^^^^^^^^^^^^^^^^^^^^^^^^^
El cliente será quien tenga que hacer efectivo el pago del servicio de Hosting de datos, que será para almacenar
la información de la base de datos y los archivos para que el sistema funcione. Los pagos se harán en el tiempo
estipulado por el sitio en donde se contrate el servicio.

Compra del dominio:
^^^^^^^^^^^^^^^^^^^
Se debe comprar un dominio de internet, para contar con el acceso desde cualquier parte del mundo a la página web.
Compra que deberá ser efectuada por La Casa de la Cultura.

Conectividad a internet:
^^^^^^^^^^^^^^^^^^^^^^^^
La Casa de la Cultura debe de contar con un servicio de internet de banda ancha para atender las conexiones entrantes
al servidor. Si no cuenta con este servicio, deberá contratarlo para que funcione el sistema.

Encargado de supervisar las entregas parciales:
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
La Casa de la Cultura debe tener una persona delegada que se encargue de validar las entregas parciales que se hagan
del sistema.
