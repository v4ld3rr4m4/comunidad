# Introducción a la segunda edición

**Cuando no estoy dirigiendo Wired, dirijo una comunidad llamada DIY Drones.** Aquí más de 20 000 miembros colaboran para hacer vehículos aéreos no tripulados (VANTs) de código abierto, que son en esencia aviones, helicópteros y otras cosas con hélices giratorias totalmente autónomos que pueden volar por ellos mismos.

La comunidad de DIY Drones ha creado incontables productos, pero el más exitoso es ArduPilot, una serie de pilotos automáticos basados en la plataforma de computación Arduino. Somos parte del movimiento de Hardware Abierto, es decir que hay elementos de software y hardware en los pilotos automáticos que nuestra comunidad crea, y ambos son de código abierto. Aunque otros y yo también tenemos compañías comerciales que hacen y venden este hardware (la mía se llama 3D Robotics), bajo los términos de la licencia de código abierto cualquiera, absolutamente cualquiera, puede usar los diseños que nuestra comunidad crea y hacerlos competir con nosotros. Puede sonar loco, pero este tipo de apertura puede crear innovaciones de forma más rápida, más barata y mejor que la investigación y diseño tradicionales de código cerrado en empresas regulares. El único riesgo es que alguna otra empresa clone el producto y lo venda por menos, dentro de los términos legales de la licencia.

Esto es exactamente lo que pasó a finales del 2010. Recibimos noticia de que copias chinas de nuestro diseño de ArduPilot Mega estaban a la venta en Taobao, eBay y otros mercados en línea. Y en efecto lo eran - clones bien producidos y totalmente funcionales. No solo eso, también nuestro manual de instrucciones en inglés había sido traducido al chino, junto con partes del software.

Nuestros miembros de la comunidad reportaron esta "evidente" piratería y preguntaron que qué íbamos a hacer al respecto.

Nada, dije yo:

> Esto es tanto esperado como fomentado en el hardware de código abierto. El software, que no cuesta nada para distribuir, es gratis. El hardware, que es costoso de hacer, es valorado al mínimo necesario para asegurar el saludable crecimiento de un negocio sostenible para asegurar calidad, soporte y disponibilidad de los productos, pero los diseños se regalan gratis también. Toda la propiedad intelectual es abierta, de forma que la comunidad puede usarla, mejorarla, hacer sus propias variaciones, etc.

> La posibilidad que otros puedan clonar los productos está integrada en el modelo. Es permitido de forma específica por nuestra licencia libre. Idealmente, la gente cambiaría/mejoraría los productos («diseños derivados«) para hacer frente a necesidades del mercado que ellos perciben y nosotros no hemos enfrentado. Este es el tipo de innovación que el código abierto está diseñado para promover. Pero si ellos sólo clonan los productos y los venden a precios más bajos, eso también está bien. El mercado decidirá.

> Por cierto, las placas de desarrollo Arduino han atravesado exactamente la misma situación con muchos clonadores chinos. Los clones algunas veces son de más baja calidad, pero incluso cuando eran buenos, la mayoría de personas continuaron apoyando los productos oficiales de Arduino y a los desarrolladores que los crearon. Hoy, los clones tienen una pequeña cuota del mercado, principalmente en mercados muy sensibles al precio como China. Y francamente, ser capaz de alcanzar un mercado con precios más bajos es una forma de innovación también, y eso no es algo malo.

> En lo personal, estoy encantado de ver este desarrollo por cuatro razones:

> 1. Creo que es estupendo que la gente haya traducido el wiki al chino, lo que lo hace accesible a más personas.

> 2. Es un signo de éxito - usted sólo es clonado si está haciendo algo que la gente quiere.

> 3. La competencia es buena.

> 4. Lo que empieza como clones puede eventualmente convertirse en innovación real y mejoras. Recuerden que nuestra licencia requiere que cualquier diseño derivado debe ser también de código abierto. Piensen lo genial que sería si un equipo chino creara mejores diseños que los nuestros. Entonces podríamos voltear la tortilla y producir su diseño, traduciendo la documentación al inglés y poniéndolos a disposición de un mercado fuera de China. ¡Todo el mundo gana! (Oye, uno puede soñar ;-) )

Poco tiempo después de que escribí esto, un miembro llamado «Hazy» respondió en los comentarios que él había trabajado con el equipo que había hecho las placas, y que era el que estaba haciendo la traducción. Lo felicité por la velocidad con la que fue hecho, y luego le pregunté si él consideraría transferir la traducción para que fuera parte de nuestro manual oficial, el cual está en un wiki en Google Code, donde se encuentra nuestro repositorio. Él accedió a hacerlo, y le di permisos para editar el wiki y que lo configurara para una traducción paralela en chino que los usuarios pudieran seleccionar.

En ese momento estábamos usando el sistema de control de versiones Subversion (ahora estamos usando Git), y Google Code tenía una implementación relativamente básica. Las páginas del wiki eran tan solo archivos en el mismo repositorio de nuestro código fuente de nuestros pilotos automáticos, y yo no había investigado las opciones de permisos muy bien. Para permitir que las personas editaran el wiki, yo simplemente les di acceso general para hacer «commits» (la capacidad para crear y editar archivos) en el repositorio entero.

Cuando le daba ese tipo de acceso a los miembros de la comunidad, usualmente les pedía que no se metieran con el código por error (la membresía en los equipos de desarrollo de código era más exclusiva, porque el peligro de desordenar las cosas era más alto), pero en el caso de Hazy lo olvidé.

La primera cosa que hizo Hazy fue integrar sin problemas la traducción china al manual, de forma que los usuarios pudieran simplemente hacer clic en un enlace para cambiar fácilmente entre los dos idiomas.

Luego, como él era un experto en nuestro autopilot (después de todo había sido parte del equipo que lo clonó), empezó a hacer correcciones al manual en inglés también. Yo pude ver todos los cambios fluyendo y los aprobé todos: eran inteligentes, correctos y estaban escritos en perfecto inglés.

Luego se puso interesante: Hazy comenzó a arreglar errores en el código mismo. La primera vez que esto pasó asumí que se había equivocado y había enviado un archivo del wiki en el directorio equivocado. Pero lo revisé y era código, y su arreglo no era solo correcto sino que estaba apropiadamente documentado. ¿Quién se hubiera imaginado que Hazy también era un programador?

Le agradecí por el arreglo, y no pensé mucho más acerca de esto. Pero luego los «commits» de código siguieron llegando. Hazy estaba trabajando a través de nuestra lista de Errores, escogiendo uno tras otro que el equipo de desarrollo habíamos estado muy ocupados para manejar nosotros mismos.

Hoy él es uno de nuestros mejores miembros del equipo de desarrollo. Aún no lo he conocido, pero después de un tiempo le pregunté un poco sobre él.

Su nombre real es Xiaojiang Huang. Vive en Beijing, y de día es un estudiante de PhD en ciencias de la computación en la Universidad de Peking.

Me contó su historia:

> Cuando era niño me fascinaban todos los tipos de modelos, y quería tener un avión a control remoto. Varios años después fui capaz de pagar un helicóptero a control remoto cuando me gradué de la universidad. También obtuve camiones y aviones a control remoto. A veces soy ridiculizado como ingenuo por jugar con «juguetes», pero estoy feliz porque es mi sueño de la niñez. Encontré ArduPilot por casualidad cuando estaba navegando en la red, y me atrajeron sus poderosas funciones. Algunos de mis amigos también estaban interesados, pero se sintieron un poco incómodos porque los documentos estaban en inglés. Así que traté de traducirlos al chino, esperando reducir la dificultad de jugar con ArduPilot para los fanáticos chinos. Gracias por el grandioso trabajo en DIYDrones, y espero que ayude a más personas a volver sus sueños realidad.

Lo que pasó aquí es mágico. Cuando por primera vez tuvimos noticias de las placas clonadas, algunos en nuestra comunidad saltaron inicialmente a la conclusión de que era otro evidente caso de piratería china y querían saber cuándo íbamos a demandar. Pero al recordarles que no era una versión «pirata», sino un «diseño derivado» totalmente permitido e incluso promovido por nuestra licencia de código abierto, el curso cambió.

Al no satanizar al equipo chino, y en cambio tratarlos como parte de la comunidad, ellos actuaron de esa forma también. Hazy dio un paso al frente, y en lugar de solo explotar nuestro trabajo, contribuyó con también.

Entonces ahora los «piratas» trabajan para nosotros. En lugar de solo usar nuestra tecnología, ellos están trabajando con nosotros para mejorar la tecnología para todos. «Hazy» realizó sus dueños y al hacerlo nos ayudó a realizar los nuestros también. Ese es el poder de la comunidad.

Todos tenemos diferentes historias de comunidad, y esta es sólo un ejemplo de cómo grandes comunidades pueden tocar a cada uno de nosotros. Sin embargo, construir una comunidad es un trabajo complejo. Involucra la cuidadosa planeación y reflexión., pero también la libertad de empoderar a los miembros de su comunidad para lograr cosas que usted jamás habría soñado.

No puedo pensar de una mejor guía que *El arte de la comunidad* y su intrépido guía turístico, Jono Bacon, para ayudarle a navegar en su jornada. En la primera edición del libro, Jono creó una fuerte base de conocimiento para construir y empoderar comunidades. La segunda edición no sólo refina y extiende este cuerpo de trabajo, sino que también comparte muchas otras historias de cómo las comunidades exitosas han sido creadas y las elecciones que se hicieron para lograrlo. Esta combinación de la experiencia y perspicacia de Jono, así como estas historias del mundo real de otros líderes de comunidades brinda un fuerte camino para tener éxito en sus propias comunidades.

-- Chris Anderson

Editor de la revista *Wired*, autor de *The Long Tail* (Hyperion), creador de DIYDrones

Berkeley, California

15 de noviembre de 2011
