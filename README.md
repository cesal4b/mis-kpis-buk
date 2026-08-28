# Mis KPIs

Una herramienta de una sola página (HTML/CSS/JS, sin backend) para llevar el seguimiento personal de tus KPIs de desempeño — pensada para el modelo típico de evaluación institucional con categorías, ponderaciones y ciclos de reporte periódico.

**Pruébala:** abre `index.html` en cualquier navegador. Todo se guarda localmente en tu navegador (`localStorage`) — nada se envía a ningún servidor.

## Qué hace

- **Categorías con ponderación** (Resultados, Procesos/Gestión, Experiencia, Desarrollo) — cada una debe sumar 100% entre sus KPIs activos.
- **Tipado de KPI (A/B/C)** con guía contextual al reportar avance:
  - **A · Cumplimiento sostenido** — el resultado se debe mantener igual todo el periodo (ej. disponibilidad, puntualidad).
  - **B · Proporcional al tiempo** — el avance se acumula (ej. ejecución presupuestal).
  - **C · Portafolio / cronograma propio** — varios procesos o proyectos activos, cada uno con su propia fecha de cumplimiento.
- **Historial de avance** por fecha, con comentario y evidencia — igual que reportarías en un sistema de HR.
- **Desglose por procesos/tareas vinculadas**: para KPIs de portafolio (Tipo C), agrega las tareas o proyectos que lo componen, dale un % a cada una, y la herramienta calcula el promedio por ti — con un "techo conservador" opcional para ítems que aún no cierran (los ya cerrados/irreversibles quedan exentos).
- **Importación de plan de trabajo**: pega tu plan de acción (líneas estratégicas + acciones clave + indicadores) o fichas de KPI ya definidas (nombre, meta, categoría, peso, línea estratégica), y la herramienta detecta y propone los campos automáticamente — incluyendo un contador que te avisa si estás por importar más KPIs de los recomendables (3-4).
- **Generador de prompt para IA**: si tu plan de acción está en bruto, un botón arma un prompt listo para pegar en Claude/ChatGPT que consolida tu lista de posibles indicadores en 3-4 KPIs bien definidos, en el formato exacto que la herramienta necesita.

## Por qué

Los sistemas institucionales de KPIs (tipo BUK y similares) muestran tu avance, pero no te ayudan a *calcular* ese número cuando tu KPI en realidad es un portafolio de tareas o proyectos distintos. Esta herramienta es ese paso intermedio: documentas tus procesos, les das un % con evidencia, y llegas al número que vas a reportar con trazabilidad de cómo se calculó.

## Stack

HTML + CSS + JavaScript vanilla. Sin dependencias, sin build, sin backend. Un solo archivo.

## Licencia

MIT — úsala, cópiala, adáptala a tu propio modelo de evaluación.
