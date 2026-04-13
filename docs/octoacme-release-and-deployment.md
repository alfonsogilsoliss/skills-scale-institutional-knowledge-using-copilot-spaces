# OctoAcme — Guía de Release y Despliegue

## Propósito
Estandarizar cómo OctoAcme libera funcionalidades a producción para reducir el riesgo y mejorar la observabilidad.

## Tipos de Release
- Parche (Patch): hotfixes para problemas críticos en producción
- Menor (Minor): funcionalidades y mejoras incrementales
- Mayor (Major): funcionalidad significativa o cambios disruptivos

## Requisitos Previos al Release
- Todos los criterios de aceptación cumplidos y PRs integrados
- CI y escaneos de seguridad pasando (validado por el **Líder Técnico**)
- Release notes redactadas
- Plan de rollback / mitigación documentado
- Pruebas de humo preparadas y aprobadas por **QA**
- Diseñador UX/UI confirma que los flujos de usuario cumplen con los criterios de usabilidad acordados
- **Stakeholder Externo** notificado con anticipación sobre la fecha y el alcance del release

## Checklist de Despliegue
- [ ] Ventana de despliegue calendarizada (si aplica)
- [ ] Backup o snapshot realizado (si corresponde)
- [ ] Despliegue en staging y pruebas de humo ejecutadas por QA
- [ ] Despliegue a producción (pipeline automatizado preferido)
- [ ] Verificaciones post-despliegue ejecutadas
- [ ] Release anunciado a stakeholders, soporte y Stakeholders Externos

## Playbook de Rollback e Incidentes
- Si un despliegue falla o causa un problema crítico:
  - Activar respuesta a incidentes y notificar al equipo de guardia
  - Hacer rollback al último release conocido como estable si es necesario
  - El **Líder Técnico** lidera el triaje de causa raíz
  - Capturar causa raíz y elementos de acción
  - Notificar al **Stakeholder Externo** sobre el incidente y el plan de acción

## Plantilla de Release Notes
- Nombre / número del release:
- Fecha:
- Resumen:
- Cambios destacados:
- Pasos de migración (si aplica):
- Problemas conocidos:
