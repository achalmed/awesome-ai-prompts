#prompt
**Instrucciones para Grok:** Utiliza únicamente la información proporcionada por el usuario para desarrollar cada sección, siguiendo las pautas del Capítulo 3 de la guía. Asegúrate de que el proceso sea lógico, secuencial y sustentado en los datos brindados, sin suposiciones externas. Presenta los resultados de manera clara y estructurada, con cuadros, esquemas o diagramas cuando se requiera, y respeta los criterios específicos de cada sección.

# 1. Prompt para Identificacion

## Diagnóstico de la Situación Actual

**Objetivo:** Reflejar la realidad del área de estudio con base en la información proporcionada, utilizando un enfoque sistemático para identificar las condiciones actuales y las brechas que justifican la intervención.

- **1.1 Diagnóstico del Área de Estudio:**
  - **Definición del Área:** Delimita el área de intervención (ubicación geográfica, límites) con base en los datos de ubicación proporcionados. Si hay mapas o referencias espaciales, indícalos.
  - **Componentes del Área:**
    - **Recurso Principal:** Describe las características físicas, estado actual y condiciones del recurso o infraestructura principal identificado en la información (dimensiones, conservación, aspectos legales).
    - **Centro de Soporte:** Analiza la infraestructura o servicios de apoyo mencionados (ubicación, accesibilidad, cobertura de servicios básicos como agua, electricidad).
    - **Accesibilidad:** Detalla las vías de conexión entre el centro de soporte y el recurso principal (tipo, estado, distancia, tiempo de recorrido), según los datos brindados.
    - **Características Físico-Ambientales:** Resume las condiciones geográficas, climáticas o hidrológicas relevantes, incluyendo riesgos naturales si se mencionan.
  - **Sustento:** Cita específicamente los datos o evidencias proporcionados para cada componente.
- **1.2 Diagnóstico de los Involucrados:**
  - **Beneficiarios:** Caracteriza a la población objetivo según la información (número, perfil demográfico, necesidades, percepciones).
  - **Operadores y Prestadores:** Describe a los actores que gestionan o prestan servicios relacionados (capacidad, organización, limitaciones), si se mencionan.
  - **Población Local Vinculada:** Analiza a los grupos indirectamente afectados o beneficiados (ingresos, expectativas), según los datos.
  - **Entidades Involucradas:** Identifica instituciones públicas o privadas señaladas, detallando sus roles y capacidades.
  - **Sustento:** Relaciona cada descripción con evidencias específicas de la información.
- **1.3 Diagnóstico de los Servicios Públicos:**
  - **Infraestructura Existente:** Detalla las instalaciones o servicios actuales (estado, capacidad, funcionamiento), según los datos.
  - **Capacidad de Carga:** Evalúa si la infraestructura soporta la demanda actual, identificando limitaciones con base en estadísticas o percepciones.
  - **Gestión Actual:** Resume las estrategias de operación o promoción existentes, si se mencionan.
  - **Sustento:** Fundamenta cada punto con la información proporcionada.
- **1.4 Análisis de Riesgos:**
  - **Peligros:** Identifica amenazas naturales o sociales señaladas (tipo, frecuencia, intensidad).
  - **Vulnerabilidad:** Evalúa la exposición del área o los involucrados a esos peligros, según los datos.
  - **Resiliencia:** Analiza la capacidad de respuesta o recuperación mencionada.
  - **Sustento:** Vincula cada elemento a evidencias concretas.

---

# 2. Prompt para Análisis de Problema Central, Causas, Efectos y Planteamiento de Proyectos de Inversión Pública

````
"**META:**
Actúa como un consultor experto en formulación de proyectos de inversión pública, especializado en el análisis de problemas centrales, sus causas y efectos, utilizando la metodología del árbol de problemas y el árbol de medios y fines. El análisis debe ser riguroso, basado en un diagnóstico detallado, y enfocado en generar soluciones integrales para problemas de servicios básicos (por ejemplo, agua potable, alcantarillado, electricidad, saneamiento), infraestructura, turismo, etc. La respuesta debe ser clara, estructurada, y cumplir con todas las indicaciones proporcionadas, asegurando que el proyecto sea viable, pertinente y sostenible.

**INSTRUCCIONES GENERALES:**
- Aplica el análisis a un proyecto de inversión pública genérico enfocado en servicios básicos, donde una población enfrenta problemas de acceso limitado o calidad inadecuada del servicio.
- Asume que el diagnóstico proporciona datos completos y específicos sobre:
  - **Población afectada:** Información demográfica, necesidades insatisfechas (ejemplo: porcentaje de hogares sin conexión al servicio, horas de servicio diarias, calidad del agua/electricidad, etc.), y factores sociales, culturales, geográficos o económicos que limitan el acceso.
  - **Unidad Productora (UP):** Desempeño actual, infraestructura existente, capacidad operativa, y limitaciones (ejemplo: redes obsoletas, fallas en mantenimiento, riesgos naturales como deslizamientos).
  - **Otros involucrados:** Entidades públicas, operadores locales, o comunidades que influyen en la ejecución del proyecto.
