#prompt #metodologia_investigacion #cuantitativo 

# Prompt 15 — Procesamiento de Datos y Modelos Estadísticos

> **Marco:** SPAR | **Dominio:** Metodología de la investigación científica cuantitativa · Análisis estadístico
> **Nivel:** Pregrado avanzado – Posgrado | **Idioma:** Español

---

## Rol

Actúa como un **metodólogo experto en análisis estadístico cuantitativo y procesamiento de datos para investigación científica**, con más de 15 años de experiencia en la selección y aplicación de herramientas estadísticas para tesis, artículos y anteproyectos académicos. Dominas el uso de software estadístico (SPSS, R, Stata, Excel) y el diseño de flujos de procesamiento coherentes con el tipo de investigación, las variables y las hipótesis del estudio.

---

## Escenario

El usuario ha completado el diseño metodológico y la definición de técnicas de recolección. Ahora necesita especificar **cómo transformará los datos brutos en resultados organizados e interpretables**, garantizando que el procesamiento sea sistemático, reproducible y coherente con los objetivos, las hipótesis y las variables del estudio.

---

## Problema

En muchas tesis y anteproyectos, la sección de procesamiento de datos se limita a mencionar el software sin justificar las herramientas estadísticas seleccionadas ni describir el flujo de trabajo. Esto genera inconsistencias entre las preguntas de investigación, los objetivos y los resultados reportados.

---

## Acciones

Generar la sección **"Procesamiento de Datos y Modelos Estadísticos"** con los siguientes apartados:

### 1. Importancia del procesamiento de datos
Párrafo que explique cómo el procesamiento sistemático:
- Transforma datos brutos en información organizada y analizable.
- Garantiza que los resultados respondan directamente a las preguntas de investigación y objetivos.
- Permite la verificación o rechazo de hipótesis con rigor estadístico.
- Asegura la reproducibilidad del análisis.

### 2. Pasos del procesamiento de datos
Describe el flujo de trabajo en orden secuencial:

1. **Recopilación y organización de datos brutos:** Obtención de los datos del trabajo de campo (cuestionarios, registros, bases de datos secundarias).
2. **Depuración y limpieza:** Identificación y tratamiento de valores atípicos (outliers), datos faltantes (missing values) y errores de registro.
3. **Codificación:** Asignación de valores numéricos a variables categóricas o de escala (p. ej., Likert 1–5, variables dummy 0/1).
4. **Estructuración de la base de datos:** Organización en matriz de datos (filas = unidades de análisis; columnas = variables e indicadores) lista para el análisis estadístico.
5. **Selección y aplicación de herramientas estadísticas:** Según los objetivos e hipótesis.
6. **Generación de resultados:** Tablas, gráficos, estadísticos descriptivos e inferenciales.
7. **Verificación de supuestos:** Antes de aplicar técnicas inferenciales (normalidad, homocedasticidad, linealidad, independencia de errores).

### 3. Herramientas estadísticas seleccionadas
Selecciona y describe al menos **tres herramientas** según el nivel de investigación y las variables:

**Estadística descriptiva** *(siempre presente)*

| Herramienta | Qué mide/analiza | Cuándo usarla |
|---|---|---|
| Distribución de frecuencias | Conteo y proporción de cada valor o categoría | Variables nominales y ordinales |
| Medidas de tendencia central (media, mediana, moda) | Valor representativo del conjunto | Variables continuas y ordinales |
| Medidas de dispersión (varianza, desviación estándar, rango, CV) | Variabilidad de los datos | Variables continuas |
| Tablas cruzadas (contingencia) | Relación entre dos variables categóricas | Nominal × Nominal |

**Estadística inferencial** *(según hipótesis y nivel de investigación)*

| Herramienta | Propósito | Nivel de investigación | Requisitos |
|---|---|---|---|
| Prueba t de Student | Comparar medias (2 grupos) | Correlacional / Explicativo | Normalidad, escala de razón/intervalo |
| ANOVA (análisis de varianza) | Comparar medias (3+ grupos) | Correlacional / Explicativo | Normalidad, homogeneidad de varianzas |
| Chi-cuadrado (χ²) | Asociación entre variables categóricas | Correlacional | Variables nominales u ordinales |
| Coeficiente de correlación de Pearson (r) | Dirección e intensidad de correlación lineal | Correlacional | Variables continuas, normalidad |
| Coeficiente de correlación de Spearman (ρ) | Correlación entre variables ordinales | Correlacional | Variables ordinales o no normales |
| Regresión lineal simple | Efecto de X sobre Y (una variable) | Explicativo | Linealidad, normalidad de residuos |
| Regresión lineal múltiple | Efecto conjunto de varias X sobre Y | Explicativo | Multicolinealidad, homocedasticidad |
| Regresión logística | Predicción de variable dicotómica | Explicativo / Predictivo | Variable dependiente binaria |
| Análisis de datos de panel | Efectos individuales + tiempo | Explicativo / Predictivo | Datos longitudinales estructurados |

Para cada herramienta seleccionada, describe:
- Qué mide o analiza en el contexto del estudio.
- Cómo se aplica a los datos recolectados.
- Qué supuestos estadísticos debe verificarse antes de aplicarla.
- Cómo se interpretarán los resultados (p-valor, coeficiente, R², etc.).

### 4. Verificación de supuestos estadísticos
Antes de aplicar técnicas inferenciales, describe cómo se verificarán los supuestos clave:

| Supuesto | Prueba de verificación | Software |
|---|---|---|
| Normalidad | Prueba de Shapiro-Wilk (n<50) / Kolmogorov-Smirnov (n≥50) / histogramas | SPSS, R |
| Homocedasticidad | Prueba de Levene; gráficos de residuos | SPSS, R |
| Linealidad | Gráficos de dispersión; correlación parcial | Excel, R |
| Independencia de errores | Prueba de Durbin-Watson (series temporales) | SPSS, Stata |
| Ausencia de multicolinealidad | Factor de Inflación de la Varianza (VIF) | SPSS, R |

### 5. Software estadístico
Propón el programa más adecuado para el estudio y justifica la elección:

| Software | Fortalezas | Mejor para |
|---|---|---|
| **SPSS** | Interfaz visual amigable, amplia difusión académica | Encuestas, análisis descriptivo e inferencial estándar |
| **R** | Gratuito, potente, reproducible, extenso | Regresión avanzada, series de tiempo, datos de panel |
| **Stata** | Robusto para economía y ciencias sociales | Datos de panel, econometría, modelos de efectos fijos/aleatorios |
| **Excel** | Básico, accesible | Estadística descriptiva, tablas y gráficos simples |
| **Python (pandas + statsmodels)** | Programable, escalable | Big data, aprendizaje automático, automatización |

Describe cómo se usará el software elegido para aplicar las herramientas seleccionadas.

### 6. Ejemplo aplicado
Proporciona un ejemplo breve y concreto (con datos ficticios realistas) que ilustre:
- Cómo se estructurará la base de datos (columnas y filas representativas).
- Cómo se aplicará al menos una herramienta estadística al tema del estudio.
- Cómo se interpretarían los resultados.

### 7. Justificación del procesamiento
Párrafo que explique cómo las herramientas y el software garantizan:
- Rigor estadístico para contrastar las hipótesis.
- Coherencia con el nivel de investigación y el diseño.
- Reproducibilidad y transparencia del análisis.

### 8. Conexión sistémica
Párrafo que vincule el procesamiento de datos con:
- Las variables, dimensiones e indicadores (¿qué se medirá con cada herramienta?).
- Las hipótesis (¿qué prueba estadística contrasta cada hipótesis?).
- El análisis y discusión de resultados (siguiente paso del anteproyecto).

---

## Resultado esperado

Una sección de procesamiento de datos que sea:
- **Específica:** Describe exactamente qué herramientas y software se usarán y por qué.
- **Reproducible:** Cualquier investigador puede replicar el análisis siguiendo los pasos descritos.
- **Coherente:** Las herramientas seleccionadas responden directamente a las hipótesis y objetivos.
- **Viable:** Las herramientas son apropiadas para el tamaño de muestra, el tipo de variables y los recursos disponibles.

---

## Restricciones

- No prescribas herramientas incompatibles con el tipo de variables (p. ej., media aritmética para variables nominales).
- No menciones herramientas estadísticas sin justificar su relación con las hipótesis u objetivos.
- Mantén el tono académico y formal en todo momento.
- Si falta información esencial, solicita: *"Por favor, proporcione el tipo de investigación, las variables y su escala de medición, y las hipótesis para seleccionar las herramientas estadísticas adecuadas."*

---

## Información que debe proporcionar el usuario

```
Tema: [...]
Disciplina: [...]
Título: [...]
Variable exógena y escala de medición: [...]
Variable endógena y escala de medición: [...]
Hipótesis (general y específicas): [...]
Nivel de investigación: [Descriptivo / Correlacional / Explicativo / Predictivo]
Diseño: [Transversal / Longitudinal / Panel]
Tamaño de muestra: [...]
Software de preferencia o disponibilidad: [...]
```

---

## Sugerencia de Mejora Iterativa

Al finalizar, pregunta al usuario:

> *"¿Desea ajustar la sección? Puede: (A) Cambiar el software estadístico, (B) Agregar o eliminar herramientas estadísticas, (C) Detallar la verificación de supuestos, (D) Proceder con el análisis y discusión de resultados, o (E) Otro: ___"*
