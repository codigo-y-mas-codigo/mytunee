 

Inteligencia Artificial generativa para profesionales de ventas - NotebookLM
============================================================================

Exported on: 29/4/2026, 4:10:06

¿Cómo redacto las instrucciones globales para que Claude use mi voz?

Para redactar las instrucciones globales de manera que Claude adopte tu voz de forma permanente, debes seguir la filosofía de **"configura una vez, nunca más"**. El objetivo es que dejes de escribir prompts largos en cada tarea y permitas que la IA consulte tu identidad directamente de tus archivos.

Aquí tienes los pasos exactos y el texto que debes utilizar según las fuentes:

1\. Dónde configurar las instrucciones

Debes dirigirte a: **Configuración → Cowork → Editar Instrucciones Globales**.

2\. Qué redactar (El "Prompt Maestro")

Copia y pega el siguiente esquema adaptándolo a tu perfil:

_"Soy_ **\[Tu Nombre\]**_,_ **\[Tu Rol, ej. Ejecutivo de Ventas Digital\]**_. Lee mis archivos de la carpeta_ **SOBRE MÍ** _antes de realizar cada tarea para entender mi tono y estilo_._Sigue siempre estas reglas de interacción:_

*   **Haz preguntas** _antes de ejecutar cualquier acción compleja_.
*   **Muestra un plan** _detallado primero para que yo lo valide_.
*   **Nunca borres archivos** _de mi carpeta maestra sin mi aprobación explícita_."

3\. Por qué funciona este métodoAl redactar las instrucciones de esta manera, obligas a Claude a consultar el archivo **mi-voz.md** que creaste previamente en tu subcarpeta **SOBRE MÍ**.Para que Claude realmente "use tu voz", ese archivo debe contener:*   **Tu tono:** (Ej. cercano, directo, sin tecnicismos innecesarios).
*   **Frases que odias:** Palabras que te hacen sonar como un robot (ej. "potenciar", "ecosistema", "disruptivo").
*   **2-3 muestras reales de escritura:** Ejemplos de correos o posts que hayas escrito tú mismo. Las fuentes recalcan: **"Pega ejemplos reales de tu trabajo, no descripciones"**.4\. Reglas de oro para que sea efectivo
*   **No uses un chat en blanco:** Para que estas instrucciones globales se activen correctamente, debes trabajar en el modo **Cowork** y haber indicado previamente cuál es tu carpeta maestra (**Claude-Trabajo**).
*   **Evita el prompting infinito:** Con esta configuración, ya no necesitas explicarle a Claude cómo quieres que escriba cada vez que le pides algo; él ya tiene tu "manual de estilo" integrado en sus instrucciones base.
    
    Dame una lista de palabras prohibidas comunes para mi-voz.md
    
    Para que tu archivo **mi-voz.md** sea realmente efectivo y logre que la IA deje de sonar como un robot, debes incluir una lista de palabras y expresiones que "delatan" el uso de inteligencia artificial o que resultan demasiado genéricas en el mundo de las ventas digitales,.
    
    Aquí tienes una lista detallada de palabras y frases prohibidas, dividida por categorías, basada en lo que hemos conversado y en las mejores prácticas de las fuentes:
    
    1\. Muletillas típicas de la IA (Las que te hacen sonar como un bot)
    
    Estas palabras son el estándar que usa la IA por defecto y que debes evitar para mantener tu autenticidad:
    
*   **"Potenciar" / "Empoderar":** Se usan en casi todos los textos genéricos de IA,.
*   **"En el dinámico mundo de hoy":** O cualquier variante como "En el ecosistema actual" o "En el panorama cambiante".
*   **"Revolucionar" / "Disruptivo":** Palabras muy desgastadas que suelen prometer más de lo que ofrecen.
*   **"Un viaje hacia...":** Ejemplo: "Acompáñame en este viaje hacia la transformación digital".
*   **"Desbloquear":** Especialmente cuando se refiere a "desbloquear el potencial".2\. Jerga corporativa vacía (Jargon)Palabras que no aportan valor real y que el profesional de ventas moderno debe evitar para ser más cercano y consultivo,:
*   **"Sinergia":** Suena anticuado y poco natural.
*   **"Soluciones 360":** Es una frase muy trillada que no explica qué haces realmente.
*   **"Añadir valor":** En lugar de decir que "añades valor", describe **qué** valor aportas específicamente,.
*   **"Optimización de procesos":** Es mejor decir "cómo ahorrar tiempo" o "hacer las cosas más rápido".3\. Aperturas y cierres genéricosLas fuentes sugieren evitar mensajes que parezcan plantillas masivas para mejorar las tasas de respuesta,:
*   **"Espero que este mensaje te encuentre bien":** Es la forma más común en que la IA empieza un correo. Es mejor ir directo al grano con un insight relevante,.
*   **"Sin compromiso":** Esta frase debilita tu posición. Si tu propuesta tiene valor, el compromiso es mutuo.
*   **"Solo te escribo para...":** No te disculpes por escribir; si tienes algo importante que decir, dilo con confianza.4\. Estética visual (Basado en tus fuentes de diseño)Si también usas la IA para crear presentaciones o contenido visual, las fuentes técnicas recomiendan evitar:
*   **"Colores neón agresivos" o "colores sobresaturados":** Debes pedirle a la IA que evite estos tonos y use una paleta de "colores apagados sofisticados" (Sophisticated Muted Palette).
*   **"Sombras duras":** En la fotografía de producto o avatares, busca siempre iluminación de estudio suave y difusa.
*   **"Degradados excesivos":** Se prefieren bloques de color planos y mate para una estética más profesional y limpia.Recomendación de implementación:En tu archivo **mi-voz.md**, bajo el encabezado **\## LO QUE ODIO (PALABRAS PROHIBIDAS)**, copia y pega esta lista. Así, cada vez que Claude redacte algo para ti, filtrará automáticamente estos términos, obligándose a buscar sinónimos más humanos y alineados con tu estilo personal,.
    
    ¿Cómo organizo el archivo mis-reglas.md para controlar a la IA?
    
    Para organizar el archivo **mis-reglas.md** y tomar el control total sobre el comportamiento de la IA, debes estructurarlo como un documento de gobernanza y protocolos de seguridad dentro de tu subcarpeta **SOBRE MÍ**.
    
    De acuerdo con las fuentes, estas son las tres reglas fundamentales que deben encabezar tu archivo para asegurar que la IA trabaje bajo tu supervisión constante:
    
*   **Preguntar primero:** Indica a la IA que, ante cualquier ambigüedad en una tarea o cuando falte contexto, no debe asumir una respuesta, sino detenerse y pedirte aclaraciones.
*   **Mostrar un plan:** Establece como norma que, antes de generar cualquier entregable largo (como una propuesta comercial o un guion), la IA te presente primero una estructura o borrador para que tú lo valides.
*   **Nunca borrar sin aprobación:** Esta es una regla crítica de seguridad; la IA debe tener prohibido eliminar archivos, párrafos importantes o documentos de tu carpeta maestra sin tu consentimiento explícito.Estructura sugerida para el archivoPuedes organizar el contenido de **mis-reglas.md** de la siguiente manera para que sea claro y ejecutable:
    
    *   **Protocolo de Interacción:** Aquí detallas que prefieres que la IA sea proactiva pero consultiva, evitando que ejecute tareas complejas de forma automática sin tu visto bueno.
    *   **Límites de Seguridad:** Especificas la restricción sobre no borrar ni sobreescribir información valiosa sin avisar.
    *   **Formato de Entrega:** Puedes definir si prefieres que los resultados se guarden siempre en una subcarpeta específica llamada **RESULTADOS** para mantener el orden en tu ecosistema de trabajo.
    
    Integración con el SistemaRecuerda que este archivo solo será efectivo si lo conectas con las **Instrucciones Globales** de tu configuración. En ese apartado (Configuración → Cowork → Editar Instrucciones Globales), debes incluir la instrucción: "Lee mis archivos de la carpeta SOBRE MÍ antes de cada tarea" y reforzar que siga estrictamente lo dictado en el archivo de reglas.Este enfoque forma parte de la estrategia de **"configura una vez, nunca más"**, diseñada para que dejes de escribir prompts repetitivos y logres que la IA actúe como un compañero de trabajo que conoce tus límites y procesos operativos.
    
    ¿Cómo redacto mi-voz.md si no tengo ejemplos de escritura?
    
    Si no tienes ejemplos de escritura previos, no te preocupes; puedes construir tu archivo **mi-voz.md** definiendo tu identidad desde cero a través de tus valores profesionales y utilizando a la propia IA para ayudarte a "encontrar" ese estilo.
    
    Aquí tienes una estrategia paso a paso para redactar el archivo sin tener muestras previas:
    
    1\. Define tu "Yo Profesional" (Método de Contraste)
    
    Aunque no tengas textos escritos, seguro que tienes claro cómo quieres sonar ante un cliente. Las fuentes sugieren que el vendedor moderno debe alejarse del perfil tradicional y adoptar uno de **consultor**.
    