- Usa datos cuantitativos (indicadores, estadísticas) y cualitativos (encuestas, observaciones) del diagnóstico para sustentar cada sección.
- Asegúrate de que el problema central sea específico, resoluble por un solo proyecto, y que la intervención sea responsabilidad del Estado.
- Evita fraccionar el proyecto; las alternativas deben abordar integralmente el problema central.
- No uses palabras como "falta", "carencia" o "inexistencia" en la redacción del problema central.
- Si no es posible plantear más de una alternativa de solución, justifica claramente por qué se trata de una solución única.
- Considera experiencias de proyectos similares, adaptándolas a las características locales, y menciona cómo se aplican o ajustan.
- Asegúrate de que las acciones propuestas sean técnicamente viables, cumplan con normas técnicas aplicables, y consideren la gestión de riesgos (por ejemplo, reducción de vulnerabilidad frente a desastres).
- Las acciones deben cumplir las siguientes características:
  - Comprenden un conjunto de actividades.
  - Son agregadas, no tan generales como una UP (ejemplo: "construcción de un local escolar") ni tan específicas como tareas detalladas (ejemplo: "excavación de zanjas").
  - Se redactan como: **Verbo + Sustantivo (activo)** (ejemplo: "Construcción de aula", "Adquisición de tomógrafo").
  - No incluyen actividades como movimiento de tierras, excavación de zanjas, o elaboración de expedientes técnicos.
- Las alternativas de solución deben analizarse en el módulo de Formulación, considerando variables de **tamaño**, **localización**, y **tecnología**.

**FORMATO DE RESPUESTA:**

1. **Definición del Problema Central:**
   - Identifica el problema central desde la perspectiva de la demanda insatisfecha (brecha de cobertura o calidad), basado en el diagnóstico.
   - Redacta una oración clara y específica que resuma la situación negativa, asegurando que:
     - Sea específica y delimitada al área de influencia del proyecto.
     - Sea coherente y lógicamente consistente con el diagnóstico.
     - Requiera intervención pública.
     - No se exprese como ausencia de una solución (evita "falta de...").
     - Permita explorar una o múltiples alternativas de solución.
   - Proporciona **indicadores cuantitativos y cualitativos** que evidencien la existencia del problema (ejemplo: porcentaje de hogares sin servicio, horas de servicio diarias, parámetros de calidad incumplidos).
   - Incluye **evidencias concretas** del diagnóstico (reportes, encuestas, análisis de laboratorio, etc.) que sustenten los indicadores.
   - Básicamente, el problema central, en la mayoría de tipologías de proyectos de inversión, se refiere a alguna de las siguientes situaciones: La población no accede al bien o servicio o la población accede de manera inadecuada al bien o servicio; su prestación no cumple con los estándares de calidad

2. **Análisis de Causas:**
   - **Causas Directas (CD):** Identifica entre 2 y 5 causas directas que expliquen el problema central, considerando:
     - **Oferta:** Factores de producción de la UP (ejemplo: infraestructura obsoleta, fallas operativas).
     - **Demanda:** Factores sociales, culturales, geográficos, o económicos que limitan el acceso (ejemplo: resistencia cultural, ubicación remota).
   - **Causas Indirectas (CI):** Identifica al menos 2 causas indirectas por cada causa directa, explicando el origen de las CD.
   - **Evidencias:** Sustenta cada causa con datos del diagnóstico (indicadores cuantitativos, cualitativos, reportes, fotos, etc.).
   - Organiza o liste (lógicamente, jerárquicamente y ordenado) las causas en una **tabla de síntesis** con dos columnas: Causa del problema (CD/CI), Sustento (evidencia).

3. **Análisis de Efectos:**
   - **Efectos Directos (ED):** Identifica un efecto directo por cada causa directa, reflejando el impacto inmediato o futuro (si no se resuelve el problema) en la población afectada.
   - **Efectos Indirectos (EI):** Identifica un efecto indirecto por cada causa indirecta, vinculados a otros mercados o servicios relacionados.
   - **Efecto Final:** Identifica un efecto final que conecte el proyecto con políticas sectoriales, regionales, o locales (ejemplo: disminución de la calidad de vida).
   - **Evidencias:** Sustenta cada efecto con datos del diagnóstico (encuestas, reportes de salud, literatura especializada, testimonios, fotos, etc.).
   - Organiza o liste (lógicamente, jerárquicamente y ordenado) los efectos en una **tabla de síntesis** con dos columnas: Efecto (ED/EI), Sustento (evidencia).
   - Y redacte el Efecto Final

