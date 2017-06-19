# Preguntas 13 - Junio - 2017

## Wireframe 1 (01-home.png):

1.¿La fecha que aparece en el listado de actividades en el centro por defecto es del día de hoy?

   **Sí**

   Es decir, ¿al entrar en la página aparecerían visibles hoy, ayer, antes de ayer, mañana y pasado mañana?

   **Sí, tal como aparece en el wireframe, aparece en el centro el día de hoy.**


2.¿Las fechas que aparecen en el listado de actividades son fijas o habrá desplazamiento al seleccionar alguna de ellas?
   Ejemplo: ¿si se selecciona "Vie 19" pasará a estar en el centro y se verá del 17 al 21 o simplemente se resaltará "Vie 19" a la derecha del listado cargando las actividades de ese día?

   **La primera opción, si se selecciona "Vie 19" pasará a estar en el centro y se verá del 17 al 21**

3.Nos gustaría saber cuál es vuestra idea para el bloque de redes ya que no hemos hablado nada sobre él.

   **He incluido en el documento funcional la información sobre este módulo. Página 39 aproximádamente.**

4.No sabemos hacia dónde deben apuntar los enlaces de "Ver todos" en convocatorias y en vídeos.

   **Llevará a la página de actualidad ( _falta por hacer_ ) filtrada por vídeos de manera que sólo se vean los vídeos**

## Wireframe 2 (02-seccion-medialab.png / 02-seccion-medialab-opcion2.png):

5.Aquí hay 2 diseños distintos, uno a página completa y otro que parece que parte la página en varias y pone un menú lateral para cambiar. ¿De qué manera debe ir?

6.¿Qué debe ir en "Equipo" y en "Empleo"?

**Equipo: Aparecerán todos los trabajadores del centro, ordenados por años y por cargo. Al pinchar en el año o navegar izquierda derecha se cambiará de año. Actualizando las personas que trabajaron en el centro ese año. Al pinchar en el cargo de un año, se filtrarán aquellos trabajadores que tuvieran ese cargo ese año. Al seleccionar una persona, aparecerá la biografía de esta.**

Por ejemplo:

        2008-2007, "Dirección". Aparecería una persona.
        2016-2015, "Mediación". Aparecerán ocho personas.
        Se podrá navegar a la biografía de cualquiera de ellos.

**Empleo: Aparecerán todas las ofertas de empleo, becas, licitaciones y adjudicaciones del centro.**


7.¿Adónde apunta el enlace "Más información" de "Espacios" (02-seccion-medialab.png)?

** A una página genérica con menú lateral que se podrá editar tanto el menú como el contenido**

## Wireframe 7 (07-actividades-vistalistado.png):
8.¿El filtro "Tipo" a qué se refiere exactamente?

**Grupo de trabajo, seminario, taller, encuentro avlab, ...**

9.En el documento funcional se habla de un listado "calendario", pero no hay diseño.

**Integrar la vista calendario en la página de actividades y en el administrador interno también se podrán gestionar las actividades.**

Revisar este calendario

https://fullcalendar.io/

https://fullcalendar.io/scheduler/

https://fullcalendar.io/js/fullcalendar-scheduler-1.6.2/demos/vertical-resource-view.html

https://fullcalendar.io/js/fullcalendar-3.4.0/demos/list-views.html


## Wireframe 8 (08-actividad-ficha-usuario no registrado.png):
10.¿Las etiquetas (tags) tienen alguna funcionalidad? No encontramos referencias a esto en el documento funcional.

**Los tags aparecen en las actividades, proyectos, post de blogs, videos. La idea es que al pinchar en un tag se enlace con la página general de actividades, proyectos o posts filtados por ese tag.**

**Por ejemplo: Si estamos en la página de una actividad y pinchamos en el tag "textil" nos llevará a la página "general de actividades" filtrada por ese tag "textil".**

**Lo mismo para proyectos, que llevaría a la página "general de proyectos".**

**Para los posts de los blogs, llevará a la página "Actualidad" en la que aparecerán los posts por ese tag.**

**Para los videos, llevará a la página "Actualidad" en la que aparecerán los videos por ese tag.**

11.Comentarios en actividades-CAPTCHA: no consideramos procedente su desarrollo al tener en cuenta los riesgos que acarrea (toda la web exige registro para participar y creemos que la inclusión de comentarios en la timeline no debería ser una excepción). Este requisito se solicitó una vez iniciado el desarrollo.

**De acuerdo, eliminamos los comentarios de usuarios no registrados, pero se mantiene la opción de poner el módulo de comentarios para usuarios registrados.**

## Wireframe 11 (11-actividad-ficha-logueado-inscripcion.png):
12.¿El formulario será el mismo para todas las actividades?

**? Sí para todas las actividades con inscripción avanzada. Este wireframe hay que trabajarlo más, ya que desde el punto de vista de usabilidad no es buena solución ponerlo en otra pantalla.**


## Wireframe 14 (14-proyecto-ficha-documentacion.png):
13.¿A qué se refiere el siguiente comentario: "Categoría por temática. Solo las actividades tienen además categoría por tipología"?

**Ese comentario no debería ir en los wireframes, no se quién lo ha puesto. Imagino que se refiere a que ahí irán los iconos de las categorías temáticas preparados por Jaime. Y en el caso de la página de Actividad aparecerá el icono de "Categoría" temática y también el "Tipo" de actividad: seminario, grupo de trabajo, taller, mesa redonda, presentación, etc**

