---
title: Lab - Análisis de ataques

---


# Lab - Análisis de ataques
Objetivos
Parte 1: investigar los IOC

Parte 2: Investigar la actividad maliciosa

Parte 3: Investigar la actividad más maliciosa

Introducción
Una vez que se ha informado y validado una alerta, se debe completar el análisis forense digital y la respuesta a incidentes. En una organización grande, los miembros del equipo de respuesta ante incidentes (CSIRT) son responsables de este proceso. El equipo de respuesta generalmente consiste en cazadores de amenazas veteranos y técnicos y analistas de ciberseguridad seleccionados. Para ayudar al equipo de respuesta de incidentes, hay varias herramientas y recursos disponibles.

En esta práctica de laboratorio, utilizará el servicio de detección de malware interactivo en línea ANY.RUN y la matriz Mitre ATT & CK para investigar posibles actividades maliciosas.

ANY.RUN ofrece un servicio gratuito en el que los usuarios de la comunidad pueden cargar archivos sospechosos de malware para su análisis. Proporciona un conjunto muy completo de funciones de análisis que le permite investigar con seguridad el comportamiento del malware. El sandbox ANY.RUN puede ejecutar el malware de manera dinámica y mostrar detalles de lo que hace el malware por medio de una una interfaz de análisis segura.

Nota: Utilizará la versión gratuita de ANY.RUN, que tiene funciones limitadas y solo puede ejecutar muestras de malware en una máquina virtual con Windows 7 de 32 bits. Dos versiones más avanzadas están disponibles para una suscripción mensual. Las versiones Searcher (Buscadores) y Hunter (Cazadores) proporcionan funciones avanzadas de acceso y otros sistemas operativos (por ejemplo, Windows 10).

Situación
Usted está trabajando como técnico cibernético y ha sido seleccionado para trabajar con el equipo de respuesta ante incidentes de XYZ, Inc. Un analista de ciberseguridad le ha pedido que evalúe los valores hash de las alertas de seguridad generadas por el Sistema de Prevención de Intrusiones (IPS). El IPS ha marcado una serie de eventos como potencialmente maliciosos.

Utilizará la herramienta en línea ANY.RUN y la matriz Mitre ATT & CK para realizar un análisis forense basado en los valores hash proporcionados.

Recursos necesarios
=  Un dispositivo con acceso a Internet.

Instrucciones
Parte 1: Investigar los IOC
En esta parte, utilizará el sitio web ANY.RUN para clasificar los valores de hash identificados para ver si son maliciosos, sospechosos o benignos.

Paso 1: Explore el sitio ANY.RUN
a.  Abra un navegador web y vaya a la página ANY.RUN.

b.  En la parte superior de la página web hay enlaces disponibles que comienzan con “WHY US” (Por qué nosotros). Haga clic en SERVICE (SERVICIO) en el menú horizontal para ir a la interfaz de servicio de sandbox.

c.  Haga clic en uno de los países del mapa para ver la lista de envíos públicos de ese país. Los usuarios de la comunidad pueden ver un análisis detallado de cada envío.

d.  Explore y familiarícese con este tablero. La herramienta ANY.RUN tiene muchas opciones disponibles que serán de gran valor para un analista de ciberseguridad. Aproveche esta oportunidad para obtener más información sobre la herramienta.

Paso 2: Validar los hash sospechosos
En este paso, investigará algunos hash MD5 de archivos que el analista de ciberseguridad identificó en la tabla a continuación. Verificará si son potencialmente maliciosos, sospechosos o benignos.

a.   Para buscar valores hash, haga clic en Public Tasks (Tareas Públicas) en el menú de la izquierda.

Esto abre la página Public submissions (Envíos públicos) que muestra una lista de tareas públicas organizadas por el envío más reciente. Tenga en cuenta que cada tarea está etiquetada con el veredicto de análisis que identifica el envío como ninguna amenaza detectada (es decir, benigna), actividad sospechosa o actividad maliciosa.

b.   El analista de ciberseguridad le ha pedido que valide varios valores hash. Complete la siguiente tabla copiando y pegando el valor hash MD5 identificado en el cuadro de búsqueda en la parte superior derecha de la ventana y presione Enter.

Nota: Estos valores de hash maliciosos también se utilizarán en las partes 2 y 3.

Haga clic en Mostrar respuesta a una respuesta de ejemplo en la tabla.