4. **Árbol de Causas y Efectos:**
   - Integra los análisis de causas y efectos en un esquema gráfico que muestre la lógica causal.
   - Usa **código Mermaid** para representar el árbol, con el problema central en el centro, causas abajo, y efectos arriba.
   - Ejemplo:
     ```mermaid
     graph TD
         A[Problema Central] --> B[Efecto Directo 1]
         A --> C[Efecto Directo 2]
         B --> D[Efecto Indirecto 1]
         C --> E[Efecto Indirecto 2]
         D --> F[Efecto Final]
         G[Causa Directa 1] --> A
         H[Causa Directa 2] --> A
         I[Causa Indirecta 1.1] --> G
         J[Causa Indirecta 1.2] --> G
         K[Causa Indirecta 2.1] --> H
````

5. **Planteamiento del Proyecto:**

   - **Objetivo Central:** Expresa el problema central en positivo, definiendo la situación deseada tras la intervención.
     - Evita incluir alternativas de solución o descripciones de la UP.
   - **Medios:** (las causas se transforman en los medios a través de los cuales se logrará solucionar el problema)
     - Convierte las **causas directas** en **medios de primer nivel**.
     - Convierte las **causas indirectas** en **medios fundamentales**.
     - Redacta los medios en positivo, reflejando cambios específicos.
   - **Fines:** (Alcanzar el objetivo del PI generará consecuencias positivas para la población beneficiada por la ejecución del proyecto y, en algunos casos, a terceros (según lo analizado en otros agentes involucrados). A estas consecuencias positivas se llaman los fines del PI.)

     - Convierte los **efectos directos** en **fines directos**.
     - Convierte los **efectos indirectos** en **fines indirectos**.
     - Convierte el **efecto final** en el **fin último**, vinculado a un objetivo de desarrollo.

   - **Árbol de Medios y Fines:**
     - Usa **código Mermaid** para representar el árbol, con el objetivo central en el centro, medios abajo, y fines arriba.
     - Ejemplo:
       ```mermaid
       graph TD
           A[Objetivo Central] --> B[Fin Directo 1]
           A --> C[Fin Directo 2]
           B --> D[Fin Indirecto 1]
           C --> E[Fin Indirecto 2]
           D --> F[Fin Último]
           G[Medio de Primer Nivel 1] --> A
           H[Medio de Primer Nivel 2] --> A
           I[Medio Fundamental 1.1] --> G
           J[Medio Fundamental 1.2] --> G
           K[Medio Fundamental 2.1] --> H
       ```
   - Identifica **indicadores de resultados** para los fines, que permitan verificar el logro del objetivo central durante la fase de funcionamiento.

6. **Alternativas de Solución:**
   - **Identificación de Acciones:**
     - Para cada medio fundamental, identifica al menos **2 acciones** posibles que sean técnicamente viables, cumplan normas técnicas, y consideren la gestión de riesgos.
     - Redacta las acciones como: **Verbo + Sustantivo (activo)** (ejemplo: "Construcción de línea de conducción"). Y enumere las acciones (Acción 1.1.1.)
     - Clasifica las acciones según el tipo de factor de producción (infraestructura, mobiliario, equipo, vehículo, terreno, intangible, infraestructura natural).
   - **Análisis de Interrelación:**
     - Clasifica las acciones como:
       - **Mutuamente excluyentes:** No pueden ejecutarse simultáneamente.
       - **Complementarias:** Deben ejecutarse conjuntamente.
       - **Independientes:** Pueden ejecutarse por separado.
   - Presenta los resultados de identificación de acciones y análisis de interrelación en una **tabla** con 4 columnas: Medio Fundamental, Acciones, Análisis (interrelación con los demás acciones, usas sus numeraciones), Tipo de Factor de Producción.
   - **Planteamiento de Alternativas:**
     - Formula al menos **2 alternativas de solución** integrales, cada una combinando acciones mutuamente excluyentes con acciones complementarias e independientes.
     - Asegúrate de que las alternativas sean:
       - **Técnicamente posibles:** Viables de ejecutar.
       - **Pertinentes:** Adecuadas a la realidad local y normas técnicas.
       - **Comparables:** Ofrecen el mismo nivel de servicio.
     - Presenta las alternativas en una **tabla** con columnas: Alternativa, Lista de Acciones con sus numeraciones.
   - Si solo hay una alternativa viable, justifica claramente por qué no se pueden plantear otras.

**ADVERTENCIAS ESPECÍFICAS:**

- **Problema Central:**
  - No debe ser tan amplio que requiera múltiples proyectos ni tan estrecho que fraccione la solución.
  - Verifica que sea responsabilidad del Estado y no implique soluciones privadas.
- **Objetivo Central:**
  - No incluyas medios, acciones, o descripciones de la UP.
  - Sé preciso y realista, evitando metas inalcanzables.
- **Causas y Efectos:**
  - Cada causa y efecto debe estar respaldado por evidencias concretas del diagnóstico.
  - Evita causas o efectos genéricos o no verificables.
- **Acciones:**
  - No incluyas gastos corrientes como actividades de operación y mantenimiento de una UP, (ejemplo: mantenimiento permanente, eventos culturales, espectáculos, concursos, entre otros).
  - Asegúrate de que las acciones sean integrales y no parciales.
  - Las acciones que se definan en el planteamiento de las alternativas de solución deben representar una solución integral al problema central identificado.
- **Alternativas:**
  - Evita fraccionar el proyecto; cada alternativa debe resolver completamente el problema central.
  - Considera variables de tamaño, localización, y tecnología en el análisis de alternativas.
- **Riesgos:**
  - Incorpora la gestión de riesgos en las acciones (ejemplo: reducir vulnerabilidad a deslizamientos).
  - Adapta las soluciones a las características geográficas y sociales locales.
- Si el usuario proporciona información adicional (por ejemplo, un diagnóstico específico o un tipo de servicio concreto), adapta el análisis a esos datos, manteniendo la estructura y rigor metodológico.
- No supongas ni inventes información sobre el proyecto de inversion; basa tu análisis en el texto proporcionado por el usuario o en la información disponible.
- En los resultados o tablas no resumas informacion.

**CONTEXTO ADICIONAL:**

- El proyecto debe alinearse con políticas sectoriales, regionales, o locales aplicables al servicio básico seleccionado.
- Si el diagnóstico no proporciona datos específicos, asume valores razonables basados en proyectos similares (por ejemplo, 30% de hogares sin acceso al servicio, 6 horas diarias de suministro, agua con parámetros fuera de norma).
- Considera factores de riesgo como desastres naturales, limitaciones presupuestales, o resistencia cultural, y propón acciones para mitigarlos.
- Si se mencionan experiencias de proyectos similares, explica cómo se adaptan al contexto local (ejemplo: un proyecto exitoso en una región urbana puede requerir ajustes para una zona rural)."
- Naturaleza de las acciones por factor de producción

| Naturaleza de las Acciones   | Factor de Producción                                   |
| ---------------------------- | ------------------------------------------------------ |
| Adquisición                  | Equipo, mobiliario, vehículos, terrenos,<br>intangible |
| Construcción                 | Infraestructura                                        |
| Reparación                   | Infraestructura, equipo mayor                          |
| Remodelación                 | Infraestructura                                        |
| Reforzamiento<br>Estructural | Infraestructura                                        |
| Implementación               | Intangible                                             |
| Adecuación                   | Infraestructura, infraestructura natural               |

":

```


---


# 3. Prompt para Formulación

## **Prompt:** Introducción al Capítulo 4

- "Redacta una introducción general para el Capítulo 4 de un proyecto de inversión pública, explicando que este capítulo tiene como propósito recoger, organizar y procesar la información relacionada con las alternativas de solución identificadas en el capítulo anterior. Indica que los principales resultados incluyen la definición del horizonte de evaluación, el análisis de oferta y demanda, el planteamiento técnico, el cronograma de actividades y los costos a precios privados de cada alternativa. Mantén el texto genérico, aplicable a cualquier PIP, destacando que la formulación busca sustentar la viabilidad técnica y económica de las soluciones propuestas."

---

## **Prompt:** 4.1 Horizonte de Evaluación

- "Describe el horizonte de evaluación para un proyecto de inversión pública, conforme a la normatividad del SNIP. Explica que comprende el período de ejecución (período cero) más un período máximo de generación de beneficios (ej. 10 años), el cual debe definirse en el perfil y mantenerse en todas las fases del ciclo del proyecto. Detalla que el período de ejecución puede superar un año y que podrían existir traslapes entre ejecución y generación de beneficios, considerando beneficios parciales de componentes culminados. Indica que cualquier variación en el horizonte requiere justificación técnica. Relaciona este apartado con el plan de implementación, enfatizando la coherencia entre ambos, y propón un esquema gráfico genérico para ilustrar el horizonte (período cero, fase de inversión y fase de beneficios), aplicable a cualquier PIP."

---

## **Prompt:** 4.2 Análisis de la Demanda


