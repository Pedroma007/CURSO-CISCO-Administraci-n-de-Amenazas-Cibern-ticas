---
title: Lab - Evaluación de vulnerabilidades

---

# Lab - Evaluación de vulnerabilidades
Objetivos
En esta práctica de laboratorio, revisaremos las características de un ejemplo de informe de vulnerabilidad de pruebas penetrantes.

Parte 1: Aprenda sobre los creadores de un informe de evaluación de vulnerabilidad

Parte 2: Revisar las secciones del informe

Trasfondo/Situación
Las evaluaciones de vulnerabilidad pueden ser realizadas internamente o por contratistas externos. Las evaluaciones de vulnerabilidad generalmente están automatizadas. Los hosts de red accesibles se identifican y luego se analizan con herramientas de evaluación de vulnerabilidades. El análisis crea muchos datos que asignan las direcciones IP del host a las vulnerabilidades detectadas. A partir de estos datos, se pueden crear datos de resumen y visualizaciones para simplificar la interpretación del informe.

Cuando se identifican, las vulnerabilidades a menudo se clasifican por gravedad, a menudo utilizando un medio estándar para hacerlo, como CVSS. Además, a menudo se proporciona información de referencia para permitir una investigación más profunda si es necesario. Por lo general, se proporciona un número de CVE que es fácil de investigar más a fondo.

El informe puede sugerir técnicas de mitigación comunes que proporcionan orientación al personal de ciberseguridad sobre cómo eliminar las vulnerabilidades que se han identificado.

Recursos necesarios
=  Computadora con acceso a Internet

=  Ejemplo de informe de evaluación de vulnerabilidad

Instrucciones
Parte 1: Aprenda sobre los creadores de un informe de evaluación de vulnerabilidad
Paso 1: Investigue el origen del informe.
El informe que utilizaremos para este laboratorio fue creado por el servicio de Higiene Cibernética de NCATS.

Investigue NCATS en Internet y responda las siguientes preguntas.

Preguntas:
¿Qué significa NCATS?

Área de respuesta
Escriba sus respuestas aquí.
National Cybersecurity Assessments and Technical Services (Evaluaciones Nacionales de Ciberseguridad y Servicios Técnicos)

Ocultar respuesta
¿Qué es el Servicio de Escaneo de Vulnerabilidades de Higiene Cibernética? Busque en la web para obtener más información.

Área de respuesta
Escriba sus respuestas aquí.
Es un servicio gratuito de evaluación de vulnerabilidades provisto por la Agencia de Ciberseguridad y Infraestructura (CISA) del Departamento de Seguridad Nacional de los Estados Unidos.

Ocultar respuesta
¿Qué otros servicios de ciberseguridad hay disponibles de NCATS?

Área de respuesta
Escriba sus respuestas aquí.
Además del análisis de vulnerabilidades de Higiene Cibernética, NCATS ofrece evaluación de campañas de suplantación de identidad, evaluación de riesgos y vulnerabilidades y revisión de diseño de arquitectura validada.

Ocultar respuesta
¿Para quién están disponibles estos servicios?

Área de respuesta
Escriba sus respuestas aquí.
Gobiernos federales, estatales, locales, tribales y territoriales, y organizaciones de infraestructura crítica del sector público y privado en los Estados Unidos.

Ocultar respuesta
Paso 2: Busque y abra el informe.
a.  El enlace al informe que revisaremos está directamente en la sección Higiene Cibernética: Escaneo de Vulneravilidad de la página de NCATS. Para acceder al enlace desde el motor de búsqueda de Google, ingrese lo siguiente: site: us-cert.cisa.gov/ CyHy

b.  Abra el informe y revise la tabla de contenido para tener una idea de lo que se incluye.

Parte 2: Revisar las secciones del informe
Las primeras dos secciones del informe explican su uso previsto y proporcionan una descripción general de alto nivel de los resultados del informe.

Paso 1: Revise la sección Cómo usar el informe.
Es importante comprender el uso previsto de cualquier informe de evaluación de seguridad. Un buen informe proporcionará pautas útiles y específicas para el uso de la evaluación.

Nota: Dado que este informe es un ejemplo, la organización para la que se preparó el informe se denomina Organización de muestra (muestra).

