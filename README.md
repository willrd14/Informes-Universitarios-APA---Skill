# Informes Universitarios APA (6ta edición)

## Descripción general

**informes-universitarios-apa** es una skill para Claude que ayuda a crear, revisar y corregir
informes, ensayos, controles de lectura, trabajos de investigación y tesis universitarias bajo
las normas de citación y referencias de la **APA en su sexta edición**, con foco especial en la
**prevención de plagio**.

Está construida a partir de dos fuentes:

- El *Manual del modelo de documentación de la Asociación de Psicología Americana (APA) en su
  sexta edición*, del Centro de Lengua y Pensamiento Crítico de la UPAEP — cubre formato de
  página, portada, los 5 niveles de encabezado, citas directas/indirectas/parentéticas y formato
  de referencias bibliográficas, hemerográficas y electrónicas.
- El artículo académico *"El plagio y su impacto a nivel académico y profesional"* (Soto
  Rodríguez, 2012, *E-Ciencias de la Información*, Universidad de Costa Rica) — cubre los
  distintos tipos de plagio (por forma, método y propósito), sus consecuencias, y cómo evitarlos.

La skill incluye tres archivos de referencia (`formato-documento.md`,
`citas-y-referencias-apa6.md`, `prevencion-plagio.md`) que Claude consulta según lo que necesite
el trabajo en curso, sin sobrecargar el contexto con información que no aplica a la tarea.

## Formas de usarla

La skill se activa automáticamente cuando se le pide a Claude, por ejemplo:

- "Ayúdame a hacer un informe/ensayo/control de lectura para la universidad."
- "Necesito un trabajo con formato APA sexta edición."
- "Revísame las citas y referencias de este documento."
- "¿Esto que escribí cuenta como plagio? Ayúdame a parafrasear correctamente."
- "Hazme la portada bilingüe con matrícula y nombre del facilitador."
- Cualquier mención de universidades o facilitadores de curso (p. ej. UASD, UFHEC), "control de
  lectura", "referencias bibliográficas", o "portada académica".

No es necesario mencionar la palabra "APA" explícitamente — la skill igual se activa si el
contexto es un trabajo académico universitario.

Cuando el resultado final debe ser un archivo Word (.docx), esta skill trabaja en conjunto con
la skill `docx`: esta define el contenido y las reglas de formato/citación, y `docx` genera el
archivo.

## IA's compatibles con la skill

Esta skill sigue el formato estándar de **Claude Skills** (carpeta con `SKILL.md` +
`references/`) y funciona en cualquier entorno de Claude que soporte skills, incluyendo:

- Claude.ai (chat web y app móvil)
- Claude Code
- Claude Cowork
- Claude API / Claude Platform (mediante configuración de skills)

No es compatible de forma nativa con otros asistentes de IA que no usen el estándar de Claude
Skills, aunque el contenido de los archivos de referencia (Markdown plano) puede reutilizarse
manualmente como material de consulta en cualquier otra herramienta.

## Instalación

1. Descarga el archivo `informes-universitarios-apa.skill` generado.
2. Ábrelo desde la tarjeta de archivo compartida en la conversación de Claude y pulsa **Save
   skill** (o el botón equivalente para guardar/instalar la skill en tu perfil).
3. Una vez instalada, la skill se activará automáticamente cada vez que el contexto de la
   conversación coincida con trabajos académicos universitarios — no requiere configuración
   adicional.

Si prefieres instalarla manualmente (por ejemplo en Claude Code), coloca la carpeta
`informes-universitarios-apa/` con su `SKILL.md` y su subcarpeta `references/` dentro del
directorio de skills correspondiente a tu entorno.

## Créditos

- **Manual del modelo de documentación APA, sexta edición.** Centro de Lengua y Pensamiento
  Crítico, Universidad Popular Autónoma del Estado de Puebla (UPAEP). Coordinado por Silva
  Ramírez, B. y Juárez Aguilar, J. (2013).
- **Soto Rodríguez, A. (2012).** *El plagio y su impacto a nivel académico y profesional.*
  E-Ciencias de la Información, 2(1), artículo 2. Escuela de Bibliotecología y Ciencias de la
  Información, Universidad de Costa Rica. ISSN 1659-4142.
- Skill construida y adaptada por **Williams R. Villavizar Hdez.** con ayuda de Claude
  (Anthropic).
