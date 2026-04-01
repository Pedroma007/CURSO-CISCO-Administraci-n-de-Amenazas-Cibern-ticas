---
title: Lab - Análisis de riesgos

---

# Lab - Análisis de riesgos
Objetivos
Parte 1: Utilizar métodos de Análisis de Riesgos

Parte 2: Calcular los riesgos

Trasfondo/Situación
Un análisis de riesgos determina las posibles vulnerabilidades y amenazas, su probabilidad y consecuencias, y las tolerancias para tales eventos. Los resultados de este proceso pueden expresarse mediante el uso de un método cuantitativo o cualitativo. El análisis cuantitativo de riesgos implica cálculos para asignar un valor a una posible vulnerabilidad o amenaza. Esta opción funciona mejor cuando se trata de activos tangibles, como edificios, computadoras o inventario. El análisis cualitativo de riesgos asigna un nivel utilizado para priorizar el riesgo potencial para que las organizaciones puedan adoptar un enfoque lógico para abordar las amenazas más críticas. Este método funciona mejor para los activos intangibles, como la propiedad intelectual, la reputación de la empresa o las cuentas por cobrar.

Recursos necesarios
Computadora personal o dispositivo móvil con acceso a internet

Instrucciones
Parte 1: Uso de métodos de análisis de riesgos
Riesgo Cuantitativo

El análisis cuantitativo de riesgos es el proceso de determinar objetivamente el impacto de un evento mediante el uso de métricas y modelos. Un análisis cuantitativo se basa en información histórica y tendencias para predecir el rendimiento futuro. El resultado del análisis es un valor.

El cálculo de la expectativa de pérdida anualizada (ALE) es un método común para estimar la disminución del valor o la capacidad de un activo después de que se produce un evento adverso.

Paso 1: Calcule el valor del activo.
En este paso, demostrará cómo calcular el valor del activo.

Costo inicial del activo

El valor del activo es el gasto total necesario para reemplazar un activo. Por ejemplo, el valor total de un activo puede incluir la compra y la licencia o el desarrollo junto con los costos de mantenimiento y soporte. En este ejemplo, el servidor de base de datos de clientes de la organización cuesta aproximadamente $20,000 USD. Esto incluye el hardware, el software y la configuración.

Valor Organizacional

Un valor intangible es más difícil de calcular porque puede incluir el costo de crear, adquirir y recrear información, y el impacto o la pérdida comercial si la información se pierde o se ve comprometida. También puede incluir costos de responsabilidad. En este ejemplo, el costo para crear el sitio web del cliente es de $40,000 USD

Valor público

Un costo intangible que incluye la pérdida de información patentada, o procesos, o la pérdida de reputación comercial. Este valor se estima en $75,000 USD.

Preguntas:
¿Cuál es el valor total de los activos del servidor?

Área de respuesta
135.000
El valor tangible e intangible del servidor es de aproximadamente $135,000 USD.

Ocultar respuesta
¿Por qué el costo intangible es tan alto? ¿Es esto realista?

Área de respuesta
Escriba sus respuestas aquí.
Considere el valor de la reputación de una organización. La reputación de un negocio es muy difícil de construir y mantener. El daño a la reputación puede ser muy costoso y permanente. Entonces, sí, esta evaluación es realista.

Ocultar respuesta
Paso 2: Calcular el Factor de Exposición
El factor de exposición se expresa como un porcentaje (o equivalente decimal) de pérdida de un activo si se detecta una amenaza o vulnerabilidad específica. El factor de exposición es un valor subjetivo. Si el activo se pierde por completo, el factor de exposición sería 100% o 1. El factor de exposición podría ser una fracción del valor, como 40% o 0.4, por ejemplo.

Pregunta:
A modo de ejemplo, ¿cuál es el impacto en el servidor si la sala de servidores se inunda y el costo para restaurar el servidor es de $30,000 USD?

Valor del activo: $135,000 USD

Costo de restauración: $30,000 USD

Factor de exposición

Área de respuesta
Escriba sus respuestas aquí.
El factor de exposición es 30 000/135 000 = 22% o 0,22

Ocultar respuesta
Paso 3: Calcule la expectativa de pérdida simple
Calcula la expectativa de pérdida simple (SLE) tomando el valor del activo y multiplicándolo por el factor de exposición. El resultado es la pérdida de dólares esperada debido a la ocurrencia de un solo evento. Un solo recurso puede tener múltiples amenazas o vulnerabilidades potenciales, y se puede calcular una sola expectativa de pérdida para cada ocurrencia.

