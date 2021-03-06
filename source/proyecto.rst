El proyecto
===========

Descripción General
-------------------

El proyecto consiste en implementar una aplicación web que sea accedida desde
cualquier parte del mundo, la cual deberá contar con un directorio de artistas
clasificados por categoría, según el tipo de arte que practiquen. Deberá permitir
a los usuarios visitantes poder registrarse, por medio de Facebook o por
e-mail en su defecto para tener una mayor interacción en la aplicación, como
calificar eventos y dejar reseñas, seguir artistas y/o eventos, suscribirse
para recibir información de los temas de su interés, etc.

La aplicación debe permitir registrar nuevos artistas, cuya información debe ser
validada por un delegado en el área de comunicación de la casa de la cultura.
Se debe poder agregar notas educativas, referente a cualquier tipo cultura.

Del lado de la casa de la cultura, la aplicación debe permitir calendarizar nuevos
eventos y asignar a estos cualquiera de los artistas que esté disponible, al igual
que la reservación de alguna instalación propia que este disponible o una instalación
externa, con la opción de incluir la ubicación en formato de mapa. También, deben
poder consultar información estadística sobre la cantidad de eventos en un lapso,
usuarios y artistas registrados, categorías preferidas, entre otras.


Modulos
-------

Artistas:
^^^^^^^^^
En éste módulo se llevará el control de los artistas que se registrarán en el
sistema. Acá se permitirá gestionar a los artistas que estarán en el directorio
de la aplicación, es decir, operaciones como registrar un artista, editar su propio
perfil, borrar la cuenta, entre otras operaciones. Acá también se abarcará la
validación de los datos del artista que desee registrarse y se proporcionará una
alternativa para que cualquier usuario o artista registrado pueda contactar a otro artista,
bien sea por su dirección de correo u obteniendo su numero de teléfono, de tal manera
que quede registrado en el sistema que el artista fue contactado.

Ver :ref:`etiqueta1`.

Usuarios:
^^^^^^^^^
En este módulo, de manera similiar al de los artistas, permitirá llevar el control
de los usuarios particulares que deseen registrarse en el sistema. Con la salvedad
de que estos tienen la alternativa de registrarse mediante su cuenta de Facebook,
desde donde se obtendrán sus datos, o en caso contrario ingresará su información
personal necesaria y una dirección de correo electrónico. Este módulo permitirá editar
el perfil de usuario, dejar reseñas sobre eventos eventos, acceso a leer notas educativas
y calificar eventos.

Ver :ref:`etiqueta2`.

Gestión:
^^^^^^^^
Este módulo será uno de los más complejos por las operaciones que permitirá realizar.
Este será el módulo que estará enfocado a los eventos, acá se permitirá asignar los
artístas al evento y también se desplegará y agregará toda la información concerniente
al evento, como los horarios disponibles de los artistas e instalaciones disponibles para
los eventos. Acá se hará la programación de eventos o el cronograma, a la cual tendrán
acceso todos los usuarios y artistas, y donde se permitirá darle seguimiento a uno o varios
eventos en particular, por medio de calendar o por notificaciónes de correo electrónico.
Este módulo estará más orientado a los responsables de manejar la aplicación en la casa de la cultura.

Ver :ref:`etiqueta3`.

Recolección:
^^^^^^^^^^^^
Este módulo, como su nombre lo indica, será el encargado de la recolección de datos
estadísticos de los demás módulos, fechas, cantidades, categorías, visitas, lugares, entre otros.
Se encargará de consultar datos correspondientes a los demás módulos y luego pasarle
los filtros adecuados para presentar la información estadística relevante. Estadísticas como,
la valoración de los eventos, la cantidad de eventos en un lapso, cantidad de eventos en un lapso
por tipo de arte (para que sepan qué arte es preferida por las personas), el número de veces que los
artistas fueron contactados, cantida de visitas, entre otros. Esta módulo funcionará específicamente
para los delegados para usar la aplicación en La Casa de la Cultura.

Control:
^^^^^^^^
Este módulo será el encargado de brindar herramientas para administrar la información que se
muestra en la página, desde acá se podrán gestionar los post educativos de libre acceso, que
serán normalmente post sobre cualquier tipo de arte y cultura, es decir, agregar, editar y
elmininar los post que en algún momento se consideren obsoletos y no aplicables, desde acá
existirá también la opción de eliminar cuentas de artistas, artistas que ya no volverán a estar
disponibles o que por politicas de la casa de la cultura ya no puedan estar en el directorio.
De igual forma como con los artistas será para los usuarios registrados. Acá tambíen se permitirá
la gestión de las categorías y en algún momento la reclasificación de eventos a otra categoría o
también eliminar algunos eventos que algún momento queden obsoletos.

Ver :ref:`etiqueta4`.
