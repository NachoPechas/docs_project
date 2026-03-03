&nbsp;											PARTE I
Preguntas Tangaritac

1.Me gustaría desempeñar el rol de responsable en bases de datos del proyecto, encargándome de definir correctamente la base de datos y asegurando la integridad y consistencia de los mismos, adicionalmente podría apoyar en las pruebas y control de calidad de cada avance del proyecto

2.Dentro de mis fortalezas se encuentran el modelado de bases de datos y programación orientada a objetos en java, tambien soy una persona organizada en la estructura de los proyecto y me enfoco en hacer suficientes pruebas para que cada avance en el proyecto no genere conflictos

3.Uno de los principales aspectos que debo mejorar es la comunicación con mi equipo de trabajo, es fundamental para explicar de manera clara las ideas y tener mejor organización en el reparto de las tareas

Preguntas Johan Muñoz

1. Me gustaría tener un rol organizativo asignando tareas y viendo que todo el proyecto esté fluyendo de manera correcta y también un rol de desarrollo de backend en el curso.
2. Tengo experiencia gestionando grupos de trabajo y también habilidades que facilitan en el desarrollo de un buen backend.
3. Debo de mejorar en gran medida el manejo de mis tiempos para poder hacer efectiva de la mejor manera todas las entregas de los cursos y poder dejarlas con un buen colchón de tiempo.
   3.Uno de los principales aspectos que debo mejorar es la comunicación con mi equipo de trabajo, es fundamental para explicar de manera clara las ideas y tener mejor organización en el reparto de las tareas



Preguntas Juan Cristiano

1. Me gustaria tener un rol enfocado en el desarrollo de backend y corregion de bugs, como proceso para debuguear posibles problemas que se presenten y hacer pruebas y testeos para el desarrolo del proyecto
2. Tengo experiencia con anterioridad corrigiendo problemas de otros compañeros en proyectos ya realizados, tambien cuneto con experiencia previa en proyectos de python y java, me interesa ir avanzando acorde al tiempo para no generar atrasos en la entregas y tener suficiente tiempo para corregir problemas en caso de haberlos
3. Uno de los aspectos a mejorar es la comunicacion con mi equipo pues me ha llegado a pasar que a la hora de corregir errores cambio codigo de mis compañeros sin documentarlo bien o informales lo cual luego genera confusiones entre nosotros

Preguntas Andrés Hernández

1. Me gustaría desempeñar el rol de diseñar la arquitectura del proyecto, definiendo el stack de tecnologías a usar, y la infraestructura donde realizar el despliegue.
2. Tengo experiencia en trabajos colaborativos, liderando pequeños proyectos de software, diseño de bases de datos, creación de APIs con Springboot.
3. De las principales características a mejorar es la gestión de tareas y la asignación de las mismas, además de llevar un buen seguimiento del desarrollo y avance de los proyectos.
   

&nbsp;											PARTE II

Acuerdo de Trabajo en Equipo

Compromisos y practicas colaborativas para el semestre

Este documento recoge los acuerdos concretos que como equipo adoptamos para organizar nuestro trabajo durante el semestre. No es una lista de buenas intenciones: es un contrato interno que describe exactamente como vamos a operar, como vamos a tomar decisiones y que hacemos cuando algo falla. Fue construido colectivamente y aplica por igual para los cuatro integrantes.

La carga de trabajo acordada es de 12 horas semanales por persona, distribuidas de forma planificada y no acumulada sobre los dias de entrega.





1\. Organizacion de tareas: tablero Kanban con ciclos de Scrum

Combinamos Kanban y Scrum: usamos un tablero visual tipo Kanban para el estado de cada tarea, pero organizamos el trabajo en sprints semanales con una reunion de planeacion al inicio y una revision al final.

Estructura del tablero

El tablero tendra cinco columnas fijas:

Backlog: todo lo identificado pero no priorizado aun.

Por hacer (Sprint actual): tareas comprometidas para esta semana.

En progreso: tareas que alguien esta trabajando activamente. Maximo 2 por persona simultaneamente.

En revision: tareas terminadas que esperan que otro integrante las valide antes de cerrarlas.

