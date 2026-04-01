---
title: Lab - Identificar Amenazas de Inteligencia Relevantes

---

# Lab - Identificar Amenazas de Inteligencia Relevantes
Objetivos
Parte 1: Investigar las CVE de MITRE

Parte 2: Acceder a la base de conocimientos MITRE ATT & CK

Parte 3: Investigar posible malware

Trasfondo/Situación
Usted ha sido contratado como analista de ciberseguridad de nivel 1 por XYZ, Inc. Los analistas de nivel 1 generalmente son responsables de responder a los tickets entrantes y las alertas de seguridad. En esta práctica de laboratorio, realizará una investigación de amenazas de inteligencia para varios escenarios que han afectado a XYZ, Inc. Cada escenario requerirá que acceda a sitios web de amenazas de inteligencia y responda preguntas sobre la amenaza encontrada en el escenario.

Recursos necesarios
=  1 computadora con acceso a Internet

Instrucciones
Parte 1: Investigación de CVE MITRE
La organización MITRE creó la base de datos de vulnerabilidades y exposiciones comunes (CVE) en 1999 para identificar, definir y clasificar vulnerabilidades de ciberseguridad divulgadas públicamente. Fue avalado por el Instituto Nacional de Normas y Tecnología (NIST) La base de datos de CVE ahora es el método estándar de registro e identificación de vulnerabilidades.

En esta parte, investigará el programa CVE y utilizará la lista de CVE para identificar amenazas.

Paso 1: Investigar el sitio web de CVE.
Vaya a https://cve.mitre.org y vaya a la página About > Terminology para responder las siguientes preguntas.

Preguntas:
¿Qué es el programa CVE?

Área de respuesta
Escriba sus respuestas aquí.
El programa CVE es un esfuerzo internacional impulsado por la comunidad para clasificar vulnerabilidades de acuerdo con las reglas y pautas del esfuerzo.

Ocultar respuesta
¿Qué es una autoridad de numeración CVE (CNA)?

Área de respuesta
Escriba sus respuestas aquí.
AC NA es una organización responsable de la asignación regular de ID de CVE a las vulnerabilidades y de crear y publicar información sobre la vulnerabilidad en el registro de CVE asociado. Cada CNA tiene una responsabilidad específica de identificación y publicación de vulnerabilidades.

Ocultar respuesta
¿Qué es un Publicador de Datos Autorizado (ADP)?

Área de respuesta
Escriba sus respuestas aquí.
Un ADP es una organización autorizada dentro del programa CVE para enriquecer un registro de CVE publicado previamente por un CNA con información adicional relacionada que incluye puntuaciones de riesgo (por ejemplo, Sistema de Puntuación de Vulnerabilidad Común (CVSS), listas de productos afectados y versiones).

Ocultar respuesta
¿Qué es la Lista de CVE?

Área de respuesta
Escriba sus respuestas aquí.
La lista de CVE es un catálogo de búsqueda de todos los registros de CVE identificados o informados por el programa de CVE.

Ocultar respuesta
¿Qué es un Registro de CVE?

Área de respuesta
Escriba sus respuestas aquí.
El registro de CVE son los datos descriptivos sobre una vulnerabilidad asociada con una ID de CVE, proporcionada por un CNA y enriquecida por los ADP. Estos datos se proporcionan en múltiples formatos legibles por humanos y máquinas. Un registro de CVE está asociado a uno de los siguientes estados: reservado, publicado y rechazado.

Ocultar respuesta
¿Qué es una ID de CVE?

Área de respuesta
Escriba sus respuestas aquí.
Un identificador alfanumérico exclusivo asignado por el programa CVE. Cada identificador hace referencia a una vulnerabilidad específica. Una ID de CVE permite que la automatización y varias partes debatan, compartan y correlacionen información sobre una vulnerabilidad específica, sabiendo que se refieren a lo mismo.

Ocultar respuesta
Paso 2: Investigar las CVE en el sitio web de Avisos de Seguridad de Cisco.
Muchos sitios de seguridad y software hacen referencia a CVE. Por ejemplo, el sitio web de cisco.com proporciona avisos de seguridad de Cisco que identifican las vulnerabilidades asociadas con los productos de Cisco. En este paso, se referirá a este sitio web para identificar una ID de CVE.

