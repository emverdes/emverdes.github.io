---
layout: single
title: "Más allá del control: cómo evolucionar en la automatización"
categories: [tech]
tags: [meta]
---

## Introducción – La lección del Maestro Oogway

El joven discípulo había pasado semanas perfeccionando cada movimiento, cada postura, cada golpe. Cada día practicaba más, convencido de que, si podía controlarlo todo, nunca fallaría. Pero cada vez que enfrentaba un nuevo desafío, su mente se bloqueaba: había demasiadas variables que no podía dominar.

Un día, el Maestro lo llevó al pie de un lago tranquilo y le dijo:

>“Nunca enfrentarás tu destino hasta que no abandones la ilusión del control.”

El discípulo, confundido, lo miró.  
El Maestro arrojó una piedra al agua, y las ondas comenzaron a expandirse.

> “Mirá el agua. No podés detener las ondas, pero podés aprender a fluir con ellas.  
> La verdadera maestría no está en controlarlo todo, sino en construir el camino para que las cosas fluyan con armonía.”

El joven entendió. Su entrenamiento ya no sería memorizar movimientos, sino aprender a construir prácticas y sistemas que funcionen, incluso cuando no pudiera ver ni controlar cada detalle.

En la automatización empresarial pasa lo mismo. Muchas organizaciones intentan controlar cada script, cada tarea, cada excepción, aferrándose a esa ilusión de control. Pero para madurar, colaborar y evitar errores, hay que dejar esa ilusión atrás y construir prácticas compartidas: entender dónde estamos (madurez), cómo evolucionar (de comunidades informales a estructuras formales) y cómo evitar caer en los antipatrones que nos devuelven al caos.

## Modelos de madurez en automatización

A la hora de recorrer el camino de la automatización, es importante saber dónde estamos, y el camino que tenemos por delante. Para eso es muy útil un modelo de madurez.

![Descripción de la imagen](/assets/images/maturity.png)

### 0. Manual

En esta etapa, las tareas de IT se realizan de forma completamente manual. No existen procedimientos definidos, la documentación es mínima o inexistente, y cada cambio o configuración depende del conocimiento individual de las personas. Los errores son frecuentes y los tiempos de entrega son altos.

### 1. Experimental

Algunos equipos comienzan a automatizar tareas puntuales, usualmente mediante scripts propios, en base a impulsos individuales, o de pequeños equipos. No hay un enfoque común ni herramientas compartidas. Cada grupo trabaja de forma aislada, con distintos lenguajes, estándares y niveles de calidad. El conocimiento no se sistematiza ni se comparte.

### 2. Definido

Se adoptan herramientas de automatización estandarizadas (como Ansible), y se establecen estructuras reutilizables (roles, playbooks, colecciones). Los procesos empiezan a documentarse formalmente y a compartirse entre equipos. Se promueve la colaboración, aunque aún de forma limitada. La automatización deja de ser una “isla” y empieza a consolidarse como una práctica organizacional.

### 3. Gestionado

La automatización se gestiona de forma centralizada o coordinada. Existen repositorios comunes, revisión de código, buenas prácticas compartidas y métricas para evaluar el impacto. La colaboración entre áreas técnicas y funcionales se vuelve sistemática. Empiezan a aparecer estructuras como una *Community of Practice* o incluso un *Center of Excellence*.

### 4. Optimizado

La automatización se alinea con los objetivos estratégicos de la organización. Se mide el valor entregado, se identifican oportunidades de mejora continua, y se priorizan iniciativas con alto impacto. La automatización es parte del ADN de la empresa: confiable, visible y sostenible. La cultura se orienta a eliminar el trabajo repetitivo y potenciar el talento.

Es importante entender que en una organización grande, no todos los equipos van a estar en el mismo nivel de madurez. Algunos estarán en el nivel 0 (Manual), la mayoría estarán en el nivel 1 (Experimental) y unos pocos posiblemente están en el nivel 2 (Definido). El primer objetivo debería ser nivelar, para que, como organización, se pueda avanzar en forma coordinada.

Ahora, la madurez no se adquiere adoptando herramientas. La clave son las personas. Ya hablamos en artículos anteriores de la importancia de seleccionar las personas claves para nuestro primer proyecto, pero hoy te quiero hablar de dos estructuras que deberías empezar a construir para nivelar a todos tus equipos de IT, llevándolos al nivel “Definido”, y desde ahí continuar avanzando hasta alcanzar los siguientes niveles.

Los conceptos de los artículos anteriores (4S, elección del primer proyecto, involucrar a personas) son fundamentales para avanzar en esas etapas.

## De Comunidad de Prácticas a Centro de Excelencia

El primer paso es construir una **Comunidad de Prácticas** (*Community of Practice* o CoP). Una comunidad de prácticas es un grupo informal de personas que comparten un interés común —en este caso, la automatización— y que se reúnen voluntariamente para aprender, compartir experiencias y mejorar su práctica profesional.

No es un equipo formal, ni responde a las estructuras jerárquicas: se forma desde la base, impulsada por la motivación de hacer mejor las cosas y ayudar a otros.

Los objetivos principales de una CoP, en este contexto, son:

- **Compartir conocimiento:** evitar reinventar la rueda. Aprender de la experiencia de otros.
- **Difundir buenas prácticas:** cómo organizar un playbook, cómo versionar roles, cómo documentar cambios.
- **Mentoría y aprendizaje cruzado:** generar un espacio donde los más experientes puedan acompañar a quienes recién comienzan.
- **Fomentar la colaboración entre equipos:** romper los silos y facilitar el intercambio entre quienes automatizan desde diferentes sectores.
- **Identificar patrones y casos de uso:** detectar qué procesos son candidatos a ser reutilizados o estandarizados a mayor escala.
- **Sembrar la base cultural para futuras estructuras formales (como un CoE):** la CoP es el semillero natural de referentes técnicos y culturales que luego pueden liderar un Centro de Excelencia a medida que la organización madura.