*   **En lugar de ejemplos, describe tu enfoque:** Indica que tu voz debe ser la de alguien que aporta valor desde el primer contacto.
*   **Prioriza habilidades humanas:** Define que tu estilo debe reflejar **empatía, escucha activa y creatividad**. Estos son los elementos que te diferenciarán en un mercado saturado.2\. Utiliza la técnica de "Generación y Refinado"Puedes usar a Claude para crear tus propios ejemplos iniciales. Pídele lo siguiente en un chat aparte:_"Actúa como un experto en ventas digitales. Basado en mi perfil de \[Consultor/Vendedor\], genera tres versiones de un correo de prospección: una formal, una cercana y una muy directa. No uses palabras robotizadas como 'potenciar' o 'ecosistema'_."Una vez que te dé las opciones:
*   Elige la que más te guste.
*   Cámbiale palabras para que suenen como tú las dirías.
*   **Ese texto resultante es ahora tu ejemplo real** para incluir en mi-voz.md.3\. Enfócate en lo que "SÍ" y lo que "NO" (Exclusión)Si no tienes muestras, el apartado de **"Frases que odias"** se vuelve el más importante para controlar a la IA.
*   **Lo que NO quieres:** Haz una lista de palabras prohibidas comunes (como "disruptivo", "sinergia" o "espero que este mensaje te encuentre bien") para obligar a la IA a buscar alternativas más humanas.
*   **Lo que SÍ quieres:** Define reglas de formato. Por ejemplo: "Mis correos nunca tienen más de dos párrafos" o "Siempre termino con una pregunta abierta para generar conversación".4\. Estructura recomendada para tu mi-voz.md (Sin ejemplos previos)Copia este esquema y completa las descripciones:
*   **\## MI TONO DESEADO:** "Quiero sonar como un consultor experto que ayuda a resolver problemas, no como alguien que solo quiere vender características. Mi tono es profesional, pero relajado y muy enfocado en la empatía".
*   **\## PALABRAS PROHIBIDAS:** (Pega aquí la lista de términos robóticos que discutimos anteriormente).
*   **\## FILOSOFÍA DE COMUNICACIÓN:** "Prefiero la brevedad. Uso datos para personalizar, pero mantengo una narrativa con insights relevantes que resuenen con los desafíos del cliente".
*   **\## MUESTRA DE PRUEBA (Creada con IA):** (Pega aquí el texto que refinaste en el punto 2).Recuerda que, según las fuentes, la IA es una herramienta para **amplificar tus habilidades**, no para reemplazarlas. Al definir estas reglas, estás sentando las bases para que Claude aprenda tu estilo a medida que trabajas con él, transformando tu sistema de un chat genérico a uno con contexto maestro.
    
    ¿Qué debo incluir en la subcarpeta PLANTILLAS de Claude-Trabajo?
    
    Dentro de la arquitectura de carpetas para tu sistema de IA, la subcarpeta **PLANTILLAS** es el espacio destinado a almacenar **tu mejor trabajo pasado**. Su propósito es servir como un "estándar de oro" para que la IA entienda el nivel de calidad, estructura y profundidad que esperas en los nuevos documentos que genere para ti.
    
    De acuerdo con las fuentes, esto es lo que deberías incluir específicamente para potenciar tu rol de ventas:
    
    1\. Comunicación y Prospección
    
