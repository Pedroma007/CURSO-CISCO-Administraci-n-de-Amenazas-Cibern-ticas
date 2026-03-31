---
title: Evaluacion de vulnerabilidades de terminales

---

# Evaluacion de vulnerabilidades de terminales
## Perfiles de la Red

![image](https://hackmd.io/_uploads/rkHmAiljbl.png)

![image](https://hackmd.io/_uploads/ryioRsgiZx.png)

Además, un perfil de los tipos de tráfico que normalmente entran y salen de la red es una herramienta importante para comprender el comportamiento de la red. El malware puede utilizar puertos inusuales que no suelen verse durante el funcionamiento normal de la red. El tráfico de host a host es otra métrica importante. La mayoría de los clientes de la red se comunican directamente con los servidores, por lo que un aumento del tráfico entre los clientes puede indicar que el malware se extiende lateralmente por la red.

Por último, otro indicador valioso son los cambios en el comportamiento de los usuarios, según lo indicado por AAA, los registros de servidor o un sistema de creación de perfiles de usuario (como Cisco Identity Services Engine [ISE]). Saber cómo utilizan habitualmente la red los usuarios permite detectar posibles riesgos en las cuentas de usuario. Un usuario que, de pronto, comienza a conectarse a la red en momentos extraños desde una ubicación remota, debe encender las alarmas si este comportamiento no es el habitual.

## Perfiles de Servidor

![image](https://hackmd.io/_uploads/B1wEM3goZg.png)

## Detección de Anomalías en la Red
Es posible describir el comportamiento de la red mediante una gran cantidad de datos diferentes, como las características del flujo de paquetes, las particularidades de los mismos paquetes y la telemetría derivada de múltiples fuentes. Un enfoque para la detección de ataques a la red es el análisis de estos datos diferentes sin estructurar mediante técnicas de análisis de datos masivos. Esto se conoce como análisis de comportamiento de red (network behavior analysis NBA).

Esto implica el uso de técnicas sofisticadas de estadística y aprendizaje mecanizado para comparar los valores de referencia del funcionamiento normal con el desempeño de la red en un momento específico. Las desviaciones significativas pueden indicar la existencia de riesgo. Además, el comportamiento de la red se puede analizar en busca de comportamientos de red conocidos que indiquen un compromiso.

La detección de anomalías puede reconocer el tráfico de red causado por la actividad del gusano que muestra un comportamiento de exploración. La detección de anomalías también puede identificar hosts infectados en la red que están buscando otros hosts vulnerables.

En la figura, se ejemplifica una versión simplificada de un algoritmo diseñado para detectar una situación inusual en los routers de frontera de una empresa.

![image](https://hackmd.io/_uploads/SydNX3li-g.png)

Por ejemplo, el analista de ciberseguridad podría proporcionar los siguientes valores:

X = 5
Y = 100
Z = 30
N = 500

Ahora bien, el algoritmo se puede interpretar como: cada 5 minutos, obtener una muestra de 1/100 de los flujos durante el segundo 30. Si el número de flujos es mayor que 500, generar una alarma. Si el número de flujos es menor que 500, no hacer nada. Este es un ejemplo sencillo del uso de un perfil de tráfico para identificar el potencial de pérdida de datos.

Además de los enfoques estadísticos y de comportamiento para la detección de anomalías es la detección de anomalías basada en reglas. La detección basada en reglas analiza paquetes decodificados para ataques basados en patrones predefinidos.

## Pruebas de Vulnerabilidad de la Red

![image](https://hackmd.io/_uploads/Bk6P4heo-g.png)

![image](https://hackmd.io/_uploads/BJ8hE3xiZg.png)

## 

![image](https://hackmd.io/_uploads/SkVoHhliWl.png)

![image](https://hackmd.io/_uploads/Bk7nH2ejbe.png)

![image](https://hackmd.io/_uploads/S1_HL3xjWx.png)

![image](https://hackmd.io/_uploads/SySLI3lobe.png)

## Sistema Común de Puntuación de Vulnerabilidades (CVSS)

### Descripción General de CVSS
El Sistema Común de Puntuación de Vulnerabilidades (Common Vulnerability Scoring System CVSS) es una herramienta de evaluación de riesgos que está diseñada para transmitir los atributos comunes y la gravedad de las vulnerabilidades en los sistemas de hardware y software. La tercera revisión, CVSS 3.0, es un marco de trabajo abierto estándar del sector e independiente de proveedores que permite ponderar los riesgos de una vulnerabilidad mediante una variedad de métricas. Estas ponderaciones se combinan para proporcionar una puntuación del riesgo inherente en una vulnerabilidad. La puntuación numérica puede utilizarse para determinar la urgencia de la vulnerabilidad y la prioridad de abordarla. Los beneficios de CVSS pueden resumirse del siguiente modo:

Proporciona puntuaciones estandarizadas de vulnerabilidades a las que se les debe dar importancia en las organizaciones.
Proporciona un marco de trabajo abierto que tiene disponible el significado de cada métrica para todos los usuarios.
Ayuda a priorizar el riesgo de una manera que tenga sentido para las organizaciones individuales.
El Foro de Respuesta a Incidentes y Equipos de Seguridad (FIRST, Forum of Incident Response and Security Teams) fue designado como custodio de CVSS para promover su adopción a nivel mundial. El estándar Versión 3 fue desarrollado con contribuciones de Cisco y otros socios de la industria. La versión 3.1 fue lanzada en junio de 2019.

### Grupos de métricas de CVSS
Antes de realizar una evaluación de CVSS, es importante conocer las palabras clave que se utilizan en el instrumento de evaluación.

Muchas de las métricas hacen referencia a la función de lo que CVSS llama una autoridad. Una autoridad es una entidad informática, como una base de datos, un sistema operativo o una caja de arena virtual, que otorga y administra el acceso y los privilegios a los usuarios.

![image](https://hackmd.io/_uploads/SyiOw3giZl.png)

![image](https://hackmd.io/_uploads/BkCiD2ei-l.png)

![image](https://hackmd.io/_uploads/BJKnPnlj-g.png)

![image](https://hackmd.io/_uploads/SyICDnli-l.png)

### Grupo de Métricas Base de CVSS

![image](https://hackmd.io/_uploads/S1mEd2ej-g.png)

![image](https://hackmd.io/_uploads/S1OKOhgsWx.png)

![image](https://hackmd.io/_uploads/H1Ea_neoZx.png)

### El Proceso de CVSS
El Grupo de Métricas Base de CVSS está diseñado como una forma de evaluar las vulnerabilidades de seguridad que se encuentran en los sistemas de software y hardware. Permite describir la gravedad de una vulnerabilidad de acuerdo con las características de un ataque exitoso de dicha vulnerabilidad. Los otros grupos de métricas modifican la puntuación de gravedad básica determinando cómo se ve afectada dicha puntuación por factores temporales y del entorno.

El Proceso de CVSS utiliza una herramienta llamada Calculadora CVSS v3.1, la cual se muestra en la figura.


![image](https://hackmd.io/_uploads/S1OOKnxjZl.png)

La calculadora es como un cuestionario en el que se toman decisiones que describen la vulnerabilidad para cada grupo de métricas. Después de realizar todas las elecciones, se genera una puntuación. El texto emergente que explica cada métrica y cada valor de métrica se muestra al pasar el mouse sobre cada una. Las elecciones se realizan seleccionando un valor para cada métrica. Se puede elegir solamente un valor por métrica.

Se puede acceder a la calculadora CVSS en la parte CVSS del PRIMER sitio web.

Para respaldar el proceso, hay disponible una guía del usuario detallada que definir criterios de métricas, ejemplos de evaluaciones de vulnerabilidades comunes y la relación de los valores de las métricas con la puntuación final.

Una vez completado el grupo de Métricas base, se muestra la clasificación numérica de gravedad, como se muestra en la figura.

![image](https://hackmd.io/_uploads/BJN3thlsbx.png)

![image](https://hackmd.io/_uploads/SkTCYnljWg.png)

![image](https://hackmd.io/_uploads/HJUQc3xs-g.png)

A fin de calcular una puntuación para los grupos de métricas temporales o del entorno, primero se debe completar el grupo de métricas básicas. Después, los valores de las métricas temporales y del entorno modificarán los resultados de las métricas básicas para proporcionar una puntuación general. La interacción de las puntuaciones para los grupos de métricas se muestra en la figura.

![image](https://hackmd.io/_uploads/SkXBqhejZx.png)

### Informes de CVSS

![image](https://hackmd.io/_uploads/S1Xa5nejWg.png)

Con frecuencia, las puntuaciones de los grupos de métricas básicas y temporales se suministrarán a los clientes de parte del proveedor de la aplicación o de seguridad en cuyo producto se haya detectado la vulnerabilidad. La organización afectada completa el grupo de métricas del entorno para adaptar la puntuación suministrada por el proveedor al contexto local.

La puntuación obtenida sirve para orientar a la organización afectada en la asignación de recursos para afrontar la vulnerabilidad. Mientras mayor sea la clasificación de gravedad, mayor será el impacto potencial de un ataque y mayor la urgencia de afrontar la vulnerabilidad. Aunque no son tan precisas como las puntuaciones numéricas de CVSS, las etiquetas cualitativas son muy útiles para comunicarse con las partes interesadas que son incapaces de entender las puntuaciones numéricas.

En general, debe afrontarse cualquier vulnerabilidad que supere el valor de 3,9. Cuanto mayor sea el nivel de clasificación, mayor será la urgencia de obtener una solución.

### Otras Fuentes de Información sobre Vulnerabilidades
Hay otras fuentes de información importantes sobre vulnerabilidades. Estas trabajan en conjunto con CVSS para proporcionar una evaluación completa de la gravedad de las vulnerabilidades. Hay dos sistemas que funcionan en los Estados Unidos:

#### Vulnerabilidades y Exposiciones Comunes (CVE, Common Vulnerabilities and Exposures)

Se trata de un diccionario de nombres comunes, en forma de identificadores de CVE, que hacen referencia a vulnerabilidades de ciberseguridad conocidas. El identificador de CVE proporciona una manera estandarizada de investigar una referencia a las vulnerabilidades. Cuando se identifica una vulnerabilidad, los identificadores de CVE pueden utilizarse para tener acceso a soluciones. Además, los servicios de inteligencia de amenazas utilizan identificadores de CVE y aparecen en diversos registros de los sistemas de seguridad. El sitio web con detalles sobre CVE incluye un enlace entre las puntuaciones de CVSS y la información de CVE. Permite navegar por los registros de vulnerabilidades de CVE según la clasificación de gravedad de CVSS.

#### Base de datos nacional sobre vulnerabilidades (NVD, National Vulnerability Database)

Esta base utiliza identificadores de CVE y suministra información adicional sobre vulnerabilidades, como puntuaciones de amenazas de CVSS, detalles técnicos, entidades afectadas y recursos para la investigación posterior. El Instituto Nacional de Normas y Tecnología (NIST) de los Estados Unidos creó y mantiene esta base de datos.

## Verifique su Comprensión - Identifique las Métricas de CVSS

![image](https://hackmd.io/_uploads/r1RM0nxjZx.png)

![image](https://hackmd.io/_uploads/BkGVAnxoZx.png)

![image](https://hackmd.io/_uploads/SkxHC2ls-g.png)

![image](https://hackmd.io/_uploads/S1lUA2giWl.png)

![image](https://hackmd.io/_uploads/r1ZPAnxsbe.png)

# Administración segura de dispositivos

## Administración de Riesgos
### Un proceso de gestión de riesgos
La gestión de riesgos implica seleccionar y especificar controles de seguridad para una organización. Es parte de un programa continuo de seguridad de la información en toda la organización que involucra la gestión de riesgos de la organización o de personas en relación con el funcionamiento de un sistema.

La gestión de riesgos es un proceso continuo y cíclico de varios pasos, como se ve en la figura.

**Un Proceso de Gestión de Riesgos**

![image](https://hackmd.io/_uploads/HkLbHpeoZx.png)

![image](https://hackmd.io/_uploads/r1mKS6eoZl.png)

![image](https://hackmd.io/_uploads/Syp-8pxobx.png)

# Administración de Vulnerabilidades
## Ciclo de vida de la Administración de vulnerabilidades
Según el NIST, la administración de vulnerabilidades es una práctica de seguridad diseñada para prevenir de forma proactiva la explotación de las vulnerabilidades de IT que existen dentro de una organización. Tiene por objetivo reducir el tiempo y el dinero invertidos en solucionar las vulnerabilidades y su aprovechamiento. La administración proactiva de las vulnerabilidades de los sistemas reducirá o eliminará el potencial de explotación e implicará considerablemente menos tiempo y esfuerzo que responder después de que se haya producido una explotación o ataque.

La administración de vulnerabilidades requiere una metodología sólida para identificar vulnerabilidades usando boletines de seguridad de proveedores y otros sistemas de información, como CVE. El personal de seguridad debe tener la competencia para evaluar el impacto (si lo hubiera) de la información sobre la vulnerabilidad que reciba. Las soluciones deben identificarse usando metodologías eficaces de implementación y evaluación de las consecuencias imprevistas de las soluciones implementadas. Por último, la solución se debe probar para verificar que se eliminó la vulnerabilidad.

Ciclo de vida de la Administración de vulnerabilidades

![image](https://hackmd.io/_uploads/ByV086go-e.png)

* Descubrir
Haga un inventario de todos los activos en la red e identifique los detalles del host, incluidos los sistemas operativos y los servicios abiertos, para identificar vulnerabilidades. Desarrolle un valor de referencia para la red. Identifique las vulnerabilidades de seguridad usando un cronograma periódico automatizado.

* Priorizar activos
Clasifique los activos en grupos o unidades comerciales y asigne un valor comercial a los grupos de activos en función de su importancia para las operaciones comerciales.

* Evaluar
Determinar un perfil de riesgo de línea base para eliminar los riesgos en función de la criticidad, la vulnerabilidad, las amenazas y la clasificación de los activos.

* Informar
Mida el nivel de riesgo comercial asociado con sus activos de acuerdo con sus políticas de seguridad. Documentar un plan de seguridad, monitorear la actividad sospechosa y describir vulnerabilidades conocidas.

* Remediar
Priorice según el riesgo comercial y aborde las vulnerabilidades en orden de riesgo.

* Verificar
Verifique que las amenazas se hayan eliminado mediante auditorías de seguimiento.

## Administración de Activos

La administración de activos implica implementar sistemas que rastrean la ubicación y configuración de dispositivos y software en red en toda una empresa. Como parte de cualquier plan de administración de la seguridad, las organizaciones deben saber qué equipo tiene acceso a la red, dónde se encuentra ese equipo dentro de la empresa y su posición lógica en la red, y qué software y datos almacenan o usan esos sistemas. La administración de activos no solo realiza un seguimiento de los activos de la empresa y de otros dispositivos autorizados, sino que también puede usarse para identificar los dispositivos que no están autorizados en la red.

El NIST especifica en su publicación NISTIR 8011 (Volumen 2) los registros detallados que deben mantenerse para cada dispositivo. El NIST describe las posibles técnicas y herramientas para poner en práctica un proceso de administración de activos:

* Detección automatizada e inventario del estado actual de los dispositivos
* Articulación del estado deseado de esos dispositivos usando políticas, planes y procedimientos en el plan de seguridad de la información de la organización
* Identificación de activos autorizados que no cumplan las reglas
* Corrección o aceptación del estado del dispositivo, posible reiteración de la definición del estado deseado
* Repetición del proceso en intervalos regulares o de manera continua

En la figura, se describe este proceso a grandes rasgos.

![image](https://hackmd.io/_uploads/B1a4O6gi-l.png)

## Administración de Dispositivos Móviles
La administración de dispositivos móviles (MDM, Mobile Device Management), especialmente en la era de BYOD, supone retos especiales para la administración de activos. No es posible controlar físicamente los dispositivos móviles en las instalaciones de una organización. Pueden ocurrir extravíos, robos o alteraciones, lo que pone en peligro el acceso a los datos y a la red. Parte de un plan MDM actúa cuando los dispositivos dejan la custodia de la parte responsable. Entre las posibles medidas, se incluye deshabilitar el dispositivo extraviado, encriptar los datos en el dispositivo y mejorar el acceso a los dispositivos con medidas de autenticación más resistentes.

Debido a la diversidad de dispositivos móviles, es posible que el diseño de algunos dispositivos que se usen en la red sea menos seguro que el de otros. Los administradores de redes deben adoptar la premisa de que ningún dispositivo móvil es confiable hasta que la organización lo proteja como se debe.

Los sistemas de MDM, como Cisco Meraki Systems Manager (en la figura), permiten que el personal de seguridad configure, monitoree y actualice un conjunto muy diverso de clientes móviles desde la nube.

![image](https://hackmd.io/_uploads/HJPiupeiZl.png)

## Administración de Configuraciones
La administración de configuraciones se ocupa del inventario y control de configuraciones de hardware y software de los sistemas. Las configuraciones seguras de los dispositivos reducen los riesgos de seguridad. Por ejemplo, una organización ofrece muchas computadoras de escritorio y portátiles a sus trabajadores. Esto aumenta la superficie de ataque de la organización, ya que cada sistema puede ser vulnerable a ataques. Para ello, la organización puede crear imágenes de software y configuraciones de hardware de referencia para cada tipo de máquina. Estas imágenes pueden incluir un paquete básico de software necesario, software de seguridad para terminales y políticas de seguridad personalizadas que controlen el acceso del usuario a los aspectos de la configuración del sistema que podrían producir vulnerabilidades. Las configuraciones de hardware pueden especificar los tipos permitidos de interfaces de red y de almacenamiento externo.

La administración de configuraciones se extiende a la configuración de hardware y software de dispositivos de red y servidores. Según la definición del NIST, la administración de configuraciones:

se compone de un conjunto de actividades encaminadas a establecer y mantener la integridad de los productos y sistemas, mediante el control de los procesos de inicialización, modificación y monitoreo de las configuraciones de esos productos y sistemas.

La publicación especial 800-128 del NIST sobre la administración de configuraciones para la seguridad de la red está disponible para su descarga desde NIST.

Para los dispositivos de interconexión de redes, hay disponibles herramientas de software que realizan copias de respaldo de las configuraciones, detectan cambios en los archivos de configuración y permiten cambiar de una vez las configuraciones en muchos dispositivos.

Con la llegada de los centros de datos y la virtualización en la nube, la gestión de varios servidores supone retos especiales. Herramientas como Puppet, Chef, Ansible y SaltStack permiten una gestión eficiente de los servidores que se utilizan en la informática basada en la nube.

## Administración de Parches Empresariales
La administración de parches está relacionada con la administración de vulnerabilidades. Las vulnerabilidades suelen aparecer sistemas operativos y firmware esenciales de los dispositivos de clientes, servidores y redes. El software de aplicación, especialmente las aplicaciones de Internet y los marcos como Acrobat, Flash y Java, también se descubre con frecuencia por tener vulnerabilidades. La administración de parches involucra todos los aspectos de la implementación de parches de software, entre ellos, la identificación de parches necesarios, y la adquisición, distribución, instalación y comprobación de parches en todos los sistemas que los requieran. La instalación de parches suele ser la manera más efectiva de mitigar las vulnerabilidades de software. A veces, es la única manera de hacerlo.

Algunas regulaciones de cumplimiento requieren la administración de parches, como Sarbanes Oxley (SOX) y la Ley de Portabilidad y Responsabilidad de Seguros Médicos (Health Insurance Portability and Accountability Act HIPAA). Si no se implementan los parches de manera sistemática y oportuna, podrían ocurrir problemas durante las auditorías y la aplicación de sanciones por incumplimiento. La administración de parches depende de los datos de la administracón de activos para identificar los sistemas que ejecutan software que requiere parches. El software de administración de parches está disponible en empresas como SolarWinds y LANDesk. Administrador de configuración de Microsoft System Center (Microsoft System Center Configuration Manager SCCM) es una herramienta de nivel empresarial para la distribución automatizada de parches a un gran número de estaciones de trabajo y servidores de Microsoft Windows.

![image](https://hackmd.io/_uploads/HJ9tY6lsZx.png)

## Técnicas de Administración de Parches

* Basado en agentes
Este requiere que un agente de software se ejecute en cada host donde se implementen parches. El agente informa si hay software vulnerable instalado en el host. El agente se comunica con el servidor de administración de parches, determina si hay parches que deban instalarse y los instala. El agente se ejecuta con los privilegios suficientes para poder instalar los parches. Los enfoques con base en agentes son el método preferido para implementar parches en dispositivos móviles.
![image](https://hackmd.io/_uploads/Hkeg96eo-l.png)


* Análisis sin agentes
Los servidores de administración de parches analizan la red en busca de dispositivos que necesiten parches. El servidor determina qué parches se necesitan y los instala en los clientes. Solamente los dispositivos que se encuentran en segmentos de red analizados se pueden parchar de esta manera. Esto puede suponer un problema para los dispositivos móviles.
![image](https://hackmd.io/_uploads/SyeNcaxjZg.png)

* Monitoreo de red pasivo
Los dispositivos que requieren parches se identifican mediante el monitoreo del tráfico en la red. Este enfoque solamente es efectivo para el software que incluye información sobre la versión en el tráfico de su red.
![image](https://hackmd.io/_uploads/BJCUc6esWe.png)

# Verifique su Comprensión - Identifique Actividades de Administración de Dispositivos

![image](https://hackmd.io/_uploads/SkiVi6ej-x.png)
![image](https://hackmd.io/_uploads/ryKBjpgo-g.png)
![image](https://hackmd.io/_uploads/ryq8opeobg.png)
![image](https://hackmd.io/_uploads/SJKvsaxs-g.png)
![image](https://hackmd.io/_uploads/BkI_i6xsWg.png)

# 
![image](https://hackmd.io/_uploads/H1Liiaxsbg.png)
![image](https://hackmd.io/_uploads/HJ6nspljWx.png)
![image](https://hackmd.io/_uploads/ry3aialobl.png)



# PRUEBA
![image](https://hackmd.io/_uploads/r1VL1AgsZx.png)
![image](https://hackmd.io/_uploads/H1k_yRljWl.png)
![image](https://hackmd.io/_uploads/Sydt1Cgj-x.png)
![image](https://hackmd.io/_uploads/Hy7oJ0gsWl.png)
![image](https://hackmd.io/_uploads/r1Z2kCgjWe.png)
![image](https://hackmd.io/_uploads/H1RnkClj-e.png)
![image](https://hackmd.io/_uploads/S1ApJRxoWl.png)
![image](https://hackmd.io/_uploads/Syc01Axs-g.png)
![image](https://hackmd.io/_uploads/H1okgReoWl.png)
![image](https://hackmd.io/_uploads/BJFgxRxsbl.png)
![image](https://hackmd.io/_uploads/SktzxCliWx.png)
![image](https://hackmd.io/_uploads/HynEl0xsZe.png)

