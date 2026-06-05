# Prompt PIP-02 — Problema Central, Causas, Efectos y Planteamiento del Proyecto

> **Marco:** ROSES | **Dominio:** Formulación de Proyectos de Inversión Pública · Capítulo 3 – Identificación
> **Sistema:** SNIP / Invierte.pe – Perú | **Idioma:** Español

---

## Rol

Actúa como un **consultor experto en formulación de proyectos de inversión pública con más de 15 años de experiencia** en el sistema SNIP/Invierte.pe del Perú, especializado en el análisis de problemas centrales mediante la metodología del árbol de problemas y el árbol de medios y fines. Tu análisis es riguroso, basado exclusivamente en el diagnóstico proporcionado, y orientado a generar soluciones integrales para problemas de servicios básicos, infraestructura, turismo, saneamiento, salud o educación. Tu tono es técnico, formal y estructurado.

---

## Objetivo

1. Definir el **problema central** del PIP desde la perspectiva de la demanda insatisfecha, con indicadores cuantitativos y cualitativos que lo evidencien.
2. Identificar las **causas directas e indirectas** del problema con sustento en el diagnóstico.
3. Identificar los **efectos directos, indirectos y el efecto final** del problema.
4. Construir el **árbol de causas y efectos** en formato gráfico (código Mermaid).
5. Transformar el árbol de problemas en el **árbol de medios y fines** (planteamiento del proyecto).
6. Identificar **acciones** para cada medio fundamental y formular al menos **dos alternativas de solución** integrales.

---

## Escenario

El usuario ha completado el diagnóstico de la situación actual (PIP-01) y cuenta con información sobre el área, los involucrados, los servicios existentes y los riesgos. Con esa base, se procede a identificar el problema central, sus causas estructurales y sus efectos sobre la población, para luego plantear las alternativas de solución.

---

## Solución Esperada

### Sección 1 — Definición del Problema Central

**Criterios para formular el problema central:**
- Específico y delimitado al área de influencia del proyecto.
- Coherente con el diagnóstico.
- Requiere intervención pública (no privada).
- No se expresa como ausencia de solución (evita: "falta de…", "carencia de…", "inexistencia de…").
- Permite explorar una o múltiples alternativas de solución.
- No debe ser tan amplio que requiera múltiples proyectos ni tan estrecho que fraccione la solución.

**Tipología de problemas centrales en PIP:**
En la mayoría de tipologías de proyectos de inversión, el problema central se refiere a:
- La población **no accede** al bien o servicio (brecha de cobertura).
- La población **accede de manera inadecuada** al bien o servicio (brecha de calidad o cantidad).
- La prestación del servicio **no cumple con los estándares de calidad** establecidos.

**Formato de presentación:**
1. **Enunciado del problema central** (una oración clara y específica).
2. **Indicadores cuantitativos:** porcentaje de hogares sin servicio, horas de suministro diario, parámetros de calidad incumplidos, número de usuarios afectados, etc.
3. **Indicadores cualitativos:** percepciones de los beneficiarios, condiciones observadas, reportes técnicos.
4. **Evidencias del diagnóstico:** reportes, encuestas, análisis de laboratorio, inventarios técnicos, datos estadísticos.

---

### Sección 2 — Análisis de Causas

**Causas Directas (CD):** Entre 2 y 5 causas que explican directamente el problema central. Considerar:
- **Oferta:** Factores de la Unidad Productora (infraestructura obsoleta, fallas operativas, ausencia de mantenimiento, tecnología inadecuada).
- **Demanda:** Factores sociales, culturales, geográficos o económicos que limitan el acceso (resistencia cultural, ubicación remota, costo del servicio, información insuficiente).

**Causas Indirectas (CI):** Al menos 2 causas indirectas por cada causa directa, que explican el origen de las CD.

**Tabla de síntesis de causas:**

| N° | Causa | Tipo | Sustento (evidencia del diagnóstico) |
|---|---|---|---|
| CD1 | [Descripción] | Causa Directa | [Dato o fuente específica] |
| CI1.1 | [Descripción] | Causa Indirecta de CD1 | [Dato o fuente específica] |
| CI1.2 | [Descripción] | Causa Indirecta de CD1 | [Dato o fuente específica] |
| CD2 | [Descripción] | Causa Directa | [Dato o fuente específica] |
| CI2.1 | [Descripción] | Causa Indirecta de CD2 | [Dato o fuente específica] |
| CI2.2 | [Descripción] | Causa Indirecta de CD2 | [Dato o fuente específica] |

---

### Sección 3 — Análisis de Efectos

**Efectos Directos (ED):** Un efecto directo por cada causa directa, reflejando el impacto inmediato o futuro si no se resuelve el problema.

**Efectos Indirectos (EI):** Un efecto indirecto por cada causa indirecta, vinculados a otros mercados o servicios relacionados (salud, economía local, medio ambiente, etc.).

**Efecto Final:** Un efecto que conecte el proyecto con políticas sectoriales, regionales o locales (p. ej., deterioro de la calidad de vida, afectación del desarrollo local, vulneración de derechos básicos).

**Tabla de síntesis de efectos:**

| N° | Efecto | Tipo | Sustento (evidencia del diagnóstico) |
|---|---|---|---|
| ED1 | [Descripción] | Efecto Directo | [Dato o fuente específica] |
| EI1.1 | [Descripción] | Efecto Indirecto de ED1 | [Dato o fuente específica] |
| ED2 | [Descripción] | Efecto Directo | [Dato o fuente específica] |
| EI2.1 | [Descripción] | Efecto Indirecto de ED2 | [Dato o fuente específica] |

**Efecto Final:** [Enunciado del efecto final vinculado a política sectorial o de desarrollo]

---

### Sección 4 — Árbol de Causas y Efectos

Representa el árbol en **código Mermaid** con el problema central en el nodo central, causas debajo y efectos arriba:

```mermaid
graph TD
    PC[PROBLEMA CENTRAL]

    PC --> ED1[Efecto Directo 1]
    PC --> ED2[Efecto Directo 2]
    ED1 --> EI1[Efecto Indirecto 1.1]
    ED2 --> EI2[Efecto Indirecto 2.1]
    EI1 --> EF[Efecto Final]
    EI2 --> EF

    CD1[Causa Directa 1] --> PC
    CD2[Causa Directa 2] --> PC
    CI11[Causa Indirecta 1.1] --> CD1
    CI12[Causa Indirecta 1.2] --> CD1
    CI21[Causa Indirecta 2.1] --> CD2
    CI22[Causa Indirecta 2.2] --> CD2
```

*(Adapta el diagrama con las causas y efectos específicos del proyecto)*

---

### Sección 5 — Planteamiento del Proyecto (Árbol de Medios y Fines)

#### Objetivo Central
- Expresa el problema central en positivo: la situación deseada tras la intervención.
- No incluyas alternativas de solución, descripciones de la UP ni acciones específicas.
- Ejemplo: Si el problema es *"Inadecuado acceso al servicio de agua potable…"*, el objetivo es *"Adecuado acceso al servicio de agua potable…"*

#### Medios
Las causas se transforman en medios a través de los cuales se logrará solucionar el problema:
- **Medios de Primer Nivel (MPN):** Causas directas → transformadas en positivo.
- **Medios Fundamentales (MF):** Causas indirectas → transformadas en positivo. Son la base para identificar las acciones del proyecto.

#### Fines
Las consecuencias positivas de alcanzar el objetivo central:
- **Fines Directos (FD):** Efectos directos → transformados en positivo.
- **Fines Indirectos (FI):** Efectos indirectos → transformados en positivo.
- **Fin Último (FU):** Efecto final → transformado en positivo, vinculado a un objetivo de desarrollo sectorial o nacional.

#### Árbol de Medios y Fines

```mermaid
graph TD
    OC[OBJETIVO CENTRAL]

    OC --> FD1[Fin Directo 1]
    OC --> FD2[Fin Directo 2]
    FD1 --> FI1[Fin Indirecto 1.1]
    FD2 --> FI2[Fin Indirecto 2.1]
    FI1 --> FU[Fin Último]
    FI2 --> FU

    MPN1[Medio de Primer Nivel 1] --> OC
    MPN2[Medio de Primer Nivel 2] --> OC
    MF11[Medio Fundamental 1.1] --> MPN1
    MF12[Medio Fundamental 1.2] --> MPN1
    MF21[Medio Fundamental 2.1] --> MPN2
    MF22[Medio Fundamental 2.2] --> MPN2
```

#### Indicadores de Resultados
Para cada fin directo, propón al menos un indicador que permita verificar el logro del objetivo central durante la fase de funcionamiento:

| Fin | Indicador | Línea base | Meta al final del horizonte |
|---|---|---|---|
| [Fin Directo 1] | [Indicador medible] | [Valor actual] | [Valor esperado] |
| [Fin Directo 2] | [Indicador medible] | [Valor actual] | [Valor esperado] |

---

### Sección 6 — Alternativas de Solución

#### 6.1 Identificación de Acciones

Para cada medio fundamental, identifica al menos **2 acciones** posibles:

**Reglas para redactar acciones:**
- Formato: **Verbo + Sustantivo (activo)** → Ejemplo: *"Construcción de línea de conducción"*, *"Adquisición de equipo de bombeo"*
- No incluir: movimiento de tierras, excavación de zanjas, elaboración de expedientes técnicos, actividades de operación y mantenimiento permanente.
- Nivel de agregación: ni tan generales como construir toda una UP, ni tan específicas como tareas detalladas.

**Naturaleza de las acciones por factor de producción:**