## Wireframe 16 (16-proyecto-ficha-descripcion-logueado.png):

**He subido los wireframes de proyecto modificado**


14.Estamos dándole vueltas al desarrollo de la caja que aparece entre "Descripción corta" y "Timeline" y creemos que la implementación que aparece en el mediador nos puede dar problemas para generar ese desplegable. Sugerimos lo siguiente:
"Ver perfil" será accesible al hacer clic en la esfera con el avatar.

**Efectivamente, al pinchar en la esfera con la foto del usuario, no aparecerá el desplegable, sino que nos llevará a la página de perfil de ese usuario**

"Solicitar mediación" podría ser un botón aparte, además si hay varios mediadores no le vemos sentido a que esa opción aparezca bajo todos los usuarios. Esto salvo que nos digáis que realmente es algún tipo de petición dirigida al mediador seleccionado en concreto. Por favor, definidnos cuál sería la funcionalidad de esta opción.

**La opción solicitar mediación la eliminamos.**

"Enviar mensaje" pasaría a estar en el Rocket Chat así que tampoco lo vemos necesario.
 **Esta funcionalidad pasa a la página de perfil del usuario.**

## Wireframe 19 (19-convocatoria.png):
15.La estructura del formulario de comentarios no concuerda con los anteriores de proyecto y actividad.

**Es necesario mejorar este wireframe y probar la página con información real**
**En esta página no hay módulo de comentario.**

## Wireframe 20 (20-convocatoria-logueado.png):
20. Este diseño no coincide con su contrapartida sin haber ingresado en el sitio.

**? No deberían ir comentarios en esa página**

## Wireframe 21 (21-convocatoria-inscripcion-logueadoPASO1.png / 21-convocatoria-inscripcion-logueadoPASO2.png):
21. El nombre en el paso 1 debería ser "Formulario de propuesta".
22. Paso 2: Suponemos que este formulario será distinto dependiendo de la categoría de la convocatoria. ¿Es correcto?

## Wireframe 22 (22-zonaprivada-miperfil.png):
23. ¿De qué manera se podrán desactivar los avisos de notificaciones por correo?

## Wireframe 24B (24B-ZonaPrivadaAdmin-MisActividades-ActivUnica.jpg):
24. ¿La gestión de colas de actividad se hará desde el panel de "Mis actividades" (si el usuario es gestor de la actividad)?

## Wireframes 27 (27-zonaprivada-mismensajes.png) y 28 (28-zonaprivada-nuevomensaje.png):
25. Desfasados, aquí va ahora Rocket Chat.

## Wireframe 31 (31-actualidad.png):
26. ¿Qué tipo de contenido debe mostrarse en esta página?
27. El contenido que aparece a la derecha, ¿es un listado distinto?
28. Los filtros que aparecen debajo del título, ¿son específicos de esta página o son categorías que se usan en alguna otra parte? ¿Qué es "filtroporpalabrasclave"?
29. Creemos que lo mejor sería cambiar el botón "Ver más" por un paginador al uso, ya que rompe la homogeneidad de la página.

## Dudas sobre proyectos:

30. Páginas: ¿Qué significan los repositorios? ¿Cuál es su funcionalidad? ¿Cómo se crean? Si son tipos de contenido no hay por qué hacer repositorio.
31. Cuando se solicita mediación, ¿se hace a un mediador en concreto o simplemente se pide que en ese proyecto se haga la mediación siendo el coordinador quien designa a un mediador?
32. Compartir proyecto: ¿cuál sería el flujo de ejecución? ¿El usuario pasa por encima del enlace y se muestran los iconos de las redes sociales? (Para dispositivos móviles habría que hacerlo de otra manera)
33. Archivos multimedia: en el resto del proyecto hemos observado que se ponen vídeos incrustados de YouTube pero podemos hacer que sean vídeos del propio sitio. ¿Es correcto?

##  Búsqueda mediante Apache Solr:

34. No hay diseño de la búsqueda general.
35. ¿Se va a desear que alguna vista más haga uso de Solr? Cuantos más elementos se añadan a Solr más lento irá, por tanto no se puede hacer que todas las búsquedas dependan de Solr.

## Otras dudas de la zona privada:

36. Proponer una solución para el sistema de foro para que pueda ser evaluada su integración. Proponemos que sea el propio sistema que incluye Drupal dada su integración de serie y que su puesta en marcha sería prácticamente inmediata.

Incluimos adjunto el calendario con el estado del proyecto según envió Francisco José Romero a Madrid Destino el día 1 de junio. Como bien comentó al final del correo donde lo envió: "[p]ara cumplir este calendario necesitamos un feedback ágil con Medialab en cuanto a que las dudas planteadas se resuelvan en tiempo y forma".




No están descritos los módulos:
Módulo de comunicación
Módulo de gestión de usuarios
Módulo de gestión de recursos
Módulo de gestión de archivo
Módulo de redes sociales



**Los botones y las cajas de texto no se diferencias. Revisar el diseño de Jaime y mejorarlo en caso de que no funcione bien.**
**Falta la página pública de perfil de usuario**
Ordenar los wireframes en teamwork.
Faltan las versiones para versión móvil, menú hamburguesa,
¿Cómo puedo ver todas las convocatorias? Dónde me lleva "Ver todas" en Convocatorias
