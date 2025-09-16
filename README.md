# Curso-IA

Curso Introductorio a la Inteligencia Artificial

## Lista de enlaces importantes para administrar nuestra cuenta Google

Vamos a usar nuestra cuenta Google para registrarnos en distintos servicios gratuitos. Para esto es importante saber administrar los accesos a sitios de terceros con mi cuenta de google. Esto permite, entre otras cosas eliminar los accesos que no nos interese mantener activos:

- [https://myaccount.google.com/connections?hl=es](https://myaccount.google.com/connections?hl=es)

Otro elemento importante a tener en cuenta para nuestra actividad digital en general en Google es exportar "mis datos" recopilados por Google. Es mucha la información que puede tener Google o Mac sobre nosotros y es importante poder tenerla nosotros también, además podemos usarlas como data de entrenamiento de "nuestras" IA's provadas:

- [https://takeout.google.com/?hl=es](https://takeout.google.com/?hl=es)

El historial de actividad de Google es otra información importante sobre nosotros mismos que incluye nuestro uso de Youtube.

- [https://myactivity.google.com/myactivity?hl=es](https://myactivity.google.com/myactivity?hl=es)

## Curso de Introducción a la Inteligencia Artificial para Profesionales

**Dictado en Paraná, Entre Ríos**
**Por: Santiago Chávez Novaro** (Museo Virtual de Matemáticas de la SMM, México)

## Objetivo del programa

Proporcionar a profesionales de cualquier disciplina una comprensión sólida, accesible y crítica de los fundamentos matemáticos, técnicos y geopolíticos que sustentan los sistemas de IA actualmente en uso, con especial énfasis en modelos de lenguaje. Al finalizar, los participantes podrán interactuar con estos sistemas de manera segura, eficiente y contextualizada, identificando sus límites y potencialidades.

## PRIMERA SESIÓN

### 0. Breve introducción a la interfaz de Meet que usaremos para las sesiones

Unirse a la sesión, levantar la mano, usar el Chat.

### 1. Construcción de intuiciones matemáticas

**Título:** *Pensar la IA sin fórmulas*
**Herramienta:** [https://sanxofon.github.io/fondo-del-mar](https://sanxofon.github.io/fondo-del-mar)
**Descripción:** Desarrollaremos una visión intuitiva de los procesos algebraicos y estadísticos que permiten a un modelo generar texto útil, sin recurrir a notación avanzada. El objetivo es que cada participante "sienta" por qué los números se transforman en palabras coherentes.

### 2. Tokenización: el primer corte del lenguaje

**Título:** *De las letras a los fragmentos significativos*
**Herramienta:** Pizarra blanca (Inkodo)
**Descripción:** Explicaremos por qué los modelos no leen palabras completas sino "tokens", cómo se construye ese vocabulario fragmentado y por qué la elección de token afecta la calidad y el costo de la respuesta.

### 3. Embeddings: coordenadas del significado

**Título:** *Ubicar ideas en un mapa de vectores*
**Herramienta:** [https://phet.colorado.edu/es/simulations/vector-addition](https://phet.colorado.edu/es/simulations/vector-addition)
**Descripción:** Presentaremos la noción de "embeddings" como una grilla estadística donde frases similares quedan vecinas. Veremos su papel dentro de bases de datos vectoriales y cómo esa proximidad permite búsquedas semánticas rápidas y precisas.

### 4. Grandes Modelos de Lenguaje (LLM)

**Título:** *¿Qué significa "entender" para una máquina?*
**Herramientas:** [https://archive.org](https://archive.org/) y [https://annas-archive.org](https://annas-archive.org/)
**Descripción:** Analizaremos la arquitectura simplificada de un LLM y por qué su capacidad de predecir el siguiente token se traduce en aparente comprensión. Discutiremos la diferencia entre memorización estadística y razonamiento genuino.

### 5. Tipos de entrada-salida más allá del texto

**Título:** *Imagen, voz, código: el mismo motor con distintos lentes*
**Herramientas:** [https://aistudio.google.com](https://aistudio.google.com)
**Descripción:** Repasaremos cómo un mismo núcleo puede aceptar y generar distintos formatos (imagen, audio, tablas, código fuente) y qué implicancias tiene esto para flujos de trabajo profesionales mixtos.

### 6. Los tres pilares del rendimiento

**Título:** *Datos, cómputo y matemática: la ecuación invisible*
**Descripción:** Profundizaremos en por qué el salto cualitativo de la IA actual proviene de la escala (cantidad de datos), el hardware especializado (GPUs/TPUs) y algoritmos que refinan el error de forma incremental y masiva.

### 7. Geopolítica de la IA

**Título:** *Mapas de poder más allá de los mapas de datos*
**Herramientas:** [https://grok.com/](https://grok.com/), [https://chat.qwen.ai](https://chat.qwen.ai)
**Descripción:** Introducción crítica a la concentración de recursos, la hegemonía lingüística del inglés y las estrategias soberanas que emergen en otros idiomas y regiones, incluyendo el español rioplatense.

## SEGUNDA SESIÓN

### 8. Prompting con base matemática

**Título:** *Instrucciones que guían la distribución de probabilidades. Repaso general*
**Descripción:** A partir de la intuición desarrollada en el módulo 1, reformularemos los principios básicos del prompting como formas de sesgar estadísticamente la salida sin caer en trucos ocultos ni mitos de "magia conversacional".

### 9. Seguridad y privacidad en modelos en línea

**Título:** *A dónde viaja tu prompt*
**Descripción:** Examinaremos la dispersión de datos que ocurre al usar servicios cloud, los riesgos de derivación, filtraciones y competencia corporativa, y evaluar si un proveedor garantiza confidencialidad real.

### 10. Markdown y editores con IA integrada

**Título:** *Escribir código y texto con asistencia local*
**Descripción:** Introducción práctica al lenguaje de marcado ligero Markdown y a editores que incorporan sugerencias de IA sin salir del equipo, permitiendo versionado claro y control total del contenido.

**Visual Studio Code:** [code.visualstudio.com](https://code.visualstudio.com/)
Descarga este programa para crear, organizar y probar tus PROMPTS y datos estructurados para los Modelos Grandes de Lenguaje (LLM). Es gratuito y de código abierto. Descarga el instalador para tu sistema operativo (Windows, Mac o Linux) e instala.

### 11. Prompting avanzado: construcción de contexto

**Título:** *Del chat vacío al entorno especializado*
**Descripción:** Aprenderemos a diseñar bloques de contexto (metadatos, historial, instrucciones dinámicas) que reduzcan la ambigüedad y aumenten la consistencia de las respuestas en tareas profesionales complejas.

1. **El modelo solo distribuye probabilidades**
   *Definición:* un LLM es un generador de probabilidades condicionadas P(token | contexto). Es decir que siempre busca la palabra que le "parece" que sigue.
   *Explicación:* al escribir un prompt fijamos el contexto; cambiar una palabra desplaza toda la distribución y altera la respuesta sin que el modelo "razone". O sea que cambiar una palabra en tu pregunta hace que el modelo elija otra distinta como la "siguiente"; no piensa, sólo cuenta probabilidades.

2. **Sesgar, no ordenar**
   *Definición:* el prompting empuja la masa de probabilidad hacia zonas deseadas.
   *Explicación:* pedir "responde como abogado" hace más probable el vocabulario jurídico, pero no garantiza certeza. Decir “actuá como maestro” empuja la respuesta hacia palabras de clase o de escuela. No fuerza, pero sí hace ese estilo más probable.

3. **Longitud útil vs. longitud total**
   *Definición:* la información relevante decae con la distancia en tokens.
   *Explicación:* **lo importante va al final** y/o **se repite**, así aumentamos su peso probabilístico.

4. **Temperatura y top-p**
   *Definición:* temperatura (T) expande o comprime la distribución; top-p recorta la cola de baja probabilidad.
   *Explicación:* estos números controlan si la respuesta es más segura o sorprendente. Una top-p baja (0.2) = más serio; alta (0.9) = más inventiva.

5. **Few-shot = estimador de máxima verosimilitud**
   *Definición:* los ejemplos ajustan implícitamente P(output | input).
   *Explicación:* dar 2 o 3 ejemplos ayuda al modelo a copiar el formato. Si los ejemplos tienen sesgo, el modelo lo reproducirá. Si los ejemplos tienen errores, el modelo los repite; revisalos antes.

6. **Roles y metainstrucciones como prior suave**
   *Definición:* "actúa como…" también modifica la probabilidad previa de ciertos tokens. Empezar con “Sos un traductor” ahorra explicaciones.
   *Explicación:* no cambia los pesos, pero reduce la entropía inicial y acorta la búsqueda. Le dice al modelo qué parte del “mapa de palabras” usar.

7. **Evaluación cuantitativa rápida**
   *Definición:* medir la variabilidad de log-prob entre respuestas compara prompts sin leer todo. Mandar la misma pregunta dos veces y ver qué tan distintas son las respuestas.
   *Explicación:* baja variabilidad suele indicar mayor confiabilidad. Si cambian mucho las respuestas del modelo, tu prompt es ambiguo; afinalo hasta que se estabilicen.

### 12. Prompting sobre datos estructurados

**Título:** *Pedirle al modelo que "lea" datos organizados sin equivocarse*
**Descripción:** Estrategias para instruir a la IA sobre esquemas, tipos de datos y validaciones, minimizando alucinaciones numéricas y garantizando salidas reproducibles.
**Guía en línea de formato JSON para principiantes:** [youtube.com/watch?v=YYfediyCwAU](https://www.youtube.com/watch?v=YYfediyCwAU)

### 13. Modelos locales y código abierto

**Título:** *IA bajo techo: privacidad, costo y hardware*
**Descripción:** Repaso de modelos abiertos disponibles, sus tamaños (GB y parámetros), requerimientos mínimos de GPU/RAM y cómo decidir cuándo un despliegue local es viable y rentable para el ámbito profesional.
**Modelos de lenguaje en nuestra propia computadora:** Descarga e instala el programa gratuito **[GPT4All](https://www.nomic.ai/gpt4all)**. Una vez instalado puedes añadirle muy fácilmente algún modelo de lenguaje de código abierto y chatear con una IA a nivel local de forma segura y sin necesidad de conexión a internet.

---

### Herramientas a utilizar en las Sesiones

**Modelos LLM para chat en línea**

EEUU:

- [https://aistudio.google.com](https://aistudio.google.com)
- [https://chatgpt.com/](https://chatgpt.com/)
- [https://www.meta.ai/](https://www.meta.ai/)
- [https://grok.com/](https://grok.com/)
- [https://claude.ai/](https://claude.ai/)

FRANCIA:

- [https://chat.mistral.ai](https://chat.mistral.ai)

CHINA:

- [https://chat.qwen.ai](https://chat.qwen.ai)
- [https://chat.deepseek.com/](https://chat.deepseek.com/)

Internacionales (Cede en UK)

- [https://huggingface.co/chat/](https://huggingface.co/chat/)

PRIVADO. Modelos pequeños.

- [https://duckduckgo.com/?q=DuckDuckGo+AI+Chat&ia=chat&duckai=1](https://duckduckgo.com/?q=DuckDuckGo+AI+Chat&ia=chat&duckai=1)

**Software recomendado para uso local de modelos en línea o locales.**

Visual Studio Code. Editor y uso de IA copilot

- [https://code.visualstudio.com/](https://code.visualstudio.com/)

GPT4All. Chatea seguro y privado con modelos abiertos de forma 100% local

- [https://www.nomic.ai/gpt4all](https://www.nomic.ai/gpt4all)

### Recomendaciones y Materiales incluidos

- Las sesiones son vía Meet (Google). Se recomienda a cada usuario tener una cuenta google (GMail) activa en su navegador durante el curso.
- Esta Guía del curso que seguiremos en línea cada uno desde su Computadora (PC, Mac, Linux)
- Mira la [lista de herramientas](lista.html) en línea abiertas y/o gratuitas de diversos países con descripciones.