Hecho: tareas completadas y validadas.



La herramienta principal sera GitHub Projects, vinculada directamente al repositorio del proyecto. Cada tarea es una tarjeta con: descripcion clara, responsable asignado, fecha limite y etiqueta de tipo (feature, bug, docs, investigacion).

Reglas del tablero

Nadie puede tener mas de 2 tarjetas en 'En progreso' al mismo tiempo.

Una tarea solo pasa a 'Hecho' cuando otro integrante distinto al responsable la reviso y aprobo.

Toda tarea nueva que surja durante la semana se agrega al Backlog antes de asignarse.

El tablero se revisa y actualiza antes de cada reunion de equipo, no despues.





2\. Frecuencia y formato de reuniones

Reunion semanal de sprint (lunes o martes, max. 45 min)

Estructura fija:

10 min: revision del sprint anterior. Que se completo, que no y por que.

25 min: planeacion del sprint nuevo. Asignacion de tareas, estimacion de tiempo y aclaraciones.

10 min: identificacion de bloqueos o dependencias entre tareas.



Esta reunion es obligatoria. Si alguien no puede asistir, debe enviar su reporte escrito al canal del equipo antes de que empiece.

Sincronizacion de mitad de semana (jueves, max. 15 min)

Por videollamada o mensaje de voz. Sirve unicamente para desatascar bloqueos o ajustar prioridades si algo cambio. No es para reportar avances; eso se hace actualizando el tablero.





3\. Reglas de uso de Git y GitHub

El repositorio es el centro del trabajo tecnico. Las siguientes reglas aplican sin excepcion, independientemente de la urgencia.

Estructura de ramas

main: rama de produccion. Solo recibe merges desde develop mediante Pull Request aprobado.

develop: rama de integracion. Es la base desde donde cada integrante crea sus ramas de trabajo.

Ramas de trabajo: se crean desde develop con el formato feature/nombre-corto, fix/nombre-corto o docs/nombre-corto segun el tipo de cambio.

Flujo de trabajo obligatorio

Prohibido hacer commits directos a main o develop. Todo cambio entra por rama propia.

Antes de abrir un Pull Request, la rama debe estar actualizada con develop (git pull origin develop).

Todo Pull Request requiere minimo una aprobacion de otro integrante antes de hacer merge.

Los mensajes de commit deben ser descriptivos: 'Agrega validacion de formulario de login', no 'fix' ni 'cambios'.

No se hace merge de un PR si hay conflictos sin resolver o si la descripcion del PR esta vacia.

Revision de Pull Requests

El revisor tiene maximo 24 horas para aprobar o pedir cambios. Si no responde en ese tiempo, el autor puede pedir a otro integrante que revise. La revision incluye: leer el codigo, verificar que cumple lo descrito en la tarea del tablero, y dejar al menos un comentario (asi sea de aprobacion).





4\. Compromisos de comunicacion y cumplimiento

Cuando alguien no puede cumplir una tarea

El compromiso base es avisar con al menos 24 horas de anticipacion si se sabe que una tarea no va a estar lista. Si el bloqueo es inesperado (enfermedad, emergencia), se avisa tan pronto como sea posible.

El aviso debe incluir: cual es la tarea, por que no puede entregarse y una propuesta de nueva fecha o de quien podria apoyar.

No avisar o avisar despues del plazo sin justificacion se registra en el acta de la reunion siguiente como incumplimiento.

Dos incumplimientos sin aviso en el semestre activan una conversacion formal para revisar la distribucion de responsabilidades.

Canal de comunicacion

WhatsApp (o el canal acordado) es para coordinacion rapida y urgencias. Las decisiones formales, cambios de alcance y acuerdos importantes se escriben siempre en el acta de reunion o como comentario en la tarea del tablero, nunca solo en chat.





5\. Como se toman decisiones en el equipo

Decisiones tecnicas cotidianas

Las decide la persona responsable de esa tarea, con libertad de consultar al equipo si tiene dudas. No requieren aprobacion grupal.

Decisiones de diseno o arquitectura que afecten a mas de uno



