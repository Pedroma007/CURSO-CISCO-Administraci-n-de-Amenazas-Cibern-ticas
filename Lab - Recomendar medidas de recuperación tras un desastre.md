---
title: Lab - Recomendar medidas de recuperación tras un desastre

---

# Lab - Recomendar medidas de recuperación tras un desastre
Objetivos
Parte 1: Desastres naturales

Parte 2: Ataque DDoS

Parte 3: Pérdida de Datos

Trasfondo/Situación
Cada organización debe estar preparada para un desastre. La capacidad de recuperarse de un desastre puede determinar la supervivencia del negocio. Un desastre puede ser un huracán o un tifón, una falla de hardware, una pérdida de datos o un ataque cibernético devastador.

Un plan de recuperación tras un desastre incluirá políticas y procedimientos que la organización siga cuando se interrumpan los servicios de TI.

En el plan, debe tener en cuenta las personas, los servicios y los equipos relacionados con TI, y las ubicaciones físicas de la empresa. También debe tener en cuenta los objetivos de punto de recuperación (RPO) y los objetivos de tiempo de recuperación (RTO).

En esta práctica de laboratorio, recomendará medidas de recuperación tras un desastre natural, una falla del equipo en el centro de datos, un ataque DDoS o la pérdida de datos para un servicio de tutoría.

En este negocio, hay estudiantes de diferentes ubicaciones geográficas que requieren clases particulares para diferentes asignaturas, como matemáticas e idiomas. Los estudiantes tienen acceso a un currículum en línea que les proporciona materiales complementarios según sus necesidades. Los estudiantes también pueden inscribirse para recibir asistencia personal de instructores para servicios de tutoría individual o en grupos pequeños programados. El negocio tiene algunas ubicaciones físicas que los clientes potenciales pueden visitar y utilizar los servicios de tutoría en persona. La empresa ofrece servicios a sus clientes desde un centro de datos en la nube cercano. El centro de datos ofrece contenido instructivo, registros de estudiantes, registro para servicios y videoconferencias en tiempo real para la instrucción directa. Otras prácticas empresariales de enrutamiento, como las copias de respaldo de los servidores empresariales in situ, se manejan en el centro de datos.

Recursos necesarios
=  Dispositivo con acceso a Internet

Instrucciones
Parte 1: Desastres naturales
Un huracán, un tifón, golpeó a su comunidad y causó daños cerca de un centro de datos. La infraestructura de red en el área también ha sufrido daños.

El daño cerca del centro de datos ha provocado una interrupción de la red y los servidores del centro de datos ya no son accesibles de forma remota. Debido al daño extenso en la comunidad, puede llevar algunos días completar una evaluación exhaustiva de daños. Puede suponer que no hay acceso a este centro de datos durante al menos una semana.

Paso 1: Identificar los riesgos potenciales.
Preguntas:
Responda las siguientes preguntas:

¿Puede la empresa operar sin acceso a este centro de datos? Explique.

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar. El negocio tendrá funciones limitadas solo en las ubicaciones físicas. La empresa requiere acceso a los servidores dentro del centro de datos de forma remota. Sin ellos, el negocio no puede funcionar porque los clientes no pueden acceder a los servicios de tutoría y al contenido en línea. Además, los instructores no pueden proporcionar tutoría y no pueden acceder a la información del alumno de forma remota.

Ocultar respuesta
¿Pueden los estudiantes acceder a sus materiales en línea? Explique.

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar. Los estudiantes no podrán acceder a los materiales en línea si todos los materiales se encuentran en el mismo centro de datos inaccesible.

Ocultar respuesta
¿Hay otras maneras en que los instructores pueden proporcionar los servicios de tutoría? Explique.

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar. Los instructores aún pueden proporcionar servicios si pueden conectarse con los estudiantes a través de aplicaciones de reuniones proporcionadas por otros proveedores en línea.

Ocultar respuesta
¿Pueden los nuevos usuarios suscribirse a los servicios de tutoría? Explique.

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar. Los nuevos usuarios no pueden utilizar el servicio si no pueden acceder a la base de datos de usuarios en línea de la empresa que se encuentra en el centro de datos inaccesible.

Ocultar respuesta
¿Pueden los empleados acceder a información interna de la empresa durante la recuperación?

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar. Los empleados no pueden acceder a la información interna si los servidores internos también se encuentran en el mismo centro de datos.

Ocultar respuesta
Paso 2: Recomendar un plan de recuperación tras un desastre.
En función de sus respuestas en el paso anterior, enumere sus recomendaciones a continuación:

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas varían. Este negocio no puede funcionar correctamente sin acceso a su base de datos de usuarios y currículum en línea. Una ubicación de respaldo debe contener una copia de respaldo actualizada de los datos esenciales. En caso de que el centro de datos actual sea inaccesible, una ubicación de respaldo debe estar en línea y proporcionar los servicios esenciales.

Copia de respaldo actual de la base de datos de usuarios y currículum en línea.
Ubicación física secundaria con un ISP diferente.
La ubicación de respaldo debe estar disponible en un corto período de tiempo durante la recuperación
Acceso al servidor interno para empleados para obtener información actualizada durante la recuperación
Copia local del plan de recuperación tras un desastre
Ocultar respuesta
Parte 2: Ataque DDoS
Algunos usuarios han informado que no pueden iniciar sesión en sus cuentas y acceder al currículum en línea. Tras una investigación más profunda, parece que el servidor web está sobrecargado por las solicitudes en un momento en que normalmente hay poco tráfico. Parece que el servidor está sufriendo un ataque de denegación de servicio.

Paso 1: Identificar los posibles problemas.
preguntas:
Responda las siguientes preguntas:

¿Puede la empresa operar sin acceso al centro de datos? Explique.

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas variarán. La empresa requiere acceso a los servidores del centro de datos de manera remota. Sin acceso, la empresa no puede funcionar porque los clientes no pueden acceder a los servicios de tutoría y al contenido en línea. Además , los instructores no pueden proporcionar tutoría ni acceder a la información de los estudiantes.

Ocultar respuesta
¿Puede la empresa seguir funcionando sin acceso al centro de datos? Explique.

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar. El negocio tiene una función limitada si solo las ubicaciones físicas con personal pueden proporcionar los servicios de tutoría.

Ocultar respuesta
¿Pueden los estudiantes acceder a sus materiales en línea? Explique.

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar. Los estudiantes no pueden acceder a sus materiales en línea porque el acceso a los servidores en el centro de datos no está disponible.

Ocultar respuesta
¿Pueden los instructores seguir ofreciendo los servicios de tutoría? Explique.

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar. Los instructores aún pueden proporcionar servicios si ellos pueden conectarse con sus estudiantes a través de aplicaciones de reuniones proporcionadas por otros proveedores en línea.

Ocultar respuesta
¿Pueden los nuevos usuarios suscribirse a los servicios de tutoría? Explique.

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar. Los nuevos usuarios no pueden utilizar el servicio si no pueden acceder a la base de datos o al currículum en línea de usuarios de la empresa.

Ocultar respuesta
¿Pueden los empleados acceder a información interna de la empresa durante la recuperación?

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar. Los empleados no tienen acceso a información interna durante la recuperación.

Ocultar respuesta
Paso 2: Recomendar un plan de recuperación.
En función de sus respuestas en el paso anterior, enumere sus recomendaciones a continuación:

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas varían. Este negocio no puede funcionar sin acceso a su base de datos de usuarios y su currículum en línea. En caso de un ataque:

Copia de respaldo actual de la base de datos del usuario, currículum en línea en una ubicación física diferente
Copias de respaldo de los servidores que pueden implementarse según sea necesario
Cada empleado debe tener una copia local del plan de recuperación tras un desastre
Identificación y prueba de servicios de comunicación alternativos a los alojados en el centro de datos
Ocultar respuesta
Parte 3: Pérdida de Datos
Los usuarios informaron que no pueden iniciar sesión en sus cuentas ni restablecer sus credenciales. Otros usuarios han informado que pudieron iniciar sesión, pero falta su progreso reciente en sus clases. Después de una investigación más profunda, parece que la pérdida de datos fue causada por un error humano.

Paso 1: Identificar los posibles problemas.
preguntas:
Responda las siguientes preguntas:

¿Puede la empresa operar con la pérdida de datos? Explique.

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar. Depende del grado de pérdida de datos. El negocio debe poder continuar con posibles limitaciones.

Ocultar respuesta
¿Pueden los estudiantes acceder a sus materiales en línea? Explique.

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar. Los estudiantes solo pueden acceder a sus materiales en línea si sus materiales en línea no son parte de los datos perdidos y sus cuentas pueden restaurarse.

Ocultar respuesta
¿Pueden los instructores seguir ofreciendo los servicios de tutoría? Explique.

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar. Los instructores solo pueden acceder a sus materiales en línea si sus materiales en línea no son parte de los datos perdidos.

Ocultar respuesta
¿Pueden los nuevos usuarios suscribirse a los servicios de tutoría? Explique.

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar. Los nuevos usuarios pueden inscribirse si no acceden a la base de datos de usuarios o al currículum en línea de la empresa que forma parte de la pérdida de datos.

Ocultar respuesta
¿Pueden los empleados acceder a información interna de la empresa durante la recuperación?

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar. Los empleados tienen acceso a la información interna durante la recuperación si no forma parte de la pérdida de datos.

Ocultar respuesta
Paso 2: Recomendar un plan de recuperación.
En función de sus respuestas en el paso anterior, enumere sus recomendaciones a continuación:

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas varían. La empresa debe contar con copias de respaldo diarias de todos los datos esenciales, como la base de datos de usuarios. Es posible que sea necesario realizar varias copias de respaldo de los datos en diferentes incrementos de tiempo, ya que los datos en buen estado podrían estar en una copia de respaldo anterior solamente.

Por ejemplo, los datos fueron dañados por la inserción de código malicioso por un atacante hace 2 días. La empresa mantiene copias de seguridad diarias completas durante siete días. Los datos dañados se pueden recuperar de la copia de seguridad que tiene 3 días. Sin embargo, por el uso de una copia de respaldo anterior se están perdiendo los datos de los últimos dos días. Por otro lado, si los datos dañados se pueden identificar y recuperar de las copias de seguridad, la pérdida de datos se puede minimizar si solo los datos dañados se reemplazan gradualmente de las copias de seguridad.

Además, la vulnerabilidad de software y los ataques maliciosos también pueden causar la pérdida de datos, además de errores humanos y sabotaje.

Conservar varias copias de las copias de respaldo realizadas en diferentes intervalos de tiempo
Software antimalware
Mantener el software actualizado
Cada empleado debe tener una copia local del plan de recuperación tras un desastre
Capacidad de restauración rápida de datos en equipos redundantes
Ocultar respuesta
Reflexión
1.  Estos casos indican requisitos de recuperación tras un desastre que son comunes a muchas empresas que utilizan centros de datos externos. ¿Qué se debe incluir en los planes de recuperación tras un desastre para muchos de estos negocios?

Área de respuesta
Escriba sus respuestas aquí.
Una cosa que es muy importante es que las operaciones de datos esenciales se alojen fuera del sitio en un centro de datos. Debido a que ese centro de datos puede ser inalcanzable, el servidor debe reflejar los datos entre dos o más centros de datos. De esta manera, se pueden crear servidores virtuales en el centro de datos de respaldo para que las operaciones comerciales se puedan restaurar lo antes posible. Es de importancia adicional, ya que la copia de respaldo más reciente puede no incluir datos dañados o últimos datos que las copias de respaldo se archiven por un período de tiempo, para que la última copia de respaldo válida pueda restaurarse.

Ocultar respuesta
2.  Ahora que ha examinado algunos escenarios y proporcionado algunas posibles medidas de recuperación tras un desastre, ¿qué otras recomendaciones prácticas son esenciales para una recuperación tras un desastre exitosa?

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar. Para que un plan de recuperación sea exitoso, se deben asignar personas responsables para liderar el proceso de recuperación y llevar a cabo las medidas de recuperación. El plan debe probarse si es posible y todos los empleados deben estar capacitados en el proceso de recuperación y saber qué hacer en caso de un desastre. El plan debe estar disponible para todos los empleados y actualizarse según sea necesario.