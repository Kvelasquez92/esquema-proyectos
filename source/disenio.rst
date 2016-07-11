Diseño de la aplicacíon
=======================

Casos de Uso
------------

A continuación se presentarán los diagramas de casos de uso para cada módulo. Estos diagramas
sirven para representar de de forma gráfica los distintos actores que tendrá el sistema,
es decir los distintos tipos de usuarios que tendrán interacción con el programa y las distintas
actividadesque cada uno de ellos podrá realizar en el programa, según cada módulo y el nivel de acceso
que tenga cada actor.

.. _etiqueta1:

Casos de uso módulo de Artistas:
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: img\moduloArtistas.png
    :width: 75%

Este módulo tiene los actores Artista y Administrador puesto que estos dos son los que realizarán
las tareas descritas en el diagrama, las cuales estan relacionadas con la gestión de Artistas.

.. _etiqueta2:

Casos de uso módulo de Usuarios:
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: img\moduloUsuarios.png
    :width: 75%

Para este diagrama serán los visitantes particulares de la página los que podrán realizar dichas tareas
específicamente, tal como se muestra, será un unico actor. En algún momento podría involucrarse acá
la tarea de eliminar el usuario, en donde podría también entrar a participar el actor Administrador.

.. _etiqueta3:

Casos de uso módulo de Gestión:
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: img\moduloGestion.png
    :width: 75

En esté módulo se incluyen todas las tareas que están relacionadas con la creación y manejo de eventos,
las cuales corresponden a La Casa de la cultura, que en este caso es el usuario Administrador.
Acá también se abarca las opciones de suscripción de los usuarios.

.. _etiqueta4:

Casos de uso módulo de Control:
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: img\moduloControl.png
    :width: 75%

Este módulo es el que incluirá las tareas más generales del sistema, las cuales están más relacionadas
con el acondicionamiento gráfico de la información dentro del programa, es por eso que solo un usuario
con privilegios de administrador podrá hacerlas, en este caso será La Casa de la Cultura.


Clases
------
En este tipo de diagrama se describe la idea principal de la lógica de programación del proyecto, normalmente
el diagrama es bastante más extenso, pero para fines practicos se define acá la parte esencial, para comprenderlo
mejor es recomendable consultar también el diagrama de BD ya que tiene bastante relación. Se puede intuir en
principio que el diagrama de clases también necesitará una clase por cada tabla del diagrama de BD, y sus asociaciones
con entre clases serán también basicamente las mismas.

.. figure:: img\diagramaClases.png

Diagrama de BD
--------------
Este diagrama describe la lógica del almacenamiento de los datos en la computadora y la relación que tendrán
estos datos entre sí. Cada tabla representa una entidad y puede entenderse que cada entidad será almacenada
con los campos indicados ya que así esta definido su formato.

.. figure:: img\modeloRelacional.png