*   **Correos de alcance (Outreach):** Aquellos mensajes personalizados que te han generado mejores tasas de respuesta en el pasado.
*   **Secuencias de seguimiento:** Estructuras de contacto que utilizas después de una primera reunión o visita web.
*   **Guiones de ventas:** Los guiones que mejor funcionan para tus llamadas en frío o presentaciones iniciales.2\. Documentación Comercial y Cierre
*   **Propuestas comerciales detalladas:** Ejemplos de propuestas que hayan sido exitosas, incluyendo cómo presentas los beneficios, métricas y casos de éxito.
*   **Presentaciones corporativas:** Estructuras de diapositivas que ya usas y que reflejan tu identidad visual y narrativa.
*   **Documentos contractuales:** Plantillas de contratos con los términos, plazos y cláusulas que sueles negociar.3\. Estrategia y Consultoría
*   **Análisis de objeciones:** Documentos donde hayas recopilado las dudas más comunes de tus clientes y cómo las has resuelto de forma persuasiva.
*   **Estructuras de Onboarding:** Plantillas de los primeros pasos que sigues con un cliente nuevo para garantizar una relación sólida desde el principio.
*   **Casos de éxito:** Relatos estructurados sobre cómo has ayudado a otros clientes, los cuales la IA puede usar para enriquecer nuevas propuestas.Regla de oro para esta carpetaLo más importante, según las fuentes visuales, es que **no incluyas descripciones de cómo haces las cosas, sino ejemplos reales de tu trabajo**. Al subir el archivo final de una propuesta exitosa o el hilo de correos que cerró una venta, le das a Claude un molde exacto para replicar tu éxito sin caer en respuestas genéricas.Al tener estos archivos en la subcarpeta **PLANTILLAS**, la IA podrá consultarlos automáticamente (gracias a tus Instrucciones Globales) para generar nuevo contenido que ya venga con el formato y la calidad que te caracterizan.
    
    ¿Cómo puedo automatizar el archivo mi-voz.md usando la IA?
    
    Para automatizar la creación de tu archivo **mi-voz.md** utilizando la IA, puedes emplear un proceso de "ingeniería inversa". En lugar de intentar describir tu estilo desde cero, puedes pedirle a la IA que **analice tu trabajo previo para extraer tu identidad** de forma automática,.
    
    Aquí tienes los pasos para lograrlo basándote en la metodología de las fuentes:
    
    1\. Preparación del "Material en Bruto"
    
    Reúne de 5 a 10 ejemplos reales de tu comunicación profesional que consideres exitosos o que mejor te representen. Pueden ser:
    
*   Correos electrónicos que cerraron una reunión,.
*   Publicaciones de LinkedIn con las que te sientas identificado,.
*   Mensajes de seguimiento o propuestas comerciales,.2\. El Prompt de Extracción de VozAbre un chat con Claude y pega esos textos. Utiliza un prompt como este para automatizar el análisis:_"Actúa como un experto en lingüística y comunicación comercial. Analiza estos ejemplos de mi escritura y genera el contenido para mi archivo_ **mi-voz.md**_. Debes extraer:_
    
    *   **Mi Tono:** _Identifica si es consultivo, directo, empático o técnico._
    *   **Frases Prohibidas:** _Identifica qué palabras típicas de IA (como 'potenciar' o 'ecosistema') NO aparecen en mis textos y deben evitarse._
    *   **Estructura recurrente:** _¿Cómo saludo? ¿Cómo cierro mis mensajes?_
    *   **Muestras de éxito:** _Selecciona los 3 mejores fragmentos cortos como ejemplos de referencia."_
    
    3\. Refinado y Formateo AutomatizadoUna vez que la IA te entregue el análisis, pídele que le dé el formato técnico adecuado:_"Ahora, organiza toda esa información en un bloque de código Markdown listo para copiar y pegar en un archivo llamado_ **mi-voz.md** _dentro de mi subcarpeta_ **SOBRE MÍ**_."_4\. Por qué este método es superior