Ocultar respuesta
Parte 2: Investigar la actividad maliciosa
En esta parte, utilizará el sitio web ANY.RUN para investigar la actividad maliciosa identificada en la parte anterior. Desde la herramienta ANY.RUN, pasará a diferentes herramientas para examinar la actividad maliciosa. Por último, utilizará la matriz Mitre ATT & K para identificar las tácticas y técnicas utilizadas por los agentes de amenazas.

Paso 1: Investigar el primer árbol de proceso de hash malicioso.
a.  Desde la página de envíos públicos ANY.RUN, busque el primer valor hash malicioso identificado en la Parte 1, paso 2b.

b.  Haga clic en la entrada resultante para abrirla en el entorno limitado ANY.RUN. La interfaz de análisis ANY.RUN proporciona información sobre muchos aspectos del comportamiento del malware.

Nota: Si se muestra más de un envío, haga clic en el envío con el nombre del archivo wireframe.exe.

c.  En el lado derecho de la pantalla, verá el árbol de procesos que muestra un grupo de barras azules horizontales en una estructura similar a un árbol anidado. Muestra todos los procesos de software que se utilizaron en el ataque. Algunos de ellos son componentes de software de Windows y otros son parte del malware.

¿Cuáles son los nombres de los procesos utilizados en esta actividad?

Área de respuesta
Escriba sus respuestas aquí.
wireframe.exe, cmd.exe, timeout.exe y NvidiaGPU.exe.

Ocultar respuesta
wireframe.exe, cmd.exe, timeout.exe y NvidiaGPU.exe.

Paso 2: Investigar el informe de texto de actividad maliciosa.
Encima del árbol de procesos hay tres cuadros de texto etiquetados como “Text report” (Informe de texto), “Processes graph” (Gráfico de procesos) y ATT&CK matrix (Matriz de ATT y CK).

a.  Haga clic en el Text report para abrir un informe en una nueva ventana del navegador web.

b.  Desplácese por el documento para ver el informe generado.

Pregunta:
¿Cuál es el valor SHA256 asociado a esta actividad?

Área de respuesta
Escriba sus respuestas aquí.
9C83A89EA0E56D5AF9AA37D2DABED20B2412DB8C9694A13128EA173A73557487

Ocultar respuesta
Paso 3: Investigar el gráfico de procesos de actividad maliciosa.
a.  Regrese a la página web de análisis y haga clic en Processes graph.

Preguntas:
¿Qué proceso se ejecutó primero?

Área de respuesta
Escriba sus respuestas aquí.
wireframe.exe

Ocultar respuesta
¿Cuál es el nombre del proceso en el cuadro resaltado en rojo?

Área de respuesta
Escriba sus respuestas aquí.
nvidiagpu.exe

Ocultar respuesta
b.  Haga clic en el cuadro resaltado en rojo.

Pregunta:
¿Cuál es el peligro identificado?

Área de respuesta
Escriba sus respuestas aquí.
ASYNCRAT fue detectado

Ocultar respuesta
ASYNCRAT fue detectado

Paso 4: Investigar la actividad maliciosa en la matriz de ATT y CK
a.  Regrese a la página web de análisis y haga clic en ATT&CK matrix para abrir la página de ATT&CK matrix.

Preguntas:
¿Cuántas tácticas, técnicas y eventos hay relacionados con esta actividad maliciosa?

Área de respuesta
Escriba sus respuestas aquí.
4 tácticas, 5 técnicas y 16 eventos.

Ocultar respuesta
¿Cuáles son las tácticas utilizadas por los agentes de la amenaza?

Área de respuesta
Escriba sus respuestas aquí.
Execution (Ejecución), Persistence (Persistencia), Privilege escalation (Escalamiento de privilegios) y Discovery (Detección)

Ocultar respuesta
b.  Haga clic en las diversas técnicas que se utilizaron.

Pregunta:
¿Qué técnica se identifica como Danger (Peligro)?

Área de respuesta
Escriba sus respuestas aquí.
Boot or Logon Autostart Execution

Ocultar respuesta
Parte 3: Investigar la actividad más maliciosa
En esta parte, repetirá los pasos de la Parte 2 para examinar las otras dos entradas maliciosas descubiertas en la Parte 1.

Paso 1: Investigar el segundo árbol de proceso de hash malicioso.
a.  Regrese a la página de Public submissions en ANY.RUN y busque el segundo valor de hash malicioso identificado en la Parte 1, paso 2b.

b.  Haga clic en la entrada resultante para abrirla en el entorno de prueba de ANY.RUN.

Pregunta:
¿Cuál es el nombre en el árbol de procesos utilizado en esta actividad?

Área de respuesta
Escriba sus respuestas aquí.
gh2st.exe

Ocultar respuesta
c.  Abra el Text Report (Informe de texto).

Pregunta:
¿Cuál es el valor SHA256 asociado a esta actividad?

Área de respuesta
Escriba sus respuestas aquí.
88DD2037D0C43ABACEBAD866DF3F8CCD2EE7D64B01405AA6756A3A1C2FAC28FA

Ocultar respuesta
d.  Regrese a la página web de análisis y abra el Processes graph.

Pregunta:
¿Cuáles son los peligros identificados?

Área de respuesta
Escriba sus respuestas aquí.
Roba credenciales de navegadores web, Roba datos de credenciales, Las acciones parecen robar datos personales, Se conecta al servidor de CnC y Se detecta REDLINE.

Ocultar respuesta
e.  Regrese a la página web de análisis para abrir ATT&CK matrix.

Preguntas:
¿Cuántas tácticas, técnicas y eventos hay relacionados con esta actividad maliciosa?

Área de respuesta
Escriba sus respuestas aquí.
3 tácticas, 7 técnicas y 245 eventos.

Ocultar respuesta
¿Cuáles son las tácticas utilizadas por los agentes de la amenaza?

Área de respuesta
Escriba sus respuestas aquí.
Credential access (Acceso a credenciales), Discovery (detección) y Collection (Recopilación).

Ocultar respuesta
c.  Haga clic en las diversas técnicas que se utilizaron.

Pregunta:
d.  ¿Qué técnicas se identifican como peligrosas?

Área de respuesta
Escriba sus respuestas aquí.
Credenciales de almacenes de contraseñas, credenciales no seguras, detección de software y recopilación de correo electrónico

Ocultar respuesta
Paso 2: Investigar el tercer árbol de proceso de hash malicioso
a.  Vuelva a la página Public submissions de ANY.RUN y busque el tercer valor de hash malicioso identificado en la Parte 1, paso 2b.

b.  Haga clic en la entrada resultante para abrirla en el entorno limitado ANY.RUN.

Pregunta:
¿Cuál es el nombre en el árbol de procesos utilizado en esta actividad?

Área de respuesta
Escriba sus respuestas aquí.
file1.exe

Ocultar respuesta
c.  Abra el Text Report (Informe de texto).

Preguntas:
¿Cuál es el valor SHA256 asociado a esta actividad?

Área de respuesta
Escriba sus respuestas aquí.
F7B1639B6C4CA677BA279B945A94C5F6D67E6C4C89FD39CD8BE882A8A7CDFCAA

Ocultar respuesta
d.  Regrese a la página web de análisis y abra el Processes graph.

Pregunta:
¿Qué peligros muestra?

Área de respuesta
Escriba sus respuestas aquí.
Roba credenciales de navegadores web, Roba datos de credenciales, Las acciones parecen robar datos personales, Se conecta al servidor de CnC, Se detectó REDLINE.

Ocultar respuesta
e.  Regrese a la página web de análisis para abrir ATT&CK matrix.

Preguntas:
¿Cuántas tácticas, técnicas y eventos hay relacionados con esta actividad maliciosa?

Área de respuesta
Escriba sus respuestas aquí.
3 tácticas, 7 técnicas y 1525 eventos.

Ocultar respuesta
¿Cuáles son las tácticas utilizadas por los agentes de la amenaza?

Área de respuesta
Escriba sus respuestas aquí.
Acceso, detección y recopilación de credenciales

Ocultar respuesta
Preguntas de reflexión
1.  Explique de qué manera el análisis forense y la respuesta ante incidentes se parecen mucho a la aplicación de la ley que intenta resolver un caso penal.

Área de respuesta
Escriba sus respuestas aquí.
Como un detective de policía, debe validar que se haya producido un delito, recopilar todas las pruebas posibles y analizar el resultado.

Ocultar respuesta
2.  Dos de nuestras actividades maliciosas se referían a Redline. ¿Qué es la línea roja?

Área de respuesta
Escriba sus respuestas aquí.
RedLine Stealer es un programa malicioso que recopila datos confidenciales de los usuarios de navegadores, sistemas y software instalado. También infecta los sistemas operativos con otro malware.