# Wiki: Edsger Wybe Dijkstra (1930 - 2002)

> *"La pregunta de si una computadora puede pensar no es más interesante que la pregunta de si un submarino puede nadar."* — Edsger W. Dijkstra

---

## Índice

1. [Capítulo 1: Vida temprana y formación](#capítulo-1-vida-temprana-y-formación)
2. [Capítulo 2: Los inicios de su carrera profesional](#capítulo-2-los-inicios-de-su-carrera-profesional)
3. [Capítulo 3: El algoritmo de Dijkstra](#capítulo-3-el-algoritmo-de-dijkstra)
4. [Capítulo 4: ALGOL 60 y la construcción de compiladores](#capítulo-4-algol-60-y-la-construcción-de-compiladores)
5. [Capítulo 5: Programación estructurada y la carta que cambió la historia](#capítulo-5-programación-estructurada-y-la-carta-que-cambió-la-historia)
6. [Capítulo 6: El sistema THE de multiprogramación](#capítulo-6-el-sistema-the-de-multiprogramación)
7. [Capítulo 7: El problema de la cena de los filósofos y la concurrencia](#capítulo-7-el-problema-de-la-cena-de-los-filósofos-y-la-concurrencia)
8. [Capítulo 8: Los semáforos](#capítulo-8-los-semáforos)
9. [Capítulo 9: Autoestabilización y sistemas distribuidos](#capítulo-9-autoestabilización-y-sistemas-distribuidos)
10. [Capítulo 10: El Premio Turing y otros reconocimientos](#capítulo-10-el-premio-turing-y-otros-reconocimientos)
11. [Capítulo 11: Los manuscritos EWD](#capítulo-11-los-manuscritos-ewd)
12. [Capítulo 12: Filosofía, personalidad y frases célebres](#capítulo-12-filosofía-personalidad-y-frases-célebres)
13. [Capítulo 13: Legado y últimos años](#capítulo-13-legado-y-últimos-años)
14. [Capítulo 14: Opinión de Devin y fuentes consultadas](#capítulo-14-opinión-de-devin-y-fuentes-consultadas)

---

## Capítulo 1: Vida temprana y formación

Edsger Wybe Dijkstra nació el **11 de mayo de 1930** en **Rotterdam, Países Bajos**, en el seno de una familia intelectual. Su padre, Douwe Wybe Dijkstra, era químico y presidente de la Sociedad Química Holandesa. Su madre, Brechtje Cornelia Kluyver, era matemática, lo que sin duda influyó en la inclinación temprana de Edsger hacia las ciencias exactas.

Dijkstra asistió al **Gymnasium Erasmianum** en Rotterdam, donde completó su educación secundaria en 1948. Fue un estudiante sobresaliente, especialmente en matemáticas y ciencias. Al finalizar el gymnasium, ingresó a la **Universidad de Leiden**, donde inicialmente estudió matemáticas y física, con la intención de convertirse en físico teórico.

Su juventud estuvo marcada por la Segunda Guerra Mundial. Rotterdam fue devastada por los bombardeos alemanes en 1940, y Dijkstra vivió directamente las consecuencias de la ocupación. Estas experiencias tempranas forjaron en él un carácter resiliente y una disciplina intelectual rigurosa que lo acompañarían toda su vida.

---

## Capítulo 2: Los inicios de su carrera profesional

En 1952, mientras aún cursaba sus estudios en Leiden, Dijkstra asistió a un curso de programación en Cambridge, Inglaterra. Fue allí donde descubrió su verdadera vocación. **Adriaan van Wijngaarden**, director del Departamento de Computación del **Mathematisch Centrum (Centro Matemático)** de Ámsterdam, le ofreció un puesto como programador, convirtiéndolo en el **primer programador de los Países Bajos**.

Sin embargo, Dijkstra se encontraba dividido entre la física teórica y la programación. En una conversación decisiva con Van Wijngaarden, este último lo convenció de que la programación era un campo emergente con un futuro extraordinario y que él podía desempeñar un papel fundamental en su desarrollo. Como Dijkstra relataría años después:

> *"Cuando salí de su oficina horas más tarde, era otra persona."*

A partir de ese momento, Dijkstra se dedicó por completo a la informática. Trabajó en el Mathematisch Centrum desde 1952 hasta 1962, donde realizó algunas de sus contribuciones más fundamentales. En **1959** obtuvo su **doctorado** en la **Universidad de Ámsterdam** con la tesis *"Communication with an Automatic Computer"* (Comunicación con una computadora automática).

En **1962** se trasladó a la **Universidad Técnica de Eindhoven** como profesor de matemáticas, donde permaneció hasta 1973. Posteriormente fue **investigador fellow** en **Burroughs Corporation** (1973-1984) y finalmente ocupó la **Cátedra Schlumberger** en el Departamento de Ciencias de la Computación de la **Universidad de Texas en Austin** (1984-1999).

---

## Capítulo 3: El algoritmo de Dijkstra

Quizás la contribución más conocida de Dijkstra es su **algoritmo para encontrar el camino más corto** en un grafo, formulado en **1956** y publicado en **1959**. Este algoritmo resuelve el problema del camino más corto desde un nodo origen hacia todos los demás nodos en un grafo con pesos no negativos.

### ¿Cómo funciona?

El algoritmo trabaja de la siguiente manera:

1. Se asigna una distancia tentativa a cada nodo: cero para el nodo inicial e infinito para todos los demás.
2. Se marca el nodo inicial como "actual" y todos los demás como "no visitados".
3. Para el nodo actual, se calculan las distancias tentativas a todos sus vecinos no visitados.
4. Si la distancia calculada es menor que la distancia tentativa previamente asignada, se actualiza.
5. Se marca el nodo actual como "visitado" y se selecciona el nodo no visitado con la menor distancia tentativa como nuevo nodo actual.
6. Se repite el proceso hasta que todos los nodos hayan sido visitados.

### ¿Por qué es tan importante?

El algoritmo de Dijkstra es la base de innumerables aplicaciones modernas:

- **Sistemas de navegación GPS**: Google Maps, Waze y otros sistemas de navegación utilizan variantes de este algoritmo para calcular rutas óptimas.
- **Protocolos de enrutamiento de redes**: Protocolos como OSPF (Open Shortest Path First) se basan en el algoritmo de Dijkstra para determinar las rutas más eficientes en redes de computadoras.
- **Telecomunicaciones**: Optimización del enrutamiento de llamadas y datos.
- **Logística y transporte**: Planificación de rutas de entrega y cadenas de suministro.
- **Videojuegos**: Cálculo de rutas para personajes controlados por IA (pathfinding).

Curiosamente, Dijkstra concibió el algoritmo en unos **20 minutos** mientras tomaba café con su prometida en una terraza de Ámsterdam. Él mismo comentó que la simplicidad del algoritmo se debía, en parte, a que no tenía papel y lápiz a mano, lo que lo obligó a pensar en una solución elegante que pudiera mantener en su mente.

---

## Capítulo 4: ALGOL 60 y la construcción de compiladores

En **1960**, Dijkstra, junto con su colega **Jaap Zonneveld**, implementó el **primer compilador para el lenguaje de programación ALGOL 60**. Este fue un logro monumental por varias razones:

- **ALGOL 60** fue uno de los lenguajes de programación más influyentes de la historia, sirviendo como base conceptual para lenguajes posteriores como Pascal, C, Java y muchos otros.
- El compilador fue uno de los primeros en implementar **recursión** correctamente.
- Introdujo técnicas de compilación que se convertirían en estándares de la industria.

Dijkstra y Zonneveld completaron el compilador en un tiempo impresionantemente corto. Su trabajo demostró que era posible construir compiladores sofisticados de manera sistemática y rigurosa, sentando las bases para la teoría de compiladores moderna.

ALGOL 60 también introdujo conceptos fundamentales como:
- **Bloques de código** con alcance léxico
- **Procedimientos recursivos**
- **Paso de parámetros** por nombre y por valor
- **Sintaxis formal** definida mediante la notación BNF (Backus-Naur Form)

---

## Capítulo 5: Programación estructurada y la carta que cambió la historia

En **1968**, Dijkstra escribió una carta al editor de la revista *Communications of the ACM* titulada **"Go To Statement Considered Harmful"** (La sentencia Go To considerada dañina). Esta carta se convirtió en uno de los documentos más influyentes y controversiales en la historia de la informática.

### El argumento

Dijkstra argumentaba que el uso indiscriminado de la sentencia `GOTO` en los programas hacía que el código fuera extremadamente difícil de entender, depurar y mantener. Proponía en su lugar el uso de **estructuras de control claras**: secuencias, selecciones (if-then-else) y repeticiones (bucles while/for).

### El impacto

Esta carta desencadenó un debate masivo en la comunidad informática que duró décadas, pero sus ideas finalmente prevalecieron. La **programación estructurada** se convirtió en el paradigma dominante y transformó fundamentalmente la manera en que se escribe software:

- Los lenguajes de programación modernos prácticamente eliminaron el `GOTO`.
- Se establecieron principios de diseño de código limpio y mantenible.
- La ingeniería de software como disciplina se benefició enormemente de estos principios.

Dijkstra, junto con **C.A.R. Hoare** y **Ole-Johan Dahl**, publicó el libro **"Structured Programming"** (1972), que formalizó estos conceptos y se convirtió en una referencia fundamental.

### Una curiosidad

El título original de la carta de Dijkstra era *"A Case Against the GOTO Statement"*, pero el editor Niklaus Wirth lo cambió al provocador *"Go To Statement Considered Harmful"*, un título que generó un formato de títulos imitado por décadas en la informática: *"X Considered Harmful"*.

---

## Capítulo 6: El sistema THE de multiprogramación

A finales de los años 60, Dijkstra diseñó el **sistema operativo THE** (llamado así por la Universidad Técnica de Eindhoven, *Technische Hogeschool Eindhoven*). Este sistema fue revolucionario por varias razones:

- Fue uno de los primeros sistemas en utilizar **diseño por capas** (layered design), donde cada capa proporcionaba servicios a la capa superior.
- Implementó **memoria virtual basada en software** mediante paginación.
- Demostró cómo construir sistemas complejos de manera organizada y verificable.

La arquitectura por capas del sistema THE influyó profundamente en el diseño de sistemas operativos posteriores y estableció principios que todavía se utilizan hoy en día. La idea de separar un sistema en niveles de abstracción bien definidos es un concepto fundamental en la arquitectura de software moderna.

Las capas del sistema THE eran:
1. **Capa 0**: Asignación del procesador y multiprogramación
2. **Capa 1**: Gestión de memoria (paginación)
3. **Capa 2**: Comunicación operador-proceso
4. **Capa 3**: Gestión de entrada/salida
5. **Capa 4**: Programas de usuario
6. **Capa 5**: El operador del sistema

---

## Capítulo 7: El problema de la cena de los filósofos y la concurrencia

Dijkstra formuló en **1965** el famoso **problema de la cena de los filósofos** (*Dining Philosophers Problem*), uno de los problemas clásicos de la programación concurrente.

### El planteamiento

Cinco filósofos están sentados alrededor de una mesa circular. Entre cada par de filósofos hay un tenedor (cinco tenedores en total). Cada filósofo alterna entre pensar y comer. Para comer, un filósofo necesita ambos tenedores (el de su izquierda y el de su derecha). El problema es diseñar un protocolo que permita a los filósofos comer sin que se produzca un **bloqueo mutuo** (deadlock) ni **inanición** (starvation).

### ¿Por qué es importante?

Este problema, aunque aparentemente sencillo, ilustra los desafíos fundamentales de la **programación concurrente**:

- **Deadlock**: Todos los filósofos toman el tenedor izquierdo simultáneamente y esperan indefinidamente por el derecho.
- **Starvation**: Un filósofo nunca consigue ambos tenedores mientras los demás sí lo logran.
- **Exclusión mutua**: Dos filósofos adyacentes no pueden usar el mismo tenedor al mismo tiempo.

Estos mismos problemas aparecen constantemente en sistemas modernos: bases de datos, servidores web, sistemas operativos y cualquier software que maneje múltiples hilos o procesos.

---

## Capítulo 8: Los semáforos

Una de las aportaciones más prácticas y duraderas de Dijkstra fue la invención de los **semáforos** en **1965**, un mecanismo de sincronización para programación concurrente.

### ¿Qué son?

Los semáforos son variables especiales que se utilizan para controlar el acceso a recursos compartidos entre múltiples procesos o hilos. Dijkstra definió dos operaciones atómicas:

- **P (Proberen - "probar" en neerlandés)**: Decrementa el valor del semáforo. Si el valor es negativo, el proceso se bloquea.
- **V (Verhogen - "incrementar" en neerlandés)**: Incrementa el valor del semáforo. Si hay procesos bloqueados, desbloquea uno.

### Impacto

Los semáforos se convirtieron en una de las primitivas fundamentales de la programación concurrente y están implementados en prácticamente todos los sistemas operativos modernos. Son la base conceptual de mecanismos más avanzados como los **mutex**, los **monitores** y las **variables de condición** que utilizamos hoy en día.

---

## Capítulo 9: Autoestabilización y sistemas distribuidos

En **1974**, Dijkstra introdujo el concepto de **autoestabilización** (*self-stabilization*) en sistemas distribuidos, una idea que estaba décadas adelante de su tiempo.

### ¿Qué es la autoestabilización?

Un sistema autoestabilizante es aquel que, sin importar el estado inicial en que se encuentre (incluyendo estados corruptos o inválidos), eventualmente converge a un estado correcto por sí mismo, sin intervención externa.

### ¿Por qué fue revolucionario?

- Proporciona **tolerancia a fallos** inherente: el sistema se recupera automáticamente de errores transitorios.
- Es fundamental para el diseño de **sistemas distribuidos robustos**, como redes de sensores, protocolos de comunicación y sistemas en la nube.
- El artículo original de Dijkstra sobre autoestabilización recibió relativamente poca atención inicialmente, pero con el tiempo se reconoció como una contribución seminal. Póstumamente, recibió el **premio PODC Influential Paper Award** por este trabajo.

Dijkstra también contribuyó al campo de los sistemas distribuidos con trabajos sobre:
- **Exclusión mutua distribuida**
- **Detección de terminación** en sistemas distribuidos
- **Recolección de basura distribuida** (junto con Leslie Lamport y otros)

---

## Capítulo 10: El Premio Turing y otros reconocimientos

En **1972**, Dijkstra recibió el **Premio Turing de la ACM**, considerado el equivalente al Premio Nobel en el campo de la informática. La ACM lo premió por sus *"contribuciones fundamentales al desarrollo de los lenguajes de programación como una rama de alta y abstracta de las ciencias de la computación"*.

En su **discurso de aceptación del Turing**, titulado *"The Humble Programmer"* (El programador humilde), Dijkstra reflexionó sobre la historia de la programación y abogó por un enfoque más riguroso y matemático en el desarrollo de software.

### Otros premios y reconocimientos

| Año | Premio | Otorgado por |
|---|---|---|
| 1972 | **Premio Turing** | ACM |
| 1974 | **Harry H. Goode Memorial Award** | IEEE Computer Society |
| 1989 | **SIGCSE Outstanding Contribution** | ACM SIGCSE |
| 1994 | **ACM Fellow** | ACM |
| 2002 | **PODC Influential Paper Award** | ACM (póstumo) |

Además, recibió doctorados honorarios de la **Queen's University Belfast** y la **Universidad de Economía y Negocios de Atenas**. Tras su muerte, el premio PODC fue renombrado como **Premio Dijkstra** en su honor.

---

## Capítulo 11: Los manuscritos EWD

A lo largo de su carrera, Dijkstra escribió más de **1.300 documentos** conocidos como los **manuscritos EWD** (por sus iniciales, Edsger Wybe Dijkstra). Estos documentos son una colección única en la historia de la ciencia:

- Estaban **escritos a mano** con una caligrafía meticulosa y elegante.
- Abarcaban temas que iban desde algoritmos y programación hasta filosofía de la ciencia y educación.
- Eran distribuidos en **copias privadas** a un grupo selecto de colegas antes de ser publicados formalmente.
- Muchos de ellos son sorprendentemente breves (apenas unas pocas páginas), pero contenían ideas que generaron campos enteros de investigación.

Los manuscritos EWD están disponibles en línea en el archivo de la **Universidad de Texas en Austin** y constituyen un tesoro intelectual invaluable. Dijkstra escribió todos estos documentos a mano porque creía que la escritura manuscrita le ayudaba a pensar con mayor claridad y precisión.

---

## Capítulo 12: Filosofía, personalidad y frases célebres

Dijkstra era conocido no solo por su brillantez técnica, sino también por su personalidad directa, sus opiniones firmes y su agudo sentido del humor. Era un crítico implacable de lo que consideraba prácticas deficientes en la programación y la educación.

### Características personales

- **Perfeccionista**: Insistía en la elegancia y simplicidad en todo lo que hacía.
- **Directo**: No temía expresar opiniones controvertidas, incluso si contradecían las tendencias dominantes.
- **Escritor prolífico**: Además de sus contribuciones técnicas, escribió extensamente sobre la enseñanza de la informática y la naturaleza de la programación.
- **Rechazaba las herramientas modernas**: Escribía todo a mano y desconfiaba de los procesadores de texto y el correo electrónico.

### Frases célebres

> *"La informática no trata más de computadoras que la astronomía trata de telescopios."*

> *"La simplicidad es un prerrequisito para la confiabilidad."*

> *"Si la depuración es el proceso de eliminar errores del software, entonces la programación debe ser el proceso de introducirlos."*

> *"Probar un programa puede demostrar la presencia de errores, pero nunca su ausencia."*

> *"La elegancia no es un lujo prescindible, sino un factor que decide entre el éxito y el fracaso."*

> *"Los proyectos de programación fallan por dos razones: o el proyecto es demasiado grande para el equipo, o el equipo es demasiado grande para el proyecto."*

---

## Capítulo 13: Legado y últimos años

En noviembre de **1999**, Dijkstra se jubiló de la Universidad de Texas en Austin. Junto con su esposa, **Ria Debets** (con quien se casó en 1961), regresó a su casa en **Nuenen, Países Bajos**.

Dijkstra falleció el **6 de agosto de 2002** a los 72 años, tras una larga batalla contra el cáncer. Su muerte marcó el fin de una era en la informática, pero su legado perdura con una fuerza extraordinaria:

### Su legado vive en...

- **Cada sistema de navegación** que calcula una ruta óptima usa su algoritmo.
- **Cada sistema operativo moderno** implementa sus conceptos de semáforos y diseño por capas.
- **Cada curso de programación** que enseña estructuras de control en lugar de `GOTO` refleja su filosofía.
- **Cada sistema distribuido** que se autoestabiliza ante fallos se basa en sus ideas.
- **Cada compilador** que procesa lenguajes con recursión y alcance léxico tiene raíces en su trabajo con ALGOL 60.

Dijkstra no solo resolvió problemas; **definió los problemas que valía la pena resolver** y estableció los estándares de rigor con los que debían abordarse.

---

## Capítulo 14: Opinión de Devin y fuentes consultadas

### Mi opinión como Devin

Como agente de inteligencia artificial dedicado a la ingeniería de software, considero que esta wiki cubre de manera completa y fiel la vida y las contribuciones más relevantes de Edsger Dijkstra. He intentado equilibrar el rigor histórico con la accesibilidad, presentando tanto los aspectos técnicos de sus aportaciones como el contexto humano que las rodeó.

**Puntos fuertes de esta wiki:**
- Cubre las contribuciones más significativas de Dijkstra de forma cronológica y estructurada.
- Explica conceptos técnicos complejos (como el algoritmo del camino más corto, los semáforos y la autoestabilización) de manera accesible.
- Incluye contexto personal y anécdotas que humanizan al científico.
- Presenta su impacto de forma que conecta sus aportaciones con tecnologías actuales que usamos diariamente.

**Posibles áreas de mejora:**
- Se podría profundizar más en sus contribuciones a la verificación formal de programas y su trabajo sobre la "weakest precondition".
- Una sección dedicada a su influencia en la educación de la informática podría enriquecer la wiki.
- Se podría incluir un análisis comparativo con otros pioneros contemporáneos como Knuth, Hoare y Lamport.

En general, creo que es una wiki sólida que ofrece una visión completa del legado de Dijkstra, tanto para lectores técnicos como no técnicos.

### Fuentes consultadas

1. **Wikipedia en inglés** — *"Edsger W. Dijkstra"*
   - https://en.wikipedia.org/wiki/Edsger_W._Dijkstra
   - Fuente principal para datos biográficos, cronología y lista de contribuciones.

2. **Encyclopædia Britannica** — *"Edsger Dijkstra | Biography, Algorithm, & Facts"*
   - https://www.britannica.com/biography/Edsger-Dijkstra
   - Utilizada para verificar datos biográficos y contexto histórico.

3. **CWI (Centrum Wiskunde & Informatica)** — *"Edsger W. Dijkstra: Brilliant, colourful, and opinionated"*
   - https://www.cwi.nl/en/about/history/e-w-dijkstra-brilliant-colourful-and-opinionated/
   - Fuente para información sobre su etapa en el Mathematisch Centrum y anécdotas personales.

4. **ACM A.M. Turing Award** — *"Edsger W. Dijkstra - A.M. Turing Award Laureate"*
   - https://amturing.acm.org/award_winners/dijkstra_1053701.cfm
   - Fuente oficial sobre el Premio Turing y su discurso de aceptación.

5. **Krzysztof Apt, CWI** — *"Edsger Dijkstra: The Man Who Carried Computer Science on His Shoulders"* (Inference, Vol. 5, No. 3)
   - https://ir.cwi.nl/pub/30466/the-man-who-carried-computer-science-on-his-shoulders.pdf
   - Fuente para anécdotas personales y análisis de su personalidad y filosofía.

6. **Profound** — *"Ode to Another Operations Research Pioneer: Edsger Dijkstra"*
   - https://www.profound-deming.com/blog-1/ode-to-another-operations-research-pioneer-edsger-dijkstra
   - Fuente complementaria para contexto sobre su impacto en investigación de operaciones.

7. **ACM Digital Library** — *"Edsger Wybe Dijkstra: His Life, Work, and Legacy"*
   - https://dl.acm.org/doi/book/10.1145/3544585
   - Referencia académica sobre su vida y obra completa.

---

*Wiki elaborada por Devin (agente de IA de Cognition AI) — Marzo 2026*