a.  Deje abierto el sitio web cve.mitre.org. En otra pestaña del navegador, busque en Internet Cisco Security Advisories (Avisos de Seguridad de Cisco) y haga clic en el enlace para ir a la página web tools.cisco.com.

b.  Esta página enumera todas las CVE conocidas actualmente. Para la columna Impact (Impacto), haga clic en la flecha hacia abajo y desmarque todo excepto Critical (Crítico), y luego haga clic en Done (Listo).

c.  Elija uno de los avisos y responda las siguientes preguntas sobre el asesoramiento seleccionado.

Preguntas:
¿Cuál es el nombre del aviso que eligió?

Área de respuesta
Escriba sus respuestas aquí.
El nombre aparece en la primera columna. Por ejemplo, "Cisco Small Business RV110W, RV130, RV130W, and RV215W Routers Remote Command Execution and Denial of Service Vulnerability"

Ocultar respuesta
¿Cuál es la ID de CVE? Utilizará esta ID en el próximo paso.

Área de respuesta
Escriba sus respuestas aquí.
La ID de CVE aparece en la tercera columna. Por ejemplo, la ID de CVE para " Cisco Small Business RV110W, RV130, RV130W, and RV215W Routers Remote Command Execution and Denial of Service Vulnerability" es CVE-2021-34730.

Ocultar respuesta
d.  Puede hacer clic en el aviso para ir a la página de detalles o hacer clic en la flecha hacia abajo junto al nombre del aviso para obtener más información.

Pregunta:
¿Hay alguna solución temporal para el aviso que eligió?

Área de respuesta
Escriba sus respuestas aquí.
>La respuesta probablemente sea "No".

Ocultar respuesta
Paso 3: Regresar al sitio web de CVE e investigue más sobre su Cisco CVE elegido.
a.  Vuelva al sitio web cve.mitre.org, que aún debe estar abierto en una pestaña del navegador.

b.  Haga clic en Search CVE List (Buscar lista de CVE) para abrir un cuadro de búsqueda.

c.  En el campo de búsqueda, introduzca la ID de CVE para el aviso crítico que documentó en el paso anterior. La ID de CVE tiene el siguiente formato: CVE- [año] - [número_ID].

Pregunta:
Describa brevemente la vulnerabilidad.

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas variarán según la CVE que se haya elegido. Por ejemplo, CVE-2021-34730 describe una vulnerabilidad en el servicio Universal Plug-and-Play (UPnP) de Cisco Small Business Routers (Enrutadores para Pequeños Negocios) que podría permitir que un atacante remoto no autenticado cree una condición de denegación de servicio (DoS). Tenga en cuenta que esta es la misma información que puede encontrar en los detalles de este aviso en el sitio web de Avisos de Seguridad de Cisco.

Ocultar respuesta
Parte 2: Acceder a la base de conocimientos MITRE ATT & CK
El marco de tácticas adversariales, técnicas y conocimiento común (ATT&CK) de MITRE permite detectar tácticas, técnicas y procedimientos del atacante como parte de la defensa de amenazas y la atribución de ataques. En esta parte, investigará el sitio web de MITER ATT & CK para responder preguntas.

Paso 1: Vaya al sitio web de MITER ATT & CK.
Vaya al sitio web https://attack.mitre.org.

La página muestra una matriz de ataque para empresas que identifica diversas tácticas y técnicas utilizadas por los agentes de amenazas. Las tácticas son los títulos de las columnas del encabezado (ej., Reconocimiento, desarrollo de recursos, etc.) con las técnicas enumeradas a continuación. Una frase corta para cada técnica resume lo que un agente de amenazas podría hacer para ejecutar un ataque. Al hacer clic en la frase vinculada, accederá a una página para obtener información detallada sobre las técnicas y los métodos de mitigación.

Nota: Es posible que deba ampliar el ancho de la ventana del navegador para ver las 14 tácticas. Alternativamente, puede mantener presionada la tecla Mayús y desplazar la rueda del mouse para desplazar la ventana hacia la izquierda y la derecha.

Esta matriz es un excelente lugar para aprender más sobre las diferentes tácticas y técnicas que los agentes de amenazas utilizan para comprometer los sistemas. Los analistas de ciberseguridad visitan regularmente este sitio para investigar ataques específicos y posibles mitigaciones.

Paso 2: Investigar la táctica de reconocimiento y la táctica de suplantación de identidad para obtener información.
Utilice la página MITER ATT & CK para responder las siguientes preguntas.