Revisen la sección uno del reporte y responda las siguientes preguntas.

Preguntas:
¿Cuál es el objetivo del informe?

Área de respuesta
Escriba sus respuestas aquí.
Para ayudar a las organizaciones a fortalecer su postura de seguridad.

Ocultar respuesta
¿En qué sección del informe puede encontrar una descripción general de alto nivel de los resultados de la evaluación, incluidas algunas comparaciones del rendimiento semanal?

Área de respuesta
Escriba sus respuestas aquí.
Informe de ciberseguridad

Ocultar respuesta
¿Dónde puede encontrar una lista detallada de resultados y recomendar mitigaciones para cada vulnerabilidad?

Área de respuesta
Escriba sus respuestas aquí.
Apéndice

Ocultar respuesta
¿Qué le permite abrir fácilmente los resultados del análisis en una hoja de cálculo u otro documento tabular?

Área de respuesta
Escriba sus respuestas aquí.
En el Apéndice G, se proporcionan archivos de valores separados por comas (CSV) para este propósito.

Ocultar respuesta
Paso 2: Revise la tarjeta de reporte de Higiene Cibernética.
Mire la tarjeta de reporte de Higiene Cibernética. Esto proporciona un resumen de alto nivel de los resultados de la evaluación. Esta organización se analiza semanalmente, por lo que se proporciona información de tendencias con los resultados del análisis actual.

Preguntas:
¿Qué porcentaje de los hosts analizados fue vulnerable? ¿Cómo se compara esto con el análisis anterior?

Área de respuesta
Escriba sus respuestas aquí.
Se encontró que el 10%, o 393, hosts eran vulnerables. Esto es 44 hosts menos que el análisis anterior.

Ocultar respuesta
Las vulnerabilidades se clasifican por gravedad. ¿Qué nivel de gravedad representa la mayor cantidad de hosts recientemente vulnerables?

Área de respuesta
Escriba sus respuestas aquí.
Se identificó recientemente que 108 hosts adicionales tenían vulnerabilidades de gravedad media.

Ocultar respuesta
¿Qué clase de vulnerabilidad requiere más tiempo para mitigar a la organización?

Área de respuesta
Escriba sus respuestas aquí.
A la organización le lleva un tiempo medio de 158 días mitigar una vulnerabilidad de nivel medio.

Ocultar respuesta
El análisis incluyó 293,005 direcciones IP, pero evaluó solo 3,986 hosts. ¿Por qué crees que es así?

Área de respuesta
Escriba sus respuestas aquí.
La organización de ejemplo proporcionó acceso a un espacio de direcciones de 293,005 direcciones, pero al momento del análisis, solo 3,986 estaban activas y accesibles para el análisis.

Ocultar respuesta
Paso 3: Revise el Resumen Ejecutivo.
Vaya al Resumen Ejecutivo Lea esta sección y responda las siguientes preguntas.

Preguntas:
¿Qué dos funciones principales incluyó la evaluación y qué hosts evaluó?

Área de respuesta
Escriba sus respuestas aquí.
La evaluación realizó mapeo de la red para identificar hosts y otra información, y la evaluación de la vulnerabilidad de los hosts con acceso a Internet que se encontraron durante el mapeo.

Ocultar respuesta
¿Cuántos tipos distintos de vulnerabilidades se identificaron?

Área de respuesta
Escriba sus respuestas aquí.
63

Ocultar respuesta
De las cinco vulnerabilidades principales por ocurrencia, ¿cuál era el protocolo o sistema común más vulnerable?

Área de respuesta
Escriba sus respuestas aquí.
Certificados SSL y conjuntos de cifrado.

Ocultar respuesta
De las cinco categorías principales por grado de riesgo, ¿qué vulnerabilidades parecen estar relacionadas con una pieza específica de hardware de red? ¿Cuál es el dispositivo?

Área de respuesta
Escriba sus respuestas aquí.
Sistema operativo MikroTik Router OS 6.41.3 SMB y servidor HTTP de MikroTik RouterOS arbitrario. Es un router MikroTik.

Ocultar respuesta
Busque en la Web en “MikroTik Router OS 6.41.3 SMB”. Busque la entrada de CVE para esta vulnerabilidad en el sitio web de la Base de Datos de Vulnerabilidad Nacional (NVD). ¿Cuál es la puntuación básica de CVSS y la calificación de gravedad?

