 #prompt #zotero 

# Task
Analiza los datos bibliográficos proporcionados por el usuario (como título, autor, fecha, DOI, URL, etc.) para identificar el tipo de elemento más adecuado en Zotero. Genera una entrada manual completa siguiendo estrictamente la _Guía Exhaustiva para Catalogar Elementos en Zotero_, seleccionando el tipo más específico posible, mapeando campos exactos y manejando casos ambiguos o no soportados.

# Request
- Usa **exclusivamente** los datos proporcionados; no inventes, asumas ni agregues información.
- Selecciona el tipo de elemento basado en las definiciones de "Cuándo utilizar" en la guía; prioriza tipos específicos sobre genéricos como "Document" o "Webpage".
- Para tipos no soportados, usa un sustituto y agrega `Type: CSL Type` en "Extra".
- Incluye solo campos soportados por el tipo seleccionado según la guía; omite "Date Added" y "Date Modified".
- Para datos no encajantes en campos estándar, usa "Extra" con formato `CSL Variable: Value`.
- Usa códigos ISO para "Language" cuando sea relevante.
- Genera tags SEO: una palabra clave principal y 3-5 secundarias/LSI relevantes, extraídas directamente de la información proporcionada o índice implícito (título, abstract, etc.), priorizando términos con potencial de búsqueda académica.
- Si los datos son insuficientes o ambiguos, selecciona el tipo más genérico y explica en justificación/notas.
- Mantén precisión, consistencia y claridad para generar citas académicas válidas.

# Action
Sigue estos pasos secuenciales para procesar los datos:
1. **Identifica el tipo de elemento**: Compara las características de los datos con las secciones "Cuándo utilizar" de los 36 tipos en la guía. Selecciona el más específico; si no encaja perfectamente, elige genérico y justifica.
2. **Justifica la selección**: Explica brevemente (1-3 oraciones) por qué el tipo es apropiado, citando criterios clave de la guía y datos relevantes.
3. **Mapea campos**: Lista todos los campos relevantes del tipo seleccionado. Asigna valores exactos de los datos; deja vacío si no aplica (no omitas el campo). Usa "Extra" para excessos.
4. **Genera tags SEO**: Extrae [Palabra clave principal], seguida de [3-5 secundarias/LSI] basadas en términos centrales del título, abstract o contenido.
5. **Agrega notas opcionales**: Incluye observaciones sobre datos incompletos, recomendaciones o advertencias.
6. **Valida**: Asegura que la salida siga el formato exacto y no viole restricciones.

# Context
La _Guía Exhaustiva para Catalogar Elementos en Zotero_ detalla 36 tipos con campos, propósitos y recomendaciones. Enfatiza tipos específicos para citas precisas, uso de "Extra" para extensiones, y evita "Document"/"Attachment" si hay alternativas. Incluye tipos no soportados vía "Extra". Los datos del usuario son variables pero limitados a lo proporcionado. El objetivo es catalogación manual en Zotero para estándares académicos (APA, MLA, etc.).

## Tipos de Elementos en Zotero:

1. Artwork (Obra de arte)

  - Para registrar obras de arte como pinturas al óleo, esculturas, fotografías o cualquier tipo de imagen visual, incluidas figuras científicas (p. ej.﻿, gráficos o diagramas).
  - Usar este tipo en lugar de "Document" para elementos visuales con un enfoque artístico o científico que requieran citar al creador como un artista.
- **Campos**:
  - **Item Type**: Seleccionar "Artwork" para categorizar como obra de arte.
  - **Artist**: Nombre del creador de la obra (persona o entidad). Ingresar en formato de dos campos (Apellido, Nombre) para personas o un campo para instituciones.
  - **Title**: Título principal de la obra, en mayúsculas según el idioma (sentence case).
  - **Abstract**: Breve descripción de la obra, si es relevante.
  - **Date**: Año de creación o publicación de la obra.
  - **Medium**: Tipo de obra o material usado (p. ej.﻿, "Pintura al óleo", "Escultura de madera", "Gráfico de dispersión").
  - **Artwork Size**: Dimensiones físicas de la obra (p. ej.﻿, "50x70 cm").
  - **Place**: Lugar donde se creó o exhibe la obra, si aplica.
  - **Publisher**: Institución o galería que publica o exhibe la obra.
  - **Language**: Código ISO del idioma (p. ej.﻿, "es-ES" para español).
  - **Short Title**: Versión abreviada del título para citas posteriores en estilos de notas.
  - **URL**: Dirección web donde se puede acceder a una representación digital de la obra.
  - **Accessed**: Fecha en que se accedió a la obra en línea.
  - **Archive**: Nombre del archivo o museo donde se encuentra la obra.
  - **Loc. in Archive**: Ubicación específica en el archivo (p. ej.﻿, número de sala o caja).
  - **Library Catalog**: Catálogo o base de datos de donde se importó la información.
  - **Call Number**: Número de clasificación en una biblioteca o archivo.
  - **Rights**: Información sobre derechos de autor o licencias.
  - **Extra**: Información adicional, como notas o campos no soportados (p. ej.﻿, "Original Date: 1886").
  - **Date Added/Modified**: Campos automáticos con la fecha de adición o modificación.
- **Información oficial de Zotero**:
  - Este tipo es ideal para citar obras de arte o imágenes visuales, diferenciándolas de documentos genéricos. La documentación recomienda usar el campo "Medium" para describir el material o tipo de obra, y "Artwork Size" para dimensiones físicas. Si la obra no encaja perfectamente, se puede adaptar usando el campo "Extra" para detalles específicos.

 2. Audio Recording (Grabación de audio)

  - Para música, grabaciones de voz, efectos de sonido, grabaciones de archivo o figuras científicas basadas en audio.
  - Usar en lugar de "Podcast" si no es un programa distribuido en línea por suscripción.
