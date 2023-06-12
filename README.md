# Preentrega3-Coitino

El proyecto consiste en la Tercer Preentrega del curso y contiene un avance de lo que se entregará en el proyecto final. Este proyecto será un blog sobre lugares de interés y actividades de Mallorca.

En esta entrega se incluyen 6 modelos:
 - SobreNosotros
 - Playas
 - Pueblos
 - Senderismo
 - Contacto
 - Presentación

Se puede acceder a la vista principal con la url 'inicio/'.

En la barra de navegación vemos los siguientes botones:
 - "Inicio" lleva al inicio desde cualquier página
 - "sobre Mí" llega a una página en la que se muestra un texto cargado directamente en el template "sobrenosotros.html". Este texto también se encuentra registrado en BBDD para que se pueda editar directamente desde la web, no se muestra desde allí porque no se utiliza CRUD en esta entrega.
 - "Contacto" permite ingresar a un formulario de contacto. Lo registrado allí se guardará en la tabla "Preentrega3App Contacto". 

En la vista principal hay un acceso a Playas, Pueblos y Senderismo. Al acceder, la web nos dirige a una vista provisional que funciona como ejemplo ya que, al no utilizarse CRUD en esta entrega no se visualizan los datos de la BBDD.

En cada uno de estos tres apartados tenemos un botón "Añadir nuevo" mediante el cual podemos acceder a un formulario para cargar datos en nuestra BBDD.

El apartado "Playas" cuanta con un botón que nos permite buscar por nombre una playa registrada en la BBDD y nos devuelve los datos guardados.

Se encuentra disponible también la url 'admin/' desde la que se puede ver y editar el contenido de la BBDD.