Área de respuesta
Escriba sus respuestas aquí.
Puntuación básica de CVSS 9.8, calificación crítica (CVE-2018-7445).

Ocultar respuesta
Busque el informe de divulgación completo de esta CVE buscando en la web o haciendo clic en un enlace de referencia. En el informe de divulgación completo, ¿cuáles son dos formas de mitigar la vulnerabilidad?

Área de respuesta
Escriba sus respuestas aquí.
El informe completo de divulgación se encuentra en el sitio web de Seclists.org. El elemento 5 dice que el Sistema Operativo del router debe actualizarse a la versión 6.41.3 o superior, o el servicio de bloqueo de mensajes del servidor (SMB) debe estar deshabilitado.

Ocultar respuesta
¿Qué tipo de vulnerabilidad es esta y qué puede hacer un atacante cuando es explotado?

Área de respuesta
Escriba sus respuestas aquí.
Es un desbordamiento del búfer. Los atacantes podrían ejecutar fácilmente el código del sistema porque no es necesario autenticar al usuario para aprovecharlo.

Ocultar respuesta
¿Qué debe haber hecho la organización de muestra para evitar que esta vulnerabilidad crítica aparezca en su red?

Área de respuesta
Escriba sus respuestas aquí.
Deberían haber seguido los avisos de productos para su hardware de red. Después de informados sobre la vulnerabilidad, deberían haber actualizado la versión de RouterOS lo antes posible.

Ocultar respuesta
Paso 4: Revise la metodología y el proceso de evaluación.
Es importante evaluar la metodología utilizada para crear una evaluación de vulnerabilidades a fin de determinar la calidad del trabajo realizado. Revise el material en esa sección del informe.

Preguntas:
En la sección Proceso, el informe menciona una red IP desde la que se realizó el análisis. ¿Cuál es la red IP y para quién está registrada? ¿Por qué es importante decirle esto a la organización de muestra?

Área de respuesta
Escriba sus respuestas aquí.
64.69.57.0/24. Varios sitios de búsqueda de direcciones IP informan que esta red IP está registrada en el Departamento de Seguridad Nacional de los Estados Unidos. Debido a que el proceso de evaluación de vulnerabilidades realiza un análisis profundo de la red de la organización, esto podría interpretarse como un ataque de reconocimiento de un agente de amenazas. La organización podría intentar accidentalmente mitigar la amenaza bloqueando las direcciones IP en esa red en el perímetro de la red. Además, para que el análisis se realice correctamente, es posible que se deba permitir el acceso de las direcciones de esta red a través de un firewall para conexiones que se originan desde fuera de la red.

Ocultar respuesta
¿Qué califica a una computadora para ser designada como host para los efectos de este informe?

Área de respuesta
Escriba sus respuestas aquí.
Un host se definir como un dispositivo con una dirección que tiene al menos un servicio abierto o de escucha ejecutándose.

Ocultar respuesta
¿Qué herramienta utilizó el análisis para la asignación de red? ¿Qué herramienta se utilizó para la evaluación de vulnerabilidades?

Área de respuesta
Escriba sus respuestas aquí.
Nmap se utilizó para la asignación de red y Nessus para el análisis de vulnerabilidades.

Ocultar respuesta
¿Quién ofrece el producto Nessus y cuál es la limitación de la versión de descarga gratuita de Nessus?

Área de respuesta
Escriba sus respuestas aquí.
Tenable proporciona el producto Nessus. La versión gratuita se limita a escanear solo 16 direcciones IP.

Ocultar respuesta
¿Vulnerabilidades con qué rango de puntuaciones de CVSS se clasifican como de “alta” gravedad?

Área de respuesta
Escriba sus respuestas aquí.
Vulnerabilidades con una puntuación base de CVSS de 7,0 a 10,0

Ocultar respuesta
Paso 5: Investigar las vulnerabilidades detectadas.
Vaya a la sección 7 del informe y busque la Tabla 6. Los nombres de vulnerabilidad constan de una frase descriptiva estándar. Seleccione una descripción y búsquela en la Web. Debería ver un enlace a tenable.com para cada una de ellas. Tenable mantiene páginas de referencia para las vulnerabilidades que Nessus puede detectar.