- "Elabora una descripción genérica del análisis de la demanda para un proyecto de inversión pública. Explica que este apartado estima y proyecta la población o usuarios que demandarán el servicio o producto del proyecto en las situaciones con y sin proyecto. Divide el análisis en:
  - **4.2.1 Definición del servicio que se proveerá:** Describe que se identificará el servicio o producto principal a ofrecer, junto con su unidad de medida (ej. usuarios/día, servicios/año).
  - **4.2.2 Estimación de la población demandante:** Indica que se definirá la población de referencia (potencial usuaria) y la población demandante efectiva (usuarios reales), considerando características generales de los beneficiarios.
  - **4.2.3 Estimación de la demanda:** Detalla que:
    - _Sin proyecto:_ Se usará data histórica o estimaciones basadas en la situación actual.
    - _Con proyecto:_ Se proyectará la demanda incremental a partir de mejoras o creación del servicio, sustentada con factores endógenos y exógenos (ej. crecimiento poblacional, accesibilidad).
      Propón que las proyecciones se basen en métodos como tasas de crecimiento o encuestas, manteniendo el enfoque flexible para cualquier tipo de proyecto."

---

## **Prompt:** 4.3 Análisis de la Oferta

- "Desarrolla un análisis de la oferta genérico para un proyecto de inversión pública. Explica que este apartado determina la capacidad actual de provisión del servicio y su proyección en el horizonte de evaluación. Divide el análisis en:
  - **4.3.1 Oferta actual:** Describe que se estimará la capacidad existente del servicio (ej. infraestructura, recursos humanos), basada en el diagnóstico del capítulo anterior.
  - **4.3.2 Oferta optimizada:** Indica que se evaluará la posibilidad de mejorar la capacidad actual sin inversión significativa (ej. ajustes en gestión o uso de recursos), explicando que, si el proyecto crea un servicio nuevo, no aplica optimización. Mantén el texto adaptable a cualquier PIP, usando ejemplos genéricos como capacidad de atención o producción, y sustenta que la oferta optimizada depende de factores como manejo eficiente o limitaciones físicas."

---

## **Prompt:** 4.4 Balance Oferta - Demanda

- "Redacta un apartado genérico sobre el balance oferta-demanda para un proyecto de inversión pública. Explica que este análisis compara la demanda efectiva (4.2) con la oferta actual (4.3) para identificar la brecha o déficit del servicio en el horizonte de evaluación. Propón una fórmula general: Brecha = Demanda efectiva - Oferta actual. Indica que la brecha servirá para dimensionar las metas del proyecto y sustentar las intervenciones técnicas. Incluye un esquema gráfico simple (oferta, demanda, brecha) y mantén el texto aplicable a cualquier tipo de servicio o sector, sin referencias específicas."

---

## **Prompt:** 4.5 Planteamiento Técnico de las Alternativas

- "Describe el planteamiento técnico genérico de las alternativas de solución para un proyecto de inversión pública, con el objetivo de maximizar beneficios al menor costo social. Divide el análisis en:
  - **4.5.1 Localización:** Explica que se seleccionará la ubicación óptima considerando accesibilidad, disponibilidad de terrenos (públicos o privados con arreglos institucionales), servicios básicos (agua, energía), compatibilidad con planes de ordenamiento territorial, condiciones geológicas y restricciones legales o ambientales.
  - **4.5.2 Tamaño:** Indica que se definirá en función de la brecha (4.4), capacidad de recepción, dimensiones del terreno, normativa técnica (ej. Reglamento Nacional de Edificaciones), recursos financieros y riesgos ambientales.
  - **4.5.3 Tecnología:** Detalla que se elegirán tecnologías adecuadas según clima, materiales disponibles, integración con el entorno, mantenimiento y financiamiento.
  - **4.5.4 Momento óptimo:** Describe que se identificará el mejor momento de ejecución considerando temporadas de baja actividad, condiciones climáticas, eventos relevantes y disponibilidad de recursos. Mantén el enfoque genérico, aplicable a cualquier PIP, con ejemplos amplios (ej. infraestructura, equipamiento)."

---

## **Prompt:** 4.6 Cronograma de Actividades


- "Elabora una guía genérica para el cronograma de actividades de un proyecto de inversión pública. Explica que este apartado identifica todas las actividades necesarias en la fase de inversión y post-inversión para cada alternativa, estimando duración, secuencia e interdependencias. Divide en:
  - **4.6.1 Fase de inversión:** Detalla etapas como diseño/expediente técnico (términos de referencia, contratación, elaboración, aprobación) y ejecución (contratación, obra, supervisión, recepción), considerando normativas de contratación.
  - **4.6.2 Fase de operación y mantenimiento:** Indica que se describirán actividades para poner en marcha y sostener el proyecto (ej. operación de infraestructura, capacitación). Propón un formato de cuadro cronológico (Año 0 a Año N) y enfatiza la coherencia con el horizonte de evaluación (4.1) y el planteamiento técnico (4.5), manteniendo flexibilidad para cualquier tipo de proyecto."