### ¿Cómo nace una Comunidad de Prácticas?

Todo empieza con el primer caso exitoso: un proceso se automatiza exitosamente. Se ve el beneficio: menos errores, más rapidez, menos trabajo repetitivo. El equipo que lo hizo se siente orgulloso… y el resto nota el impacto.

Y luego ocurre algo natural: alguien pregunta **“¿Cómo lo hicieron?”**. Aparece una conversación, un hilo, una reunión espontánea. Se organizan demos, charlas internas, “cafés técnicos”, y así nace una Comunidad de Prácticas.

### ¿Qué puede hacer la organización para facilitar y nutrir a una CoP?

Te sugiero un conjunto de actividades que podés promover en tu organización:

- **Talleres técnicos abiertos (hands-on):** en un laboratorio donde se pueda probar Ansible en un entorno controlado.
- **Charlas internas / lightning talks:** donde integrantes del equipo pueden mostrar algo que automatizaron, en un estilo informal.
- **Hackathones o desafíos para automatizar tareas**, con incentivos simbólicos o reales (stickers o medallas digitales, recursos para un after del equipo, etc.). Los desafíos pueden ser individuales o por equipos.
- **Canales internos dedicados** (chat, foro, wiki, repositorio) que permitan hacer preguntas, compartir recursos, pedir ayuda, etc.
- **Reconocimiento explícito del liderazgo informal** en reuniones, Town Halls, boletines, a quienes aportan a la Comunidad. Puede ser simbólico, pero tiene alto impacto para apuntalar la cultura.

La CoP te va a llevar al estado “Definido” del Modelo de Madurez, por lo tanto, en el punto que estés hoy, a partir del primer proyecto deberías estar tomando acción para que se genere esa Comunidad.

Una vez que llegás a esta etapa, lo que vas a necesitar para pasar al estado “Gestionado” y seguir avanzando es un **Centro de Excelencia** (*Center of Excellence* o CoE).

## El Centro de Excelencia de Automatización

Al contrario de la CoP, un CoE es una estructura **formal** dentro de la organización, que se encarga de liderar, coordinar y sostener las iniciativas de automatización, para que sean sostenibles y escalables, y estén alineadas a la estrategia y objetivos de la organización.

El CoE se crea cuando la organización ya reconoce el valor de la automatización, y necesita ordenar y profesionalizar los esfuerzos.

**Objetivos principales del CoE de Automatización:**

- **Definir estándares técnicos y de calidad:** cómo se escriben, documentan, prueban y versionan los artefactos de automatización.
- **Seleccionar y mantener herramientas comunes:** entorno de desarrollo, orquestación, control de versiones, etc.
- **Reutilizar y mantener componentes compartidos:** gestiona el catálogo de automatismos, listos para ser consumidos por diferentes equipos.
- **Dar soporte y acompañamiento a los equipos:** provee guía, formación y ayuda técnica.
- **Alinear la automatización con los objetivos del negocio.**
- **Medir y reportar resultados:** define métricas de madurez, ROI y adopción, para mostrar el progreso y el valor aportado.

Se podría resumir así:

- **La Comunidad de Prácticas cultiva la cultura.**  
- **El Centro de Excelencia la transforma en estructura.**

El CoE nace desde una CoP madura. Lo importante es que no borre la cultura comunitaria, sino que la potencie con recursos, foco y visibilidad organizacional.

Recuerda que debes olvidar la **ilusión del control**.

## Antipatrones en automatización (y cómo evitarlos)

Para terminar, en el camino de la automatización es fácil caer en algunas trampas. Te comento los antipatrones más comunes:

- **Automatizar caos:** procesos mal definidos o ineficientes. Muchas veces se piensa que la automatización, “automágicamente”, va a resolver problemas con los procesos. No hay atajos: trabajá en tus procesos antes de automatizarlos.
- **Scriptitis:** proliferación de scripts sin estándares. Este es un problema cuando tenés equipos que ya tienen automatismos que funcionan. La CoP puede ayudar a mostrar valor, y hacer la transición.
- **Tecnología primero:** obsesión con la herramienta sobre los objetivos.
- **Silos automatizados:** equipos que no comparten ni reutilizan. Relacionado con el antipatrón de *Scriptitis*. Falta de pensamiento estratégico y de alineación con el negocio.
- **Falta de métricas:** no medir impacto ni aprendizaje.

Recuerda las **4S (Sencillo, Seguro, Sostenible, Significativo)**, que vimos en el [artículo anterior](https://www.enriqueverdes.com/tech/Ansible3/). Involucrar a las personas correctas, y mostrar éxitos tempranos. Ansible es una herramienta excelente, pero es eso, una herramienta. Usarla correctamente te va a aportar muchísimo valor.

## Y así llegamos al final de esta serie…

La parte más fácil de la automatización es adoptar Ansible y escribir playbooks. Lo verdaderamente crítico es construir capacidad y dar valor para el negocio. Para eso empezamos con pequeños logros, involucramos a las personas, compartimos lo que aprendemos, evitamos las trampas comunes y vamos consolidando una práctica que escale.

Como nos enseñó el maestro Oogway:

> “El verdadero crecimiento ocurre cuando dejamos de querer controlarlo todo, y empezamos a construir sistemas que nos permitan avanzar juntos.”
