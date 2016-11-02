
#ContentTaskMS

Proyecto de prácticas para la asignatura Cloud Computing de primer curso del master profesional en ingeniería informática de la UGR.

##Problema y solución propuesta

###Problema

Controlar un sistema CMS como por ejemplo Wordpress donde colaboran muchas personas, como por ejemplo en un magazine online, puede ser una ardua labor a la hora de la planificación y gestión de tareas como por ejemplo calendarios de publicación, eventos relevantes, o las fechas de entrega para diseños gráficos necesarios como por ejemplo para una campaña de publicidad en dicho magazine.

###Solución

Se desarrollará un software capaz de gestionar todas las tareas o al menos las críticas de un magazine online o un sistema de gestión de contenidos donde colaboren muchos usuarios y sea necesaria una organización y control de los hitos y tareas realizadas.

##Tecnologías del proyecto

###Arquitectura
Dado el carácter cloud y la necesidad de un buen escalado de cara al aumento del número de usuarios, se utilizará una arquitectura basada en microservicios.

###Microservicios
Los microservicios a implementar en la primera versión de la aplicación serán los críticos para un equipo de personas que trabajen colaborativamente en un CMS. Por un lado se implementaran un microservicio encargado de la gestión de roles dentro del equipo, a su vez se implementará otro microservicio encargado de la gestión de las tareas e información asociada a estas que pueden tener asignadas las diferentes personas involucradas.

###Back-end

El back end irá implementado sobre node.js, con el microframework Express y bases de datos MongoDB.

###Front-end

En el Front-end usaremos el framework AngularJS, CSS3 con Bootstrap y HTML5.

Licencia

Licencia [GNU GPL v3](https://github.com/joseangeldiazg/MII-CloudComputing/blob/master/LICENSE).