Preguntas:
¿Cuántas técnicas se atribuyen a la táctica de reconocimiento?

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar, pero en el momento de escribir este artículo, había 10 técnicas bajo la táctica de reconocimiento.

Ocultar respuesta
En Reconocimiento, haga clic en Suplantación de identidad para obtener información y lea la descripción. Describa brevemente cómo un agente de amenazas podría recopilar información de reconocimiento mediante técnicas de suplantación de identidad (phishing).

Área de respuesta
Escriba sus respuestas aquí.
Los adversarios pueden enviar mensajes de suplantación de identidad para obtener información confidencial que puede utilizarse durante la focalización. Todas las formas de suplantación de identidad son ingeniería social que se envía electrónicamente. La suplantación de identidad (phishing) puede ser un objetivo, conocido como suplantación de identidad donde el adversario apuntará a un individuo, una empresa o un sector específicos.

Ocultar respuesta
Expanda el menú desplegable debajo del encabezado de suplantación de identidad para información o consulte el menú a la izquierda. ¿Cuáles son las sub-técnicas utilizadas al suplantar la información?

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas deben ser Spearphishing Service, Spearphishing Attachment y Spearphishing Link.

Ocultar respuesta
¿Qué medidas podría tomar para mitigar estas técnicas?

Área de respuesta
Escriba sus respuestas aquí.
Configuración de software mediante la suplantación de identidad y autenticación de correo electrónico para filtrar mensajes y capacitación de usuarios para identificar ataques de ingeniería social.

Ocultar respuesta
Paso 3: Investigar la táctica de Comando y Control y la técnica de Codificación de Datos.
Utilice la página MITER ATT & CK para responder las siguientes preguntas.

Nota: Comando y Control es la táctica número 12 en la matriz. Es posible que deba ampliar el ancho de la ventana del navegador para verla. Alternativamente, puede mantener presionada la tecla Mayús y desplazar la rueda del mouse para desplazar la ventana hacia la izquierda y la derecha.

Preguntas:
¿Cuántas técnicas se atribuyen a la táctica de Comando y Control?

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar, pero en el momento de escribir este artículo había 16 técnicas disponibles.

Ocultar respuesta
En Comando y Control, haga clic en Codificación de Datos y lea la descripción. Describa brevemente cómo un agente de amenazas podría utilizar la codificación de datos para Comando y Control.

Área de respuesta
Escriba sus respuestas aquí.
Los actores de amenazas pueden codificar datos para hacer que el contenido del tráfico de Comando y Control sea más difícil de detectar. La información de Comando y Control (C2) puede codificarse mediante un sistema de codificación de datos estándar (p. Ej., ASCII, Unicode, Base64, MIME) y en compresión de datos (ej., Gzip).

Ocultar respuesta
¿Qué podría hacer para mitigar esta técnica?

Área de respuesta
Escriba sus respuestas aquí.
Los sistemas de prevención y detección de intrusiones (IDS/IPS) en la red que utilizan firmas / reglas de red para identificar el tráfico de malware adverso específico se pueden utilizar para mitigar la actividad a nivel de la red.

Ocultar respuesta
Paso 4: Investigar la táctica de impacto
Utilice la página MITER ATT & CK para responder las siguientes preguntas.

Nota: La táctica de Impacto es la última táctica en el extremo derecho de la matriz.

Preguntas:
¿Cuántas técnicas se atribuyen a la táctica del Impacto?

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas pueden variar, pero en el momento de escribir este artículo había 13 técnicas disponibles.

Ocultar respuesta
En Impacto, haga clic en Limpiar disco y lea la descripción. Describa brevemente el impacto si un agente de amenazas limpia un disco?

Área de respuesta
Escriba sus respuestas aquí.
Las respuestas variarán. Los adversarios pueden borrar o corromper datos de discos sin procesar en sistemas específicos para interrumpir la disponibilidad del sistema y los recursos de red. El malware utilizado para borrar discos puede tener características similares a gusanos para propagarse a través de una red mediante técnicas adicionales.

Ocultar respuesta
¿Qué podría hacer para mitigar esta técnica?