Por ejemplo, se estima que un ataque de denegación de servicio tiene un factor de impacto o de exposición del 20% o 0,2. Esto significa que la SLE es de $135,000 USD x 0,2 = $27,000 USD.

Estime la SLE si se produce una falla en el disco duro o la unidad de almacenamiento donde el mismo valor de activo se estima en $135,000 USD. Este tipo de pérdida daría lugar a un factor de exposición de 0,5.

Preguntas:
¿Cual es la SLE?

Área de respuesta
Escriba sus respuestas aquí.
La SLE es de 135,000 x 0,5 = $67,500 USD

Ocultar respuesta
Calcule la SLE de un ataque de ransomware con un factor de exposición del 100% o 1,0.

Área de respuesta
Escriba sus respuestas aquí.
La SLE sería 135,000 x 1,0 = $135,000 USD

Ocultar respuesta
Paso 4: Calcule la tasa anualizada de ocurrencias
La tasa anualizada de ocurrencia (ARO) es una medida de la frecuencia con que se produce un evento en un solo año. ARO siempre se expresa en una calificación anual, incluso si se produce un incidente y se registra en otras medidas de tiempo. En nuestro ejemplo, el servidor de la base de datos del cliente se ve afectado por un ataque de denegación de servicio o DDoS cada 120 días o 4 meses en promedio. Esto significa que el evento ocurrirá tres veces en un año calendario en promedio, por lo que el ataque DoS / DDoS tiene un ARO de 3.

a.  En esta situación, calcule el ARO de un ataque de ransomware en el servidor de base de datos de clientes empresariales. En promedio, el servidor experimenta ataques de ransomware cada 24 meses o dos años.

Pregunta:
¿Cuál es el ARO de un ataque de ransomware en el servidor de base de datos del cliente?

Área de respuesta
Escriba sus respuestas aquí.
Si el evento ocurre cada veinticuatro meses, el ARO sería 12/24 = 0.5.

Ocultar respuesta
b.  En esta situación, calcule el ARO de una falla de hardware con el servidor de base de datos del cliente. En promedio, el servidor experimenta fallas de hardware cada 30 meses.

Pregunta:
¿Cuál es el ARO de las fallas de hardware con el servidor de base de datos del cliente?

Área de respuesta
Escriba sus respuestas aquí.
Si el evento ocurre cada treinta meses, el ARO sería 12/30 = 0,4.

Ocultar respuesta
Paso 5: Calcular la expectativa de pérdida anualizada
La expectativa de pérdida anualizada (ALE) es el producto del ARO y el SLE. Para calcular el ALE, tome el SLE y multiplíquelo por el ARO. Por ejemplo, si se determina que un corte de energía tiene un SLE de $50,000 USD y un ARO de 0.5, el ALE sería de $ 25,000 USD.

Preguntas:
¿Cuál es el ALE de una falla de hardware con el servidor de base de datos del cliente si el SLE = $5000 USD y ARO = 2,5?

Área de respuesta
Escriba sus respuestas aquí.
ALE = 5000 x 2,5 = $12,500 USD

Ocultar respuesta
¿Cuál es el ALE de un ataque de hacking con el servidor de base de datos de clientes si el SLE = $10,000 USD y ARO = 0,5?

Área de respuesta
Escriba sus respuestas aquí.
ALE = 10000 x 0,5 = $5,000 USD

Ocultar respuesta
Paso 6: Calcular el análisis de riesgo cualitativo
Un análisis cualitativo compara el impacto de una amenaza con la probabilidad de que ocurra y utiliza etiquetas como baja, media o alta. El impacto de un evento es una medida de la pérdida cuando una amenaza aprovecha una vulnerabilidad. La probabilidad es la probabilidad de que ocurra el evento de amenaza.

El análisis de riesgo cualitativo examina el nivel de impacto general en la organización. Estos problemas incluyen la pérdida de ingresos, la pérdida de reputación y la pérdida de clientes.

![image](https://hackmd.io/_uploads/H16mZIbiWe.png)

En el primer evento, el servidor web experimenta una falla en el disco duro que causa una pérdida de ingresos, reputación y clientes. Este es un impacto de muy alto riesgo y una posible probabilidad de ocurrencia.

Pregunta:
Utilizando la siguiente tabla, ¿cuál es el impacto cualitativo?

Área de respuesta
Escriba sus respuestas aquí.
Grave

![image](https://hackmd.io/_uploads/S1xPZUZsbg.png)
En el segundo evento, se lanza un ataque de denegación de servicio contra el servidor web. Este es un impacto de alto riesgo y una probabilidad probable de ocurrencia.

Pregunta:
Utilizando la siguiente tabla, ¿cuál es el impacto cualitativo?

Área de respuesta
Escriba sus respuestas aquí.
Grave

![image](https://hackmd.io/_uploads/H1CKWL-iWx.png)
En el tercer evento, hay un incendio en la sala de servidores. Este es un impacto de muy alto riesgo y una rara probabilidad de ocurrencia.

Pregunta:
Utilizando la siguiente tabla, ¿cuál es el impacto cualitativo?

Área de respuesta
Escriba sus respuestas aquí.
Moderado
![image](https://hackmd.io/_uploads/r1Q2b8ZsWl.png)

En el cuarto evento, se robaron datos de tarjetas de crédito. Este es un impacto de muy alto riesgo y una probabilidad poco probable de ocurrencia.

Pregunta:
Utilizando la siguiente tabla, ¿cuál es el impacto cualitativo?

Área de respuesta
Escriba sus respuestas aquí.
Grave
![image](https://hackmd.io/_uploads/HyvAZUboWg.png)

En el quinto evento, hay un tornado en el área. Este es un impacto de bajo riesgo y una rara probabilidad de ocurrencia.

Pregunta:
Utilizando la siguiente tabla, ¿cuál es el impacto cualitativo?

Área de respuesta
Escriba sus respuestas aquí.
Menor
![image](https://hackmd.io/_uploads/rJ4xGLZo-x.png)

Parte 2: Calcular los riesgos
Paso 1: Escenario de los equipos portátiles de la empresa ABC
Pregunta
ABC Company posee 65 computadoras portátiles. Cada computadora portátil cuesta $1,200 USD. Basará sus cálculos en el valor de una computadora portátil. El equipo identificó tres amenazas. Según los datos internos, calcule el ARO y el ALE con la información proporcionada. Introduzca los valores que faltan en la tabla.

![image](https://hackmd.io/_uploads/B1QVM8bobg.png)

Paso 2: Escenario de la red de área de almacenamiento de la empresa ABC
Pregunta:
La empresa ABC está realizando un análisis de riesgos para su red de área de almacenamiento. El valor total del activo es de $250,000 USD. El equipo identificó las tres amenazas que se muestran en la tabla. Los datos del fabricante y los registros de la empresa proporcionaron los datos que figuran en la tabla. Introduzca los valores que faltan en la tabla.
![image](https://hackmd.io/_uploads/ryB8G8Zo-l.png)

Paso 3: Escenario de amenazas del servidor de base de datos de la empresa ABC:
Pregunta
Compañia ABC gastó $18,000 USD en un servidor de base de datos. La configuración e instalación totalizaron $2,000 USD. Complete la tabla de desafíos de análisis de riesgos según las cuatro amenazas identificadas por el equipo de ABC. Introduzca los valores que faltan en la tabla.
![image](https://hackmd.io/_uploads/HkM9z8bobl.png)
![image](https://hackmd.io/_uploads/SJrsGLboZx.png)

Paso 4: Escenario del desafío del sistema de punto de venta de la empresa ABC
Pregunta:
ABC Company gastó $10,000 USD en su sistema de punto de venta remoto. La configuración e instalación totalizaron $5,000 USD. Complete la tabla en función de las cuatro amenazas identificadas por el equipo de ABC. Introduzca los valores que faltan en la tabla.
![image](https://hackmd.io/_uploads/rJG17UZjbg.png)

Paso 5: Escenario del desafío de las instalaciones de nube privada de la empresa ABC
Pregunta:
BC Company gastó $500,000 USD en el desarrollo y la compra de una instalación de nube privada. La configuración e instalación totalizaron $50,000 USD y la programación y el desarrollo de aplicaciones costaron otros $450,000 USD. Complete la tabla de desafíos de análisis de riesgos en función de las cuatro amenazas identificadas por el equipo de ABC. Introduzca los valores que faltan en la tabla.
![image](https://hackmd.io/_uploads/HJx4XUWjZl.png)


