# OctoAcme — Gestión de Riesgos y Comunicación

## Propósito
Explicar cómo identificar, gestionar y comunicar riesgos y dependencias.

## Registro de Riesgos
Mantener una tabla simple con:
- ID
- Descripción
- Impacto (Alto/Medio/Bajo)
- Probabilidad (Alta/Media/Baja)
- Responsable
- Plan de mitigación
- Estado

## Ciclo de Vida del Riesgo
- Identificar: durante la planificación y la ejecución continua (el **Líder Técnico** lidera la identificación de riesgos técnicos; **QA** identifica riesgos de calidad)
- Evaluar: estimar impacto y probabilidad
- Mitigar: reducir mediante acciones y planes de contingencia
- Monitorear: revisar en sincronizaciones semanales y actualizar estado

## Comunicación con Stakeholders
- Identificar grupos de stakeholders y sus necesidades de comunicación (p. ej., ingeniería, ventas, soporte, Stakeholders Externos)
- Proveer actualizaciones regulares (semanales o basadas en hitos) al **Stakeholder Externo** para mantener alineación con las expectativas del negocio
- Usar una única fuente de verdad (README del proyecto o documento de release) para el estado del proyecto
- El **Project Manager** coordina la comunicación de riesgos y bloqueos relevantes a los Stakeholders Externos

## Plantillas de Comunicación
Plantilla de Estado Semanal:
- Avance esta semana:
- Próximos pasos:
- Riesgos y bloqueos:
- Solicitud / Decisiones necesarias:

Comunicación de Incidentes:
- Resumen del triaje
- Acciones en curso
- Cronograma esperado
- Retrospectiva post-incidente sin culpas programada

## Rutas de Escalamiento
- Equipo → PM → Product Lead → Sponsor
- Para incidentes de seguridad, seguir el runbook de incidentes de seguridad y notificar al equipo de Seguridad de guardia
- Cuando el impacto afecte compromisos con Stakeholders Externos, el PM los notifica de inmediato y coordina una actualización de expectativas
