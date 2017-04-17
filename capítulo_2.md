# Capítulo dos

## Planeando su comunidad

> «Debemos todos mantenernos unidos, o ciertamente, todos deberemos mantenernos separados.»

-- Benjamin Franklin

**Mi mejor amigo es un tipo llamado Stuart Langridge, a quien yo llamo «Aq».** (Su apodo era «Aquarius» en un grupo de usuarios en línea dedicado a un autor de fantasía, por razones que hacen que mis ojos se pongan vidriosos cuando trata de explicarlas.) Yo conocí a Aq en Wolverhampton, en el centro de Inglaterra, donde me mudé para ir a la universidad. Rápido nos volvimos amigos.

Con mi curiosidad picada inicialmente por el Grupo de Usuarios de Linux de Neil, yo estaba ansioso por formar el mío: el astutamente llamado Grupo de Usuarios de Linux de Wolverhampton. Seis meses después, Aq deambuló en una reunión, entero con la que ahora es su marca registrada de personalidad rimbombante.

A través de los años, Aq y yo compartimos muchas cervezas y algunos currys, debatiendo y discutiendo cada tema imaginable sobre el Software Libre. Ningún tema estaba fuera de alcance, y disfrutábamos grandemente la pasión del otro por el tema. También disfrutábamos la oportunidad de demostrar que el otro estaba equivocado. Esos debates inspiraron muchos proyectos. Uno de ellos fue LugRadio.

A lo largo de la vida de LugRadio, Aq y yo debatimos cómo nosotros - o más específicamente, yo - grabábamos el programa. Como el músico residente de un cuarteto fabuloso, con un cuarto lleno de equipo de grabación, yo manejé la grabación y edición, usando Mac OS X y el sistema de producción de audio Cubase.

Sí, gente, lo leyeron bien: LugRadio era un programa entero sobre Software Libre pero grabado en un sistema propietario, con una aplicación propietaria. Afortunadamente, la comunidad tomó la buena posición de recordarme de mi presunto «odio a la libertad» casi todos los días. Que suerte la mía. Desafortunadamente, yo no quería pasar mi vida ocupado en la ciencia espacial que era la ingeniería de audio en Linux. Amo tocar música, no pasar mis días pensando acerca de con cuál tamaño de muestra debería configurar mi software.

El debate se enfurecía, y yo me estaba enfermando cada vez más de la discusión. Algo tenía que cambiar.

Una tarde en la casa de Aq, estábamos tomando té y debatiendo sobre código abierto como de costumbre. Una área adicional en la que mi amigo cascarrabias y yo compartíamos un profundo interés era el diseño de interacción: cómo hacer productos e interfaces más sencillas. Así surgió el tema de grabación de audio en Linux.

Nuestro debate era más parecido a un resonante acuerdo. Ambos citamos ejemplo tras ejemplo de pobres decisiones de interfaz: métodos de interacción que se basaban en preguntas redundantes, asumían conocimientos complicados, y otras humillaciones. Mi solución fue empezar desde cero. Y así lo hicimos.

Pensamos que sería divertido repensar completamente la grabación de audio. Nos sentamos con papel y lápiz, y más tazas de té, discutiendo y debatiendo hasta las 4 a.m. Cuando llegué a casa y arrastré mi agotado cuerpo hasta la cama, el bolos de mi computadora portátil contenía tres hojas de papel esbozando un enfoque totalmente nuevo de grabación de audio.

A pesar de nuestros esfuerzos creativos, yo simplemente no tenía ni el tiempo ni el conocimiento para escribir un editor de audio. Pude haber usado mis pobres habilidades de programación y desarrollo para producir un intento bastante feo, pero eso hubiera sido de poca utilidad, y yo ya estaba intensamente ocupado. A pesar de esta falta de tiempo y habilidades, yo no quería que nuestros diseños languidecieran en la obscuridad, entonces hice un borrador de unos bosquejos y escribí una extensa entrada de blog explicando cómo funcionaban. Informé a la comunidad de LugRadio y esperé silencio: el mundo siguiendo, nuestros diseños ignorados.

Unas cuantas semanas más tarde deambulaba en los foros de LugRadio y noté que un poco de código había sido agregado a un repositorio. Lo descargué y se veía como una increíblemente simple primera versión de la interfaz que existía en mis bosquejos.

Estaba paralizado.

Y también lo estaba Aq.

El autor era un chico bastante simpático llamado Jason Field, quien tenía una pasión por escribir código y por Linux. Yo inmediatamente le escribí un correo para contactarlo. Su simple contribución me había inspirado a considerar el proyecto más allá, y ver si los diseños realmente eran posibles de construir. El dijo que sí.

Los miembros de la comunidad de LugRadio estaban igualmente intrigados por la historia sobre este nuevo editor de audio: ellos lo apodaron JonoEdit. Yo estaba halagado y un poco avergonzado.

Era tiempo de poner la máquina a rodar. Configuramos un repositorio de código, un sitio web, una lista de correos, un sistema de seguimiento de errores y calendarizamos reuniones regulares. Organizamos días de programación, fiestas de aplastar errores, y discusiones en línea para planear y alcanzar algunas importantes decisiones de arquitectura. Nueva gente se unió al equipo, incluyendo a Laszlo Pandy, quien se convirtió en el subsiguiente líder del proyecto.

Un poco después en el desarrollo, el proyecto tuvo un importante cambio de nombre; yo no estaba feliz con *JonoEdit*. Luego de pedir sugerencias, Steve Parkes, uno de los presentadores originales de LugRadio, sugirió *Jokosher*. El nombre estaba formado por «Jo», y «Kosher», que él entendía como «Sin tocino» o «No Bacon» en Inglés, de forma que construía mi nombre. De nuevo, estaba halagado. Se sintió raro, pero al equipo le gustó el nuevo nombre, y nos quedamos con ese.

Todos trabajaron duro. Pasamos largas tardes escribiendo código, depurando, arreglando errores y escribiendo documentación. Pieza por pieza construimos no sólo una aplicación, sino también una comunidad. Desarrollamos un sentido de unidad, y nos empezamos a convertir en un equipo.

Eventualmente, luego de meses de trabajo, publicamos la primera versión. A partir de unas pocas ideas, expresadas con mis habilidades de diseño de principiante, construimos algo que la gente podía tocar. Hoy, aunque me he alejado para trabajar en otras cosas, Jokosher es un proyecto próspero.

La mayoría de proyectos de Software Libre se forman a partir de una persona rascando en algo que le causa comezón. Esa persona escribe código y lo publica; si el código rasca las comezones de otras personas, la colaboración comienza. Jokosher era diferente. Existió en su totalidad en papel antes de existir en código. La aplicación tenía sus raíces en un nuevo enfoque de diseño de interacción, de forma que tener un diseño documentado era esencial. El diseño y la especificación de la interfaz que lo acompañaba actuaban como una referencia desde la cual se construye el software.

Lo que esta experiencia me enseñó, totalmente por casualidad, fue que la velocidad y el éxito de una comunidad tiene una correlación directa con la estrategia, estructura y planeación: incluso un simple conjunto de bosquejos puede ayudar a dirigir el progreso en la dirección correcta. Las comunidades que aparecen más por accidente que por intención tienden a desarrollarse y madurar de forma lenta. Las comunidades organizadas prosperan porque la estructura les brinda un sentido de valor, convicción y vigilancia. Una estrategia hará que las cosas ocurran para su comunidad.

***

**El libro de casos de la comunidad**

> Desde el punto de vista de un producto, hacemos a nuestros usuarios partes interesadas. Los alentamos y habilitamos para personalizar Firefox y para que tomen parte en dirigir nuestros productos a partir de pruebas y brindar retroalimentación.

-- Mary Colvig, acerca de Estrategia.

Lea la entrevista completa en el [Capítulo 14](capítulo_14.md).

***

### Planeando para el éxito

Como descubrirá a través de *El Arte de la Comunidad*, a mi me gusta introducir conceptos de una forma muy específica. Primero presento una discusión de alto nivel acerca de las prioridades principales y cubro los fundamentos. Luego, me enfoco en los detalles y desarrollo el tema. Este enfoque hace que introducir el tema sea más parecido a entrar en una piscina caliente en un día soleado, que lanzarse a un río congelado en Finlandia.

Nuestro objetivo en este capítulo es explorar cómo construir una estrategia para nuestras comunidades. Primero exploramos cuatro cimientos dentro de una comunidad. Cada uno de estos aloja los detalles subyacentes que exploraremos a lo largo del resto del libro. Dentro de estos cimientos están los equipos, los buques de la comunidad, los cuales luego abriremos para ver cómo trabajan. A continuación definiremos nuestra misión, objetivos y metas, y los levantaremos en un plan estratégico final. Cubriremos mucho terreno en este capítulo, así que tome una taza de té (yo recomendaría también una Hobnob para sumergirla en él), y póngase cómodo.

Con tantas áreas de discusión, necesitamos seleccionar los conceptos clave y tenerlos a mano. Es fácil olvidar o leer por encima aspectos sutiles pero importantes en el crecimiento de una comunidad. Para hacer esto sencillo, voy a agregarlos a una lista de cosas por hacer conforme los descubrimos a lo largo del capítulo.

***

** Lista de cosas por hacer para la Comunidad **

* Detalle de ejemplo.

* Detalle de ejemplo.

***

Más adelante en el libro volveremos a visitar esta lista y la usaremos para formar las bases de nuestro plan estratégico.

#### Comunidad: el vistazo general

Construir una comunidad fuerte es un prospecto emocionante y gratificante, pero llegar ahí puede ser complejo. Usted sólo necesita ver la tabla de contenidos de este libro para ver que el tema es enormemente diverso y detallado.

Primero necesitamos dar un paso atrás y entender nuestros objetivos generales. Cuando nos levantamos y decidimos que queremos construir una comunidad, ¿qué es lo que queremos lograr? Aparte de las metas de la comunidad misma, ya sea construir un proyecto de software, cambiar un sistema político, o cualquier otra cosa, ¿cómo inspiramos a un conjunto de gente a marchar hacia adelante como si fueran uno solo? ¿Cómo exactamente unimos a la gente? Bueno, podemos explicar esto usando... puntos.

Sí, puntos.

Ya sé lo que están pensando: usted está loco, Bacon. Los puntos parecen algo sencillo. Por supuesto que lo son, pero son diferentes en muchas formas. Diferentes colores, diferentes tamaños, diferentes formas. Usted puede no saber esto, pero los puntos tienen montones de personalidades. Tome por ejemplo los tres puntos mostrados en la Figura 2-1.

# TODO: Figura 2-1.

Lectores, quiero presentarles a la familia Punto: Juan, Paulina y Ken. Aunque se vean similares, cada uno tiene una personalidad y habilidades muy distintivas. Lo que los une es la misma pasión: crear un sitio web de red social completamente nuevo y original, construido para puntos, por puntos, llamado... PuntoBook.

Juan, Paulina y Ken contribuyen en formas muy diferentes. Juan (a la izquierda) es un programador, Paulina (en el centro) ama escribir documentación, y Ken (a la derecha) es bastante aficionado al dibujo. Lo sé, él tiene esa apariencia artística.

Juan, Paulina y Ken no están solos. Hay muchos puntos como ellos allá afuera en la Internet...

El problema, como pueden ver en la Figura 2-2, es que todos los Juanes, Paulinas y Kens, y sus respectivas habilidades, están dispersos por toda la Internet. Y en realidad no se conocen. Están unidos por la misma meta, pero no están trabajando juntos.

# TODO: Figura 2-2.

Una comunidad es justo como la Figura 2-2: un conjunto disperso de puntos. Uno de nuestros primeros objetivos es juntar estas áreas de interés conectadas en un equipo bien formado. Resulta que cuando los Juanes tienen la posibilidad de hablar con otros Juanes, algunas cosas interesantes ocurren. Estos equipos son contenedores importantes de experiencia e interés dentro de nuestra comunidad más amplia (vea la Figura 2-3).

# TODO: Figura 2-3.

Si pensamos en una comunidad como un grupo entremezclado de puntos amontonados sobre un interés compartido (e.g., protestar contra una ley ridícula, discutir sobre un tema, construir un sistema operativo), los equipos son el más pequeño de los subgrupos, por lo general basados alrededor de un interés primario o un conjunto de habilidades (e.g., promoción y documentación) que ayuda hacia el interés compartido.

Como un ejemplo, la comunidad de Ubuntu tiene un interés compartido de construir un sistema operativo de Software Libre. Para hacer esto, hay muchos grupos más pequeños que realizan traducciones, producen paquetes, escriben documentación, prueban software, promueven Ubuntu, y mucho más. Estos son los equipos que buscamos construir: separar nuestra amplia comunidad en pedazos más pequeños, más manejables. Cada equipo se une para resolver una parte de la objetivo más grande de la comunidad.

Los equipos son una figura esencial en la construcción de comunidad: no sólo son los contenedores en los cuales la comunidad crece, sino que también son unidades convenientes de capacidad, que le ayudan a entender estratégicamente la estructura de su comunidad y encontrar de qué es capaz. Cuando Juan Punto conoce otros puntos que comparten sus intereses y se emociona por las mismas oportunidades, los equipos también se vuelven contenedores de *pertenencia*.

Aunque los equipos tienen un enfoque principal (por lo general una habilidad, como el arte o la documentación), no debería ser demasiado rígido en ese enfoque. Cada equipo tendrá miembros que están interesados en esta función primaria, pero que también traerán otras habilidades y percepciones al equipo. Como un ejemplo, en una comunidad de software, es enormemente valioso para el equipo de arte tener también miembros con habilidades de programación: con frecuencia pueden acelerar la implementación de contribuciones de arte en el desarrollo técnico de la aplicación. Como tal, alienten y optimicen una membresía basada en el enfoque principal del equipo, pero también celebren y hagan uso de las otras habilidades de sus miembros.

Los equipos ofrecen abundancia de oportunidades y beneficios al construir una comunidad fuerte, y los discutiremos de forma extensa más adelante en el capítulo. Primero, agreguemos esta meta en nuestra lista de cosas por hacer.

***

** Lista de cosas por hacer para la Comunidad **

* Identificar cómo podemos dividir la comunidad en equipos.

***

Aunque la construcción de equipos es valiosa, no es suficiente. Como una unidad de capacidad, un equipo es aún parte de la comunidad más amplia que se esfuerza por una meta común. Necesitamos asegurar que nuestros equipos encajan como un rompecabezas completo. La comunicación, las ideas y las historias deben fluir libremente entre sus equipos, como en la Figura 2-4.