*   **Evita la subjetividad:** A veces creemos que escribimos de una forma, pero los datos (tus textos reales) muestran otra. La IA detecta patrones que tú podrías pasar por alto, como el ratio de tiempo que dedicas a escuchar vs. hablar en tus textos,.
*   **Consistencia inmediata:** Al usar tus propios textos como base, aseguras que el "Vendedor Digital" que la IA potenciará sea una versión auténtica de ti mismo, no una imitación genérica,.
*   **Escalabilidad:** Una vez automatizado este archivo y vinculado a tus **Instrucciones Globales**, Claude aplicará ese estilo a cada propuesta, correo o post que le pidas en el futuro, permitiéndote escalar tu presencia de manera eficiente,.Nota importante: Aunque la IA automatice la redacción del archivo, las fuentes subrayan que el toque final siempre debe ser tuyo. Revisa el resultado para asegurarte de que la **empatía y la conexión emocional** (habilidades humanas insustituibles) estén bien reflejadas en las muestras seleccionadas,.
    
    ¿Qué archivos guardar en la subcarpeta PROYECTOS según el curso?
    
    Según la estructura de la carpeta maestra **"Claude-Trabajo"** detallada en las fuentes, en la subcarpeta **PROYECTOS** debes guardar **un archivo por cada proyecto que tengas activo** en ese momento.
    
    A diferencia de la carpeta **PLANTILLAS** (que guarda tu mejor trabajo pasado) o **SOBRE MÍ** (que guarda tu identidad), la carpeta **PROYECTOS** está diseñada para el trabajo en curso. Basándome en el contenido del curso, estos son ejemplos de lo que podrías incluir como un "proyecto activo":
    
*   **Prospección de una cuenta específica:** Un archivo con la investigación y el contexto de una empresa que estás intentando captar utilizando herramientas como Apollo u Ocean.
*   **Creación de un Buyer Persona:** El perfil detallado de un cliente ideal en el que estés trabajando actualmente para un nuevo mercado.
*   **Preparación de una propuesta comercial:** El borrador y los datos específicos de una negociación abierta que estés personalizando con ayuda de la IA.
*   **Simulación de un cierre:** Un documento con las objeciones reales que te ha planteado un cliente específico para practicar la respuesta con la IA antes de la reunión final.
*   **Plan de Onboarding:** Los pasos y notas específicas para el inicio de la relación con un nuevo cliente que acabas de cerrar.La clave de esta carpeta es que permite a Claude separar el contexto de un cliente "A" de un cliente "B", evitando que la información se mezcle y asegurando que cada respuesta sea precisa para el **proyecto específico** en el que estás trabajando.
    
    ¿Qué debo poner exactamente en el archivo sobre-mi.md?
    
    Para configurar correctamente tu archivo **sobre-mi.md** dentro de la subcarpeta **SOBRE MÍ**, debes enfocarte en proporcionar contexto operativo actual en lugar de un historial académico o laboral tradicional.
    
    De acuerdo con las fuentes, esto es exactamente lo que debes incluir:
    