---

# 5. Prompt para Costos a Precios Privados

## **Prompt:**

- "Redacta un apartado genérico sobre los costos a precios privados para un proyecto de inversión pública. Explica que se estimarán los costos en dos momentos: período de inversión (construcción) y período de operación (funcionamiento), a precios de mercado. Divide en:

### **4.7.1 Costos de Inversión a Precios de Mercado**

Genere una **tabla** de los costos de inversión a precios de mercado para las **Alternativas de Solución 1 y 2**, desglosando los siguientes componentes:

- **Intangibles:** estudios, capacitaciones, licencias y otros costos administrativos.
- **Activos fijos:** infraestructura y equipamiento.
- **Otros gastos:** supervisión, mitigación ambiental, entre otros.

#### **Estructura de la Tabla**

Cada alternativa debe presentarse en la siguiente estructura de columnas:
**Alternativa de Solución | Und. | Cant. | C.U. | M.O.C. | M.O.N.C. | Materiales | Equipo y Herramientas | Costo Directo | Gastos Generales (10%) | Utilidad (10%) | Parcial | Impuestos (IR=10% + IGV=18%) | Total a Precios Privados (S/.) | Clasificación**

📌 **La columna "Clasificación"** debe indicar a qué categoría pertenece cada subacción , eligiendo entre:

1. **Estudios y expedientes técnicos**
2. **Inversión fija (Infraestructura)**
3. **Equipamiento**
4. **Inversión intangible**
5. **Supervisión**
6. **Mitigación ambiental**

#### **Organización de las Filas**

La estructura jerárquica de las filas debe seguir esta lógica

1. **Medios de Primer Nivel (MPN)**
   - **Medios Fundamentales (MF)**
     - **Acciones específicas** (cada una debe desglosarse en al menos dos subacciones).
       📌 **Condiciones adicionales:**

- **Cada costo debe estar sustentado con metrados y costos unitarios** según referencias de Perú para garantizar precisión.
- **Los MPN, MF y acciones deben ser estrictamente los asignados a cada alternativa.**

  - **4.7.2 Costos de operación y mantenimiento:**

Genere tres conjuntos de tablas para estimar los costos Costos de operación y mantenimiento en tres escenarios:

1. **Situación sin proyecto**
2. **Situación con proyecto – Alternativa 1**
3. **Situación con proyecto – Alternativa 2**
   Cada conjunto de tablas debe incluir lo siguiente:
4. **Tabla de Costos de Personal**
   - Columnas:
      | **Personal** | **Unidad** | **Cantidad** | **Sueldo Básico Mensual (S/.)** | **Aportaciones (9%)** | **Monto a Precios Privados (S/.)** |
5. **Tabla de Insumos, Materiales y Herramientas**
   - Columnas:
      | **Insumos, Materiales y Herramientas** | **Unidad** | **Cantidad** | **Parcial (S/.)** | **Monto a Precios Privados (S/.)** |
6. **Tabla de Costos de Mantenimiento**
   - Columnas:
      | **Costos de Mantenimiento** | **Unidad** | **Cantidad** | **Parcial (S/.)** | **Monto a Precios Privados (S/.)** |

Los valores deben basarse en promedios actuales o proyectados de Perú y debe ser estrictamente relacionado al proyecto.

- **4.7.3 Flujo de costos incrementales:** Indica que se calculará como la diferencia entre costos con y sin proyecto (Inversión + O&M con proyecto - O&M sin proyecto), compatible con el cronograma (4.6). Propón un cuadro de flujos anuales y mantén el texto genérico, aplicable a cualquier PIP."

---

Notas Finales

- Estos prompts son completamente genéricos, alineados con la estructura del Capítulo 4 de la guía y adaptables a cualquier proyecto de inversión pública, sin referencias específicas al caso de Sillustani o al sector turismo, salvo donde la guía lo menciona como ejemplo.
- Si deseas que ejecute alguno de estos prompts para generar el texto completo de una subsección, por favor indícalos. Alternativamente, puedo continuar con prompts para el resto del documento o ajustar algo según tus necesidades.

¿Cómo te gustaría proceder? ¿Ejecutamos algún prompt o seguimos con otra sección?

---

Prompts Generales para el Capítulo 5: Evaluación

# 5. Prompt para Evaluación Social

**Objetivo:** Evaluar las alternativas de solución desde los puntos de vista privado y social, comparando beneficios y costos sociales.

## **Prompt:** 5.1.1 Metodología de Evaluación Aplicada:**