Área de respuesta
Escriba sus respuestas aquí.
Implemente un plan de recuperación tras un desastre de TI que contenga procedimientos para realizar copias de respaldo periódicas de datos que puedan utilizarse para restaurar los datos de la organización. Garantizar que las copias de respaldo se almacenen fuera del sistema y que estén protegidas de los métodos comunes que los adversarios pueden utilizar para obtener acceso y destruir las copias de respaldo a fin de evitar la recuperación.

Ocultar respuesta
Parte 3: Investigar posible malware
Hay un número de herramientas que un analista de ciberseguridad puede utilizar para validar software malicioso. En esta parte, investigará una alerta de IPS para ver si se trata de software malicioso.

Paso 1: Generar un hash SHA256 para un archivo sospechoso.
Como analistas de ciberseguridad de nivel 1, tiene acceso a un sistema de administración de eventos de información de seguridad (SIEM) en su estación de administración de Linux. El SIEM acaba de enviarle una alerta de IPS que hace referencia a una dirección IP local del 10.8.19.101. Decide examinar el tráfico real identificado en la alerta utilizando Wireshark.

a.  A medida que se desplaza por las distintas capturas de paquetes de la dirección IP 10.8.19.101, observa que el host descargó un archivo, como se muestra en la figura.

La figura muestra un archivo pcap de Wireshark. Se selecciona un paquete de solicitud HTTP GET para la dirección de origen 10.8.19.101. En el panel Detalles del paquete, el URI para la solicitud GET es http://185.244.41.29/ooiwy.pdf
b.  Decide exportar este archivo desde Wireshark para el análisis de malware mediante el comando File > ExportObjects > HTTP y guardar el archivo con el nombre ooiwy.pdf.

c.  A continuación, generará el valor hash SHA256 del archivo guardado con el comando sha256sum como se muestra.

[analyst@secOps ~]:~$ sha256sum ooiwy.pdf

f25a780095730701efac67e9d5b84bc289afea56d96d8aff8a44af69ae606404 ooiwy.pdf

Observe la firma de hash SHA256 que se generó. Esta cadena se puede validar en varios sitios de reputación de archivos para ver si el archivo es malware.

Paso 2: Buscar el hash en los sitios web de reputación de archivos.
Hay varios sitios de reputación de archivos que pueden utilizarse para investigar este archivo. En este paso, utilizará el sitio web Talos de Cisco y virustotal.com.

a.  Busque "Cisco Talos" y haga clic en el primer enlace para acceder al sitio web de Cisco Talos Intelligence Group.

b.  Busque los menús en la parte superior y sobre el Reputation Center (Centro de reputación) para desplegar un submenú. Haga clic en el enlace de la página de búsqueda Talos File Reputation (Reputación de Archivos de Talos).

c.  Copie el valor hash de SHA resaltado del paso anterior y péguelo en la ventana de búsqueda. Haga clic en la casilla de verificación “I’m not a robot” y luego haga clic en Buscar.

d.  Revise la información de este archivo.

Preguntas:
¿Cuál es la puntuación de reputación de archivos ponderados de Talos? ¿Es eso bueno o malo?

Área de respuesta
Escriba sus respuestas aquí.
Puede colocar el mouse sobre el ? para saber que la puntuación es una escala de 1 a 100. La puntuación del archivo es 100, lo que identifica este archivo como extremadamente malicioso.

Ocultar respuesta
e.  Busque y navegue hasta el sitio web de VirusTotal.

f.  Haga clic en Buscar, pegue el hash SHA256 en el campo y presione Intro. La página muestra todos los proveedores de seguridad que han identificado este archivo como malicioso (a la izquierda) y los nombres que estas empresas utilizan para identificar el archivo malicioso.

g.  Observe los encabezados de columna DETECTION, DETAILS, RELATIONS, BEHAVIOR, y COMMUNITY. Utilice la información de la página DETAILS para responder las siguientes preguntas.

Preguntas:
¿Cuándo fue creado este archivo?

Área de respuesta
Escriba sus respuestas aquí.
Creation Time  2021-07-06 13:28:40

Ocultar respuesta
¿Con qué otros nombres se conoce el archivo además de ooiwy.pdf?

Área de respuesta
Escriba sus respuestas aquí.
RegistryDemo, RegistryDemo.EXE, cdnupdaterapi.png, and ooiwy.pdf.exe

Ocultar respuesta
¿Cuál es la máquina de destino?

Área de respuesta
Escriba sus respuestas aquí.
Procesadores Intel 386 o procesadores posteriores compatibles.