*   **Tu día a día profesional:** Describe qué haces en tu jornada cotidiana, tus responsabilidades principales y los retos que enfrentas habitualmente. Las fuentes recalcan explícitamente: **"no pongas tu currículum"**.
*   **Tu identidad como vendedor:** Define tu rol actual. Las fuentes sugieren que el profesional moderno debe verse como un **vendedor digital** o un **consultor** que aporta valor desde el primer contacto, utilizando la tecnología para anticiparse a las necesidades del cliente.
*   **Tus pilares de trabajo:** Menciona cómo equilibras el uso de **datos, habilidades humanas (como la empatía y la escucha activa) y tecnología** en tu proceso comercial.
*   **Contexto de tu mercado:** Explica brevemente quiénes son tus clientes ideales o prospectos y qué problemas específicos les ayudas a resolver.
*   **Ejemplos reales, no descripciones:** En lugar de solo decir qué haces, las fuentes recomiendan **pegar ejemplos reales de tu trabajo** para que la IA entienda el contexto práctico de tus tareas.Estructura sugerida para el archivo:
    
    *   **Perfil Actual:** "Soy \[Tu Nombre\], responsable de desarrollo de negocio enfocado en \[Tu Sector\]. Mi objetivo es actuar como un consultor para mis clientes".
    *   **Responsabilidades Diarias:** "Mi día a día consiste en identificar prospectos de alta calidad, personalizar mensajes de alcance y gestionar el pipeline en el CRM".
    *   **Habilidades Clave:** "Priorizo la conexión emocional y la comunicación clara, apoyándome en la IA para las tareas operativas y repetitivas".
    *   **Flujo de Trabajo:** (Aquí puedes pegar un breve resumen de una propuesta exitosa o un esquema de cómo preparas una reunión real).
    
    Al completar este archivo con información sobre **quién eres y qué haces hoy**, permites que Claude deje de dar respuestas genéricas y se convierta en un asistente que realmente entiende tu entorno de trabajo.
    
    ¿Cómo puedo usar Claude para extraer mi tono de correos?
    
    Para usar Claude como una herramienta que extraiga tu tono real de tus correos electrónicos, debes pasar del modelo de "chat convencional" al modelo de **"Cowork"** y contexto maestro propuesto en las fuentes.
    
    Aquí tienes los pasos detallados para lograrlo:
    
    1\. Recopila tus "muestras de oro"
    
    No le describas a Claude cómo escribes; **muéstrale** cómo lo haces. Selecciona entre 3 y 5 correos electrónicos reales que hayas escrito y que consideres que mejor representan tu estilo profesional. Las fuentes recalcan que es fundamental usar **ejemplos reales de tu trabajo**, no descripciones teóricas.
    
    2\. El prompt de extracción de tonoAbre un chat en Claude (preferiblemente en modo **Cowork** habiendo indicado ya tu carpeta maestra) y pega tus correos con la siguiente instrucción:_"Actúa como un experto en comunicación y lingüística. Analiza estos correos electrónicos que he escrito y extrae mi 'ADN' de escritura para crear mi archivo_ **mi-voz.md**_. Identifica:_
*   **Mi Tono:** _¿Es consultivo, directo, empático o técnico?_
*   **Mis muletillas y estructuras:** _¿Cómo inicio y cierro? ¿Uso frases cortas o largas?_
*   **Lo que evito:** _Identifica qué palabras 'típicas' de vendedor o de IA no suelo usar."_3\. Organiza la información en mi-voz.mdUna vez que Claude te dé el análisis, guarda esa información en un archivo llamado **mi-voz.md** dentro de tu subcarpeta **SOBRE MÍ** (la cual debe estar dentro de tu carpeta maestra **Claude-Trabajo**).El archivo debe quedar estructurado así:
*   **Tono:** (Ej: Profesional pero cercano, enfocado en aportar valor desde el primer contacto).
*   **Frases que odias:** Palabras que Claude detectó que no usas o que quieres prohibir expresamente para no sonar como un robot.
*   **Muestras de escritura:** Pega aquí los 2 o 3 correos que usaste para el análisis como referencia constante para la IA.4\. Configura el uso automático (Instrucciones Globales)Para que no tengas que pedirle a Claude que use tu tono en cada nuevo correo, configura las **Instrucciones Globales** en la sección de Cowork:
    
    *   Ve a **Configuración → Cowork → Editar Instrucciones Globales**.
    *   Redacta: "Soy \[Tu Nombre\], \[Tu Rol\]. Lee mi archivo **mi-voz.md** _en la carpeta_ **SOBRE MÍ** _antes de redactar cualquier mensaje para imitar mi tono exacto"_.
    
    ¿Por qué hacer esto?Al automatizar la extracción de tu tono, permites que la IA **amplifique tus habilidades humanas** (como la empatía y la creatividad) en lugar de reemplazarlas con textos genéricos. Esto te permite ser un profesional más **estratégico que táctico**, escalando tu personalización en cada interacción comercial de manera eficiente.
    
    Dame una lista de palabras prohibidas comunes para mi-voz.md
    
    Para que tu archivo **mi-voz.md** sea realmente efectivo y logre que Claude deje de sonar como un robot, debes incluir una lista de palabras y expresiones que "delatan" el uso de inteligencia artificial o que resultan demasiado genéricas en el ámbito de las ventas digitales. El objetivo es alejarse de los **"mensajes genéricos"** que no aportan valor y que suelen ser ignorados por los prospectos.
    
    Aquí tienes una lista detallada de palabras prohibidas dividida por categorías, basada en las fuentes y nuestra conversación:
    
    1\. Clichés típicos de la IA (Las que te hacen parecer un bot)
    
    Estas palabras son las que la IA utiliza por defecto y que debes prohibir para mantener tu **autenticidad**:
    