# TODO: Figura 2-4.

El flujo de comunicación entre los equipos es mucho más complejo que lo que se podrían imaginar al inicio. ¿Cómo podemos asegurar un flujo sencillo de ideas y progreso entre dos equipos que se enfocan en partes diferentes de la comunidad? ¿Cómo puede su equipo de arte comunicarse bien con su equipo de desarrollo? Esto abre una enorme cantidad de preguntas. Incluso con los tres equipos de la Figura 2-4, ¿cómo se comunican? ¿Qué medios usan? ¿Cómo lidian con problemas de geografía y zonas horarias? ¿Cómo reportan sus interacciones a la comunidad? ¿Cómo le dan seguimiento a su progreso? ¿Cómo entendemos cómo los diferentes equipos trabajan juntos? No es un problema fácil de resolver.

Estas preguntas no son sólo acerca de cómo dos o tres equipos se comunican. Estas llegan al corazón del ethos de la comunidad como un todo: el estándar para cómo están estructurados los equipos, cómo se comportan, y cómo se comunican.

Como lo mencioné antes, aunque sus equipos tengan un enfoque principal (como traducciones, digamos), habrán muchas otras habilidades presentes en sus equipos, y muchas personas estarán en múltiples equipos. No necesitamos sólo fomentar la comunicación efectiva entre equipos (como reuniones regulares, verificación de progreso, y canales de comunicación compartidos), sino que también necesitamos hacer uso de personas que tienen sus pies en múltiples equipos. Ellos pueden ser el pegamento que mantiene unidos los equipos. Estas personas deberían estar en su lista de tarjetas por enviar en navidad.

Este tema es parte de la *gobernancia*, y es tan grande y crítico para el éxito de la comunidad que le he dedicado el [Capítulo 10](capítulo_10.md) más adelante en este libro. Asegurémonos de tomar nota de la comunicación del equipo en nuestra lista de cosas por hacer, aunque hasta después veamos cómo construir esto cuando discutamos gobernancia.

***

** Lista de cosas por hacer para la Comunidad **

* Identificar cómo podemos dividir la comunidad en equipos.
* Asegurar que los equipos se pueden comunicar de forma clara y efectiva.

***

La siguiente área de atención es el crecimiento de los y las contribuyentes. Nos gustan los puntos como Juan, Paulina y Ken, y queremos alentar más como ellos en nuestra comunidad, como podemos ver en la Figura 2-5.

Cuando se trata de nuevos contribuyentes, esencialmente buscamos satisfacer dos deseos primarios: *capacidad* y *diversidad*.

Con la *capacidad*, nuestro objetivo es poner más manos a la obra. Más manos (coordinadas) por lo general significan que más cosas se terminan. La mayoría de comunidades tienen metas algo audaces (que discutiremos más adelante), y estas metas casi siempre superan los recursos disponibles para implementarlas. Este cuello de botella puede causar agotamiento (un tema que discutiremos de forma extensa en el [Capítulo 11](capítulo_11.md), pero de forma más inmediata genera una necesidad de encontrar más recursos.

Atraer miembros a su comunidad es una gran tarea, pero atraer un rango diverso de contribuyentes es algo muy distinto. Aunque no es crítica en una comunidad, la diversidad tiene un gran valor: diferentes habilidades, culturas, perspectivas, actitudes y experiencias hace una experiencia de comunidad más rica.

# TODO: Figura 2-5.

Más adelante en este libro, en el [Capítulo 7](capítulo_7.md), exploramos cómo atraer miembros a su comunidad. Esto requiere no sólo hacer a su comunidad atractiva para posibles miembros, sino también ofrecerles un flujo de trabajo efectivo de forma que puedan ver que sus contribuciones se aprovechen sin mucha molestia. ¿Qué retos enfrentan sus miembros al contribuir? ¿Cómo podemos hacer que esas barreras sean lo más bajas posible para la sangre nueva pero que sigan atrayendo las habilidades correctas? ¿Cuáles son las habilidades correctas? Agreguemos esta meta importante a la lista de cosas por hacer.

***

** Lista de cosas por hacer para la Comunidad **

* Identificar cómo podemos dividir la comunidad en equipos.
* Asegurar que los equipos se pueden comunicar de forma clara y efectiva.
* Atraer un rango diverso de contribuyentes a nuestra comunidad para que se involucren y contribuyan con nuestros objetivos.

***

El último gran paso al construir una comunidad sólida es construir un ambiente positivo, como se muestra en la Figura 2-6 (nos enfocaremos en construir un ambiente sólido en el [Capítulo 4](capítulo_4.md). Su comunidad debería sentirse inspirada, motivada y emocionada por la oportunidad de cumplir los objetivos que soñaron.

# TODO: Figura 2-6.

El ambiente juega un enorme rol en todo lo que hacemos. Cada elemento de nuestro ambiente afecta nuestras perspectivas, emociones y expectativas.

Considere un ambiente convencional, como un barrio. Muchos atributos del ambiente pueden afectar la percepción, por ejemplo, de la sensación de seguridad. Ejemplos que afectan esa sensación incluyen el tamaño y el estilo de las casas, los tipos de carros en la calle, los residentes, lo que visten y su lenguaje corporal, la iluminación en las calles durante la noche, el ruido de fondo, la cantidad de tráfico, y más. Compare y contraste un barrio en apariencia amistoso y social, en el cual los niños caminan por ahí y la gente está hablando en la calle, con un lugar poco amistoso, cerrado y restringido en el que pocas personas están hablando y compartiendo sus vidas con los demás. El dinero no es el factor decisivo aquí: comunidades cerradas súper caras por lo general tienen tan poca socialización como cuadras de torres muy pobres en el centro de la ciudad. Fundamentalmente, las dos tienen las mismas piezas centrales - casas, calles, carros, alumbrado público, residentes y así - pero el ambiente afecta grandemente la percepción. La percepción mental de un pintoresco pueblo rural adornado con sus pequeñas calles, tiendas de té y una abundante cantidad de gente mayor jugando ajedrez es muy diferente a esa de una cuadra del centro de la ciudad con sus edificios cuadrados, grandes portones y gente apurándose para ir a trabajar.

El ambiente no sólo afecta la percepción, sino también la oportunidad. En un barrio que se percibe como inseguro, es menos probable que los residentes interactúen entre ellos debido al miedo. En una comunidad que se siente segura y acogedora, prosperan los grupos locales, conversaciones ad hoc y otras interacciones. Estas consideraciones no sólo aplican a las comunidades geográficas, su ambiente en línea tiene la misma importancia.

Agreguemos el ambiente a la lista, y hagamos una rápida recapitulación de nuestros asuntos principales hasta ahora.

***

** Lista de cosas por hacer para la Comunidad **

* Identificar cómo podemos dividir la comunidad en equipos.
* Asegurar que los equipos se pueden comunicar de forma clara y efectiva.
* Atraer un rango diverso de contribuyentes a nuestra comunidad para que se involucren y contribuyan con nuestros objetivos.
* Construir un ambiente que conduzca a nuestros objetivos más amplios.

***

### Equipos: los componentes básicos de la pertenencia

Cada objetivo en nuestra lista de cosas por hacer es clave para una comunidad sólida, y aunque tal vez no se den cuenta, cada uno también tiene algo en común: *equipos*. Exploremos esto en más detalle.

Los equipos son los componentes básicos de la estructura de la comunidad. Estos son los bloques de Lego que construyen un ejército de voluntarios unidos por una misión. Pero como componentes básicos, estos encajan en muchas formas diferentes, con incontables variaciones y posibilidades de cómo se construyen.

Para que entendamos comunidad, necesitamos entender qué hace que los equipos funcionen. Ahora vamos a pasar un tiempo enfocándonos en los ingredientes esenciales que deberían estar presentes en todos lo equipos. Estos ingredientes son los elementos de las mejores prácticas que hacen equipos fuertes, acogedores y productivos. Exploraremos estos ingredientes fundacionales ahora, y más adelante en el capítulos vamos a determinar de cuáles equipos específicos constará nuestra comunidad.

#### Encontrando su lugar

Todo el mundo tiene sueños. Todos tenemos ambiciones y experiencias que codiciamos, y todos somos culpables de aprovechar la oportunidad de un día lluvioso para quedarnos mirando hacia la ventana y dejar que nuestras mentes nos lleven a esas grandiosas visiones, ya sea volar al espacio, hacer millones de dólares o tocar el bajo frente a miles de personas.

Los sueños de Adam Sweet eran diferentes. El *había* tocado el bajo frente a miles de personas. Ese joven y fumador manojo de energía con pelo de picos reunió una banda con sus amigos y lograron obtener un contrato para una grabación a la tierna edad de 18 años. Conocidos como Passion Star, la banda tocó en Radio One Roadshow: una gira por todo Reino Unido compuesta por artistas establecidos y nuevo talento.

Aunque sonaba divertido, Adam había tenido suficiente. Él quería normalidad. Él quería una casa, una novia, una vida regular, no una vida en un pequeño bus con cuatro musos con problemas de higiene. Pero Adam aún quería una pasión (sin ser una estrella). Él necesitaba un interés para envolver su sentido natural de curiosidad y exploración. Entonces, compró una computadora.

Aún cuando era el año 2000 y él tenía 24 años, les podría sorprender que Adam nunca había tenido una computadora antes. De inmediato perplejo con su nueva amiga, compró una revista para entenderla mejor, y resulta que dicha revista presentaba al sistema operativo Linux en la portada. No sabiendo nada mejor, él saltó a instalarlo. Por supuesto, fue un desastre épico, como lo era Linux por lo general en aquel momento. Mientras trataba de encontrar ayuda, Adam se topó con su primera comunidad, la cual también servía como un equipo: mi grupo de usuarios de Linux.

Cuando Adam entró, se enfrentó a los mismos miedos, incertidumbres y curiosidades que yo compartí al inicio del libro. Sin embargo, estaba de igual forma inspirado e intrigado por el concepto de la comunidad. Aunque se sintió raro, también se sintió obligado a quedarse.

Cuando Adam se unió por primera vez al grupo, preguntó un bombardeo de preguntas, con frecuencia disculpándose cuando sentía que eran «estúpidas» a pesar de las garantías de que no habían preguntas estúpidas.

Conforme construyó su confianza, él empezó a experimentar. El grupo se había vuelto un excelente lugar para que la gente donara equipo viejo. Adam tomaba este interminable flujo de aparatos viejos, probaba nuevos programas y compartía sus experiencias con el resto del grupo. Con forme nuevos miembros se unían y preguntaban cosas, él les respondía y compartía sus experiencias. Rápidamente se estaba convirtiendo en una especie de experto en Linux.

Él continuó jugando, creciendo, estudiando en la universidad y, pronto, encontró un trabajo como administrador de sistemas. Poco después conoció a su novia, Jenny, y se mudaron a su propia casa. Adam había logrado lo que quería: normalidad, un sentido de seguridad y una pasión.

Lo que encuentro tan entrañable sobre la historia de Adam es que un grupo de usuarios de Linux (un equipo dentro de la comunidad general de Linux) haya contribuido tan decisivamente con sus ambiciones. Si Adam no se hubiera unido a un equipo, ya sea mi GUL o cualquier otro grupo, no estoy seguro de que la historia hubiese tenido el mismo final.

Los equipos llenan un rol importante en una comunidad fuerte: son pequeños ecosistemas con atributos que pueden ser enormemente valiosos para el éxito de su comunidad a una escala más amplia. Una vez que hemos visto estos atributos a un alto nivel, podemos usar este conocimiento para construir nuestra estrategia práctica de implementación más adelante en este capítulo.

#### Unidades de pertenencia

Los equipos son las unidades de pertenencia. Los miembros se unen, se energizan con el espíritu del equipo, y desarrollan un sentimiento de pertenencia que los incita a contribuir de vuelta con el equipo. Esta filosofía de  «Círculo de vida» le brinda al equipo un consistente intercambio de experiencias y valor.

Si abrimos un equipo podemos ver varias generaciones, como aros en la corteza de un árbol. Cada generación es una fuente de historias (ya establecidas en el capítulo anterior como una fuente importante de comunicación) y también una fuente de mentoría. Cada generación transmite historias, experiencias y lecciones de vida a la nueva generación.

Esto es exactamente lo que pasó con Adam. Cuando se unió al grupo, necesitaba asistencia y soporte. Cuando recibió esta ayuda, el equipo le brindó un sentido de valor. Este valor inspiró a Adam a tratar al equipo con respeto y priorizar su importancia en su vida. Conforme el equipo abrió puertas de conocimiento, conexiones sociales se abrieron y él tuvo un sentimiento de pertenencia. Esta pertenencia se sellaba cada vez que impartía su propia experiencia a nuevos y existentes miembros del grupo. Él recibía la debida apreciación y agradecimientos que él entregó a otros cuando era nuevo.

Parte de la razón por la que Adam tuvo una experiencia tan positiva fue que entendió la amplitud total del equipo. En cualquier agrupación humana natural, el *alcance* y la familiaridad del ambiente juegan un rol importante.

El alcance define la amplitud y el alcance de algo. Es el tamaño de un libro, la capacidad de la sede de un festival, y la exhaustividad de un proyecto. El alcance describe la extensión de la pecera mental en la que estamos, ya sea un libro, una sede o una iniciativa. Un ejemplo típico de alcance que es familiar para todos nosotros es el lugar en el que vivimos.

El mundo es un lugar bien grande. Su magnitud se refuerza por la televisión, sitios web, libros, historias y fotografías que vemos todos los días. Por miles de años, humanos y animales han desarrollado una tendencia natural de dividir el mundo en pedazos más manejables. La sociedad toma el mismo enfoque: países se dividen en estados y condados; estados y condados se dividen en ciudades, pueblos y villas; y ciudades, pueblos y villas se dividen en calles y, finalmente, casas.

Las comunidades geográficas son semejantes a las comunidades digitales: con ambas, nuestra percepción afecta nuestra confianza. Tomen el ejemplo de alguien que se traslada a una área completamente nueva. Para la mayoría de las personas que se han mudado recientemente, el ambiente es al inicio enormemente abrumador. Una vez que esta persona ha explorado la mayor parte de la ciudad, pueblo o villa, y conocido dónde quedan la tienda de comestibles, los hospitales y otros recursos principales, ella empieza a desarrollar un sentido de confianza. Entender el alcance del área nos da esta confianza.

La razón de esto es que somos criados para tener precaución ante lo desconocido. Desafortunadamente, esto también nos vuelve temerosos. Cuando conocemos la extensión total de la pecera en la que vivimos, así como a los otros peces que están con nosotros, eso nos ayuda a construir un sentido medido de seguridad. Su sentido de alcance le hace sentir seguro cuando confirma que vive en una calle segura y no en el medio del hampa.

El alcance de los nativos también afecta nuestra percepción. Contraste a alguien con pocos amigos y vecinos aparentemente extraños, con alguien que tiene muchos amigos y vecinos muy sociales. Cuando se empiezan a hacer conexiones personales recurrentes con amigos regulares, conocidos e intereses amorosos, un sentimiento de pertenencia comienza a fluir a través de las venas. Esto no es diferente en una pequeña comunidad en persona o en línea.

Los equipos son enormemente valiosos al brindar un alcance manejable para sus nuevos contribuyentes. Si su comunidad tiene 1000 personas en un único equipo, su comunidad se puede sentir abrumadora. Si en lugar de eso está partida en 10 equipos, cada uno con 100 personas, y cada equipo enfocado en una área distinta, esto es mucho más accesible.

Agreguemos esta premisa importante de la construcción de equipos a nuestra lista de cosas por hacer.

***

** Lista de cosas por hacer para la Comunidad **

* Identificar cómo podemos dividir la comunidad en equipos.
* Asegurar que los equipos se pueden comunicar de forma clara y efectiva.
* Atraer un rango diverso de contribuyentes a nuestra comunidad para que se involucren y contribuyan con nuestros objetivos.
* Construir un ambiente que conduzca a nuestros objetivos más amplios.
* Definir el alcance de cada equipo, y ayudar a los miembros del equipo a entender este alcance.

***


#### Leer versus escribir

Las comunidades vienen en muchas formas. Rodean libros, películas, productos de software, campañas políticas, esfuerzos de derechos civiles y más. En todas sus coloridas y variadas formas, todas las comunidades comparten una característica distintiva: la unidad de personas alrededor de una creencia o interés común. Es pasión lo que une a estas personas.

##### Comunidades de lectura, en su mayoría

Un gran ejemplo de esta pasión son los fanáticos de *Star Trek*. Yo no soy de ninguna manera un miembro de esa comunidad (y sólo tengo un conocimiento básico del programa), pero esta es claramente de gran alcance y mantiene una vasta membresía. Los *Trekkies*, como son conocidos, se reúnen al rededor del mundo para discutir, debatir y consumir *Star Trek* en toda su salvaje y bastante rara gloria. Ah, y también visten disfraces bastante ridículos y en ocasiones extraños.

Podemos definir a los Trekkies como *fanáticos* - disfrutan un interés común, ya sea en línea o en convenciones al rededor del mundo, y su rol principal es compartir el consumo de ese interés con otros. Como fanáticos, los Trekkies en raras ocasiones tienen un impacto directo en el interés unificador: el Trekkie promedio no podría cambiar la historia del programa, contribuir con los disfraces o los efectos especiales, o mejorar lo que ya existe. En su lugar, la colaboración en el mundo Trekkie produce contenido para otros Trekkies: no le tomará mucho encontrar maravillosamente detallados disfraces, utilería, tatuajes, historias y otras creaciones hechas por fanáticos.

Aunque parece haber una división colaborativa muy distintiva entre el proveedor (el programa) y el consumidor (el fanático), hay un punto intermedio. Estas comunidades se están volviendo cada vez más importantes para los proveedores y nunca antes los artistas, músicos, productores y políticos han estado tan conscientes de sus seguidores. Internet ha permitido que los fanáticos se conecten de forma más sencilla con su héroes, y esto ha desarrollado un tipo de colaboración.

Hay muchos ejemplos de esto. Stephen Fry, un respetado actor británico, empezó a usar el servicio de microblogging Twitter y en unos meses ya tenía 400 000 personas siguiendo sus actualizaciones. La administración Obama ha hecho uso de blogs y YouTube de forma amplia para distribuir contenido e invitar a la retroalimentación.

Un productor que se ha involucrado repetidamente con su comunidad de fanáticos es Joss Whedon, el estadounidense escritor, director y productor ejecutivo de *Buffy the Vampire Slayer* nominado a los Premios de la Academia y ganador del premio Hugo. Whedon ha sido conocido por usar varios medios en línea para interactuar con fanáticos y hasta ha referenciado contribuciones de fanáticos en su trabajo.

Un ejemplo de estos fue la referencia en un episodio al «demonio Polgara». El nombre «Polgara» viene originalmente de libros escritos por el autor estadounidense David Eddings. La decisión de Whedon de usar l nombre fue inspirada por una fanática que escribía de forma regular en el foro oficial de *Buffy the Vampire Slayer* bajo ese mismo nombre. Whedon y el productor David Fury usaron ese nombre como un tributo a sus contribuciones regulares en la comunidad.

Otro ejemplo del compromiso de Whedon con su comunidad flotó a la superficie durante una huelga de escritores. Él trabajo con otros escritores para escribir y producir *Dr. Horrible's Sing-Along Blog*, un musical corto de 45 minutos que fue publicado en Internet. Cada episodio del musical estaba en línea sólo por unos pocos días, y Whedon generaba interés dentro de la comunidad usando Twitter e interactuando con los fanáticos.

Estos son ejemplos de construcción de comunidad en acción. Los productores están uniendo grupos de gente interesada, brindando facilidades de comunicación, y motivando y posibilitando que esas personas colaboren. Incluso si la extensión de esa colaboración es un grupo de fanáticos brindando retroalimentación en un foro, la colaboración aún sucede.

Así es como la mayoría de las comunidades funcionan. La colaboración es un subproducto no oficial, y aunque pueda no cambiar o mejorar la creación del productor, aún es probable que ofrezca valor real. El enfoque principal de estas comunidades están en asegurar que la comunidad (a) siempre tenga acceso al producto y (b) pueda comunicarse sobre este con otros. La base de estos tipos de comunidades está en el *acceso*.

Aunque cada comunidad tenga la característica de gente reunida alrededor de una creencia o interés compartido, el impacto real de la comunidad en esta creencia o interés compartido varía grandemente.

##### Comunidades centradas en escritura

Para algunas comunidades, la colaboración va mucho más lejos. Se convierte en algo más profundo, más intrínseco y más accesible para todos. En lugar de simplemente *disfrutar haciendo cosas juntos*, la colaboración va tan lejos como ayudar a las personas a *crear cosas juntas*. En estos ambientes, la comunidad también asume el rol de productor del contenido.

El ejemplo típico aquí es una de las muchas comunidades de Cultura Libre, así como Linux, Wikipedia, OpenStreetMap, Creative Commons, etcétera. En estas comunidades, los miembros de la comunidad tienen la oportunidad de cambiar el mismo contenido que los une.

La comunidad de Ubuntu es un ejemplo de esto. Ubuntu es un sistema operativo de Linux completamente libre, que es diseñado para brindar un sistema completo, gratuito, estable y seguro para computadoras de escritorio, servidores o dispositivos móviles. Ubuntu está construido usando cientos de piezas de Software Libre preexistente, a las que nos referimos como aplicaciones *«upstream»*. Cada aplicación «upstream» tiene su propia comunidad de voluntarios y desarrolladores. Ubuntu en sí mismo tiene una comunidad de voluntarios y desarrolladores que toman dichos programas «upstream» y lo ensamblan en un sistema fácil de instalar y fácil de usar.

Ubuntu ha engendrado una comunidad enorme. Más de 200 grupos de usuarios de Ubuntu, conocidos como Ubuntu LoCo teams, se han formado alrededor del mundo. Casi todos los paises tienen un LoCo team, con un rango de usuarios desde expertos de Linux hasta usuarios completamente nuevos. Estas personas son, en una palabra, *asombrosas*. (Tal vez estoy un poco sesgado...)

Cualquier persona en la comunidad de Ubuntu puede afectar lo que aparece en Ubuntu mismo. Cada parte del sistema está abierta a contribuciones. Esto incluye los programas en el disco, la documentación y recursos de soporte, arte y diseño, reportes de errores, y casi cualquier otra cosa. Cada uno tiene la oportunidad, a través de trabajo duro y mérito, de hacer contribuciones positivas al sistema de Ubuntu alrededor del cual se reune la comunidad.

Entender cómo nuestras comunidades colaboran es importante para entender qué queremos lograr y qué es posible. Agreguemos esto a nuestra lista de cosas por hacer.

#### Meritocracia

#### Trabajar juntos es el éxito

#### Diversidad

### Diseñando su comunidad

#### Incluyendo la apertura

#### Construyendo una declaración de misión

#### Construyendo un plan estratégico

##### Estructurando el plan

### Rellenando el plan

#### Haciendo una lluvia de ideas

##### Técnica 1: poner en duda las suposiciones

##### Técnica 2: pensar fuera de la caja

##### Técnica 3: hagamos que apeste

### Juntando los hilos

#### Equipos: divide y vencerás

##### Identificar cómo se puede dividir su comunidad en equipos

##### Definir el alcance de cada equipo, y ayudar a los miembros de los equipos a entender ese alcance

##### Entender la extensión y el rango de la colaboración entre nuestro equipos

##### Asegurar que los equipos se puedan comunicar de forma clara y efectiva

### Documentando su estrategia

### Soportando financieramente su comunidad

#### Oportunidades de ganancias

##### Publicidad en línea

##### Ventas

##### Donaciones

##### Patrocinios

### Terminando