- **Campos**:
  - **Item Type**: Seleccionar "Audio Recording".
  - **Performer**: Nombre del intérprete principal (persona o grupo). Ingresar en formato de dos campos para personas.
  - **Composer**: Nombre del compositor de la música, si aplica.
  - **Words By**: Autor de las letras o texto hablado (p. ej.﻿, letrista o guionista).
  - **Title**: Título de la grabación (p. ej.﻿, nombre de la canción o pieza).
  - **Abstract**: Descripción breve del contenido.
  - **Date**: Fecha de publicación o grabación.
  - **Format**: Formato de la grabación (p. ej.﻿, "CD", "MP3").
  - **Running Time**: Duración de la grabación (p. ej.﻿, "3:45 mins").
  - **Label**: Compañía discográfica que distribuye la grabación.
  - **Series**: Nombre de una serie de grabaciones, si aplica.
  - **Series Title**: Título de una serie específica dentro de una publicación.
  - **Volume**: Número de volumen, si es parte de una colección.
  - **Place**: Lugar de publicación o grabación.
  - **Publisher**: Editorial o productora de la grabación.
  - **ISBN**: Número ISBN, si la grabación está publicada como parte de un conjunto.
  - **Language**: Código ISO del idioma.
  - **Short Title**: Título abreviado para citas posteriores.
  - **URL**: Dirección web de la grabación.
  - **Accessed**: Fecha de acceso en línea.
  - **Archive/Loc. in Archive**: Archivo y ubicación específica donde se encuentra.
  - **Library Catalog/Call Number**: Catálogo y número de clasificación.
  - **Rights/Extra/Date Added/Modified**: Igual que en "Artwork".
- **Información oficial de Zotero**:
  - Este tipo cubre cualquier grabación de audio, desde música hasta grabaciones históricas. El campo "Format" es clave para especificar el medio físico o digital. Los creadores como "Performer" o "Composer" son esenciales para citas precisas. Para roles adicionales (p. ej.﻿, productores), usar el campo "Extra" con el formato "Director: Nombre || Apellido".

 3. Bill (Proyecto de ley)

  - Para propuestas de legislación presentadas ante un cuerpo legislativo.
  - Usar en lugar de "Statute" si la legislación aún no ha sido aprobada.
- **Campos**:
  - **Item Type**: Seleccionar "Bill".
  - **Sponsor**: Autor principal del proyecto (persona o entidad).
  - **Cosponsor**: Coautores o patrocinadores adicionales.
  - **Title**: Título oficial del proyecto de ley.
  - **Abstract**: Resumen del contenido del proyecto.
  - **Bill Number**: Número asignado al proyecto de ley.
  - **Code**: Nombre del código donde se publica el proyecto.
  - **Code Volume**: Volumen del código.
  - **Code Number**: Número específico dentro del código.
  - **Section**: Sección específica del proyecto citada.
  - **Date**: Fecha de presentación del proyecto.
  - **Legislative Body**: Cuerpo legislativo que debate el proyecto (p. ej.﻿, "Senado").
  - **Session**: Sesión legislativa en la que se presentó.
  - **History**: Información sobre el historial procesal del proyecto.
  - **Language/Short Title/URL/Accessed/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".
- **Información oficial de Zotero**:
  - Este tipo es específico para legislación propuesta. El campo "Bill Number" es crucial para identificar el proyecto, y "History" permite rastrear su progreso. La documentación sugiere usar "Extra" para campos legales adicionales no soportados, como "Event Place".

 4. Blog Post (Entrada de blog)

  - Para artículos o entradas publicadas en un blog personal.
  - Usar "Magazine Article" o "Newspaper Article" para publicaciones en línea de medios más grandes (p. ej.﻿, blogs de NYT).
  - Se recomienda usar "Webpage" si no se ajusta a otros tipos más específicos.
- **Campos**:
  - **Item Type**: Seleccionar "Blog Post".
  - **Author**: Autor de la entrada, en formato de dos campos.
  - **Commenter**: Persona que comenta la entrada (no usado en citas).
  - **Title**: Título de la entrada del blog.
  - **Abstract**: Resumen del contenido.
  - **Blog Title**: Nombre del blog que contiene la entrada.
  - **Website Type**: Género del sitio web (p. ej.﻿, "Blog personal"), raramente usado.
  - **Date**: Fecha de publicación de la entrada.
  - **Language/Short Title/URL/Accessed/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

 5. Book (Libro)

  - Para libros publicados, incluidas monografías, antologías o textos académicos.
  - Usar "Report" para documentos gubernamentales, informes técnicos o manuales.
  - Puede adaptarse para ítems inusuales si otros tipos no encajan.
  - Se recomienda usar "Type" o "Extra" para especificar subtipos (p. ej.﻿, "Novela" o "Biografía"). El campo "Edition" debe contener solo números, y "Series" es clave para colecciones editoriales.
- **Campos**:
  - **Item Type**: Seleccionar "Book".
  - **Author**: Autor principal del libro.
  - **Editor**: Editor del libro, si aplica.
  - **Translator**: Traductor, si el libro es una traducción.
  - **Contributor**: Colaboradores adicionales (no usados en citas).
  - **Title**: Título completo del libro.
  - **Abstract**: Resumen del contenido.
  - **Series**: Nombre de la serie editorial, si aplica.
  - **Series Number**: Número del libro en la serie.
  - **Volume**: Volumen del libro, si es parte de una colección.
  - **# of Volumes**: Número total de volúmenes en la obra.
  - **Edition**: Número de edición (p. ej.﻿, "2" para segunda edición).
  - **Place**: Lugar de publicación.
  - **Publisher**: Editorial que publicó el libro.
  - **Date**: Año de publicación.
  - **# of Pages**: Número total de páginas.
  - **ISBN**: Número ISBN del libro.
  - **Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

 6. Book Section (Sección de libro)

  - Para capítulos, prólogos, introducciones, apéndices, comentarios u otras secciones de un libro.
  - Usar en lugar de "Book" cuando se cita una parte específica de un libro.
  - Se sugiere usar "Extra" para campos como "Chapter Number".
- **Campos**:
  - **Item Type**: Seleccionar "Book Section".
  - **Author**: Autor de la sección.
  - **Editor/Translator/Contributor**: Igual que en "Book".
  - **Title**: Título de la sección o capítulo.
  - **Book Title**: Título del libro que contiene la sección.
  - **Abstract/Series/Series Number/Volume/# of Volumes/Edition/Place/Publisher/Date/# of Pages/ISBN/Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Book".
  - **Pages**: Rango de páginas de la sección dentro del libro.
 
 7. Case (Caso legal)

  - Para casos legales, ya sean publicados o inéditos.
  - Usar en lugar de "Document" para citas legales formales.
  - Se recomienda consultar la sección de "Legal Citations" para soporte adicional.
- **Campos**:
  - **Item Type**: Seleccionar "Case".
  - **Author**: Abogado o entidad que presenta el caso (rara vez usado).
  - **Counsel**: Abogado que argumenta el caso.
  - **Case Name**: Título oficial del caso (p. ej.﻿, "Roe v. Wade").
  - **Abstract**: Resumen del caso.
  - **Court**: Tribunal donde se argumentó el caso.
  - **Date Decided**: Fecha de la decisión del caso.
  - **Docket Number**: Número de expediente asignado.
  - **Reporter**: Publicación donde se reporta el caso.
  - **Reporter Volume**: Volumen del reporter.
  - **First Page**: Primera página del caso en el reporter.
  - **History**: Recursos relacionados con el historial del caso.
  - **Language/Short Title/URL/Accessed/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

8. Conference Paper (Artículo en conferencia)

  - Para trabajos presentados en conferencias y publicados en actas formales (p. ej.﻿, como libro o revista).
  - Usar "Presentation" para trabajos no publicados en actas.
  - Si la conferencia y la publicación tienen lugares diferentes, usar "Extra" para "Event Place".
- **Campos**:
  - **Item Type**: Seleccionar "Conference Paper".
  - **Author**: Autor del artículo.
  - **Title**: Título del artículo.
  - **Abstract**: Resumen del contenido.
  - **Proceedings Title**: Título de las actas donde se publicó.
  - **Conference Name**: Nombre de la conferencia.
  - **Place**: Lugar de publicación de las actas.
  - **Publisher**: Editorial de las actas.
  - **Date**: Año de publicación.
  - **Volume**: Volumen de las actas.
  - **Pages**: Rango de páginas del artículo.
  - **Series**: Serie de la publicación, si aplica.
  - **DOI**: Identificador DOI del artículo.
  - **ISBN**: ISBN de las actas.
  - **Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

 9. Dictionary Entry (Entrada de diccionario)

  - Para entradas publicadas en un diccionario.
  - Usar en lugar de "Encyclopedia Article" si el recurso es específicamente un diccionario.
  - Se sugiere usar "Book Section" si la entrada es más extensa o compleja.
- **Campos**:
  - **Item Type**: Seleccionar "Dictionary Entry".
  - **Author**: Autor de la entrada, si se especifica.
  - **Title**: Título de la entrada (p. ej.﻿, la palabra definida).
  - **Dictionary Title**: Título del diccionario.
  - **Abstract/Series/Series Number/Volume/# of Volumes/Edition/Place/Publisher/Date/Pages/ISBN/Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Book".

 10. Document (Documento)

  - Para documentos genéricos no cubiertos por otros tipos.
  - Evitar su uso si es posible, ya que tiene pocos campos y soporte limitado en estilos de cita.
  - Se recomienda usar "Book", "Report" o "Manuscript" para mejores resultados en citas.
- **Campos**:
  - **Item Type**: Seleccionar "Document".
  - **Author**: Autor del documento.
  - **Title**: Título del documento.
  - **Abstract**: Resumen del contenido.
  - **Publisher**: Entidad que publica el documento.
  - **Date**: Fecha de publicación.
  - **Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

 11. Email (Correo electrónico)

  - Para mensajes enviados por correo electrónico u otras formas de comunicación personal.
  - Usar en lugar de "Letter" si la comunicación es digital.
- **Campos**:
  - **Item Type**: Seleccionar "Email".
  - **Author**: Remitente del correo.
  - **Recipient**: Destinatario del correo.
  - **Subject**: Asunto del correo electrónico.
  - **Abstract**: Resumen del contenido.
  - **Date**: Fecha de envío.
  - **Language/Short Title/URL/Accessed/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

 12. Encyclopedia Article (Artículo de enciclopedia)

  - Para artículos o capítulos publicados en una enciclopedia.
  - Usar en lugar de "Dictionary Entry" si el recurso es una enciclopedia general.
- **Campos**:
  - **Item Type**: Seleccionar "Encyclopedia Article".
  - **Author**: Autor del artículo.
  - **Title**: Título del artículo.
  - **Encyclopedia Title**: Título de la enciclopedia.
  - **Abstract/Series/Series Number/Volume/# of Volumes/Edition/Place/Publisher/Date/Pages/ISBN/Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Book".

 13. Film (Película)

  - Para películas artísticas, incluyendo ficción, no ficción y documentales.
  - Usar "Video Recording" para videos no artísticos (p. ej.﻿, YouTube).
  - Se recomienda usar etiquetas en "Extra" para roles adicionales.
- **Campos**:
  - **Item Type**: Seleccionar "Film".
  - **Director**: Director de la película (autor principal).
  - **Producer/Scriptwriter**: Productores o guionistas, si aplica.
  - **Cast Member**: Actores principales (no usado en citas).
  - **Title**: Título de la película.
  - **Abstract**: Resumen de la trama o contenido.
  - **Date**: Año de estreno.
  - **Format**: Formato de la película (p. ej.﻿, "DVD", "Streaming").
  - **Running Time**: Duración de la película.
  - **Distributor**: Compañía que distribuye la película.
  - **Genre**: Género de la película (p. ej.﻿, "Drama").
  - **Place/Publisher/ISBN/Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

14. Forum Post (Publicación en foro)

  - Para publicaciones en foros en línea, incluidas redes sociales como tweets o comentarios de Facebook.
  - Usar en lugar de "Blog Post" si la publicación es en un foro o red social.
  - Se sugiere usar "Webpage" para publicaciones en línea más genéricas.
- **Campos**:
  - **Item Type**: Seleccionar "Forum Post".
  - **Author**: Autor de la publicación.
  - **Commenter**: Persona que comenta (no usado en citas).
  - **Title**: Título de la publicación o mensaje.
  - **Abstract**: Resumen del contenido.
  - **Forum/Listserv Title**: Nombre del foro o plataforma (p. ej.﻿, "Twitter").
  - **Post Type**: Tipo de publicación (p. ej.﻿, "Tweet").
  - **Date**: Fecha de publicación.
  - **Language/Short Title/URL/Accessed/Rights/Extra/Date Added/Modified**: Igual que en "Artwork". 
  
15. Hearing (Audiencia)

  - Para informes o registros de audiencias formales de un cuerpo legislativo.
  - Usar en lugar de "Document" para citas legales específicas.
- **Campos**:
  - **Item Type**: Seleccionar "Hearing".
  - **Contributor**: Persona o entidad asociada (autor principal).
  - **Title**: Título de la audiencia.
  - **Abstract**: Resumen del contenido.
  - **Committee**: Comité que realiza la audiencia.
  - **Place**: Lugar de la audiencia.
  - **Publisher**: Entidad que publica el registro.
  - **Date**: Fecha de la audiencia.
  - **# of Volumes**: Número de volúmenes del registro.
  - **Document Number**: Número de identificación del registro.
  - **Pages**: Rango de páginas citado.
  - **Legislative Body**: Cuerpo legislativo (p. ej.﻿, "Congreso").
  - **Session**: Sesión legislativa.
  - **History**: Historial procesal de la audiencia.
  - **Language/Short Title/URL/Accessed/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

16. Instant Message (Mensaje instantáneo)

  - Para mensajes enviados por servicios de mensajería instantánea o chat.
  - Usar en lugar de "Email" si la comunicación es en tiempo real.
  - Se sugiere usar "Letter" para comunicaciones similares no digitales.
- **Campos**:
  - **Item Type**: Seleccionar "Instant Message".
  - **Author**: Remitente del mensaje.
  - **Recipient**: Destinatario del mensaje.
  - **Title**: Título o asunto del mensaje.
  - **Abstract**: Resumen del contenido.
  - **Date**: Fecha de envío.
  - **Language/Short Title/URL/Accessed/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

17. Interview (Entrevista)

  - Para grabaciones, transcripciones o registros de entrevistas.
  - Usar en lugar de "Document" para entrevistas formales o publicadas.
- **Campos**:
  - **Item Type**: Seleccionar "Interview".
  - **Interview With**: Persona entrevistada (autor principal).
  - **Interviewer**: Persona que realiza la entrevista.
  - **Title**: Título de la entrevista, si tiene uno.
  - **Abstract**: Resumen del contenido.
  - **Date**: Fecha de la entrevista.
  - **Medium**: Formato de la entrevista (p. ej.﻿, "Grabación de audio", "Transcripción").
  - **Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

18. Journal Article (Artículo de revista académica)

  - Para artículos publicados en revistas académicas, ya sea en formato impreso u online.
  - Usar en lugar de "Magazine Article" para publicaciones académicas revisadas por pares.
  - Se recomienda usar "Extra" para campos como "PMID" o "Status" (p. ej.﻿, "in press").
- **Campos**:
  - **Item Type**: Seleccionar "Journal Article".
  - **Author**: Autor del artículo.
  - **Reviewed Author**: Autor de la obra reseñada, si es una reseña.
  - **Title**: Título del artículo.
  - **Publication**: Nombre de la revista.
  - **Abstract**: Resumen del artículo.
  - **Volume**: Volumen de la revista.
  - **Issue**: Número de la revista.
  - **Pages**: Rango de páginas del artículo.
  - **Date**: Fecha de publicación.
  - **Series/Series Title**: Serie o sección especial de la revista.
  - **Journal Abbr**: Abreviatura de la revista (según estándares como MEDLINE).
  - **DOI**: Identificador DOI del artículo.
  - **ISSN**: Número ISSN de la revista.
  - **Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

19. Letter (Carta)

  - Para cartas enviadas entre personas u organizaciones, especialmente comunicaciones históricas o personales.
  - Usar en lugar de "Email" para comunicaciones no digitales.
  - Se sugiere usar "Manuscript" para cartas históricas con valor archivístico.
- **Campos**:
  - **Item Type**: Seleccionar "Letter".
  - **Author**: Remitente de la carta.
  - **Recipient**: Destinatario de la carta.
  - **Title**: Título o descripción de la carta.
  - **Abstract**: Resumen del contenido.
  - **Type**: Tipo de carta (p. ej.﻿, "Correspondencia privada").
  - **Date**: Fecha de envío.
  - **Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

20. Magazine Article (Artículo de revista)

  - Para artículos publicados en revistas populares, comerciales o no académicas.
  - Usar en lugar de "Journal Article" si no es una publicación revisada por pares.
  - Se recomienda usar "Journal Article" para publicaciones académicas y "Newspaper Article" para diarios.
- **Campos**:
  - **Item Type**: Seleccionar "Magazine Article".
  - **Author**: Autor del artículo.
  - **Title**: Título del artículo.
  - **Publication**: Nombre de la revista.
  - **Abstract**: Resumen del contenido.
  - **Volume/Issue**: Volumen y número de la revista, si aplica.
  - **Date**: Fecha de publicación.
  - **Pages**: Rango de páginas.
  - **ISSN**: Número ISSN de la revista.
  - **Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

21. Manuscript (Manuscrito)

  - Para manuscritos inéditos, ya sean históricos o modernos (p. ej.﻿, trabajos no publicados, borradores o artículos en proceso).
  - Usar en lugar de "Document" para documentos con valor archivístico o académico.
  - Se recomienda usar "Extra" para detalles archivísticos adicionales.
- **Campos**:
  - **Item Type**: Seleccionar "Manuscript".
  - **Author**: Autor del manuscrito.
  - **Title**: Título del manuscrito.
  - **Abstract**: Resumen del contenido.
  - **Type**: Tipo o estado del manuscrito (p. ej.﻿, "Manuscrito inédito", "Trabajo en proceso").
  - **Date**: Fecha de creación o redacción.
  - **Place**: Lugar donde se creó el manuscrito.
  - **# of Pages**: Número de páginas.
  - **Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

22. Map (Mapa)

  - Para mapas o modelos geográficos.
  - Usar en lugar de "Artwork" si el enfoque es cartográfico.
- **Campos**:
  - **Item Type**: Seleccionar "Map".
  - **Cartographer**: Creador del mapa (autor principal).
  - **Title**: Título del mapa.
  - **Abstract**: Descripción del contenido.
  - **Type**: Tipo o género del mapa (p. ej.﻿, "Mapa topográfico").
  - **Scale**: Escala del mapa (p. ej.﻿, "1:50,000").
  - **Series/Series Title**: Serie cartográfica, si aplica.
  - **Edition**: Edición del mapa.
  - **Place/Publisher/Date/ISBN/Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

23. Newspaper Article (Artículo de periódico)

  - Para artículos publicados en periódicos, ya sea en formato impreso u online.
  - Usar en lugar de "Magazine Article" si el medio es un diario.
- **Campos**:
  - **Item Type**: Seleccionar "Newspaper Article".
  - **Author**: Autor del artículo.
  - **Title**: Título del artículo.
  - **Publication**: Nombre del periódico.
  - **Abstract**: Resumen del contenido.
  - **Place**: Lugar de publicación del periódico.
  - **Edition**: Edición del periódico (p. ej.﻿, "Edición matutina").
  - **Date**: Fecha de publicación.
  - **Section**: Sección del periódico (p. ej.﻿, "Internacional").
  - **Pages**: Rango de páginas.
  - **ISSN**: Número ISSN del periódico.
  - **Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

24. Patent (Patente)

  - Para patentes otorgadas por una invención.
  - Usar en lugar de "Document" para citas legales específicas.
- **Campos**:
  - **Item Type**: Seleccionar "Patent".
  - **Inventor**: Creador de la invención (autor principal).
  - **Attorney/Agent**: Abogado o agente que representa al inventor.
  - **Title**: Título de la patente.
  - **Abstract**: Resumen de la invención.
  - **Country**: País que emite la patente.
  - **Assignee**: Entidad a la que se asignan los derechos.
  - **Issuing Authority**: Oficina que emite la patente.
  - **Patent Number**: Número de la patente.
  - **Filing Date**: Fecha de presentación de la solicitud.
  - **Issue Date**: Fecha de emisión de la patente.
  - **Application Number**: Número de la solicitud.
  - **Priority Numbers**: Números de prioridad internacional.
  - **References**: Recursos relacionados con la patente.
  - **Legal Status**: Estado legal de la patente.
  - **Language/Short Title/URL/Accessed/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

25. Podcast (Podcast)

  - Para episodios de programas de audio o video distribuidos en línea, generalmente por suscripción.
  - Usar en lugar de "Audio Recording" si el contenido es un podcast.
  - Se sugiere usar "Audio Recording" para grabaciones no distribuidas como podcasts.
- **Campos**:
  - **Item Type**: Seleccionar "Podcast".
  - **Podcaster**: Anfitrión del podcast (autor principal).
  - **Guest**: Invitado en el episodio, si aplica.
  - **Title**: Título del episodio.
  - **Abstract**: Resumen del contenido.
  - **Program Title**: Nombre del programa de podcast.
  - **Episode Number**: Número del episodio.
  - **Date**: Fecha de publicación.
  - **Running Time**: Duración del episodio.
  - **Format**: Formato del podcast (p. ej.﻿, "MP3").
  - **Language/Short Title/URL/Accessed/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

26. Presentation (Presentación)

  - Para presentaciones en conferencias, simposios o reuniones, no publicadas en actas.
  - Usar "Conference Paper" si la presentación se publicó en actas.
  - Se sugiere usar "Extra" para "Event Date" si es diferente de la fecha de publicación.
- **Campos**:
  - **Item Type**: Seleccionar "Presentation".
  - **Presenter**: Persona que realiza la presentación (autor principal).
  - **Title**: Título de la presentación.
  - **Abstract**: Resumen del contenido.
  - **Meeting Name**: Nombre del evento o conferencia.
  - **Place**: Lugar donde se realizó la presentación.
  - **Date**: Fecha de la presentación.
  - **Type**: Formato de la presentación (p. ej.﻿, "Póster", "Conferencia").
  - **Language/Short Title/URL/Accessed/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

27. Radio Broadcast (Emisión de radio)

  - Para programas de radio, como noticias, series de entretenimiento o grabaciones archivadas.
  - Usar en lugar de "Podcast" si no es un programa distribuido por suscripción.
- **Campos**:
  - **Item Type**: Seleccionar "Radio Broadcast".
  - **Director**: Director del programa (autor principal).
  - **Producer/Scriptwriter/Cast Member/Guest**: Roles adicionales, si aplica.
  - **Title**: Título del episodio o programa.
  - **Abstract**: Resumen del contenido.
  - **Program Title**: Nombre del programa de radio.
  - **Episode Number**: Número del episodio, si aplica.
  - **Date**: Fecha de emisión.
  - **Running Time**: Duración del programa.
  - **Network**: Cadena de radio que emite el programa.
  - **Format**: Formato de la emisión (p. ej.﻿, "Streaming").
  - **Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

28. Report (Informe)

  - Para informes publicados por organizaciones, gobiernos o instituciones, incluidos preprints y documentos de trabajo.
  - Usar en lugar de "Book" para informes técnicos o gubernamentales.
  - Se sugiere usar "Extra" para campos como "Status" (p. ej.﻿, "preprint").
- **Campos**:
  - **Item Type**: Seleccionar "Report".
  - **Author**: Autor del informe.
  - **Title**: Título del informe.
  - **Abstract**: Resumen del contenido.
  - **Report Number**: Número asignado al informe.
  - **Report Type**: Tipo de informe (p. ej.﻿, "Informe técnico").
  - **Institution**: Organización que publica el informe.
  - **Place**: Lugar de publicación.
  - **Date**: Fecha de publicación.
  - **Pages**: Número de páginas.
  - **Series/Series Number**: Serie del informe, si aplica.
  - **DOI**: Identificador DOI, si aplica.
  - **Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

29. Software (Software)

  - Para programas de computadora, aplicaciones o software.
  - Usar en lugar de "Document" para citas de software específicas.
- **Campos**:
  - **Item Type**: Seleccionar "Software".
  - **Programmer**: Creador del software (autor principal).
  - **Title**: Nombre del software.
  - **Abstract**: Descripción del software.
  - **Version**: Versión del software (p. ej.﻿, "2.3.1").
  - **System**: Sistema operativo o plataforma (p. ej.﻿, "Windows").
  - **Company**: Empresa que publica el software.
  - **Date**: Fecha de publicación.
  - **Language**: Lenguaje de programación, si aplica.
  - **Short Title/URL/Accessed/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

30. Statute (Ley)

  - Para leyes o legislación aprobada.
  - Usar en lugar de "Bill" si la legislación ya está promulgada.
- **Campos**:
  - **Item Type**: Seleccionar "Statute".
  - **Sponsor**: Autor principal de la ley.
  - **Title**: Título oficial de la ley.
  - **Abstract**: Resumen del contenido.
  - **Name of Act**: Nombre completo de la ley.
  - **Code**: Código donde se publica la ley.
  - **Code Volume**: Volumen del código.
  - **Code Number**: Número de la ley en el código.
  - **Public Law Number**: Número de la ley pública.
  - **Date Enacted**: Fecha de promulgación.
  - **Section**: Sección citada.
  - **Pages**: Páginas en el código.
  - **Legislative Body**: Cuerpo que aprobó la ley.
  - **Session**: Sesión legislativa.
  - **History**: Historial de la ley.
  - **Language/Short Title/URL/Accessed/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

31. Thesis (Tesis)

  - Para tesis de grado, ya sean publicadas o inéditas.
  - Usar en lugar de "Manuscript" para trabajos académicos formales.
  - Se recomienda usar "Extra" para campos como "Submitted Date".
- **Campos**:
  - **Item Type**: Seleccionar "Thesis".
  - **Author**: Autor de la tesis.
  - **Title**: Título de la tesis.
  - **Abstract**: Resumen del contenido.
  - **Type**: Tipo de tesis (p. ej.﻿, "Tesis doctoral", "Tesis de maestría").
  - **University**: Universidad que otorga el grado.
  - **Place**: Lugar de la universidad.
  - **Date**: Año de presentación.
  - **# of Pages**: Número de páginas.
  - **Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

32. TV Broadcast (Emisión de televisión)

  - Para episodios de series de televisión o programas emitidos.
  - Usar en lugar de "Video Recording" para emisiones formales.
- **Campos**:
  - **Item Type**: Seleccionar "TV Broadcast".
  - **Director**: Director del episodio (autor principal).
  - **Producer/Scriptwriter/Cast Member/Guest**: Roles adicionales.
  - **Title**: Título del episodio.
  - **Abstract**: Resumen del contenido.
  - **Program Title**: Nombre del programa.
  - **Episode Number**: Número del episodio.
  - **Date**: Fecha de emisión.
  - **Running Time**: Duración del episodio.
  - **Network**: Cadena de televisión.
  - **Format**: Formato de la emisión (p. ej.﻿, "Streaming").
  - **Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

33. Video Recording (Grabación de video)

  - Para videos que no encajan en "Film", "TV Broadcast" o "Podcast" (p. ej.﻿, videos de YouTube o figuras científicas).
  - Usar en lugar de "Document" para contenido audiovisual.
- **Campos**:
  - **Item Type**: Seleccionar "Video Recording".
  - **Director**: Director del video (autor principal).
  - **Producer/Scriptwriter**: Roles adicionales.
  - **Title**: Título del video.
  - **Abstract**: Resumen del contenido.
  - **Date**: Fecha de publicación.
  - **Format**: Formato del video (p. ej.﻿, "MP4").
  - **Running Time**: Duración del video.
  - **Studio**: Estudio que produce el video.
  - **Language/Short Title/URL/Accessed/Archive/Loc. in Archive/Library Catalog/Call Number/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

34. Webpage (Página web)

  - Para páginas web genéricas que no encajan en tipos más específicos como "Blog Post" o "Report".
  - Usar como última opción si no hay un tipo más adecuado.
- **Campos**:
  - **Item Type**: Seleccionar "Webpage".
  - **Author**: Autor de la página.
  - **Title**: Título de la página.
  - **Abstract**: Resumen del contenido.
  - **Website Title**: Nombre del sitio web.
  - **Website Type**: Género del sitio (p. ej.﻿, "Sitio corporativo"), raramente usado.
  - **Date**: Fecha de publicación o actualización.
  - **Language/Short Title/URL/Accessed/Rights/Extra/Date Added/Modified**: Igual que en "Artwork".

35. Attachment (Archivo adjunto)

  - Para archivos independientes (p. ej.﻿, PDF, JPEG, DOCX) no asociados a un ítem principal.
  - Evitar su uso, ya que tiene funcionalidad limitada (no se pueden citar ni buscar adecuadamente).
  - Se recomienda asociar archivos a ítems completos (p. ej.﻿, "Journal Article" con un PDF adjunto).
- **Campos**:
  - **Item Type**: Seleccionar "Attachment".
  - **Title**: Nombre del archivo.
  - **Date Added/Modified**: Campos automáticos.

36. Note (Nota)

  - Para notas independientes usadas para organización o anotaciones.
  - No es ideal para citas, ya que usa los primeros 120 caracteres como título.
- **Campos**:
  - **Item Type**: Seleccionar "Note".
  - **Title**: Primeros 120 caracteres de la nota (automático).
  - **Date Added/Modified**: Campos automáticos.

## Tipos de Elementos No Soportados Formalmente

Zotero no soporta formalmente los siguientes tipos, pero pueden citarse usando el campo "Extra" con el formato `Type: CSL Type`. Ejemplo: `Type: dataset`.

- **Dataset (Conjunto de datos)**: Para datos crudos o conjuntos de datos.
  - **Campos sugeridos**: Usar "Report" o "Document" y agregar `Type: dataset` en "Extra". Incluir "Identifier", "Version", "Repository".
  - Se recomienda usar "Extra" para "DOI" o "Format".
- **Figure (Figura)**: Para figuras en trabajos académicos.
  - **Campos sugeridos**: Usar "Artwork" y agregar `Type: figure` en "Extra". Incluir "Medium".
  - **Información oficial**: Similar a "Artwork", pero enfocado en figuras científicas.
- **Musical Score (Partitura musical)**: Para partituras escritas.
  - **Campos sugeridos**: Usar "Book" o "Manuscript" y agregar `Type: musical_score` en "Extra".
  - Se sugiere usar "Extra" para detalles específicos.
- **Pamphlet (Folleto)**: Para trabajos publicados informalmente.
  - **Campos sugeridos**: Usar "Report" y agregar `Type: pamphlet` en "Extra".
  - **Información oficial**: Menos técnico que "Report".
- **Book Review (Reseña de libro)**: Para reseñas de libros publicadas.
  - **Campos sugeridos**: Usar "Journal Article", "Magazine Article" o "Newspaper Article" con "Reviewed Author" y agregar `Type: review-book` en "Extra".
  - Se recomienda especificar "Reviewed Title" en "Extra".
- **Treaty (Tratado)**: Para tratados legales entre naciones.
  - **Campos sugeridos**: Usar "Document" y agregar `Type: treaty` en "Extra".
  - Se sugiere consultar "Legal Citations".
  
## Campos Adicionales en "Extra"

Para campos no soportados, usar el formato `CSL Variable: Value` en el campo "Extra". Ejemplos:

- `PMID: 123456`
- `Status: in press`
- `Director: Kubrick || Stanley`

Campos comunes:

- **PMID/PMCID**: Identificadores de PubMed.
- **Status**: Estado de publicación (p. ej.﻿, "forthcoming").
- **Original Date**: Fecha original de publicación (formato ISO).
- **Director/Editorial Director/Illustrator**: Roles de creadores adicionales.