*   **"Potenciar" / "Empoderar":** Términos extremadamente usados por modelos de lenguaje para describir mejoras.
*   **"En el dinámico mundo de hoy":** O variantes como "En el ecosistema actual" o "En el panorama cambiante". Son rellenos que no aportan los **insights relevantes** que busca un cliente.
*   **"Revolucionar" / "Disruptivo":** Palabras desgastadas que suelen sonar a promesa vacía en lugar de a una solución real basada en datos.
*   **"Un viaje hacia...":** Ejemplo: "Acompáñame en este viaje hacia la transformación digital".
*   **"Desbloquear":** Especialmente cuando se refiere a "desbloquear el potencial".2\. Jerga corporativa vacía (Buzzwords)Palabras que entorpecen la **comunicación clara** y la **empatía**, que son habilidades humanas insustituibles:
*   **"Sinergia":** Suena anticuado y poco natural para un perfil de **consultor** moderno.
*   **"Soluciones 360":** Una frase trillada que no explica el valor real y diferenciado de tu oferta.
*   **"Añadir valor":** En lugar de usar esta frase, las fuentes sugieren **describir específicamente el valor** que aportas.
*   **"Optimización de procesos":** Es mejor usar un lenguaje más directo y cercano al cliente.3\. Aperturas y cierres genéricosEvita las fórmulas que delatan un proceso manual y repetitivo del pasado:
*   **"Espero que este mensaje te encuentre bien":** Es la apertura estándar de la IA. Es preferible ir directo al grano con un problema que puedas resolver o una oportunidad específica.
*   **"Sin compromiso":** Esta frase puede debilitar tu posición de consultor experto.
*   **"Solo te escribo para...":** Transmite falta de seguridad. Si tienes una narrativa con **insights relevantes**, no necesitas disculparte.4\. Estándares estéticos y visuales (Si generas contenido)Si utilizas la IA para crear propuestas o presentaciones visuales (como en Canva o HeyGen), las fuentes técnicas recomiendan evitar:
*   **"Colores neón agresivos" o "oversaturated":** Debes pedir colores **"Sophisticated Muted"** (tonos tierra o desaturados) para una apariencia más profesional.
*   **"Sombras duras":** Se debe buscar una iluminación de estudio suave y difusa.
*   **"Degradados (Gradients)":** Se prefieren bloques de color planos y mate para una estética limpia y moderna.Instrucción de implementación:En tu archivo mi-voz.md, dentro de la subcarpeta **SOBRE MÍ**, crea un apartado llamado \## FRASES QUE ODIAS y pega esta lista. Esto obligará a Claude a buscar alternativas más humanas y alineadas con tu estilo de **vendedor digital**.