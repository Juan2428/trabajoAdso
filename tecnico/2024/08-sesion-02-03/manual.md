Para crear un encabezado, agrega entre uno y seis símbolos <kbd>#</kbd> antes del encabezado del texto. El número de <kbd>#</kbd> que utilices determinará el nivel jerárquico y el tamaño tipográfico del encabezado.

# A first-level heading
## A second-level heading
### A third-level heading

Al usar dos o más encabezados, GitHub genera automáticamente una tabla de contenido a la que puede acceder haciendo clic en  dentro del encabezado del archivo. Todos los títulos de encabezado aparecen en la tabla de contenido, y puede hacer clic en un título para ir a la sección seleccionada.

# Estilos de texto
Puedes indicar énfasis con texto en negrita, cursiva, tachado, o de subíndice o superíndice en los campos de comentarios y archivos .md.

Bold	** ** o __ __

Cursiva	* * o _ _ 

Tachado	~~ ~~	

Cursiva en negrita y anidada	** ** y _ _	t**	

Todo en negrita y cursiva	*** ***

Subscript	<sub> </sub>	

Superscript	<sup> </sup>	

# Entrecomillado de texto
Puede entrecomillar texto con >.

Text that is not a quote

> Text that is a quote


 # Código de cita
Puedes indicar un código o un comando dentro de un enunciado con comillas simples. El texto dentro de las comillas simples no será formateado. También puedes presionar el método abreviado de teclado Comando+E (Mac) o Ctrl+E (Windows o Linux) para insertar las comillas simples de bloque de código en una línea de Markdown.

> Use `git status` to list all new or modified files that haven't yet been committed.


   # Modelos de color compatibles
En los problemas, las solicitudes de incorporación de cambios y los debates, puedes llamar a los colores dentro de una oración mediante comillas simples. Un modelo de color compatible dentro de las comillas simples mostrará una visualización del color.

> The background color is `#ffffff` for light mode and `#000000` for dark mode.


   # Vínculos
Puede crear un vínculo en línea escribiendo su texto entre corchetes [ ] y escribiendo la URL entre paréntesis ( ). También puede usar el método abreviado de teclado Command+K para crear un vínculo. Cuando haya seleccionado texto, puede pegar una dirección URL del Portapapeles para crear automáticamente un vínculo a partir de la selección.

También puedes crear un hipervínculo de Markdown resaltando el texto y usando el método abreviado de teclado Comando+V. Si quieres reemplazar el texto por el vínculo, usa el método abreviado de teclado Comando+Mayús+V.

This site was built using [GitHub Pages](https://pages.github.com/).

> Captura de pantalla de GitHub Markdown en la que se muestra cómo el texto entre corchetes, "GitHub Pages", aparece como un hipervínculo azul.


 #  Vínculos relativos
Puedes definir enlaces relativos y rutas de imagen en los archivos representados para ayudar a que los lectores naveguen hasta otros archivos de tu repositorio.

> Un enlace relativo es un enlace que es relativo al archivo actual. Por ejemplo, si tiene un archivo Léame en la raíz del repositorio y tiene otro archivo en docs/CONTRIBUTING.md, el vínculo relativo a CONTRIBUTING.md en el archivo Léame podría tener este aspecto:

[Contribution guidelines for this project](docs/CONTRIBUTING.md)
GitHub transformará de manera automática el enlace relativo o la ruta de imagen en cualquier rama en la que te encuentres actualmente, de modo que el enlace o ruta siempre funcione. La ruta de acceso del vínculo será relativa al archivo actual. Los vínculos que comienzan por / serán relativos a la raíz del repositorio. Puede usar todos los operandos de vínculo relativos, como ./ y ../.

Los enlaces relativos son más sencillos para los usuarios que clonan tu repositorio. Puede que los enlaces absolutos no funcionen en los clones de tu repositorio. Recomendamos usar enlaces relativos para consultar los archivos dentro de tu repositorio.

 # Imágenes
Puede mostrar una imagen agregando ! y ajustar el texto alternativo en [ ]. El texto alternativo es un texto corto equivalente a la información de la imagen. Luego, escribe el vínculo de la imagen entre paréntesis ().

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)


 # Hacer referencia a propuestas y solicitudes de extracción
Puede mencionar una lista de las incidencias y solicitudes de incorporación de cambios dentro del repositorio escribiendo #. Escribe el número o el título de la propuesta o la solicitud de extracción para filtrar la lista, y luego presiona cada pestaña o ingresa para completar el resultado resaltado.

Para obtener más información, vea «Referencias y direcciones URL autovinculadas».

 # Hacer referencia a recursos externos
Si se configuran las referencias autovinculadas personalizadas para un repositorio, entonces las referencias a recursos externos, como un informe de problemas de JIRA o un ticket de Zendesk, se convertirán en vínculos acortados. Para saber qué autovínculos se encuentran disponibles en tu repositorio, contacta a alguien con permisos administrativos sobre el mismo. Para obtener más información, vea «Configurar enlaces automáticos para referenciar recursos externos».

 # Cargar activos
Puedes cargar activos como imágenes si las arrastras y sueltas, las seleccionas de un buscador de archivos o si las pegas. Puede cargar recursos en las incidencias, solicitudes de incorporación de cambios, comentarios y archivos .md en el repositorio.

 # Usar emojis
Puedes agregar emoji a la escritura escribiendo :EMOJICODE:, dos puntos seguidos del nombre del emoji.

> @octocat :+1: This PR looks great - it's ready to merge! :shipit:
