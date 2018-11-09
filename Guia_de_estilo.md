# Guía de estilo para el idioma (ab-CD)

* Formalidad y tono
* Expresión natural
* Referencias culturales, modismos y jerga
* Unidades y conversión de unidades
  * Formato de fecha
  * Vista de calendario
  * Formato de tiempo
  * Numerales
  * Moneda
  * Unidades de medida
  * Formato de dirección y código postal
  * Formato de número de teléfono
* Gramática
  * Revisiones de ortografía y gramática
  * Puntuación
  * Espacios en blanco
* Reglas de copiado

> Inserta el nombre de tu local en la línea de abajo y déjalo en tu guía de estilo a menos que no se aplique a tu local. Puedes traducirlo si tu guía de estilo está en tu idioma.

Esta guía de estilo proporciona instrucciones para traducir a[El nombre de tu local] local. Esta guía de estilo debe utilizarse en coordinación con la [Guía de estilo general de Mozilla L10n](https://mozilla-l10n.github.io/styleguides/mozilla_general/).

> Incluye aquí otra información introductoria relevante, como una página web de la comunidad o información de contacto.


## Formalidad y tono

> ¿Quién es el usuario objetivo de este proyecto y cuáles son sus antecedentes?
>
> Describe brevemente los usuarios de tu local. Si el tipo de usuario de un proyecto a otro varía, indícalo aquí.
>
> ¿Cómo esperarías interactuar con un usuario objetivo de este proyecto?
>
> Describe el tipo de interacción que esperas que los usuarios de tu local. Las interacciones pueden variar de autoritarias y formales a amistosas y casuales. Indica qué tipo de tono prefieres en tu local.
>
> Describe las características que creas son el tono correcto. Por ejemplo, el español tiene múltiples formas del pronombre de la segunda persona. Generalmente, tu es considerado informal y personal y usted es considerado formal e impersonal. Las pautas de Mozilla Photon prefieren una interacción informal y personal; sin embargo, si la cultura de tu local prefiere una interacción formal, ésta debe ser declarada en la guía de estilo de tu comunidad.
>
> ¿Es el lenguaje formal o informal apropiado para todos los proyectos de Mozilla l10n en tu idioma, o sólo para algunos de ellos? ¿Cuáles?
>
> Si el tono varía de un proyecto a otro, indica qué tono es el mejor para cada proyecto.


## Expresión natural

> ¿Qué tipo de expresión suena natural en tu local?
>
> Describe las características de una localización con sonido natural.
>
> ¿Tu local permite muchas palabras y frases prestadas o pocas?
>
> Enumera los casos específicos importantes o incluye un enlace a los recursos pertinentes. Por ejemplo, la frase En ocho días podría traducirse como en ocho días. Sin embargo, una expresión natural en inglés sería en siete días o incluso en una semana. Las tres son traducciones correctas, pero las dos últimas son más naturales en inglés.


## Referencias culturales, modismos y jerga

> ¿Cómo se manejan las referencias culturales, los modismos y la jerga en tu local?
>
> Define una política para manejar estas referencias culturales, expresiones idiomáticas y jerga que puedas estandarizar en todos los proyectos.
>
> Un ejemplo de una referencia cultural en inglés sería la frase "reunión inicial". Esta es una referencia que utiliza un término de fútbol americano. Significa una reunión para comenzar un proyecto. Para traducirlo, puedes seguir uno de dos enfoques:
>
 > 1. Encuentra una frase de referencia equivalente en tu idioma.
 > 2. Eliminar la referencia cultural y traducir el significado central (por ejemplo, una reunión de inicio).
>
> ¿Existen recursos para referencias culturales, modismos y jerga en tu idioma?
>
> Enumera los recursos que puedes utilizar para encontrar equivalentes culturales (por ejemplo, un diccionario de jerga en tu idioma).


## Unidades y conversión de unidades

>   ¿Tu localidad utiliza el sistema métrico o el sistema imperial?
>
> Indica qué sistema de medición se utiliza en tu localidad para el peso, la distancia, etc. Indica cualquier otra información del sistema de medición o unidades de medida que sean relevantes para tu localidad.


### Formato de fecha

> ¿Cómo se expresan los formatos de fecha para semanas y meses?
>
> Declara si las fechas están completamente explicadas, abreviadas o representadas de otra manera y el orden de año, mes y día. Esto se puede representar con una tabla. Borra los marcadores de comillas alrededor de la plantilla de ejemplo o muestra el formato con tu propio ejemplo.
>
> Nombre | Formato | Ejemplo 
> ------ | ------- | -------
> Breve  | mm/dd/yy | 12/31/99
> Abreviado | mmm dd | Dic 31
> Largo | Mes y día,  año | Diciembre 31, 1999


### Vista de calendario

> ¿Qué fecha se considera el primer día de la semana, domingo o lunes?
>
> ¿Se observa el calendario lunar? ¿Otro calendario regional observado?


### Formato de tiempo

> ¿Cómo se expresa el tiempo en tu idioma?
>
> Indica cómo se expresa el tiempo, incluyendo la expresión de 0-24 horas, hora, minuto y segundo si es relevante.


### Numerales

> ¿Cómo se expresan los números y porcentajes en tu idioma?
>
> Declar< cuáles son los separadores para tu sistema de números y cualquier otra información relevante. Esto se puede representar con una tabla. Borra los marcadores de comillas alrededor de la plantilla de ejemplo o muestra el formato con tu propio ejemplo.
> 
> Separador | Nombre del carácter | Símbolo | Ejemplo
> --------- | ------------------- | ------- | -------
> Decimal | Período | . | 1.23
> Miles | Comas | , | 1,234
> Porcentaje | Signo porcentual | % | 99.95% 

### Moneda

> ¿Qué moneda y símbolos se utilizan en tu país/idioma?
>
> Indica los símbolos de moneda que se utilizan en tu localidad. Si tu idioma cubre diferentes países o monedas o los símbolos de moneda común varían dependiendo de la base de cada proyecto, declara los diferentes tipos y usos.


### Unidades de medida

> ¿Utilizas el sistema imperial, métrico o náutico para medir el peso, la distancia, etc.?


### Formato de dirección y código postal

> ¿Cuál es el formato de la dirección en tu idioma?
> 
> Muestra el formato de dirección postal de tu localidad. Borra los marcadores de comillas alrededor de uno de los ejemplos o muestra el formato con tu propio ejemplo.
>
> Ejemplo: La mayoría de los países asiáticos empiezan de grandes a pequeños:
> ```[País]
> [código postal][estado/provincia][ciudad][distrito][distrito]
> [número de la calle y nombre][número del edificio y de la suite]
> [Destinatario] 
> ```
>
> Los países de lenguas europeas empiezan de pequeños a grandes:
> 
> ```[Destinatario]
> [número de la calle y nombre][número del edificio y de la suite]
> [distrito][ciudad][estado/provincia][código postal]
> [País]
> ```

### Formato de número de teléfono

> ¿Cómo se expresan los números de teléfono en tu idioma?
>
> Muestra el formato del número de teléfono. ¿Cambia el formato de los números de teléfono móvil y fijo? Adapta la plantilla de ejemplo o muestra el formato con sus propios ejemplos.
>
> ```(###) ###-####
> ```

## Gramática

### Revisiones de ortografía y gramática

> ¿Tu idioma tiene revisiones ortográficas o gramaticales estándar?
>
> Enumera y explica cualquier referencia ortográfica o gramatical para tu idioma y la frecuencia con la que se deben utilizar.


### Puntuación

> ¿Utilizas reglas de puntuación diferentes en tu localización de Mozilla que las que define el estándar de tu idioma?
>
> Describe cualquier variación en la puntuación de los proyectos de Mozilla a partir de los estándares lingüísticos. Si la puntuación varía de un proyecto a otro, enumera los proyectos que utilizan la puntuación variante.


### Espacios en blanco

> ¿Tu idioma requiere el uso de espacios en blanco alrededor de palabras, oraciones, párrafos, etc.?
>
> Describe las reglas relevantes de los espacios en blanco en tu idioma en lo que respecta a la localización de Mozilla. Si los espacios en blanco varían de un proyecto a otro o dependiendo del elemento de la interfaz, describe cómo.


## Reglas de copiado

> Por favor, deja la siguiente línea en tu guía de estilo a menos que no se aplique a tu localidad. Puedes traducirlo si tu  guía de estilo está en tu idioma.

Lee acerca de los estilos de las reglas de copia en la [Guía de Estilo General de Mozilla L10n] (https://mozilla-l10n.github.io/styleguides/mozilla_general/#copy-rules).

> ¿Existe un estándar internacional/nacional para la capitalización en tu idioma?
>
> Indica si tu idioma utiliza caso de título, caso de sentencia, mayúsculas o alguna otra estructura de capitalización. Si el estilo cambia para diferentes elementos textuales como títulos de películas, libros, nombres de marcas o elementos de la cara del usuario (Guardar, Archivar, etc.).
>
> ¿Es el estándar de mayúsculas apropiado para todos los proyectos de Mozilla l10n de tu idioma o sólo para algunos de ellos? ¿Cuáles?
>
> Si las reglas de copia en tu idioma cambian de un proyecto a otro, enumera las reglas de copia para cada proyecto.
>
> ¿Es el estándar de mayúsculas apropiado para todos los elementos de la interfaz de usuario en tu idioma o sólo para algunos de ellos? ¿Cuáles?
>
> ¿Existen otras convenciones tipográficas con respecto a las comillas, comillas, apóstrofes, uso de texto en negrita o cursiva, texto en mayúsculas, etc.?

