# 📚 Repositorio de Prompts — Edison Achalma

> **Colección personal y profesional de prompts optimizados para inteligencia artificial**, organizados por categorías temáticas para investigación académica, redacción, productividad y educación.

---

## 📋 Tabla de Contenidos

- [Descripción General](#descripción-general)
- [Autor](#autor)
- [Estructura del Repositorio](#estructura-del-repositorio)
- [Categorías de Prompts](#categorías-de-prompts)
  - [Escritura Académica](#-escritura-académica)
  - [Creación de Contenido](#-creación-de-contenido)
  - [Educación](#-educación)
  - [Meta-Prompts](#-meta-prompts)
  - [Herramientas de Productividad](#-herramientas-de-productividad)
  - [Documentos Administrativos](#-documentos-administrativos)
- [Guía de Uso](#guía-de-uso)
- [Marcos de Trabajo Utilizados](#marcos-de-trabajo-utilizados)
- [Convenciones y Estándares](#convenciones-y-estándares)
- [Licencia](#licencia)
- [Contacto](#contacto)

---

## Descripción General

Este repositorio contiene una colección curada de **prompts estructurados y optimizados** para modelos de lenguaje (LLMs) como Claude, GPT y Grok. Los prompts están diseñados para maximizar la calidad y precisión de las respuestas en contextos académicos, profesionales y de productividad personal.

Cada prompt sigue metodologías reconocidas de ingeniería de prompts (LangGPT, ROSES, TRACE, RTF, entre otros) y está documentado con su justificación, flujo de trabajo y ejemplos de uso.

### ¿Para quién es este repositorio?

- 🎓 **Estudiantes universitarios** que necesitan asistencia en redacción académica, tesis y monografías.
- 👨‍🏫 **Docentes e investigadores** que buscan automatizar tareas repetitivas de redacción y análisis.
- 📊 **Economistas y científicos sociales** que trabajan con metodología de investigación cuantitativa.
- ✍️ **Creadores de contenido** que producen blogs, artículos SEO y material educativo.
- 🛠️ **Usuarios de herramientas de productividad** como Zotero, Obsidian y Super Productivity.

---

## Autor

| Campo                    | Información                                                    |
| ------------------------ | -------------------------------------------------------------- |
| **Nombre**               | Elmer Edison Achalma Mendoza                                   |
| **Alias**                | Edison Achalma                                                 |
| **ORCID**                | [0000-0001-6996-3364](https://orcid.org/0000-0001-6996-3364)   |
| **Correo institucional** | elmer.achalma.09@unsch.edu.pe                                  |
| **Correo personal**      | achalmed.18@gmail.com                                          |
| **Sitio web**            | [achalmaedison.netlify.app](https://achalmaedison.netlify.app) |
| **Afiliación**           | Universidad Nacional de San Cristóbal de Huamanga (UNSCH)      |
| **Escuela**              | Escuela Profesional de Economía                                |
| **Ciudad**               | Ayacucho, Perú                                                 |
| **Licencia**             | MIT                                                            |

---

## Estructura del Repositorio

```
📁 repositorio-prompts/
│
├── 📄 LICENSE
├── 📄 README.md
│
├── 📁 academic_writing/
│   ├── 📁 apa_quarto/
│   │   └── 2025-12-10 prompt generador interactivo avanzado de plantillas apaquarto.md
│   └── 📁 monographs/
│       ├── 2026-01-16 prompt 3 para generar y revisar contenido de monografías en formato markdown con estilo APA.md
│       ├── 2026-02-15 prompt 1 para generar títulos de monografias.md
│       ├── 2026-02-15 prompt 2 para generar la estructura de monografías.md
│       ├── 2026-02-15 prompt 5 para generar contenido de presentaciones en LaTex.md
│       └── 2026-02-15 prompt 6 para generar guion de presentaciones.md
│
├── 📁 content_creation/
│   ├── 2025-01-19 prompt para blogs seo.md
│   └── 2025-04-18 prompt para metadescripcion.md
│
├── 📁 education/
│   ├── 📁 courses/
│   │   └── 2025-07-01 prompt para estudiar cursos.md
│   ├── 📁 english/
│   │   ├── 2025-05-25 prompt para estudiar ingles.md
│   │   └── 2025-06-17 prompt para aprender ingles con duolingo.md
│   └── 📁 research_methodology/
│       ├── 2025-01-19 prompt para investigacion cuantitativa.md
│       ├── 2025-03-28 prompt para formulacion de proyectos social.md
│       └── 2025-07-02 promp para notebooklm.md
│
├── 📁 meta_prompts/
│   ├── 2024-08-02 prompit.md
│   └── 2025-05-19 prompt para generar prompts.md
│
├── 📁 productivity_tools/
│   ├── 📁 super_productivity/
│   │   └── 2025-11-25 prompt para super productivity.md
│   └── 📁 zotero/
│       ├── 2025-04-18 prompt para zotero 1 - catalogacion.md
│       ├── 2025-04-23 prompt para zotero 2 - generador de fichas textuales.md
│       └── 2025-05-25 prompt para zotero 3 - generador de parafraseo complejo.md
│
└── 📁 administrative/
    └── 2025-07-01 prompt para documentos administrativos.md
```

---

## Categorías de Prompts

---

### 📝 Escritura Académica

Prompts especializados para producción de documentos académicos con estándares internacionales.

#### `academic_writing/apa_quarto/`

##### 🔹 Generador Interactivo Avanzado de Plantillas Apaquarto

**Archivo:** `2025-12-10 prompt generador interactivo avanzado de plantillas apaquarto.md`

Genera plantillas completas de archivos Quarto (`.qmd`) utilizando la extensión **apaquarto** para documentos en estilo **APA 7ª edición**.

| Campo                  | Detalle                                 |
| ---------------------- | --------------------------------------- |
| **Marco**              | LangGPT                                 |
| **Versión**            | 3.0                                     |
| **Formatos de salida** | `.docx`, `.html`, `.pdf`, `.typst`      |
| **Especialización**    | Economía, ciencias sociales, psicología |

**Características principales:**

- Formulario interactivo con tres modos: completo (A), paso a paso (B) y rápido (C)
- Generación automática de YAML con todos los metadatos APA
- Ejemplos con código R para tablas (`flextable`) y figuras (`ggplot2`)
- Soporte para múltiples autores con afiliaciones compartidas y roles CRediT
- Validación automática de errores comunes
- Checklist de verificación antes de renderizar
- Soporte multilingüe (español, inglés, francés, etc.)

**Datos de autor por defecto configurados:**

```yaml
name: Edison Achalma
orcid: 0000-0001-6996-3364
email: elmer.achalma.09@unsch.edu.pe
affiliation: Universidad Nacional de San Cristóbal de Huamanga
```

---

#### `academic_writing/monographs/`

##### 🔹 Generador de Títulos de Monografías

**Archivo:** `2026-02-15 prompt 1 para generar títulos de monografias.md`

Genera entre 3 y 5 propuestas de títulos académicos optimizados para monografías universitarias.

| Campo                   | Detalle                                 |
| ----------------------- | --------------------------------------- |
| **Marco**               | ROSES                                   |
| **Audiencia**           | Estudiantes universitarios              |
| **Extensión de título** | Máximo 120 caracteres (~14 palabras)    |
| **Tipos**               | Compilación, Investigación, Experiencia |

**Qué genera:**

- Variante 1: Descriptiva directa (más formal, técnica)
- Variante 2: Descriptiva con énfasis (balance entre precisión y atractivo)
- Variante 3: Título compuesto (metáfora + descripción técnica)
- Justificación de cada propuesta
- Recomendación final fundamentada

---

##### 🔹 Generador de Estructura de Monografías

**Archivo:** `2026-02-15 prompt 2 para generar la estructura de monografías.md`

Genera automáticamente la estructura jerárquica completa de una monografía según su tipo.

| Campo                   | Detalle                                 |
| ----------------------- | --------------------------------------- |
| **Marco**               | ROSES                                   |
| **Tipos de monografía** | Compilación, Investigación, Experiencia |
| **Profundidad máxima**  | 3 niveles (1.1.1)                       |
| **Numeración**          | Sistema decimal                         |

**Cómo funciona:**

1. Identifica automáticamente el tipo de monografía según el tema
2. Genera capítulos (3–4) con subcapítulos específicos (3–5 por capítulo)
3. Produce sub-subcapítulos cuando la complejidad lo requiere
4. Entrega tabla de verificación de calidad estructural
5. Incluye sugerencias de distribución de páginas

---

##### 🔹 Generador de Contenido de Monografías (APA + Markdown)

**Archivo:** `2026-01-16 prompt 3 para generar y revisar contenido de monografías en formato markdown con estilo APA.md`

El prompt más completo para generación de monografías académicas. Transforma material disperso en documentos listos para renderizar con Quarto.

| Campo                  | Detalle                                  |
| ---------------------- | ---------------------------------------- |
| **Marco**              | ROSES                                    |
| **Extensión estimada** | 20–50 páginas (8.000–20.000 palabras)    |
| **Formato de salida**  | Markdown compatible con Quarto/apaquarto |
| **Estilos**            | APA 7ª edición                           |

**Capacidades:**

- Genera YAML completo con metadatos APA
- Produce introducción, marco teórico, metodología, resultados, discusión y conclusiones
- Incluye código R para tablas y figuras
- Aplica 15 principios de redacción académica anti-IA
- Maneja ecuaciones en LaTeX (inline y display)
- Genera referencias bibliográficas en formato `.bib`
- Incluye apéndices con referencias cruzadas automáticas

**Datos por defecto del autor:**

```
Autor: Edison Achalma Mendoza
Email: elmer.achalma.09@unsch.edu.pe
ORCID: 0000-0001-6996-3364
Institución: UNSCH — Escuela Profesional de Economía
```

---

##### 🔹 Generador de Guión de Presentaciones (Clase)

**Archivo:** `2026-02-15 prompt 6 para generar guion de presentaciones.md`

Crea guiones completos y naturales para cada diapositiva de una presentación académica.

| Campo                 | Detalle                            |
| --------------------- | ---------------------------------- |
| **Marco**             | LangGPT                            |
| **Formato de salida** | Markdown (compatible con Obsidian) |
| **Tiempo estimado**   | 1–1.5 min por diapositiva          |
| **Audiencias**        | Pregrado, posgrado, profesionales  |

**El guión incluye:**

- Texto conversacional que suena natural (no leído)
- Indicaciones `[PAUSA]`, `[SEÑALAR]`, `**énfasis**`
- Preguntas retóricas para mantener engagement
- Respuestas a preguntas probables de los estudiantes
- Transiciones fluidas entre diapositivas
- Cronograma general y gestión de tiempo
- Consejos de lenguaje corporal
- Checklist pre-clase y post-clase

---

##### 🔹 Generador de Presentaciones en LaTeX/Beamer

**Archivo:** `2026-02-15 prompt 5 para generar contenido de presentaciones en LaTex.md`

Genera código LaTeX/Beamer completo, funcional y bien documentado para presentaciones académicas profesionales.

| Campo              | Detalle                        |
| ------------------ | ------------------------------ |
| **Marco**          | ROSES                          |
| **Tecnología**     | LaTeX + Beamer                 |
| **Aspect ratio**   | 16:9 (moderno) o 4:3 (clásico) |
| **Compatibilidad** | TeXLive, MiKTeX                |

**Patrones de slides disponibles:**

- Bullets simples
- Dos columnas
- Figura + texto
- Ecuaciones matemáticas (amsmath)
- Código fuente (listings)
- Diagramas TikZ
- Bloques destacados (block, alertblock, exampleblock)
- Animaciones y overlays
- Separadores de sección

---

### 📢 Creación de Contenido

Prompts para producción de contenido digital optimizado para SEO y redes.

#### `content_creation/`

##### 🔹 Suite de Prompts para Blogs SEO

**Archivo:** `2025-01-19 prompt para blogs seo.md`

Colección de 5 prompts especializados para el ciclo completo de creación de contenido de blog.

| #   | Prompt                    | Función                                                              |
| --- | ------------------------- | -------------------------------------------------------------------- |
| 1   | Generador de Índice SEO   | Crea índices optimizados con H1, H2, H3 y preguntas de investigación |
| 2   | Optimizador de Índice     | Mejora índices existentes para SEO y UX                              |
| 3   | Mejora de Contenido       | Añade rigor académico con citas APA y optimización SEO               |
| 4   | Generador de Introducción | Crea introducciones de 200–300 palabras con gancho y keywords        |
| 5   | Generador de Metadatos    | Produce título, subtítulo, abstract, keywords y metadescripción      |

**Herramientas SEO de referencia:** Keyword Suggest (Kiwosan), Google Keyword Planner, Ahrefs, SEMrush

**Elementos generados por el Prompt 5 (metadatos completos):**

- Título H1 (40–65 caracteres)
- Subtítulo H2 (10–15 palabras)
- Running Head / Título corto (máx. 50 caracteres)
- Tags SEO (1 principal + 3–5 secundarios/LSI)
- Metadescripción (150–160 caracteres)
- Abstract en inglés (150–250 palabras, formato APA)
- Keywords APA en inglés (3–5 términos)
- Categorías académicas

---

##### 🔹 Generador de Metadescripciones

**Archivo:** `2025-04-18 prompt para metadescripcion.md`

Genera metadescripciones únicas, relevantes y optimizadas siguiendo las directrices oficiales de Google.

**Criterios aplicados:**

- Unicidad por página
- 150–160 caracteres máximos
- CTA implícita
- Integración natural de palabra clave
- Cumplimiento de directrices del Centro de la Búsqueda de Google

---

### 🎓 Educación

Prompts para aprendizaje, estudio y metodología de investigación.

#### `education/courses/`

##### 🔹 Asistente de Estudio Progresivo de Textos Académicos

**Archivo:** `2025-07-01 prompt para estudiar cursos.md`

Tutor académico especializado en análisis progresivo de textos complejos en economía, filosofía, derecho y ciencias afines.

| Campo              | Detalle                                                                  |
| ------------------ | ------------------------------------------------------------------------ |
| **Marco**          | ROSES                                                                    |
| **Disciplinas**    | Economía, matemáticas, estadística, filosofía, derecho                   |
| **Tipos de texto** | Ensayos, libros académicos, artículos científicos, tesis, notas de clase |

**Proceso de análisis por sección:**

1. Explicación inicial del concepto
2. Identificación de ideas principales y secundarias (para subrayado selectivo)
3. Vocabulario desconocido con definiciones contextualizadas
4. Conceptos previos necesarios
5. Explicación detallada con ejemplos y analogías
6. Resumen en viñetas con abreviaturas y símbolos
7. Preguntas para reflexión crítica

---

#### `education/english/`

##### 🔹 Asistente para Cursos de Inglés

**Archivo:** `2025-05-25 prompt para estudiar ingles.md`

Procesa materiales de cursos de inglés (tipo libro de texto) y genera respuestas detalladas con pronunciaciones IPA y traducciones.

| Campo                 | Detalle                |
| --------------------- | ---------------------- |
| **Marco**             | ROSES                  |
| **Nivel**             | Básico a intermedio    |
| **Formato de salida** | Markdown para Obsidian |

**Secciones que procesa:**

- Speaking, Reading, Vocabulary, Grammar, Listening, Pronunciation, Writing
- Para cada tarea: instrucciones + respuestas en inglés y español
- Pronunciación IPA + fonética españolizada
- Simulaciones de conversaciones nativas con contexto cultural
- Ejercicios de corrección y mejora de redacción

---

##### 🔹 Asistente para Aprender Inglés con Duolingo

**Archivo:** `2025-06-17 prompt para aprender ingles con duolingo.md`

Transforma apuntes y frases de Duolingo en material de estudio enriquecido.

| Campo              | Detalle                 |
| ------------------ | ----------------------- |
| **Marco**          | LangGPT                 |
| **Nivel objetivo** | A1 → B1                 |
| **Formato**        | Markdown con tablas IPA |

**Estructura de cada nota generada:**

```markdown
- Glosario con IPA y fonética
- Notas gramaticales y reglas
- Frases similares/variaciones (tabla)
- Lecturas cortas (50-100 palabras)
- Speaking practice (diálogos)
- Ejercicios interactivos
```

---

#### `education/research_methodology/`

##### 🔹 Suite Completa para Investigación Cuantitativa

**Archivo:** `2025-01-19 prompt para investigacion cuantitativa.md`

La colección más extensa del repositorio: **12 prompts secuenciales** para desarrollar un anteproyecto de investigación cuantitativa completo.

| #   | Sección                       | Descripción                                                 |
| --- | ----------------------------- | ----------------------------------------------------------- |
| 0   | Búsqueda bibliográfica        | Ecuaciones de búsqueda en Scopus, WoS, Google Scholar       |
| 1   | Tema de investigación         | Identificación y delimitación del tema                      |
| 2   | Título                        | Condensación del tema en un título preciso                  |
| 3   | Enunciado del problema        | Descripción del problema con evidencias                     |
| 4   | Formulación del problema      | Pregunta general y específicas                              |
| 5   | Objetivos                     | General y específicos con verbos por nivel de investigación |
| 6   | Justificación y delimitación  | Teórica, práctica, metodológica y social                    |
| 7   | Antecedentes                  | Revisión y redacción de antecedentes (17 líneas mínimo)     |
| 8   | Tipo y nivel de investigación | Clasificación con justificación APA                         |
| 9   | Hipótesis y variables         | Formulación y definición conceptual/operacional             |
| 10  | Diseño experimental           | Experimental, cuasiexperimental o no experimental           |
| 11  | Población y muestra           | Determinación con fórmulas estadísticas                     |
| 12  | Instrumentos                  | Cuestionarios, entrevistas, observación                     |

---

##### 🔹 Prompts para Formulación de Proyectos de Inversión Pública

**Archivo:** `2025-03-28 prompt para formulacion de proyectos social.md`

Prompts especializados en metodología del SNIP peruano para formulación y evaluación de proyectos de inversión pública.

**Módulos disponibles:**

- Diagnóstico del área de estudio e involucrados
- Árbol de problemas (causas, efectos, problema central)
- Árbol de medios y fines (en código Mermaid)
- Identificación y análisis de acciones y alternativas
- Análisis de demanda y oferta
- Balance oferta-demanda y brecha
- Costos a precios privados y sociales
- Evaluación social (VANS, TIRS, análisis de sensibilidad)
- Sostenibilidad y gestión
- Matriz de Marco Lógico (MML)

---

##### 🔹 Generación de Instrucciones para NotebookLM

**Archivo:** `2025-07-02 promp para notebooklm.md`

Genera instrucciones optimizadas para búsqueda de fuentes académicas en NotebookLM de Google.

**Incluye flujo de 4 pasos:**

1. Generación de instrucción de búsqueda de fuentes
2. Análisis de páginas encontradas
3. Creación de landing page en Gemini con la información
4. Catálogo de servicios de enseñanza y redacción académica

---

### 🧰 Meta-Prompts

Prompts para crear y optimizar otros prompts.

#### `meta_prompts/`

##### 🔹 Generador Universal de Prompts

**Archivo:** `2025-05-19 prompt para generar prompts.md`

Ingeniero de prompts experto que selecciona el marco óptimo y genera prompts estructurados de alta calidad.

| Campo                     | Detalle               |
| ------------------------- | --------------------- |
| **Marco del meta-prompt** | LangGPT               |
| **Marcos disponibles**    | 15 marcos distintos   |
| **Formato de salida**     | Markdown estructurado |

**Marcos de trabajo disponibles:**

| Marco       | Ideal para                                   |
| ----------- | -------------------------------------------- |
| **RTF**     | Tareas simples y directas                    |
| **APE**     | Acciones con propósito y expectativas claras |
| **CHAT**    | Proyectos con antecedentes complejos         |
| **ROSES**   | Soluciones a problemas con pasos definidos   |
| **LangGPT** | Sistemas complejos y roles especializados    |
| **SCOPE**   | Planificación estratégica con evaluación     |
| **TRACE**   | Tareas técnicas con ejemplos de referencia   |
| **SPAR**    | Análisis situación-problema-acción-resultado |
| **CARE**    | Contexto con acción y resultados esperados   |
| **COAST**   | Proyectos con soporte tecnológico            |
| **RACE**    | Roles con acciones y resultados              |
| **RISE**    | Roles con input, pasos y expectativas        |
| **SAGE**    | Análisis situacional con evaluación          |
| **TAG**     | Tareas simples con metas claras              |
| **CRISPE**  | Generación creativa con múltiples enfoques   |
| **SMART**   | Metas específicas, medibles y con tiempo     |

---

##### 🔹 Colección de Prompts por Dominio

**Archivo:** `2024-08-02 prompit.md`

Colección histórica de prompts base organizados por dominio profesional.

**Dominios cubiertos:**

| Dominio                              | Número de prompts |
| ------------------------------------ | ----------------- |
| Generación de texto (ChatGPT)        | 5                 |
| Generación de imágenes               | 5                 |
| Análisis económico                   | 10                |
| Tesis académica                      | 15                |
| Blog de economía                     | 10                |
| Filosofía académica                  | 8                 |
| Ciencias políticas                   | 8                 |
| Filosofía marxista/leninista/maoísta | 6                 |
| EViews (econometría)                 | 8                 |
| Stata                                | 8                 |
| RStudio / R                          | 8                 |
| LaTeX                                | 8                 |
| Python / Conda                       | 8                 |
| GNU/Linux                            | 8                 |
| Redacción académica                  | 10                |
| Normas APA                           | 8                 |
| Normas Vancouver                     | 6                 |

---

### 🛠️ Herramientas de Productividad

Prompts integrados con herramientas específicas de productividad académica.

#### `productivity_tools/super_productivity/`

##### 🔹 Sistema Integral de Productividad — Super Productivity

**Archivo:** `2025-11-25 prompt para super productivity.md`

El prompt más extenso y complejo del repositorio. Transforma cualquier documento o tarea en bloques copy-paste listos para Super Productivity.

| Campo                 | Detalle             |
| --------------------- | ------------------- |
| **Marco**             | LangGPT             |
| **Versión**           | 3.0                 |
| **Sistema operativo** | Kubuntu Linux (KDE) |

**Capacidades (3 módulos principales):**

**Módulo A — Conversor de Documentos:**
Transforma convocatorias, cronogramas, syllabi, planes de trabajo en proyectos estructurados por fases con etiquetas y horarios.

**Módulo B — Conversor de Material de Estudio:**
Detecta el tipo de material y genera sesiones de estudio estructuradas:

| Tipo de material    | Estructura                         |
| ------------------- | ---------------------------------- |
| Temario             | Por temas/unidades                 |
| Presentación PPT    | Por secciones de diapositivas      |
| Capítulo de libro   | Método SQ3R adaptado               |
| Artículo científico | Estructura IMRyD                   |
| Syllabus            | Por semanas/unidades               |
| Apuntes de clase    | Por bloques temáticos              |
| Video de clase      | Por timestamps o bloques de 25 min |
| Glosario            | Por bloques de 8–12 conceptos      |

**Módulo C — Asistente de Productividad Diaria:**
Detecta y trabaja con 8 gatillos de procrastinación:

| Gatillo              | Estrategia                        |
| -------------------- | --------------------------------- |
| 🌊 Overwhelm         | Sesión de foco de 10 minutos      |
| ✨ Perfeccionismo    | Progress over Perfection (30 min) |
| ❓ Falta de claridad | Claridad rápida (10 min)          |
| 😴 Aburrimiento      | Game On con sistema de puntos     |
| 😨 Miedo             | Experimento seguro de 5 min       |
| 📱 Distracciones     | Fortaleza + Firejail              |
| 🔋 Baja energía      | Reboot físico + tarea fácil       |
| 😤 Resistencia       | ¿Por qué sí? + Pair with Pleasure |

**18 modos de planificación disponibles:**

| #   | Modo                   | Función                      |
| --- | ---------------------- | ---------------------------- |
| 1   | Next Best Action       | Una sola tarea recomendada   |
| 2   | 90-Min Power Block     | Bloque de foco intenso       |
| 3   | Quick Win Hunter       | Victorias en 30 min          |
| 4   | Daily Blueprint        | Plan completo del día        |
| 5   | Reality-Based Schedule | Horario realista             |
| 6   | Minimum Viable Day     | Lo esencial cuando hay caos  |
| 7   | Big Rocks Week         | 3 prioridades semanales      |
| 8   | Realistic Week Planner | Semana con interrupciones    |
| 9   | Procrastination Buster | Desbloqueo específico        |
| 10  | 2-Minute Momentum      | Arranque mínimo              |
| 11  | Pattern Interrupt      | Romper espirales             |
| 12  | Micro Habit Designer   | Hábitos de 2 minutos         |
| 13  | Keystone Habit Finder  | Hábito con efecto cascada    |
| 14  | Bad Habit Replacer     | Reemplazar hábitos negativos |
| 15  | Quick Decision Maker   | Decisión en 10 min           |
| 16  | Problem Solver Express | Resolución exprés            |
| 17  | Stuck → Unstuck        | Desbloqueo de proyectos      |
| 18  | Weekly Review          | Revisión semanal             |

**Herramientas integradas en el flujo de trabajo:**
`Super Productivity` · `Zotero` · `Obsidian` · `Xournal++` · `RStudio` · `VS Code` · `LaTeX` · `Firejail` · `GnuCash` · `Duolingo` · `edX`

---

#### `productivity_tools/zotero/`

##### 🔹 Catalogación en Zotero

**Archivo:** `2025-04-18 prompt para zotero 1 - catalogacion.md`

Genera entradas manuales completas para Zotero identificando el tipo de elemento más adecuado entre los 36 tipos disponibles.

**36 tipos de elementos soportados:**

```
Artwork · Audio Recording · Bill · Blog Post · Book · Book Section · Case
Conference Paper · Dictionary Entry · Document · Email · Encyclopedia Article
Film · Forum Post · Hearing · Instant Message · Interview · Journal Article
Letter · Magazine Article · Manuscript · Map · Newspaper Article · Patent
Podcast · Presentation · Radio Broadcast · Report · Software · Statute
Thesis · TV Broadcast · Video Recording · Webpage · Attachment · Note
```

**Tipos no soportados (manejados vía `Extra`):**

- Dataset, Figure, Musical Score, Pamphlet, Book Review, Treaty

**Subtipos especializados documentados:**

- Presentation: 12 subtipos (Class slides, Poster, Webinar, etc.)
- Thesis: 11 subtipos (PhD, Master's, Bachelor's, etc.)
- Report: 14 subtipos (Technical, Preprint, Working paper, etc.)
- Manuscript: 12 subtipos
- Webpage: 15 subtipos
- Forum Post: 10 subtipos (incluyendo Tweet, Reddit, Stack Overflow)
- Letter: 9 subtipos

**Tags SEO generados automáticamente:**

- 1 palabra clave principal
- 3–5 palabras clave secundarias/LSI

---

##### 🔹 Generador de Fichas Textuales

**Archivo:** `2025-04-23 prompt para zotero 2 - generador de fichas textuales.md`

Genera fichas textuales académicas completas en formato Markdown para Zotero Better Notes.

| Campo                 | Detalle                    |
| --------------------- | -------------------------- |
| **Marco**             | LangGPT                    |
| **Norma de citas**    | APA 7ª edición             |
| **Formato de salida** | Markdown para Better Notes |
| **Mínimo de citas**   | 7 por sección/capítulo     |

**Estructura de cada ficha:**

```markdown
# Título del texto

**Referencia completa** (APA 7ª ed.)

## Summary / Resumen (150-200 palabras)

## Quotes / Citas (mínimo 7)

- Cita textual exacta
- Traducción (si texto en inglés)
- Idea principal
- Palabras clave
- Ideas secundarias
- Parafraseo (6 pasos Turnitin)
- Observaciones/Puntos clave
- Etiqueta emoji

## Questions / Preguntas (3-5 críticas)

## New or Relevant Words to Define

## New Citations / Nuevas citas
```

**Sistema de etiquetas/emojis:**

| Emoji | Categoría                 |
| ----- | ------------------------- |
| 🧠    | Definición/Concepto       |
| 💬    | Cita textual poderosa     |
| 📚    | Marco teórico             |
| 🎯    | Idea principal            |
| 🔄    | Argumento/Contraargumento |
| 🔴    | Datos/Resultados          |
| 🧪    | Hallazgo/Descubrimiento   |
| 🧩    | Ejemplo/Caso              |
| ⚠️    | Problema/Vacío            |
| ✅    | Conclusión                |

**Sistema de colores de subrayado:**

| Color          | Tipo de contenido           |
| -------------- | --------------------------- |
| 🟡 Amarillo    | Concepto / definición       |
| 🔵 Azul        | Teoría o enfoque            |
| 🟢 Verde       | Idea principal              |
| 🟠 Naranja     | Idea secundaria             |
| 🌸 Magenta     | Cita potente / frase clave  |
| 🔴 Rojo        | Dato / estadística          |
| 🟣 Morado      | Argumento / contraargumento |
| ⚪ Gris claro  | Palabra clave               |
| ⚫ Gris oscuro | Palabra desconocida         |

---

##### 🔹 Generador de Parafraseo Complejo

**Archivo:** `2025-05-25 prompt para zotero 3 - generador de parafraseo complejo.md`

Genera párrafos académicos con parafraseo complejo integrando múltiples fuentes.

| Campo                     | Detalle                                     |
| ------------------------- | ------------------------------------------- |
| **Marco**                 | LangGPT                                     |
| **Norma**                 | APA 7ª edición                              |
| **Fuentes por párrafo**   | Mínimo 3, máximo 6                          |
| **Extensión del párrafo** | 150–200 palabras (~17 líneas)               |
| **Método**                | 6 pasos Turnitin + 8 técnicas de parafraseo |

**Las 8 técnicas de parafraseo aplicadas:**

| #   | Técnica                                      |
| --- | -------------------------------------------- |
| 1   | Cambio de función gramatical                 |
| 2   | Uso de sinónimos                             |
| 3   | Expresión alternativa de números/porcentajes |
| 4   | Cambio de orden de palabras/ideas            |
| 5   | Diferentes estructuras para definiciones     |
| 6   | Variación en indicadores de atribución       |
| 7   | Cambio en estructura de oraciones            |
| 8   | Conservación de términos clave               |

**Estructura del párrafo generado:**

1. Idea principal (2–3 líneas)
2. Desarrollo descriptivo (8–10 líneas)
3. Idea complementaria (3–4 líneas)
4. Conclusión (2–3 líneas)

**Indicadores de atribución incluidos:**
`plantea`, `sostienen`, `describen`, `según`, `de acuerdo con`, `afirma`, `señala`, `argumenta`, `postula`, `concluye`, `enfatiza`, `analiza`

---

### 📄 Documentos Administrativos

Prompts para redacción de documentos formales en el ámbito peruano.

#### `administrative/`

##### 🔹 Suite de Documentos Administrativos

**Archivo:** `2025-07-01 prompt para documentos administrativos.md`

Cuatro prompts especializados en documentos administrativos peruanos conforme al TUO de la Ley N° 27444.

| #   | Documento            | Descripción                                             |
| --- | -------------------- | ------------------------------------------------------- |
| 1   | **Solicitud formal** | Simple y colectiva (memorial) con formulario rellenable |
| 2   | **Oficio**           | Simple y múltiple con distribución                      |
| 3   | **Informe**          | Administrativo con carácter de declaración jurada       |
| 4   | **Memorando**        | Simple y múltiple de comunicación interna               |

**Datos por defecto del solicitante:**

```
Nombre: Elmer Edison Achalma Mendoza
DNI: 76932189
Código: COD-09170105
Domicilio: AA HH Covadonga Mz I Lt 05
Celular: 934179301
Email institucional: elmer.achalma.09@unsch.edu.pe
Email personal: achalmed.18@gmail.com
Ciudad: Ayacucho
```

**Estructura de cada documento:**

- Membrete, código, fecha, destinatario
- Sumilla/asunto, referencia (si aplica)
- Exordio, exposición, conclusión
- Antefirma, firma y posfirma, sello
- Anexo y con copia/distribución

---

## Guía de Uso

### Cómo usar un prompt

1. **Navega** a la carpeta temática que corresponda a tu necesidad.
2. **Abre** el archivo Markdown del prompt seleccionado.
3. **Lee** la sección de `Rol`, `Objetivos` y `Restricciones` para entender qué hace.
4. **Copia** el bloque de código del prompt (marcado con triple backtick ` ``` `).
5. **Pega** en tu modelo de IA preferido (Claude, GPT, Grok, etc.).
6. **Completa** la información que el prompt solicita en los campos indicados con `[Inserta aquí]`.
7. **Ajusta** el output con las opciones de mejora iterativa al final de cada prompt.

### Convención de nombres de archivos

Los archivos siguen el formato:

```
YYYY-MM-DD prompt [número] para [descripción].md
```

Ejemplo: `2026-02-15 prompt 3 para generar y revisar contenido de monografías en formato markdown con estilo APA.md`

### Completar campos obligatorios

Todos los prompts usan la misma convención para campos que el usuario debe completar:

- `[Inserta aquí]` → Reemplazar con tu información
- `[Tema específico]` → Reemplazar con tu tema concreto
- `[ ]` → Checkbox: marcar con `[x]` para activar opciones
- Datos con "por omisión" → Se usan los datos de Edison Achalma por defecto si no se especifican

---

## Marcos de Trabajo Utilizados

Este repositorio implementa los siguientes marcos de ingeniería de prompts:

### LangGPT

Ideal para sistemas complejos con roles especializados, flujos de trabajo multi-etapa y prompts que requieren alta consistencia. Usado en: Sistema de Productividad, Generador de Fichas, Apaquarto.

### ROSES (Role · Objective · Scenario · Solution · Steps)

Ideal para tareas con contexto realista y soluciones paso a paso. Usado en: Monografías, Metodología de Investigación, Estudiar cursos.

### RTF (Role · Task · Format)

Para tareas simples y directas. Usado como base en prompts de generación de texto corto.

### APE (Action · Purpose · Expectation)

Para prompts orientados a resultados con propósito claro. Usado en generación de contenido SEO.

---

## Convenciones y Estándares

### Normas aplicadas

- **APA 7ª edición** para citas, referencias y estructura de documentos académicos
- **Estilo Quarto/apaquarto** para documentos renderizables
- **Formato Markdown** compatible con Obsidian, Zotero Better Notes y GitHub
- **ISO 639-1** para códigos de idioma en YAML (`es`, `en`, `fr`, etc.)
- **Sistema decimal** para numeración de secciones en monografías
- **Método Turnitin de 6 pasos** para parafraseo ético

### Etiquetas de contenido (tags)

Los archivos pueden estar marcados con las siguientes etiquetas en su encabezado:

| Tag                          | Descripción                             |
| ---------------------------- | --------------------------------------- |
| `#prompt`                    | Archivo de prompt principal             |
| `#ia`                        | Relacionado con inteligencia artificial |
| `#metodologia_investigacion` | Metodología de investigación científica |
| `#redaccion`                 | Redacción académica o profesional       |
| `#seo`                       | Optimización para motores de búsqueda   |
| `#zotero`                    | Integración con Zotero                  |
| `#productividad`             | Herramientas de productividad personal  |
| `#idioma`                    | Aprendizaje de idiomas                  |
| `#apa`                       | Normas APA                              |

---

## Historial de Versiones

| Fecha      | Descripción                                                 |
| ---------- | ----------------------------------------------------------- |
| 2024-08-02 | Primera colección de prompts base (`prompit.md`)            |
| 2025-01-19 | Prompts para investigación cuantitativa y SEO               |
| 2025-03-28 | Prompts para formulación de proyectos de inversión pública  |
| 2025-04-18 | Sistema de catalogación en Zotero (parte 1)                 |
| 2025-04-23 | Generador de fichas textuales para Zotero (parte 2)         |
| 2025-05-19 | Meta-prompt generador de prompts                            |
| 2025-05-25 | Generador de parafraseo complejo para Zotero (parte 3)      |
| 2025-06-17 | Prompt para aprender inglés con Duolingo                    |
| 2025-07-01 | Documentos administrativos + Prompt para estudiar cursos    |
| 2025-07-02 | Prompt para NotebookLM                                      |
| 2025-11-25 | Sistema integral de productividad (Super Productivity)      |
| 2025-12-10 | Generador avanzado de plantillas Apaquarto                  |
| 2026-01-16 | Generador de contenido de monografías con APA               |
| 2026-02-15 | Suite completa de presentaciones (guión, estructura, LaTeX) |

---

## Licencia

Este proyecto está bajo la **Licencia MIT**.

```
MIT License

Copyright (c) 2026 Edison Achalma

Se concede permiso, de forma gratuita, a cualquier persona que obtenga una
copia de este software y de los archivos de documentación asociados (el
"Software"), para tratar el Software sin restricción, incluyendo sin limitación
los derechos de usar, copiar, modificar, fusionar, publicar, distribuir,
sublicenciar y/o vender copias del Software...
```

Consulta el archivo [`LICENSE`](./LICENSE) para el texto completo.

---

## Contacto

¿Tienes preguntas, sugerencias o quieres colaborar?

| Canal                  | Dirección                                                                     |
| ---------------------- | ----------------------------------------------------------------------------- |
| 📧 Email institucional | elmer.achalma.09@unsch.edu.pe                                                 |
| 📧 Email personal      | achalmed.18@gmail.com                                                         |
| 🌐 Sitio web           | [achalmaedison.netlify.app](https://achalmaedison.netlify.app)                |
| 🏛️ Institución         | [Universidad Nacional de San Cristóbal de Huamanga](https://www.gob.pe/unsch) |

---

<div align="center">

**Hecho con ❤️ desde Ayacucho, Perú**

_"El conocimiento compartido es el conocimiento multiplicado."_

</div>