## Subtipos
### 1. Presentation 
- Class slides – Diapositivas de clase universitaria
- Conference presentation – Presentación oral en conferencia
- Keynote speech – Conferencia magistral / Keynote
- Invited talk – Charla invitada
- Guest lecture – Clase impartida como invitado
- Poster presentation – Presentación en póster
- Lightning talk – Charla relámpago (5-10 min)
- Workshop slides – Diapositivas de taller o workshop
- Seminar slides – Diapositivas de seminario
- Webinar slides – Diapositivas de webinar en línea
- Defense presentation – Defensa de tesis o proyecto final
- Teaching material – Material docente general (sin presentación formal)
### 2. Thesis 
- PhD thesis – Tesis doctoral
- Doctoral dissertation – Tesis doctoral (EE.UU.)
- Master's thesis – Tesis de maestría
- Master's dissertation – Tesis de maestría (Reino Unido)
- Bachelor's thesis – Tesis de grado / licenciatura
- Honors thesis – Tesis de honor (programas de excelencia)
- Habilitation thesis – Tesis de habilitación (Alemania, Francia)
- Thesis (unpublished) – Tesis inédita / no publicada
- Thesis (published as book) – Tesis publicada como libro
- Tesis doctoral – Tesis doctoral (etiqueta en español si prefieres)
- Tesis de maestría – Tesis de maestría (etiqueta en español si prefieres)
### 3. Website Type 
- Course homepage – Página principal del curso (Coursera, edX, Moodle)
- Syllabus – Programa / sílabus del curso
- Institutional page – Página oficial de universidad o departamento
- Personal academic page – Página personal de profesor/investigador
- Research group page – Página de grupo de investigación
- Project website – Sitio web de proyecto de investigación
- Online documentation – Documentación oficial en línea
- Government webpage – Página oficial de gobierno
- NGO webpage – Página de ONG o fundación
- Company page – Página corporativa
- Online encyclopedia entry – Entrada en Wikipedia u otra enciclopedia en línea
- Wiki page – Página de wiki (cualquier wiki)
- Landing page – Página de aterrizaje
- FAQ page – Página de preguntas frecuentes
- Contact page – Página de contacto
### 4. Forum Post
- Tweet – Publicación en Twitter/X (un solo tuit)
- Twitter thread – Hilo completo en Twitter/X
- Facebook post – Publicación en Facebook
- Reddit post – Publicación en Reddit
- Stack Overflow question – Pregunta en Stack Overflow
- Stack Overflow answer – Respuesta en Stack Overflow
- GitHub issue – Issue en GitHub
- GitHub comment – Comentario en issue o PR de GitHub
- Discord message – Mensaje en Discord
- Mastodon toot – Publicación en Mastodon
### 5. Letter 
- Personal letter – Carta personal
- Business letter – Carta comercial
- Official letter – Carta oficial
- Open letter – Carta abierta
- Love letter – Carta de amor
- Historical correspondence – Correspondencia histórica
- Letter to the editor – Carta al director (periódico/revista)
- Recommendation letter – Carta de recomendación
- Cover letter – Carta de presentación (para empleo)
### 6. Report Type
- Technical report – Informe técnico
- Government report – Informe gubernamental
- White paper – Libro blanco / documento de posición
- Working paper – Documento de trabajo
- Policy report – Informe de políticas públicas
- Annual report – Informe anual
- Consultancy report – Informe de consultoría
- Preprint – Prepublicación (arXiv, bioRxiv, SSRN)
- Institutional report – Informe institucional
- Field report – Informe de campo
- Evaluation report – Informe de evaluación
- Conference report – Informe oficial de conferencia
- Research report – Informe de investigación
- Progress report – Informe de avance
### 7. Manuscript
- Unpublished manuscript – Manuscrito inédito
- Manuscript in preparation – Manuscrito en preparación
- Manuscript submitted – Manuscrito enviado (under review)
- Manuscript accepted – Manuscrito aceptado (in press)
- Author's original – Versión original del autor (pre-revisión)
- Accepted manuscript – Versión final aceptada (post-revisión)
- Historical manuscript – Manuscrito histórico
- Lecture notes – Apuntes de clase del profesor
- Student paper – Trabajo de curso / ensayo de estudiante
- Personal notes – Mis apuntes personales
- Draft – Borrador
- Pre-print version – Versión preprint
  
## Consejos Generales

- **Selección del tipo de elemento**: Elegir el tipo más específico posible para mejorar la precisión de las citas.
- **Uso de "Extra"**: Aprovechar este campo para información no cubierta por los campos estándar.
- **Citas legales**: Consultar la sección "Legal Citations" de Zotero para soporte adicional.
- **Archivos**: Siempre asociar archivos adjuntos a ítems completos para mejor funcionalidad.
- **Idioma**: Usar códigos ISO (p. ej.﻿, "es-ES") para consistencia en el formato de títulos."

# Example
**Datos de entrada de ejemplo**: Título: "Machine Learning in Healthcare"; Autor: John Doe; Fecha: 2020; Publicación: Journal of Medical AI; Volumen: 15; Issue: 3; Páginas: 45-60; DOI: 10.1234/example; Abstract: Aplicaciones de ML en diagnósticos.

**Salida esperada**:
1. **Tipo de elemento seleccionado**: Journal Article
2. **Justificación**: Los datos describen un artículo en revista académica con volumen, issue, páginas y DOI, alineándose con "Cuándo utilizar" para publicaciones revisadas por pares, no una revista popular.
3. **Campos para ingresar en Zotero**:
   - Author: Doe, John
   - Title: Machine Learning in Healthcare
   - Publication: Journal of Medical AI
   - Abstract: Aplicaciones de ML en diagnósticos
   - Volume: 15
   - Issue: 3
   - Pages: 45-60
   - Date: 2020
   - DOI: 10.1234/example
4. **Tags o Palabras Clave (SEO):** [Machine Learning], [Healthcare AI, Medical Diagnostics, ML Applications, Journal AI, DOI Citation]
5. **Notas adicionales**: Datos completos; considera agregar ISSN si disponible en búsquedas futuras para mejorar importación automática.










## Para Calibre column subtipo

PRESENTATION, Class slides, Conference presentation, Keynote speech, Invited talk, Guest lecture, Poster presentation, Lightning talk, Workshop slides, Seminar slides, Webinar slides, Defense presentation y Teaching material, THESIS, PhD thesis, Doctoral dissertation, Master’s thesis, Master’s dissertation, Bachelor’s thesis, Honors thesis, Habilitation thesis, Dissertation (unpublished), Thesis (published as book, Tesis doctoral y Tesis de maestría, WEBPAGE, Course homepage, Syllabus, Institutional page, Personal academic page, Research group page, Project website, Online documentation, Government webpage, NGO webpage, Company page, Online encyclopedia entry, Wiki page, Landing page, FAQ page y Contact page, FORUM POST,  Tweet, Twitter thread, Facebook post, Reddit post, Stack Overflow question, Stack Overflow answer, GitHub issue, GitHub comment, Discord message y Mastodon toot, LETTER, Personal letter, Business letter, Official letter, Open letter, Love letter, Historical correspondence, Letter to the editor, Recommendation letter y Cover letter, REPORT, Technical report, Government report, White paper, Working paper, Policy report, Annual report, Consultancy report, Preprint, Institutional report, Field report, Evaluation report, Conference report, Research report y Progress report, MANUSCRIPT, Unpublished manuscript, Manuscript in preparation, Manuscript submitted, Manuscript accepted (in press), Author's original manuscript, Accepted manuscript, Historical manuscript, Lecture notes (professor), Student paper, Personal notes, Draft y Pre-print version.