a.   Abra la página de referencia de la vulnerabilidad y revise la información que le proporciona Tenable. Lea la sinopsis y la descripción de la vulnerabilidad. Algunas páginas de referencia proporcionan medidas de mitigación sugeridas.

b.   Seleccione tres de las vulnerabilidades de la lista de vulnerabilidades principales y repita este proceso. Revise la vulnerabilidad, el número de CVE, la descripción y las medidas de mitigación, si las hubiera. Investigue la vulnerabilidad si está interesado.

Paso 6: Investigar la mitigación de vulnerabilidades.
Vaya al apéndice C del informe. Se enumeran técnicas de mitigación para muchas de las vulnerabilidades detectadas. Responda las siguientes preguntas.

Preguntas:
¿Cuál es la dirección IP del host que ejecuta un servicio PHP vulnerable? ¿Por qué cree que esta vulnerabilidad existe en este host?

Área de respuesta
Escriba sus respuestas aquí.
x.x.124.231. El host requiere que su software se actualice. Aparentemente, la administración de parches y los servicios de actualización no se utilizan para el host.

Ocultar respuesta
¿Qué debe hacerse para mitigar esta vulnerabilidad?

Área de respuesta
Escriba sus respuestas aquí.
Actualice el software de servicio de PHP a la versión 5.6.34 o superior.

Ocultar respuesta
Hay muchos problemas asociados con SSL. ¿Cuáles son algunas de las medidas de mitigación recomendadas en el informe?

Área de respuesta
Escriba sus respuestas aquí.

Forzar el uso de SSL para algunos protocolos.
Comprar o generar certificados adecuados para los servicios.
Reemplazar los certificados vencidos.
Configurar las aplicaciones para utilizar cifrados de resistencia adecuados.
Reemplazar SSL 2.0 o 3.0 por TLS 1.1 o superior.
Ocultar respuesta
Preguntas de reflexión
1.  Describa la evaluación de vulnerabilidades que realizó el NCCIC, incluido cómo se realizó, las herramientas utilizadas y una breve descripción de los resultados.

Área de respuesta
Escriba sus respuestas aquí.
NCCIC ofrece un servicio gratuito de análisis de vulnerabilidades para organizaciones gubernamentales y privadas calificadas. El escaneo se realiza de forma remota y periódica. Los informes de resultados están disponibles para los beneficiarios. Los informes se pueden utilizar para detectar vulnerabilidades, preparar tendencias y actualizaciones semanales y orientar en la mitigación de vulnerabilidades. NCCIC utiliza Nmap para crear un mapa de red en el que se identifican los hosts y Nessus para analizar las vulnerabilidades de los hosts identificados. Los informes incluyen numerosos detalles, tablas y gráficos para ayudar a comunicar a los beneficiarios los problemas de seguridad en la red que requieren atención. Cada vulnerabilidad se clasifica por gravedad según su puntuación de CVSS.

Ocultar respuesta
¿Cómo son útiles los nombres de vulnerabilidad para futuras investigaciones?

Área de respuesta
Escriba sus respuestas aquí.
Los nombres de vulnerabilidad coinciden con una referencia mantenida por Tenable, la empresa que ofrece Nessus. La referencia de Tenable proporciona más detalles sobre las vulnerabilidades y, a menudo, proporciona enlaces a otras fuentes de información adicional. La referencia de Tenable también proporciona enlaces a especificaciones de CVE para la vulnerabilidad. Tenable también proporciona los vectores CVSS para la vulnerabilidad.

Ocultar respuesta
2.  Proporcione tres acciones que podría tomar según la información proporcionada en un informe de Higiene Cibernética.

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas varían. Algunos ejemplos son:

Utilice el informe para identificar vulnerabilidades críticas que deben abordarse de inmediato.
Identificar los hosts que requieren medidas de mitigación para abordar las vulnerabilidades, especialmente si se descubre que el host tiene múltiples vulnerabilidades.
Identificar las vulnerabilidades que comparten muchos hosts en la red.
Recomendar soluciones centralizadas, como sistemas de administración de parches para reducir la probabilidad de que aparezcan vulnerabilidades críticas o de alta gravedad en la red.