- "Describe la metodología de evaluación social para un proyecto de inversión pública, utilizando el enfoque Costo/Beneficio. Explica que se estimarán los flujos incrementales de beneficios sociales (mejoras en el bienestar de la población) y costos sociales (inversión, operación y mantenimiento) para cada alternativa identificada en el capítulo anterior. Indica que se calcularán el Valor Actual Neto Social (VANS) y la Tasa Interna de Retorno Social (TIRS) con una tasa de descuento definida por el Anexo SNIP 10 (por ejemplo, 10%). Detalla que la metodología compara la situación sin y con proyecto, y que los indicadores reflejarán la rentabilidad social. Mantén el texto genérico, aplicable a cualquier PIP, sin mencionar sectores específicos."

## **Prompt:** 5.1.2 Beneficios Sociales:

- "Identifica y describe cómo se cuantificarán los beneficios sociales de las alternativas de un proyecto de inversión pública. Explica que los beneficios se derivan de los fines establecidos en el capítulo 3 (por ejemplo, reducción de riesgos, mejora de servicios), y que se estimarán mediante:
  - Incremento del bienestar (valoración de daños evitados o tiempo ahorrado).
  - Mejoras indirectas (salud, calidad de vida).
    Propón una fórmula general: ∆BS = (Beneficio incremental por usuario × Nº de beneficiarios × Factor de corrección). Indica que los datos se obtendrán de encuestas o estudios de campo comparando la situación sin y con proyecto. Mantén el enfoque genérico, sin referirte a un tipo de proyecto específico, y sustenta con la lógica de la guía."

## **Prompt:** 5.1.3 Costos Sociales

- "Explica cómo se estimarán los costos sociales de las alternativas de un proyecto de inversión pública. Detalla que se partirá de los costos privados (inversión, operación y mantenimiento) y se aplicarán factores de corrección por distorsiones de mercado (según Anexo SNIP 10), desagregándolos en:
  1. Mano de obra calificada (FC=0.91).
  2. Mano de obra no calificada (FC variable por zona).
  3. Bienes transables (FC=0.85).
  4. Servicios no transables (FC=0.91).
     Describe que se construirán flujos incrementales anuales comparando la situación sin y con proyecto, y presenta un ejemplo general de cálculo para el Año 0 (inversión) y Año 1 (O&M). Mantén el texto aplicable a cualquier PIP, sin especificar rubros concretos."

## **Prompt:** 5.1.4 Indicadores de Rentabilidad Social

- "Describe cómo se calcularán los indicadores de rentabilidad social (VANS y TIRS) para las alternativas de un proyecto de inversión pública. Indica que se usarán los flujos de beneficios sociales (5.1.2) y costos sociales (5.1.3) sobre un horizonte definido (ej. 10 años), aplicando una tasa de descuento del Anexo SNIP 10 (ej. 10%). Presenta fórmulas:
  - VANS = ∑ (Flujo neto social / (1+r)^t).
  - TIRS como la tasa que hace VANS = 0.
    Explica que se incluirán costos y beneficios asociados a reducción de riesgos y manejo ambiental. Propón una tabla genérica de flujos netos (Beneficios - Costos) y sustenta que estos indicadores evalúan la viabilidad social del proyecto, manteniendo el enfoque general."

---

5.2 Análisis de Sensibilidad

## **Prompt:**

- "Elabora un análisis de sensibilidad genérico para un proyecto de inversión pública. Identifica variables críticas que afecten la rentabilidad social, como:
  - Costos de inversión.
  - Costos de operación y mantenimiento.
  - Beneficios sociales estimados.
  - Tasa de crecimiento de beneficiarios.
    Explica que se simularán variaciones (ej. ±20%) en cada variable y se evaluará su impacto en VANS y TIRS. Indica que se determinará el umbral en que el proyecto deja de ser rentable (VANS < 0 o TIRS < tasa de descuento). Sostén que este análisis mejora la toma de decisiones, usando un enfoque aplicable a cualquier PIP, sin referencias específicas."

---

## **Prompt:** 5.3 Análisis de Sostenibilidad


- "Desarrolla un análisis de sostenibilidad genérico para un proyecto de inversión pública, asegurando la generación continua de beneficios durante su horizonte de evaluación. Incluye:
  - **Arreglos institucionales:** Describe roles de las entidades responsables (ej. Unidad Ejecutora, operadores) en operación y mantenimiento, sustentados por convenios o compromisos.
  - **Capacidad de gestión:** Evalúa la experiencia institucional, recursos humanos y financieros de las entidades involucradas.
  - **Sostenibilidad financiera:** Propón estimar ingresos (tarifas, transferencias) para cubrir costos de O&M, con una fórmula general: Tarifa = VAC / Nº de beneficiarios, donde VAC = ∑ (Costos / (1+r)^t).
  - **Participación de beneficiarios:** Detalla su rol en identificación, ejecución y operación (ej. pago de tarifas).
  - **Riesgos:** Considera eventos externos (desastres) y medidas de mitigación. Mantén el texto genérico, aplicable a cualquier proyecto, sin especificar sectores."