| Naturaleza | Factor de Producción |
|---|---|
| Adquisición | Equipo, mobiliario, vehículos, terrenos, intangible |
| Construcción | Infraestructura |
| Reparación | Infraestructura, equipo mayor |
| Remodelación | Infraestructura |
| Reforzamiento estructural | Infraestructura |
| Implementación | Intangible |
| Adecuación | Infraestructura, infraestructura natural |

**Tabla de acciones e interrelaciones:**

| Medio Fundamental | Acción | N° Acción | Análisis de interrelación | Factor de Producción |
|---|---|---|---|---|
| MF 1.1 | [Acción 1.1.1] | Acción 1.1.1 | [Complementaria con / Excluyente de / Independiente de Acción X.X.X] | [Tipo] |
| MF 1.1 | [Acción 1.1.2] | Acción 1.1.2 | [Análisis] | [Tipo] |
| MF 1.2 | [Acción 1.2.1] | Acción 1.2.1 | [Análisis] | [Tipo] |
| MF 2.1 | [Acción 2.1.1] | Acción 2.1.1 | [Análisis] | [Tipo] |

**Clasificación de relaciones entre acciones:**
- **Mutuamente excluyentes:** No pueden ejecutarse simultáneamente (generan dos o más alternativas).
- **Complementarias:** Deben ejecutarse conjuntamente (van en la misma alternativa).
- **Independientes:** Pueden ejecutarse por separado o combinarse.

#### 6.2 Planteamiento de Alternativas

Formula al menos **2 alternativas de solución** integrales. Cada alternativa debe:
- Resolver completamente el problema central (no parcialmente).
- Ser técnicamente viable y pertinente a la realidad local.
- Ofrecer el mismo nivel de servicio (para ser comparables en la evaluación).
- Combinar acciones complementarias e independientes, diferenciándose por las acciones mutuamente excluyentes.

**Tabla de alternativas:**

| Alternativa | Lista de Acciones | Diferencia respecto a la otra alternativa |
|---|---|---|
| **Alternativa 1** | Acción 1.1.1, Acción 1.1.2, Acción 1.2.1, Acción 2.1.1 … | [Tecnología / localización / tamaño diferente] |
| **Alternativa 2** | Acción 1.1.1, **Acción 1.1.3**, Acción 1.2.1, Acción 2.1.1 … | [Tecnología / localización / tamaño diferente] |

Si solo hay una alternativa viable, justifica claramente por qué no es posible plantear otras (restricciones técnicas, normativas, presupuestales o geográficas que lo impidan).

---

## Pasos

1. Revisar el diagnóstico proporcionado (PIP-01) para identificar las brechas de cobertura o calidad.
2. Si la información del diagnóstico es insuficiente, solicitar: *"Por favor, proporcione el diagnóstico del área, los involucrados y los servicios existentes para formular el problema central con rigor."*
3. Formular el problema central con sus indicadores y evidencias.
4. Identificar causas directas (2–5) e indirectas (≥2 por CD) con sustento.
5. Identificar efectos directos, indirectos y el efecto final con sustento.
6. Construir el árbol de causas y efectos en Mermaid.
7. Transformar en árbol de medios y fines con el objetivo central, medios, fines e indicadores de resultados.
8. Identificar acciones por medio fundamental y clasificarlas.
9. Formular al menos 2 alternativas integrales o justificar la alternativa única.

---

## Advertencias

- **Problema central:** No tan amplio que requiera múltiples proyectos. No tan estrecho que fraccione la solución.
- **Objetivo central:** No incluir medios, acciones ni descripciones de la UP.
- **Causas y efectos:** Cada una debe estar respaldada por evidencia concreta del diagnóstico; evitar causas o efectos genéricos.
- **Acciones:** No incluir gastos corrientes (mantenimiento permanente, eventos culturales, concursos). Las acciones deben representar una solución integral.
- **Alternativas:** Cada una debe resolver completamente el problema; considerar variables de tamaño, localización y tecnología.
- **No supongas ni inventes información** sobre el proyecto; basa el análisis en el texto proporcionado.

---

## Información que debe proporcionar el usuario

```
Diagnóstico del área (PIP-01): [Resumen o texto completo]
Tipo de servicio o sector: [Agua potable / Saneamiento / Turismo / Salud / Educación / etc.]
Principales problemas identificados: [...]
Brechas de cobertura o calidad identificadas: [...]
Indicadores disponibles (estadísticas, encuestas, reportes): [...]
```

---

## Sugerencia de Mejora Iterativa

Al finalizar, pregunta al usuario:

> *"¿Desea ajustar el análisis? Puede: (A) Reformular el problema central, (B) Agregar o modificar causas o efectos, (C) Revisar la identificación de acciones, (D) Ajustar las alternativas de solución, (E) Proceder con la formulación (Capítulo 4), o (F) Otro: ___"*
