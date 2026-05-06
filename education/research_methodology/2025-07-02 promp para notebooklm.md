#prompt #ia
# PASO 1. Prompt para Generar una Instrucción de Búsqueda de Fuentes en NotebookLM

```markdown
## Tarea
Actúa como un bibliotecario académico experto con 10 años de experiencia en investigación en economía, matemáticas, estadística e informática. Tu tarea es generar una instrucción clara, concisa y detallada (máximo 500 palabras) para buscar fuentes relevantes en NotebookLM de Google, basada en el contexto proporcionado por el usuario en `[input]`.

## Solicitud
Crea una instrucción que:
- Busque fuentes confiables y relevantes (artículos académicos, libros, páginas web, videos, notas de investigación, transcripciones, etc.) en los dominios de economía, matemáticas, estadística o informática.
- Se alinee con el tema, propósito y preferencias especificados en `[input]` (por ejemplo, tesis, artículo, blog, estudio de curso, desarrollo de aplicativos).
- Priorice fuentes de alta calidad, como artículos académicos (por ejemplo, de JSTOR, Springer, Elsevier), libros de editoriales reconocidas (como Wiley, Oxford University Press), videos de creadores verificados (como canales de YouTube de universidades o expertos), o documentación técnica de sitios confiables (como GNU.org, Stack Overflow) o (peer-reviewed, editoriales reconocidas, creadores confiables).
- Sea clara, estructurada y no supere las 500 palabras.
- Use un tono profesional y académico, evitando jerga innecesaria.

## Acción
1. Analiza el contexto proporcionado en `[input]` para identificar el tema, propósito y preferencias del usuario (por ejemplo, tema: modelos econométricos, propósito: tesis, preferencias: artículos recientes).
2. Extrae palabras clave relevantes y sinónimos para optimizar la búsqueda.
3. Busca fuentes recientes (últimos 5 años, salvo excepciones justificadas) y relevantes al dominio especificado en `[input]`.
4. Verifica que las fuentes sean confiables, priorizando contenido de alta calidad académica o profesional (por ejemplo, de bases como JSTOR, Springer, universidades, repositorios académicos, canales de YouTube de expertos).
5. Incorpora las preferencias del usuario (por ejemplo, solo artículos académicos, fuentes gratuitas) si se especifican en `[input]`.
6. Asegúrate de que la instrucción sea flexible y aplicable al contexto proporcionado.

## Contexto
El usuario es un estudiante o profesional que realiza investigaciones en economía, matemáticas, estadística o informática. Los propósitos incluyen escribir tesis, artículos, blogs, estudiar cursos o desarrollar aplicativos. NotebookLM debe buscar fuentes útiles, confiables y relevantes, abarcando desde artículos académicos hasta recursos accesibles como videos o páginas web. La instrucción debe ser práctica, clara y directamente utilizable en NotebookLM.

## Input del Usuario
[input: Especifica el tema, propósito y preferencias de la búsqueda. Por ejemplo, "tema: aplicaciones de machine learning en economía, propósito: artículo para un blog, preferencias: artículos académicos y videos, publicados después de 2021."]

## Ejemplo
**Input**: [tema: métodos estadísticos para análisis de series temporales, propósito: tesis en estadística, preferencias: artículos académicos y libros, publicados después de 2020]  
**Instrucción Generada**:  
"Busque fuentes confiables sobre métodos estadísticos para análisis de series temporales, priorizando artículos académicos de bases como JSTOR, Springer o Elsevier, y libros de editoriales reconocidas como Wiley o Oxford University Press. Asegúrese de que las fuentes sean de los últimos 5 años y de nivel académico."

## Optimización
Si la respuesta no cumple con las expectativas (por ejemplo, fuentes irrelevantes o falta de detalle), solicita al usuario ajustar el `[input]` con más detalles sobre el tema, propósito o preferencias (por ejemplo, idioma, nivel de profundidad).
```


# PASO 2. Analizar estas paginas

Analiza estas páginas de productos digitales: identifica el lenguaje persuasivo, los mensajes que más se repiten, tono emocional que usan y como estructura la información para convencer al visitante 

# PASO 3. creamos landing page en Gemini con la información obtenida en NotebookLM

"Ayúdame a diseñar una landing page para vender [nombre del producto o tipo: Ebook/ plantilla/curso] inspirándote en el estilo visual de las páginas más famosas, Utiliza el análisis de tono, lenguaje y estructura que te paso a continuación como base para adaptar el contenido al público objetivo"



# PASO 4. Servicios de Enseñanza y Redacción Académica

Ofrecemos una amplia gama de servicios educativos y de redacción académica, diseñados para estudiantes universitarios, preuniversitarios y profesionales que buscan excelencia en sus proyectos académicos y profesionales. A continuación, se detallan nuestros servicios:

## Cursos Universitarios y Preuniversitarios

Impartimos cursos especializados en las siguientes áreas:

- [ ] **Macroeconomía**: Fundamentos y análisis de variables económicas a gran escala.
- [ ] **Microeconomía**: Estudio de los comportamientos económicos individuales y de mercado.
- [ ] **Economía Matemática**: Aplicación de herramientas matemáticas al análisis económico.
- [ ] **Filosofía Marxista**: Exploración de los principios y teorías del marxismo.
- [x] **Metodología de Investigación**: Técnicas para la redacción de tesis, monografías y artículos científicos. ✅ 2025-07-02
- [ ] **Matemática Básica**: Conceptos fundamentales para estudiantes de nivel inicial.
- [ ] **Cálculo y Análisis Matemático**: Desarrollo de habilidades en cálculo diferencial, integral y análisis avanzado.
- [ ] **Investigación de Mercados**: Métodos para analizar tendencias y comportamientos del consumidor.
- [ ] **Formulación y Evaluación de Proyectos**: Diseño y análisis de proyectos de inversión privada.
- [ ] **Inteligencia Comercial para Exportación**: Estrategias para la expansión en mercados internacionales.
- [ ] **Economía Preuniversitaria**: Preparación en conceptos económicos básicos para estudiantes de nivel secundario.
- [ ] **Álgebra Preuniversitaria**: Reforzamiento de álgebra para ingreso a la universidad.
- [ ] Estadistica
- [ ] Econometría

## Servicios de Redacción y Revisión Académica

- [ ] **Redacción y Revisión de Tesis y Monografías**: Asesoría integral en la elaboración, estructuración y corrección de trabajos académicos, garantizando calidad y rigor.
- [ ] **Redacción de Trabajos Académicos en LaTeX**: Elaboración de documentos académicos con formato profesional utilizando LaTeX, ideal para presentaciones impecables.
- [ ] **Formulación y Evaluación de Proyectos de Inversión Privada**: Desarrollo de planes de negocio y análisis financiero para proyectos de inversión.

## Cursos Especializados

- [x] **Manejo de Zotero y Sistema APA**: Capacitación en el uso de Zotero para la gestión de referencias bibliográficas y aplicación del sistema APA en trabajos académicos. ✅ 2025-07-03
- [ ] **Curso de Software Económicos**: Formación en herramientas de software especializadas para el análisis económico y financiero.
- [x] **Curso de LaTeX**: Aprendizaje práctico para la creación de documentos académicos y profesionales con LaTeX. ✅ 2025-07-03

Nuestros servicios están diseñados para brindar un acompañamiento personalizado, asegurando un aprendizaje efectivo y resultados de alta calidad en cada proyecto.




---

PARA investigadores

- Ayúdame a entender el foco y objetivo de investigación de estos artículos 
- Crea una revisión de literatura con base en las fuentes