---

## **Prompt:** 5.4 Análisis de Impacto Ambiental


- "Describe un análisis de impacto ambiental genérico para un proyecto de inversión pública. Identifica impactos potenciales en:
  - **Ejecución:** Ruido, residuos, alteración del entorno.
  - **Operación:** Cambios en el ecosistema, manejo de desechos.
    Propón medidas de mitigación (control de residuos, monitoreo). Explica que se verificará si el proyecto requiere Certificación Ambiental según el SEIA (Anexo II), o si solo debe cumplir normas ambientales generales (residuos, suelos, patrimonio). Mantén el enfoque general, aplicable a cualquier PIP, y sustenta con la lógica de la guía."

---

## **Prompt:** 5.5 Selección de Alternativas


- "Explica cómo se seleccionará la mejor alternativa de un proyecto de inversión pública, comparando:
  - Rentabilidad social (VANS y TIRS de 5.1.4).
  - Sensibilidad (variables críticas de 5.2).
  - Sostenibilidad (institucional y financiera de 5.3).
  - Impacto ambiental (menor afectación de 5.4).
    Indica que se describirán aspectos de viabilidad técnica, ambiental, institucional y sociocultural, considerando costos y beneficios de reducción de riesgos. Mantén el texto genérico, aplicable a cualquier PIP, sin referirte a casos específicos."

---

5.6 Organización y Gestión

## **Prompt:** 5.6.1 Organización durante la Etapa de Inversión

- "Define la organización genérica para la etapa de inversión de un proyecto de inversión pública. Indica que la Unidad Ejecutora (UE) designará un órgano técnico responsable (ej. Oficina de Infraestructura), detallando:
  - Estructura: Roles y tamaño organizativo.
  - Capacidad: Experiencia, recursos humanos y logísticos.
  - Modalidad: Justifica contrata o administración directa con criterios (costo, capacidad).
    Explica la interacción con otras instituciones (permisos, financiamiento). Mantén el enfoque general, sin especificar proyectos."

## **Prompt:** 5.6.2 Organización de la Operación y Mantenimiento

- "Describe la organización genérica para la operación y mantenimiento de un proyecto de inversión pública. Identifica la unidad administrativa responsable (pública o privada), incluyendo:
  - Estructura: Funciones y roles (ej. mantenimiento, recaudación).
  - Relaciones: Dependencia con otras entidades (financiamiento, supervisión).
  - Capacidad: Experiencia y recursos para sostenibilidad.
    Propón un organigrama textual y sustenta con un enfoque aplicable a cualquier PIP."

---

5.7 Plan de Implementación

## **Prompt:**

- "Elabora un plan de implementación genérico para un proyecto de inversión pública, basado en las actividades del capítulo 4. Detalla:
  - **Actividades:** Fases de ejecución (ej. estudios, obras).
  - **Metas:** Resultados cuantificables (ej. infraestructura construida).
  - **Responsables:** Entidades o equipos técnicos.
  - **Recursos:** Personal y equipos necesarios.
    Presenta un cuadro con cronograma anual (Año 0 a Año 1), manteniendo el texto flexible para cualquier PIP."

---

## **Prompt:** 5.8 Financiamiento

- "Define el financiamiento genérico de un proyecto de inversión pública. Incluye:
  - **Entidades:** Fuentes de fondos (gobierno, privados, beneficiarios) y porcentajes.
  - **Fuentes:** Tipos de recursos (ordinarios, donaciones, préstamos).
  - **Sustento:** Explica cómo se garantizará la disponibilidad presupuestaria (convenios, ingresos).
    Mantén el enfoque general, aplicable a cualquier PIP, sin especificar montos o instituciones concretas."

---

## **Prompt:** 5.9 Matriz de Marco Lógico (MML)


- "Construye una Matriz de Marco Lógico genérica para un proyecto de inversión pública. Incluye:
  - **Fin:** Objetivo superior (ej. mejora del bienestar).
  - **Propósito:** Resultado central (ej. servicio operativo).
  - **Componentes:** Elementos clave (ej. infraestructura).
  - **Actividades:** Acciones específicas (ej. construcción).
  - **Indicadores:** Metas cuantificables.
  - **Fuentes:** Informes, encuestas.
  - **Supuestos:** Factores externos (ej. estabilidad institucional).
    Presenta un cuadro flexible, basado en los objetivos del capítulo 3, aplicable a cualquier PIP."
```
