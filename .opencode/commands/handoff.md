---
description: Volcar el estado actual de la tarea a HANDOFF.md
---

Actualiza `HANDOFF.md` con el estado actual de la tarea, para que cualquier CLI (Claude Code u OpenCode) pueda retomar desde ahi.

Formato exacto del archivo:

# Estado actual
_Actualizado: <fecha y hora actual>_
## Objetivo
## Hecho
## En curso / bloqueado
## Proximo paso exacto
## Archivos tocados

Reglas:
- Maximo 40 lineas. Sobrescribe el archivo completo, no lo acumules.
- "Hecho": solo lo verificado, con la ruta concreta del archivo.
- "En curso / bloqueado": el bloqueo exacto y que se necesita para desbloquearlo.
- "Proximo paso exacto": una sola accion, lo mas concreta posible (archivo + linea).
- No copies historial viejo ni decisiones ya superadas.
- Si no hay nada que registrar, deja las secciones en "(pendiente)".